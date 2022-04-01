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



Last Updated: 2022-04-01 09:02:30 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/indonesia/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-04-01 08:59:51 </td>
   <td style="text-align:left;"> Indonesia Manufacturing Grows Modestly </td>
   <td style="text-align:left;"> The S&amp;P Global Indonesia Manufacturing PMI edged up to 51.3 in March 2022 from 51.2 a month earlier. The latest figure represented the seventh straight month of expansion, as employment grew the most in almost three years and buying activity grew further ahead of the fasting month of Ramadan and Eid-ul-Fitr celebration. Meantime, both output and new orders increased at the slowest rates since last August with foreign demand  slowing amid reports of shipping constraints. At the same time, backlogs of work fell, linked to slower increase in new orders. On the price front, both input cost and output prices continued to rise, and at faster rates. Finally, sentiment was at eight-month high,  as the latest COVID-19 wave receded. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-04-01 08:57:00 </td>
   <td style="text-align:left;"> US Futures Edge Up Ahead of Key Jobs Report </td>
   <td style="text-align:left;"> US equity futures edged higher in Asian trade on Friday after Wall Street closed out the first negative quarter in two years, as investors looked ahead to a key monthly jobs report to guide the outlook for monetary policy. Futures contracts tied to the three major indexes each gained about 0.2%. Stocks saw an accelerated selling into the close on Thursday, with the Dow falling 1.56%, the S&amp;P 500 losing 1.57% and the Nasdaq Composite declining 1.54%. All three major averages posted their worst quarter since March 2020, marked by surging inflation and rising interest rates, exacerbated by the war in Ukraine. The Dow and S&amp;P 500 dropped 4.6% and 4.9% respectively during the period, while the Nasdaq slumped 9%. Investors also remained cautious after Treasury yields inverted this week for the first time in years, signaling a possible recession. Meanwhile, a strong jobs report on Friday could bolster the Fed’s aggressive tightening plans to control inflation without slowing the economy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-04-01 08:50:14 </td>
   <td style="text-align:left;"> Japan Manufacturing PMI Revised Higher </td>
   <td style="text-align:left;"> The au Jibun Bank Japan Manufacturing PMI was revised higher to 54.1 in March 2022, compared to the preliminary estimate of 53.2, and a final 52.7 a month earlier, which was the weakest growth in five months, pointing to the 14th straight month of expansion in the sector and one that was solid overall, amid declining Covid-19 infections. Output returned to expansion territory, albeit only marginally, while new order growth quickened, with a solid reduction in new exports sales, which fell at the sharpest pace since July 2020, due to re-imposing lockdown restrictions in parts of China dan the Russia-Ukraine war. On the price side, input price inflation accelerated to the fastest since August 2008, due to higher raw material prices. As a result, output price inflation accelerated to the third-fastest in the survey history.  Finally, business confidence weakened to a seven-month low. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ireland/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-04-01 08:28:47 </td>
   <td style="text-align:left;"> Ireland Manufacturing Growth Accelerates in March </td>
   <td style="text-align:left;"> The AIB Ireland Manufacturing PMI increased to 59.4 in March 2022 from 57.8 in the previous month, which was the weakest expansion in 11 months, was mainly driven by the new orders, output and employment. At the same time, input and output prices increased at the record rates, with costs boosted by raw materials, energy, fuel, and transport charges and general market volatility and uncertainty, due to the war in Ukraine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/exports-yoy </td>
   <td style="text-align:left;"> 2022-04-01 08:14:00 </td>
   <td style="text-align:left;"> South Korea Exports Stay Robust </td>
   <td style="text-align:left;"> Exports from South Korea grew by 18.2% yoy to USD 63.48 billion in March 2022, above market forecasts of 17.5% and after a 20.6% rise a month earlier. This marked the 16th straight month of double-digit growth despite escalating geopolitical tensions in eastern Europe and supply bottlenecks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/imports-yoy </td>
   <td style="text-align:left;"> 2022-04-01 08:13:00 </td>
   <td style="text-align:left;"> South Korea Imports Extend Double Digit Growth </td>
   <td style="text-align:left;"> Imports to South Korea expanded 27.9% yoy in March 2022, compared with market forecasts of 27.8% and after a 25.2% gain in the prior month. The latest reading marked the 14th straight month of double digit growth in arrivals, underscoring strong domestic demand following an acceleration in COVID-19 vaccinations and despite mounting geopolitical risks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/business-confidence </td>
   <td style="text-align:left;"> 2022-04-01 08:07:00 </td>
   <td style="text-align:left;"> Japan Q1 Business Mood Eases </td>
   <td style="text-align:left;"> The Bank of Japan's index for big manufacturers' sentiment fell to 14 in Q1 2022 from 18 in Q4 2021 and compared with market consensus of 12, reflecting the impact of the Ukraine crisis and commodity inflation.  Mood softened among firms producing lumber &amp; wood products (20 vs 25 in Q4), pulp &amp; paper (-3 vs 11), chemicals (28 vs 31), ceramics, stone (0 vs 9), food &amp; beverages (-5 vs 2), processed metals (3 vs 6), business oriented machinery (22 vs 25), electrical machinery (24 vs 29), basic materials (16 vs 18), motor vehicles (-15 vs -8), and processing (12 vs 16). At the same time confidence was unchanged for firms producing petroleum &amp; coal (at 27) while strengthened among non-ferrous metals (21 vs 15), and production machinery (43 vs 40). Meantime, big firms planned to  rise capital spending by 2.2%, much softer than 9.3% previously. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/balance-of-trade </td>
   <td style="text-align:left;"> 2022-04-01 08:05:56 </td>
   <td style="text-align:left;"> South Korea Trade Balance Swings to Deficit </td>
   <td style="text-align:left;"> South Korea posted a trade deficit of USD 0.14 billion in March 2022, swinging from a surplus of USD 3.96 billion in the same month a year earlier, as imports rose faster than exports, a preliminary reading showed. Arrivals jumped by 27.9 percent year-on-year while shipments grew at a softer 18.2 percent. In 2021, the country recorded a trade surplus of USD 29.49 billion, down sharply from USD 44.76 billion in 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60928727?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-01 07:07:16 </td>
   <td style="text-align:left;"> Five reasons why prices and bills are going up </td>
   <td style="text-align:left;"> A cost of living crunch is hitting millions of people across the UK, as soaring energy bills start to bite into family finances and prices rise in the shops.                                                                                                                                                                                , Much has been said about the squeeze on our budgets, and relatively few people will emerge from it with their personal finances unscathed.                                                                                                                                                                                                   , April is a key month because it is when many of the most significant changes and bill rises take effect.                                                                                                                                                                                                                                     , Inflation is the rate at which prices rise. If a bottle of milk costs £1 and that rises by 5p, then milk inflation is 5%. The optimum level, and the Bank of England's target, is a 2% inflation rate.                                                                                                                                       , This first chart shows how inflation - charting the rising cost of living - is at its highest rate for about 30 years. Official figures reveal these price rises are widespread among the various things we buy.                                                                                                                             , They are about to accelerate. The government's official forecaster, the Office for Budget Responsibility (OBR), says the rate will peak at nearly 9% later in the year, before slowing. That means prices will continue to go up, but eventually not at such a rapid rate.                                                                   , There is little sign of income keeping pace with pay rises and benefit increases (although minimum pay - through the National Living Wage - is going up by 6.6%), so our "real" income and standard of living will fall.                                                                                                                     , The biggest impact this year is the sharp increase in the cost of energy.                                                                                                                                                                                                                                                                    , Businesses are passing on some of these costs to consumers in higher prices. Households are protected from the fluctuations owing to the domestic energy price cap.                                                                                                                                                                          , Yet, the chart shows how the cap, and therefore the typical annual household gas and electricity bill is rising by about £700. The OBR is predicting a further rise of more than £800 a year in October.                                                                                                                                     , The chart also shows how there is little bill-payers can do about it. They used to be able to shop around for a cheaper tariff but, at present, no deals are cheaper than the default price cap. The government is giving some support with a £150 council tax rebate in April, and a £200 grant in October, which will need to be paid back., As well as the soaring cost of heating and powering the home, filling a car with petrol or diesel is getting more expensive too.                                                                                                                                                                                                             , These prices can be quite volatile, week to week, unlike domestic gas and electricity.                                                                                                                                                                                                                                                       , The graphic shows the cost of filling a tank for different types of vehicles, according to the RAC motoring group. Even if you do not run a car, there is concern that pricier fuel will eventually feed through to more expensive bus and coach tickets.                                                                                    , The most expensive monthly bill for millions of people is their rent, or their mortgage repayment.                                                                                                                                                                                                                                           , Three-quarters of mortgage borrowers in the UK are on fixed-rate deals, so only see a change in their repayments when their current term ends.                                                                                                                                                                                               , Another two million homeowners are on deals where the interest rate varies - known as tracker or standard variable rate mortgages. The Bank of England has raised the base interest rate three times in four months since December.                                                                                                          , The chart shows how this has increased the monthly bill for these variable mortgage customers for the first time in a long time.                                                                                                                                                                                                             , Many workers will be paying more tax from now, most significantly through increased National Insurance payments.                                                                                                                                                                                                                             , In July, people will be able to earn more before they start to pay this tax, following a change announced by Chancellor Rishi Sunak in his recent Spring Statement.                                                                                                                                                                          , Combining those two measures means that in the next 12 months, anyone earning less than about £34,000 will pay less National Insurance than they did last year. Anybody earning more than that will pay more, as the final chart shows.                                                                                                      , Kevin Parle has been on the run since 2004 - will he ever be brought to justice?                                                                                                                                                                                                                                                             , Louis Theroux on storytelling and the culture wars                                                                                                                                                                                                                                                                                           , Russell Kane tackles the former president's legacy                                                                                                                                                                                                                                                                                           , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60914889?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-01 07:05:40 </td>
   <td style="text-align:left;"> Energy price cap: Expert money hacks to tackle rising bills </td>
   <td style="text-align:left;"> Prices are rising at their fastest rate for 30 years and millions of households are facing the prospect of a soaring energy bill.                                                                                                                                    , We asked four experts for their top tips on what people can do to protect their finances and soften the blow of rising bills.                                                                                                                                        , Bola Sol is a finance coach and author of How to Save It.                                                                                                                                                                                                            , She says it's time to do a deep dive on your budget and find out exactly where your money is going.                                                                                                                                                                  , "Start by assessing if there is room for negotiation in any of your fixed expenses," she says. "Is there a better and cheaper provider?"                                                                                                                             , When it comes to variable monthly outgoings decide what should stay and what should go, she says.                                                                                                                                                                    , "Every budget needs a miscellaneous fund for those expenses you did not see coming," she says. "Have one in for each month."                                                                                                                                         , "Look at your calendar at who is celebrating a birthday, baby shower, wedding or occasion this month," she says.                                                                                                                                                     , "Ask yourself, if you go, how much will it cost you and is it worth going given the current climate?"                                                                                                                                                                , She suggests joining supermarket rewards schemes and family deals for streaming services as well as comparing prices online and searching for discount codes.                                                                                                        , Myron Jobson is the senior personal finance analyst at the investment platform, Interactive Investor.                                                                                                                                                                , He says making small cuts in lots of places can be a less painful way to improve your finances.                                                                                                                                                                      , "While making huge cuts to a few areas of spending could significantly ease the cost of living squeeze on your finances, they could also have an unacceptable knock-on effect on your quality of life and take a heavy toll on mental and emotional health," he says., But small changes can add up, he says.                                                                                                                                                                                                                               , "For example, you do not have to completely forgo your daily coffee purchase, but you can cut back on how often you buy them."                                                                                                                                       , After over two years of Covid restrictions, many of us are keen to spend money on getting out more, he says.                                                                                                                                                         , "Halving the number of jaunts averaging £50 a week in a month, for example, would give you an extra £100 a month which could go towards footing the extra £57.75 a month increase to the average energy bill," he says.                                              , Kayley Hignell is the head of families, welfare and work at Citizens Advice.                                                                                                                                                                                         , She says if you are facing tough times it is important to make sure you are getting all the support you are entitled to.                                                                                                                                             , You can use the Citizens Advice benefits calculator to work out if here's any help you could be claiming, she says.                                                                                                                                                  , "Important benefits to consider might be Personal Independent Payment, if you need extra help for an illness or disability, or universal credit if you are on a low income or unemployed," she says.                                                                 , "Pension Credit, which can top up your income in retirement, is something many people do not know they are entitled to.                                                                                                                                              , "There are also schemes like local council tax reductions and the new Household Support Fund where you will need to speak to your local council about what might be on offer."                                                                                       , Low-income families might also be able to get help with the costs of sending children to school, including school meals, transport and uniform through your local education authority, she says.                                                                     , Helen Undy is chief executive of the Money and Mental Health Policy Institute.                                                                                                                                                                                       , She says mental health and finances can be intrinsically linked so money troubles can have a serious impact on our mental wellbeing, and vice versa.                                                                                                                 , "If you are feeling stressed or worried about your financial situation, it is important to know that you are not alone and there is help out there," she says.                                                                                                       , "There is no debt problem that is not fixable with the right support. If you're struggling to keep up with bills, there are lots of free debt advice organisations that can help," she says.                                                                         , "Similarly, if your finances are starting to take a toll on your mental health, it's important to seek help."                                                                                                                                                        , She suggests contacting your GP or speaking to a charity like the Samaritans.                                                                                                                                                                                        , "In recent years lots of banks and energy companies have introduced tools to help customers manage their finances so it is worth asking your providers what they can offer," she says.                                                                               , These include sending copies of bills and other letters to a nominated person of your choice, so that they can help you make decisions.                                                                                                                              , Some banks now offer a carer's card, which is a debit card for a loved one to use on your behalf for limited purposes such as grocery shopping, she says.                                                                                                            , Kevin Parle has been on the run since 2004 - will he ever be brought to justice?                                                                                                                                                                                     , Louis Theroux on storytelling and the culture wars                                                                                                                                                                                                                   , Russell Kane tackles the former president's legacy                                                                                                                                                                                                                   , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60943192?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-01 07:04:49 </td>
   <td style="text-align:left;"> Energy price cap: Bill shock for millions as rises hit </td>
   <td style="text-align:left;"> Millions of people will now feel the impact of an unprecedented £700-a-year rise in energy costs - at the same time as a host of bill hikes take effect.                                                                                                                                                                       , The 54% rise in the energy price cap means a household using a typical amount of gas and electricity will now pay £1,971 per year.                                                                                                                                                                                             , A further rise pushing the annual bill up to £2,600 should be expected in October, one analyst has told the BBC.                                                                                                                                                                                                               , Council tax, water bills and car tax are also going up for some on 1 April.                                                                                                                                                                                                                                                    , Minimum wage rates are rising which, along with some financial support from the government, is partially softening the blow.                                                                                                                                                                                                   , The £693 a year rise in a typical energy bill will affect 18 million households, with 4.5 million customers on prepayment meters facing an even bigger increase of £708 a year.                                                                                                                                                , Among them is Winston Carrington, a grandfather in his 70s, who said he was growing vegetables in the garden of his Manchester home to help ease the impact of the rising cost of living.                                                                                                                                      , "I'm going to grow, and I'm going to fill my freezer this year with my own produce. I'm going to have to," said Mr Carrington, who uses a prepayment meter.                                                                                                                                                                    , "I can't go away this year again, not because of Covid or anything. I just can't afford to go away. The state pension that we're getting at the moment does not cover what I need."                                                                                                                                            , Prices in general are rising at their fastest rate for 30 years, but the sudden increase in the cost of energy is the most significant for individuals. A number of suppliers' websites have struggled to cope as customers provided meter readings to ensure they paid no more than was absolutely required.                  , Dame Clare Moriarty, chief executive of Citizens Advice, said: "The energy price cap rise will be potentially ruinous for millions of people across the country. It comes just as another new, bleak record is set for people needing crisis support from us."                                                                 , The governor of the Bank of England, Andrew Bailey, said the country is facing the biggest single shock from energy prices since the 1970s. It is the largest increase, by far, in the energy regulator Ofgem's price cap, since it was introduced.                                                                            , The cap, set every six months for England. Wales and Scotland, is designed to protect domestic customers from the volatility of wholesale energy prices.                                                                                                                                                                       , However, official forecasters and analysts have warned people to be braced for another huge rise in energy bills when the next cap takes effect in October. Wholesale prices have been affected by the war in Ukraine and ongoing pressure on suppliers.                                                                       , This could add another £629 to a typical bill in October, according to the most up-to-date prediction, provided to the BBC from leading energy consultancy firm Cornwall Insight.                                                                                                                                              , If this proved to be accurate, then the average bill next winter would be double that of the winter just gone. A typical bill is expected to fall back to the current level in summer 2023, although longer-term forecasts are tricky.                                                                                         , Chris O'Shea, chief executive of Centrica, which owns the UK's largest supplier British Gas, said his businesses was supporting struggling customers and was giving grants to those most in need.                                                                                                                              , "We would love to do more. The reality is that for a retail energy company, the market has gone through quite a change, and profits have reduced quite substantially," he told the BBC's Big Green Money Show.                                                                                                                 , However, he accepted that profits had risen sharply for the heavily taxed exploration arm of the business.                                                                                                                                                                                                                     , "If you are feeling stressed or worried about your financial situation, it is important to know that you are not alone and there is help out there," said Helen Undy, chief executive of the Money and Mental Health Policy Institute.                                                                                         , "There is no debt problem that is not fixable with the right support. If you're struggling to keep up with bills, there are lots of free debt advice organisations that can help," she said.                                                                                                                                   , "Similarly, if your finances are starting to take a toll on your mental health, it's important to seek help."                                                                                                                                                                                                                  , Council taxes and water bills are also going up for many people, added to the rising cost of food and household items.                                                                                                                                                                                                         , One estimate suggests that a typical consumer is now facing a £73 a month increase in bills, of which about £58 is from rising energy costs.                                                                                                                                                                                   , "The added cost pressures set to come into play in April threatens to obliterate even the most finely tuned budgets." said Myron Jobson, senior personal finance analyst at Interactive Investor.                                                                                                                              , The Office for National Statistics said that low earners, renters, parents, people with disabilities, unemployed people and divorcees were least able to afford a bill shock.                                                                                                                                                  , Even before the latest increases, charity Citizens Advice said that in March, it referred 24,752 people to food banks or to other charitable support, up by 44% compared to the same month last year.                                                                                                                          , The government has said it was taking "decisive action" to help people with the cost of living, including a £200 reduction to energy bills in October - which needs to be paid back in instalments, and a £150 reduction in council tax bills for 80% of billpayers.                                                           , Chancellor Rishi Sunak told the BBC's Newscast: "I'm confident in what we've done. I know it's tough for people. We're facing a very difficult situation with the price of things going up and I want to do what we can to ameliorate some of that, but I'm also honest with people that we can't ameliorate all of it, sadly.", Some 2.5 million UK workers have received a pay rise, with new National Minimum Wage and National Living Wage rates. The latter, for workers aged 23 and over, has increased by 6.6% to £9.50 an hour.                                                                                                                         , Kevin Parle has been on the run since 2004 - will he ever be brought to justice?                                                                                                                                                                                                                                               , Louis Theroux on storytelling and the culture wars                                                                                                                                                                                                                                                                             , Russell Kane tackles the former president's legacy                                                                                                                                                                                                                                                                             , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/31/health/first-challenge-study-covid-19/index.html </td>
   <td style="text-align:left;"> 2022-04-01 06:47:23 </td>
   <td style="text-align:left;"> First human challenge study of Covid-19 yields valuable insights about how we get sick - CNN </td>
   <td style="text-align:left;"> (CNN)It takes just a tiny virus-laden droplet -- about the width of a human blood cell -- to infect someone with Covid-19.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , That's just one of the findings from research that deliberately infected healthy volunteers with the SARS-CoV-2 virus. The findings were published Thursday in the journal Nature Medicine.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Challenge studies can be controversial because they involve intentionally giving someone a virus or other pathogen in order to study its effects on the human body.  Even with safeguards in place, there's an element of risk, particularly when studying a new virus.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , But they are also hugely valuable for understanding the course of an infection.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , "Really, there's no other type of study where you can do that, because normally, patients only come to your attention if they have developed symptoms, and so you miss all of those preceding days when the infection is brewing," said lead study author Dr. Christopher Chiu, an infectious disease physician and immunologist at Imperial College London.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Volunteers were carefully screened                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , The study began in March 2021. The 36 volunteers were between the ages of 18 and 30.  They were allowed to participate only if they didn't have any risk factors for severe Covid-19, such as being overweight, having reduced kidney or liver function, or having any heart, lung or blood problems. They also signed an extensive informed consent form to participate.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , To further minimize the risks, researchers conducted the study in phases.  The first 10 infected volunteers got the antiviral drug remdesivir to reduce their chances of progressing to severe disease.  Researchers also had monoclonal antibodies at the ready in case anyone took a turn for the worse.  Ultimately, the remdesivir proved unnecessary, and researchers never had to give anyone antibodies.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , The volunteers got a tiny drop of fluid containing the originally detected strain of the virus through a long, thin tube inserted into their nose.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , They were medically monitored 24 hours a day and stayed for two weeks in rooms at London's Royal Free Hospital that had special air flow to keep the virus from escaping.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Half were infected                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , A total of 18 participants became infected, two of whom never developed symptoms.  Among the people who got sick, their illnesses were mild. They had stuffy noses, congestion, sneezing and sore throats.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Most of the study participants who caught Covid-19 -- 83% -- lost their sense of smell, at least to a degree.  Nine couldn't smell at all.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , This now-well-known symptom got better for most people, but six months after the study ended, there's one person whose sense of smell isn't back to normal but is improving.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , That's a concern because another recent study found that this loss of smell was tied to changes in the brain.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Chiu says the researchers gave the participants cognitive tests to check their short-term memory and reaction time. They're still looking at that data, but he thinks those tests "will really be informative."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , None of the study volunteers developed lung involvement in their infections.  Chiu thinks this is because they were young and healthy and inoculated with tiny amounts of virus.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Beyond the loss of smell, no other symptoms persisted.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , A closer look at infection as it moves through the body                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Under these carefully controlled conditions, researchers were able to learn a lot about the virus and how it moves through the body:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Tiny amounts of virus, about 10 microns -- the amount in a single droplet someone sneezes or coughs -- can make someone sick.Covid-19 has a very short incubation period.  It takes about two days after infection for a person to start shedding virus.People shed high amounts of virus before they show symptoms (confirming something epidemiologists had figured out).On average, the young, healthy study volunteers shed virus for 6½ days, but some shed virus for 12 days.Infected people can shed high levels of virus without any symptoms.  About 40 hours after the virus was introduced, it could be detected in the back of the throat.It took about 58 hours for virus to show up on swabs from the nose, where it eventually grew to much higher levels.Lateral flow tests, the rapid at-home kind, work really well for detecting when a person is contagious.  The study found that these kinds of tests could diagnose infection before 70% to 80% of viable virus had been generated., Chiu says his study emphasizes a lot of what we already know about Covid-19 infections, not least of which is why it's so important to cover both your mouth and nose when sick to help protect others.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , More challenge studies planned                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , This challenge study was so successful that Chiu plans to do it again, this time with vaccinated people infected with the Delta variant to study their immune response.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , He says his team also plans to continue studying the people who didn't get sick.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , "That's what's really interesting," he said.  About half of the study participants never got sick and never developed antibodies, despite getting exactly the same dose of the virus.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Everyone was screened for antibodies to closely related viruses, like the original SARS virus.  So it wasn't cross-protection that kept them safe; it was something else.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , "There are lots of other things that help protect us," Chiu said. "There are barriers in the nose. There are different kinds of proteins and things which are very ancient, primordial, protective systems, and they are likely to have been contributing to them not being infected, and we're really interested in trying to understand what those are."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Understanding what other factors may be at play could help us provide more generalized protection to people in case of a future pandemic.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Dr. Kathryn Edwards, a pediatric infectious disease specialist at Vanderbilt University who wrote an editorial published alongside the study, said the research offers important information about infection and contagion with the SARS-CoV-2 virus.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Blood and tissue samples collected for the study will continue to be analyzed for years to come, she said. "I think those are all in the freezer, so to speak, and are being dissected.  So I think that should be very powerful."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , In the end, she thinks the study has put many of the fears about human challenge studies to rest and paved the way for others.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , "We won't be doing challenge studies in babies, and we won't be doing it in, you know, 75-year-old people with chronic lung disease," she said.  But in young, healthy people, "I think these are studies that will be helpful."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-04-01 06:39:00 </td>
   <td style="text-align:left;"> Australia Manufacturing PMI highest in 8 Months: Ai Group </td>
   <td style="text-align:left;"> Manufacturing PMI in Australia increased to 55.70 points in March from 53.20 points in February of 2022.It was the highest reading since July of 2021. Five of the six manufacturing sectors reported positive trading conditions, with buoyant conditions reported by manufacturers in the machinery &amp; equipment, building materials, and TCF, paper &amp; printing products sectors. On the other hand, the large food &amp; beverage sector remained in contraction in March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/jamaica/gdp-growth-annual </td>
   <td style="text-align:left;"> 2022-04-01 06:37:05 </td>
   <td style="text-align:left;"> Jamaica GDP Growth Advances to 6.7% in Q4 </td>
   <td style="text-align:left;"> The economy of Jamaica expanded 6.7 percent over a year in the fourth quarter of 2021, accelerating from an upwardly revised 5.9 percent growth in the previous quarter. Output grew at at a faster pace mainly for agriculture, forestry and fishing (13.8 percent vs 7.3 percent in Q3), electricity and water supply (5.8 percent vs 0.6 percent), construction (5.9 percent vs 4.4 percent) and wholesale and retail trade (10.6 percent vs 4.4 percent). Meanwhile, output declined faster for mining and quarrying (-60.5 percent vs -29.1 percent). On a seasonally adjusted quarterly basis, the economy advanced by 1.4 percent, compared to an upwardly revised 0.8 percent rise in the previous quarter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60945248?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-01 06:20:39 </td>
   <td style="text-align:left;"> Russia threatens to stop supplying gas if not paid in roubles </td>
   <td style="text-align:left;"> Russia has told "unfriendly" foreign countries they must start paying for gas in roubles or it will cut supplies.                                                                                                                                                                                                                                                                      , Vladimir Putin has signed a decree stating buyers "must open rouble accounts in Russian banks" from Friday.                                                                                                                                                                                                                                                                            , "Nobody sells us anything for free, and we are not going to do charity either - that is, existing contracts will be stopped," the Russian president said.                                                                                                                                                                                                                              , Mr Putin's demand is being seen as an attempt to boost the rouble, which has been hit by Western sanctions.                                                                                                                                                                                                                                                                            , His decree means foreign buyers of Russian gas would have to open an account at Russia's Gazprombank and transfer euros or US dollars into it.                                                                                                                                                                                                                                         , Gazprombank would then convert this into roubles which will then be used to make the payment for gas.                                                                                                                                                                                                                                                                                  , Though the order comes into effect for gas exported from Friday onwards, the payments for that gas will not be paid by European buyers until mid-May, Dr Jack Sharples, a research fellow at the Oxford Institute for Energy Studies told the BBC.                                                                                                                                     , That suggests there may not be an immediate threat to supplies.                                                                                                                                                                                                                                                                                                                        , Mr Putin said the switch to roubles was meant to strengthen Russia's sovereignty, and it would stick to its obligations on all contracts, if Western nations obliged.                                                                                                                                                                                                                  , Germany said the change announced by Mr Putin amounted to "blackmail".                                                                                                                                                                                                                                                                                                                 , Since Russia invaded Ukraine, Western nations have issued economic and trading sanctions on Russia, but the European Union has not placed bans on oil or gas, unlike the US and Canada, as its member nations rely heavily on it.                                                                                                                                                      , The EU gets about 40% of its gas and 30% of its oil from Russia, and has no easy substitutes if supplies are disrupted. Meanwhile, Russia currently gets €400m (£340m) per day from gas sales to the bloc and it has no way of rerouting this supply to other markets.                                                                                                                 , For the Kremlin this is designed to suggest a dramatic escalation in the economic battle between the West and Russia over the invasion of Ukraine.                                                                                                                                                                                                                                     , Vladimir Putin has outlined a pathway for the cutting of gas supplies to Europe if Western customers refuse to pay for supplies in the Russian currency the rouble.                                                                                                                                                                                                                    , However, the market reaction suggests the details of the mechanism mean that, in practice, European customers will just have to change their currency dealers to Gazprombank. That bank has already been left unsanctioned, for the purpose of continuity of energy trade.                                                                                                             , As a result, gas prices remain very high, but did not today shoot into the stratosphere. There should be a workaround.                                                                                                                                                                                                                                                                 , As one leading analyst told me, this solution has "saved face" for Putin, who can sound tough on domestic TV. Ultimately, as Russian officials have repeatedly said for decades, Russian supply of energy to the West continued uninterrupted even during the height of the Cold War.                                                                                                  , Ultimately, Russia still needs the money for the gas, and still wants to leave the possibility of a market for its main export once a peace deal is signed. However, it is also true to say that the threat of a cut-off has escalated. EU nations have prepared emergency measures to manage demand, and would be more willing to face that now during spring and summer than winter. , The net effect of the mechanism announced is to limit the ability of the West to freeze the revenues they pay to Gazprom, which Putin described as receiving the gas for free.                                                                                                                                                                                                         , Some Ukrainian officials have suggested such an approach. Oil and gas dollars and euros continue to help the Kremlin resist an otherwise tough set of financial sanctions.                                                                                                                                                                                                             , Analysts said Russia halting gas flows to EU member countries to "force the issue" would mark a "major escalation not even performed at the height of the Cold War".                                                                                                                                                                                                                   , "It would mark another major financial blow to Russia's coffers," the analysts at Fitch Solutions added.                                                                                                                                                                                                                                                                               , It is also unclear whether Russia's new payment mechanism for gas would fully ban payments in euros.                                                                                                                                                                                                                                                                                   , Western companies and governments have rejected Russia's demands to pay for gas in roubles as a breach of existing contracts, which are set in euros or US dollars.                                                                                                                                                                                                                    , German Chancellor Olaf Scholz said German companies would continue to pay for Russian gas using euros as stipulated in contracts.                                                                                                                                                                                                                                                      , Nathan Piper, head of oil and gas research at Investec, told the BBC the move by Mr Putin was an attempt to put economic pressure "back on Europe" and that more foreign exchange demand for roubles would likely push up the value of the currency.                                                                                                                                   , "However, long term Russia needs to remain a reliable supplier of gas so it is unclear if they would actually restrict gas supply," he added.                                                                                                                                                                                                                                          , "That said, even the risk of it is keeping UK/European gas prices at near record highs and six times the 10-year average. This is translating to steep rises in consumers' energy bills."                                                                                                                                                                                              , Dr Sharples of the Oxford Institute for Energy Studies, said the two sides could adapt and continue their trade uninterrupted, or one or both parties could claim breach of contract and escalate the situation.                                                                                                                                                                       , "One would hope that even if the situation escalated to a point where one or both parties call for arbitration, that the gas would continue to flow. However, a stoppage cannot be ruled out," he said.                                                                                                                                                                                , Germany, which gets about half its gas and a third of its oil from Russia, has urged its citizens and companies to reduce consumption in anticipation of possible shortages. Austria, which imports about 40% of its gas from Russia, is tightening its monitoring of the market.                                                                                                      , Under an existing gas emergency plan, the "early warning phase", which both Germany and Austria have begun, is the first of three steps designed to prepare the country for a potential supply shortage. In its final stage, the governments would bring in gas rationing.                                                                                                             , Elsewhere, Bulgaria, which gets 90% of its gas via imports from Russian company Gazprom, has opened a tender for underground drilling as part of plans to almost double the country's gas storage capacity and prepare for any supply disruptions.                                                                                                                                     , While the UK would not be directly impacted by supply disruption, as it imports less than 5% of its gas from Russia, it would be affected by prices rising in the global markets as demand in Europe increases.                                                                                                                                                                        , The UK government said it was not planning to pay for Russian gas in roubles.                                                                                                                                                                                                                                                                                                          , Kevin Parle has been on the run since 2004 - will he ever be brought to justice?                                                                                                                                                                                                                                                                                                       , Louis Theroux on storytelling and the culture wars                                                                                                                                                                                                                                                                                                                                     , Russell Kane tackles the former president's legacy                                                                                                                                                                                                                                                                                                                                     , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/industrial-sentiment </td>
   <td style="text-align:left;"> 2022-04-01 06:15:00 </td>
   <td style="text-align:left;"> Australia Markit PMI Revised Higher </td>
   <td style="text-align:left;"> The IHS Markit Australia Manufacturing PMI was revised higher to 57.7 in March of 2022 from a preliminary estimate of 57.3. Manufacturing output growth continued, supported by higher demand. However, further output expansion was constrained by issues of manpower and material shortages, in addition to flooding and COVID-19 disruptions. Hiring and purchasing activity likewise rose. That said, issues of supply constraints and price pressures mounted for Australian manufacturers, which spurred further safety stock building. On the price front, both input cost and output prices rose with the rate of output price inflation accelerating to a survey record. Overall business confidence remained positive in March, though the level of business confidence dropped to an eight-month low on the back of concerns over rising business costs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/31/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-04-01 06:03:56 </td>
   <td style="text-align:left;"> Stock futures bounce as investors assess start of new quarter, bond market recession indicator </td>
   <td style="text-align:left;"> , Stock futures rose early Thursday as investors assessed a new quarter of trading and a troublesome bond market recession indicator.                                                                                                                                                                                                                                                                                                                   , Investors were also awaiting the official jobs report for March, which the Labor Department will release at 8:30 a.m. ET on Friday.                                                                                                                                                                                                                                                                                                                   , Dow futures gained 90 points, or 0.3%. S&amp;P 500 futures added 0.2% and Nasdaq 100 futures rose 0.3% to kick off the first trading session of the second quarter.                                                                                                                                                                                                                                                                                       , The Dow Jones Industrial Average slumped on Thursday to close out the first negative quarter for stocks in two years, with losses accelerating in the final hour of trading. The Dow dropped 550.46 points, or 1.56%, to 34,678.35. The S&amp;P 500 slid 1.57% to 4,530.41, and the Nasdaq Composite was down 1.54% to 14,220.52.                                                                                                                         , All three major averages posted their worst quarter since March 2020. The Dow and S&amp;P 500 declined 4.6% and 4.9% respectively during the period, and the Nasdaq dropped more than 9%. Stocks did stage a late-quarter comeback in March however after sharp declines from rising interest rates and inflation marked the first part of the year.                                                                                                      , Stocks for now shook off a recession signal from the bond market that was triggered after the closing bell Thursday. The 2-year and 10-year Treasury yields inverted for the first time since 2019. For some investors, it's a signal that the economy is headed for a possible recession, though the inverted yield curve does not predict exactly when it will happen and history shows it could be more than a year away or longer.                , "I think everybody needs to acknowledge the fact that we are obviously going to be moving into a slower economic environment," Shannon Saccocia, chief investment officer at Boston Private Wealth, told CNBC's "Closing Bell."                                                                                                                                                                                                                       , "You need to get earnings growth from somewhere, and if it's not going to be a secular tailwind, like fiscal spend and monetary policy looseness, then you have to look for growth elsewhere. I think we're going to see some real nuance in trading over the course of the next three months or so as people look for that growth against this more challenging economic backdrop."                                                                  , A strong jobs report Friday could give the Fed more confidence to keep its aggressive rate-hiking plan in place this year to stifle inflation without fear of slowing the economy too much. Economists expect that about 490,000 jobs were added in March, according to the consensus estimate from Dow Jones, following a 678,000 payrolls addition in February. The unemployment rate is expected to fall to 3.7% from 3.8%, according to Dow Jones., GameStop rallied more than 10% in extended trading after the video game retailer and meme stock announced its intentions for a stock split.                                                                                                                                                                                                                                                                                                           , Energy prices declined on Thursday after the White House said it will release an unprecedented amount of oil from the Strategic Petroleum Reserve. Up to 1 million barrels of oil per day will be released for the next six months.                                                                                                                                                                                                                   , Other key indicators to watch out for include the ISM manufacturing index and the construction spending report, both of which will be released at 10 a.m. ET on Friday.                                                                                                                                                                                                                                                                               , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                      , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                      , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                    , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/ethanol </td>
   <td style="text-align:left;"> 2022-04-01 05:48:21 </td>
   <td style="text-align:left;"> Ethanol Hits 4-week Low </td>
   <td style="text-align:left;"> Ethanol decreased to a 4-week low of 2.4125 USD/Gal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/31/technology/amazon-union-election-alabama.html </td>
   <td style="text-align:left;"> 2022-04-01 05:23:36 </td>
   <td style="text-align:left;"> Amazon Union Vote in Alabama Favors Opponents for Now - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , The count was much closer than another unionization vote taken at the facility last year.                                                                                                                                                                                                                                                                                                                                                                                                                                                              , By Noam Scheiber                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Union supporters are narrowly trailing opponents in a union election at an Amazon warehouse in Alabama, the National Labor Relations Board said on Thursday. But the count was far closer than a vote at the same warehouse last year, when workers rejected the union by a more than 2-to-1 ratio.                                                                                                                                                                                                                                                    , The union had 875 yes votes versus 993 no votes, but the more than 400 challenged ballots are sufficient to potentially affect the outcome. The challenges will be resolved at a labor board hearing in the coming weeks.                                                                                                                                                                                                                                                                                                                              , Overall, roughly 2,300 ballots were cast in the election in Bessemer, Ala., out of more than 6,100 eligible employees.                                                                                                                                                                                                                                                                                                                                                                                                                                 , The labor board mandated the revote, which was conducted by mail from early February to late March, after concluding that Amazon violated the so-called laboratory conditions that are supposed to prevail during a union election.                                                                                                                                                                                                                                                                                                                    , “Regardless of the final outcome, workers here have shown what is possible,” said Stuart Appelbaum, president of the Retail, Wholesale and Department Store Union, which sought to organize the workers. “They have helped ignite a movement.”                                                                                                                                                                                                                                                                                                         , Speaking in a videoconference with reporters after the vote count, Mr. Appelbaum said the organizing in Bessemer had helped spark union campaigns at other companies, like REI and Starbucks, and in other parts of the country.                                                                                                                                                                                                                                                                                                                       , Amazon did not respond to a request for comment.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , The labor board is also counting votes in another high-profile election, at an Amazon warehouse on Staten Island. At the end of the first day of counting on Thursday, 57 percent of the ballots supported being represented by Amazon Labor Union, and 43 percent were opposed. The N.L.R.B. said the count should be finished Friday.                                                                                                                                                                                                                , Workers who supported the union in Bessemer cited frustrations over low pay, inadequate breaks and overly aggressive productivity targets. Amazon has said its pay — just under $16 per hour for full-time, entry-level workers — is competitive for the area. It has also pointed to a benefits package that it says is attractive, including complete health care benefits for full-time employees as soon as they join the company. The company has said its performance targets reflect safety considerations and individual employees’ experience., Several employees who backed the union said co-workers were generally less afraid to question management or show their union support this year than during last year’s election. “People are asking more questions,” Jennifer Bates, an employee who helped lead the organizing effort both last year and this year, said in an interview this month. “More employees are standing up and speaking out.”                                                                                                                                               , The union also cited key differences in its approach to the more recent election. Last year, the union curtailed in-person organizing efforts because of Covid-19 safety concerns, but this time its organizers visited workers at home. Other unions dispatched organizers to Alabama to aid in these efforts.                                                                                                                                                                                                                                        , Workers also appeared to be more active in organizing within the plant. They wore union T-shirts to work twice each week to demonstrate support, and one group delivered a petition to managers with more than 100 signatures complaining of inadequate breaks and break room equipment.                                                                                                                                                                                                                                                               , Still, Amazon retained advantages, not least of which was its high rate of employee turnover, which made it difficult for organizers to sustain momentum as disaffected workers simply left their jobs.                                                                                                                                                                                                                                                                                                                                                , The company also appeared to spend generously on its effort to dissuade employees from backing the union, hiring consultants and holding more than 20 anti-union meetings with employees per day before mail ballots went out in early February. In a Labor Department filing released on Thursday, Amazon disclosed that it had spent more than $4 million on labor consultants last year. It has yet to reveal how much it spent on consultants this year.                                                                                           , Union supporters accused Amazon of excluding them from meetings to mute criticism and pushback, but Amazon denied the accusation.                                                                                                                                                                                                                                                                                                                                                                                                                      , The tally announced on Thursday was consistent with a broader trend in rerun elections, more than half of which unions have lost since 2010.                                                                                                                                                                                                                                                                                                                                                                                                           , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/currency </td>
   <td style="text-align:left;"> 2022-04-01 05:15:01 </td>
   <td style="text-align:left;"> South Korean Won Hits 5-week High </td>
   <td style="text-align:left;"> USDKRW decreased to a 5-week low of 1190 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/31/europe/irpin-ukraine-war-destruction-intl/index.html </td>
   <td style="text-align:left;"> 2022-04-01 05:04:41 </td>
   <td style="text-align:left;"> Irpin: Ukrainians have retaken Irpin from the Russian invaders. But it's a city that now lies in ruins - CNN </td>
   <td style="text-align:left;"> Irpin, Ukraine (CNN)A child's doll lies curb side, covered in dirt and debris, in the war-torn Kyiv suburb of Irpin.                                                                                                                                                                       , There's not a sign of the child who owned it, or of any of the residents of the building next to it, which was shattered to pieces after taking a direct hit from Russian artillery.                                                                                                       , This is what Irpin -- or what's left of it -- looks like, just a couple of days after Ukrainian forces took it back from Russian control.                                                                                                                                                  , The area is still extremely dangerous and remains off limits to civilians. As fighting continues in the nearby areas of Bucha and Hostomel, Irpin is still well within range for Russian artillery.                                                                                        , CNN was granted rare access to the city by Ukrainian forces on Thursday.                                                                                                                                                                                                                   , We snake our way to Irpin through dirt roads in the middle of the forest that separates the suburb from Kyiv at breakneck speed.                                                                                                                                                           , "It's safer this way," Andriy, the 29-year-old Ukrainian soldier driving us explains. "It's the best way of avoiding Russian artillery."                                                                                                                                                   , Across the Irpin river, the destruction caused by a month of confrontation between Russian and Ukrainian forces is everywhere. There are few unbroken windows, fallen trees in nearly every corner and no shortage of broken down or destroyed military equipment. Most of it is Russian.  , The majority of the town's residents have fled, but Ivan Boyko decided to stay. He sent most of his family away, to safety, opting to endure the inferno of the Russian offensive.                                                                                                         , "I am 66 years old, I'm not afraid anymore," he says.                                                                                                                                                                                                                                      , Despite staying in Irpin, Boyko has been forced to move out of his house and into a bomb shelter because of all the intense shelling.                                                                                                                                                      , "It's impossible to go home," he explains. "Every night and day they shoot. It's scary to go out."                                                                                                                                                                                         , "People brought all they have to the bomb shelter," he adds.                                                                                                                                                                                                                               , After days of intense shelling, Irpin is eerily quiet, the silence only broken by sporadic gunfire in the distance. It looks like a ghost town.                                                                                                                                            , Authorities here are using the opportunity to recover bodies of those killed in previous weeks. Less than 24 hours ago, they had to stop because of a Russian attack.                                                                                                                      , "Our police group, which was recovering cadavers, was fired upon with mortars," the Chief of Police for the Kyiv region told journalists in Irpin on Thursday. "They were lying under the bridge for an hour, waiting for it to stop."                                                     , "The enemy is acting dirtily. It can fire shots from a distance of up to 7 kilometers (around 4.3 miles)," he adds.                                                                                                                                                                        , A few blocks away we meet 51-year-old Volodymyr Rudenko. Born and raised in Irpin, he is patrolling the town in military fatigues and an AK-47 in his hands.                                                                                                                               , "I grew up here. I practically haven't left Irpin since 1975. Now it's my duty to defend it," he says.                                                                                                                                                                                     , He picked up arms when the Russians invaded and refused to leave -- even when they took partial control of the town.                                                                                                                                                                       , "I haven't left Irpin since the first day of the war, not even for a single day," Rudenko says.                                                                                                                                                                                            , "It was very hard. There were very strong attacks," he explains. "...there were 348 impacts in one area in a single hour."                                                                                                                                                                 , The ferocity of those bombings is on full display here and it is hard to see how any of the more than 60,000 of the town's residents could return anytime soon. Most buildings are either destroyed or damaged beyond repair.                                                              , According to local authorities, around 50% of the critical infrastructure has been destroyed.                                                                                                                                                                                              , Irpin is now under full Ukrainian control, but some Russian operatives remain in the area. Local authorities are organizing search parties for Russian soldiers who remain.                                                                                                                , Mayor Oleksandr Markushin is leading one of the special forces units tasked with that job.                                                                                                                                                                                                 , "We are working. There is information that there are two Russian soldiers dressed in civilian clothes," Markushin says.                                                                                                                                                                    , "With our group, we are going to clean them up," he adds.                                                                                                                                                                                                                                  , After a few hours, we drive out through the same dirt paths, hoping to avoid Moscow's artillery.                                                                                                                                                                                           , It's been a good day for Andriy and his fellow soldiers, with a lot less fighting in and around Irpin.                                                                                                                                                                                     , "The Russians are retreating," he says.                                                                                                                                                                                                                                                    , Retaking the town has lifted everyone's spirits and Andriy has faith Ukrainians won't stop there.                                                                                                                                                                                          , "My 29th birthday is in a few weeks," he says. "I hope we'll have beaten them by then."                                                                                                                                                                                                    , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.marketwatch.com/story/a-dozen-s-p-500-stocks-just-had-their-worst-quarter-ever-as-tech-stocks-sloughed-off-nearly-2-trillion-in-value-11648760186 </td>
   <td style="text-align:left;"> 2022-04-01 04:56:00 </td>
   <td style="text-align:left;"> A dozen S&amp;P 500 stocks just had their worst quarter ever, as tech stocks sloughed off nearly $2 trillion in value - MarketWatch </td>
   <td style="text-align:left;"> A stock selloff to start 2022 led to the worst quarter in history for a dozen S&amp;P 500 stocks, as investors punished pandemic darlings and highly valued tech companies, subtracting roughly $2 trillion in market cap.                                                                                                                                                                                                                                                                                                                                                               , Tech companies took the brunt of a first-quarter selloff that was felt throughout Wall Street, as the Nasdaq Composite Index 
        COMP
       lost $1.99 trillion in market cap through Wednesday’s close, its worst quarterly performance since the fourth quarter of 2018, according to Dow Jones Market Data Group. More broad-based indexes also lost more than $1 trillion in market cap but held up better than the tech-heavy Nasdaq, with the S&amp;P 500 index 
        SPX
       declining by $1.46 trillion.                                                         , Dow Jones Market Data Group found 12 stocks that suffered their worst quarterly percentage decline, and roughly half could be considered tech companies: Etsy, PayPal, Facebook parent company Meta Platforms, Keysight Technologies, Match Group and Charter Communications. Others that may not be considered “tech companies” were still harmed by some of the same dynamics that damaged those stocks, however — Xylem, which sells controls technology and other supplies to the water industry, saw its margins slammed by increasing costs of components for those systems.   , Deep Dive: These 10 stocks fell at least 20% in the first quarter, but are expected to soar up to 66% from here                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , The 12 stocks combined to lose nearly half a trillion dollars in market cap on their own, a total of $494.19 billion. The bulk of that came from Facebook, which dropped more than $300 billion in valuation as investors chopped off roughly a third of its stock price.                                                                                                                                                                                                                                                                                                            , Facebook’s market-cap decline is more than the actual market caps of The Walt Disney Co. 
        DIS
       and legacy tech stalwarts such as Cisco Systems Inc. 
        CSCO
       and Oracle Corp. 
        ORCL,
       and almost exactly three times the combined valuations of social-media competitors Snap Inc. 
        SNAP,
       Twitter Inc. 
        TWTR
       and Pinterest Inc. 
        PINS,
       which were collectively worth about $105.6 billion at Thursday’s close.                                                                      , Meta stock was slammed by a change in Apple Inc.’s 
        AAPL
      mobile operating system that harmed Facebook advertisers’ ability to track their campaigns. Executives blamed the changes for a holiday-season earnings miss and weak first-quarter sales guidance, leading to huge declines in the stock. Other social-media companies were not immune, with Twitter declining nearly 10% in the quarter, Snap falling more than 20% and Pinterest’s decline topping 30%.                                                                                                  , See also: Meta CFO cries ‘wolf’ again with bleak Facebook outlook — but he may be right this time                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Other tech companies experienced big gains during the pandemic, but saw that trajectory reverse hard as growth petered out. PayPal was a highflier during the early part of the pandemic, but the company shocked investors when it announced a change to its strategy earlier this year. The financial-technology pioneer was showing sharp growth in active accounts, but executives said in February that they planned to instead start focusing on driving activity among more lucrative users, rather than expanding the user base in the absolute.                             , For more: PayPal stock dives to worst day on record after ‘ugly’ earnings report                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Investors were surprised, as the new strategy meant that PayPal would be abandoning a longer-term target for user growth that it had maintained just months earlier. Additionally, the company pointed to negative spending impacts among lower-income consumers. PayPal’s spending commentary on the whole struck one analyst as more downbeat than what card companies Visa Inc. 
        V
       and Mastercard Inc. 
        MA
       had recently offered.                                                                                                                , Etsy surged along with sales of masks and other pandemic-related gear combining with a general e-commerce upswing, but analysts believe the company may have hit a growth plateau. “While the company has demonstrated remarkable success in reactivating dormant buyers, we believe new buyer growth may’ve peaked,” Truist analysts recently wrote, while maintaining a buy rating and $220 price target.                                                                                                                                                                          , Read: Etsy sellers plan boycott, call company’s new fee hike ‘pandemic profiteering’                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Online dating also received a boost during the pandemic, but Match’s forecast earlier this year was light amid concerns about the Omicron variant. Analysts still see possibilities that online dating could bounce back in a big way this year, however — Wedbush analysts wrote earlier this year that “Match continues to be viewed as a ‘reopening play,’ and if COVID cases ease as we head into the warmer months, we should see improving growth as we head into 2H, and management is more optimistic about how 2H will play out.”                                           , Online dating amid coronavirus: Longer conversations and a ‘pivot’ to video dates                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    ,  After benefiting from the work-from-home boom at the beginning of the COVID-19 crisis, Charter is seeing a slowdown in broadband subscriber growth. The company is now looking for its next leg of growth, and it may have found it in the wireless business. Charter posted a record quarter of wireless additions with its latest earnings report, but it remains to be seen how the company will fare in the competitive market for phone plans.                                                                                                                                 , Other tech stocks had historically bad quarters as well, but did not set a record. Netflix Inc. 
        NFLX,
       for example, fell 37.8%, its worst quarterly performance since the second quarter of 2012, while Adobe Inc.’s 
        ADBE
       19.7% decline was its worst since the third quarter of 2011 and Intuit Inc.’s 
        INTU
       25.2% plunge was its worst since the dot-com-bust era, the first quarter of 2001, according to Dow Jones Market Data Group.                                                                                        , MarketWatch staff writer Emily Bary contributed to this article.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , The Hormel Foods brand is voluntarily recalling more than 9,000 cases of peanut butter across 18 states that may have been contaminated                                                                                                                                                                                                                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Jeremy Owens is MarketWatch’s technology editor and San Francisco bureau chief. You can follow him on Twitter @jowens510. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-04-01 04:43:00 </td>
   <td style="text-align:left;"> Brazilian Stocks Snap 2-Session Rally </td>
   <td style="text-align:left;"> The main Sao Paulo Index, Ibovespa, ended 0.22% lower to close at 119,999 on Thursday, snapping the two-session rally and tracking the weak global markets amid threats of aggressive rate hike bets and the war in Ukraine. Greater aversion to risks by the investors and a fall in commodity-linked stocks, especially oil weighed on the index. On the other hand, stocks exposed to interest rate hikes rose, limiting further losses. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-04-01 04:29:00 </td>
   <td style="text-align:left;"> Toronto Stocks Extend Declines </td>
   <td style="text-align:left;"> The S&amp;P/TSX Composite index closed 0.84% lower at 21,890.16 level, extending last session’s slight decline and tracking the fall in global markets amid twin threats of hawkish central banks bent on clamping down the surging inflation and the war in Ukraine. Health-care sector dragged the most, led by Canopy Growth (-4.1%) and Tilray (-4.1%). Also, technology booked losses with declines coming particularly from HUT 8 Mining (-4.2%) and Telus International (-3.4%). In financials, both CI Financial and Laurentian Bank dipped 2.6%. On the contrary, losses were limited by utilities and communiactions sector. For the month, the TSX booked 3.6% gain, its biggest advance since October, while it advanced 3.1% since the start of the year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gas-tax-holiday-not-off/story.aspx?guid={696379F7-751C-457B-9EE0-5B52361D5EE6}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-01 04:26:09 </td>
   <td style="text-align:left;"> Gas tax holiday not off table, White House says  - MarketWatch </td>
   <td style="text-align:left;"> A gasoline 
        RB00,
        -0.23%
       tax holiday remains an option under consideration as the Biden administration seeks to give Americans relief from high prices, a White House spokeswoman said Thursday. "The president is not taking anything off the table at this stage," White House communications director Kate Bedingfield told reporters. Earlier Thursday, Biden announced the U.S. would release 1 million barrels of oil per day for the next six months from the Strategic Petroleum  Reserve, or more than 180 million barrels in total. House Speaker Nancy Pelosi, meanwhile, has sounded a skeptical note about the effectiveness of such a holiday., BlackRock's Robert Kapito says an "entitled" generation that has never had to cope with shortages is about to get a wake-up call.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Robert Schroeder is the Washington bureau chief for MarketWatch. Follow him on Twitter @mktwrobs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/white-house-wont-name-oil-gas-companies-blaming-high-prices </td>
   <td style="text-align:left;"> 2022-04-01 04:22:00 </td>
   <td style="text-align:left;"> White House won’t name oil and gas companies it’s blaming for high prices </td>
   <td style="text-align:left;"> Marc Short, former Chief of Staff to VP Pence, shares his take on Biden's plan to release oil from the Strategic Oil Reserve and the climate agenda outlined in the president's latest budget.                                                                                                                                                                                                                                                                                                                                                                       , The White House declined to specifically name any oil and gas companies that President Biden blamed earlier Thursday for exploiting the rise in energy prices and lining the pockets of investors.                                                                                                                                                                                                                                                                                                                                                                   , National Economic Council Director Brian Deese was asked during Thursday’s press briefing to identify what companies the Biden administration considers to be good actors or bad actors.                                                                                                                                                                                                                                                                                                                                                                             , BIDEN ADMINISTRATION TO RELEASE 1 MILLION BARRELS OF OIL DAILY FROM US RESERVES                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , "I want to give you an opportunity, for Americans who want to do the patriotic thing, where should they be going to buy their gas right now?" the reporter asked. "Are there good companies that have worked with the administration and folks that you're frustrated with right now?"                                                                                                                                                                                                                                                                               , White House National Economic Council Director Brian Deese gestures as he speaks during the daily White House press briefing on January 12, 2022 in Washington, DC. (Photo by Anna Moneymaker/Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                                           , Deese declined to name any companies, saying, "I would say our goal is to provide relief to all Americans in all geographies across the country."                                                                                                                                                                                                                                                                                                                                                                                                                    , "And that means doing everything we can to bring down the price of gas at the pump everywhere," Deese continued. "And so that's our focus, and the issue of the prices of gas going up very quickly and tracking oil prices and coming down much more slowly is not new. It's old enough that economists have a particular term associated with it called rockets and feathers. But it just because we can identify it doesn't mean that it reflects an efficient market or competitive market. So that that has been that has been our focus."                      , Biden announced earlier Thursday that he will release an additional 1 million barrels of oil each day for the next six months, 180 million total, from the U.S. Strategic Petroleum Reserve (SPR) in an effort to combat soaring gasoline prices. That would leave the already-depleted SPR down to around 388 million barrels, the lowest level since March 1984.                                                                                                                                                                                                   , U.S. President Joe Biden speaks about reducing energy prices in the Eisenhower Executive Office Building in Washington, D.C., U.S., on Thursday, March 31, 2022.  (Photographer: Al Drago/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                                 , Biden also called on Congress to force oil companies to pay fees for unused leases, accusing energy producers of "hoarding" wells on federal lands. He said that companies "sitting on unused leases and idle wells will either have to start producing or pay the price for their inaction."                                                                                                                                                                                                                                                                        , "For U.S oil companies that are recording their largest profits in years, they have a choice," the president said. "One, they can put those profits to productive use by producing more oil, restarting idle wells, or producing on the sites they already are leasing, giving the American people a break by passing some of the savings on to their customers and lowering the price at the pump. Or they can, as some of them are doing, exploit the situation, sit back, ship those profits to the investors while American families struggle to make ends meet.", A car passes a gas station sign in Annapolis, Maryland, on March 14, 2022, as record high gas prices hit working-class Americans with inflation already surging. (Jim Watson/AFP via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                                                    , The oil and gas industry insists that obtaining a lease is merely the first step in a process that includes permitting and investigating whether there is actually any fossil fuel below the ground to extract.                                                                                                                                                                                                                                                                                                                                                      , The White House pressure on oil companies over "unused" leases is being echoed by Democrats in Congress, who are pushing the companies' CEOs to testify next week.                                                                                                                                                                                                                                                                                                                                                                                                   , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , The House Committee on Energy and Commerce said on Tuesday executives from BP America, Chevron, Devon Energy Corp., ExxonMobil Corp., Pioneer Natural Resources Co., and Shell USA, will participate in a hearing next week.                                                                                                                                                                                                                                                                                                                                         , The April 6 hearing notably does not include the nation's two largest refineries, Texas-based Marathon or Valero, or the owner of the largest refinery in America, Saudi Aramco. Refining is a key step between oil production and the gas pump.                                                                                                                                                                                                                                                                                                                     , Fox News’ Bradford Betz, Kyle Morris and Breck Dumas contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60936468?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-01 04:20:12 </td>
   <td style="text-align:left;"> Biden orders 'unprecedented' release of oil reserves </td>
   <td style="text-align:left;"> US President Joe Biden has ordered a major release of oil from America's reserves in an effort to bring down high fuel costs.                                                                                                                                                       , The release of up to 180m barrels of oil over six months is the largest since the reserve was created in 1974.                                                                                                                                                                      , Oil prices dropped on reports of the move, which is aimed at easing a supply crunch sparked by war in Ukraine.                                                                                                                                                                      , But the release - of about 1m barrels a day - is unlikely to fully resolve the energy crisis, analysts say.                                                                                                                                                                         , Mr Biden promised further action to boost US output, saying the release would "serve as [a] bridge until the end of the year when domestic production ramps up".                                                                                                                    , He called for companies to pay extra if they choose not to use oil wells on land they lease from the government, as well as investments to speed up the adoption of greener energy sources.                                                                                         , Following Mr Biden's remarks, US oil benchmark West Texas Intermediate was more than 7% lower at about $100 a barrel, while Brent Crude fell roughly 5.4% to around $107.                                                                                                           , The soaring cost of fuel has become a major political issue around the world, including in the US, which hosts mid-term elections in November.                                                                                                                                      , Mr Biden said the scale of the release from the Strategic Petroleum Reserve - which together amounts to less than two days of global consumption - was "unprecedented".                                                                                                             , Thursday's announcement marked the third time in six months Mr Biden has moved to draw down America's crude oil stockpiles                                                                                                                                                          , But the release of additional reserves is unlikely to be enough to compensate for lost supplies from Russia - the world's second-biggest oil exporter after Saudi Arabia.                                                                                                           , "While stock releases will help to keep a lid on prices in the short term, we think it will take an increase in global production to spark a sustained fall in prices," said Edward Gardner, commodities economist at Capital Economics.                                            , Brent crude - the global benchmark for oil prices - hit $139 a barrel earlier this month after Russia's invasion of Ukraine and sanctions slapped on Moscow by the US and its allies.                                                                                               , Energy prices have fallen back since then, but oil is still almost 70% higher than it was a year ago.                                                                                                                                                                               , Analysis by Samira Hussain, BBC News reporter                                                                                                                                                                                                                                       , It makes for an excellent headline: President Biden releases unprecedented amounts of oil from strategic reserves. But it really only offers a temporary fix to global shortages. So why is the White House even bothering?                                                         , Domestically, the President is under a tremendous amount of pressure. November is the midterm elections and Democrats hold a very slim majority that they are desperate to hold on to.                                                                                              , Rising inflation was already an issue, and Republicans have been laying the blame for the high cost of living on the White House and specifically Mr Biden.                                                                                                                         , The record high cost of fuel just adds to the pain being felt by the American middle class. And it certainly doesn't jive well with the president's "Joe from Scranton" vibe.                                                                                                       , Global demand for energy had been rising prior to Russia's invasion of Ukraine as economies started to reopen as coronavirus lockdown measures were relaxed.                                                                                                                        , However, the war in Ukraine has raised fears of supply issues, with warnings that Russian oil exports could fall by as much as 3m barrels a day.                                                                                                                                    , Most major energy-producing nations are either at full capacity or are unwilling to increase output.                                                                                                                                                                                , On Thursday, the Organization of the Petroleum Exporting Countries (Opec) and its allies, including Russia, confirmed they were sticking to their existing deal to gradually increase production.                                                                                   , The decision came despite pressure from the US, UK and others on members of the group of oil producing nations to boost output.                                                                                                                                                     , "The consensus on the outlook pointed to a well-balanced market," the group said.                                                                                                                                                                                                   , "Current volatility is not caused by fundamentals, but by ongoing geopolitical developments."                                                                                                                                                                                       , The International Energy Agency (IEA) has called an emergency meeting but it is unclear whether other countries, including the UK, France, Germany and Japan, will follow the US by releasing oil reserves.                                                                         , Mr Biden said he was coordinating with Western nations on the release of the stockpiles and expected them to release another 30 to 50 million barrels.                                                                                                                              , Also on Thursday, Japan said that it would take emergency measures to secure supplies of seven strategic materials it relies on heavily from Russia or Ukraine as the war and sanctions cause disruptions to supplies.                                                              , The country's industry minister said the actions include government support to boost domestic production, alternative procurement and to help technological developments to reduce use of the materials, which include liquefied natural gas and gases used in computer chip-making., This video can not be played                                                                                                                                                                                                                                                        , Kevin Parle has been on the run since 2004 - will he ever be brought to justice?                                                                                                                                                                                                    , Louis Theroux on storytelling and the culture wars                                                                                                                                                                                                                                  , Russell Kane tackles the former president's legacy                                                                                                                                                                                                                                  , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/dow-ends-550-points-lower/story.aspx?guid={85414788-B274-4CF0-8C1C-E6F609730717}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-01 04:06:49 </td>
   <td style="text-align:left;"> Dow ends 550 points lower as investors close books on losing quarter - MarketWatch </td>
   <td style="text-align:left;"> Stocks  closed sharply lower Thursday, capping a volatile and losing quarter for major U.S. equity indexes. The Dow Jones Industrial Average 
        DJIA,
        -1.56%
       fell around 550 points, or 1.6%, to close near 34,678, according to preliminary figures, while the S&amp;P 500 
        SPX,
        -1.57%
       fell around 72 points, or 1.6%, to end near 4,530.The Nasdaq Composite 
        COMP,
        -1.54%
       shed around 222 points, or 1.5%, finishing near 14,221. That left the S&amp;P 500 down nearly 5% for the first three months of 2022, its first losing quarter in two years. The Dow fell 4.6% over the first quarter, while the Nasdaq dropped 9.1%., The last time all three of these indexes endured this technical chart pattern was in March 2020.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , William Watts is MarketWatch’s senior markets writer. Based in New York, Watts writes about stocks, bonds, currencies and commodities, including oil. He also writes about global macro issues and trading strategies. Before moving to New York, he reported for MarketWatch from Frankfurt, London and Washington, D.C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/1109:hk </td>
   <td style="text-align:left;"> 2022-04-01 04:06:04 </td>
   <td style="text-align:left;"> China Resources Land earnings above expectations at 2.89 HKD </td>
   <td style="text-align:left;"> China Resources Land (1109) released earnings per share at 2.89 HKD, compared to market expectations of 2.74 HKD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/argentina/consumer-confidence </td>
   <td style="text-align:left;"> 2022-04-01 03:53:20 </td>
   <td style="text-align:left;"> Argentina Consumer Morale Worsens in March </td>
   <td style="text-align:left;"> The consumer confidence indicator in Argentina fell to 36.9 in March of 2022 from 39.4 in the prior month as Sentiment deteriorated broadly across all subindices: Argentina’s macroeconomic situation (37.3 vs 40.6 in February), personal financial situation (42.7 vs 44.1) and propensity to purchase durable goods (30.7 vs 33.6). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/el-salvador/gdp-growth-annual </td>
   <td style="text-align:left;"> 2022-04-01 03:42:00 </td>
   <td style="text-align:left;"> El Salvador GDP Growth Eases in Q4 </td>
   <td style="text-align:left;"> The economy of El Salvador expanded 3.7 percent in the fourth quarter of 2021, easing from a 11.6 percent jump in the previous period, as the effects of a lower base of comparison started to fade. It was the weakest growth rate since the first quarter of 2021 amid a slowdown in household consumption (7.8 percent vs 16.9 percent), government spending (6.1 percent vs 10.3 percent), and fixed investment (6.6 percent vs 20.3 percent). Also, net exports contributed negatively to the GDP as imports jumped 19.9 percent, while exports advanced at a slower 1.6 percent. Considering the full 2021, the economy grew 10.3 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/03/31/business/meta-child-sexual-abuse.html </td>
   <td style="text-align:left;"> 2022-04-01 03:38:52 </td>
   <td style="text-align:left;"> Adults or Sexually Abused Minors? Getting It Right Vexes Facebook - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , The company reports millions of photos and videos of suspected child sexual abuse each year. But when ages are unclear, young people are treated as adults and the images are not reported to the authorities.                                                                                                                                                                                                                                                                       , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                              , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                       , By Michael H. Keller                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Facebook is a leader among tech companies in detecting child sexual abuse content, which has exploded on social media and across the internet in recent years. But concerns about mistakenly accusing people of posting illegal imagery have resulted in a policy that could allow photos and videos of abuse to go unreported.                                                                                                                                                      , Meta, the parent company of Facebook, Instagram, Messenger and WhatsApp, has instructed content moderators for its platforms to “err on the side of an adult” when they are uncertain about the age of a person in a photo or video, according to a corporate training document.                                                                                                                                                                                                     , Antigone Davis, head of safety for Meta, confirmed the policy in an interview and said it stemmed from privacy concerns for those who post sexual imagery of adults. “The sexual abuse of children online is abhorrent,” Ms. Davis said, emphasizing that Meta employs a multilayered, rigorous review process that flags far more images than any other tech company. She said the consequences of erroneously flagging child sexual abuse could be “life-changing” for users.      , While it is impossible to quantify the number of images that might be misclassified, child safety experts said the company was undoubtedly missing some minors. Studies have found that children are physically developing earlier than they have in the past. Also, certain races and ethnicities enter puberty at younger ages, with some Black and Hispanic children, for example, doing so earlier than Caucasians.                                                              , “We’re seeing a whole population of youth that is not being protected,” said Lianna McDonald, executive director of the Canadian Center for Child Protection, an organization that tracks the imagery globally.                                                                                                                                                                                                                                                                      , Each day, moderators review millions of photos and videos from around the world to determine whether they violate Meta’s rules of conduct or are illegal. Last year, the company made nearly 27 million reports of suspected child abuse to a national clearinghouse in Washington that then decides whether to refer them to law enforcement. The company accounts for more than 90 percent of the reports made to the clearinghouse.                                               , The training document, obtained by The New York Times, was created for moderators working for Accenture, a consulting firm that has a contract to sort through Facebook’s noxious content and remove it from the site. The age policy was first disclosed in California Law Review by a law student, Anirudh Krishna, who wrote last year that some moderators at Accenture disagreed with the practice, which they referred to as “bumping up” adolescents to young adults.         , Accenture declined to comment on the practice.                                                                                                                                                                                                                                                                                                                                                                                                                                       , Technology companies are legally required to report “apparent” child sexual abuse material, but “apparent” is not defined by the law. The Stored Communications Act, a privacy law, shields companies from liability when making the reports, but Ms. Davis said it was unclear whether the law would protect Meta if it erroneously reported an image. She said lawmakers in Washington needed to establish a “clear and consistent standard” for everyone to follow.               , Legal and tech policy experts said that social media companies had a difficult path to navigate. If they fail to report suspected illicit imagery, they can be pursued by the authorities; if they report legal imagery as child sexual abuse material, they can be sued and accused of acting recklessly.                                                                                                                                                                           , “I could find no courts coming close to answering the question of how to strike this balance,” said Paul Ohm, a former prosecutor in the Justice Department’s computer crime division who is now a professor at Georgetown Law. “I don’t think it’s unreasonable for lawyers in this situation to put the thumb on the scale of the privacy interests.”                                                                                                                              , Charlotte Willner, who leads an association for online safety professionals and previously worked on safety issues at Facebook and Pinterest, said the privacy concerns meant that companies “aren’t incentivized to take risks.”                                                                                                                                                                                                                                                    , But Ms. McDonald, of the Canadian center, said the rules should err on the side of “protecting children,” just as they do in commerce. She cited the example of cigarette and alcohol vendors, who are trained to ask for identification if they have doubts about a customer’s age.                                                                                                                                                                                                 , Representatives for Apple; Snap, the owner of Snapchat; and TikTok said their companies took the opposite approach of Meta, reporting any sexual image in which a person’s age was in question. Some other companies that scan their services for illegal imagery, including Dropbox, Google, Microsoft and Twitter, declined to comment on their practices.                                                                                                                         , In interviews, four former content moderators contracted by Meta said they encountered sexual images every day that were subject to the age policy. The moderators said they could face negative performance reviews if they made too many reports that were deemed out of policy. They spoke on the condition of anonymity because of nondisclosure agreements and concerns about future employment.                                                                                , “They were letting so many things slide that we eventually just didn’t bring things up anymore,” said one of the former moderators, who described detecting images of oral sexual abuse and other explicit acts during his recent two-year tenure at Accenture. “They would have some crazy, extravagant excuse like, ‘That blurry portion could be pubic hairs, so we have to err on the side of it being a young adult.’”                                                          , The number of reports of suspected child sexual abuse has grown exponentially in recent years. The high volume, up from roughly 100,000 in 2009, has overwhelmed both the national clearinghouse and law enforcement officials. A 2019 investigation by The Times found that the Federal Bureau of Investigation could only manage its case load from the clearinghouse by limiting its focus to infants and toddlers.                                                               , Ms. Davis said a policy that resulted in more reports could worsen the bottleneck. “If the system is too filled with things that are not useful,” she said, “then this creates a real burden.”                                                                                                                                                                                                                                                                                       , But some current and former investigators said the decision should be made by law enforcement.                                                                                                                                                                                                                                                                                                                                                                                       , “No one should decide not to report a possible crime, especially a crime against a child, because they believe that the police are too busy,” said Chuck Cohen, who led a child exploitation task force in Indiana for 14 years.                                                                                                                                                                                                                                                     , Dana Miller, the commander of a similar task force in Wisconsin, said tech companies could not know whether a report might be useful in furthering an existing investigation. “Even though everyone is overwhelmed, we’re not comfortable on our side making a blanket statement that we don’t want to see those reports,” she said.                                                                                                                                                 , Yiota Souras, general counsel at the National Center for Missing and Exploited Children, the national clearinghouse for the reports, said the center’s caseload “can’t be at play here.” She said imagery should always be reported if it might involve a child.                                                                                                                                                                                                                     , How Facebook makes its age determinations is also a point of contention. According to the training document and interviews, Facebook instructs its moderators to incorporate so-called Tanner stages when assessing age. Initially developed in the late 1960s by Dr. James M. Tanner, a British pediatrician, the tool outlines the progressive phases of puberty. But it was not designed to determine someone’s age.                                                              , In a 1998 letter to the journal Pediatrics, Dr. Tanner said that using the stages to measure “chronologic age” when analyzing child sexual abuse imagery was “wholly illegitimate.” Dr. Tanner died in 2010. The co-author of the letter, Dr. Arlan L. Rosenbloom, now a retired pediatric endocrinologist, said in an interview that a child at 13 or 14 could be “fully developed” under the Tanner stages. He also characterized Meta’s approach as “a total misuse” of the scale., Ms. Davis said the scale was widely used in the tech industry and was just one factor in estimating age. She acknowledged its limitations and said the company was exploring alternatives.                                                                                                                                                                                                                                                                                           , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/colombia/interest-rate </td>
   <td style="text-align:left;"> 2022-04-01 03:15:00 </td>
   <td style="text-align:left;"> Colombia Hikes Interest Rate by Less than Expected </td>
   <td style="text-align:left;"> The central bank of Colombia raised its benchmark interest rate by 100bps to 5.0% in its March 31stmeeting, surprising markets with a smaller than expected rate hike given the recent surge in inflation. It followed a 100bps increase in the previous meeting, marking the 5th consecutive rate hike. Consumer prices in Colombia rose 8% in February from a year earlier, the fastest since 2016 and double the upper limit of the central bank’s target range. The bank noted that Russia’s invasion of Ukraine could intensify inflation and hence raised the inflation expectations to 6.4% in 2022 and 3.8% in 2023. Meanwhile, it also revised its growth forecast for 2022 upwards from 4.3% to 4.7%. However, the monetary authority reiterates its commitment to the gradual return of inflation to the 3% annual target, for which it will continue to make the necessary decisions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/600519:ch </td>
   <td style="text-align:left;"> 2022-04-01 03:05:16 </td>
   <td style="text-align:left;"> Kweichow Moutai earnings above expectations at 12.10 CNY </td>
   <td style="text-align:left;"> Kweichow Moutai (600519) released earnings per share at 12.10 CNY, compared to market expectations of 11.93 CNY. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/601066:ch </td>
   <td style="text-align:left;"> 2022-04-01 03:04:31 </td>
   <td style="text-align:left;"> China Securities Co Ltd earnings above expectations at 0.34 USD </td>
   <td style="text-align:left;"> China Securities Co Ltd (601066) released earnings per share at 0.34 USD, compared to market expectations of 0.18 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/oil-futures-mark-lowest-finish/story.aspx?guid={626ECCBC-E559-4270-A04A-B9EDC41F2972}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-01 02:55:11 </td>
   <td style="text-align:left;"> Oil futures mark lowest finish in over 2 weeks as U.S. announces biggest-ever release from crude reserves - MarketWatch </td>
   <td style="text-align:left;"> Oil futures dropped on Thursday as the U.S. announced its biggest-ever release from the nation's Strategic Petroleum Reserve. President Joe Biden authorized the release of 1 million barrels of oil per day for the next six months. It's "essentially a temporary measure designed to minimize the spring rally, and to that end, it could increase supplies marginally and thereby keep prices commensurately lower," said Marshall Steeves, energy markets analyst at S&amp;P Global Commodity Insights. "However, the war in Ukraine remains the overriding consideration and the possible loss of Russian output is the motivating factor." West...
    , Pat Gelsinger took in total compensation of $178.6 million in 2021, for ten-and-a-half months of work as Intel's CEO                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/03/31/former-oligarch-leonid-nevzlin-renounces-russian-citizenship-ctw-gold-vpx.cnn </td>
   <td style="text-align:left;"> 2022-04-01 02:36:41 </td>
   <td style="text-align:left;"> Watch: Why this former oligarch renounced his Russian citizenship - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-04-01 02:13:00 </td>
   <td style="text-align:left;"> Oil Falls Sharply as US Announces Reserve Release </td>
   <td style="text-align:left;"> WTI crude futures dropped more than 6% to below $102 per barrel on Thursday, as the Biden administration announced the largest-ever strategic petroleum reserve release. The plan involves putting on the market 1 million barrels of oil per day for six months to lower the gasoline prices that have hit record levels following Russia's invasion of Ukraine. The White House also asked US oil producers to increase output and said it would impose levies on those that were not making use of their drilling licenses on public lands. Meanwhile, OPEC+ agreed to raise its output targets by 432,000 barrels per day from May 1, as expected. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-futures-post-gains-session/story.aspx?guid={503CDD37-83B0-4489-B701-5A14EACA2963}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-01 02:11:34 </td>
   <td style="text-align:left;"> Gold futures post gains for the session, month and quarter - MarketWatch </td>
   <td style="text-align:left;"> Gold futures settled higher Thursday, posting a gain for the month as well as the quarter. "Gold will remain headline driven and seems poised to make another run higher as the latest Russian move on gas contracts suggests a breakthrough in peace talks seems very far away," said Edward Moya, senior market analyst at OANDA. Russia issued a decree Thursday, demanding payment for natural gas in rubles, but left a loophole to allow dollar and euro payments through a designated bank, the Associated Press reported. June gold 
        GCM22,
        -0.85%
       rose $15, or 0.8%, to settle at $1,954 an ounce. Based on the most-active contract, prices rose 2.8% for the month, but ended the quarter with a gain of 6.9%, according to Dow Jones Market Data., JPMorgan, Citi, Wells Fargo and Bank of America in all account for 25% of fossil fuel financing in the last six years, since the Paris climate pact was signed.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/macys-add-2800-jobs-584/story.aspx?guid={F3968D2E-4F77-413C-AFE2-DC0C9E05EF5D}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-01 01:55:56 </td>
   <td style="text-align:left;"> Macy's to add 2,800 jobs with $584 million North Carolina fulfillment center - MarketWatch </td>
   <td style="text-align:left;"> Macy's Inc. 
        M,
        -4.73%
       said Thursday that it will open a fulfillment center in China Grove, N.C. in 2024 that will employ 2,800 workers. The facility, which will span 1.4 million square feet and cost $584 million, will account for 30% of the department store retailer's digital supply chain capacity. Macy's is also expanding its Texas facility, with the new distribution center expected to be complete mid-2023. Macy's stock was down 3.5% on Thursday, but has rallied more than 52% over the past year., Pat Gelsinger took in total compensation of $178.6 million in 2021, for ten-and-a-half months of work as Intel's CEO                                                                                                                                                                                                                                                                                                                                                                                                                            , Tonya Garcia is a MarketWatch reporter covering retail and consumer-oriented companies. You can follow her on Twitter @tgarcianyc. She is based in New York. Tonya joined MarketWatch from Moguldom Media, where she was business editor for MadameNoire, a website targeting African-American women with a range of content from personal finance to economics, politics, education and lifestyle and entertainment.  She also worked at Mediabistro, and previously handled media relations for MSLGroup’s consumer practice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/colombia/unemployment-rate </td>
   <td style="text-align:left;"> 2022-04-01 01:54:00 </td>
   <td style="text-align:left;"> Colombia Jobless Rate Falls to 12.9% in February </td>
   <td style="text-align:left;"> The unemployment rate in Colombia fell to 12.9 percent in February of 2022 from 15.5 percent in the corresponding month of the previous year. The number of unemployed fell by 0.49 million to 3.21 million, while employment went up by 0.86 million to 21.7 million. Meanwhile, the employment rate increased to 55.9 percent from 52.8 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/biden-white-house-strategic-petroleum-reserve-energy-industry </td>
   <td style="text-align:left;"> 2022-04-01 01:52:22 </td>
   <td style="text-align:left;"> Energy industry slams Biden's Strategic Petroleum Reserve release plan: 'Not a long-term solution' </td>
   <td style="text-align:left;"> Fox Business spoke with energy industry leaders and Sen. Dan Sullivan, R-Alaska, about the Biden White House's claim that 9,000 oil and natural gas drilling leases sit unused.                                                                                                                                                                                                                                                                                            , Energy industry representatives Thursday slammed President Biden's plan to release one million barrels of oil per day from the Strategic Petroleum Reserve as short-sighted amid other policies that discourage production.                                                                                                                                                                                                                                                , "While this release could provide some near-term relief, it is not a long-term solution to meeting growing demand for affordable and reliable energy," said Frank Macchiarola, American Petroleum Institute's senior vice president of policy, economics and regulatory affairs. "Instead of managing from crisis to crisis, we should be focused on promoting policies that avoid them altogether through increased production of our nation’s domestic energy resources.", Energy prices skyrocketed in recent months, especially since Russia's invasion of Ukraine. Bipartisan pressure forced Biden to ban Russian oil imports, and officials like Energy Secretary Jennifer Granholm adjusted to be more favorable to U.S. production since the war started.                                                                                                                                                                                      , President Biden boards Air Force One at Andrews Air Force Base, Md., Dec. 15, 2021.  (AP Photo/Andrew Harnik / AP Newsroom)                                                                                                                                                                                                                                                                                                                                                , BIDEN ADMINISTRATION TO RELEASE 1M BARRELS OF OIL DAILY FROM US RESERVES                                                                                                                                                                                                                                                                                                                                                                                                   , But energy industry officials, Republicans and even some Democrats continued to criticize the administration for some of its policies they say are harming investment in U.S. energy and long-term production.                                                                                                                                                                                                                                                             , Now amid increasing pressure over gas prices, the White House announced Thursday that Biden will aim to increase domestic supply by injecting an unprecedented amount of oil into the market.                                                                                                                                                                                                                                                                              , "After consultation with allies and partners, the president will announce the largest release of oil reserves in history, putting one million additional barrels on the market per day on average — every day — for the next six months," the White House announced. "The scale of this release is unprecedented: the world has never had a release of oil reserves at this 1 million-per-day rate for this length of time."                                               , The White House added that the Department of Energy will use the revenue derived from the release to restock the reserves and "provide a signal of future demand and help encourage domestic production today."                                                                                                                                                                                                                                                            , Oil well equipment on the Forth Berthold Indian Reservation near New Town, N.D. MHA Nation produces about a quarter of North Dakota's annual oil output.  (Tyler Olson/FOX Business)                                                                                                                                                                                                                                                                                       , ENERGY INDUSTRY SWIPES BACK AT PSAKI ‘RED HERRING’ COMMENT ON OIL AND GAS LEASES                                                                                                                                                                                                                                                                                                                                                                                           , The White House also argued that energy companies "aren't doing their part and are choosing to make extraordinary profits without making additional investment to help with supply."                                                                                                                                                                                                                                                                                       , "Right now, the oil and gas industry is sitting on more than 12 million acres of non-producing federal land with 9,000 unused but already-approved permits for production," the White House said. "Today, President Biden is calling on Congress to make companies pay fees on wells from their leases that they haven’t used in years and on acres of public lands that they are hoarding without producing."                                                             , That move from the White House continues a pattern that started earlier this month when White House press secretary Jen Psaki criticized the energy industry for allowing so many oil and gas leases to sit unused. But American Exploration and Petroleum Council (AXPC) CEO Anne Bradbury at the time called it a "red herring" that doesn't reflect the reality of the energy industry.                                                                                 , American Petroleum Institute President and CEO Mike Sommers told FOX Business at the time that, often times, there simply isn't oil or gas below the leased land Psaki referenced.                                                                                                                                                                                                                                                                                         , President Biden speaks during a meeting with German Chancellor Olaf Scholz in the Oval Office of the White House Feb. 7, 2022, in Washington. (AP Photo/Alex Brandon / AP Newsroom)                                                                                                                                                                                                                                                                                        , "The administration is claiming they are responding to ‘Putin’s Price Hike at the Pump,’ but their planned solution is to target American energy producers with new taxes and fees, while our industry continues to face increased hurdles and regulatory red tape the Biden Administration itself has put in place to restrict domestic production," Bradbury said of Biden's plan Thursday.                                                                              , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                , "A punitive fee on federal lands will not incentivize or expedite development," she added. "Pulling crude from the Strategic Petroleum Reserve will not lower prices in the long term and may even do more harm than good. And targeting American energy workers with false narratives about pricing does not change the law of supply and demand."                                                                                                                        , Western Energy Alliance President Kathleen Sgamma Thursday slammed the administration for how it's handling energy prices and the industry in general. But she said the fact that the White House is talking about increasing production is a good sign.                                                                                                                                                                                                                   , "The White House is in a panic because polling suggests Americans understand that the anti-oil and -gas agenda of this administration is the primary reason gasoline prices are high," Sgamma said. "The president is trying to pass blame onto producers. On the plus side, we’re glad the president now wants us to develop on federal lands, since he had spent the past two years promising to eliminate federal oil." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/rail-visions-stock-opens-well/story.aspx?guid={A3841190-7F6E-48A9-AA4A-9A19119AAA83}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-04-01 01:50:40 </td>
   <td style="text-align:left;"> Rail Vision's stock opens well below IPO price, and keeps falling - MarketWatch </td>
   <td style="text-align:left;"> Rail Vision Ltd. 
        RVSN,
        -25.18%
       received a very cool reception on Wall Street, as the Israel-based railway-safety technology company's shares opened 24% below the initial public offering price, then kept falling. The company raised $15.6 million in the upsized IPO, as it sold 3.79 million share units at $4.13 each, which was the bottom of the expected range, with each unit consisting of one ordinary share and one warrant to buy one ordinary share at an initial exercise price of $4.13. The company had said last week that it expected to offer up to 3.55 million share units at a price of between $4.13 and $5.87 per unit. Aegis Capital was the sole book-running manager. Rail Vision recorded a net loss of $5.13 million on revenue of $417,000 during the six months ended June 30, 2021, after a loss of $5.07 million on no revenue a year earlier. The Nasdaq-listed stock's first trade was at $3.14 at 11:10 a.m. Eastern for 144,848 shares, and that price remained the intraday high. The traded as low as $2.45, or 40.7% below the IPO price, before paring some losses to be down 35.0% in afternoon trading, enough to make it the Nasdaq's biggest loser. The company has gone public at a time of relative investor disdain for IPOs, as the Renaissance IPO ETF 
        IPO,
        -2.20%
       has tumbled 23.0% year to date while the S&amp;P 500 
        SPX,
        -1.57%
       has slipped 3.8%., The Hormel Foods brand is voluntarily recalling more than 9,000 cases of peanut butter across 18 states that may have been contaminated                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-04-01 01:43:00 </td>
   <td style="text-align:left;"> US Stocks Wrap 1st Losing Quarter in 2 Years </td>
   <td style="text-align:left;"> US stocks again extended the decline in the last hour of trading to end the quarter sharply lower as investors reassessed the outlook of tightening monetary policy while watching developments in the Russia-Ukraine war. The Dow slid 550 points while the S&amp;P 500 the Nasdaq Composite was down more than 1.5%. The equity markets have been very volatile so far this year. In the first three months of 2022, the Dow and S&amp;P 500 are both down about 4.5% and the Nasdaq is off 9%, the first losing quarter in 2 years. Still, the stocks finished March on a solid note with Dow up 2.2% and the S&amp;P 500 and Nasdaq gaining more than 3%| after a rally in recent weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ukraine/current-account </td>
   <td style="text-align:left;"> 2022-04-01 01:36:00 </td>
   <td style="text-align:left;"> Ukraine Current Account Surplus Widens in February </td>
   <td style="text-align:left;"> Ukraine’s current account surplus widened to USD 383 million in February of 2022 from USD 134 million in the corresponding month of the previous year. The services surplus rose to USD 453 million from USD 298 million and the primary income swung to a surplus of USD 83 million from a deficit of USD 5 million. At the same time, the secondary income surplus widened to USD 456 million from USD 321 million. On the contrary, the goods deficit increased to USD 609 million from USD 480 million a year ago. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/31/the-great-resignation-is-still-in-full-swing-heres-what-to-know.html </td>
   <td style="text-align:left;"> 2022-04-01 01:28:45 </td>
   <td style="text-align:left;"> The Great Resignation is still in full swing. Here’s what to know </td>
   <td style="text-align:left;"> , The pandemic-era trend known as the "Great Resignation" remains a prominent feature of the labor market, as favorable conditions lead workers to quit their jobs at near-record levels in search of better (and ample) opportunities elsewhere.                                                                                                                 , Nearly 4.4 million Americans quit their jobs in February, the U.S. Department of Labor said Tuesday.                                                                                                                                                                                                                                                            , That's about 100,000 more people than quit in January, and just shy of the 4.5 million record set in November.                                                                                                                                                                                                                                                  , "These quits are still extremely high, and that shows the Great Resignation is still in full swing," said Daniel Zhao, senior economist at the career site Glassdoor.                                                                                                                                                                                           , The high demand for workers shows little sign of abating but may have plateaued, he added.                                                                                                                                                                                                                                                                      , "It wouldn't be a surprise to see that cool down in 2022," Zhao said. "But that's not to say we should expect the Great Resignation to disappear overnight."                                                                                                                                                                                                    , Resignations, or "quits" — which are generally voluntary separations initiated by workers — serve as a measure of employees' willingness or ability to leave jobs, according to the Labor Department.                                                                                                                                                           , Job openings, like resignations, have also lingered near record highs, helping fuel workers' confidence in finding new gigs elsewhere.                                                                                                                                                                                                                          , There were 11.3 million job openings in February — essentially unchanged from January and down slightly from December's record of more than 11.4 million.                                                                                                                                                                                                       , Job openings reflect employer demand for workers and tend to move up and down with resignations, Zhao said.                                                                                                                                                                                                                                                     , The layoff rate — a measure of layoffs relative to the overall level of employment — also remains near historic lows, at 0.9% in February.                                                                                                                                                                                                                      , The layoff rate has been at or under 1% for the past year. It hadn't previously touched 1% since record keeping started in 2000.                                                                                                                                                                                                                                , Meanwhile, 202,000 people filed a new claim for unemployment benefits last week, the Labor Department said Thursday. That trend is below the historical average, said Robert Frick, corporate economist at Navy Federal Credit Union.                                                                                                                           , The U.S. unemployment rate fell to 3.8% in February, its lowest level since February 2020. The Labor Department is issuing its March jobs report on Friday.                                                                                                                                                                                                     , These data points — "quits," job openings, layoffs and benefits — reflect a job market that's been strong for workers.                                                                                                                                                                                                                                          , Employer demand for labor picked up steam in the spring and early summer 2021, as Covid-19 vaccines started rolling out broadly in the U.S. and the economy began emerging from its pandemic hibernation.                                                                                                                                                       , That high demand has outpaced the ready supply of workers, and businesses have raised wages at their fastest clip in years to compete for talent. Others have expanded their hiring pool.                                                                                                                                                                       , "There is a brutal battle for lower-skilled employees occurring," Ron Hetrick, senior economist at Emsi Burning Glass, a job market analytics firm, said. "Companies that usually require college degrees are starting to drop those requirements, meaning they're now entering into the fray to find the same worker that other companies have trouble hiring.", Most people who quit are switching jobs rather than leaving the labor force altogether, according to Nick Bunker, an economist at job site Indeed. The number of people hired in February exceeded resignations by about 2.3 million people, the Labor Department said.                                                                                         , However, there are signs the Great Resignation trend may have topped out at the end of 2021. Resignations and job openings seem to be plateauing, a sign that employer demand may wane throughout 2022, Zhao said.                                                                                                                                              , The Federal Reserve, the U.S. central bank, started raising its benchmark interest rate in March (which will raise borrowing costs for companies and households). The Fed is aiming to cool off the economy and rein in inflation, which is running at a 40-year high. The war in Ukraine may also have dampening effect on the economy.                        , "It's possible that with the benefit of hindsight, we'll say December 2021 was the peak of employer demand in this cycle, before rate hikes, geopolitical uncertainty and other risk factors slowed the economy," Zhao said.                                                                                                                                    , "[But] as long as employer demand remains high, I fully expect the Great Resignation to continue," he added.                                                                                                                                                                                                                                                    , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                          , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                          , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                              , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/angola/interest-rate </td>
   <td style="text-align:left;"> 2022-04-01 01:12:00 </td>
   <td style="text-align:left;"> Angola Holds Interest Rate at 20% </td>
   <td style="text-align:left;"> The National Bank of Angola kept its benchmark policy rate at 20% during its regular meeting on March 31st 2022. The decision is aimed at maintaining prudence and stability in the conduct of monetary policy as risks and uncertainties associated with the internal and external economic context prevails despite the domestic inflation slowing down amid lower food prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2022-04-01 00:50:00 </td>
   <td style="text-align:left;"> Dollar Bounces Off One-Month Lows </td>
   <td style="text-align:left;"> The dollar recovered from its lowest level in a month to consolidate above the 98 neighbourhood amid some safe-haven demand stemming from the lack of progress in Russia-Ukraine peace negotiations. Investors are now closely watching the nonfarm payroll report on Friday, which could pave the way for the US Federal Reserve's policy stance. On top of a very tight job market, inflation is currently running at 40-year highs, which, in turn, led to bets of a 50-bps hike in May. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/03/31/stocks-making-the-biggest-moves-midday-walgreens-amd-dell-and-more.html </td>
   <td style="text-align:left;"> 2022-04-01 00:39:21 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Walgreens, AMD, Dell and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                               , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                                                                                   , Walgreens — The drug store chain fell about 5% after the company reported its quarterly results. Despite recording a beat on earnings, it did not raise its forecast for the year The company's president said on its earnings call Thursday that demand for Covid testing has slowed since January, and it could take time for its healthcare investments to pay off.        , Baidu — Shares for the tech company tumbled roughly 7%. Baidu was added to the Securities and Exchange Commission's list of U.S.-traded China stocks that could be delisted should the internet search company fail to disclose financial audits to U.S. regulators.                                                                                                          , AMD — The chipmaker lost 7.1% after Barclays downgraded the stock to equal-weight and lowered its price target from $148 to $115. The bank cited "cyclical risk across several end markets," including PC and gaming as contributors to the downgrade.                                                                                                                        , Dell Technologies and HP — Shares of the computer equipment companies fell after Morgan Stanley downgraded Dell to equal-weight and HP to underweight. The bank cited ongoing macro uncertainty and a "cautious hardware outlook" among the reasons for the downgrade. Dell fell 5.4%, while HP shed 5%.                                                                      , PVH — Shares of the Calvin Klein parent fell 6.4% after Morgan Stanley downgraded the stock to equal-weight from overweight. "Expect the stock to remain range-bound for now," the firm said.                                                                                                                                                                                 , Amylyx Pharmaceuticals — The stock lost 13.5% after a Food and Drug Administration panel voted to not recommend the approval of an experimental ALS drug developed by Amylyx. The panel said study data failed to prove that the drug was effective in fighting the disease.                                                                                                  , Occidental Petroleum — Shares rallied about 2% after CEO Vicki Hollub purchased 14,191 of her own company's shares. The moves come after Warren Buffett's recent buying spree in the outperforming energy stock.UBS — The bank's stock rose 1.2% after Goldman Sachs initiated UBS with a buy rating. Goldman said the rise of fintech is a positive for the banking industry., — CNBC's Tanaya Macheel, Sarah Min and Samantha Subin contributed reporting                                                                                                                                                                                                                                                                                                   , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                        , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                        , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                              , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                              , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                            , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-04-01 00:35:02 </td>
   <td style="text-align:left;"> South African Stocks End Flat, Post Monthly Loss </td>
   <td style="text-align:left;"> The JSE FTSE All Share index ended virtually unchanged at 75,497 in a choppy session on Thursday, as traders continued to monitor developments around the conflict in Ukraine, while also trying to assess the outlook for inflation and growth. Locally, Finance Minister Enoch Godongwana told lawmakers that South Africa will temporarily cut the general fuel levy by 1.5 cents a litre until end-May, as part of emergency interventions to help cushion consumers from high domestic fuel prices. Recent data showed producer price inflation in South Africa accelerated to 10.5% in February, above market expectations, boosted by fuel prices. On the business front, miner Northam Platinum posted a 60% jump in half-year profit, as firmer platinum group metal prices helped offset a dip in metal production caused by work stoppages and Covid-19 absenteeism. The JSE booked a 0.8% loss in March, the first decline since September 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/wheat </td>
   <td style="text-align:left;"> 2022-04-01 00:34:00 </td>
   <td style="text-align:left;"> Wheat Jumps After Report Shows Lower US Stockpiles </td>
   <td style="text-align:left;"> Chicago wheat skyrocketed to above $10.6 per bushel before bottoming around the $10.3 level after a government report showed stockpiles were much lower than expected in the US, the world’s biggest exporter. Wheat stored in all positions on March 1, 2022, totalled 1.025 billion bushels, down 22% from a year ago and below market expectations of 1.045 billion bushels, the US Department of Agriculture said. Still, wheat prices remained well below 14-year highs of $12.4 per bushel after the war in the region interrupted shipping from the Black Sea. New data indicated that India, the world’s second-largest producer, could set a record amount of wheat exports in the coming year, while improved conditions for Kansas winter wheat to be harvested soon also led to higher supply prospects. In March, the commodity rallied almost 15% and is now on track for a second consecutive monthly gain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-04-01 00:24:00 </td>
   <td style="text-align:left;"> UK Stocks Snap 2-Session Rally </td>
   <td style="text-align:left;"> The FTSE 100 ended 0.83% lower to close at 7515.68 on Thursday amid fears of a slowdown of global growth, the war in Ukraine and surging inflation. Drags were led by consumer staples with Unilever, British American Tobacco, Diageo falling the most. Among the individual stocks, British advertising agent S4 Capital plunged more than 6% after pulling the publication of its results due to an auditing delay. Energy giants like BPL and Shell ended 1.9% and 0.1% respectively tracking weaker crude oil prices. On the other hand, British wealth manager Quilter gained 2.2%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/lifestyle/electric-cars-searches-gas-prices </td>
   <td style="text-align:left;"> 2022-04-01 00:21:25 </td>
   <td style="text-align:left;"> Gas prices driving 173% increase in searches for electric cars </td>
   <td style="text-align:left;"> Here are your FOX Business Flash top headlines for March 31.                                                                                                                                                                                                                                                                                                                                                                                                              , Searches for electric vehicles skyrocketed in March as prices at the gas pump remain elevated nationwide, according to a new report.                                                                                                                                                                                                                                                                                                                                      , From Feb. 24 to March 25, searches for electric vehicles on Cars.com increased more than 170% as gas prices reached record highs, according to the automotive website.                                                                                                                                                                                                                                                                                                    , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                   , "The war in Ukraine, proposed infrastructure legislation, rising gas prices and supply-chain issues are just a few drivers of market volatility that have spurred consumer interest in EVs," according to Cars.com.                                                                                                                                                                                                                                                       , A Tesla electric car is seen parked at a charging station in Altamonte Springs, Florida on January 20, 2019.  ( Paul Hennessy/NurPhoto via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                   , As of Thursday, the national average for a gallon of gasoline is at an elevated $4.22. Prices stabilized over the weekend after continuously rising since the beginning of the year due to strained supply and increased demand, according to Edmunds.                                                                                                                                                                                                                    , Consumers were already reeling at the pump even before the war compounded the issue, driving oil prices even higher. For instance, two-thirds of Americans said gas prices were already too expensive even when the national average hit $3.53 per gallon earlier this year, according to a recent AAA survey. Over half of motorists, 59%, admitted that if prices hit $4 a gallon, they would make changes to their driving habits or lifestyle, according to the data. , Although electric vehicles have been gaining popularity, with searches for them nearly doubling since last year, that doesn't mean consumers are buying them, according to Cars.com.                                                                                                                                                                                                                                                                                      , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                               , Purchases for electric cars "still lag due to extremely limited supply and several barriers to entry, with EVs constituting less than 1% of vehicles on the road," according to the report.                                                                                                                                                                                                                                                                               , Jenni Newman, Cars.com editor-in-chief, said that "automakers need to ramp up production, but until the supply-chain shortages level out, the extreme lack of available EVs can’t keep up with the growing demand in the current market."                                                                                                                                                                                                                                 , Gas prices in Westchester are above $6 as prices at the pump continue to rise across the Southland on Sunday, March 13, 2022, in Los Angeles, CA. (Jason Armond/Los Angeles Times via Getty Images / Getty Images)                                                                                                                                                                                                                                                        , Newman said this may eventually change with nearly 50 new models hitting the market in 2025.                                                                                                                                                                                                                                                                                                                                                                              , AVERAGE GAS PRICES COULD FALL UNDER $4 IN COMING WEEKS, EXPERT SAYS                                                                                                                                                                                                                                                                                                                                                                                                       , Currently, consumers in California, Florida, Texas and Illinois have the "strongest interest" for such cars, according to the report.                                                                                                                                                                                                                                                                                                                                     , Georgia, Virginia, Pennsylvania and Arizona do not even have enough supply to keep up with increasing demand, according to the automotive website.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/stock-market </td>
   <td style="text-align:left;"> 2022-04-01 00:19:00 </td>
   <td style="text-align:left;"> Russian Stocks Surge as Trading Hours Normalize </td>
   <td style="text-align:left;"> The MOEX Russia Index surged 7.6% to close at 2,703 on Thursday, extending yesterday’s rebound in the exchange’s first full day of trading since Russia’s invasion. During the session, President Putin signed a decree stating that foreign purchases of LNG can only be made with rubles as of April 1st, a move that Western leaders outright rejected, while Germany already activated an emergency plan that could lead to energy rationing. Still, Gazprom shares closed 12.3% higher. Financial stocks also ended in the green, driven by VTB (15.4%) and Sberbank (6.8%), while shares from online retailer Ozon (33.2%) surged after the US removed its subsidiary bank from the list of sanctioned institutions. The central bank allowed short sales of certain securities for clearing members, but it remained prohibited for brokers’ clients. The exchange is amid a gradual reopening of its financial markets following a preventive shutdown that lasted a month to keep Russian assets from sustaining steep losses. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-04-01 00:13:00 </td>
   <td style="text-align:left;"> French Stocks Post Worst Quarterly Performance in 2 years </td>
   <td style="text-align:left;"> The CAC 40 extended declines for the second consecutive session and ended 1.21% lower to close at 6659.87. It was the worst quarterly performance since the quarter ended March 2020, amid fears of a slowdown in global growth, the war in Ukraine and surging inflation. Drags were led by banks and capital goods with 35 out of 40 stocks ending in the red. Among the individual stocks, Worldline SA, payment leader fell the most (-6.65%) after Apple announced plans to develop its own technology in payment services and infrastructure. On the other hand, Pernod Ricard took the lead with a gain of 1.17 % amid a greater than expected performance outlook from Citi. Elsewhere, Capgemini booked 1.1% gain after Credit Suisse started covering the stock with an “outperformance” recommendation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60938730?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-04-01 00:11:46 </td>
   <td style="text-align:left;"> Energy websites crash in meter readings rush </td>
   <td style="text-align:left;"> Energy websites have been crashing as customers rush to submit meter readings ahead of bills rising on Friday.                                                                                                                                                                                                                                  , A number of major suppliers said they were working to resolve issues with their websites.                                                                                                                                                                                                                                                       , Experts have encouraged people to submit readings so their usage is covered by the current cheaper rates.                                                                                                                                                                                                                                       , On Friday, the energy price cap - the maximum price suppliers in England, Wales and Scotland can charge households - is being raised.                                                                                                                                                                                                           , It means the energy bill of a typical household will increase by 54%.                                                                                                                                                                                                                                                                           , Recording a meter reading prevents suppliers estimating usage and potentially charging for energy used before 1 April at the higher rate.                                                                                                                                                                                                       , Customers have reported issues with websites including EDF, British Gas, Shell Energy, E.On, SSE, Scottish Power, So Energy and Octopus Energy.                                                                                                                                                                                                 , Greg Jackson, chief executive of Octopus Energy, said the company was currently receiving around 40,000 meter readings an hour, whereas a normal day would be a couple of thousand.                                                                                                                                                             , However, he urged people not to panic about submitting a reading before 1 April.                                                                                                                                                                                                                                                                , "I think with most companies, certainly with Octopus, you can give it any time in the next week and... we'll apply it to the day when you took it," he told the BBC's World at One programme.                                                                                                                                                   , Mr Jackson added that he was "pretty sure that'll apply universally".                                                                                                                                                                                                                                                                           , One British Gas customer, Izmir Smajlaj from Streatham, said he had tried for almost two hours to submit a meter reading online.                                                                                                                                                                                                                , "Every time it pops up as an error. The system is probably overloaded with people trying to do the same," he told the BBC.                                                                                                                                                                                                                      , "I tried a laptop, phone, my partner's phone. Tried to reach the British Gas helpline for half an hour then gave up [because] I'm at work."                                                                                                                                                                                                     , Graham Ruddock, a retired civil engineer from Bracknell in Berkshire, said he had been trying to log into his account with E.On Next all morning to enter his meter readings.                                                                                                                                                                   , He told the BBC he had been unable to access his account, instead getting a message advising him to try again later because of "higher than usual levels of traffic".                                                                                                                                                                           , Graham said his gas and electricity bill was rising from £80 a month to £200 a month from April, adding that energy price rises would be "the biggest single change in my finances".                                                                                                                                                            , In response to one customer who complained they were unable to submit a meter reading online, E.On Next, in a now deleted tweet, blamed consumer expert Martin Lewis for creating "unprecedented demand bringing down Britain".  Mr Lewis had urged his social media followers to submit meter readings ahead of 1 April when prices will rise. , E.On later apologised for the tweet, saying it was "an ill-considered and off-the-cuff remark made by one of our energy specialists and in no way reflects our position".                                                                                                                                                                       , "We can confirm to our customers that any meter readings they take today can be updated to their account online in the coming days," a spokeswoman said.                                                                                                                                                                                        , Citizens Advice said firms should have been better prepared for a surge of customers submitting readings.                                                                                                                                                                                                                                       , The charity's head of energy policy, Gillian Cooper, said the situation was "frustrating" for customers worried about how they will cope with rising bills.                                                                                                                                                                                     , However, energy companies said they were seeing unprecedented traffic to their websites.                                                                                                                                                                                                                                                        , A message on the British Gas website said it was facing "some technical issues we're trying to resolve as quickly as possible".                                                                                                                                                                                                                 , It said customers could still submit readings, but warned it could take "a little time to update your account with the meter reading you provided today".                                                                                                                                                                                       , A Scottish Power spokesman said: "We are aware of an issue some of our customers are facing trying to log their meter readings on our website and are working to have the issue resolved as quickly as possible."                                                                                                                               , He added that customers could still log meter readings on the company's app, which was still working.                                                                                                                                                                                                                                           , A spokesman for EDF said it was aware of technical issues affecting its website and app when customers tried to submit meter readings.                                                                                                                                                                                                          , "We are working hard to try and resolve this and would encourage customers to try again later and apologise for the inconvenience this is causing," he said.                                                                                                                                                                                    , A spokesman for Shell Energy said: "Our website is experiencing disruption as we deal with a surge in the number of customers trying to access their account."                                                                                                                                                                                  , Kevin Parle has been on the run since 2004 - will he ever be brought to justice?                                                                                                                                                                                                                                                                , Louis Theroux on storytelling and the culture wars                                                                                                                                                                                                                                                                                              , Russell Kane tackles the former president's legacy                                                                                                                                                                                                                                                                                              , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/mortgage-rates-surge-highest-since-2018 </td>
   <td style="text-align:left;"> 2022-04-01 00:10:57 </td>
   <td style="text-align:left;"> Mortgage rates surge to highest since 2018 </td>
   <td style="text-align:left;"> Fox Business’ Gerri Willis discusses how the increase in home prices and decrease in inventory have deterred many homebuyers from purchasing on ‘The Claman Countdown.’                                                                                                                                                                                                                                                                                                   , The average rate for a 30-year fixed-rate loan jumped to 4.67%, mortgage-finance giant Freddie Mac said Thursday, marking the weekly figure’s highest reading since December 2018.                                                                                                                                                                                                                                                                                        , FILE - Newly finished development of homes for sale, built by home builder KB Homes, are pictured in Carlsbad, California. (REUTERS/Mike Blake) (REUTERS/Mike Blake / Reuters Photos)                                                                                                                                                                                                                                                                                     , The 30-year fixed rate rose from 4.42% a week ago, continuing a steady rise that has pushed home-loan rates within sight of 5% for the first time in four years. This year’s surge in mortgage rates was hardly unforeseen, given the record lows reached in the pandemic period and concerns about high U.S. inflation readings, but it has unfolded faster than expected. At the beginning of the year, the average rate on America’s most popular home loan was 3.22%. , HOME PRICES UNEXPECTEDLY RISE 19.2% IN JANUARY: CASE-SHILLER                                                                                                                                                                                                                                                                                                                                                                                                              , Higher mortgage rates typically slow home buying activity, but the number of applications submitted by hopeful home buyers has risen for three of the past four weeks, according to the Mortgage Bankers Association, showing the U.S. home boom is far from over.                                                                                                                                                                                                        , (AP Photo/Michael Conroy, File) (AP Photo/Michael Conroy / AP Newsroom)                                                                                                                                                                                                                                                                                                                                                                                                   , "It’s going to take a pretty healthy increase in rates to moderate the demand," said Phil Shoemaker, president of originations at Homepoint Financial Corp., a Michigan-based mortgage lender.                                                                                                                                                                                                                                                                            , HOUSING MARKET ‘STARING INTO FACE OF PERFECT STORM,’ EXPERT WARNS                                                                                                                                                                                                                                                                                                                                                                                                         , Expectations that the Federal Reserve will raise interest rates several more times this year to control inflation are driving up mortgage rates. Before the central bank raised rates for the first time since 2018, the Fed’s decision to unwind its purchases of mortgage-backed securities had started forcing rates upward.                                                                                                                                           , A man walks past open house signs in front of condominiums for sale in Santa Monica, California. REUTERS/Lucy Nicholson (REUTERS/Lucy Nicholson / Reuters Photos)                                                                                                                                                                                                                                                                                                         , Home prices continue to push homeownership out of the question for many Americans. The median sales price of an existing home rose 15% in February from a year earlier.                                                                                                                                                                                                                                                                                                   , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                               , Rising rates are reducing refinances, which powered much of the mortgage market’s boom in 2020 and 2021. About four million Americans could lower their monthly mortgage payments through a refinancing in February, down from close to 16 million a year ago, according to mortgage-data firm Black Knight Inc. Refinancings are expected to make up 33% of mortgage originations this year, down from 59% in 2021, according to the Mortgage Bankers Association. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-04-01 00:10:00 </td>
   <td style="text-align:left;"> Ibex Ends Lower, Posts Monthly Loss </td>
   <td style="text-align:left;"> The Ibex 35 amplified losses and ended 1.2% down at 8,445 on Thursday, mainly dragged down by a 5% slump in shares of fashion retailer Inditex, tracking its Swedish counterpart H&amp;M, which plunged over 10% after reporting a smaller than expected profit for its fiscal first quarter. Almirall and Pharmamar also declined significantly. Meanwhile, market sentiment continued to be dominated by concerns over the economic impact of a prolonged war on inflation and growth. The index lost 0.4% in March, the third consecutive month of decreases. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/bidens-us-oil-production-progressives-climate-advocates </td>
   <td style="text-align:left;"> 2022-04-01 00:08:32 </td>
   <td style="text-align:left;"> Biden's pivot on US oil production draws ire from progressives, climate advocates </td>
   <td style="text-align:left;"> Trucking Association of New York President Kendra Hems argues smaller carriers, which she says account for 91% of fleets across the country, are feeling the 'pinch' the most.                                                                                                                                                                                                                                                , President Biden's plan to ramp up liquefied natural gas shipments to Europe to help the continent ween itself off Russian energy won applause from the oil and gas industry, but risks drawing the ire of progressives who want the White House to focus on combating climate change.                                                                                                                                         , The Biden administration announced last week that it will work with international partners to supply at least 15 billion cubic meters of extra LNG supplies to Europe this year. Members of the European voting bloc also committed to receiving 50 billion cubic meters of American fuel until at least 2030 – part of a broader plan to reduce their reliance on Russia, which accounted for 40% of gas shipments last year., BIDEN ADMINISTRATION TO RELEASE 1M BARRELS OF OIL DAILY FROM US RESERVES                                                                                                                                                                                                                                                                                                                                                      , "We’re coming together to reduce Europe’s dependence on Russian energy," Biden said during a joint press conference with European Commission President Ursula von der Leyen.                                                                                                                                                                                                                                                  , But environmental activists and progressives have accused Biden of backpedaling on his campaign promises to "confront the existential threat of climate change."                                                                                                                                                                                                                                                              , Oil futures rose on Tuesday morning, following a volatile start to the week, as the market weighed a coordinated international release of crude inventories against Russian supply disruptions in the wake of Moscow's invasion of Ukraine. (Photo by Mario Tama/Getty Images / Getty Images)                                                                                                                                 , Peggy Shepard, a co-founder and executive director at We Act for Environmental Justice, said it was time for the White House to move away from fossil fuels – including halting LNG exports and infrastructure expansion. She said that soaring oil and gasoline prices only prove that the U.S. needs to focus on green energy initiatives.                                                                                  , "Building even more LNG export terminals would lock in fossil fuel infrastructure and pollution for decades to come," Shepard said.                                                                                                                                                                                                                                                                                           , Although Biden previously called for transitioning away from fossil fuels – including eliminating greenhouse gases from power plants by 2035 – he has fully embraced fossil-fuel expansion in an effort to punish Moscow over its invasion of Ukraine one month ago.                                                                                                                                                          , White House national climate adviser Gina McCarthy has acknowledged that Europe’s current energy needs have taken precedence over climate goals in the short term. Asked by Bloomberg how the White House was balancing the two, she said: "We’re actually not balancing right now."                                                                                                                                          , U.S. President Joe Biden speaks on the economy in the Eisenhower Executive Office Building in Washington, D.C., U.S., on Tuesday, Nov. 23, 2021.  (Oliver Contreras/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                                , "Right now, we’re working on an emergency problem that the EU and we have on energy prices and security," McCarthy said on the sidelines of a renewable energy summit in Washington, per Bloomberg. "But our goals remain the same – and that’s clean energy."                                                                                                                                                                , Still, the White House has maintained that the new LNG import terminals and pipelines will be constructed with greenhouse gas emissions reductions in mind, including relying on clean energy to power operations, reducing methane leakage and building "clean and renewable hydrogen-ready infrastructure."                                                                                                                 , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                   , Activists say the president needs to go further and follow through on his campaign pledges.                                                                                                                                                                                                                                                                                                                                   , "President Biden campaigned on bold and ambitious goals to tackle the climate crisis and environmental injustice," Kelly Sheehan, the Sierra Club’s director of energy campaigns, told Bloomberg News. "Supporting the push to expand gas exports and lock in decades of fossil fuel production is directly in conflict with these goals."  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-03-31 23:58:27 </td>
   <td style="text-align:left;"> Italian Stocks End Lower </td>
   <td style="text-align:left;"> The FTSE MIB index closed 1.1% lower at 25,021 on Thursday, pressured by stocks linked to raw materials as investors weighed on the economic consequences of Russia only accepting gas payment in rubles, while digesting a batch of economic data. Surging energy and commodity prices have already led the Italian government to slash its 2022 growth forecasts to 2.8% from 4.7% and heavily subsidize energy bills. In Milan, Telecom Italia (-7.1%) plunged after reports from Financial Times indicated the telecom is considering to spin off its fixed network assets, while investors still await the firm’s decision regarding CVC’s €6 billion proposal for a stake in the newly created enterprise services business and KKR’s €33 billion takeover bid. On the data front, Italy’s inflation rate for March came at a higher than expected 31-year high of 6.7%, while the unemployment rate for February was at a 22-month low of 8.5%. The index closed the month of March with a decline of 1% and fell 8.5% in Q1. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-03-31 23:56:00 </td>
   <td style="text-align:left;"> European Stocks Post Worst Quarter Since 2020 </td>
   <td style="text-align:left;"> Main bourses in Europe ended the last trading day of March and the first quarter on a weak note, with the pan-European STOXX 600 bottoming around the 450 level but recording a monthly gain of almost 1% for March. Growth in the euro area has deteriorated significantly as inflation challenges intensify on the heels of the ongoing Russia-Ukraine conflict. Recent data showed that the eurozone consumer sentiment posted the second sharpest decline ever while companies' output expectations collapsed. In the meantime, ECB President Christine Lagarde said that the central bank could end its bond-buying stimulus scheme in the third quarter amid record inflationary pressures. As a result,  the European blue-chip index ended the first quarter of 2022 more than 6% lower, its worst three-month period since 2020. The benchmark DAX 30 closed down around 14,400 and posted its third consecutive monthly decline. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/zambia/inflation-cpi </td>
   <td style="text-align:left;"> 2022-03-31 23:49:00 </td>
   <td style="text-align:left;"> Zambia Inflation Rate at Over 2-Year Low </td>
   <td style="text-align:left;"> Zambia's annual inflation rate decelerated for the eighth straight month to 13.1% in March of 2022, from 14.2% in the previous month. It was the lowest reading since January of 2020, amid a slowdown in prices of both food (15.3% vs 16% in February) and non-food products (10.3% vs 11.8%). On a monthly basis, consumer prices were up 0.8%, slowing from a 1.7% rise in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/us-energy-secretary-critical-not-to-rely-on-oil-gas-from-other-countries </td>
   <td style="text-align:left;"> 2022-03-31 23:47:59 </td>
   <td style="text-align:left;"> US energy secretary: ‘Critical’ not to rely on oil, gas from other countries </td>
   <td style="text-align:left;"> FOX Business' Edward Lawrence reports from the White House, where President Biden is tapping into the nation's oil reserve to better control high gas prices.                                                                                                                                                                                                                                                           , As President Biden readies a plan to release one million barrels of oil a day from the nation’s oil reserve, U.S. Energy Secretary Jennifer Granholm stressed the importance of energy independence Thursday in a FOX Business interview.                                                                                                                                                                               , "We know that it is critical for us to make sure that we are not reliant on fuels from other countries, for example, oil and gas," Granholm told  Edward Lawrence.                                                                                                                                                                                                                                                      , The administration’s decision to pump from the national emergency supply for a 180-day period would put the Strategic Petroleum Reserve at its lowest levels since 1984.                                                                                                                                                                                                                                                , Acknowledging it’s a short-term solution, Granholm claimed the best way to get oil prices down is to speed up the switch from fossil fuels.                                                                                                                                                                                                                                                                             , BIDEN RESTRICTING U.S. OIL, GAS DRILLING A JOBS, SUPPLY KILLER: AMERICAN PETROLEUM INSTITUTE VP                                                                                                                                                                                                                                                                                                                         , "That's one of the reasons why we would like to see a greater push in the U.S. toward electric vehicles and reduce the cost of those electric vehicles," Granholm said.                                                                                                                                                                                                                                                 , Biden has no plans to change the administration’s policies and regulations related to the industry, the energy secretary added.                                                                                                                                                                                                                                                                                         , Secretary of Energy Jennifer Granholm (Drew Angerer/Getty Images)                                                                                                                                                                                                                                                                                                                                                       , This marks the third time since November that Biden has tapped into the petroleum reserve. Other steps the White House has taken to lower gas prices include asking OPEC to increase production and requesting the Federal Trade Commission to open an investigation into alleged price-gouging.                                                                                                                        , Officials are now putting the blame on oil companies, calling executives to testify in front of the House Energy Committee next week.                                                                                                                                                                                                                                                                                   , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                             , American Petroleum Institute Senior Vice President Frank Macchiarola detailed the difficult environment Biden has created for the industry on "Mornings with Maria" early Thursday, setting the tone for how oil execs are likely to respond.                                                                                                                                                                           , American Petroleum Institute Senior Vice President Frank Macchiarola argues the Biden administration needs to end restrictions on U.S. oil production.                                                                                                                                                                                                                                                                  , "If the administration really wants to be strategic here, they'll promote the production of oil and gas in the United States through development on federal lands and waters. They'll stop restricting access to pipeline infrastructure. They'll cancel these proposals to increase taxes on American producers," Macchiarola noted. "Those are the things that are going to provide relief for Americans at the pump.", READ MORE FROM FOX BUSINESS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/government-bond-yield </td>
   <td style="text-align:left;"> 2022-03-31 23:45:00 </td>
   <td style="text-align:left;"> India 10Y Bond Yield Rises </td>
   <td style="text-align:left;"> India 10Y Bond yield rose to 6.84%, the highest in 2 weeks after the Reserve Bank of India announced to auction USD 112 billion dollars of bonds or 59% of the full year target, in the first half of the fiscal year starting April 1st, in line with past years amid a global bond rout and persisting Russia-Ukraine tensions.  Despite the rise in domestic inflation and potential inflationary pressures from surging crude oil prices, the Reserve Bank of India kept interest rate at a record low of 4% since March 2020 in contrast to hawkish stances by major global central banks including the Fed and the BoE. Meanwhile, traders now await the RBI’s next monetary policy decision due April 8th to gauge how long the RBI continues its accommodative stance amid price pressures and how it can support the bond market, with having limited scope for bond purchases as it soaks up excess liquidity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/kenya/inflation-cpi </td>
   <td style="text-align:left;"> 2022-03-31 23:27:00 </td>
   <td style="text-align:left;"> Kenya March Inflation Rate Hits 3-Month High </td>
   <td style="text-align:left;"> The annual inflation rate in Kenya accelerated to a three-month high of 5.56% in March of 2022, from 5.08% in the previous month. Main upward pressure came from prices of food &amp; non-alcoholic beverages (9.92% vs 8.69%), namely cooking oil (35.15%) and wheat flour (17.68%), amid the effects of the war in Ukraine. Inflation also accelerated for furnishings (6.44% vs 5.41%) and housing &amp; utilities (4.91% vs 4.79%), on account of prices of gas (38.18%). On a monthly basis, consumer prices inched up 0.85%, following a 0.4% rise in the prior month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/small-business-sentiment </td>
   <td style="text-align:left;"> 2022-03-31 23:22:21 </td>
   <td style="text-align:left;"> Canada Small Business Morale at 7-Month High </td>
   <td style="text-align:left;"> Canada's CFIB's Business Barometer long-term index, based on a 12-month business outlook, rose by 2 points to 65.1 in March of 2022. Long-term optimism saw significant increases in Central Canada (Ontario at 67.2), Eastern Canada (Nova Scotia at 66.7 and PEI at 64.6), as well as Western Canada (Alberta at 62.1). The general business health indicator remained positive, with 34% of business owners reporting good business health, while price or wage increases have seen small upward movements. Still, fuel and energy prices have seen the most significant upwards trend reaching 72%. Meantime, the short-term index, based on a 3-month outlook, gained 6 points to 60.2, the highest level since pre-pandemic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/31/energy/russia-gas-ruble-standoff/index.html </td>
   <td style="text-align:left;"> 2022-03-31 23:16:51 </td>
   <td style="text-align:left;"> Russia raises stakes in energy standoff by insisting on rubles for gas - CNN </td>
   <td style="text-align:left;"> London/Paris (CNN Business)Russia has doubled down on its threat to cut off natural gas supplies to Western countries that refuse to pay in rubles, raising new concerns about an energy supply crunch and rationing in Europe.                                                                                                                        , Moscow said last week it wanted to be paid in rubles, rather than US dollars or euros, and senior Russian lawmakers said supplies could be cut if customers refused. Germany, Russia's biggest energy customer in Europe, had described the plan as "blackmail" and a breach of contract.                                                              , President Vladimir Putin signed a decree Thursday that requires buyers of natural gas from "unfriendly countries" to hold accounts at Gazprombank — Russia's third-largest bank — and settle contracts in rubles. It takes effect on Friday.                                                                                                           , "If these payments are not made, we shall deem this as non-performance on the part of the buyers and that will lead to consequences," Putin said in a televised address. "Nobody gives us anything for free and we're not about to be charitable," he added.                                                                                           , Putin had given the Russian central bank and state-owned gas giant Gazprom until Thursday to come up with detailed proposals to switch the payment currency for gas to rubles.                                                                                                                                                                         ,                                                                                                                                                                                                                                                                                                                                                        , According to the decree, Gazprombank would open accounts on behalf of Western gas buyers, purchase rubles on their behalf and then transfer the cash to Gazprom's accounts.                                                                                                                                                                            , Europe's leading economies rejected any change to the terms of existing supply agreements, and said they were prepared for all scenarios including disruption to flows of natural gas.                                                                                                                                                                 , "The contracts are in euros and must be paid in euros and will be paid in euros," French finance minister Bruno Le Maire said during a joint press conference with his German counterpart Robert Habeck. "We will not accept the method of payment for [Russian] gas in any other currency than stated in the contract," Le Maire added.               , German Chancellor Olaf Scholz also said that Berlin will make payments for Russian gas only in euros.                                                                                                                                                                                                                                                  , "We have looked at the contracts on gas delivery and other deliveries. [The contracts state] that payments are to be made in euros, sometimes in US dollars, but mostly in euros. And I made clear in my conversation with the Russian president that this will remain as it is," Scholz told reporters in Berlin.                                     , A spokesperson for UK Prime Minister Boris Johnson said Britain wouldn't accept Putin's demand. Energy Secretary Kwasi Kwarteng had made it clear that "this is not something that the UK would be looking into," the spokesperson added.                                                                                                              , The German government on Wednesday activated a three-stage plan for managing gas reserves in a crisis, issuing an "early warning" of possible shortages. The gas crisis plan could lead to rationing if supplies are significantly disrupted, with major industrial customers hit first to protect households, hospitals and other essential services. , Habeck said that the country had enough gas for now, but he urged all consumers to reduce their use as far as possible with immediate effect, an appeal repeated by other governments in Europe.                                                                                                                                                       ,                                                                                                                                                                                                                                                                                                                                                        , The European Union depends on Russia for about 40% of its natural gas. EU leaders have set a target of reducing consumption of Russian gas by about 66% by the end of this year and are scrambling to find alternative sources, including extra shipments of liquified natural gas from the United States.                                             , Experts say disruption to European gas supplies is now more likely, but not inevitable.                                                                                                                                                                                                                                                                , "Neither Gazprom nor the Kremlin appear eager to shut off Russia's large export earnings from gas," analysts at Eurasia wrote in a note on Wednesday. "Rather, the ruble payments scheme is instead seen in Russia as a way to boost demand for rubles by converting more of those export earnings into Russian currency."                             , Still, any move by Moscow to halt or largely curtail deliveries would deliver a huge shock to the region. Germany, the region's biggest economy, is already at risk of a recession as factories struggle with soaring energy costs.                                                                                                                    , — Inke Kappeler, Niamh Kennedy and Anastasia Graham Yooll contributed to this article.                                                                                                                                                                                                                                                                 , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-targets-russian-tech-sector/story.aspx?guid={BFFA0219-72CD-4605-A225-A3D2FD258F19}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-31 23:15:55 </td>
   <td style="text-align:left;"> U.S. targets Russian tech sector in latest round of sanctions over Ukraine invasion - MarketWatch </td>
   <td style="text-align:left;"> The U.S. is targeting Russia's technology sector in the latest round of sanctions aimed at punishing Moscow over its invasion of Ukraine. The Treasury's Office of Foreign Assets Control said Thursday it is targeting operators in the sector "to prevent it from evading unprecedented multilateral sanctions and procure critical western technology." Treasury is designating 21 entities and 13 individuals as part of its crackdown, it said in a news release. Among the tech companies sanctioned is Joint Stock Company Mikron, the largest Russian manufacturer and exporter of microelectronics.  ,  Russian troops handed control of the Chernobyl nuclear power plant back to the Ukrainians and left the heavily contaminated site early Friday, more than a month after taking it over, Ukrainian authorities said, as fighting raged on the outskirts of Kyiv and other fronts.                                                                                                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Robert Schroeder is the Washington bureau chief for MarketWatch. Follow him on Twitter @mktwrobs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/belgium/current-account </td>
   <td style="text-align:left;"> 2022-03-31 23:14:25 </td>
   <td style="text-align:left;"> Belgium Current Account Swings to Deficit in Q4 </td>
   <td style="text-align:left;"> Belgium recorded a current account deficit of EUR 6,249 million in the fourth quarter of 2021, swinging from a EUR 0.438 million surplus in the corresponding period of the previous year. It was the first current account deficit since the second quarter of 2019 and the highest since the second quarter of 2015. The goods account recorded a deficit of EUR 4.761 million, swinging from the gap of EUR 1.607 million. Also, the services gap widened to EUR 0.910 million from EUR 0.243, million while the primary income deficit narrowed to EUR 0.671 million from EUR 1.066 million. On the other hand, the secondary income gap narrowed to EUR 1.251 million from EUR 1.993 million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/energy/kremlin-decree-foreign-currency-can-still-buy-natural-gas </td>
   <td style="text-align:left;"> 2022-03-31 23:13:32 </td>
   <td style="text-align:left;"> Kremlin decree: Foreign currency can still buy natural gas </td>
   <td style="text-align:left;"> Here are your FOX Business Flash top headlines for March 31.                                                                                                                                                                                                                                                                                                                                                                                                                               , "Unfriendly countries" can continue to pay for natural gas in foreign currency through a Russian bank that will convert the money into rubles, according to a Kremlin decree published by state media Thursday, a day after the leaders of Italy and Germany said they received assurances from President Vladimir Putin.                                                                                                                                                                  , Putin talked tougher, saying Russia will start accepting ruble payments starting Friday for Western countries that imposed sanctions over its conflict with Ukraine. He said contracts will be stopped if buyers don’t sign up to the new conditions, including opening ruble accounts in Russian banks.                                                                                                                                                                                   , RUSSIAN RUBLE MAKES ALMOST FULL RECOVERY DESPITE WESTERN SANCTIONS                                                                                                                                                                                                                                                                                                                                                                                                                         , "If these payments are not made, we will consider it a failure of the buyer to fulfill its obligations, with all the ensuing consequences," Putin said.                                                                                                                                                                                                                                                                                                                                    , The decree Putin signed and published by state news agency RIA Novosti says a designated bank will open two accounts for each buyer, one in foreign currency and one in rubles. The buyers will pay in foreign currency and authorize the bank to sell that currency for rubles, which are placed in the second account, where the gas is formally purchased.                                                                                                                              , Russian President Vladimir Putin attends a meeting with top officials on support to aviation industry in Russia amid western sanctions vis videoconference at the Novo-Ogaryovo residence outside Moscow, Russia, Thursday, March 31, 2022. (Mikhail Klime (AP)                                                                                                                                                                                                                            , Speaking shortly after Putin’s announcement, German Chancellor Olaf Scholz gave a noncommittal initial response to Russia’s new conditions. He said the gas contracts stipulate payment mostly in euros and sometimes in dollars. He said he made clear to Putin in a phone call Wednesday "that it will stay that way."                                                                                                                                                                   , "What his ideas are for how this can happen is what we will now look at closely," Scholz told a reporters in Berlin. "But in any case, what goes for companies is that they want to and will be able to pay in euros."                                                                                                                                                                                                                                                                     , Italian Premier Mario Draghi said earlier Thursday that he had also received assurances from Putin that Europe would not have to pay in rubles and diffused fears that Moscow would cut off supplies of gas used for heating and electricity.                                                                                                                                                                                                                                              , RUSSIA-CHINA HAVE ‘VERY DANGEROUS’ PARTNERSHIP: EXPERT                                                                                                                                                                                                                                                                                                                                                                                                                                     , Draghi said Putin assured him during a 40-minute phone call Wednesday evening that "existing contracts remain in force. ... European companies will continue to pay in dollars and euros."                                                                                                                                                                                                                                                                                                 , Putin announced last week that Russia will demand "unfriendly" countries pay for natural gas only in Russian currency, instructing the central bank to work out a procedure for buyers to acquire rubles in Russia. That sent already high gas prices even higher amid fears it could be a prelude to a natural gas shutoff, which could disrupt Europe’s economy and hurt Russia’s finances. The Group of Seven major economies, including Italy and Germany, agreed to reject the demand., Italian Premier Mario Draghi attends a press conference at the Foreign Press Club in Rome, Thursday, March 31, 2022. (AP Photo/Domenico Stinellis) (AP / AP Images)                                                                                                                                                                                                                                                                                                                        , Draghi said Putin gave a lengthy explanation of how to both maintain the payments in euros and dollars while satisfying Russia’s "indication of payments in rubles."                                                                                                                                                                                                                                                                                                                       , Draghi said he referred the discussion to experts and that analysis was underway "to understand what it means," including whether "European companies can continue to pay as foreseen, if this means something for the ongoing sanctions."                                                                                                                                                                                                                                                 , "The feeling is one I have had since the beginning, that it is absolutely not simple to change the currency of payments without violating the contracts,″ Draghi said.                                                                                                                                                                                                                                                                                                                     , STOCKS LOWER, OIL FALLS AS BIDEN SAYS US WILL RELEASE 1M BARRELS DAILY FROM RESERVES                                                                                                                                                                                                                                                                                                                                                                                                       , Draghi also told the foreign press corps that Europe is pushing for a cap on gas prices with Russia, saying its payments are funding the war in Ukraine and the prices being paid by Europe are out of line with the global market.                                                                                                                                                                                                                                                        , "We — Germany and Italy, along with other countries that are importers of gas, coal, grains, corn — are financing the war. There is no doubt," Draghi said. "For this reason, Italy along with other countries, are pushing for a cap on the price of gas. There is no substantial reason that the price of gas is so high for Europeans."                                                                                                                                                 , Draghi noted that Russia has no other market for its gas, giving Europe room to maneuver. Asked about the risk that Russia would respond by turning off the taps, Draghi said, "no there is no danger."                                                                                                                                                                                                                                                                                    , In this picture taken trough a window, German Chancellor Olaf Scholz waits for the arrival of Austria's Chancellor Karl Nehammer at the chancellery in Berlin, Germany, Thursday, March 31, 2022. (AP Photo/Michael Sohn) (AP / AP Images)                                                                                                                                                                                                                                                 , The prospect of continued gas deliveries in exchange for euros drew a cautious welcome from German industry.                                                                                                                                                                                                                                                                                                                                                                               , "It’s good news at least in the short term, because Russian gas deliveries can’t be replaced in the short term," Achim Dercks, the deputy managing director of the Association of German Chambers of Commerce and Industry, told RBB24 Inforadio on Thursday.                                                                                                                                                                                                                              , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                    , He noted that companies are concerned that any cutoff would affect industry in particular, "but ultimately that would have severe economic effects for us all." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/chile/retail-sales-annual </td>
   <td style="text-align:left;"> 2022-03-31 23:11:24 </td>
   <td style="text-align:left;"> Chile Retail Sales Growth at 1-Year Low </td>
   <td style="text-align:left;"> Retail sales in Chile climbed 11.1 percent year-on-year in February of 2022, the slowest increase since February last year and following a downwardly revised 13.5 percent jump in the previous month. It was the 19th straight month of growth in retail activity in a row. On a monthly basis, retail sales fell 5.0 percent, following an upwardly revised 28.1 percent slump in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/biden-release-more-oil-strategic/story.aspx?guid={B848CFE4-58E3-4306-8E63-19486DD7E9F1}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-31 23:07:16 </td>
   <td style="text-align:left;"> Biden will release more oil from Strategic Petroleum Reserve, White House says - MarketWatch </td>
   <td style="text-align:left;"> President Joe Biden plans to order the release of 1 million barrels of oil per day for the next six months from the U.S. Strategic Petroleum Reserve, senior Biden administration officials told reporters on Thursday. Reports late Wednesday said Biden looked poise to order such a release.       , Whatever happens in Ukraine and in the rest of the world, Russia's fate is sealed: A future as dark as its darkest past                                                                                                                                                                               ,                                                                                                                                                                                                                                                                                                       , Victor Reklaitis is MarketWatch's Money &amp; Politics reporter and is based in Washington, D.C. Prior to joining MarketWatch, he served as an assistant editor and reporter at Investor's Business Daily. Before IBD, he worked for several newspapers in Virginia. Follow Victor on Twitter at: @vicrek. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/biden-invoke-defense-production-act/story.aspx?guid={5494F6E8-2FDB-4AA5-A4EB-F1EF97FF65E4}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-03-31 23:06:01 </td>
   <td style="text-align:left;"> Biden to invoke Defense Production Act for minerals for EV batteries, White House says - MarketWatch </td>
   <td style="text-align:left;"> President Joe Biden on Thursday will announce he's using the Defense Production Act to secure American supplies of the critical materials needed to boost a clean-energy economy, focusing on the procurement of the tools needed to build batteries in the U.S. that will go into electric vehicles, senior Biden administration officials told reporters. Reports on Wednesday had said Biden was considering invoking the Defense Production Act this week to boost domestic production of minerals used in batteries needed for EVs., BlackRock's Robert Kapito says an "entitled" generation that has never had to cope with shortages is about to get a wake-up call.                                                                                                                                                                                                                                                                                                                                                                                                       ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Victor Reklaitis is MarketWatch's Money &amp; Politics reporter and is based in Washington, D.C. Prior to joining MarketWatch, he served as an assistant editor and reporter at Investor's Business Daily. Before IBD, he worked for several newspapers in Virginia. Follow Victor on Twitter at: @vicrek. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/cape-verde/gdp-growth-annual </td>
   <td style="text-align:left;"> 2022-03-31 23:06:00 </td>
   <td style="text-align:left;"> Cape Verde GDP Expands 13.2% YoY in Q4 </td>
   <td style="text-align:left;"> The economy of Cape Verde advanced 13.2 percent year-on-year in the fourth quarter of 2021, following an upwardly revised 9.4 percent expansion in the previous three-month period. It was the fourth consecutive quarter of growth driven by low base effects from the previous year when the pandemic shock led to an unprecedented recession and amid the gradual reopening of economic activity. The main drivers of recovery were manufacturing industries (35.1 percent vs 15.4 percent in Q3), electricity and water (18.1 percent vs 14.9 percent), accommodation and restaurants (1145.9 percent vs 348.5 percent), services (11.8 percent vs 7.7 percent) and public Administration (13.3 percent vs 1 percent). On the demand side, household consumption (27.5 percent vs 16.2 percent) and exports (119.4 percent vs 108.4 percent) were the key growth drivers. Considering the full 2021, the GDP expanded 7 percent on year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-03-31 22:58:00 </td>
   <td style="text-align:left;"> US Natural Gas at 5-Month High </td>
   <td style="text-align:left;"> US natural gas futures gained momentum trade $5.8 per million British thermal units on Thursday, the highest since November 4th, 2021, on expectations of strong overseas demand. Russia’s President Putin signed a decree mandating “unfriendly” nations to pay for natural gas in rubles, to which European leaders strongly refused. US LNG exports are at record highs as Europe tries to replace Russian supplies due to the war in Ukraine. Meanwhile, EIA data showed working gas in storage in the lower 48 US states increased by 26 bcf last week, more than analyst forecasts, as utilities started to rebuild inventories earlier than usual. Still, storage levels remained 16% below the five-year average for this time of year. For the month, the contract was set for a 27% jump. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-03-31 22:56:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index Falls for 6th Day, Posts Monthly Gain </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index went down 0.5% to 2,358 on Thursday, its lowest since March 8th, extending losses for the sixth session, amid weakness in the smaller vessels segments. The panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, decreased about 2.9% to 3,141; and the supramax index dropped 67 points to 2,808. Meanwhile, the capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, surged 6.9% to 1,760, tracking rising iron ore prices. The Baltic Dry Index gained about 6.4% this quarter and 15.6% in March, its second monthly gain this year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/03/31/europe/ukraine-russia-troops-regrouping-intl-cmd/index.html </td>
   <td style="text-align:left;"> 2022-03-31 22:48:53 </td>
   <td style="text-align:left;"> Russia says its military is regrouping. A ramped-up assault on eastern Ukraine could be next - CNN </td>
   <td style="text-align:left;"> Lviv, Ukraine (CNN)Russia's military says it has moved on to a new phase of its so-called "special military operation" in Ukraine, claiming that it is shifting its focus to the Donbas region in Ukraine's east.                                                                                                                                                                                                                                                                                                         , Is this regrouping of forces a feint -- allowing battered Russian forces to regroup after suffering serious losses at the hands of Ukrainian defenders -- or a simple face-saving measure? Is Russia actually moving troops and equipment to concentrate on Ukraine's east, where Moscow has recognized two separatist republics?                                                                                                                                                                                         , On paper, that seems to be the case. Russian Ministry of Defense spokesperson Maj. Gen. Igor Konashenkov said a "planned regrouping of troops" was underway around Kyiv and Chernihiv, one day after Russian negotiators said Moscow's forces would take steps toward de-escalation around those two cities. He said Russian forces were regrouping in order to "intensify operations in priority areas and, above all, to complete the operation for the complete liberation of Donbas."                                 , US officials and military analysts have rightly been skeptical of Russia's claims of de-escalation, and some observers have suggested Russia's shifting military objectives are meant to conceal massive setbacks on the battlefield. But there is evidence that Russian military activity is ramping up in the east: Ukrainian officials on Thursday reported heavy shelling of a number of Ukrainian cities, particularly in the Luhansk and Donetsk regions of the Donbas and around the northeastern city of Kharkiv. , Escalating attacks in eastern Ukraine                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , In a statement on Telegram, Oleh Synyehubov, the head of the Kharkiv region military administration, said: "Over the past day, Russian troops have struck 47 times with artillery, mortar, tank, and strikes in the areas of Piatihatky, Oleksiyivka, and the residential area of the Kharkiv Traсtor Plant district. About 380 shellings from Grad and Smerch [rocket artillery] were recorded. In Saltivka, the enemy damaged the gas pipeline, there was a major fire, and rescuers have worked to localize it."       , Synyehubov said Russian forces had inflicted heavy fire on Derhachi, northwest of the city of Kharkiv, killing one person and injuring three others, and destroying a city council building.                                                                                                                                                                                                                                                                                                                              , "The fiercest point [in Kharkiv region] remains Izium, where fighting and constant shelling continue," he said. "We are working every day to open 'green' [humanitarian] corridors. But so far Russia does not give us such an opportunity."                                                                                                                                                                                                                                                                              , Ukrainian military governors in the Luhansk and Donetsk regions also reported heavy shelling Thursday amid an apparent shift by the Russian military to redirect military efforts to the Donbas region.                                                                                                                                                                                                                                                                                                                   , "We clearly feel that the transfer of [military] technology in our direction is beginning now," said Serhiy Haidai, Head of Luhansk region military administration, in televised remarks. "And as the equipment and personnel are being turned over, our enemies are simply firing more densely, powerfully. Everything is already involved here: aircraft, artillery, heavy-caliber weapons, mortars — all settlements are being shelled."                                                                               ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Pavlo Kyrylenko, Head of Donetsk region military administration, said on Telegram that Russian forces overnight continued shelling in the central part of the region.                                                                                                                                                                                                                                                                                                                                                     , "In Maryinka, Krasnohorivka and Novomykhailivka, the enemy again used white phosphorous shells," he said, referring to munitions that are either banned or circumscribed under international law in populated areas. "Eleven wounded civilians from the Maryinka community, including 4 children, were taken to the Kurakhiv City Hospital."                                                                                                                                                                              , Kremlin spokesperson Dmitry Peskov said Russia never violates international conventions when asked to comment on a claim by Ukrainian President Volodymyr Zelensky regarding the alleged use of phosphorus bombs by Russian forces, Russian media reported.                                                                                                                                                                                                                                                               , Questions about Russian troop morale                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Ukraine's General Staff said in a statement Thursday that Russian forces may indeed be regrouping on the territory of Belarus, which has been a staging area for the Russian invasion of Ukraine.                                                                                                                                                                                                                                                                                                                         , The statement said the movement of Russian military equipment had been observed in Belarus, "probably for regrouping units, as well as creating a reserve to replenish losses in manpower, weapons and equipment of groups operating in Ukraine."                                                                                                                                                                                                                                                                         , Outside analysis suggests that Russian troops have seen serious equipment losses and heavy casualties. The Russian military said nearly a week ago that 1,351 military personnel had been killed in Ukraine and 3,825 had been wounded, casualty figures that the US, Ukraine and NATO say represent a serious underreporting of troop losses.                                                                                                                                                                            , Jeremy Fleming, Director of Government Communications Headquarters (GCHQ), the UK spy agency speaking during a trip to Canberra, Australia, suggested that Russian troop morale was seriously plummeting and that Russian President Vladimir Putin -- who lives in an information bubble as well as in physical isolation -- may not be aware of the extent of the problem for his military.                                                                                                                              , "We've seen Russian soldiers -- short of weapons and morale -- refusing to carry out orders, sabotaging their own equipment and even accidentally shooting down their own aircraft. And even though we believe Putin's advisers are afraid to tell him the truth, what's going on and the extent of these misjudgments must be crystal clear to the regime."                                                                                                                                                              , Putin on Thursday signed a decree to draft 134,500 Russians into the military to replace conscripts who are rotating out of service.                                                                                                                                                                                                                                                                                                                                                                                      , The Russian military has a mixed manpower system that has draftees as well as contract servicemembers, and the country has a twice-annual call-up for conscription.                                                                                                                                                                                                                                                                                                                                                       , Putin originally claimed that conscripts would not take part in the war, but the Russian defense ministry subsequently acknowledged that draftees were fighting in Ukraine --  and Ukrainian forces claim to have taken a considerable number of Russian conscripts prisoner.                                                                                                                                                                                                                                             , An intensifying humanitarian crisis                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , The humanitarian situation remains grave in many Ukrainian cities, particularly in the besieged southeastern port city of Mariupol.                                                                                                                                                                                                                                                                                                                                                                                       , On Thursday, hopes were raised of the possibility that busloads of residents of Mariupol -- which has been under weeks of relentless shelling and bombing by Russian forces -- might be able to leave through a so-called humanitarian corridor.                                                                                                                                                                                                                                                                          , But the convoy was held up at a Russian checkpoint in Vasylivka, a city between the Ukrainian-held city of Zaporizhzhia and the Russian-held city of Berdiansk, according to Iryna Vereshchuk, the Ukrainian minister for Reintegration of Temporarily Occupied Territories.                                                                                                                                                                                                                                              , Vereshchuk said about 100,000 people requiring immediate evacuation remain in the city, out of a pre-war population of over 400,000.                                                                                                                                                                                                                                                                                                                                                                                      , "That is, another 100,000 women, children, the elderly, and people with disabilities who need our and the world's help," she said.                                                                                                                                                                                                                                                                                                                                                                                        , Ukrainian officials say around 90% of the buildings in the city have been damaged or left uninhabitable after weeks of bombardment.                                                                                                                                                                                                                                                                                                                                                                                       , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hong-kong/currency </td>
   <td style="text-align:left;"> 2022-03-31 22:45:33 </td>
   <td style="text-align:left;"> Hong Kong Dollar Hits 27-month Low </td>
   <td style="text-align:left;"> USDHKD increased to a 27-month high of 7.8308 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/covid-tests-vaccines-help-walgreens-beat-earnings </td>
   <td style="text-align:left;"> 2022-03-31 22:36:12 </td>
   <td style="text-align:left;"> COVID tests, vaccines help Walgreens beat expectations on earnings </td>
   <td style="text-align:left;"> Fox News congressional correspondent Chad Pergram reports from Capitol Hill on the White House asking for more coronavirus funding.                                                                                                                                                                                                                                                  , Walgreens Boots Alliance exceeded analysts' earnings expectations for the second quarter, when pharmacy sales were driven up on demand for COVID-19 tests and vaccines as the omicron variant swept the U.S.                                                                                                                                                                         , Walgreens logo is seen in San Francisco, California, United States on October 18, 2021. (Photo by Yichuan Cao/Sipa USA) (Yichuan Cao/Sipa USA)                                                                                                                                                                                                                                       , The Deerfield, Illinois-based firm reported earnings of $1.59 per share on Thursday for the quarter ending Feb. 28, beating Wall Street's projection of $1.40.                                                                                                                                                                                                                       , SECOND BOOSTER DOSE OF PFIZER, MODERNA COVID-19 VACCINES AUTHORIZED BY FDA                                                                                                                                                                                                                                                                                                           , The company said its U.S. retail comparable sales growth of 14.7% was the highest it has seen in more than 20 years. Revenue climbed roughly 3% to $33.76 billion, surpassing analysts' estimate of $33.23 billion.                                                                                                                                                                  , Walgreens CEO Rosalind Brewer (Photo credit: iStock)                                                                                                                                                                                                                                                                                                                                 , "Second quarter results demonstrated broad-based execution, driving strong comparable sales and robust earnings growth," CEO Rosalind Brewer said in a statement announcing the results. "We continue to make important strides along our strategic priorities, building a consumer-centric, technology-enabled healthcare enterprise at the center of local communities," she added., GOP LAWMAKER CALLS FOR AN ‘OPERATION WARP SPEED’ FOR COVID-19 THERAPEUTICS                                                                                                                                                                                                                                                                                                           , Walgreens is the largest pediatric vaccine provider in the pharmacy channel (istock / iStock)                                                                                                                                                                                                                                                                                        , All told, the pharmaceutical giant that operates nearly 9,000 locations in the U.S. and another 2,300-plus abroad administered 11.8 million COVID-19 vaccinations and 6.6 million COVID-19 tests in the second quarter.                                                                                                                                                              , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                          , Walgreens is the largest pediatric vaccine provider in the pharmacy channel, the company reported.                                                                                                                                                                                                                                                                                   , The Associated Press contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/currency </td>
   <td style="text-align:left;"> 2022-03-31 22:35:00 </td>
   <td style="text-align:left;"> Ruble Steady Amid Gas Currency Dispute </td>
   <td style="text-align:left;"> The Russian ruble traded at 79 per USD on Thursday, strengthening to levels only seen before Russia’s invasion of Ukraine, after President Putin signed a decree mandating that foreign purchases on Russian natural gas must be made in rubles. Under the decree, gas purchases are to be made through transactions from Russian banks, many of which were hit by sanctions. Western leaders rejected the move, stating it is a breach of contract. The ruble fell to as low as 150 per dollar earlier in March as the West imposed unprecedented levels of sanctions against the Russian economy, with a US-led ban on the country’s energy exports. The currency has since staged a dramatic rebound after the Russian central bank raised its key interest rate to 20% and Moscow imposed strict capital controls to keep businesses and individuals from selling rubles. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mauritius/gdp-growth-annual </td>
   <td style="text-align:left;"> 2022-03-31 22:33:00 </td>
   <td style="text-align:left;"> Mauritius GDP Expands Faster in Q4 </td>
   <td style="text-align:left;"> The economy of Mauritius grew 6.2 percent from a year earlier in the fourth quarter of 2021, quickening from a downwardly revised 4.6 percent growth in the previous three-month period. It was the third consecutive quarter of economic expansion, after a pandemic-induced recession. The main driver of growth was the tourism-related sector (157.1 percent vs 103.9 percent in Q3), following the easing of some travel restrictions. Positive contributions also came from mining &amp; quarrying (22.4% after showing no growth); construction (9.1% vs 12.9%); information &amp; communication (7.3% vs 7.2%) and finance &amp; insurance (5.7% vs 4.5%). Considering the full year of 2021, the GDP advanced by 4%, compared with a 14.9% plunge in 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/stock-market </td>
   <td style="text-align:left;"> 2022-03-31 22:20:36 </td>
   <td style="text-align:left;"> Stocks in Mexico Hit All-time High </td>
   <td style="text-align:left;"> IPC Mexico increased to an all-time high of 56280 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-03-31 22:00:00 </td>
   <td style="text-align:left;"> Brazilian Equities Edge Up </td>
   <td style="text-align:left;"> The main Sao Paulo Index, Ibovespa, was up 0.4% to around 120,780 on Thursday, remaining close to high levels not seen since August 2021, extending gains for the third straight session. Grupo Soma, Ecorodovias and Positivo were leading the gains. On the other hand, Petrobras, Banco Pan and Suzano dragged.  At the same time, investors continued to gauge the outlook for inflation and interest rates, while monitoring the conflict in Ukraine. On the data front, Brazil's jobless rate stood at 11.2% in the three months through February, the lowest level for the period in six years, slightly below market forecasts of 11.4%. On a monthly basis, the Ibovespa is on track to book an over 6.5% gain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-03-31 21:55:00 </td>
   <td style="text-align:left;"> Toronto Stocks Hit New All-Time High </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, resumed its upward trend, breaking record highs on Thursday, as gains in heavyweight mining stocks more than offset losses in major energy stocks. On corporate news, Royal Bank of Canada made an all-cash, £1.6 billion offer for the British wealth management company Brewin Dolphin. Meanwhile, Suncor Energy said a fire at its 146 thousand bpd refinery in Edmonton had been extinguished. On the data front, the Canadian economy likely advanced 0.8% m-o-m in February, quickening from a 0.2% expansion in January. On a monthly basis, the index is set for a 5.5% rise, its best monthly performance since November of 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/eu-natural-gas </td>
   <td style="text-align:left;"> 2022-03-31 21:53:00 </td>
   <td style="text-align:left;"> EU Natural Gas Rises 6% </td>
   <td style="text-align:left;"> EU natural gas futures rose more than 6% to above €125 per megawatt-hour in a volatile Thursday session, after Russia’s President Putin reignited supply fears after signing a decree forcing “unfriendly” countries to pay for natural gas in rubles. Germany and France accused the Russian President of blackmail and were preparing for a possible halt in natural gas supplies. In Q3 2021, Gazprom, which is Europe’s largest supplier of natural gas, relied on the euro for roughly 59% of foreign sales. Support also came from forecasts of below-average temperatures in northwest Europe, which should add pressure on utilities' inventory replenishing efforts, and reports that unplanned outages at Norwegian gas fields continued to affect output. On a monthly basis, the contract is set to end flat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/current-account </td>
   <td style="text-align:left;"> 2022-03-31 21:52:03 </td>
   <td style="text-align:left;"> India Current Account Gap Largest in 2 Years </td>
   <td style="text-align:left;"> India recorded a current account gap of $23 billion or 2.7% of the GDP in the last quarter of 2021, the largest in two years, mainly due to a wider trade deficit. The goods gap increased to $60.4 billion from $34.6 billion a year earlier. The primary income gap also increased to $11.7 billion from $10.1 billion. On the other hand, the services surplus widened to $27.8 billion from $23.2 billion, mainly due to exports of computer and business services. The secondary income surplus increased by $2 billion to $21.3 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/opec-refuses-increase-oil-output-us-release-reserves </td>
   <td style="text-align:left;"> 2022-03-31 21:50:33 </td>
   <td style="text-align:left;"> OPEC refuses to increase oil output as US announces massive release of crude reserves </td>
   <td style="text-align:left;"> Marc Short, former Chief of Staff to VP Pence, shares his take on Biden's plan to release oil from the Strategic Oil Reserve and the climate agenda outlined in the president's latest budget.                                                                                                                                                                                                                    , OPEC and its allies including Russia decided on Thursday to stick with a schedule of gradual production increases as the U.S. weighs an unprecedented release from its national strategic petroleum reserves in an attempt to bring down gasoline prices.                                                                                                                                                         , The group, known as OPEC+, said Thursday that it would boost crude output by 432,000 barrels a day in May as it works to restore pre-pandemic levels of production, according to a statement. That's up slightly from 400,000 barrels per day in previous months.                                                                                                                                                 , BIDEN ADMINISTRATION TO RELEASE 1M BARRELS OF OIL DAILY FROM US RESERVES                                                                                                                                                                                                                                                                                                                                          , The oil-producing nations have resisted pressure from the U.S. to pump more crude as prices soar, exacerbating already sky-high inflation. The high prices have also helped Russia to offset the pain of Western sanctions imposed over its invasion of Ukraine last month.                                                                                                                                       , OPEC Secretary General Mohammad Sanusi Barkindo (C) participates in the Atlantic Council's Global Energy Forum in Dubai, on March 28, 2022.  ((Photo by KARIM SAHIB/AFP via Getty Images) / Getty Images)                                                                                                                                                                                                         , The move came as President Biden on Thursday morning ordered a record-setting 180 million barrels of oil released from the nation's Strategic Petroleum Reserve in hopes of lowering gas prices. If fully enacted, the president's plan would release 1 million barrels per day for the next 180 days.                                                                                                            , Established after a 1973-74 oil embargo by Arab members of OPEC, the reserve has been used in several emergencies, including in 2005 after Hurricane Katrina made landfall and destroyed swaths of the Gulf of Mexico oil infrastructure. At the time, the Bush administration authorized the release of 20.8 million barrels of crude oil to U.S. producers.                                                     , Proponents of releasing barrels from the emergency stockpile say that doing so would increase oil supplies and reduce prices at the pump, while also generating billions in revenue for the federal government. Still, critics say that releasing emergency supplies is a short-term fix to a problem and does not actually increase the country's oil-production capabilities.                                   , U.S. President Joe Biden speaks in the Roosevelt Room of the White House in Washington, D.C., U.S., on Tuesday, March 8, 2022.  (Photographer: Oliver Contreras/Sipa/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                   , The soaring oil prices have roots in the faster-than-expected economic recovery from the pandemic, which has triggered the hottest inflation in decades amid strong consumer demand, an influx of government stimulus and disruptions in the global supply chain. But in recent weeks, the war between Russia and Ukraine has sent global prices even higher as it impedes the world's access to energy supplies. , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                       , The average price for a gallon of gas was at $4.22 nationwide Thursday, according to AAA, up from $2.87 one year ago but down slightly from last week's level. In California, prices are as high as $6 a gallon. Until this month, prices had not topped $4 a gallon nationally since 2008. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/nuclear </td>
   <td style="text-align:left;"> 2022-03-31 21:40:55 </td>
   <td style="text-align:left;"> Nuclear Energy Index Hits All-time High </td>
   <td style="text-align:left;"> Nuclear Energy Index increased to an all-time high of 1486 USD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/norway/stock-market </td>
   <td style="text-align:left;"> 2022-03-31 21:37:44 </td>
   <td style="text-align:left;"> Stocks in Norway Hit All-time High </td>
   <td style="text-align:left;"> Oslo increased to an all-time high of 1429 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-31 21:31:00 </td>
   <td style="text-align:left;"> Wall Street Struggles to Find Traction </td>
   <td style="text-align:left;"> Major indexes in the US stock market opened Thursday's session mostly down as investors reassessed the outlook of tightening monetary policy while watching developments in the Russia-Ukraine war. The labour market remains very tight, with recent data showing job openings hovered near record highs in February while jobless claims remained near levels not seen since 1969. The robust job market data came on the heels of rising inflation, currently at 40-year highs, which, in turn, prompted bets on a higher possibility of a 50-bps hike in May. Still, equities markets have rallied in the second half of the month. The Dow is up nearly 4% in March, while the S&amp;P 500 and Nasdaq added about 5% each. However, the Dow and S&amp;P 500 are both down about 3% for the first quarter, and the Nasdaq is off more than 7%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/eu-natural-gas </td>
   <td style="text-align:left;"> 2022-03-31 21:28:50 </td>
   <td style="text-align:left;"> TTF Gas is up by 5.77% </td>
   <td style="text-align:left;"> Natural Gas EU Dutch TTF increased 5.77% to 125.84 EUR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/czech-republic/interest-rate </td>
   <td style="text-align:left;"> 2022-03-31 21:26:25 </td>
   <td style="text-align:left;"> Czech National Bank Hikes Interest Rate by 50bps </td>
   <td style="text-align:left;"> The Czech National Bank raised its benchmark two-week repo rate by 50bps to 5% on March 31st of 2022, the highest since November of 2001 and in line with expectations. The central bank has raised the rate by 475bps since June of 2021, among the most aggressive tightening cycles in Europe, to curb surging consumer prices. Inflation hit a 24-year high of 11.1% in February, driven by surging energy and food prices, and are expected to rise further due to Russia’s invasion of Ukraine. Meanwhile, the central bank raised the Lombard rate and the discount rate by the same extent to 6% and 4%, respectively. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-03-31 21:04:00 </td>
   <td style="text-align:left;"> Brent Drops as Biden Mulls Major Reserves Release </td>
   <td style="text-align:left;"> Brent crude futures dropped 5% to below $108 per barrel on Thursday as the Biden administration announced the largest-ever strategic petroleum reserve release. The plan involves putting on the market 1 million barrels of oil per day for six months to lower the gasoline prices that have hit record levels following Russia's invasion of Ukraine. The White House also asked US oil producers to increase output and said it would impose levies on those that were not making use of their drilling licenses on public lands. Meanwhile, OPEC+ agreed to raise its output targets by 432,000 barrels per day from May 1, as expected. Still, Brent crude is set for a fourth consecutive month of gains, after reaching the highest since 2008 at near $140 per barrel on March 7th, as demand recovery from the coronavirus pandemic gathered pace while the war in Europe squeezed the already tight market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-03-31 20:54:00 </td>
   <td style="text-align:left;"> US Futures Lack Direction </td>
   <td style="text-align:left;"> US futures were little changed on Thursday, with energy shares under pressure during pre-market hours amid a fall in oil prices as the Biden administration pledged to make a huge reserves release to curb rising oil prices and a tight supply. At the same time, traders continue to follow the Russia-Ukraine ceasefire talks and reassess the outlook for inflation and the direction of monetary policy. On the month, the S&amp;P 500 and Nasdaq are up about 5% each, while the Dow is nearly 4% higher. Considering Q3 however, the 3 main averages are on track to book the first quarterly loss since Q1 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-03-31 20:50:00 </td>
   <td style="text-align:left;"> Oil Tumbles as US Mulls Major Reserves Release </td>
   <td style="text-align:left;"> WTI crude futures dropped more than 5% to below $102 per barrel on Thursday, following reports that the Biden administration is set to announce today the massive release of US crude oil reserves. The plan will involve putting on the market around 1 million barrels of oil per day for several months to lower the gasoline prices that have hit record levels following Russia's invasion of Ukraine. The moves also came as US crude stocks fell by 3.4 million barrels last week, way bigger than the 1-million-barrel drop forecast. Meanwhile, OPEC+ agreed to raise its output targets by 432,000 barrels per day from May 1, as expected. US crude prices are heading for a fourth consecutive month of gains, having hit the highest since 2008 at almost $126.42 per barrel on March 7th, as demand recovery from the coronavirus pandemic gathered pace while the war in Europe squeezed the already tight market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/601857:ch </td>
   <td style="text-align:left;"> 2022-03-31 20:48:47 </td>
   <td style="text-align:left;"> Petrochina earnings above expectations at 0.09 CH </td>
   <td style="text-align:left;"> Petrochina (601857) released earnings per share at 0.09 CH , compared to market expectations of 0.08 CH . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/1177:hk </td>
   <td style="text-align:left;"> 2022-03-31 20:44:21 </td>
   <td style="text-align:left;"> Sino Biopharmcl earnings below expectations at 0.12 USD </td>
   <td style="text-align:left;"> Sino Biopharmcl (1177) released earnings per share at 0.12 USD, compared to market expectations of 0.16 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ptr:us </td>
   <td style="text-align:left;"> 2022-03-31 20:42:58 </td>
   <td style="text-align:left;"> Petrochina earnings above expectations at 1.42 USD </td>
   <td style="text-align:left;"> Petrochina (PTR) released earnings per share at 1.42 USD, compared to market expectations of 1.31 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/wba:us </td>
   <td style="text-align:left;"> 2022-03-31 20:42:03 </td>
   <td style="text-align:left;"> Walgreens Boots Alliance earnings above expectations at 1.59 USD </td>
   <td style="text-align:left;"> Walgreens Boots Alliance (WBA) released earnings per share at 1.59 USD, compared to market expectations of 1.37 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hmb:ss </td>
   <td style="text-align:left;"> 2022-03-31 20:40:29 </td>
   <td style="text-align:left;"> H&amp;M earnings below expectations at 0.10 SEK </td>
   <td style="text-align:left;"> H&amp;M (HMb) released earnings per share at 0.10 SEK, compared to market expectations of 0.60 SEK. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-04-01 09:02:46 UTC +8

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
   <td style="text-align:left;"> 2022-04-01 09:02:12 </td>
   <td style="text-align:left;"> $SPY Losers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 09:01:59 </td>
   <td style="text-align:left;"> At the Close Thursday 
 
DJIA 
34678.35 
-550.46 
-1.56% 
NASDAQ 
14220.52 
-221.76 
-1.54% 
S&amp;amp;P 500 
4530.41 
-72.04 
-1.57% 
 
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 09:01:52 </td>
   <td style="text-align:left;"> $SPY scammers still out trying to scam </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 09:01:49 </td>
   <td style="text-align:left;"> $SPY VILLI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 09:01:48 </td>
   <td style="text-align:left;"> $QQQ european markets gonna crash $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 09:01:46 </td>
   <td style="text-align:left;"> $SPY Cathie Wood dumped shares of Tesla worth $40million today. $TSLA 

Guess she finally learned to sell the top. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 09:01:04 </td>
   <td style="text-align:left;"> $SPY this is wild
https://www.washingtonpost.com/nation/2022/03/30/south-dakota-hotel-native-americans/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 09:00:58 </td>
   <td style="text-align:left;"> @STCKPRO https://www.pymnts.com/mobile-applications/2022/robinhood-beta-suggests-retirement-accounts-are-coming-to-the-app/  ? ? ? ? ? $SPY $DJIA $ROKU $PLTR $HOOD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 09:00:50 </td>
   <td style="text-align:left;"> $SPY Think Tesla could&amp;#39;ve avoided this ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 09:00:48 </td>
   <td style="text-align:left;"> $SPY I need a hail Mary.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 09:00:32 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m just waiting for you. . Wait what, alter ego. . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 09:00:13 </td>
   <td style="text-align:left;"> $SPY https://twitter.com/backtolife_2022/status/1509194433018871809?s=21&amp;amp;t=bb_R1FttqzD8-mmbIQLmYQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 09:00:04 </td>
   <td style="text-align:left;"> $SPY Bulls better watch out if OFG is not posting tomorrow....it&amp;#39;s about to get real </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:59:50 </td>
   <td style="text-align:left;"> $QQQ $SPY 3 more years of this smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:59:33 </td>
   <td style="text-align:left;"> $TSLA Just read that Kathy would dumped Tesla shares worth 40 million on Thursday

$spy  Considerable amount

Cathy’s throwing down she’s like $40M bye bye 

Like no big  deal  $40 M. On a Thursday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:59:32 </td>
   <td style="text-align:left;"> $TSLA wakeup Elon, not all Tesla holder is usa, many china, me hold Tesla moon $spy

We pay tax if you do the not split dividend thingy, wakeup Elon!!! Elon you anti China holder or what?

SPLIT the normal way, not dividend split, need pay tax, you are kid elon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:59:21 </td>
   <td style="text-align:left;"> $SPY .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:59:14 </td>
   <td style="text-align:left;"> $SPY .99cent a scoop. It goes down, we don&amp;#39;t promise how it goes out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:59:07 </td>
   <td style="text-align:left;"> $UVXY can you bastards get this up to $20 so I can buy some more quarterly calls on $spy Goldman and all the banks about to scare everyone for cheaper premiums again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:58:58 </td>
   <td style="text-align:left;"> $SPY $QQQ When the EU is de-industrialized in the next decade without cheap energy they won’t matter anyways. In the long run cheap energy and goods made from it always wins. That’s how the China-Russia alliance will completely de-industrialize the west except for the US.

Europe is gonna be the biggest loser in the NWO. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:58:54 </td>
   <td style="text-align:left;"> $SPY tomorrow can&amp;#39;t come fast enough </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:58:40 </td>
   <td style="text-align:left;"> $SPY new month new gains </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:58:05 </td>
   <td style="text-align:left;"> $SPY Seriously, what if you blocked everyone who disagreed with you? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:58:01 </td>
   <td style="text-align:left;"> $SPY sanctions are most definately not working in our favor </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:58:00 </td>
   <td style="text-align:left;"> $SPY I am a coastal elite and I would like spy to go to 462 Monday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:57:52 </td>
   <td style="text-align:left;"> $SPY Zurich Switzerland for Vacation? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:57:47 </td>
   <td style="text-align:left;"> $SPY 🎧 
 
https://open.spotify.com/track/1HmzAZUvhQLhLo2z3ocpZI?si=2Fe9NAwyQkueS1KYQTuFAg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:57:40 </td>
   <td style="text-align:left;"> $TSLA dividend is bad, why pay tax? I&amp;#39;M CHINA, YOU ELON MAKE THIS not split FOR WHAT!!! $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:57:25 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA 

This feels like the peak of fear at the end of Monday March 14, just before the face ripping one week rally of 10+%. 
How many bears were so sure that we will have an epic market collapse on Tuesday, March 15, eh? How many were counting their puts would print bigly? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:57:05 </td>
   <td style="text-align:left;"> $SPY look at 2-10 speed 
It’s 0.01 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:56:58 </td>
   <td style="text-align:left;"> $SPY but what if I don&amp;#39;t have a wiener or a vajayjay? I&amp;#39;m dyslexic so I see yag instead. Golly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:56:00 </td>
   <td style="text-align:left;"> $SPY now I see some bullish signs for tomorrow, likely to be green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:55:32 </td>
   <td style="text-align:left;"> $SPY transgenders should be forced to identify that in their driver&amp;#39;s license before they can get surgery or hormones </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:55:11 </td>
   <td style="text-align:left;"> $SPY Brother, pm me @OldManJenkins_ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:55:08 </td>
   <td style="text-align:left;"> $SPY Bull or Bear and zodiac sign. I’m tryna see something. 👀 

Bearish - Capricorn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:55:07 </td>
   <td style="text-align:left;"> $SPY darn. I guess germany ain&amp;#39;t getting gas lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:55:06 </td>
   <td style="text-align:left;"> $SPY Can I get a bounce off the monthly 9ema that would be dope. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:54:49 </td>
   <td style="text-align:left;"> $SPY @OldManJenkins bro Pm me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:54:46 </td>
   <td style="text-align:left;"> $SPY gypsies dont need gas anyway </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:54:27 </td>
   <td style="text-align:left;"> $SPY Simple guys if you are holding puts expiring on April 14 or next week, and you got in before the flush because you know what you are doing. Sell half if $SPX takes back SMA100 and exit the trade if SPX regains $4575. If not, let the puts ride. That what I&amp;#39;m advising my peeps in my private room. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:54:06 </td>
   <td style="text-align:left;"> $SPY wow so no rubles no gas to EU ? Starting tmrw ?
Sorry if selling my 10 calls dragged u down this much i mean i will buy again soon dnt worry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:53:41 </td>
   <td style="text-align:left;"> $SPY status check of markets. . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:53:40 </td>
   <td style="text-align:left;"> $SPY $BBIG $AMC $GME anybody else using that neat little elliot wave indicator on tradingview...seems to give decent entrys by showing the possible abc waves at the end of each impulse wave...i believe its a built in indicator...ive caught some good dips using it this week for the first time combined with Ew oscillator for confirmation along with price action TA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:53:21 </td>
   <td style="text-align:left;"> $SPY blocked and reported!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:52:35 </td>
   <td style="text-align:left;"> $SPY CATALYST: Non-Farm Payrolls Economic Data will be released on Fri. Apr. 1 at 8:30 AM. 
 
View details and track upcoming catalysts: https://www.catacal.com/catalyst/non-farm-payrolls-3 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:52:20 </td>
   <td style="text-align:left;"> $SPY hari-kari </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:52:12 </td>
   <td style="text-align:left;"> $QQQ $SPY 

Now that they have the end-of-quarter options expirations, it only adds to more volatilities and more premium money for MM’s to make. 

This is absolutely criminal. Soon, they will like to have options expiring everyday! 

I remember back when there were only monthly options. Those were the good days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:52:09 </td>
   <td style="text-align:left;"> $SPY that end of day volume was not by accident... strong feeling its going to be painful.. On the bright side I have my options at a low price, so I should be fine., Diamond hands </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:51:56 </td>
   <td style="text-align:left;"> $SPY watching closely rn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:51:52 </td>
   <td style="text-align:left;"> $SPY Harry Dent calling for 90% sell off!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:51:31 </td>
   <td style="text-align:left;"> $SPY Biden tapping oil reserves 
stock market said way late and will do little if anything 
market plunged on Biden weakness </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:51:23 </td>
   <td style="text-align:left;"> $SPY likely in the same range, slightly green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:51:16 </td>
   <td style="text-align:left;"> $SPY not sure if anyone heard today but I think the yields may have inverted. Can anyone confirm? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:51:11 </td>
   <td style="text-align:left;"> $SPY the sun will come out, tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:51:06 </td>
   <td style="text-align:left;"> $SPY 

The moments TWOWS lives for❤️❤️❤️

Amazing market for day traders! Just love this market $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:51:05 </td>
   <td style="text-align:left;"> $GUSH $SPY Needs to cool down more into next week. Holding $TELL for double digits. $WWR for upcoming run. When the cannabis bill passes don&amp;#39;t miss next run. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:50:54 </td>
   <td style="text-align:left;"> $SPY will smith would slap these markets in the face </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:50:21 </td>
   <td style="text-align:left;"> $SPY Uh, yeah.  

Did The Son Of The World&amp;#39;s Third-Richest Man Trade NFTs With Inside Information? https://www.forbes.com/sites/jeffkauflin/2022/03/30/did-the-son-of-the-worlds-third-richest-man-trade-nfts-with-inside-information/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:50:13 </td>
   <td style="text-align:left;"> $SPY where are all those oil experts from last night. I guess that indicator didn&amp;#39;t work today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:50:13 </td>
   <td style="text-align:left;"> Current 2&amp;amp;10 spread: .0051

$NASDAQ $QQQ $SPY $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:49:31 </td>
   <td style="text-align:left;"> $uvxy $spy I’m going on vacation By plane to a secluded place thanks for all the money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:49:23 </td>
   <td style="text-align:left;"> $SPY that guy in window had pootz today 
https://www.youtube.com/watch?v=9N0jn0weuvc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:49:18 </td>
   <td style="text-align:left;"> $SPY where is the value of the dollar the greatest and recieving the most return right now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:49:14 </td>
   <td style="text-align:left;"> $SPY Can we just forget about spy and make OTC and small caps great again??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:48:25 </td>
   <td style="text-align:left;"> $SPY yield inverted awesome </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:48:19 </td>
   <td style="text-align:left;"> $SPY counting crows are the best band ever who is second? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:48:05 </td>
   <td style="text-align:left;"> $SPY 1 more dip to buy the rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:47:38 </td>
   <td style="text-align:left;"> $SPY does anybody have any stats the day prior to April? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:47:31 </td>
   <td style="text-align:left;"> $SPY Old guys only trade on green days....Red days are for golfing....That&amp;#39;s just how we role.....LOL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:47:27 </td>
   <td style="text-align:left;"> $SPY This was an easy play the market hit $461 one time and didn&amp;#39;t hit it again for days. All you had to do was buy puts at the high and average them down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:47:23 </td>
   <td style="text-align:left;"> $SPY anyone remember beginning of Covid when Ackman saying sky is falling sell everything.... as he bought the hell out of hotels? Now he quits short selling. Spreading fear is far more profitable it would seem... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:47:12 </td>
   <td style="text-align:left;"> $SOFI I love to read all the negative comments (easy to bash and hard to build). People pretend not to understand that innovation in the fintech area is key, and the model of big banks will change dramatically in the next few years. Online banking and the innovative tools will provide successful solutions in an environment where low/no cost is critical to  customers, as well as the competition and generating better profits.  Tomorrow is a new month, new quarter and a new day....  
$SPY $QQQ should have a beautiful day and the whole market should join the party 
SOFI to the MOOOOOOOOOOOOOOOOOOOOOOOOON!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:46:46 </td>
   <td style="text-align:left;"> $SPY in a few weeks some fake bull will be begging for this 451 dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:46:33 </td>
   <td style="text-align:left;"> $SPY $QQQ $SQQQ $TQQQ Just an idea. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:46:07 </td>
   <td style="text-align:left;"> $SPY I am ok with Putin shutting off the flow of gas. Good that we find and use workarounds now so Russia just becomes more useless.
 
We’ll get through everything. It’s the people of Ukraine that need the world help and resources. Let’s focus on giving them what they need. Putin won’t last much longer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:46:04 </td>
   <td style="text-align:left;"> $SPY let’s see if futes hold up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:45:48 </td>
   <td style="text-align:left;"> $SPY futures are ripping. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:45:13 </td>
   <td style="text-align:left;"> $SPY We called it before it happened. Check out the time of the post on the pick. The plan now is to sell half if SPX takes back SMA100 and close the trade if we get back to $4575. If not, let it ride for a week or two while the support pivots keep popping. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:45:11 </td>
   <td style="text-align:left;"> $SPY stock analysis based on today&amp;#39;s closing price 

https://youtu.be/zA0k2KevtdU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:44:40 </td>
   <td style="text-align:left;"> $SPY $QQQ $SOFI $GME 🌚🍟 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:44:35 </td>
   <td style="text-align:left;"> $SPY Seriously why would you not sell your puts at close after that drop lmao? Bears always talking about bulls being greedy.. look in a fkn mirror </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:44:30 </td>
   <td style="text-align:left;"> $SPY Annnnnnd WELCOMEEE!!! To the Ponzi Casinoooo!!!!! How may i help you? My name is Jerome Powell. What can i get for ya tonight? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:44:07 </td>
   <td style="text-align:left;"> $SPY Anybody have thoughts on CTHR? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:43:51 </td>
   <td style="text-align:left;"> $SPY do bears know they are long term losers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:43:45 </td>
   <td style="text-align:left;"> $SLV Selling $24c for April 14th tomorrow. Proceeds to buy $SPY June $400P. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:43:25 </td>
   <td style="text-align:left;"> $SPY $QQQ In Venezuela everyone is fit except empanada eating Maduro. In the new Bidenzuela economy we will all be healthy and fit. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:43:22 </td>
   <td style="text-align:left;"> $SPY gap down and I’ll feed my grandma pube soup 🥣 $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:43:20 </td>
   <td style="text-align:left;"> $SPY if Apple give each iPhone owner 1 free game, what would it be? Vote now $aapl

Btd 6
Mobile legend
Candy crush </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:43:18 </td>
   <td style="text-align:left;"> $SPY Early this week Cramer said market has bottomed and it is time to buy. Today, he said this “Jim Cramer says market will find a bottom &amp;#39;far more quickly than you think&amp;#39; and is poised to rally” 

I pity those who listen to him to make their investment’s or trading decision 👌🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:43:05 </td>
   <td style="text-align:left;"> $SPY Man people need to lighten up......OFG MIA on every red day.......LOL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:42:46 </td>
   <td style="text-align:left;"> $SPY Gap at 444 needs to be filled. Stop playing the guessing game with your money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:42:33 </td>
   <td style="text-align:left;"> $SPY I told em I was out in September cause this shit was toppy. You better believe I&amp;#39;m been bricked up and selling rips while most still hoping for more stimmy since. #Grown. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:42:00 </td>
   <td style="text-align:left;"> $SPY u know u fkd when.... multiple layaway companies are listed with multi billion dollar valuations. . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:41:53 </td>
   <td style="text-align:left;"> $SPY wen sub 400 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:41:23 </td>
   <td style="text-align:left;"> $SPY peak cancel, trying to cancel will smith now, gtfo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:41:20 </td>
   <td style="text-align:left;"> $SPY The most important thing right now is to know - is it a bear or bull market? From these two points of view, you&amp;#39;ll see two different scenarios. For bears this is an amazing opportunity to short this pos down to 380, for bulls - once this pullback hits some support level, it&amp;#39;ll become a decent btfd opportunity. Just need to know the answer - is it a bull or bear market? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:41:13 </td>
   <td style="text-align:left;"> $DIS didn&amp;#39;t know Disney would be lgbt,
Roblox is like Lego, one female one male to connect and play $spy

Roblox is anti lgbt right $RBLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:41:07 </td>
   <td style="text-align:left;"> $SPY: We loaded calls at the close from our buy level analyzed for all our members last night.  We are hoping to get an oversold bounce on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:40:51 </td>
   <td style="text-align:left;"> $SPY i hope Putin closes the pipeline tomorrow... what a play, he is playing chess while biden plays in his sandbox... maybe by doing this the dems will finally wake up.... If true and putin acts... prepare yourselves </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:40:49 </td>
   <td style="text-align:left;"> $SPY Red futures in T - 2 hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:40:19 </td>
   <td style="text-align:left;"> $SPY $455 open? I’ve seen this chart before, it rallied the next day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:39:56 </td>
   <td style="text-align:left;"> $SPY Tomorrow. I&amp;#39;m coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:39:52 </td>
   <td style="text-align:left;"> $SPY Permabulls want a green candles with no reasons? 
Question: Why are you bullish, bulls? 
Answer: Charts say so, powell, and printer 

Question: why are you bearish, bears? 
Answer: Economic datas’ like inflations, PPI, etc.

Conclusion: No matter who’s right or wrong, reality will set in 🔜🔜🔜 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:39:46 </td>
   <td style="text-align:left;"> $GME ===&amp;gt; $240  by FRIDAY CLOSE!  😊🎊🎉🎈🔥🚀🚀🚀 
. 
$SPY $QQQ  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:39:36 </td>
   <td style="text-align:left;"> $SPY woah that was a sell off into the close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:39:34 </td>
   <td style="text-align:left;"> $SPY 

How many of the One Million daily Barrels will be allocated to John Kerry for his private jet?  Did they say ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:39:07 </td>
   <td style="text-align:left;"> $SPY NEW ARTICLE : The Markets Continue Short-Term Consolidation (Technically Speaking For 3/31) https://www.stck.pro/news/SPY/25398193 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:38:55 </td>
   <td style="text-align:left;"> $SPY stop shorting oil, I own exon Mobil, you guys are bad!!! All Joe fault if my profit decrease $xom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:38:55 </td>
   <td style="text-align:left;"> $SPY INVERTED YIELD CURVE #@@$#ES!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:38:49 </td>
   <td style="text-align:left;"> $SPY bulls buying puts at close because they had fomo  
(it will go down again after you lose your money) 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:38:08 </td>
   <td style="text-align:left;"> $SPY waiting on adults to chime on q2 prospective </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:37:56 </td>
   <td style="text-align:left;"> $SPY I use an algorithm similar to this method to trade spy.  Yes you can win 100% of the time. Here&amp;#39;s proof. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:37:55 </td>
   <td style="text-align:left;"> $SPY No one talking about futes today? guessing its flat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:37:42 </td>
   <td style="text-align:left;"> $SPY Bonds shaking things up, they&amp;#39;ve been, but most have been ignoring their volatility, blinded by the bear rally, getting stuck like bears did </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:37:36 </td>
   <td style="text-align:left;"> $SPY well a lot of people in denial.
The capitulation candles will provoke massive decapitation.
See you in hell fake economy and dementia bidon the ultimate carcass president. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:37:30 </td>
   <td style="text-align:left;"> $SPY $QQQ I wish I would&amp;#39;ve traded some $GME when it was under $100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:37:24 </td>
   <td style="text-align:left;"> $SPY backtestested weekly breakout level. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:37:15 </td>
   <td style="text-align:left;"> $SPY I’m really curious to see how the market reacts when Powell hikes rates 50 points in may and June and inflation still comes out at 7-8%.  

That’s when the cultists will realize they made a mistake </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:37:07 </td>
   <td style="text-align:left;"> $SPY gotta short the heck out of oil boy! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:37:01 </td>
   <td style="text-align:left;"> $SPY $RSX Even though capitalism won the cold war, it wasn&amp;#39;t the end of history because information access wasn&amp;#39;t at its peak natural resting place. Russia ended up wining out because it focused on  something that prepared the people for the truth and made them skeptical of information, the unrest in social pressure under communism train its populace in life skills while American held their head in the clouds thinking that the mind is a loose clay for them to form all by themselves in their happiness. The US is fucked. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:36:58 </td>
   <td style="text-align:left;"> $SPY Miss ya Trump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:36:15 </td>
   <td style="text-align:left;"> $SPY Cutting troop levels to 20 yr lows in the face of WW3. Yeah that sounds about right for these lunatics. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:36:10 </td>
   <td style="text-align:left;"> $SPY The Biden admin is releasing the entire oil reserves??? Man so stupid </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:36:05 </td>
   <td style="text-align:left;"> $SPY Bulls in denial since Jan 2022. Group think will sink the ship. Oldfnguy is the captain  😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:35:59 </td>
   <td style="text-align:left;"> $SPY where’s Hunter when I need him? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:35:55 </td>
   <td style="text-align:left;"> $SPY free money Friday tomorrow or nah? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:35:46 </td>
   <td style="text-align:left;"> $SPY if Powell really wanted to fight inflation he’d consider an April rate hike </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:35:40 </td>
   <td style="text-align:left;"> $SPY Real ones often offend while setting new trends. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:35:28 </td>
   <td style="text-align:left;"> US mortgage rates climb steeply, slowing housing boom

https://www.aljazeera.com/amp/economy/2022/3/31/us-mortgage-rates-climb-steeply

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:35:12 </td>
   <td style="text-align:left;"> $SPY 150% week let’s finish strong 💪🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:35:01 </td>
   <td style="text-align:left;"> $SPY how the monthly closed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:34:58 </td>
   <td style="text-align:left;"> $SPY lost momo trend temporarily. Likely chops people up between the .236 and .382 for the next week or two. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:34:49 </td>
   <td style="text-align:left;"> $SPY vix looks like its ready to break out again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:34:46 </td>
   <td style="text-align:left;"> The US reportedly watered down sanctions against a key Russian oligarch out of fear that disrupting his business empire could hurt the global economy

https://www.businessinsider.com/us-treasury-watered-down-sanctions-russian-oligarch-alisher-usmanov-report-2022-3?amp

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:34:37 </td>
   <td style="text-align:left;"> $SPY will the oldfngguy post tomorrow and bring us a bull run or will he remain in his pen while the market falls apart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:34:22 </td>
   <td style="text-align:left;"> $SPY 🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:34:16 </td>
   <td style="text-align:left;"> $SPY why’s the IQ level here so low </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:33:59 </td>
   <td style="text-align:left;"> $SPY wen capitulation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:33:45 </td>
   <td style="text-align:left;"> $SPY 🙃💯🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:33:39 </td>
   <td style="text-align:left;"> $SPY happy poo again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:33:18 </td>
   <td style="text-align:left;"> $SPY 

Roads have been packed for weeks everywhere I go.   Apparently folks aren&amp;#39;t heeding CNN advice.  Darn it!

&amp;quot;In the longer term, the really smart strategy for the Biden administration or any future administration would be to attack this problem, not from the supply side, but rather from the demand side,&amp;quot; Raimi said.

He said there was &amp;quot;very little&amp;quot; the Biden administration could do to reduce gas prices because of international events, like Russia invading Ukraine, &amp;quot;that the U.S. has no control over.&amp;quot; Later on, he argued the &amp;quot;key&amp;quot; for consumers to feel relief from the high prices is to not use as much&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:33:17 </td>
   <td style="text-align:left;"> $SPY people posting bearish since biden said food shortages but a lot of Americans need to lose weight anyway we will come out of this healthy and athletic. bullish imo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:32:55 </td>
   <td style="text-align:left;"> $SPY the most unexpected thing to happen tomorrow is to head past 462 and I think it&amp;#39;s possible. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:32:45 </td>
   <td style="text-align:left;"> $SPY be like,  if I&amp;#39;m number 2, show me whos number 1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:32:34 </td>
   <td style="text-align:left;"> $SPX $SPY $IWM $QQQ $VIX Market Reversal Confirmed - Where are the supports  https://youtu.be/l-lPt4KyUsM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:32:29 </td>
   <td style="text-align:left;"> $SPY US equities will always be one of the best assets you can own. buyers will always step in. short term have fun bears, but don’t get too comfortable 😉 

$qqq $arkk $djia $iwm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:31:12 </td>
   <td style="text-align:left;"> $QQQ I got bitches and they buy me clothes…or at least used to $SPY $HOOD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:30:54 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m actually Chris Angel&amp;#39;s and my trades are magic. I make money disappear. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:30:49 </td>
   <td style="text-align:left;"> $SPY Be sure to search me up on Discord before I invade you 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:30:48 </td>
   <td style="text-align:left;"> $SPY struggling to get above </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:30:44 </td>
   <td style="text-align:left;"> $SPY @DoomerStonks obj won&amp;#39;t me f*ck me over tomorrow hope lmfao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:30:26 </td>
   <td style="text-align:left;"> $SPY safest LT (2-3yrs) is just short Nasdaq. Unless Fed turns on the printers again. But I think everyone knows, they lost all credibility. . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:30:18 </td>
   <td style="text-align:left;"> $SPY Futes Trippin 🏃‍♂️ 🏃‍♀️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:30:11 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:30:02 </td>
   <td style="text-align:left;"> $SPY people will always complain no matter what you do </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:29:42 </td>
   <td style="text-align:left;"> $SPY futes ripping 🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:29:25 </td>
   <td style="text-align:left;"> $SPY maybe I&amp;#39;ll just play some online monopoly and listen to YouTube videos for a bit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:29:13 </td>
   <td style="text-align:left;"> $SPY next main candle daily ends @ 4450

    $spx  $qqq   $dia   $ndx  🏷  

                 Had to tag it    🏷. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:28:58 </td>
   <td style="text-align:left;"> $SPY I would honestly be surprised if these green futures carry into tomorrow. Flat at the most and green by Monday or Tuesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:28:43 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:28:15 </td>
   <td style="text-align:left;"> $SPY $DJIA -- Reversal arrived right on time. 
 
Published nightly in the newsletter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:28:09 </td>
   <td style="text-align:left;"> $SPY $QQQ this could be a real ominous weekly candle…unless we get a push up tomorrow.  I think we get a big green one tomorrow.  💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:27:54 </td>
   <td style="text-align:left;"> $SPY it wasn’t just the US market that dropped at the end of the day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:27:37 </td>
   <td style="text-align:left;"> $BABA copy the first 10 comment and turn onto a serious thesis study $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:27:36 </td>
   <td style="text-align:left;"> $SPY  
 
I love momentum </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:27:34 </td>
   <td style="text-align:left;"> $SPY I thought options close at 4? How do these still trade after 4? Makes no sense </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:27:23 </td>
   <td style="text-align:left;"> $SPY $QQQ Futes look good! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:27:14 </td>
   <td style="text-align:left;"> $SPY Went all in on the dip today, but only to dump on these bag holders EOD tomorrow for a minor gain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:27:13 </td>
   <td style="text-align:left;"> $SPY not sure which way I&amp;#39;m going yet tonight, shorted last night 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:27:03 </td>
   <td style="text-align:left;"> $SPY ~ green nice and early should make for another good day tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:26:43 </td>
   <td style="text-align:left;"> $SPY  
If stocktwits existed when I was in school it would have been pretty sweet. You could have  just copy the first 10 random comments and turn it in for a senior thesis, regardless of the area of study </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:26:43 </td>
   <td style="text-align:left;"> $SPY 454 already. Closed at 451.64. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:26:40 </td>
   <td style="text-align:left;"> $SPY you scammers     $ndx   $nasdaq  $qqq 

$SPX  likely drops another -$100 overnight    

There’s now in play lower gaps that fill </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:26:36 </td>
   <td style="text-align:left;"> $SPY Futes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:25:51 </td>
   <td style="text-align:left;"> $SPY those who are bullish in these conditions - how do you even do it? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:25:41 </td>
   <td style="text-align:left;"> $SPY 

And people wonder why he will never win.  🙄

&amp;quot;Beto O’Rourke was blasted on social media after posting a photo of himself wearing a shirt that said, &amp;quot;Don’t mess with trans kids,&amp;quot; a play on the popular phrase &amp;quot;Don’t mess with Texas&amp;quot;

🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:25:19 </td>
   <td style="text-align:left;"> $SPY oil futures went negative oil and every complained oil was too cheap.  Well now enjoy your expensive oil. Now you happy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:25:12 </td>
   <td style="text-align:left;"> $SPY I blocked OFG years ago. Let me guess, this old idiot disappeared this afternoon and wasn’t spamming the board with 1000x messages berating bears. Typical bulltard. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:25:10 </td>
   <td style="text-align:left;"> $SPY - anyone seen stockmaster aka Hollywood tonight?   I have to see which way he’s leaning towards so I can do the opposite. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:24:30 </td>
   <td style="text-align:left;"> $SPY 443.22 on the table tomorrow eod </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:24:24 </td>
   <td style="text-align:left;"> $SPY I got 80000 in a variety of stocks I held and 20000 in uvxy sqqq abs d sdow.  Or and spxu combined. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:24:22 </td>
   <td style="text-align:left;"> $SPY I get all my expert commentary / insight from Stonktwits 👌🏻😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:23:54 </td>
   <td style="text-align:left;"> $SPY Disney princess </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:23:48 </td>
   <td style="text-align:left;"> $SPY turd dropping tomorrow. Long volatility here as we stay range bound 420-460 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:23:35 </td>
   <td style="text-align:left;"> $SPY recession is here. we see limit down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:23:30 </td>
   <td style="text-align:left;"> $SPY This heals my soul when I don&amp;#39;t feel right. 
https://www.youtube.com/watch?v=tUEJkwA1VI4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:23:22 </td>
   <td style="text-align:left;"> $DIS $SPY

Oh geez ...

&amp;quot;Florida’s Republican Gov. Ron DeSantis addressed on Thursday the suggestion of repealing a 55-year-old state law that allows Disney to effectively govern itself on the grounds of Walt Disney World, following the company’s public opposition to a controversial parental rights law in Florida&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:22:49 </td>
   <td style="text-align:left;"> $SPY s/o the drummer from weeper like that dance he does </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:22:26 </td>
   <td style="text-align:left;"> $SPY one day chart looks obsurd. No people can draw the line and say look </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:22:24 </td>
   <td style="text-align:left;"> $SPY calls beging of week puts today SPY paid nicely this week. Looking for an inside day tomorrow I&amp;#39;m thinking small green on the day anticipation of alot of sideways action options will decay away tomorrow. Small Green. Way to much headline risk for the weekend . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:22:12 </td>
   <td style="text-align:left;"> $SPY job report </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:22:06 </td>
   <td style="text-align:left;"> $SPY #wallStreetBets oh my god. This is amazing lmao. I wrote a bot that does something similar on StockTwits, but this guy takes it to another level lol.

https://youtu.be/USKD3vPD6ZA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:21:55 </td>
   <td style="text-align:left;"> WE ARE NOW LIVE🔥 
Im going to breakdown 👇 
📈 TRADE IDEAS 
🔫TRIGGERS 
🎯TARGETS  
👉https://us02web.zoom.us/j/86008942468 $spy #pressit  $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:21:48 </td>
   <td style="text-align:left;"> $SPY $MU Who needs WallStreetBets when you have Xtrades. Thanks to Xtrades, I have doubled my entire portfolio in just one week. Joining this Discord community was the best investment I&amp;#39;ve ever made!~! amazing-stocks-room.stockmarketus.xyz/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:21:30 </td>
   <td style="text-align:left;"> @OldFngGuy You still keeping that same energy? $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:21:17 </td>
   <td style="text-align:left;"> $SPY why can’t we all just get along </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:18:51 </td>
   <td style="text-align:left;"> $SPY FYI it&amp;#39;s global warming... NOT CLIMATE CHANGE!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:18:35 </td>
   <td style="text-align:left;"> $SPY selling puts around opening and riding calls back to $460… EASY 🎯🏁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:18:14 </td>
   <td style="text-align:left;"> $SPY this guy quiet in this group right now because he wasn’t looking at the $Vix yesterday 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:18:10 </td>
   <td style="text-align:left;"> $SPY we have unemployment numbers and Fed speakers tomorrow.  Which way will we go? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:17:57 </td>
   <td style="text-align:left;"> $SPY the SPY late night crew will arrive soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:17:44 </td>
   <td style="text-align:left;"> $SPY guys the fund rate, oil, covid, etc. Im just waiting for the professionals to weigh in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:17:26 </td>
   <td style="text-align:left;"> $SPY the war money is not done buying but they also like a bargain, think about it before making your next trade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:17:12 </td>
   <td style="text-align:left;"> $SPY we want 472 by 4/14 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:17:07 </td>
   <td style="text-align:left;"> $SPY can we all just buy now and pay later? Like when we&amp;#39;re dead? Seems to be a boomer theme.   
. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:15:51 </td>
   <td style="text-align:left;"> $BAC $SPY $AAPL Less not forget, in time for ER…https://www.cnbc.com/2018/02/14/amazon-and-bank-of-america-partner-for-lending-program-but-growth-has-stalled.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:15:23 </td>
   <td style="text-align:left;"> $SPY start building that pipeline, and building EV technology. Keep USA cranking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:15:20 </td>
   <td style="text-align:left;"> $SPY Where do you see the housing market going? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:15:12 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $IWM Rejected outside of trend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:15:06 </td>
   <td style="text-align:left;"> $SPY who got scared today?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:15:06 </td>
   <td style="text-align:left;"> $SPY just funny idiot bulls said they wouldn&amp;#39;t buy in until 460. Wonder how many got faked out bought in with limit orders and lost $$$. Seriously, quit looking at charts! Either hold long, or leave with your head between your legs and quit trading crap. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:14:15 </td>
   <td style="text-align:left;"> $SPY new IPhone just arrived sucka </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:14:09 </td>
   <td style="text-align:left;"> $SPY end of the quarter profit taking at the end there. Fresh money coming in tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:14:06 </td>
   <td style="text-align:left;"> $SPY are futures up or down.  I got no idea what I am even in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:13:44 </td>
   <td style="text-align:left;"> $NIO I’m not bullish on a damn thing… Too much uncertainty in the market and with mid terms coming up it’s gonna turn into the Wild Wild West I’m strictly day trading both long and short… You’ll be amazed how much 5, 10, 50 bucks adds up when you do it all day long… $SPY $QQQ $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:13:14 </td>
   <td style="text-align:left;"> Comparing $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:12:57 </td>
   <td style="text-align:left;"> Most active $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:12:39 </td>
   <td style="text-align:left;"> $SPY ded </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:12:37 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:12:01 </td>
   <td style="text-align:left;"> $SPY futures are why I have trust issues </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:11:53 </td>
   <td style="text-align:left;"> $SPY my prediction is more red for tomorrow and Monday and a move up into Tuesday and rest of next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:11:53 </td>
   <td style="text-align:left;"> $SPY $QQQ $MU there is no possible way we get 3 red days in a row. Got calls at 455 calls see ya tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:11:51 </td>
   <td style="text-align:left;"> $SPY just got 2 big azz ribeyes for 20.00 at meijers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:11:33 </td>
   <td style="text-align:left;"> $SPY child predators get treated like presidents NOWaDAys… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:11:13 </td>
   <td style="text-align:left;"> $SPY assuming Govt controls price of Gas is idiotic. That would make America a semi socialist state. Oil has not been about supply and demand for decades. Oil and gas prices run by hedge funds.  
 Wake up, take a red pill . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:11:11 </td>
   <td style="text-align:left;"> $SPY 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:11:06 </td>
   <td style="text-align:left;"> $SPY Why does a covid Vaccine Card come with 4 slots for Vax Shots? Why did they make them this way well before there was even 2 shots necessary??????? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:11:04 </td>
   <td style="text-align:left;"> $SPY Oh and I Just realized we have a 4hr bounce of the RSI trendline. VIX, OI option $$ and RSI all have setups now! (Click to see as always). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:11:01 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;ve been preparing for this $BABA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:10:48 </td>
   <td style="text-align:left;"> $SPY if you think this will be green tomorrow, and you have calls, you are in for a powerful amount of pain. -2% minimum by end of day. Play intraday calls only, or hold your puts and don’t even watch the screen tomorrow. Check in before the bell and enjoy the weekend. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:10:27 </td>
   <td style="text-align:left;"> $SPY 460 tomorrow folks 

Don’t miss it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:10:19 </td>
   <td style="text-align:left;"> $SPY that plunge was hilarious. Easiest short ever. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:10:10 </td>
   <td style="text-align:left;"> $SPY how come my posts don’t have ads with cool chicks from ST and everybody else’s does. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:10:01 </td>
   <td style="text-align:left;"> $SPY red tomorrow boys. my donkey senses are tingling that means my puts are going to be printing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:09:35 </td>
   <td style="text-align:left;"> $spy expect it to do the unexpected tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:09:05 </td>
   <td style="text-align:left;"> $SPY Who is bullish tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:08:57 </td>
   <td style="text-align:left;"> $SPY This goes out to my gay bears and bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:08:43 </td>
   <td style="text-align:left;"> $SPY $LGVN $GME  
 
Serious question: 
 
How much would you pay (hypothetical) someone per month who provided daily and weekly watchlists, intraday alerts, provided live access to their Trade Ideas scanner, live traded everyday with you, and offered tutorial videos and notes? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:08:34 </td>
   <td style="text-align:left;"> $SPY Divided States of Banana Americas. Money and Crime are Free </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:08:31 </td>
   <td style="text-align:left;"> $SPY be careful out there Futes ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:08:11 </td>
   <td style="text-align:left;"> $SPY Come on Jill, he just wanted sniff her hair. 

https://youtube.com/shorts/Mdp6KHG4E9o?feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:08:03 </td>
   <td style="text-align:left;"> $SPY ill go on vacation for a month if this open above  455 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:08:00 </td>
   <td style="text-align:left;"> $SPY big DIX visualized </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:07:58 </td>
   <td style="text-align:left;"> $SPY not a bear or bull here, what are we looking at tomorrow ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:07:56 </td>
   <td style="text-align:left;"> $SPY some evening humor </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:07:36 </td>
   <td style="text-align:left;"> $SPY during recession, the most valuable item is not food

Its water, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:06:47 </td>
   <td style="text-align:left;"> $SPY the freaks come out at night </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:06:46 </td>
   <td style="text-align:left;"> $SPY i hate people that cause fear

Recession is nothing, you can always move to China, it&amp;#39;s the same, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:05:31 </td>
   <td style="text-align:left;"> $SPY way more to go 
 
A dozen S&amp;amp;P 500 stocks just had their worst quarter ever, as tech stocks sloughed off nearly $2 trillion in value </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:05:13 </td>
   <td style="text-align:left;"> $SPY $5B to sell at the close today! compare that to the previous few days to see the magnitude. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:05:11 </td>
   <td style="text-align:left;"> $SPY 100% cash. 
https://www.youtube.com/watch?v=UJWk_KNbDHo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:04:33 </td>
   <td style="text-align:left;"> $SPY its sad when everyone knows FED is killing the American dream but FED doesn’t dream…..They have stopped dreaming decades ago actually. They set the game until its over, instead of keeping the game going, maybe losing at half time but still in the game. Sucks for all of us but maybe thats whats needed is to end FED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:03:53 </td>
   <td style="text-align:left;"> $DVN: Inverse head and shoulders setting up here. Buy some dated calls. Should pay nicely in the near future. 
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:03:07 </td>
   <td style="text-align:left;"> $SPY I bet futes are ripping rn

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:03:06 </td>
   <td style="text-align:left;"> $SPY narrative is now “recession is good, it will fix inflation…” …. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:02:59 </td>
   <td style="text-align:left;"> $SPY the funny think about markets, is the target weaknesses. Investor/trader behavior is a huge target of weakness. Chasers get burned, because they panic. 

And it goes both ways, though the snicker sell is more prevalent at the beginning of a new trend after a sell off. 

Go back 2 years to the day. @PurpleReign8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:02:50 </td>
   <td style="text-align:left;"> $SPY SPY 2022-03-31 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=vl0NuXb_vIk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:02:38 </td>
   <td style="text-align:left;"> $CFVI $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:02:14 </td>
   <td style="text-align:left;"> $SPY big sell off to look positive for quarter on books. Will see relief tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:01:46 </td>
   <td style="text-align:left;"> $SPY 🔥😏 April fools can be epic. New quarter. Rip to 460 then rug to 448... imagine that shit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:01:30 </td>
   <td style="text-align:left;"> $KR: Testing my patience but such a bullish looking chart here. Continues to consolidate after the ER gap up. Should breakout any day now. However, if this breaks under 55, this most likely going to fill the gap below. 
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:01:13 </td>
   <td style="text-align:left;"> $SPY damnit not gonna be able to sleep tonight thinking about a epic lotto Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:00:56 </td>
   <td style="text-align:left;"> $SPY Haven’t seen this one in a while lol 😝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:00:51 </td>
   <td style="text-align:left;"> https://seekingalpha.com/article/4499108-adding-etsy-to-your-portfolio?mailingid=27219389&amp;amp;messageid=2800&amp;amp;serial=27219389.4788&amp;amp;utm_campaign=rta-stock-article&amp;amp;utm_medium=email&amp;amp;utm_source=seeking_alpha&amp;amp;utm_term=27219389.4788

$spy $etsy $qqq $dia $iwm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:00:46 </td>
   <td style="text-align:left;"> FUTES SENSATIONAL $spy $QQQ  
 
Are we back to the regime of stonks only up? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:00:45 </td>
   <td style="text-align:left;"> $SPY for anyone that looted a business or 2 last year tax day is approaching </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:00:33 </td>
   <td style="text-align:left;"> $spy not posting for bullish bearish implication, but interesting flat 20sma and price sitting on top….looks cool🤷‍♂️🍻. See what happens when it gets to the 50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:00:14 </td>
   <td style="text-align:left;"> $SPY China invading Taiwan will be a black swan or a grey rhino? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 08:00:05 </td>
   <td style="text-align:left;"> $SPY in the 1930 something, the biggest impact of a barrel of oil is not the price of the oil, but the price of the steel tin that carry the oil,

Mind blown </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:59:58 </td>
   <td style="text-align:left;"> $SPY so you&amp;#39;re telling me that my 19.5% raise at work is only like 9.5% after inflation. Cool, I only worked my ass off for that raise for 2 years. Thanks Dems. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:59:49 </td>
   <td style="text-align:left;"> $SPY probably flat open small red to get more puts then 460s again 😭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:59:46 </td>
   <td style="text-align:left;"> $SPY gonna be bad for the market if the burn us tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:59:44 </td>
   <td style="text-align:left;"> $SPY $QQQ Recession in 6-12 months </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:59:26 </td>
   <td style="text-align:left;"> $SPY This whole Russia Ukraine situation hasn&amp;#39;t even begun. Mr Workman&amp;#39;s opinion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:59:25 </td>
   <td style="text-align:left;"> $SPY $QQQ $DXY $NASDAQ nobody is realizing that the end of USD power is very good news for stock market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:59:14 </td>
   <td style="text-align:left;"> Social medias incentivize bold claims (majority lies and a supper tiny lucky ones), this feature induces bias in your decision making. ST reward gambling ideas on speculative extreme reward/extreme risk, but it makes you broke, ignore the noise. The boring, slow, unemotional truth is not highlighted anywhere in the media (especially social media). boring facts do not sell and draw attention. $SPY, $QQQ, $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:59:14 </td>
   <td style="text-align:left;"> $MSFT $SPY $BRK.B $VTI ’cause I’ve seen better days. Been the star of many plays. I’ve seen better days. And the bottom drops out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:59:06 </td>
   <td style="text-align:left;"> $SPY is the bear market over? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:58:59 </td>
   <td style="text-align:left;"> $SPY $SPX #ES_F 
What a load of bullocks 
Tom Lee said $500 by May </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:58:52 </td>
   <td style="text-align:left;"> $SPY a barrel of oil is 100, by gas station is twice as much, I rather pump a barrel of oil into my car than a gas station </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:58:48 </td>
   <td style="text-align:left;"> $QQQ $SPY Shorts tomorrow gonna be like…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:58:22 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures higher, looks like the market will start Q2 with a bang tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:58:18 </td>
   <td style="text-align:left;"> $SPY how to buy barrel of oil and pump into my car, without gas station </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:57:57 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:57:45 </td>
   <td style="text-align:left;"> $SPY madness </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:57:44 </td>
   <td style="text-align:left;"> $SPY Only hermits living under rocks are unaware of Hunter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:57:20 </td>
   <td style="text-align:left;"> $SPY joe Biden son smokes crack….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:57:18 </td>
   <td style="text-align:left;"> $SPY i think i figured this out…gov will default before they let 401ks crash. So calls until news of default then switch to puts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:57:11 </td>
   <td style="text-align:left;"> $SPY big selling volume eod. Anybody see that continuing at market open? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:56:49 </td>
   <td style="text-align:left;"> $SPY well Joe you are really a clown </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:56:47 </td>
   <td style="text-align:left;"> $SPY 
Thank god we finally broke the 453 down. Now next stop 445 fib. Hope it doesn’t take as long to get there! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:56:37 </td>
   <td style="text-align:left;"> $GME Plans to issue a stock dividend in the form of a stock split. Guess who did this before multiplying their market cap in the process?  $AAPL and $TSLA 

Good luck short sellers. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:56:18 </td>
   <td style="text-align:left;"> $SPY In 2008 we had hiked 8 times before we inverted. These fukn clowns are going into inversion at basically at zero fed rate. At some point market has to take a bullet or whole fiat system will collapse. American dollar has never been weaker. You need spy 40% gains to break even you idiots. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:55:58 </td>
   <td style="text-align:left;"> $AMC last chance to MOON ...  
just bought 12K Last dry powder $spy  
 
LFG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:55:51 </td>
   <td style="text-align:left;"> $SPY back to 460 then it’s ova </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:55:51 </td>
   <td style="text-align:left;"> $SPY what happens when oil drops into the 90’s tomorrow 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:55:28 </td>
   <td style="text-align:left;"> $SPY not sure if you guys covered this @HatchingGains  @Callum_Thomas . Btw I looked in my followers and I couldn&amp;#39;t find you. Had to search hard for you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:54:45 </td>
   <td style="text-align:left;"> $SPY Short all pops tmrw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:54:41 </td>
   <td style="text-align:left;"> $SPY my fucking tater tots </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-04-01 07:54:40 </td>
   <td style="text-align:left;"> $SPY CNBC said futes look good, pre-order lambo. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 09:01:48 </td>
   <td style="text-align:left;"> $QQQ european markets gonna crash $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 09:00:48 </td>
   <td style="text-align:left;"> $AAPL $QQQ - RSI and MACD support a fall in price. If Apple doesn&amp;#39;t break $178 and remain or if we continue 3-4 more days of selling, Apple could head back down to the $150s. Personally, its still a VERY overpriced stock as it was trading at $30-50s in 2018-2019, yet, during the LARGEST unemployment event, pandemic, and steep recession, Apple somehow hit $130 in Aug 2020. This clearly tells you the stock is bloated. While to us it seems insane that Apple could drop to $140, even at that price its overvalued. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:59:50 </td>
   <td style="text-align:left;"> $QQQ $SPY 3 more years of this smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:58:58 </td>
   <td style="text-align:left;"> $SPY $QQQ When the EU is de-industrialized in the next decade without cheap energy they won’t matter anyways. In the long run cheap energy and goods made from it always wins. That’s how the China-Russia alliance will completely de-industrialize the west except for the US.

Europe is gonna be the biggest loser in the NWO. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:57:25 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA 

This feels like the peak of fear at the end of Monday March 14, just before the face ripping one week rally of 10+%. 
How many bears were so sure that we will have an epic market collapse on Tuesday, March 15, eh? How many were counting their puts would print bigly? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:52:35 </td>
   <td style="text-align:left;"> $SPY CATALYST: Non-Farm Payrolls Economic Data will be released on Fri. Apr. 1 at 8:30 AM. 
 
View details and track upcoming catalysts: https://www.catacal.com/catalyst/non-farm-payrolls-3 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:52:12 </td>
   <td style="text-align:left;"> $QQQ $SPY 

Now that they have the end-of-quarter options expirations, it only adds to more volatilities and more premium money for MM’s to make. 

This is absolutely criminal. Soon, they will like to have options expiring everyday! 

I remember back when there were only monthly options. Those were the good days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:50:13 </td>
   <td style="text-align:left;"> Current 2&amp;amp;10 spread: .0051

$NASDAQ $QQQ $SPY $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:49:50 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:47:35 </td>
   <td style="text-align:left;"> $QQQ stock analysis based on today&amp;#39;s closing price 

https://youtu.be/HZfNuO4EcwM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:47:12 </td>
   <td style="text-align:left;"> $SOFI I love to read all the negative comments (easy to bash and hard to build). People pretend not to understand that innovation in the fintech area is key, and the model of big banks will change dramatically in the next few years. Online banking and the innovative tools will provide successful solutions in an environment where low/no cost is critical to  customers, as well as the competition and generating better profits.  Tomorrow is a new month, new quarter and a new day....  
$SPY $QQQ should have a beautiful day and the whole market should join the party 
SOFI to the MOOOOOOOOOOOOOOOOOOOOOOOOON!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:46:33 </td>
   <td style="text-align:left;"> $SPY $QQQ $SQQQ $TQQQ Just an idea. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:44:40 </td>
   <td style="text-align:left;"> $SPY $QQQ $SOFI $GME 🌚🍟 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:44:38 </td>
   <td style="text-align:left;"> $QQQ call holders beware. This market looks like it&amp;#39;s gonna get weird real quick. Candles on the weekly, daily, hourly and 15 minute are all pointing to a bearish reversal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:43:25 </td>
   <td style="text-align:left;"> $SPY $QQQ In Venezuela everyone is fit except empanada eating Maduro. In the new Bidenzuela economy we will all be healthy and fit. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:40:49 </td>
   <td style="text-align:left;"> $QQQ all time high tomorrow??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:39:46 </td>
   <td style="text-align:left;"> $GME ===&amp;gt; $240  by FRIDAY CLOSE!  😊🎊🎉🎈🔥🚀🚀🚀 
. 
$SPY $QQQ  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:37:53 </td>
   <td style="text-align:left;"> $QQQ Futes Trippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:37:30 </td>
   <td style="text-align:left;"> $SPY $QQQ I wish I would&amp;#39;ve traded some $GME when it was under $100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:37:24 </td>
   <td style="text-align:left;"> $QQQ 

call and put buyers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:37:06 </td>
   <td style="text-align:left;"> $QQQ $NDX -- not a great close today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:35:28 </td>
   <td style="text-align:left;"> US mortgage rates climb steeply, slowing housing boom

https://www.aljazeera.com/amp/economy/2022/3/31/us-mortgage-rates-climb-steeply

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:34:46 </td>
   <td style="text-align:left;"> The US reportedly watered down sanctions against a key Russian oligarch out of fear that disrupting his business empire could hurt the global economy

https://www.businessinsider.com/us-treasury-watered-down-sanctions-russian-oligarch-alisher-usmanov-report-2022-3?amp

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:33:13 </td>
   <td style="text-align:left;"> $QQQ even cramer said we oversold 🤣
Gonna look meet kevin and kevin oleary next 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:32:34 </td>
   <td style="text-align:left;"> $SPX $SPY $IWM $QQQ $VIX Market Reversal Confirmed - Where are the supports  https://youtu.be/l-lPt4KyUsM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:32:29 </td>
   <td style="text-align:left;"> $SPY US equities will always be one of the best assets you can own. buyers will always step in. short term have fun bears, but don’t get too comfortable 😉 

$qqq $arkk $djia $iwm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:31:12 </td>
   <td style="text-align:left;"> $QQQ I got bitches and they buy me clothes…or at least used to $SPY $HOOD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:29:13 </td>
   <td style="text-align:left;"> $SPY next main candle daily ends @ 4450

    $spx  $qqq   $dia   $ndx  🏷  

                 Had to tag it    🏷. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:28:58 </td>
   <td style="text-align:left;"> $QQQ  The &amp;quot;200 pound /dma&amp;quot; Gorilla...Can&amp;#39;t get that monkey off the QQQ&amp;#39;s back... as of late: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:28:09 </td>
   <td style="text-align:left;"> $SPY $QQQ this could be a real ominous weekly candle…unless we get a push up tomorrow.  I think we get a big green one tomorrow.  💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:27:23 </td>
   <td style="text-align:left;"> $SPY $QQQ Futes look good! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:26:53 </td>
   <td style="text-align:left;"> $QQQ $NVDA Who needs WallStreetBets when you have Xtrades. Thanks to Xtrades, I have doubled my entire portfolio in just one week. Joining this Discord community was the best investment I&amp;#39;ve ever made!!~! amazing-stocks-room.stockmarketus.xyz/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:26:40 </td>
   <td style="text-align:left;"> $SPY you scammers     $ndx   $nasdaq  $qqq 

$SPX  likely drops another -$100 overnight    

There’s now in play lower gaps that fill </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:26:19 </td>
   <td style="text-align:left;"> $QQQ 340 now. Whip saw man </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:25:00 </td>
   <td style="text-align:left;"> $QQQ we gap down pre market? Bought tqqq before the dip😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:15:12 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $IWM Rejected outside of trend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:13:44 </td>
   <td style="text-align:left;"> $NIO I’m not bullish on a damn thing… Too much uncertainty in the market and with mid terms coming up it’s gonna turn into the Wild Wild West I’m strictly day trading both long and short… You’ll be amazed how much 5, 10, 50 bucks adds up when you do it all day long… $SPY $QQQ $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:11:53 </td>
   <td style="text-align:left;"> $SPY $QQQ $MU there is no possible way we get 3 red days in a row. Got calls at 455 calls see ya tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:11:30 </td>
   <td style="text-align:left;"> Watch list for tomorrow part 2: $QQQ $DWAC $TWTR $THCA $LGVN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:10:35 </td>
   <td style="text-align:left;"> $QQQ I think we may see a big sell-off which looks to have started today. There is too much uncertainty going on with sky high inflation that is not slowing down. The ultimate recession indicator is on the verge of going off with the 2/10 year bond yield about to invert. Russia is not backing off on demanding payment in rubles for energy exports to Europe. 

Wheat/fertilizer market supply is threatening world food supply. Feds will most likely raise rates by 50 basis points very soon. I don&amp;#39;t think people realize how dire the economic situation we are in. Feds have no idea how to handle this, they will try to keep the public calm but the walls are cracking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:05:12 </td>
   <td style="text-align:left;"> SweepCast alerted: $QQQ with Unusual Options Activity Alerted on $370 CALL Expiring: 06-30-2022 worth 394K🐂 |🥇 Start Your Trial by Joining Our StockTwits Premium Room or Visit Website in Profile! 🥇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:01:47 </td>
   <td style="text-align:left;"> $QQQ pullback into the uptrend line that was used as an extension guardrail from the prior rallies. Now let&amp;#39;s see if it provides support tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:00:51 </td>
   <td style="text-align:left;"> https://seekingalpha.com/article/4499108-adding-etsy-to-your-portfolio?mailingid=27219389&amp;amp;messageid=2800&amp;amp;serial=27219389.4788&amp;amp;utm_campaign=rta-stock-article&amp;amp;utm_medium=email&amp;amp;utm_source=seeking_alpha&amp;amp;utm_term=27219389.4788

$spy $etsy $qqq $dia $iwm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 08:00:46 </td>
   <td style="text-align:left;"> FUTES SENSATIONAL $spy $QQQ  
 
Are we back to the regime of stonks only up? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:59:44 </td>
   <td style="text-align:left;"> $SPY $QQQ Recession in 6-12 months </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:59:31 </td>
   <td style="text-align:left;"> $BTC.X $BCH.X $DJIA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:59:25 </td>
   <td style="text-align:left;"> $SPY $QQQ $DXY $NASDAQ nobody is realizing that the end of USD power is very good news for stock market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:59:14 </td>
   <td style="text-align:left;"> Social medias incentivize bold claims (majority lies and a supper tiny lucky ones), this feature induces bias in your decision making. ST reward gambling ideas on speculative extreme reward/extreme risk, but it makes you broke, ignore the noise. The boring, slow, unemotional truth is not highlighted anywhere in the media (especially social media). boring facts do not sell and draw attention. $SPY, $QQQ, $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:58:48 </td>
   <td style="text-align:left;"> $QQQ $SPY Shorts tomorrow gonna be like…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:58:22 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures higher, looks like the market will start Q2 with a bang tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:58:12 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOG $QQQ load uppp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:57:06 </td>
   <td style="text-align:left;"> $QQQ when you look at your life, and stocktwits aint helping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:55:02 </td>
   <td style="text-align:left;"> $QQQ 0.8 basis points between the 2/10 year bond yields.. don&amp;#39;t think anything is going to be major but it is interesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:54:00 </td>
   <td style="text-align:left;"> In the last month $QQQ has a been trading in the 317.45 - 371.83 range, which is quite wide. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:51:30 </td>
   <td style="text-align:left;"> $QQQ room 362 get at us 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:50:03 </td>
   <td style="text-align:left;"> $QQQ $SPY

Hey when is that crudely worded tweet coming out regarding the oil reserve stuff? Will he mention which public companies get to refine it? 

Please let me know! I’m not used to this new schedule 🤣

Ok, good night. Make sure to smoke lots of crack and watch futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:48:51 </td>
   <td style="text-align:left;"> $QQQ Haha 
 
Beartards all on here rejoicing its over. 
 
Its not. 
 
LMFAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:48:33 </td>
   <td style="text-align:left;"> $SPY  $QQQ what a scam artist politician..anything to point the finger..oh wait..GAS WAS ALREADY GOING WAY UP BEFORE THE WAR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:46:42 </td>
   <td style="text-align:left;"> $SPY $QQQ California getting free gas cards? Sweet let’s increase demand with free money and eat through more of the reserve oil while not fixing the production of new oil. I’m buying up oil and natural gas stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:41:58 </td>
   <td style="text-align:left;"> $QQQ oil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:40:19 </td>
   <td style="text-align:left;"> $SPY $QQQ Gov making a nice buying opportunity for the banks to make bank, nice pun huh. Biden not fixing the problem, just making it worse, but great for the banks to position in Oil and natural gas investments </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:35:19 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA 

0331 baby!! No better way to end it on a red day. Machine gunners definitely bought poots.😤😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:35:05 </td>
   <td style="text-align:left;"> $QQQ did you follow my twitter. Made money again using my daily tradeplans. Making money every day! Follow my twitter if you wish to use the daily trade plans I post there @optionboys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:34:20 </td>
   <td style="text-align:left;"> $SPY $QQQ Don&amp;#39;t forget April is historically one of the best months of the year for the market, even in midterm years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:27:12 </td>
   <td style="text-align:left;"> Gorgeous ascending triangle on futes 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:26:36 </td>
   <td style="text-align:left;"> $QQQ Morons lol....up 0.60c and bulls are celebrating 🤣🤡🔻🚽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:26:35 </td>
   <td style="text-align:left;"> $SPY $QQQ Bulls when we have two red days after a ridiculous three week bull run😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:25:20 </td>
   <td style="text-align:left;"> $QQQ remember when markets were bright Green all futures session yesterday Only to bleed all day? Ya, me too. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:25:00 </td>
   <td style="text-align:left;"> $SPY “come man give me a break” 

$QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:23:29 </td>
   <td style="text-align:left;"> Market Finally Sells-Off ahead of the Friday Jobs Report - What We&amp;#39;re Seeing Now $QQQ $XLF $DJI $SPX https://talkmarkets.com/content/stocks--equities/market-finally-sells-off-ahead-of-the-friday-jobs-report-what-were-seeing-now?post=349955 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:20:21 </td>
   <td style="text-align:left;"> $QQQ lookin&amp;#39; for a backtest to $360 on this prior downtrend. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:18:41 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA Someone tell Brandon that oil reserves are meant for times of emergency and war... not for agenda and election. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:18:37 </td>
   <td style="text-align:left;"> $QQQ $VIX is about to spike tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:15:38 </td>
   <td style="text-align:left;"> $QQQ Biden wants to burn  $35.00 per barrel oil out of the strategic reserves and then buy $100 a barrel oil from terrorists 

This moron will sink the markets to all new time lows yet! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:14:18 </td>
   <td style="text-align:left;"> $SPY $QQQ You know it’s bad when they have to tap into the reserve barrels 😅. Yet stocks just on going higher lol. It’s not our fault. They are creating this bubble. Cpi will look stupid in April lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:10:39 </td>
   <td style="text-align:left;"> $SPY you scammers     $ndx   $nasdaq  $qqq   

There’s now in play lower gaps too fill </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:08:46 </td>
   <td style="text-align:left;"> $QQQ $SPY  tomorrow it’ll drop some more👍👍👍🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:08:40 </td>
   <td style="text-align:left;"> $QQQ $SPY 

Face ripper tomorrow! Repeat of Tuesday March 15 that started 10+% rally in one week! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:07:20 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM

$1k -&amp;gt; $1m challenge update:

Day 0
Starting amount: $1,000
Current amount: $1,000
Target: $1,000,000 

1st challenge was a success getting from $1k to $100,000 in about 3 months trading SPY options.

Now I will be looking to take this a step further and hit that $1,000,000 mark.

All trades will be alerted real time in the discord, and will cataloged daily on here.

Once again I’m simply trying to prove the sheer impact of compounding. My game plan is to look for 15-20% trades on options daily, and simply compound all profits while keeping tight SLs and proper risk management to minimize the downside on all plays. 

Paired with our in-house options strategy that has yielded and over 85% success rate over 4 months I’m confident we will be able to get this challenge from $1k to $1m within hopefully 4-6 months.

Follow along for the ride 🏄‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:07:03 </td>
   <td style="text-align:left;"> $SPY Do you want to see the truth 

Just caught this headline $QQQ $DIA $DJIA 

. $ES_F   I do not want to hear your B.S 

                   Anymore about peace. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:04:46 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $SPX $NASDAQ  The Truth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:02:10 </td>
   <td style="text-align:left;"> $SPY $QQQ Despite all these people on StockTwits constantly boasting about their MIRACULOUS successes, I promise you most retail traders (especially those playing options) have been getting absolutely fucked this year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 07:00:54 </td>
   <td style="text-align:left;"> $SPY EOM OPEX turned into a gigantic bear trap with that EOD volume. Sleep tight. 🥳 $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:58:38 </td>
   <td style="text-align:left;"> https://www.youtube.com/watch?v=H0V6_VgPUjU $amzn $tsla $nvda $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:57:49 </td>
   <td style="text-align:left;"> $UVXY $QQQ engineered drop. The market can&amp;#39;t go down far once the printing press prints $$$ to prop it up. Mostly such drops are to simulate a sense of fairness and normalcy but always to catch retails and make them bagholders. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:54:46 </td>
   <td style="text-align:left;"> $QQQ $SPY Look at this put buy on SPY
Ohhhh baby....
🔻🔻🔻🚽🚽🚽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:54:03 </td>
   <td style="text-align:left;"> $SPY $QQQ market is tough to trade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:52:54 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $SPY $QQQ This is the most important chart in crypto right now. Pearson chart of the correlation between Spy and BTC: key takeaways are 1) long term the correlation is near 0 (no correlation) and 2) Whenever the correlation gets high (correlated), it always snaps back to the long term average near 0. Usually going negative for a while (inversely correlated) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:52:07 </td>
   <td style="text-align:left;"> $SPY $QQQ Any news after hours ? It big green after close ; wtf they make bear trap ? I bought sqqq and they trapped me ? lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:51:10 </td>
   <td style="text-align:left;"> $SPY $QQQ $SQQQ $TQQQ Tomorrow I’ll be looking for entry at $445 with a tight stop loss at $442. Hopefully I can ride that to $460 and decide from there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:50:49 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $VIX anyone know what triggered that sell off at 3:50? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:49:38 </td>
   <td style="text-align:left;"> $QQQ Double top </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:49:34 </td>
   <td style="text-align:left;"> Stock futures bounce as investors assess start of new quarter, bond market recession indicator

$SPY $DJIA $QQQ

https://www.cnbc.com/2022/03/31/stock-market-futures-open-to-close-news.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:49:34 </td>
   <td style="text-align:left;"> $QQQ futures unstoppable: it feels like the March low all over again - next massive leg higher starts tomorrow!!!! $spy $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:49:27 </td>
   <td style="text-align:left;"> $QQQ me, when I get rich </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:48:27 </td>
   <td style="text-align:left;"> Futures green 😈
$SPY $QQQ $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:47:44 </td>
   <td style="text-align:left;"> $QQQ $SPY  LABOR REPORT EXPECTATIONS?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:46:12 </td>
   <td style="text-align:left;"> $QQQ $SPY You gotta love the shenanigans AH &amp;amp; PM with futures. What a joke.  If you actually believe we&amp;#39;re going to bounce higher here, you better get ready to bend over and have your lube ready. 
Any smart investor knows MORE PAIN IS COMING. 
🔻🔻🔻🚽🚽🚽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:45:53 </td>
   <td style="text-align:left;"> $QQQ 361 in extended hours 😁💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:42:49 </td>
   <td style="text-align:left;"> $QQQ 

This should be around $364.5 not $363 in AH. WTF? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:42:43 </td>
   <td style="text-align:left;"> $DIA $QQQ $SPY VERY red tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:41:22 </td>
   <td style="text-align:left;"> $QQQ did you follow my twitter. Made money again using my daily trade plans. Making money every day! Follow my twitter if you wish to use the daily trade plans I post there  @optionboys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:40:29 </td>
   <td style="text-align:left;"> $SPY $qqq

Feel dejavu all over again... It was like this yesterday AH 
Futes green then market open bam -- red!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:40:02 </td>
   <td style="text-align:left;"> $QQQ Day trade🎉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:39:30 </td>
   <td style="text-align:left;"> $QQQ $SPY

MAN! I could really use an opinionated tweet related to a publicly traded company from someone in a high ranking government position right now! 

SAD! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:39:11 </td>
   <td style="text-align:left;"> $SPY  $QQQ Futures green ; so was bear trap at close again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:35:53 </td>
   <td style="text-align:left;"> $QQQ you may laugh at this but this is why we need strong action hero like leadership in gov. Not discussing transgender rights and all that just plain efficiancy and someone who does what he needs to. Left was never known for that. Yes we have had som good leaders from the left through history but generally speaking they are con men. 

Putin did his part for his country. So did China. Now Europe is in shambles and hard working U.S intelligence and gov workers have been screwed by their leader. Sad, sad times if we dont vote them out of Australia, Canada, Scandinavia and Europe. Bring back the strong ones </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:31:09 </td>
   <td style="text-align:left;"> Daily Market Recap for Thursday 3/31/2022 for #Stocks #Bitcoin #Gold and #Silver
https://youtu.be/2VA37dR6G7k

$SPY $QQQ $IWM $TLT $UUP

Nailing this market action. It not hard if you know the repeating patterns.  Cheers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:31:01 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Retest and take out the lows 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:30:25 </td>
   <td style="text-align:left;"> $QQQ they really ran all the moves those last 3 hours. Smaller candle, doji to upside then lower low candle to the next level.  Ha!  Love it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:29:32 </td>
   <td style="text-align:left;"> CONGRATULATIONS ON THE WIN 🌟 AMAZING TRADE CALLED OUT JUST BEFORE THE SOUR HOUR TODAY. LAST 15 MINUTES WERE LIT 🔥 MADE OVER 90% PROFITS ON THIS ALERT. 

JOIN OUR PREMIUM STOCKTWITS ROOM FOR MORE TRADE ALERTS &amp;amp; IDEAS:
https://rooms.stocktwits.com/checkout/4560671/prod_Kpk7ezeIDS8ksT

FOLLOW THIS ACCOUNT TO GET REAL TIME NEWS UPDATES. 

$TSLA $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:29:21 </td>
   <td style="text-align:left;"> Software engineers caught doing a bad BAD thing for some sweet cha-ching https://www.billionaireclubcollc.com/software-engineers-caught-doing-a-bad-bad-thing-for-some-sweet-cha-ching/  $DJIA $SPY $QQQ $DXY $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:28:57 </td>
   <td style="text-align:left;"> $QQQ 
🇺🇸🇺🇸🇺🇸

https://youtu.be/giXco2jaZ_4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:28:31 </td>
   <td style="text-align:left;"> $SPY $USO $DJIA $LABU $QQQ 2-year Treasury yield tops 10-year rate, a ‘yield curve’ inversion that could signal a recession

https://news.alertsandnews.com/2-year-treasury-yield-tops-10-year-rate-a-yield-curve-inversion-that-could-signal-a-recession/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:25:26 </td>
   <td style="text-align:left;"> $QQQ I bet this goes back to $352 over then next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:24:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY The brics countries want to change the world order. Its starting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:23:49 </td>
   <td style="text-align:left;"> $SPY $QQQ apparently the sell off today was “only” due to end of quarter rebalancing funny business 🙄. However, if the markets would have ripped into the close, then the narrative would have been “big money wants to get in before end of quarter rebalancing!” 🚀. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:21:46 </td>
   <td style="text-align:left;"> $QQQ growth is in shambles. Buy commodities and short $ARKK and any of your other favorite trash growth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:19:54 </td>
   <td style="text-align:left;"> $QQQ $SPY 

Why the AH prices are not following the futures as much?? 

Is this quarterly dividend adjustments or something? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:19:14 </td>
   <td style="text-align:left;"> $QQQ $SPY a round of applause to PCE… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:18:55 </td>
   <td style="text-align:left;"> $SPY $QQQ $SPX $DJIA If new gov ends up hitting the true all time high button : </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:16:01 </td>
   <td style="text-align:left;"> $QQQ why so many Democrat drinking Biden&amp;#39;s kool-aid about economy 🤔.  Russia turned of gas to Europe will sell only in rubles.  Meaning USD dollar isn&amp;#39;t the main currency anymore for fuel!!! Like it was I  1950s. Brandon is staring to empty US militarily oil reserves !!!!!!! Because NO One whant to deal with him for oil!!! India made a deal with Russia to buy their oil/gas in Rubles. China, Brazil and all Arabic countries will start deal with Russia in Rubles eventually. Europe will be broke soon. Nato and USA will have No oil to figth anyone soon. Just because thkse dumb twits don&amp;#39;t what to open Alberta and Texas pipe. Putin&amp;#39;s approved rate is over 80% !!! Biden&amp;#39;s approved rates is dropping at the rate that I don&amp;#39;t even know it is atm. And everyone is saying US economy is never been so strong. Inflation! Is through the roof.... anyway Let&amp;#39;s go Brandon!!!! We need Trump back ASAP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:15:37 </td>
   <td style="text-align:left;"> I knew the market would be red today so I put on my red lights this morning in my trading room. My $FB $QQQ $SPY $AMD.. Puts did very well today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:15:08 </td>
   <td style="text-align:left;"> $QQQ Bears time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:14:54 </td>
   <td style="text-align:left;"> UK MILITARY INTELLIGENCE: RUSSIA IS REDEPLOYING FORCES FROM GEORGIA TO BOLSTER ITS INVASION OF UKRAINE. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:14:21 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA Brandon blaming oil companies for price gouging today is an embarrassment to the Democratic party, an insult to Moderates and Republicans. Releasing 1/3 of our reserves for political reasons and agenda is a disgrace and reckless. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:12:50 </td>
   <td style="text-align:left;"> Alert on $SQQQ delivered today at 11:24AM CDT on 3/31/2022 🎯 

Real-time alerts in the link on my bio. $TQQQ $QQQ $NQ_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:10:25 </td>
   <td style="text-align:left;"> $QQQ love when I see these headlines. Bring on the fear. Perfect recipe for wall of worry lockout rally. Now let’s get a nice pullback for some huckleberry dip buys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:10:02 </td>
   <td style="text-align:left;"> Market was red today? 
 
Sorry we didn&amp;#39;t notice $LGVN 100% blinded us 🚀 
 
5 buy alerts 1st at $10 last at $14, last TP at $14.55 🎯 
 
Total March +207.5% gain with 2 red and 2 breakeven days 💯 
All alerts called out live with full trade plan 
 
Bring it on April💪🏼 
 
$spy $qqq $dia $btc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:09:19 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-03-31 Daily Forecast Video: 
https://www.youtube.com/watch?v=NKIdotknRrY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:08:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:07:40 </td>
   <td style="text-align:left;"> $QQQ anyone else see it?? Then likely trade within the lower green/red range until end of year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:07:15 </td>
   <td style="text-align:left;"> $QQQ Futes are ripping!! Lol its April fools here in Sweden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:05:18 </td>
   <td style="text-align:left;"> $QQQ $SPY 

Futures are RIPPING!!!!!!

LFG! 🚀🚀🚀🚀🚀🔥🔥🔥🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:05:15 </td>
   <td style="text-align:left;"> $SQQQ Nice to be in the green again --   folks should note the large green candles going into the close, which is usually a good indicator that more gains can be expected tomorrow.  However, I heard one source today, suggest that the red in $QQQ may have been related to institutional end-of-quarter rebalancing of portfolios to reflect 60% stock/ 40% bond ratios -- as the recent run in stocks may have caused portfolios to become stock &amp;quot;top-heavy&amp;quot; requiring some selling of stocks, and buying of bonds.  As for me, I&amp;#39;m holding all my shares,  @ $33.12 ave, at least for now... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:04:28 </td>
   <td style="text-align:left;"> $QQQ $AMD $SPY that feeling when you take a five figure L and book your weekend resort trip on the same day. Sometimes you just gotta focus on you and the loved ones. The market will always go up in time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:04:06 </td>
   <td style="text-align:left;"> $QQQ why is this looking like Feb 2nd and we will likely see a week of sideways action from here to 355 back to this level?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:03:23 </td>
   <td style="text-align:left;"> $QQQ If you can get almost the same interest rate on a 2 year note as you can on a 10, you know there will be a mass exodus from stocks to a sure bet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 06:02:45 </td>
   <td style="text-align:left;"> $QQQ $SPY 

Bond people are wrong again, losers!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:59:19 </td>
   <td style="text-align:left;"> $SPY Algo&amp;#39;s will def move on the inverted 2 &amp;amp; 10s tomorrow so just be ready 
 
watching $aapl $qqq $jpm $msft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:52:56 </td>
   <td style="text-align:left;"> $QQQ Prediction for tomorrow:
They run it back up to $365 in the morning. Then slow fade to $362. &amp;amp; then we ultimately end the day around $357-358. 
Watch &amp;amp; see💰💰💰💰💰💰💰💰💰💰PUTS‼️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:52:05 </td>
   <td style="text-align:left;"> Live updates | Pentagon: Weapons shipments arrive in Ukraine https://www.billionaireclubcollc.com/live-updates-pentagon-weapons-shipments-arrive-in-ukraine/ $DJIA $SPY $QQQ $VIX $DXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:50:29 </td>
   <td style="text-align:left;"> Stocktwits: 
VIDEO: Broad Market Technical Analysis Chart 3/31/2022 $SPY $QQQ $GME $TSLA $CCJ https://www.chartguys.com/daily-market-videos/4206/bears-back-in-action </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:50:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 84178900. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:45:35 </td>
   <td style="text-align:left;"> $QQQ $SPY - interesting read to reflect https://www.thebalance.com/2007-financial-crisis-overview-3306138 - if you adjust for inflation durable goods for Feb actually declined YoY - in this case though, the Fed must raise rates, the worst outcome to have to cause a recession to correct inflation b/c doubled the balance sheet in 2 years what took 12 years to get there before. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:45:15 </td>
   <td style="text-align:left;"> Stocks end lower, ending market’s worst quarter in 2 years https://www.billionaireclubcollc.com/stocks-end-lower-ending-markets-worst-quarter-in-2-years/  $DJIA $QQQ $DXY $VIX $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:45:05 </td>
   <td style="text-align:left;"> $GME stock splits. A pre indicator for falling stock market and econemy $TSLA $AMZN $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:43:39 </td>
   <td style="text-align:left;"> latexc4aadbda296a39875e765488f08e36aeROKU 
Market likely goes lower 
$AMD $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:42:21 </td>
   <td style="text-align:left;"> $SPY oh we&amp;#39;re dying take out tonight huh... delivery vegan 🦞 and dairy free dessert 🍨 😁🙋‍♂️💦 
 
BULLS got played majorly, I feel sorry for them because they refuse to accept reality that that &amp;quot;old bull market ponzi energy&amp;quot; is drying up! - NO WORRIES we&amp;#39;re hiring down at the local BEARMART 🐻🏢  $TSLA $AAPL $QQQ $LULU 😆🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:40:31 </td>
   <td style="text-align:left;"> $QQQ Shanghai shut down will be huge, shortly  

Biden wants to punish oil companies for unused leases which, will only cost us more money

Powell wants the market down and will get it there one way or another

Employment will be lower tomorrow which means that less people working, more expensive labor costs and more supply chain issues 

💩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:39:02 </td>
   <td style="text-align:left;"> $500 and counting on my short idea from earlier this week, played $aapl puts 

hit that FOLLOW button bc i’ll be posting an analysis on next steps as well as any other plays i’m eyeing 

this 11 day streak apple was on had to come to an end eventually 
 
also watching $vix for a spike to see if we pull back harder 

watch $spy $qqq $dia as well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:35:16 </td>
   <td style="text-align:left;"> Lo de hoy era esperado no podíamos llevar mas de 10 días verdes o planos sin bajadas o recogida de beneficios. Calma, paciencia que todo sigue su curso!!  $QQQ $SPY $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:33:36 </td>
   <td style="text-align:left;"> $UVXY Russian gas issue could really **** things up for EU. Putin played the West like a fiddle. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:32:20 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA nice healthy pullback </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:31:03 </td>
   <td style="text-align:left;"> $GME CATALYST: Gamestop Annual Shareholder Meeting is happening on Thu. Jun. 9 at 11:00 AM. 
 
View details and track upcoming catalysts: https://www.catacal.com/catalyst/gamestop-annual-shareholder-meeting 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:29:58 </td>
   <td style="text-align:left;"> $QQQ may 370 puts SHINING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:28:01 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $AMZN $TSLA  https://www.cnbc.com/2022/03/31/2-year-treasury-yield-tops-10-year-rate-a-yield-curve-inversion-that-could-signal-a-recession.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:27:49 </td>
   <td style="text-align:left;"> $QQQ more charts 
https://twitter.com/Reformed_Trader/status/1509638648135925767?s=20&amp;amp;t=__oPDaWfu6ruwrN4ycJKog </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:23:31 </td>
   <td style="text-align:left;"> $QQQ loaded more end of day. What a gift </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:21:48 </td>
   <td style="text-align:left;"> latexd0b3b7bd1866bda5d1b24d84e07ebc4dSPY: -5.55% 
$QQQ: -10.18% 
 
Trades: 135 
Winners: 132 
Losers: 3 
Scorecard: 97.78% 
*** Keep in mind, I mainly trade deep OTM plays to reduce cost basis *** 
 
Full story: https://stockaholics.net/threads/value-543-trade-journal-2-0.12676/page-4 
 
Here are my current long positions; of note, I reduced my cost basis by 2.16%, which is a full point more than last month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:19:59 </td>
   <td style="text-align:left;"> $SPY $QQQ Jobs report tomorrow morning, I think it will show another month of strong jobs gains along with huge surge in wages. If the report is strong then the market should embrace it since it would mean the recession isn’t coming anytime soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:19:50 </td>
   <td style="text-align:left;"> $QQQ rejection of vwap from ATH was to be expected. low 350&amp;#39;s would be a healthy/painful retrace, but likely gets bought up quickly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:19:32 </td>
   <td style="text-align:left;"> $SPY 👟🛍 

$NKE $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:18:54 </td>
   <td style="text-align:left;"> $QQQ $357 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:16:06 </td>
   <td style="text-align:left;"> $QQQ You cannot only feel something is wrong with the markets and price action but anyone who deep dives in macro economics knows it for sure. This will go wrong at some point. Be bullish be bearish ...just make money ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:15:36 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA 
Bye Bye Bull Market it was fun while it lasted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:13:33 </td>
   <td style="text-align:left;"> $AMD $QQQ $NVDA big flush on the way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:13:18 </td>
   <td style="text-align:left;"> $AAPL  $QQQ They&amp;#39;re getting ready for tomorrow, which way will it go? Happy April Fools day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:13:11 </td>
   <td style="text-align:left;"> $SPY OOF to all the goofy Permabulls who follow these charlatan analysts etc that tell you - &amp;quot;YIELDS DON&amp;#39;T MATTER&amp;quot; 💀😆🤡 $TNX $TLT $DXY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:11:40 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA $GOLD $USS_F 

2-year yield tops 10-year rate, an inversion that could signal a recession https://www.cnbc.com/2022/03/31/2-year-treasury-yield-tops-10-year-rate-a-yield-curve-inversion-that-could-signal-a-recession.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:11:13 </td>
   <td style="text-align:left;"> $SPY $QQQ Behaved as expected. Tomorrow will likely resume the upside to fill the gap at 4630-4660; 4455 is a good support.  
$XBI Just went two weeks tight and two months tight; a very good predictor of a big move next month or two, hepefully to the upside. See pic where two month tight patterns are circled.  
https://www.tradingview.com/x/hmOQsdy3/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:11:01 </td>
   <td style="text-align:left;"> $SPY $QQQ Looks like all the big guys sold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:10:52 </td>
   <td style="text-align:left;"> $SPY $QQQ are about to blow chunks to pay the Apes $GME $AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:10:38 </td>
   <td style="text-align:left;"> $SPY $qqq gamestop splits, well that is a ponzi but fine it goes up, why did amc went up with it? To make other apes happy to? This is hilarious 😂 just tells you the state of the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:10:03 </td>
   <td style="text-align:left;"> $QQQ $SPY does $GME rippin&amp;#39; mean market tanks tomorrow (note: must be greater than -3% drop to qualify as tanking)? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:09:00 </td>
   <td style="text-align:left;"> 🚀🚀🚀 $GME $AMC 🚀🚀🚀 
    !SHORTS ARE DONE FOR? 
$SPY $QQQ $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:08:26 </td>
   <td style="text-align:left;"> $QQQ wtf the 2yr/10yr inverted and stayed inverted. Completely missed that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:07:28 </td>
   <td style="text-align:left;"> $SPY Has anyone seen Fed balance sheet recently? You don’t want to see it. Mind blowing $QQQ $IWM 

It is really concerning 🤔🤔🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:05:04 </td>
   <td style="text-align:left;"> $QQQ holy shit MOC was $5 billion more on the sell side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:04:48 </td>
   <td style="text-align:left;"> $SPY $qqq have you asked yourself how idiots survived so far? Like by natural selection shouldn&amp;#39;t extinction happen? I know why, stock market and ponzis like GameStop :))) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:03:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA SHE DONE POOPED THE BED 💩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 05:02:11 </td>
   <td style="text-align:left;"> $QQQ  imma trade the biggie bounce tomorrow for a 13 cent gain.  Profit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:59:22 </td>
   <td style="text-align:left;"> UKRAINE’S PRESIDENT ZELENSKY: THE SITUATION IN UKRAINE&amp;#39;S SOUTH AND DONBAS REGION REMAINS EXTREMELY DIFFICULT. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:59:03 </td>
   <td style="text-align:left;"> $SPY well $gme splitting should be the sign to leave thus market. $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:58:56 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA Everyone I talk to is short into the month of April. It seems anything with cyclical exposure is poised to re-price for recession. Such an obvious positioning gives me a little pause-- I&amp;#39;m obviously hedged but am reluctant to go net short. If you read through the PCE data, it&amp;#39;s not farfetched to make the case that inflationary pressure is stabilizing, given the massive end-market headline price hikes that hit shelves in February and the relatively low sequential comp.  Could be a wall of worry scenario, especially if the Fed maintains a level head. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:58:36 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DJIA the world is at a tipping point you know what that means ...DOOM correction ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:58:30 </td>
   <td style="text-align:left;"> $QQQ briefly inverted 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:57:04 </td>
   <td style="text-align:left;"> $QQQ easy money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:56:38 </td>
   <td style="text-align:left;"> Today&amp;#39;s NASDAQ ( $QQQ ) HeatMap of large cap stocks, Healthcare sector $MRNA $GILD $AMGN $DXCM  
     
Learn more: finscreener.org/map/map </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:55:38 </td>
   <td style="text-align:left;"> $QQQ I closed my swing short...I&amp;#39;ve been posting thrashing viscera messages all week...and my target was the lagging 1 hour 50ma...as posted this morning.  A 359 target looks very reasonable though...but I&amp;#39;m not playing anymore sorcery games...GL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:54:22 </td>
   <td style="text-align:left;"> $QQQ $SPY 

That last 15 minutes were the finest display of WS assholes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:54:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMD why did market sell off? Inflation is priced in already tho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:52:42 </td>
   <td style="text-align:left;"> $QQQ Wait for it 
Q’s will 💩 tomorrow 
353-355 Zone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:52:22 </td>
   <td style="text-align:left;"> $SPY $QQQ now AMC and GME squeezing again. The rest of the market will tank tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:52:13 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $AMD $IWM  
Bulls be like… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:51:47 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DJIA S&amp;amp;P 500 Ends Lower to Wrap Up Worst Quarter in 2 Years!!! https://www.investing.com/news/stock-market-news/sp-500-ends-lower-to-wrap-up-worst-quarter-in-2-years-2795918 BLOOD ON the streets tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:51:35 </td>
   <td style="text-align:left;"> $QQQ who like the “W” move and “V”? 
 
im a V person myself </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:49:46 </td>
   <td style="text-align:left;"> $QQQ Easy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:49:26 </td>
   <td style="text-align:left;"> $SPY  $QQQ  just taking a breather. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:47:53 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM yikes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:47:16 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:45:51 </td>
   <td style="text-align:left;"> NASDAQ $QQQ Top Gainers during today $SPLK $INTU $SGEN $VRTX 
  
Learn more: https://www.finscreener.org/screener/top-gainers/stocks/nq100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:45:50 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

did elon tweet something?... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:45:16 </td>
   <td style="text-align:left;"> $SPY $QQQ Puts paid nicely today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:44:50 </td>
   <td style="text-align:left;"> Goldman Sachs: Broad Economic Model Shows Almost No Chance Of Recession In Next 12 Months, 38% Probability Of Recession In The Following Year

I would never believe on Banks $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:44:18 </td>
   <td style="text-align:left;"> $SPY $XLE $QQQ 

A politician tells homeless constituents to &amp;quot;Go home!&amp;quot; 🤦

And these are the &amp;quot;leaders&amp;quot; we are counting on to keep the economy going? 🥴 

Oh boy. We&amp;#39;re in serious trouble. 

It&amp;#39;s no wonder the approval rating of Congress is lower than that of the inflation rate. 😂

https://twitter.com/greg_price11/status/1509559084273524739?t=xu31l6XVO4Sm_jIuABevOA&amp;amp;s=19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:44:15 </td>
   <td style="text-align:left;"> Todays close was hands down the most savage bear trap of the year. Congrats to all followers $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:43:39 </td>
   <td style="text-align:left;"> $QQQ My target for this correction. $354 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:42:53 </td>
   <td style="text-align:left;"> $QQQ $IWM $SPY $DJIA FAQ I&amp;#39;m not BTFD ..market will crash soon hard !!!accumulating cash to buy some real cheap stocks ..looking for the double bottom signal then load the boat...CRASH ALERT is elevated !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:41:54 </td>
   <td style="text-align:left;"> And just like that...I&amp;#39;m almost bullish now, lol 
What happened in the last 45min? 
Would like to see: 
a) $SPX in the low 4400, with 
b) a &amp;quot;panic&amp;quot; day, then 
c) a &amp;quot;turnaround&amp;quot; day 
So that I can re-buy $SPY $QQQ $IWM (see my 3/29 tweet) 
 
&amp;quot;You will do best if you let stock setups guide you and ignore all the noise from of opinions, economics and the &amp;quot;stories.&amp;quot; For most investors this is difficult. They love to think they know the reasons behind a price move. It&amp;#39;s all BS. The average investor never outsmarts price.&amp;quot; - M.Minervini 
 
Disclosure:  I have NOT read his books, attended his seminars, or paid for his subscriptions.  I just follow him on Twitter, and like his tweets on trading philosophy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:41:11 </td>
   <td style="text-align:left;"> $SPY $QQQ Okay. Yield on 2-year treasury is now less than 1 basis point away from the 10-year. Yield curve is going to invert </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:40:44 </td>
   <td style="text-align:left;"> $QQQ 

Yep ⚠️⚠️340 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:40:10 </td>
   <td style="text-align:left;"> $QQQ 50% Fibonacci acting as a resistance. Will we end the week as a green or red candle? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:39:08 </td>
   <td style="text-align:left;"> Kyle with another good web 3 podcast roadmap and ideas 

$btc.x $qqq https://twitter.com/joshuarosenthal/status/1509210365980200975?s=12&amp;amp;t=nh6asMwK664E19PF3m-3UA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:38:20 </td>
   <td style="text-align:left;"> Nice pullback continuation today.  I wasn&amp;#39;t sure how today would trade, honestly, since the last day of the quarter can just get weird...and this was by no means an &amp;#39;ordinary&amp;#39; quarter.  Of note, we saw finally saw average volume today on the $SPY. (but not the $QQQ, still  light volume there).  Maybe this move will have conviction to it; we&amp;#39;ve gone through 8x trading days of only seeing 50% - 75% average volume. 
 
As for my trades today, I finally got out of a position I&amp;#39;ve had in $AMC +2.52%.  I (unintentionally) entered this last year, after getting put shares during the WallStreetBets mania.  
 
Speaking of pops, I also rolled my $CCL covered calls to 4/14 -- my contracts went ITM a couple days ago, so I pushed the expiration out a little and picked up another round of premium, reducing my underlying long position&amp;#39;s basis. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:37:21 </td>
   <td style="text-align:left;"> $QQQ Think this will move up a percent and a half tomorrow in order to burn both the puts/calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:37:07 </td>
   <td style="text-align:left;"> $QQQ how this sh.t rise AH again. No sense. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:36:49 </td>
   <td style="text-align:left;"> Jefferies says Altair, Bentley Systems among &amp;#39;logical&amp;#39; targets for Siemens 13:53 SIEGY, $ALTR, $BSY, ANSS, CDNS In a note to investors before the open, Jefferies analyst Simon Toennessen said he sees &amp;quot;strong logic&amp;quot; for Siemens (SIEGY) to pursue a large software deal to strengthen its offerings in simulation/EDA, close a gap to peers in process software and/or build out digital offerings in Smart Infrastructure. Noting that U.S. software multiples have now reverted to pre-Covid levels, Toennessen called out Altair Engineering (ATLR), Bentley Systems (BSY) and Nemetschek as three targets he views as the &amp;quot;most logical deals&amp;quot; for Siemens. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:36:41 </td>
   <td style="text-align:left;"> $QQQ monster sell volume into close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:35:45 </td>
   <td style="text-align:left;"> $QQQ lets see how it goes tommorow ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:34:28 </td>
   <td style="text-align:left;"> $SPY $QQQ very ugly close as selling accelerated into the close maybe ahead of the jobs report. A/D numbers were actually positive for most of the day closing  with 1348 Adv and 2042 Dec  but the price declines were worse. On the NYSE there were 119 New Highs and 73 New Lows </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:33:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA ALWAYS LISTEN TO YOUR BACON 🥓🥓🥓🥓🥓🥓🥓🥓🥓🥓🥓🥓🥓🥓🥓🥓🥓🥓 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:33:40 </td>
   <td style="text-align:left;"> $QQQ $SPY $BTC.X 

You know the party has reached rock bottom when it’s members are supporting and rooting on a foreign power while they actively murder the citizens of another country.

Pro-putin and pro russia sentiment has invaded our country. The right wingers must be stopped </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:33:31 </td>
   <td style="text-align:left;"> $QQQ I’m sooo blown away at how many uneducated day traders are on this trash. Good God. Read a damn book on how the Federal Reserve works. And who owns it. It’s Bidens fault. No it’s Americans fault to allow a private bank to regulate one’s currency. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:33:21 </td>
   <td style="text-align:left;"> $GME stock split and $AMC running mate not far behind 🚀🚀🚀

#optiontrading #tradeidea #daytrade $SPY $QQQ $CRYPTO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:33:18 </td>
   <td style="text-align:left;"> Well played $gme smart move  
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:32:58 </td>
   <td style="text-align:left;"> $AMZN 100C WEEKLY CALL SURPASSED 18. $SPY $QQQ $UVXY $TEUM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:32:45 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DJIA Oh market futures crashing hard bloodbath tomorrow .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:32:44 </td>
   <td style="text-align:left;"> $QQQ gap filled? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:30:42 </td>
   <td style="text-align:left;"> $QQQ I&amp;#39;m bullish but if the market does crash, it will be on the hands of Democrats who have absolutely no knowledge or control of fiscal/monetary policy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:30:37 </td>
   <td style="text-align:left;"> $AAPL $SPY $ViX $QQQ over/under how many times that graph/chart of “return to normal” gets posted tonight? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:29:47 </td>
   <td style="text-align:left;"> The 9 month moving average continues to be pivotal for the Nasdaq Futures and QQQ. No surprise there.  
 
See prior posts (my Nasdaq Futures Daily chart shows it as the red zone). 
 
$QQQ $NQ_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:29:26 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA Gotta love those end of day MM pussy sell offs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:28:57 </td>
   <td style="text-align:left;"> $ATVI $MSFT $SPY $QQQ 

🤡ATVI ❄️BOYS 

Options trader 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:26:28 </td>
   <td style="text-align:left;"> $QQQ I just want to be rich enough to enjoy the sun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:26:12 </td>
   <td style="text-align:left;"> $QQQ 
Kotick and his cohort…..thick as thieves😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:25:52 </td>
   <td style="text-align:left;"> $QQQ $SPY $BTC.X 

Want to know why our markets are tanking?

Because republicans are traitors. From the top on down to the hillbilly hicks, republicans are actively campaigning and doing everything in their power to sink America </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:25:50 </td>
   <td style="text-align:left;"> $GME yup.

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:24:47 </td>
   <td style="text-align:left;"> $SPY $QQQ i need a cig and a shower after that close.. oh baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:23:54 </td>
   <td style="text-align:left;"> $QQQ  I would be really pissed if my broker just bought the dip😣

I’d be telling that firm to undo the trade at their cost 💩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:23:14 </td>
   <td style="text-align:left;"> $QQQ Wow lol, what a dump into close. You can see the exuberant optimism of bears in the comments here calling everyone &amp;quot;retarded&amp;quot; lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:23:11 </td>
   <td style="text-align:left;"> $BB trending $GME $AMC $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:23:05 </td>
   <td style="text-align:left;"> $QQQ This volume SUCKS of course they can just drive it down to Max Pain, watch tomorrow be green because put/call ratio is 2.5 and April is a green month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:22:49 </td>
   <td style="text-align:left;"> Markets Tumble To Conclude Action-Packed Q1  $QQQ $SPY $DIA $VRTX $SPLK 

https://newsfilter.io/a/e126d9979c1e1f3692de381b30d79a91 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:22:44 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:21:12 </td>
   <td style="text-align:left;"> $COST rotation from stocks to bonds

End of Quarter rotation doesn’t look good for the future of markets. $SPY $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:21:07 </td>
   <td style="text-align:left;"> $SPY $QQQ ohhh ya baby all is safe now bulls. AH huge spike buy it up... Hahahhaha more fuel for the long squeeze. Bulls be like time for next leg up! Haha literally had their legs amputated this afternoon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:19:45 </td>
   <td style="text-align:left;"> $SPY $QQQ A strange close, most likely due to some end of quarter action. The market should resume its uptrend when Q2 starts tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:19:40 </td>
   <td style="text-align:left;"> $QQQ 

Better tech ETF?
$VGT vs. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:19:13 </td>
   <td style="text-align:left;"> $QQQ Dirty, dirty, dirty broker dealer trades going into the close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:18:43 </td>
   <td style="text-align:left;"> $QQQ there’s nothing left to save this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:18:12 </td>
   <td style="text-align:left;"> $QQQ u either buy at these levels or you believe in impending doom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:18:08 </td>
   <td style="text-align:left;"> $QQQ : $NASDAQ Price &amp;gt;21D&amp;gt;50D , but now has fallen below 200D EMA.. oscillators were flashing overbought ... If this is a real reversal rally , what you would like to see is 21D / 8D EMS support held and index getting back above 200D with some real volume (140% of daily average), and may be some tests along the way ...ideally you want 200D EMA to get some respect  =&amp;gt; That&amp;#39;d be the clear conviction on this being a real reversal ...then just a bear market flash rally $STUDY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:17:30 </td>
   <td style="text-align:left;"> $QQQ $SPY 

I guess that was extreme quarter ending window dressing to the other side. 

FINE. We go up bigly tomorrow with newly available cash for April from investors, tax returns, and of course our darling Fed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:17:13 </td>
   <td style="text-align:left;"> $SPY $QQQ BULLS ARE JUST SO STUPID AT THE MOMENT...THEY TRADE LIKE PLAYING DARTS BLINDLY 🤣🤣🤣🤡🤡🤡🤡🔻🔻🔻🔻🚽🚽🚽🚽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:16:16 </td>
   <td style="text-align:left;"> $SPY $QQQ Look at this beautiful print for puts....just beautiful 🔻🔻🔻🚽🚽🚽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:15:56 </td>
   <td style="text-align:left;"> $SPY $qqq Feds ain’t buying anymore, feds raising interest rates, commodities going up, food prices and inflation sky high.. idc if gas drops.. everything else is f*cked. FAANG pumped to un belief. Heavy cash and nice chunk holding in $sqqq. Let s see who wins. 🐂 vs 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:14:40 </td>
   <td style="text-align:left;"> $SPY  $qqq so big drop before close but green pump right the way after 4pm !!! What the heck wrong with this market … why buyers wait till 4pm close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:14:32 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:14:06 </td>
   <td style="text-align:left;"> $SPY Another good day for bulls to average down. Just keep buying the dip, fed will send us V tmrw 

$AAPL $QQQ $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:13:53 </td>
   <td style="text-align:left;"> $SPY cant wait when this makes the biggest fattest inverse h&amp;amp;s 
Its coming! Its gonna be $QQQ  hugeeeee </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:13:47 </td>
   <td style="text-align:left;"> $SPY $QQQ Quarter end rebalance over. Next week calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:13:46 </td>
   <td style="text-align:left;"> $SPY holy shit that selloff was absolutely INSANE I’m super concerned $QQQ $NVDA $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:13:45 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:13:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $UPST $AMD selling any rip tomorrow and prepare for more downside. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:13:05 </td>
   <td style="text-align:left;"> $SPY 
    $444.44 tomorrow intraday 
based on my current trades ♨️

$vixy $uvxy $sqqq
$qqq

given reality I’m rn =&amp;gt;&amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:12:40 </td>
   <td style="text-align:left;"> $QQQ GO WOKE GO BROKE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:12:17 </td>
   <td style="text-align:left;"> $QQQ I hope this piece of shit opens up high so I can buy more cheap juicy puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:12:15 </td>
   <td style="text-align:left;"> $QQQ perfect bounce tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:10:43 </td>
   <td style="text-align:left;"> $QQQ 2/10 year bond yields are within 1 basis point. The inversion is happening either tomorrow or Monday. May not mean much yet but it will sure rattle the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:10:33 </td>
   <td style="text-align:left;"> *NASDAQ 100 FALLS 9% FOR WORST QUARTER SINCE MARCH 2020 
$QQQ $NDX $NQ_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:10:03 </td>
   <td style="text-align:left;"> $QQQ I’ve never shorted the market before, today was my first. This shit feels amazing 😂🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:09:48 </td>
   <td style="text-align:left;"> $SPY $QQQ propped up real volume comes in and it flushes. Such a Bs market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:09:45 </td>
   <td style="text-align:left;"> $QQQ Lmao.. good ol&amp;#39; power hr .. that setup did NOT work .. but the trailing stop-WIN protected me for a +0.25 RRR💪 .. turns out it was a BULL TRAP Lmao 😆... Tomorrow another day and I have a feeling it will be a good one ( hoping for a gap down actually)... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:09:40 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Closing imbalance = ~$4.8B to the SELL side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:09:33 </td>
   <td style="text-align:left;"> $QQQ $SPY I am buying the fn dip....💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:09:28 </td>
   <td style="text-align:left;"> $QQQ Swinging 360 Poots for tomorrow and 355 for next week.
Time the Qs rectify the relentless run up past two weeks on not good news. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:09:15 </td>
   <td style="text-align:left;"> $SPY legit question. What the fuck did you guys expect? NINE rate hikes into 2023. Market is forward looking. Wake the fuck up. $QQQ $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:09:02 </td>
   <td style="text-align:left;"> $SPY the same volatility  happens every last day of the month…. Why is everyone so forgetful on here. Anyway, thank you idiots. Fin twit losers were buying calls today. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:09:00 </td>
   <td style="text-align:left;"> $QQQ love the bears getting all excited without realizing the sell off was caused by month end rebalancing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:08:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Market momo &amp;amp; activity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:08:08 </td>
   <td style="text-align:left;"> $QQQ approaching 8-day ema on daily chart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:07:51 </td>
   <td style="text-align:left;"> GAP DOWN FRIDAY...I AM BUYER IF WE DO $SPY latexffaee7a690940762cfea6da4f7592328NVDA  
 
💰FOLLOW for our signals DAILY💰 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:07:33 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Fear &amp;amp; Greed Index </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:07:22 </td>
   <td style="text-align:left;"> $NQ_F $QQQ $SPY closed at last month highs. Let’s see that massive green candle next month to ATH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:07:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DJIA

IVE HAD DAYS WHERE I WAS DOLO

BUT I’VE NEVER CAUGHT A BAD CASE

OF FOMO 

well that’s just perfect. thanks swae! 

That’s a wrap. +93.11% 
Trades closed? Fuck no! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:07:15 </td>
   <td style="text-align:left;"> $QQQ I told yah.  Thursday would be bloody </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:06:48 </td>
   <td style="text-align:left;"> $SPY So lets go over what was clear 2 days ago &amp;amp; why I called out Cramer &amp;amp; CNBC. 
 
Every pro knew how EOQ would go w/ rebalancing &amp;amp; after that pop but they were telling folks to Buy. 
 
Always do your own DD folks &amp;amp; dont let the Pros screw you 
 
$aapl $amzn $baba $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:06:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Economic calendar for 4/1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:06:40 </td>
   <td style="text-align:left;"> If you’re trading this week, Read This! $QQQ RSI Indicator left the overbought zone. View odds of downtrend. https://srnk.us/go/3543364 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:06:24 </td>
   <td style="text-align:left;"> $QQQ First time in a month it didn&amp;#39;t pump into close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:06:20 </td>
   <td style="text-align:left;"> Stocks opens lower, oil slides ahead of release of crude https://www.billionaireclubcollc.com/stocks-opens-lower-oil-slides-ahead-of-release-of-crude/ $DJIA $DXY $QQQ $VIX $WTI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:06:18 </td>
   <td style="text-align:left;"> $QQQ 60/40 funds rebalancing $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:05:52 </td>
   <td style="text-align:left;"> $CEI Wow, oil prices oversold here and people are still not buying? Tisk tisk, oil goes up when the market drops, a lot of dropping still to come. $SPY $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:05:28 </td>
   <td style="text-align:left;"> $QQQ Loved the pump fake going into the final seconds of the close today 

355 Tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:05:18 </td>
   <td style="text-align:left;"> $QQQ $SPY have a feeling China is going for Taiwan soon. Chinese stocks been dumping hard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-04-01 04:04:32 </td>
   <td style="text-align:left;"> Market wrap: 
🔷 US indices closed lower on the day:  
$DJIA -1.6%, $SPX -1.6%, $QQQ -1.5% 
🔷 #Gold (+0.1%) edged higher while #WTI (-6.5%) fell sharply. 
🔷 #JPY was the day&amp;#39;s strongest major currency; #EUR was the weakest. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 09:00:48 </td>
   <td style="text-align:left;"> $AAPL $QQQ - RSI and MACD support a fall in price. If Apple doesn&amp;#39;t break $178 and remain or if we continue 3-4 more days of selling, Apple could head back down to the $150s. Personally, its still a VERY overpriced stock as it was trading at $30-50s in 2018-2019, yet, during the LARGEST unemployment event, pandemic, and steep recession, Apple somehow hit $130 in Aug 2020. This clearly tells you the stock is bloated. While to us it seems insane that Apple could drop to $140, even at that price its overvalued. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 08:46:45 </td>
   <td style="text-align:left;"> $AMZN $AAPL Who needs WallStreetBets when you have Xtrades. Thanks to Xtrades, I have doubled my entire portfolio in just one week. Joining this Discord community was the best investment I&amp;#39;ve ever made!~~!! amazing-stocks-room.stockmarketus.xyz/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 08:46:09 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Former top national security officials side with Apple in app store antitrust case https://www.stck.pro/news/AAPL/25397228 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 08:43:49 </td>
   <td style="text-align:left;"> $AAPL -- There was a triple reversal signal on the 29th. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 08:43:20 </td>
   <td style="text-align:left;"> $SPY if Apple give each iPhone owner 1 free game, what would it be? Vote now $aapl

Btd 6
Mobile legend
Candy crush </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 08:34:38 </td>
   <td style="text-align:left;"> $AAPL … oh did y’all think this would hit $200? Lol. The White House is destroying the middle class and this won’t get to $200 under Biden. You may as well get used to this shit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 08:32:28 </td>
   <td style="text-align:left;"> Apple Inc. (NASDAQ: $AAPL), ( $ABNB) – 34 Public Companies That Made Time’s 100 Most Influential For 2022: $AMC, $DIS Disney, $F Ford And More https://www.billionaireclubcollc.com/apple-inc-nasdaqaapl-abnb-34-public-companies-that-made-times-100-most-influential-for-2022-amc-disney-ford-and-more/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 08:27:00 </td>
   <td style="text-align:left;"> The industry average ROE is 17.76%. $AAPL outperforms 94% of its industry peers. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 08:25:16 </td>
   <td style="text-align:left;"> $PATH bought 5k more shares at 20.80, holding 10k shares now at 21.5, till 50 we go.

$BABA $NIO $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 08:21:51 </td>
   <td style="text-align:left;"> $AAPL  
 
Apple has won support from the billionaire industrialist Koch brothers’ advocacy group in a court fight over anti-competition claims with Apple’s App Store - Bloomberg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 08:21:18 </td>
   <td style="text-align:left;"> $AAPL wouldn’t be surprised to see this moon tomorrow or drop lower. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 08:16:46 </td>
   <td style="text-align:left;"> $AAPL ‘It will help us quite a bit’ — ‘CODA’ Oscars win could be a boon for real-life family’s hometown cinema

https://www.marketwatch.com/story/it-will-help-us-quite-a-bit-coda-oscars-win-could-be-a-boon-for-real-life-familys-hometown-cinema-11648755799?mod=home-page </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 08:15:59 </td>
   <td style="text-align:left;"> $AAPL regardless of this downtrend now that yes will hit $172-$170 before going up. What you all think about new ATH next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 08:15:51 </td>
   <td style="text-align:left;"> $BAC $SPY $AAPL Less not forget, in time for ER…https://www.cnbc.com/2018/02/14/amazon-and-bank-of-america-partner-for-lending-program-but-growth-has-stalled.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 08:15:12 </td>
   <td style="text-align:left;"> $AAPL bear trap. Glad I bought some calls for next week at the end of the day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 08:13:28 </td>
   <td style="text-align:left;"> $AAPL $GOOG $AMZN $NVDA $MSFT  
Russia and China are leading a New “World Order,” Russian foreign minister says  
  
Chinese Foreign Minister Wang Yi &amp;amp; Russian Foreign Minister Sergei Lavrov met Wednesday in Tunxi, China, marking Lavrov’s second trip abroad since Russia invaded Ukraine February 24th. China and Russia are moving towards creating a new “just, democratic world order,” Lavrov said in a video released by the Russian Ministry of Foreign Affairs. Wang shared Lavrov’s signs of encouragement and said he left the meeting “more determined’ to boost the relationship between China and Russia.  
  
China has consistently called for a peaceful resolution in Ukraine, Wang repeated this Wednesday. However they have yet to condemn Russia for the invasion China and Russia have said in a joint statement that there is “no limit” to the relationship between the two countries, and Lavrov has said relations with China are at their best level ever.  
https://www.france24.com/en/live-news/20220330-russian-fm-hails-china-as-part-of-emerging-just-world-order </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 08:12:06 </td>
   <td style="text-align:left;"> $AAPL We didn&amp;#39;t see the clown bears come out for 11 days and now all of a sudden they all appear to tell us were in for it? WOW! 10 green days and 1 red. I&amp;#39;ll be happy to get used to being wrong... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 08:06:53 </td>
   <td style="text-align:left;"> If $Gme keeps trading that way they will have a bigger market  cap that $aapl and $ tsla combine ...heh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 08:05:16 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple Wins Koch Group Support Over Epic Games Lawsuit https://www.stck.pro/news/AAPL/25394735 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 08:03:21 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-03-31 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=FTsnoNTTEco </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 08:00:19 </td>
   <td style="text-align:left;"> $AAPL I need everyone&amp;#39;s input.   Price predictions for AAPL - End of Day 4/1 
 
Thanks in Advance.  
 
Curious to see what others are thinking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 07:58:12 </td>
   <td style="text-align:left;"> $AAPL $MSFT $GOOG $QQQ load uppp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 07:56:37 </td>
   <td style="text-align:left;"> $GME Plans to issue a stock dividend in the form of a stock split. Guess who did this before multiplying their market cap in the process?  $AAPL and $TSLA 

Good luck short sellers. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 07:56:25 </td>
   <td style="text-align:left;"> $AAPL $BTC.X seems they have everything trading on same algo’s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 07:52:26 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL My interview with @DolanDrumpf went so well and I learned a lot!  Now I’m trying to figure out who should be the next Stocktwitter to be interviewed on my YouTube channel.  I’m looking for suggestions or volunteers! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 07:49:06 </td>
   <td style="text-align:left;"> $AAPL alright bulls, you been winning since last week. It&amp;#39;s ours turn now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 07:43:00 </td>
   <td style="text-align:left;"> $SPY  amount of negative and positive articles regarding $AAPL this week seems excessive. I wonder what games are being played..? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 07:42:13 </td>
   <td style="text-align:left;"> $AAPL $140-135
$UPST $80
$AMD $85
$ROKU $70 
It will get there sooner or later </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 07:38:23 </td>
   <td style="text-align:left;"> $AAPL I feel Apple will touch $140 in April.  I am concerned about their recent strategy move and outlook. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 07:36:48 </td>
   <td style="text-align:left;"> $SPY small cap futures are weak. That&amp;#39;s all you need to know. Suckers rally coming to an end. Anyone else wants to buy $aapl at 30 p/e when 10yr avg is around 15? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 07:35:19 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA 

0331 baby!! No better way to end it on a red day. Machine gunners definitely bought poots.😤😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 07:27:07 </td>
   <td style="text-align:left;"> $AAPL $118 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 07:26:02 </td>
   <td style="text-align:left;"> $AAPL #CHWY #AAPL @quantcha you all ready🍋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 07:24:08 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple Rolls Out Apple Business Essentials for US Small Businesses https://www.stck.pro/news/AAPL/25394737 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 07:17:31 </td>
   <td style="text-align:left;"> $AAPL we have to quit being cult  members and look  at the reality of this stock , I wonder what tomorrow is going to bring 🥵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 07:08:22 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $MRVL $PATH 
Bears celebrating  for 1.3% relief rally. 
Futures are already recovering  ⤴️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 07:00:59 </td>
   <td style="text-align:left;"> $AAPL wild ass day, join the winning team 💪🏻💪🏻💎💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 07:00:20 </td>
   <td style="text-align:left;"> $AAPL Option to look at today.. 👀 👀  $205.00 Call for Friday, April 8, 2022. Roughly 2 Thousand dollars! 💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:56:59 </td>
   <td style="text-align:left;"> $AAPL 

https://appleinsider.com/articles/22/03/31/apple-named-a-titan-in-times-2022-list-of-most-influential-companies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:56:12 </td>
   <td style="text-align:left;"> $AAPL 

https://www.apple.com/newsroom/2022/03/apple-launches-50-million-supplier-employee-development-fund/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:56:06 </td>
   <td style="text-align:left;"> $AAPL $GOOG $AMZN $NVDA $MSFT  
Paying attention to the elephant in the room is often a good idea. 
 
FAANG&amp;#39;s cost of customer acquisition is going up 30% to 40% &amp;amp; we all know (or most) know this because FB, GOOG guide to where they need to perform in their ER/conference calls.  
 
In a down market what matters is Growth, Burn, Margins! &amp;amp; a stockpile of cash. 
 
The market in its current mode is just unwinding the destruction that Fed/J.Powell created in the last 24 months. 
 
&amp;quot;We don’t need to debate recession. It’s arrived for 80% of the economy via real disposable income – -0.2% in Feb for the 7th straight decline. Only other time this happened? Try Dec’ 73-Jun ’74 amid the recession that few saw coming. Denial isn’t an effective strategy&amp;quot; 
 
&amp;quot;Real estate represents &amp;gt;50% of global “wealth”, and it is therefore such an important driver for the business cycle. 
 
The Fed is telling you they want the housing market to slow down&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:53:49 </td>
   <td style="text-align:left;"> $AAPL 

https://arstechnica.com/gadgets/2022/03/apple-plans-to-build-its-own-financial-infrastructure-for-payments-and-lending/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:49:34 </td>
   <td style="text-align:left;"> $QQQ futures unstoppable: it feels like the March low all over again - next massive leg higher starts tomorrow!!!! $spy $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:43:25 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : California attorney general jumps into Epic-Apple antitrust battle https://www.stck.pro/news/AAPL/25393674 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:43:02 </td>
   <td style="text-align:left;"> $AAPL Daily 
 
Free discord link in bio. 
 
Back below 177 level. Be careful with this one, can see 168 very quick after 11 straight green days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:39:47 </td>
   <td style="text-align:left;"> $AABB $LGVN $DWAC $XOM $AAPL https://www.reddit.com/r/aabbstock/comments/tqr9w9/aabb_revenue_streams_and_deliverables/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:37:27 </td>
   <td style="text-align:left;"> $AAPL window dressing ran this up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:36:37 </td>
   <td style="text-align:left;"> $AAPL ....Totally normal candle right there...🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:36:32 </td>
   <td style="text-align:left;"> $AAPL we tried to tell you bulls to take profit … but instead you were greedy… enjoy the ride down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:35:33 </td>
   <td style="text-align:left;"> ..Interest Rates to Will Smith the Market?!!! https://www.billionaireclubcollc.com/interest-rates-to-will-smith-the-market/ $AAPL $MSFT $AMD $NVDA $AFRM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:33:09 </td>
   <td style="text-align:left;"> $AAPL hope fucking Tesla phone come out soon this mtf apple gonna go bankrupt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:32:04 </td>
   <td style="text-align:left;"> Daily Market Recap for Thursday 3/31/2022 for #Stocks #Bitcoin #Gold and #Silver
https://youtu.be/2VA37dR6G7k

$AMD $AAPL $TSLA $RBLX

Who shorted tech?  Look for pops to short. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:30:30 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $MSFT $AMZN 
🙋‍♀️ Hey bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:28:59 </td>
   <td style="text-align:left;"> $AAPL F&amp;#39;ed myself on AAPL CALLS 4/1. What an  INTENSE PAST 2 DAYS, good job bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:25:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 52 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=analyst-ratings&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:23:16 </td>
   <td style="text-align:left;"> $ISPO $SPY $AAPL 💎💎 it’s been a great week so far whether you made a little coin or a ton of coin  with me let’s keep banking together ❤️❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:17:49 </td>
   <td style="text-align:left;"> Played the trend that was given to us today. It&amp;#39;s best to always scalp and compound your trades. We aren&amp;#39;t in a market for swinging anymore and it is best to be all cash when the day ends. Played $SPY $NVDA $AAPL and $AMC. Had to delete my old post to re-upload the AMC Play as well. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:14:30 </td>
   <td style="text-align:left;"> $AAPL y’all sound like a bunch of noobs on this board.. stocks go up, they go down, then back up, then back down. Relax </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:14:11 </td>
   <td style="text-align:left;"> $AAPL I seriously hope all you bulls who think it should go up just because lose your asses </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:10:22 </td>
   <td style="text-align:left;"> $AAPL https://stocktwits.com/Ns09877/message/448884577 
 
Told ya </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:08:55 </td>
   <td style="text-align:left;"> $AAPL yesterday Cramer said apple was a screening buy! Today he’s like let the market come back down! How is he still on TV </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:07:58 </td>
   <td style="text-align:left;"> $AAPL remember the best way to fight inflation is to buy stocks and this one is still a </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:07:34 </td>
   <td style="text-align:left;"> $TSLA $AAPL no one in their goddamn mind is going to subscribe for luxury goods, which will undoubtedly be more expensive than financing or inhibit cash flows…there is a reason this mode doesn’t work, banks will always get $$ cheaper </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 06:05:38 </td>
   <td style="text-align:left;"> CITI&amp;#39;s take on how the Oasis gets built and by whom. $NVDA $FB $AAPL $RBLX $MSFT http://citi.us/3wUabgv </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:59:31 </td>
   <td style="text-align:left;"> $AAPL Lucky number for bears; 173,27 - 168,33 - 164,86 
164,86 my next friday target </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:59:19 </td>
   <td style="text-align:left;"> $SPY Algo&amp;#39;s will def move on the inverted 2 &amp;amp; 10s tomorrow so just be ready 
 
watching $aapl $qqq $jpm $msft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:58:45 </td>
   <td style="text-align:left;"> $AAPL market going up ah and this continues to dump. When it picks a direction, whether pumping or dumping, it sticks to it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:58:01 </td>
   <td style="text-align:left;"> $TSLA $SPY $AAPL $MSFT $BABA 
Happy  ❤  Thursday, everyone  🎊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:57:42 </td>
   <td style="text-align:left;"> top dark pool prints from today $AAPL  $GOOGL  $AMD  $JPM  $DDOG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:42:21 </td>
   <td style="text-align:left;"> $SPY oh we&amp;#39;re dying take out tonight huh... delivery vegan 🦞 and dairy free dessert 🍨 😁🙋‍♂️💦 
 
BULLS got played majorly, I feel sorry for them because they refuse to accept reality that that &amp;quot;old bull market ponzi energy&amp;quot; is drying up! - NO WORRIES we&amp;#39;re hiring down at the local BEARMART 🐻🏢  $TSLA $AAPL $QQQ $LULU 😆🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:40:39 </td>
   <td style="text-align:left;"> $AAPL Could see 167.50 tomorrow to wipe out the retail call buyers.  Finger on the trigger. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:40:28 </td>
   <td style="text-align:left;"> $AAPL What I see today is hedge fund exit the pool, it will be another bloody day tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:39:15 </td>
   <td style="text-align:left;"> $AAPL I was saying Bear Trap all day and nobody listened 🤦🏻‍♂️🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:39:02 </td>
   <td style="text-align:left;"> $500 and counting on my short idea from earlier this week, played $aapl puts 

hit that FOLLOW button bc i’ll be posting an analysis on next steps as well as any other plays i’m eyeing 

this 11 day streak apple was on had to come to an end eventually 
 
also watching $vix for a spike to see if we pull back harder 

watch $spy $qqq $dia as well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:38:22 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:37:45 </td>
   <td style="text-align:left;"> $AAPL whose holding calls for next week and the following? 🙋🏻‍♂️🤦🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:36:11 </td>
   <td style="text-align:left;"> $SPY Bull thesis is that sheep stocks like $AAPL and $TSLA continue running to ever-higher highs, unperturbed by deteriorating fundamentals. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:36:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Hackers duped Apple, Meta into handing over user data: report https://www.stck.pro/news/AAPL/25391042 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:34:31 </td>
   <td style="text-align:left;"> $AAPL headed much higher!!🙌 
#TLRY aapl was once at $7  load‘em 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:30:41 </td>
   <td style="text-align:left;"> $AMD That’s what they do they whore you out 🤦‍♂️ ask $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:28:01 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $AMZN $TSLA  https://www.cnbc.com/2022/03/31/2-year-treasury-yield-tops-10-year-rate-a-yield-curve-inversion-that-could-signal-a-recession.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:27:25 </td>
   <td style="text-align:left;"> $AAPL $SPY AAPL 170 soon SPY 450 soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:24:09 </td>
   <td style="text-align:left;"> $DIS looking to sink some money in something for spring? #1 sporting goods retailer by Oppenheimer. 

Academy Sports and Outdoors $AAPL $WMT $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:15:01 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL #throwbackThursday to happier times! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:14:22 </td>
   <td style="text-align:left;"> $SPY “they“ manufactured and sold gazillion synthetic shares of $gme and its still at $200 LOL $gme may be bigger than $aapl …..Trilions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:14:19 </td>
   <td style="text-align:left;"> $AMZN $AAPL $TSLA $SPY $MSFT stronger ones </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:13:18 </td>
   <td style="text-align:left;"> $AAPL  $QQQ They&amp;#39;re getting ready for tomorrow, which way will it go? Happy April Fools day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:10:23 </td>
   <td style="text-align:left;"> $NVDA fearless one. $SPY $BOXL $AAPL $GMBL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:09:22 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL a lot of you don&amp;#39;t know the money printer origin story and that is sad. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:08:11 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Are Bearish Mulders dreams coming true? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:03:29 </td>
   <td style="text-align:left;"> $SPY $UVXY $AAPL $GME $AMC When meme stocks are blowing I take that as a sign the market is about to crash.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:03:26 </td>
   <td style="text-align:left;"> $AAPL 180 eow perma bulltards </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:03:10 </td>
   <td style="text-align:left;"> $AAPL what a bunch of fucking scammers 🤡. Had my puts ready but thing kept going sideways sold for small profit. Then thing drops 3$ in 5 minutes wtf.... they are after retail!! This hedgies and funds wanna take our money $$.. protect and take profits when you have them other wise you&amp;#39;ll end up with half of your investment or 25% of it 😂 fucking scanming sons of bitches </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:02:47 </td>
   <td style="text-align:left;"> $AAPL great day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:01:29 </td>
   <td style="text-align:left;"> $AAPL can still rally a little bit higher before turning back down.  We do not like to chase the rally off the lows, there is momentum divergence at the lows and suggests that another leg lower will take place in the future. There is not a good setup to sell, or buy, we prefer sidelines on AAPL right now #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:01:15 </td>
   <td style="text-align:left;"> $AAPL legend said will hold 177 forever，lets see who will buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:00:46 </td>
   <td style="text-align:left;"> $AAPL looks like a hanging man on the quarterly. Interesting to see how the next quarter plays out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 05:00:30 </td>
   <td style="text-align:left;"> $GME $AMC Stock splits are meaningless, but GME is a stock in an alternate universe 
 
when a big deal company splits like $AAPL or $TSLA we all know it does not have an effect, but like magic it rises the price. 
 
Gamestop will increase and AMC will get a good kick in the ass, but splitting will not cause the finding or counting of “synthetic “ shares. 
 
We are in a place that does not exist, enjoy the ride, it will be bumpy from here  
 
this GME split may just start the AMC run to new highs, 
 
s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:59:56 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $MSFT $AMZN 
Bulls had 11 bulls days. 
We&amp;#39;re just having 2 bear days.
Way to go 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:57:30 </td>
   <td style="text-align:left;"> $AAPL apple can get to 1 trillion revenue soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:55:19 </td>
   <td style="text-align:left;"> $AAPL 

Thanks for competing my withdraw transaction, central bank! I’m looking to perform another.

Currently working on the slip. Just a moment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:53:21 </td>
   <td style="text-align:left;"> $TSLA $SPY $AAPL $MSFT $AMZN 
High Five to  Bears 👋
Great team work 👏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:52:16 </td>
   <td style="text-align:left;"> $FSR  $AAPL $TSLA 
https://seekingalpha.com/amp/news/3801868-fisker-is-still-a-buy-at-morgan-stanley-despite-slower-production-ramp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:52:13 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $AMD $IWM  
Bulls be like… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:52:08 </td>
   <td style="text-align:left;"> $AAPL for my birthday i am hoping Steve Jobs ressurrects tomorrow  or an Iphone recall </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:51:22 </td>
   <td style="text-align:left;"> $SPY expect more bad news coming out of China shutdown. $400 soon lol 😂  $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:50:54 </td>
   <td style="text-align:left;"> $AAPL dude i called it I SOLD MY PUTS AT THE TOP SOMEONE STRING ME UP BY MY TOES </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:50:26 </td>
   <td style="text-align:left;"> $AAPL $165 gap fill! Ouch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:49:14 </td>
   <td style="text-align:left;"> $AAPL $SPY $UVXY Brace for selloff tomorrow. April 12 may rock markets... April 28 apple earnings; expect a decrease in earnings outlook for next quarter and marginal growth. If Apple falls April 28 the whole market will follow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:49:12 </td>
   <td style="text-align:left;"> $AAPL … the worst quarter since 2020! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:48:46 </td>
   <td style="text-align:left;"> $AAPL … the markets just ended the month with the worst quester since 2020! Let’s go Brandon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:45:58 </td>
   <td style="text-align:left;"> $GME Remember folks, there are kids on ST like @jackk1 sharing advice, be careful when you see them :o) 
 
$baba $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:45:57 </td>
   <td style="text-align:left;"> $AAPL 

Looks like it&amp;#39;ll be sell in April and go away... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:43:39 </td>
   <td style="text-align:left;"> $AAPL Our followers have been winning since…. Well, see our feed and you will know! Great work y’all…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:43:25 </td>
   <td style="text-align:left;"> $AAPL Pamp it! I&amp;#39;m buying a few billion! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:40:16 </td>
   <td style="text-align:left;"> $AAPL feels good to finally be a winner. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:40:15 </td>
   <td style="text-align:left;"> $AAPL Anyone know how low this can go? Looking to buy 2024 200$ calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:39:21 </td>
   <td style="text-align:left;"> $AAPL I hope y’all bulls prepared da anus for
Tmmr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:37:06 </td>
   <td style="text-align:left;"> $QS stock is about to double 
Price target $TSLA $AMC $GME $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:34:15 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-03-31 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=FTsnoNTTEco </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:34:15 </td>
   <td style="text-align:left;"> $AAPL 5.11 m volume in a single candle ten minutes before close. Ludicrous </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:33:30 </td>
   <td style="text-align:left;"> $AAPL 

Again 

Best u can do???

Never sell 🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:33:28 </td>
   <td style="text-align:left;"> $AAPL does anyone think this will go to 200 in the next 5 years? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:33:13 </td>
   <td style="text-align:left;"> $AAPL Still holding my April 4/8 $175 puts, up about 33% on the position right now. Expecting some more selling tomorrow after the weak show out by the bulls today. Shorts will be all over the market tomorrow, could get ugly quick.📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:32:05 </td>
   <td style="text-align:left;"> $BB Buy a little every month for a few years I’m confident there’s a big reward coming as car production returns to normalcy and ivy becomes the goto platform with $amzn !! Reminds me of $AAPL late 90’s during their turn around!  Check out $NTRBW chart and the fails to deliver year to date.. and $NTRB fails to deliver in January were a very large % of DTC share count.. see NTRBinfo.com for my RedChip disclosure.  $BB still my favorite for potential trillion dollar company by 2030.. we shall see…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:30:54 </td>
   <td style="text-align:left;"> $AAPL bought .41 175 puts &amp;amp; sold before close for 1.23.

Maybe I left money on the table, BUT I’m happy with a triple👍🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:30:37 </td>
   <td style="text-align:left;"> $AAPL $SPY $ViX $QQQ over/under how many times that graph/chart of “return to normal” gets posted tonight? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:29:54 </td>
   <td style="text-align:left;"> $AAPL apple to $5.63 or whatever the bears like to say😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:29:05 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $MSFT latex145382f9bd1260d6d0f36cd1ae27d8ffTSLA 879k (57% call/43% put)
$AMC 878k (68% call/32% put) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:28:47 </td>
   <td style="text-align:left;"> $AAPL Option Alert.. High Volume Options... 👀 👀  $177.5 Call for Friday, April 1, 2022. Roughly 5 Million dollars! 💰💰 WOAH 💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:28:42 </td>
   <td style="text-align:left;"> $AAPL still big sell prints coming though in AH - 27K share print in the last minute... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:26:16 </td>
   <td style="text-align:left;"> $SPY I heard $AAPL going to 200 this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:24:56 </td>
   <td style="text-align:left;"> $AAPL both are shit, calls/puts lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:24:02 </td>
   <td style="text-align:left;"> $AAPL has a Return On Equity of 139.79%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:23:38 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $BABA $JD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:23:10 </td>
   <td style="text-align:left;"> $AAPL company losing focus. 
 
Snap out of it TC...come on.   
 
We know the copany will drop to new 52 week lows with the production cuts and the recession... 
 
But launching stuff no one wants... 
 
Time for an exec retreat, maybe some new blood, some new thinking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:23:03 </td>
   <td style="text-align:left;"> $AAPL literally bought calls 1 min before that dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:23:03 </td>
   <td style="text-align:left;"> $AAPL - they will pump this to ATH before it’s all over </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:22:44 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:21:31 </td>
   <td style="text-align:left;"> $AAPL 172 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:20:35 </td>
   <td style="text-align:left;"> $AAPL Apple adds another subscription product, this time for companies

https://www.cnbc.com/2022/03/31/apple-launches-business-essentials-as-part-of-subscription-push.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:20:22 </td>
   <td style="text-align:left;"> $AAPL somehow I feel in April low touch is $140 per share. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:18:43 </td>
   <td style="text-align:left;"> $AAPL My guess, tomorrow 176.50 to burn both, puts and calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:18:28 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $SNOW $ABNB 
👇 Bulls at closing  😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:15:43 </td>
   <td style="text-align:left;"> $AAPL what’s that 17 m buy after hour anyone can advise </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:15:43 </td>
   <td style="text-align:left;"> $AAPL market is going to shit again. Nasdaq heading down another 20%+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:15:29 </td>
   <td style="text-align:left;"> $GOOGL $AAPL $TSLA why everything dropping all the sudden? Some news’s broke out or some? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:15:09 </td>
   <td style="text-align:left;"> $AAPL go to 160 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:14:56 </td>
   <td style="text-align:left;"> $AAPL lmfao sorry see you at 170 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:14:06 </td>
   <td style="text-align:left;"> $SPY Another good day for bulls to average down. Just keep buying the dip, fed will send us V tmrw 

$AAPL $QQQ $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:14:03 </td>
   <td style="text-align:left;"> If bulls don’t wake up over night rip $amzn $aapl $msft $tsla $GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:13:44 </td>
   <td style="text-align:left;"> $AAPL $178 tomorrow baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:13:28 </td>
   <td style="text-align:left;"> $AAPL i feel like making another account just to inverse my plays ngl

should’ve held my 172 puts lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:13:23 </td>
   <td style="text-align:left;"> $AAPL 170 tomorrow baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:12:53 </td>
   <td style="text-align:left;"> $AAPL  nice day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:12:33 </td>
   <td style="text-align:left;"> $AAPL Trading at a rudiciculous multiple with poor q2 and q3 outlook or earnings forecast so getting April 14 170 Poots. Could print big by then if market decides to finally understand that this pruxe for the biggest company in the world even is still overvalued. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:12:18 </td>
   <td style="text-align:left;"> $AAPL market manipulating piles of trash trying to push it down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:11:02 </td>
   <td style="text-align:left;"> $AAPL damn it, like after record two weeks green, now bears are like it&amp;#39;s judgment Day, Jesus will come back and I have to get ready before it&amp;#39;s too late, just keep calm and have a long vision.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:10:40 </td>
   <td style="text-align:left;"> $AAPL April Fools tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:09:59 </td>
   <td style="text-align:left;"> $AAPL ok $174-175 is what I said to buy back so mission accomplished </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:09:40 </td>
   <td style="text-align:left;"> $AAPL nothing like a 16m share sell print to boost confidence about this charade continuing to generate endless prints... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:09:34 </td>
   <td style="text-align:left;"> $AAPL he said buy and stocks tanked. Just legend 😂

https://invescohood.com/jim-cramer-says-buy-these-stocks/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:09:28 </td>
   <td style="text-align:left;"> $AAPL Gravity finally caught up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:09:19 </td>
   <td style="text-align:left;"> $AAPL even 170 puts can print tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:09:15 </td>
   <td style="text-align:left;"> $SPY legit question. What the fuck did you guys expect? NINE rate hikes into 2023. Market is forward looking. Wake the fuck up. $QQQ $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:09:11 </td>
   <td style="text-align:left;"> $SPY You say we&amp;#39;re going back to &amp;quot;ATH&amp;quot; 😆🤣😭📉  
 
OOF CALLS got DECIMATED!!! 😕⛔💀 $TSLA $AMD $AAPL $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:09:03 </td>
   <td style="text-align:left;"> $AAPL what happened? Why everything crashing? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:08:27 </td>
   <td style="text-align:left;"> $aapl 170 put lotto swing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:08:16 </td>
   <td style="text-align:left;"> latexe2a398e34b4fc614207b4ffabe2ffc13AMD ↗️ 

$AAPL $AVGO $INTC $NVDA  https://digital-strategy.ec.europa.eu/en/events/information-session-european-chips-act </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:07:12 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Just when you thought NFTs couldn&amp;#39;t get any dumber,  I present https://opensea.io/kansascash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:06:50 </td>
   <td style="text-align:left;"> That’s a wrap for Q1 up $743k. My top traded stocks were $COIN $CFVI $DWAC $FREY and $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:06:48 </td>
   <td style="text-align:left;"> $SPY So lets go over what was clear 2 days ago &amp;amp; why I called out Cramer &amp;amp; CNBC. 
 
Every pro knew how EOQ would go w/ rebalancing &amp;amp; after that pop but they were telling folks to Buy. 
 
Always do your own DD folks &amp;amp; dont let the Pros screw you 
 
$aapl $amzn $baba $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:06:44 </td>
   <td style="text-align:left;"> $AAPL needed the exact opposite lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:06:34 </td>
   <td style="text-align:left;"> $AAPL too many bears lmao. I smell a run tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:06:29 </td>
   <td style="text-align:left;"> $TSLA lol, just know, you still have the opportunity to sell after hours or at the open. The stock will be down 5-10% tomorrow. The market going to unravel. MM and dark pools fucked everyone. $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:06:04 </td>
   <td style="text-align:left;"> $AAPL i dumped at a huge gain thank you so much </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:06:01 </td>
   <td style="text-align:left;"> $NVDA $AAPL $TSLA $AMZN $BTC.X  market looks like it’s gonna plunge. This was all I saw the last hour lmfao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:05:54 </td>
   <td style="text-align:left;"> $WMT  Bring me that V shaped recovery 💪 $AAPL $SPY $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:05:45 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:04:59 </td>
   <td style="text-align:left;"> $AAPL scalped a put in the last ten minutes. Got one for next week hoping to close out tomorrow. Currently at 33 percent profit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:04:38 </td>
   <td style="text-align:left;"> $AAPL need 130 next week then 80 after earnings fail </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:04:33 </td>
   <td style="text-align:left;"> $AAPL Damnnnn that was a full blown dump! Will this dump continue into tomorrow??? That’s the real question! I’ll be on the sidelines for now until the dump is complete. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:04:23 </td>
   <td style="text-align:left;"> $AAPL this play just paid so heavy for the group and me, MASSIVE DAY and giving a deal to new members in honor! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:04:16 </td>
   <td style="text-align:left;"> $SPY $AAPL and here I stopped watching intraday because nothing was happening. WTF lmao, powerful sour hour </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:03:24 </td>
   <td style="text-align:left;"> $MSFT $AAPL $TSLA $FB $GOOG all look the same within that last 5 minutes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:03:19 </td>
   <td style="text-align:left;"> You all had your nice little bill run now let’s head back down to $150 $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:03:14 </td>
   <td style="text-align:left;"> About to hit some rough waters soon! 
 
$SPY $QQQ $AAPL  
 
Lets catch this move. 
 
💰FOLLOW for our signals DAILY💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:03:12 </td>
   <td style="text-align:left;"> $AAPL on a holiday and not following, did something happen? Glad i covered the 10x$175 Short puts yesterday tho lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:02:56 </td>
   <td style="text-align:left;"> $spy $qqq $tsla $aapl must of been politicians unloading. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:02:44 </td>
   <td style="text-align:left;"> $AAPL but but $180 this week, $200 soon 🤣 it will never see $200, biggest overhyped stock in the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:02:31 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:01:23 </td>
   <td style="text-align:left;"> $AAPL this dumping better continue tomorrow. I want to see that phantom vix spike to 23.30 tested </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:01:10 </td>
   <td style="text-align:left;"> $AAPL full market dump and pump. Damn, this is beyond manipulation. This is unbelievable corruption. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:00:33 </td>
   <td style="text-align:left;"> Be prepared for tomorrow!  
$TSLA $NVDA $AAPL $AMZN $SPY  
 
Will you ride this back down? 
 
💰FOLLOW for our signals DAILY💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:00:25 </td>
   <td style="text-align:left;"> $AAPL last 15 min was epic.  Volume
Was outa control.  Shesh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:00:23 </td>
   <td style="text-align:left;"> $AAPL $SPY 🏆🏆🏆

calling  it a day 💋💋

Hope you banked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 04:00:06 </td>
   <td style="text-align:left;"> $AAPL 4.14 $177.5C loaded on up... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:59:28 </td>
   <td style="text-align:left;"> $SPY $AAPL $MSFT $FB $TSLA 
So beautiful ~~~ 😭😭😭
We’re killing it. 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:59:03 </td>
   <td style="text-align:left;"> $AAPL 👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:58:01 </td>
   <td style="text-align:left;"> This market very much so could get crushed tomorrow!  
 
$SPY $TSLA $NVDA $AMZN $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:57:50 </td>
   <td style="text-align:left;"> $AAPL puts before 
Close? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:57:27 </td>
   <td style="text-align:left;"> $AAPL 134 ı will buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:56:57 </td>
   <td style="text-align:left;"> $AAPL when does the downward earnings guidance adjustment come out for Q1? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:56:32 </td>
   <td style="text-align:left;"> $AAPL 

All I’d did was add more to my profitable portfolio . My entire portfolio is made up of the most profitable stocks. No worries here, the money managers are buying up these stocks as they drive the price down . Good luck to all. The real investors </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:55:54 </td>
   <td style="text-align:left;"> $AAPL Bulls just trying to catch this knife! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:55:18 </td>
   <td style="text-align:left;"> $SPY Go For IT Bulls~~~ 😆📉💀🙃 $aapl $tsla $amc $chwy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:54:45 </td>
   <td style="text-align:left;"> $AAPL holding till tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:54:20 </td>
   <td style="text-align:left;"> $AAPL 💎💎how are them apple puts doing ? $LGVN $DNN $UROY  me your blessing if you follow me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:53:35 </td>
   <td style="text-align:left;"> $AAPL $TSLA China shutdown and closing factories will cut these stocks in half lol 😂 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:52:40 </td>
   <td style="text-align:left;"> $AAPL hahahahahhahaha who bought the top? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:52:34 </td>
   <td style="text-align:left;"> $AAPL wtf was that? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:52:28 </td>
   <td style="text-align:left;"> $AAPL jesus at least bounce or something this trades like a fucking penny stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:52:10 </td>
   <td style="text-align:left;"> $AAPL where all the bulls at? What happened to never shorting apple? LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:51:52 </td>
   <td style="text-align:left;"> $AAPL Good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:51:17 </td>
   <td style="text-align:left;"> $AAPL  Tech is now getting decimated </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:51:17 </td>
   <td style="text-align:left;"> $AAPL every pullback load a little more…#TLRY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:50:15 </td>
   <td style="text-align:left;"> $AAPL trying to hold 176  
171 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:49:02 </td>
   <td style="text-align:left;"> $CSIQ  
 
RECURRING REVENUE is a game changer. 
 
Canadian Solar is crushing it with their strong focus on recurring revenue: 
 
🟢Partial ownership of solar farms: electricity sales revenue 
and 
🟢Operation and maintenance of solar farms 
 
Much the same way that service revenue drove $AAPL to new heights, the diversification of Canadian Solar&amp;#39;s business model is capitalizing on more than just the cost superiority of utility scale solar. 
 
They are positioning themselves to be a cash generating beast. Once this becomes crystal clear to the market, a leap seems inevitable. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:47:18 </td>
   <td style="text-align:left;"> $AAPL  Thank goodness they just put that GREEN phone out...🤦‍♂️ Wait for it it&amp;#39;ll get there...🍀$QQQ $TSLA $SPY $STUDY 🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:46:14 </td>
   <td style="text-align:left;"> $CRWD Fake Out and Deception. 😂 
MMs putting carrot out in front then rug pull

$RH $AAPL $SPY $ROKU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:45:06 </td>
   <td style="text-align:left;"> $AAPL Gimme your premiums 🔥🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:44:58 </td>
   <td style="text-align:left;"> $AAPL live flow. Bears taking over! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:44:57 </td>
   <td style="text-align:left;"> $AAPL not a bubble at all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:44:20 </td>
   <td style="text-align:left;"> $AAPL This is the best short idea for the rest of the week...go short and sit on it....they will nail this stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:42:20 </td>
   <td style="text-align:left;"> $AAPL 2 days pinned! Burned all premiums for the week! Great job u fucken cunts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:41:36 </td>
   <td style="text-align:left;"> $TSLA MMs have been diligent, but the outflows will begin to manifest here. And then a bigger selloff at 3:50. They are genuinely going to crash the market tomorrow. $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:40:19 </td>
   <td style="text-align:left;"> $AAPL aapl $175 put cheap asf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:39:33 </td>
   <td style="text-align:left;"> $AAPL dump it or pump it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:39:04 </td>
   <td style="text-align:left;"> $ROKU at 58.00 on ROKU once 100.00 Breaks 
Whales are probably selling and shorting 😂 
$RH $AAPL $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:38:51 </td>
   <td style="text-align:left;"> $SPY $AAPL $UVXY I hear the fat lady warming up! expect some major pull back in the next few weeks;  again testing lows from earlier this month.  The titanic did not sink instantly! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:37:18 </td>
   <td style="text-align:left;"> $AAPL ATVI. DO IT. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:37:13 </td>
   <td style="text-align:left;"> $AAPL options are all over the place </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:36:37 </td>
   <td style="text-align:left;"> $AMD $AAPL $NVDA $SPY Bears don’t need a manipulated rally in order to make profit. Bears simply need patience and the market to trade freely as it should. 🎯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:36:24 </td>
   <td style="text-align:left;"> $SPY Oh, okay. $AAPL is just excluded from time space continuum now and hanging in midair. That seems legit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:35:40 </td>
   <td style="text-align:left;"> $AAPL Tough markets to trade in. Better for longer term investors </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:35:26 </td>
   <td style="text-align:left;"> $AAPL Short this with equity you cheap traders </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:35:16 </td>
   <td style="text-align:left;"> $AAPL one leg down 175-176 
Tomorrow all the way to 171 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:34:56 </td>
   <td style="text-align:left;"> $AAPL vix is starting to move up careful with longs rn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:34:50 </td>
   <td style="text-align:left;"> $AAPL Aww, love head fakes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:34:37 </td>
   <td style="text-align:left;"> $AAPL $SPY is getting slammed yet, Apple is still strong..👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:34:03 </td>
   <td style="text-align:left;"> $AAPL so market bleeding and this can’t drop one manipulation at its finest Smfh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:33:56 </td>
   <td style="text-align:left;"> $AAPL This could be the year of Tech decimation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:32:39 </td>
   <td style="text-align:left;"> latexaec964c6b34d1b54d5f1381efda0ad59BTC.x 
$NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:31:42 </td>
   <td style="text-align:left;"> $AAPL has surpassed 1 million option contracts traded today. 55% of those contracts are calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:30:40 </td>
   <td style="text-align:left;"> $AAPL closes above 177 pump into close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:29:32 </td>
   <td style="text-align:left;"> $AAPL the stock will be down 3 to $4 tomorrow , just remember where you heard it first </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:27:22 </td>
   <td style="text-align:left;"> $AABB $TSLA $AAPL $AMZN $GOOGL even lunch money makes sense now https://www.reddit.com/r/aabbstock/comments/tqr9w9/aabb_revenue_streams_and_deliverables/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:26:36 </td>
   <td style="text-align:left;"> $AAPL Bear Trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:26:01 </td>
   <td style="text-align:left;"> $SPY $qqq $aapl $amzn $goog that bounce gonna be HUGEEEEEEE🔥🔥🔥🔥🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:25:45 </td>
   <td style="text-align:left;"> $AAPL 

This trend is clearly indication of many people losing money on short coverage to prevent margin calls.

They are closing shorts at that range to minimize loss.

So it’s bound to take off anyways breaking 178 resistance point. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:25:30 </td>
   <td style="text-align:left;"> $AAPL let’s go power hour!! I’m tryna get some real cheap puts😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:25:30 </td>
   <td style="text-align:left;"> $AAPL I see this going to South Korea to 170 tomorrow and 165 Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:24:59 </td>
   <td style="text-align:left;"> Apple, Meta and Amazon drop off Comparably’s 2022 best company cultures list after topping last year’s ranking—here’s why

$AAPL $FB $AMZN

https://www.cnbc.com/2022/03/31/apple-meta-and-amazon-drop-off-comparablys-annual-best-company-cultures-list.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:24:23 </td>
   <td style="text-align:left;"> $AAPL wasn’t brave enough to hold 4/1 puts but I’m going for 4/8😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:22:51 </td>
   <td style="text-align:left;"> $AAPL what was that harsh up / down roller coaster ride? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:22:34 </td>
   <td style="text-align:left;"> $AAPL purest pump and dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:22:34 </td>
   <td style="text-align:left;"> $AAPL up tomorrow. This fake out and consolidating is okay. 180c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:21:14 </td>
   <td style="text-align:left;"> $AAPL that Liddo bull trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:20:29 </td>
   <td style="text-align:left;"> $AAPL $180 calls yesterday and today 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:19:35 </td>
   <td style="text-align:left;"> $AAPL  Posted the larger chart earlier on this saying this is what they want if they get her above the red line she technically regains horizontal support and a trend line it doesn&amp;#39;t matter what they have to do to get it there or how sloppy the chart is as long as they keep it above that line they will claim victory </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:19:13 </td>
   <td style="text-align:left;"> $AAPL I too enjoy a nice fake out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:18:40 </td>
   <td style="text-align:left;"> Some top tech sector flow coming in above ask 
 
$ADSK - $1.8M put block 
$NVDA - $632K call sweep 
$AAPL - $615K call sweep </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:18:20 </td>
   <td style="text-align:left;"> $TSLA $GM $TTDKY $AAPL collective power house </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:15:15 </td>
   <td style="text-align:left;"> $NVDA ran over 249%. $SPY $QQQ $AMZN $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:14:35 </td>
   <td style="text-align:left;"> $AAPL  whale dumping to retailers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:12:01 </td>
   <td style="text-align:left;"> $AAPL Might get some window dressing here so bag holding advisers can tell their clients they tanked in the best and CNBC&amp;#39;s fave next quarter lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:09:59 </td>
   <td style="text-align:left;"> $AAPL it’s gonna be a red day and that’s fine but damn. Drop if you wanna drop. Quit bending over😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:09:31 </td>
   <td style="text-align:left;"> $KT Just saying.....

$MSFT $TSLA $AMZN $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:09:28 </td>
   <td style="text-align:left;"> $AAPL  is it possible tomorrow 182 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:08:04 </td>
   <td style="text-align:left;"> $V $MA $AAPL $WEN $SBUX some stocks were down more than 40 percent, does anyone realize we basically had a crash last month? 
 
Get ready for another bull run! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:06:50 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL

the printer still works folks, believe in 
it.😤🙏 🖨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:06:35 </td>
   <td style="text-align:left;"> $AAPL $FB $AMZN Apple, Meta and Amazon drop off Comparably’s annual best company cultures list

https://news.alertsandnews.com/apple-meta-and-amazon-drop-off-comparablys-annual-best-company-cultures-list/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:06:04 </td>
   <td style="text-align:left;"> $AAPL  They have pulled the same formation off so many times in the past few days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:04:42 </td>
   <td style="text-align:left;"> $AAPL bulls who bought bottom of dip, boom!  bears who bought bottom of dip? doom... like always ;-) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:03:40 </td>
   <td style="text-align:left;"> $MSFT $AAPL last 2 days of month/ quarter rebalancing done- we go up from here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:03:39 </td>
   <td style="text-align:left;"> $AAPL too easy Wall Street lol $$$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:03:24 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL

do what you do best brandon and full send this sh*t </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:03:00 </td>
   <td style="text-align:left;"> $AAPL she’s gonna blow 🤢 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:02:15 </td>
   <td style="text-align:left;"> $AAPL break out 💪🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:02:10 </td>
   <td style="text-align:left;"> $AAPL   🍏 WallSt/Mkt, taking care of “End of Month Business”, today.  Remember, many HFunds will “Close-Out March with Losses” and are/were “positioned off-sides” going into April 1.  Today/Yesterday, was about an “orderly period”, to cleanup, close-out, and re-position.  Trade smart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:01:53 </td>
   <td style="text-align:left;"> $AAPL could $SPY and 🍏 finish the day green?!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:01:08 </td>
   <td style="text-align:left;"> $AAPL Reaction Now. 
Volume &amp;gt;150K. Per Minutes. 
Nasdaq change. 
Go to POSITIVE. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 03:00:36 </td>
   <td style="text-align:left;"> $AAPL Clown ass stock dawg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 02:59:49 </td>
   <td style="text-align:left;"> $AAPL Pocket change $$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 02:59:19 </td>
   <td style="text-align:left;"> $AAPL Most overbought markets since june 20,2020 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 02:59:05 </td>
   <td style="text-align:left;"> $AAPL nice leg up right there - PH should be interesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 02:56:39 </td>
   <td style="text-align:left;"> $SPY The close should be interesting. Pros not looking to Buy into the Data &amp;amp; w/ April coming up the Selling into may should ramp up so lets see how this plays out in things like $aapl $amzn $msft $ QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 02:55:56 </td>
   <td style="text-align:left;"> $AAPL power hour?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 02:55:00 </td>
   <td style="text-align:left;"> $AAPL I guess imma gamble into tomorrow with puts😢 pray for me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 02:54:54 </td>
   <td style="text-align:left;"> $AAPL $V $MA $WEN $SBUX jobs report tomorrow bitches!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 02:54:50 </td>
   <td style="text-align:left;"> $AAPL 
Market Cautious.  
After 3PM. Next definition 
UP OR DOWN NASDAQ. 
🍏🔜🔝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 02:54:25 </td>
   <td style="text-align:left;"> $aapl buy signal detected 🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 02:50:43 </td>
   <td style="text-align:left;"> $AAPL buying more. Can never own enough of this baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 02:50:14 </td>
   <td style="text-align:left;"> $AAPL shorties love this stonk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 02:49:08 </td>
   <td style="text-align:left;"> $AAPL wants to go!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-04-01 02:47:27 </td>
   <td style="text-align:left;"> $AAPL pinned between 175 put and 177.50 call and burning both </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 09:01:46 </td>
   <td style="text-align:left;"> $SPY Cathie Wood dumped shares of Tesla worth $40million today. $TSLA 

Guess she finally learned to sell the top. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:59:33 </td>
   <td style="text-align:left;"> $TSLA Just read that Kathy would dumped Tesla shares worth 40 million on Thursday

$spy  Considerable amount

Cathy’s throwing down she’s like $40M bye bye 

Like no big  deal  $40 M. On a Thursday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:59:32 </td>
   <td style="text-align:left;"> $TSLA wakeup Elon, not all Tesla holder is usa, many china, me hold Tesla moon $spy

We pay tax if you do the not split dividend thingy, wakeup Elon!!! Elon you anti China holder or what?

SPLIT the normal way, not dividend split, need pay tax, you are kid elon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:59:07 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Cathie Wood Dumped Tesla Shares Worth $40M On Thursday https://www.stck.pro/news/TSLA/25398898 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:57:40 </td>
   <td style="text-align:left;"> $TSLA dividend is bad, why pay tax? I&amp;#39;M CHINA, YOU ELON MAKE THIS not split FOR WHAT!!! $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:57:25 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA 

This feels like the peak of fear at the end of Monday March 14, just before the face ripping one week rally of 10+%. 
How many bears were so sure that we will have an epic market collapse on Tuesday, March 15, eh? How many were counting their puts would print bigly? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:56:50 </td>
   <td style="text-align:left;"> $TSLA Cathie Wood Dumped Tesla Shares Worth $40M On Thursday 

https://newsfilter.io/a/3d19df987b6bac3432993edd6ec86360 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:53:47 </td>
   <td style="text-align:left;"> $TSLA this is going to boooom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:53:29 </td>
   <td style="text-align:left;"> $TSLA The biggest Tesla Maxi Cathie Woods is selling off rapidly. Not too much gain from here possibly. She&amp;#39;s still bullish, but I guess she sees better short term allocation opportunities. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:50:10 </td>
   <td style="text-align:left;"> $TSLA $1150 by 2pm est mark it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:41:52 </td>
   <td style="text-align:left;"> $TSLA is it true that tesla is going to stop priducing cars snd focus on mopeds/Vespas insted?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:41:44 </td>
   <td style="text-align:left;"> $AMC $TSLA Who needs WallStreetBets when you have Xtrades. Thanks to Xtrades, I have doubled my entire portfolio in just one week. Joining this Discord community was the best investment I&amp;#39;ve ever made!~!~ amazing-stocks-room.stockmarketus.xyz/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:40:11 </td>
   <td style="text-align:left;"> $GGPI  2024 1. Polestar 2. Tesla $TSLA $LCID $FSR  everyone else BK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:39:46 </td>
   <td style="text-align:left;"> $GME ===&amp;gt; $240  by FRIDAY CLOSE!  😊🎊🎉🎈🔥🚀🚀🚀 
. 
$SPY $QQQ  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:39:31 </td>
   <td style="text-align:left;"> $TSLA this thing is running tomorrow and next week. Stocks only go up.. blah blah blah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:39:10 </td>
   <td style="text-align:left;"> $TSLA you gotta try harder if you want us to feel the sting.  The economy is roaring! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:37:59 </td>
   <td style="text-align:left;"> $TSLA same guy tells me 1053 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:35:25 </td>
   <td style="text-align:left;"> $TSLA  Gut tells me TSLA will test $1053 tomorrow morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:33:15 </td>
   <td style="text-align:left;"> $TSLA https://www.businessinsider.com/tesla-bull-stock-split-electric-vehicle-retail-investor-elon-musk-2022-3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:32:04 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-31 Chart Analysis Video: 
https://www.youtube.com/watch?v=lofGaydy9SE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:30:45 </td>
   <td style="text-align:left;"> $TSLA This thing is gonna absolutely moon shot on Monday after monstrous delivery numbers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:24:09 </td>
   <td style="text-align:left;"> $TSLA 🚨 LAST OPTION TRADED BEFORE AH TODAY😎🎰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:23:23 </td>
   <td style="text-align:left;"> I needed a win today. thank you $GME sold 25 percent of shares. Loading more $SNDL wtf not just insane news. Love it. $AMC is running a little too. $TSLA all day every day. $NIO needed a cool off. Tomorrow we Friday green this bitch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:21:55 </td>
   <td style="text-align:left;"> WE ARE NOW LIVE🔥 
Im going to breakdown 👇 
📈 TRADE IDEAS 
🔫TRIGGERS 
🎯TARGETS  
👉https://us02web.zoom.us/j/86008942468 $spy #pressit  $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:21:31 </td>
   <td style="text-align:left;"> $TSLA Seems like the stock price will go 700-1000 channel for a while until break out higher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:18:49 </td>
   <td style="text-align:left;"> Why is $TSLA doing a stock split now? 
 
Well, I have a theory on that. Hear me out... 
 
WATCH: https://youtu.be/RIz4VziiGCk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:17:43 </td>
   <td style="text-align:left;"> latex182a2dae8857d2802944cec74dee8eeeTSLA to 1051 can come if it stays under 1100 Puts can work under 1075. 
 
$AMZN if we see a sell off it can drop to 3242 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:13:25 </td>
   <td style="text-align:left;"> $HIMX $NVDA $NIO $TSLA Electric Vehicle adoption is a major uplift for chipmakers 

https://finance.yahoo.com/video/electric-vehicle-adoption-major-uplift-143001737.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:12:55 </td>
   <td style="text-align:left;"> $TSLA Cathie Wood’s @ARKInvest sold more than 36k shares of $TSLA shares today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:12:10 </td>
   <td style="text-align:left;"> $TSLA Can’t lie today wasn’t nice lol. Bulls we had a good run. Next week we could regain the throne . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:11:51 </td>
   <td style="text-align:left;"> $TSLA 1150 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:11:20 </td>
   <td style="text-align:left;"> Cathie Wood sold 37,500 shares of $TSLA today. 
 
I now have 37,500 more reasons to be bullish on $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:08:21 </td>
   <td style="text-align:left;"> $TSLA so many bears in here saying drop tomorrow I think we’ll run </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:06:10 </td>
   <td style="text-align:left;"> $TSLA $1200 by when? Next Friday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:02:31 </td>
   <td style="text-align:left;"> $TSLA  Hey tessie cult bitches....lil lesson....these are called bearish island reversals. Smart people DON&amp;#39;T BUY HERE.  I have my eye on a long entry, but definitely not here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:01:32 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:00:40 </td>
   <td style="text-align:left;"> $TSLA Elon tomorrow morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 08:00:00 </td>
   <td style="text-align:left;"> $TSLA is one of the better performing stocks in the Automobiles industry. https://www.chartmill.com/stock/quote/TSLA/technical-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:59:26 </td>
   <td style="text-align:left;"> $TSLA stock has been closing in on their 52wk high of 1,243. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:59:00 </td>
   <td style="text-align:left;"> $TSLA 1375$ gonna be ok for may 20th? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:58:51 </td>
   <td style="text-align:left;"> $TSLA sorry to be the messenger of bad news fellas, but there will be a healthy pull back tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:58:40 </td>
   <td style="text-align:left;"> $TSLA love red days buy! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:58:05 </td>
   <td style="text-align:left;"> $TSLA momentum shifted 
Unless PR comes out 
May drop more tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:56:37 </td>
   <td style="text-align:left;"> $GME Plans to issue a stock dividend in the form of a stock split. Guess who did this before multiplying their market cap in the process?  $AAPL and $TSLA 

Good luck short sellers. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:56:26 </td>
   <td style="text-align:left;"> $TSLA 😳👉 https://youtu.be/Qcqjt_6g7-I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:55:46 </td>
   <td style="text-align:left;"> $TSLA Pharaoh thought he was in control too. You won&amp;#39;t be able to play with these numbers that come out. 😉🙃🙂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:55:34 </td>
   <td style="text-align:left;"> $TSLA when are delivery numbers out? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:53:40 </td>
   <td style="text-align:left;"> $TSLA bears Elon got a surprise for you for april fools day. It&amp;#39;s your day right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:53:25 </td>
   <td style="text-align:left;"> $TSLA keep coming down mama, $999 and </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:52:50 </td>
   <td style="text-align:left;"> $TSLA 

https://twitter.com/unusual_whales/status/1509591085634363393?s=21&amp;amp;t=o24W_jApnoLPtx1SQK7x3g </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:52:26 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL My interview with @DolanDrumpf went so well and I learned a lot!  Now I’m trying to figure out who should be the next Stocktwitter to be interviewed on my YouTube channel.  I’m looking for suggestions or volunteers! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:52:22 </td>
   <td style="text-align:left;"> $AMC $amd $TSLA  all will come bakk down 🚨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:50:46 </td>
   <td style="text-align:left;"> $TSLA Bitcoin is dumping, it’s best to sell and buy puts fuck tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:50:37 </td>
   <td style="text-align:left;"> $TSLA When is delivery report due? Any insight into that? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:49:46 </td>
   <td style="text-align:left;"> $TSLA holy smokesss reddy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:47:51 </td>
   <td style="text-align:left;"> $ADA.X No doubt this will flip $ETH.X by 2030. We are still SO EARLY. I&amp;#39;ve been wrong before and I&amp;#39;ve been right ( $TSLA  ). Just be patient and life will be good. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:47:33 </td>
   <td style="text-align:left;"> $TSLA down 2 bucks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:46:58 </td>
   <td style="text-align:left;"> $TSLA not even 2% down wym </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:46:57 </td>
   <td style="text-align:left;"> $TSLA AH CRASH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:46:39 </td>
   <td style="text-align:left;"> $TSLA watch out bulls. Down not even a percent after hours! Wow, such a crash 🤡🤣 dumb ass bears. So desperate. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:46:18 </td>
   <td style="text-align:left;"> $TSLA bears literally just seem like the most angry and sad people… “it can’t keep going” lol money is fake and made up and the world is in DEBT (LOL WHAT) they won’t let this shit crash they’ll just keep printing money and change some bullshit around to make it make sense… it’s a joke. Even if this dropped 20 points tomorrow bears will be like “omg it’s happening”. Such a joke. Get a beer and have some fun… keep betting against Tesla lmaoooooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:45:35 </td>
   <td style="text-align:left;"> $TSLA she’s taking a nice little spill after hours ain’t she? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:45:05 </td>
   <td style="text-align:left;"> $TSLA Elon and Cathie woods on live </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:44:37 </td>
   <td style="text-align:left;"> $TSLA under 1070 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:42:51 </td>
   <td style="text-align:left;"> $TSLA usually when tesla is starting with green it ends up red but if it starts with red it ends green! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:42:47 </td>
   <td style="text-align:left;"> $TSLA Same old story, trapped the RobinHood traders with a phony run up to be followed by weeks of dumping on their heads, just like January </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:41:55 </td>
   <td style="text-align:left;"> $TSLA crashing after hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:41:12 </td>
   <td style="text-align:left;"> $TSLA 

How many shares or overprices properties are you required to own on credit in order to flex one on TikTok?

Wheel covers (plastic logos) are like 300 dollars, correct?

Oh and besides all that, this shit bearish mayne </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:41:04 </td>
   <td style="text-align:left;"> $TSLA meme stock investors are selling this and running it down AH to buy $GME.. I don’t blame em.. if you’re gonna own a meme stock atleast own a good one! GME up 15% on split news and TRASHLA only up 6% 

🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:40:40 </td>
   <td style="text-align:left;"> $AMZN $TSLA

https://www.fool.com/investing/2022/03/30/my-2-best-stock-split-growth-stocks-to-buy-now-and/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:38:45 </td>
   <td style="text-align:left;"> $TSLA sucks when low of day happens after hours…not a good sign for my calls next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:38:07 </td>
   <td style="text-align:left;"> $TSLA Crashing after hours Jesus </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:36:47 </td>
   <td style="text-align:left;"> $TSLA why is this down after hours when futures up bigly? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:35:29 </td>
   <td style="text-align:left;"> $TSLA $SPY $GME $AMZN  all these stock splits attempt to retain buyers through rough times, and to avoid higher buyback rates , retail thinks they are trying to help existing investors 😀 8 slice pizza better than a 6 slicer , lets pay more..hahahaha 😆 😂 😜 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:35:19 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA 

0331 baby!! No better way to end it on a red day. Machine gunners definitely bought poots.😤😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:32:51 </td>
   <td style="text-align:left;"> $TSLA tesla order to buy back tesla in Germany after auto pilot driving like a drunken sailor what the hell is going on here I want answers god damn it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:32:25 </td>
   <td style="text-align:left;"> $TSLA 5 day Chart ridiculous. the yellow lines are major support levels. Saying this can free fall is a under statement. Puts for the next 2 weeks. Thx me layer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:29:12 </td>
   <td style="text-align:left;"> $TSLA after market red or green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:25:49 </td>
   <td style="text-align:left;"> $BTC.X for all the folks still questioning if bitcoin is an inflation hedge.  $TSLA is up 1.36x on its BTC purchase from a year ago and $MSTR is up 1.6x by DCA over a similar timeframe.  While the dollar has lost 7.5% in value due to inflation.   https://yellowblock.io/hold-my-beer-terra-already-up-165m-from-buying-bitcoin-as-btc-stash-nears-teslas/ $MARA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:23:59 </td>
   <td style="text-align:left;"> $TSLA 

Seriously !! 🤣🤣🤣
IIHS!!? 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:22:19 </td>
   <td style="text-align:left;"> $TSLA 

Today’s and yesterday’s volumes on the two down days were very light. About 50%-60% of the normal volume. We are going to rocket up soon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:22:08 </td>
   <td style="text-align:left;"> $TSLA YO THIS SHIT DIPPING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:20:48 </td>
   <td style="text-align:left;"> $TSLA  🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:19:59 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/3xbuYIt9Ryo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:18:41 </td>
   <td style="text-align:left;"> $GME $AMC $SAITAMA.X $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:18:40 </td>
   <td style="text-align:left;"> $SPY my outs from Mid-April have Max Pain. $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:18:27 </td>
   <td style="text-align:left;"> $TSLA $GME $AMC journey to $10k begins </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:17:37 </td>
   <td style="text-align:left;"> $TSLA so many desperate bears here. Let’s go over to GME and piss off the apes instead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:16:17 </td>
   <td style="text-align:left;"> $TSLA All the day gamers here are a hoot. I own leaps, see U in Jan’23 at $1500 and Jan ‘24 at $2500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:16:02 </td>
   <td style="text-align:left;"> $TSLA China lockdown is getting more expanded. not good fir Tesla? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:12:18 </td>
   <td style="text-align:left;"> $TSLA Sold a 4/8 $1015P for $13.50 late afternoon. Waiting for tomorrow or Monday to sell more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:12:01 </td>
   <td style="text-align:left;"> $ibatf $llkkf $tsla 💰💰🕰🕰🕰🔋🔋🔋🔋🔋🔋🔋🔋🔋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:11:22 </td>
   <td style="text-align:left;"> $TSLA TESLA Stock Price  Prediction and Analysis for tomorrow Friday April 1
https://youtu.be/a3KDEovHsuo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:10:17 </td>
   <td style="text-align:left;"> $TSLA where were the fomoers @7-8-900s?? Of course can get a 60-90 pt retracement .  Welcome to the stok mkt! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:09:36 </td>
   <td style="text-align:left;"> $TSLA dippping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:09:25 </td>
   <td style="text-align:left;"> $TSLA Option to look at today.. 👀 👀  $1600.00 Call for Friday, April 1, 2022. Roughly 2 Thousand dollars! 💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:08:48 </td>
   <td style="text-align:left;"> $TSLA 🛥 🛥 🛥🛥🛥🛥🛥🛥🛥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:08:22 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $MRVL $PATH 
Bears celebrating  for 1.3% relief rally. 
Futures are already recovering  ⤴️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:07:46 </td>
   <td style="text-align:left;"> After this $TLRY $CLVR Marijuana bill stuff, I’ll be long $GME $AMZN &amp;amp; $TSLA and just wait it out.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:07:20 </td>
   <td style="text-align:left;"> $TSLA why bulls big mad that some of us bought Puts 😂🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 07:04:29 </td>
   <td style="text-align:left;"> Comparison charts: $GME and $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:59:07 </td>
   <td style="text-align:left;"> $TSLA Do not buy, blood is coming 🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:58:38 </td>
   <td style="text-align:left;"> https://www.youtube.com/watch?v=H0V6_VgPUjU $amzn $tsla $nvda $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:56:17 </td>
   <td style="text-align:left;"> How can I buy Russian stocks from UK or europe?
Please don&amp;#39;t teach me humanity. Im from middle east. This is new for you not for me. $TSLA $FB $AMC $GME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:56:15 </td>
   <td style="text-align:left;"> $TSLA 1132 tomorrow 😐😀📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:55:24 </td>
   <td style="text-align:left;"> $TSLA Weak ass AH meanwhile futures are up o well ill wait until monday for my 100 point pop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:53:53 </td>
   <td style="text-align:left;"> $TSLA @BBKingSing  imagine getting all your stock calls this wrong 😂 😂 Gordon Johnson of stocktwits lady’s and gentleman 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:53:33 </td>
   <td style="text-align:left;"> This is why Hedge Funds use A.I. $TSLA Aroon Indicator entered an Uptrend. View odds of downtrend. https://srnk.us/go/3543818 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:53:05 </td>
   <td style="text-align:left;"> $SPY $TSLA are people calling into Cramer, from a halfway house? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:53:04 </td>
   <td style="text-align:left;"> $TSLA As bullish as I always am, it’s finally rolled over. Could see a gap up Monday but likely done for this week, I’ll be watching tomorrows action. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:52:59 </td>
   <td style="text-align:left;"> $TSLA puts from yesterday went pretty well. After adding to it took 50% profit. Still in next weeks. 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:51:37 </td>
   <td style="text-align:left;"> $TSLA Cramer is bullish. Sorry longs. It was nice while it lasted. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:48:50 </td>
   <td style="text-align:left;"> $TSLA Follow Wall Street and Buy TSLA Stock to Bet on National Security

https://investorplace.com/2022/03/follow-wall-street-and-buy-tsla-stock-to-bet-on-national-security/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:48:01 </td>
   <td style="text-align:left;"> $TSLA MASSIVE SELLOFF INCOMING GOOD LUCK CALL HOLDERS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:46:54 </td>
   <td style="text-align:left;"> $TSLA Massive Tesla sell off. GL tomorrow and in the coming weeks bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:45:21 </td>
   <td style="text-align:left;"> $TSLA wen ceo social media pump? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:43:35 </td>
   <td style="text-align:left;"> $TSLA NEWS - TSLA Possible Stock Split: 
https://www.youtube.com/watch?v=rF_AhzPRCNQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:42:51 </td>
   <td style="text-align:left;"> $TSLA okay I lied I bought 21 1200 calls tomorrow expiry for .18 each for a $360 lotto ticket. This hits 1150 tomorrow that’s 10k let’s go and hit it based on nothing!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:39:41 </td>
   <td style="text-align:left;"> $TSLA tomorrow will be a fun one to watch. Bulls still all hope and no reality. Yeah I’ve been bearish since $900, but not so worried. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:39:32 </td>
   <td style="text-align:left;"> $TSLA will become the 1st $10 Trillion company.. mark this post 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:39:27 </td>
   <td style="text-align:left;"> Well, here we go again. $GME calls to $400 are out once again. 
 
Will history repeat itself for a 3rd time?  
 
Well, we all remember what a cult stock like Tesla $TSLA did when it announced a stock split in 2020.  
 
It ran up 10X from the lows in 2020 to the highs in 2021.  
 
However, do not for one second believe that will happen with GME but a run-up to $400 as the article mentions is now a real possibility because of that stock split news in the works. This type of news could or may drive high buyer interest back into GME at FOMO type levels at some point in the near future. 
 
Just make sure to lock in profits along the way up. 
 
Also keep eyes on $AMC as this too could follow GME as a sympathy play. 
 
 https://uk.investing.com/news/stock-market-news/could-gamestop-reach-400-again-technically-yes-and-heres-why-2616796 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:39:17 </td>
   <td style="text-align:left;"> $TSLA Daily 
 
Free Discord link in bio, First 100 members get entered in a giveaway. 
 
Tesla has been trying to get over the 1118 resistance for the past few days. Gap is open at 1010.64, can be filled before we go higher. Would like to see break above 1118 resistance or gap filled before going long. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:38:57 </td>
   <td style="text-align:left;"> $TSLA they are gonna hit hard tomorrow at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:38:30 </td>
   <td style="text-align:left;"> $IPOF Is Ipof STARLINK? $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:33:11 </td>
   <td style="text-align:left;"> $TSLA I got some puts. Lets see if they print tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:32:04 </td>
   <td style="text-align:left;"> Daily Market Recap for Thursday 3/31/2022 for #Stocks #Bitcoin #Gold and #Silver
https://youtu.be/2VA37dR6G7k

$AMD $AAPL $TSLA $RBLX

Who shorted tech?  Look for pops to short. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:31:35 </td>
   <td style="text-align:left;"> $TSLA 

Don’t bet against Tesla. Never too late to learn. LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:30:38 </td>
   <td style="text-align:left;"> $TSLA With Tesla Localizing EV Production, This Analyst Says Musk’s Brand Is Becoming A Renewable Energy Play

https://news.alertsandnews.com/with-tesla-localizing-ev-production-this-analyst-says-musks-brand-is-becoming-a-renewable-energy-play/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:30:30 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $MSFT $AMZN 
🙋‍♀️ Hey bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:29:32 </td>
   <td style="text-align:left;"> CONGRATULATIONS ON THE WIN 🌟 AMAZING TRADE CALLED OUT JUST BEFORE THE SOUR HOUR TODAY. LAST 15 MINUTES WERE LIT 🔥 MADE OVER 90% PROFITS ON THIS ALERT. 

JOIN OUR PREMIUM STOCKTWITS ROOM FOR MORE TRADE ALERTS &amp;amp; IDEAS:
https://rooms.stocktwits.com/checkout/4560671/prod_Kpk7ezeIDS8ksT

FOLLOW THIS ACCOUNT TO GET REAL TIME NEWS UPDATES. 

$TSLA $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:29:14 </td>
   <td style="text-align:left;"> $TSLA lol if you have puts… man they may just rip faves off tomorrow to the upside it’s been consolidating for a bit. No position. Chillin if I had calls or puts right now I would be STRESSED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:28:28 </td>
   <td style="text-align:left;"> $TSLA $176,456.27 tomorrow based on advanced TA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:28:15 </td>
   <td style="text-align:left;"> $TSLA I don’t think it’ll go sub $1000 . I think a pull back tomorrow for another bullish run Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:26:32 </td>
   <td style="text-align:left;"> $TSLA bear told me to spread cheeks so I shall:( </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:25:17 </td>
   <td style="text-align:left;"> $TSLA lmfao Tesla is so weak that all it takes is one day to turn the entire weekly candle from bullish to bearish 🤣🤣🤣

Spread your cheeks bulls, you blew your shot! 🤣🤣💀💀💀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:22:48 </td>
   <td style="text-align:left;"> $TSLA or $XPEV ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:21:48 </td>
   <td style="text-align:left;"> $TSLA tap that 1020 gap man that’s what we all need </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:21:10 </td>
   <td style="text-align:left;"> $TSLA $500 tomorrow 🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:16:44 </td>
   <td style="text-align:left;"> $TSLA Still </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:14:26 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:14:10 </td>
   <td style="text-align:left;"> So $GME consulting with Elon $TSLA now? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:13:39 </td>
   <td style="text-align:left;"> $TSLA when the sell off starts, how many PMs will stick around for delivery numbers that will already be reflecting over a week of China? No one wants to start the quarter on a sour note after such a triumphant recovery for Q1. MMs can’t control this tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:13:02 </td>
   <td style="text-align:left;"> $HOMERUN.X $TT.X $TSLA  come check us out, 100x your investment!!!

We&amp;#39;re just getting started </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:10:37 </td>
   <td style="text-align:left;"> $TLOFF $TSLA $TMC https://finance.yahoo.com/news/us-ev-battery-supply-chain-194900498.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:09:10 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-31 Daily Forecast Video: 
https://www.youtube.com/watch?v=QDm-Rizbtxc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:08:26 </td>
   <td style="text-align:left;"> $TSLA Friday sell off, 10% day EZ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:08:19 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:07:34 </td>
   <td style="text-align:left;"> $TSLA $AAPL no one in their goddamn mind is going to subscribe for luxury goods, which will undoubtedly be more expensive than financing or inhibit cash flows…there is a reason this mode doesn’t work, banks will always get $$ cheaper </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:07:29 </td>
   <td style="text-align:left;"> $GME 10x after split like $TSLA see you at $1000 lads </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:02:08 </td>
   <td style="text-align:left;"> $TSLA is there really any reason to rent a car for 1k a month? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:01:45 </td>
   <td style="text-align:left;"> $TSLA 
Jeez. Some people got no chill on ST🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:01:08 </td>
   <td style="text-align:left;"> $TSLA shame on you if you didn’t go short today. The MMs won’t be in control tomorrow $SPY $ AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 06:00:29 </td>
   <td style="text-align:left;"> $TSLA Frickin 4-D chess going on between heggies MM and Memers! CRAZY 👏👏👏
Now gme announcing split like tsla!  Wen amc split?  Exposing synthetics and crushing shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:59:55 </td>
   <td style="text-align:left;"> $TSLA this continues to get wrecked tomorrow . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:58:06 </td>
   <td style="text-align:left;"> $TSLA $SPY 
Historically tomorrow is suppose to be green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:58:01 </td>
   <td style="text-align:left;"> $TSLA $SPY $AAPL $MSFT $BABA 
Happy  ❤  Thursday, everyone  🎊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:57:53 </td>
   <td style="text-align:left;"> $TSLA When volume returns,  doubt it&amp;#39;s going to be very bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:57:47 </td>
   <td style="text-align:left;"> $TSLA and this guy has to get a sex change 😂 post pics @internetentrepreneur </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:57:00 </td>
   <td style="text-align:left;"> $TSLA is expected to show a strong growth in EPS. In the coming 5 years, the EPS will grow by 26.78% yearly. https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:56:57 </td>
   <td style="text-align:left;"> $TSLA don’t listen to this guy.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:56:36 </td>
   <td style="text-align:left;"> $TSLA supply chain is the only krptonite. Musk should spend money on tech innovation to take tsla to next dimension </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:56:17 </td>
   <td style="text-align:left;"> $TSLA do not listen to anyone talking of rebalancing etc….the only reason this got as high as it did was to crush the Q1 numbers. Funds will be taking risk off starting tomorrow. Tsla is the biggest risk out there in terms of volatility and market cap. Still a great company, but could easily shave off 5-10% tomorrow, and likely will. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:55:14 </td>
   <td style="text-align:left;"> $TSLA Heyyyy doofus me, you forgot to hit the blue post button 😂 

We all make mistakes see..like some of those call options held expiring tomorrow. 

GL 🍀✌️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:53:46 </td>
   <td style="text-align:left;"> $TSLA #TLRY🔥 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:52:42 </td>
   <td style="text-align:left;"> $AMD $TSLA institutions rebalanced today as last day of the quarter we&amp;#39;ll be back to the game tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:52:04 </td>
   <td style="text-align:left;"> $TSLA sub $1000 tomorrow ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:52:02 </td>
   <td style="text-align:left;"> $TSLA $QS yall are in bed together dont lie, knowing j.b straubel is an independent director at QS and also the co-founder of tesla

Quantumscape AND TESLA?!?!

Both following company in coordination </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:51:26 </td>
   <td style="text-align:left;"> $TSLA 

Knew this week might finish below $1100 since there are so many calls at the strike, although one more day in this week.

Ahh… but next week.  That is an entirely different story. Quarterly delivery number and Texas Giga Factory and possible stock split decision… all coming soon!! 
Back toward $1200. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:50:29 </td>
   <td style="text-align:left;"> Stocktwits: 
VIDEO: Broad Market Technical Analysis Chart 3/31/2022 $SPY $QQQ $GME $TSLA $CCJ https://www.chartguys.com/daily-market-videos/4206/bears-back-in-action </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:50:04 </td>
   <td style="text-align:left;"> $SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:46:44 </td>
   <td style="text-align:left;"> latex2e4772876f4684fd250a12f679249977$SPY $TSLA $AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:45:08 </td>
   <td style="text-align:left;"> $TSLA bears think this is the start of the  big correction... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:45:05 </td>
   <td style="text-align:left;"> $GME stock splits. A pre indicator for falling stock market and econemy $TSLA $AMZN $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:44:33 </td>
   <td style="text-align:left;"> $ISPO shorts will never be afford SAFE and LUXURIOUS travel $BKNG $NCLH $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:42:21 </td>
   <td style="text-align:left;"> $SPY oh we&amp;#39;re dying take out tonight huh... delivery vegan 🦞 and dairy free dessert 🍨 😁🙋‍♂️💦 
 
BULLS got played majorly, I feel sorry for them because they refuse to accept reality that that &amp;quot;old bull market ponzi energy&amp;quot; is drying up! - NO WORRIES we&amp;#39;re hiring down at the local BEARMART 🐻🏢  $TSLA $AAPL $QQQ $LULU 😆🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:39:42 </td>
   <td style="text-align:left;"> $TSLA here goes my 2000$ in drain. Need to find some good opportunity to make it back. 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:37:41 </td>
   <td style="text-align:left;"> $TSLA Russia just handed Tesla a golden ticket. 
Forcing Europe to buy rubles for gas is going to lead to a multinational ramp up of solar and energy storage 100%. 
This is huge and a bit of a distraction from the car business but the immediate cash infusion for every national interest... this is massive. Like quantum leap massive. Expect this domino&amp;#39;s revelation in about 2 weeks. 
Mark it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:37:34 </td>
   <td style="text-align:left;"> $TSLA with 310k delivered in Q1 Tesla will deliver by far more than 1 MILLION cars during past 12 months $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:37:09 </td>
   <td style="text-align:left;"> $TSLA @Tsm 4/14 130C at 0.05 🤣😅 keep loading up , i will get back to Tesla after ER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:36:11 </td>
   <td style="text-align:left;"> $SPY Bull thesis is that sheep stocks like $AAPL and $TSLA continue running to ever-higher highs, unperturbed by deteriorating fundamentals. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:32:47 </td>
   <td style="text-align:left;"> $TSLA bargain buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:31:00 </td>
   <td style="text-align:left;"> $SPY Q1 is in the books!   Q2 going to be even better!    

$AMD $TSLA $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:30:21 </td>
   <td style="text-align:left;"> $TSLA is lord elon selling again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:29:59 </td>
   <td style="text-align:left;"> Closed my $TSLA position for a $490 profit didn&amp;#39;t want to hold through earnings closed my $USO position for a quick $348 profit and opened a new position in $TLT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:29:28 </td>
   <td style="text-align:left;"> $TSLA Wanna bet bears get shanghai&amp;#39;d again tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:29:24 </td>
   <td style="text-align:left;"> $AMZN $GOOGL $TSLA $GME $SPY

All the big boys doing stock splits before the big market crash?? 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:28:08 </td>
   <td style="text-align:left;"> $TSLA https://247wallst.com/autos/2022/03/30/tesla-thrives-as-gm-collapses/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:28:01 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $AMZN $TSLA  https://www.cnbc.com/2022/03/31/2-year-treasury-yield-tops-10-year-rate-a-yield-curve-inversion-that-could-signal-a-recession.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:27:43 </td>
   <td style="text-align:left;"> With Tesla Localizing EV Production, This Analyst Says Musk’s Brand Is Becoming A Renewable Energy Play https://www.billionaireclubcollc.com/with-tesla-localizing-ev-production-this-analyst-says-musks-brand-is-becoming-a-renewable-energy-play/  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:26:23 </td>
   <td style="text-align:left;"> $TSLA 320,000 deliveries or greater will be reported Saturday , you heard it here folks ✌️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:26:00 </td>
   <td style="text-align:left;"> $FUBO 811.27k after hours volume...more than $PYPL $TSLA $DIDI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:25:48 </td>
   <td style="text-align:left;"> $TSLA Looks like it might swing between 1050 to 1100. Tomorrow is money making day if you time it right </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:24:09 </td>
   <td style="text-align:left;"> $DIS looking to sink some money in something for spring? #1 sporting goods retailer by Oppenheimer. 

Academy Sports and Outdoors $AAPL $WMT $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:23:49 </td>
   <td style="text-align:left;"> What GameStop Investors Should Know About The Stock Split Plan  $GME $TSLA $AMZN $GOOG $GOOGL 

https://newsfilter.io/a/104959cdc41809ce34e76e7272e45160 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:23:21 </td>
   <td style="text-align:left;"> #GME Soars 20% After Announcing Stock Split $GME Also $AMZN $TSLA $AMC https://talkmarkets.com/content/stocks--equities/gme-soars-20-after-announcing-stock-split?post=349944 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:21:28 </td>
   <td style="text-align:left;"> $AMC for those who dont understand shorting of hedges  
$GME  $ARKK $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:21:22 </td>
   <td style="text-align:left;"> $TSLA Elon Musk says he plans to send 1 million people to Mars by 2050 by launching 3 Starship rockets every day and creating &amp;#39;a lot of jobs&amp;#39; on the red planet !! 🤣 You ignorant gullible Musketeers. Self Driving Vehicles by 2017! 🤣 Dancing man in a body suit 🤣  Musk the greatest act since L Ron Hubbard and Jim Bakker of PTL Club. Hilarious. His Cult of teenaged brained fans worship him. He’s a real life comic book hero! It’s The Future, Bro 🤡 https://www.businessinsider.com/elon-musk-plans-1-million-people-to-mars-by-2050-2020-1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:19:44 </td>
   <td style="text-align:left;"> $TSLA So you guys still like paying more for a pizza cut in 8 slices , instead of 6? Cool </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:19:24 </td>
   <td style="text-align:left;"> $QS go watch this and then try to tell me buying Qs isn’t like buying $TSLA at $20

https://m.youtube.com/watch?v=hkY4SAX3yaA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:16:09 </td>
   <td style="text-align:left;"> $MULN many stock analysts are of the opinion that shorts here are playing with fire and that a short squeeze could happen at any moment. Strong balance sheet (65million$ of net cash), impressive catalysts (selling of electric vans to Fortune500 company), high growth hot sector (EVs). Government support and subisidies incoming, sexy desirable roducts (Mullen 5...)...you have to be a moron or an idiot to fully short a company like. This is a question of when not of if this short squeeze. We could witness here a $GME or $AMC or $NIO or $TSLA 2.0 scenario. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:15:51 </td>
   <td style="text-align:left;"> $TSLA maximum pain $1045 tomorrow let&amp;#39;s see what happens </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:15:05 </td>
   <td style="text-align:left;"> $TSLA LOTTO. BOUGHT APR 14 $1200 call and sold 125Rcall and paid $3.15. SL 1.5. Worth the risk. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:15:01 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL #throwbackThursday to happier times! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:14:40 </td>
   <td style="text-align:left;"> $TSLA I wanna buy but hopefully under $1,000 or $1010 for the April Fools sale </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:14:19 </td>
   <td style="text-align:left;"> $AMZN $AAPL $TSLA $SPY $MSFT stronger ones </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:14:19 </td>
   <td style="text-align:left;"> $TSLA short term view, i do think tesla will test la (lol had to) 1200 level before falling and honestly i don&amp;#39;t trust anything but for the next few weeks or so i&amp;#39;m doing some DCA as my cost is around 800 currently, i&amp;#39;ll buy more on dips and use trailing stops in the high 1100s on 75% of my position https://www.tradingview.com/x/n1fboC9h/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:13:23 </td>
   <td style="text-align:left;"> $TSLA top of mountain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:13:03 </td>
   <td style="text-align:left;"> $TSLA $1150 tomorrow based on the massive bull flag and the Massive Amount of people who bought puts omg 🤣✅🤣✅✅🤣✅🎉💰🎉💰💰💰💰💰💰💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:12:45 </td>
   <td style="text-align:left;"> $TSLA - When are they opening giga factory in Texas ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:11:45 </td>
   <td style="text-align:left;"> $TSLA c’mon,let’s fill that 1021.80 gap and move on! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:10:41 </td>
   <td style="text-align:left;"> $TSLA so the whole market entering a downtrend,  and this is going to ATH? ....okkkk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:09:22 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL a lot of you don&amp;#39;t know the money printer origin story and that is sad. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:08:24 </td>
   <td style="text-align:left;"> $GM   So GM is using a Tesla Model 3 to see how the Summon Feature works….. that figures.  What a bunch of loser hypocrites… $GM.   Here is another really good tip from $TSLA that GM can copy….. get rid of the union.

https://www.zerohedge.com/technology/pictures-reveal-gm-benchmarking-tesla-summons-feature-model-3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:08:17 </td>
   <td style="text-align:left;"> $TSLA $Gme remember when everyone is trying to make ev cars. Now everyone tryna do stock splits. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:08:11 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Are Bearish Mulders dreams coming true? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:08:07 </td>
   <td style="text-align:left;"> $TSLA  Tesla Q1 Production Blowout will humiliate analysts 
https://youtu.be/uys71W3tknU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:07:58 </td>
   <td style="text-align:left;"> $GME Member $TSLA split ? This is the same. 
Ten times. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:07:54 </td>
   <td style="text-align:left;"> $TSLA 🤣🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:06:45 </td>
   <td style="text-align:left;"> $GME RC goes after pappa Musk $TSLA . Shorts are fuked so hard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:05:02 </td>
   <td style="text-align:left;"> $TSLA Let&amp;#39;s keep doing this until it comes down to earth folks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:03:45 </td>
   <td style="text-align:left;"> $TSLA if you think there is any chance this goes up tomorrow, you are nutso. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:02:47 </td>
   <td style="text-align:left;"> $TSLA 

Tesla is NOT a meme stock! 

Why some include it with GME, AMC, etc? 

SMH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:01:31 </td>
   <td style="text-align:left;"> With Tesla Localizing EV Production, This Analyst Says Musk&amp;#39;s Brand Is Becoming A Renewable Energy Play $TSLA $APTV $AXL https://www.benzinga.com/analyst-ratings/analyst-color/22/03/26399276/with-tesla-localizing-ev-production-this-analyst-says-musks-brand-is-becoming-a-ren#.YkYWnw0yTog.twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:00:30 </td>
   <td style="text-align:left;"> $GME $AMC Stock splits are meaningless, but GME is a stock in an alternate universe 
 
when a big deal company splits like $AAPL or $TSLA we all know it does not have an effect, but like magic it rises the price. 
 
Gamestop will increase and AMC will get a good kick in the ass, but splitting will not cause the finding or counting of “synthetic “ shares. 
 
We are in a place that does not exist, enjoy the ride, it will be bumpy from here  
 
this GME split may just start the AMC run to new highs, 
 
s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:00:12 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-03-31 Chart Analysis Video: 
https://www.youtube.com/watch?v=lofGaydy9SE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 05:00:07 </td>
   <td style="text-align:left;"> $gme is ripping.
$tsla  $btc.x $appl $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:59:56 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $MSFT $AMZN 
Bulls had 11 bulls days. 
We&amp;#39;re just having 2 bear days.
Way to go 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:59:48 </td>
   <td style="text-align:left;"> $TSLA We need a repeat of this tomorrow folks, those puts need to get fatter ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:58:40 </td>
   <td style="text-align:left;"> $TSLA  Some are highly underestimating this company...and a 50 year old man that has been paying attention to all the worlds&amp;#39; problems his entire life , and has thought about how to make it better , his entire life . 

Eat your heart out , legacy auto makers . This is efficiency at a completely mindblowing level !

https://youtu.be/IO5XC1x27gg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:57:37 </td>
   <td style="text-align:left;"> $TSLA well 1050 torromorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:54:44 </td>
   <td style="text-align:left;"> $TSLA with the gas price surge, everyone spent the last month ordering teslas . I see more teslas on the road than some well know car companies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:54:23 </td>
   <td style="text-align:left;"> $TSLA my number 1 stock! Bought the last stock split  back in 2019/20 I believe. 8k+ profit. Almost sold when fear was at its peak! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:53:21 </td>
   <td style="text-align:left;"> $TSLA $SPY $AAPL $MSFT $AMZN 
High Five to  Bears 👋
Great team work 👏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:52:27 </td>
   <td style="text-align:left;"> $SPY $TSLA $AMZN $GME 

2022 the year of stock splits 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:52:22 </td>
   <td style="text-align:left;"> $TSLA imagine everyone is wrong and BOOM 1150 tomorrow 🤣✅🤣✅🎈🎉👍💰💪🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:52:16 </td>
   <td style="text-align:left;"> $FSR  $AAPL $TSLA 
https://seekingalpha.com/amp/news/3801868-fisker-is-still-a-buy-at-morgan-stanley-despite-slower-production-ramp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:51:22 </td>
   <td style="text-align:left;"> $SPY expect more bad news coming out of China shutdown. $400 soon lol 😂  $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:50:00 </td>
   <td style="text-align:left;"> $TSLA beat these corporate types send this to 700 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:49:23 </td>
   <td style="text-align:left;"> $TSLA will close around $1100 tomorrow going into the huge weekend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:49:22 </td>
   <td style="text-align:left;"> $TSLA Should the gap fill, 5% drop from current level.  buy orders at 1020 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:48:57 </td>
   <td style="text-align:left;"> $WWR $tsla $blbx $amd
“This plant not only will make Alabama the U.S. leader in graphite production, the go-to place for this important resource in battery manufacturing, it also will elevate our standing even more as a major player in the fast-growing electric vehicle sector,” Governor Kay Ivey said </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:47:47 </td>
   <td style="text-align:left;"> $TSLA The reason Tesla beat Q4 deliveries so bad is because idiot analysts predicted 263,000 cars and they delivered 308,600.  
With Shanghai closed for 6 days, I would be shocked they can beat estimates to an amount that much given analysts got there shit together. Playing with fire holding into this announcement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:47:22 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Follow Wall Street and Buy TSLA Stock to Bet on National Security https://www.stck.pro/news/TSLA/25389698 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:45:50 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

did elon tweet something?... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:44:49 </td>
   <td style="text-align:left;"> $TSLA reportedly pausing solar roof installations due to supply issues </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:44:42 </td>
   <td style="text-align:left;"> $TSLA I’ll be happy she drop to 1050 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:43:39 </td>
   <td style="text-align:left;"> $TSLA $1200 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:43:24 </td>
   <td style="text-align:left;"> $GME I am still spending money from the $TSLA stock split. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:43:22 </td>
   <td style="text-align:left;"> Follow Wall Street and Buy $TSLA Stock to Bet on National Security 
 
https://investorplace.com/2022/03/follow-wall-street-and-buy-tsla-stock-to-bet-on-national-security/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:43:18 </td>
   <td style="text-align:left;"> $TSLA Looks kinda toppy on the 4 hr MACD.  
GLTA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:42:26 </td>
   <td style="text-align:left;"> $TSLA #TLRY #GME 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:41:41 </td>
   <td style="text-align:left;"> $TSLA first actual red day in like 2 1/2 weeks lol and it’s only down 1.5% 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:41:36 </td>
   <td style="text-align:left;"> $TSLA sell it and buy $GME 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:41:09 </td>
   <td style="text-align:left;"> $GME $TSLA Funds have suggested the stock split after these companies robbed funds for growth.  Once the stock splits are done there will be more short shares available to short the stock. However retail never learns </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:40:47 </td>
   <td style="text-align:left;"> $TSLA $XPEV $NIO $SPY 
Down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:40:14 </td>
   <td style="text-align:left;"> $TSLA last 4th Q delivery beat went from 1050 to 1200. Holding calls till next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:39:57 </td>
   <td style="text-align:left;"> $AMZN $TSLA $GME Stock splits are always a bearish indicator. Haven’t figured out why people rush to buy during that announcement besides the fact that they know dumb money so going to rush and buy and it’s to simply take advantage of the stock increase. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:39:37 </td>
   <td style="text-align:left;"> $TSLA and so it begins </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:39:17 </td>
   <td style="text-align:left;"> $TSLA turning bearish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:38:38 </td>
   <td style="text-align:left;"> $TSLA Option Alert.. High Volume Options... 👀 👀  $1100 Call for Friday, April 1, 2022. Roughly 26 Million dollars! 💰💰💰 MASSIVE MONEY 💰💰💰 Learn more on StockOrbit! Link on profile!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:38:16 </td>
   <td style="text-align:left;"> $TSLA RSI has turned over on the daily. But Stochastic RSI is still alive on the daily. The run may not be over yet. Both indicators need to turn over before bulls should panic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:38:07 </td>
   <td style="text-align:left;"> $TSLA what are the odds of the delivery numbers coming out tonight or before market open tomorrow vs the projected weekend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:38:05 </td>
   <td style="text-align:left;"> $TSLA The market took a big turd at close.  Bears need that. Bulls getting too cocky </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:38:04 </td>
   <td style="text-align:left;"> $SPY $TSLA Who knows what a double penetrating unkept Harold is? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:37:14 </td>
   <td style="text-align:left;"> $TSLA WOW LOOK AT GME, STOCK SPLIT GO CRAZY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:37:06 </td>
   <td style="text-align:left;"> $QS stock is about to double 
Price target $TSLA $AMC $GME $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:37:04 </td>
   <td style="text-align:left;"> $GME 👀 stock split  
 
$SPY $TSLA $AMC $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:36:03 </td>
   <td style="text-align:left;"> $GME what?! Share price under 200, yet let&amp;#39;s split it to pump. $TSLA started this, it&amp;#39;s not even funny anymore $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:35:04 </td>
   <td style="text-align:left;"> $TLRY    bye bye bears, squeeze of the century coming tomorrow - get this trending !!!  AND SET YOUR SELL LIMITS TO $100 UNTIL APRIL 20TH (420)   $AMC  $GME $TSLA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:34:33 </td>
   <td style="text-align:left;"> $TSLA time to load the dip at that $1,078.82, if it holds 1,078.00, then it will probably have a small bounce off that support at $1,077.51 to maybe $1,300-1,400 area; since they will likely beat that 220,000 cars sold forecast and in general shouldn&amp;#39;t be valued as a car company, it should reach $2,500-2,600 by April 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:34:31 </td>
   <td style="text-align:left;"> $HYMC 
$TSLA …we are running AH!!🏃‍♀️🏃‍♀️🏃‍♀️🏃‍♀️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:33:43 </td>
   <td style="text-align:left;"> $TSLA 

bearanos has entered the chat... 💬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:33:03 </td>
   <td style="text-align:left;"> $TSLA this is heading back to the 50 sma around 900. That was a filthy short squeeze the last few weeks. There&amp;#39;s nobody left to cover now so down it goes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:32:33 </td>
   <td style="text-align:left;"> $TSLA Quick sell-off was end of quarter rebalancing for SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:32:28 </td>
   <td style="text-align:left;"> $TSLA too many puts today, bear rug pull coming to a forest 🌳 near you. 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:31:41 </td>
   <td style="text-align:left;"> $GME Cohen and Musk must be bros. Burning Gary and Kenny $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:31:36 </td>
   <td style="text-align:left;"> $TSLA  BREAKING! Tesla Giga Berlin Produces 1 Model Y Every 150 Seconds 
A video, released hours ago, shows that Tesla Giga Berlin is producing Model Y electric vehicles every 150 seconds. This translates into 1000 vehicles a week at Giga Berlin.  
 
https://youtu.be/3My774ArWIY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:30:22 </td>
   <td style="text-align:left;"> $TSLA call for next week!! Monday opening over 1105 
Mark it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:30:01 </td>
   <td style="text-align:left;"> $SPY $TSLA i will be here carrying on with my training. Stay calm and DD on :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:29:46 </td>
   <td style="text-align:left;"> $TSLA imagine those delivery numbers tomorrow… uh oh bears ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:29:26 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA Gotta love those end of day MM pussy sell offs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:29:05 </td>
   <td style="text-align:left;"> $SPY $TSLA latex467d5543cf6566e141363bb5acbc2b40TSLA 879k (57% call/43% put)
$AMC 878k (68% call/32% put) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:28:27 </td>
   <td style="text-align:left;"> $TSLA just want the dip before the rip✅🤝💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:28:22 </td>
   <td style="text-align:left;"> $TSLA 

Up
It
Goes 🚀🏁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:27:57 </td>
   <td style="text-align:left;"> $TSLA this $1025 manàna </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:27:44 </td>
   <td style="text-align:left;"> $TSLA that was a bearish end.. max volume on sell... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:27:40 </td>
   <td style="text-align:left;"> $TSLA lol bears out in full force🤣 doing the happy dance!!! It did close bearish see how we open… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:27:05 </td>
   <td style="text-align:left;"> $TSLA holding calls for next week. Not selling until Tuesday. 🤞hoping this rebounds to 1100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:26:25 </td>
   <td style="text-align:left;"> $TSLA Break $1064 FILLS Gap And my Pockets with 💰💰💰💰💰❗️❗️❗️❗️❗️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:26:22 </td>
   <td style="text-align:left;"> $TSLA has Elron announced another stock split yet? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:24:45 </td>
   <td style="text-align:left;"> $TSLA Bearish close. Short term okay—consolidation healthy after that insane run. 

I think flat to down heading into Friday &amp;amp; delivery report. Then next week we see either 1000 or test 1200 and sell off. Consolidate for a few weeks into earnings or official split announcement (early May?). Then moon. JM2C </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:24:06 </td>
   <td style="text-align:left;"> $TSLA there&amp;#39;s still time for 1500 by the end of the week 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:23:38 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $BABA $JD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:23:19 </td>
   <td style="text-align:left;"> $TSLA not included 🤷‍♀️ TIME100 Most Influential Companies 2022 | TIME https://time.com/collection/time100-companies-2022/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:22:58 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:22:45 </td>
   <td style="text-align:left;"> $TSLA Elon sold top ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:22:44 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-04-01 04:21:46 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
</tbody>
</table></div>

---
