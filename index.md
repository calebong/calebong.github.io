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



Last Updated: 2022-02-04 10:40:03 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/philippines/food-inflation </td>
   <td style="text-align:left;"> 2022-02-04 10:18:25 </td>
   <td style="text-align:left;"> Philippines Food Inflation Unchanged </td>
   <td style="text-align:left;"> Food prices in the Philippines increased by 1.6 percent year-on-year in January 2022, the same pace as in the previous month. Those figures used 2018 as the base year. Inflation was unchanged for fish (at 6.2%), while cost rose for rice (1 percent vs -0.1 percent), corn (27.7 percent vs 16.5 percent), milk, cheese, egg (0.9 percent vs 0.7 percent), meat (4.3 percent vs 8.7 percent), flour, bread and other bakery products, pasta products, and other cereals (2.7 percent vs 2.4 percent), oils and fats (8.5 percent vs 8 percent), sugar, jam, honey, chocolate &amp; confectionery (2.8 percent vs 2.1 percent), and ready-made food and other food products, N.E.C (1.9 percent vs 1.3 percent). In contrast, prices dropped further vegetables (-10.9 percent vs -15.1 percent), and fruits (-5.7 percent vs -3.7 percent).
; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/romania/retail-sales-annual </td>
   <td style="text-align:left;"> 2022-02-04 10:04:58 </td>
   <td style="text-align:left;"> Romanian Retail Sales Rise the Most in 3 Months </td>
   <td style="text-align:left;"> Retail sales in Romania advanced by 7.0 percent in December of 2021 over the same month in the previous year, after an upwardly revised 6.2 percent gain in the previous month. It was the tenth straight month of increase in retail trade, and the strongest in three months, as sales of both non-food products (7.8 percent vs 2.6 percent in November) and food, beverages, and tobacco (4.7 percent vs 4.2 percent) grew faster. Meanwhile, sales of automotive fuel increased softer (7.4 percent vs 13.1 percent). On a monthly basis, retail sales went up 0.9 percent in December, easing from an upwardly revised 1.1 percent gain in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/stock-market </td>
   <td style="text-align:left;"> 2022-02-04 09:54:21 </td>
   <td style="text-align:left;"> Australian Shares Muted, Set for Weekly Gain </td>
   <td style="text-align:left;"> The S&amp;P/ASX 200 Index was little changed around 7,080 on Friday and was on track to gain more than 1% this week, as investors welcomed the central bank’s decision to push back on market bets for an early rate hike. The Reserve Bank of Australia decided on Tuesday to keep rates at 0.1% and called an end to its bond buying program, as widely expected, but governor Philip Lowe reiterated that the bank will stay patient on moving policy. Investor sentiment has been swinging between concerns over policy tightening by the U.S. Federal Reserve and other central banks and confidence in the global economic recovery. Internal components of the Australian market traded mixed on Friday, with gains from Westpac (1.5%), Macquarie (1.2%), Brainchip (5.3%), Woodside Petroleum (0.3%) and South32 (1.3%). Meanwhile, the market laggards include BHP Group (-1%), ANZ Bank (-1.1%), Novonix (-1.2%), Pilbara Minerals (-1.8%) and Mineral Resources (-2%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-04 09:29:00 </td>
   <td style="text-align:left;"> South Korea 10Y Bond Yield Hits 3-1/2-year High </td>
   <td style="text-align:left;"> South Korea 10 Year Government Bond Yield increased to a 3-1/2-year high of 2.642%, tracking the yield on benchmark 10- and five-year year Japanese governments bond. Yield 10-and five-year Japanese government bonds rose to a six-year high on Friday, amid global inflationary pressures.  Investors also weighed new data about January inflation. South Korea's consumer inflation for January hovered near a decade-high on surging and food prices, boosting the case for more interest rate hikes in 2022. January consumer prices jumped 3.6% year-on-year, beating market expectations of a 3.3% rise, and above the central bank's 2% target for a 10th straight month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/philippines/inflation-cpi </td>
   <td style="text-align:left;"> 2022-02-04 09:21:00 </td>
   <td style="text-align:left;"> Philippines January Inflation Rate Slightly Below Forecasts </td>
   <td style="text-align:left;"> The annual inflation rate in the Philippines fell to 3.0% in January 2022 from 3.2% in the prior month and compared with market consensus of 3.1%. Those figures used 2018 as the base year. Prices slowed for housing (4.5% vs 5.1% in December), alcoholic beverages &amp; tobacco (5.6% vs 6.2%), health (3.1% vs 3.2%), recreation (1.5% vs 1.6%), restaurant &amp; accommodation (3% vs 3.2%), and education (0.6% vs 0.7%). Meantime, inflation was unchanged for both food &amp; non-alcoholic beverages (at 1.6%) and financial services (43.3% vs 43.3%) while cost rose faster for transport (7.0% vs 6.6%), clothing (2% vs 1.9%), furnishing and household maintenance (2.4% vs 2.1%), communication (0.7% vs 0.6%) , and personal care, miscellaneous (2.2% vs 2.1%). On a monthly basis, consumer prices rose 1.0%, after a 0.4% rise in December, exceeding estimates of 0.4%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-04/gold-heads-for-weekly-gain-as-stocks-drop-before-u-s-jobs-data?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-04 09:17:07 </td>
   <td style="text-align:left;"> Gold Heads for Weekly Gain as Stocks Drop Before U.S. Jobs Data </td>
   <td style="text-align:left;"> Ranjeetha Pakiam                                                                                                                                                                                                                                                                                        , Gold headed for a weekly advance as U.S. equities fell after Meta Platforms Inc. suffered a historic share-price rout, while investors awaited a key jobs report for more clues on the Federal Reserve’s monetary policy path.                                                                          , The Facebook parent plunged 26% Thursday on the back of woeful earnings results, erasing about $251 billion in market value in the biggest one-day wipeout for any U.S. company. Concerns over tightening monetary policy also contributed to the worst slide for American technology shares since 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/interest-rate </td>
   <td style="text-align:left;"> 2022-02-04 09:03:00 </td>
   <td style="text-align:left;"> RBA to Stay Patient Before Lifting Rates: Policy Statement </td>
   <td style="text-align:left;"> Ceasing purchases under the bond purchase program does not imply a near-term increase in interest rates, nor does it represent a tightening of monetary policy, the Reserve Bank of Australia reiterated in its monetary policy statement. The committee judged that it is too early to conclude that inflation is sustainably within the 2 to 3% target range. "The board is prepared to be patient as it monitors how the various factors affecting inflation in Australia evolve. It will do what is necessary to maintain low and stable inflation, which is important not only in its own right but also as a precondition for a sustained period of full employment." Regarding the effect of the Omicron, it is expected to drag on growth in economic activity during early 2022 with household spending is forecast to be lower. On prices,  underlying inflation is forecast to increase to 3.75% by mid-2022 before easing as international and domestic supply chain pressures subside. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-04/tiger-global-raises-11-billion-for-latest-private-fund?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-04 09:02:29 </td>
   <td style="text-align:left;"> Tiger Global Raises $11 Billion for Latest Private Fund </td>
   <td style="text-align:left;"> Hema Parmar                                                                                                                                                                                                   , Tiger Global Management has raised more than $11 billion for its latest venture capital fund, and is targeting another billion dollars before its March close.                                                , The Private Investment Partners 15 fund -- known as PIP 15 -- is on track to close with $12 billion, according to a person familiar with the matter, exceeding the initial fundraising target of $10 billion.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/wool </td>
   <td style="text-align:left;"> 2022-02-04 09:00:13 </td>
   <td style="text-align:left;"> Wool Hits 31-week High </td>
   <td style="text-align:left;"> Wool increased to a 31-week high of 1449 AUD/100Kg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-04 08:59:35 </td>
   <td style="text-align:left;"> US Futures Jump on Amazon, Snap Earnings </td>
   <td style="text-align:left;"> US equity futures jumped on Friday as investors cheered blowout earnings from several technology stocks, after the Nasdaq posted its worst day in more than a year. Dow futures gained 0.5%, while S&amp;P 500 and Nasdaq 100 futures rallied 1% and 1.8%, respectively. Amazon shares surged 14% in after-hours trading following a strong quarterly report, helped by its investment in Rivian and growth in its main businesses. Snap also rocketed 58% after reporting its first-ever quarterly net profit, along with Pinterest which jumped 20% on an earnings beat. The moves came after Meta Platforms dropped 26% following a disappointing earnings report, dragging the market lower. The Nasdaq led the declines in regular trading on Thursday, falling 3.74% for its worst day since September 2020, followed by the S&amp;P 500 (-2.44%) and the Dow (-1.45%). Meanwhile, investors await the highly-anticipated nonfarm payroll due Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/03/technology/air-force-clearview-ai-glasses.html </td>
   <td style="text-align:left;"> 2022-02-04 08:41:14 </td>
   <td style="text-align:left;"> Air Force Taps Clearview AI to Research Face-Identifying A.R. Glasses - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                       , In a flyer, Clearview said the product “saves lives,” “saves time” and “improves health” by increasing social distancing and keeping officers’ hands free to grab their weapons.                                                                                                                                                                                                                                    , By Kashmir Hill                                                                                                                                                                                                                                                                                                                                                                                                     , The U.S. Air Force is looking into keeping its airfields safer with help from the facial recognition start-up Clearview AI.                                                                                                                                                                                                                                                                                         , The Air Force Research Laboratory awarded Clearview $49,847 to research augmented reality glasses that could scan people’s faces to help with security on bases.                                                                                                                                                                                                                                                    , Brian Ripple, a spokesman for the lab, described the work as a three-month study to figure out the “scientific and technical merit and feasibility” of using such glasses for face recognition.                                                                                                                                                                                                                     , “No glasses or units are being delivered under this contract,” Mr. Ripple said on Thursday.                                                                                                                                                                                                                                                                                                                         , In other words, the lab is paying for the glasses to be developed, but it isn’t buying them yet. Mr. Ripple provided “a one-page overview from the company,” titled, “Clearview AI: Augmented Reality Glasses To Secure Bases and Flightlines.” The flyer said the product “saves lives,” “saves time” and “improves health” by increasing social distancing and keeping officers’ hands free to grab their weapons., New York-based Clearview AI has been the target of international investigations and lawsuits because it scraped billions of photos from the public internet to build a facial recognition tool used by law enforcement. Hundreds of federal agencies and local police departments have employed Clearview’s technology.                                                                                             , The company describes its software as ideal for investigations that take place after a crime has been committed and not for surveillance, but it has experimented with real-time facial recognition.                                                                                                                                                                                                                , In January 2020, a technologist at The Times found code in the company’s app that showed it could be paired with augmented reality glasses. At the time, Hoan Ton-That, the chief executive of Clearview AI, acknowledged designing a prototype but said the company had no plans to release it.                                                                                                                    , “We continually research and develop new technologies, processes and platforms to meet current and future security challenges, and look forward to any opportunities that would bring us together with the Air Force in that realm,” Mr. Ton-That said in a statement after the contract became public. “Once realized, we believe this technology will be an excellent fit for numerous security situations.”      , Last month, Mr. Ton-That said in a public letter that his company would not use its technology “in a real-time way,” but outfitting glasses with the technology to recognize faces seems to fit that bill.                                                                                                                                                                                                          , In a phone call, Mr. Ton-That said Clearview’s database of 10 billion photos “won’t be used for any real-time surveillance” and that any augmented reality glasses would rely instead on “limited data sets — for example, outstanding warrants, missing children or persons of interest.”                                                                                                                          , The Air Force contract was signed in November, but only became public on Thursday. It was first highlighted on Twitter by Jack Poulson, the executive director of Tech Inquiry, a nonprofit that monitors government procurement of surveillance technology.                                                                                                                                                        , The Air Force previously awarded Clearview AI $50,000 in December 2019 for research and development. BuzzFeed News previously reported that the Air Force was one of many divisions within federal agencies that had performed trials with the company’s facial recognition software.                                                                                                                               , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/world-asia-india-60194920?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-04 08:20:03 </td>
   <td style="text-align:left;"> Koo: India's Twitter alternative with global ambitions </td>
   <td style="text-align:left;"> Can Indian microblogging app Koo beat Twitter?                                                                                                                                                                                                                                                           , That's certainly the goal, according to co-founder Mayank Bidawatka, who says Koo expects to surpass Twitter's 25 million-strong user base in India this year.                                                                                                                                           , It had touched 20 million downloads in India by the end of 2021.                                                                                                                                                                                                                                         , "We are now available in 10 languages, including English. This year we'd like to cover all of India's 22 official languages," he told the BBC at the company's headquarters in the southern city of Bangalore, a tech hub.                                                                               , Koo was thrust into the spotlight last year as an alternative to Twitter amid a row between the Indian government and the US microblogging platform.                                                                                                                                                     , Prime Minister Narendra Modi's government asked the platform to block allegedly incendiary accounts - Twitter complied initially and then restored them, citing "insufficient justification". The face-off continued as the government threatened legal action against the company's employees in India. , This was in addition to an ongoing dispute over new digital rules that sparked concerns about free speech and privacy. WhatsApp sued the government, saying the rules would force it to violate privacy protections.                                                                                     , Irked by Twitter's defiance and alleged failure to comply with digital rules, a flurry of cabinet ministers and lawmakers from Mr Modi's Bharatiya Janata Party (BJP) migrated to Koo overnight. Mr Modi, who has a huge following on Twitter, has stayed put.                                           , Koo, which caters primarily to non-English users in India, launched in early 2020. It expanded to Nigeria in 2021 when the country suspended Twitter. It now wants to reach 100 million users by the end of 2022.                                                                                        , Mr Bidawatka founded Koo along with Aparmeya Radhakrishna, an angel investor and entrepreneur whose ride-sharing business TaxiForSure was acquired by the Indian company Ola for $200m (£147m) in 2015. The two also run Vokal, a knowledge-sharing platform in Indian languages.                        , Since last year, Koo has attracted cricketers and Bollywood stars - and it expects the number of "eminent accounts", which now number 5,000, to triple by the end of the year.                                                                                                                           , But it's also accused of amplifying government propaganda and letting anti-Muslim hate speech go unchecked.                                                                                                                                                                                              , Social media has become yet another battleground in a sharply polarised India - and the supporters of the Hindu nationalist BJP have long been accused of relentlessly trolling those who are seen as critical or opposed to Mr Modi.                                                                    , Koo's guidelines explicitly prohibit hate speech and discriminatory or offensive content. But with "koos" (its version of tweets) being generated every second, moderation is hard, as is the case on other social media platforms, including Twitter.                                                   , Mr Bidawatka says the problem needs to be solved using technology rather than human moderators, and by involving the user community to flag posts they deem toxic.                                                                                                                                       , He says that there are "a lot of BJP folk" on Koo, but disagrees that it's an echo chamber of right-leaning, anti-liberal voices. He adds that the app hosts opposition leaders from 19 other parties, including state chief ministers from the main opposition Congress party.                          , "There will always be some early adoptors. But how you start, and what happens in the beginning should not define your entire journey," Mr Bidawatka said. "As entrepreneurs, there is no reason for us to create something that only a section of the population will use."                             , But according to Nikhil Pahwa, a digital rights activist, there is a clear rationale for Mr Modi's government to promote Koo as a homegrown, even "nationalist" alternative to Twitter, so that it can create a "soft landing spot" for itself, in case the need to ban Twitter arises in the future.    , Much like the Chinese "splinternet", where the state controls cyberspace, India has, over the years, been pushing for greater digital sovereignty and control of its internet, Mr Pahwa says.                                                                                                            , These wider trends "will provide further tailwinds to Indian-owned platforms (like Koo)," he adds.                                                                                                                                                                                                       , He also notes that global big tech, governed by policies around data and security "will find it increasingly difficult to grow in India".                                                                                                                                                                , Koo has a fair shot at success, he believes, if it can solve the issue of how best to moderate content, while creating a safe space for users, which Twitter has long struggled with.                                                                                                                    , But it will need to make a more concerted effort to attract users with a diversity of political views. As of now, liberal or anti-establishment voices might be disinclined to leave Twitter or have an account on both platforms.                                                                       , The app's requirement for authentication via a mobile phone number to register will also pose a challenge, Mr Pahwa says, because while it would allow Koo to moderate content better, it "takes away the comfort of anonymity" that Twitter grants to its users.                                        , Still, Koo's distinctive focus on building a product for non-English speakers makes it a compelling product.                                                                                                                                                                                             , Over the last few months the company has experimented a lot, such as giving people the ability to 'koo' in multiple languages at once, and on one screen.                                                                                                                                                , Mr Bidawatka says Bollywood actors - who usually communicate with their fans in English on social media - make use of this feature to reach wider audiences across multiple languages.                                                                                                                   , Koo currently competes with ShareChat in India, a far bigger rival in terms of its user base. As it scales up across Indian languages, it will be doubling its headcount to 500 people.                                                                                                                  , Buoyed by the platform's success in Nigeria, Mr Bidawatka plans to take the platform to countries outside India where English is not the dominant language.                                                                                                                                              , "South East Asia is exciting because of the large population and under-penetration of existing platforms. That's definitely on the cards," Mr Bidawatka says.                                                                                                                                            , "English is spoken by only 20% of the world - 80% of the world does not speak English," he adds. "That  entire market is open to us."                                                                                                                                                                    , This video can not be played                                                                                                                                                                                                                                                                             , When Ruby Wax met Pamela Anderson...                                                                                                                                                                                                                                                                     , Russell Kane and guests explore the life of Queen Elizabeth I...                                                                                                                                                                                                                                         , The story of the Holocaust through the eyes of remarkable 106-year-old Boris Pahor                                                                                                                                                                                                                       , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-04/u-s-cements-lng-export-crown-as-venture-global-fires-up-plant?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-04 08:17:32 </td>
   <td style="text-align:left;"> U.S. Cements LNG Export Crown as Venture Global Fires Up Plant </td>
   <td style="text-align:left;"> Sergio Chapa                                                                                                                                                                                                                                                                                                                      , Venture Global LNG began producing liquefied natural gas at its Calcasieu Pass plant in Louisiana, solidifying the U.S.’s position as the world’s top producer of the superchilled fuel.                                                                                                                                          , The $5.8 billion export facility began making LNG on Jan. 19, according to a Thursday filing with the Federal Energy Regulatory Commission. When it starts commercial service in mid-2022, the U.S. will have the capacity to ship as much as 13.9 billion cubic feet of LNG per day, more than top producers Australia and Qatar. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/inflation-cpi </td>
   <td style="text-align:left;"> 2022-02-04 07:38:11 </td>
   <td style="text-align:left;"> South Korea Inflation Remains Above Expectations </td>
   <td style="text-align:left;"> Consumer prices in South Korea rose 3.6% in January 2022 from a year earlier, slowing from a 3.7% gain in the previous month but posted higher than market expectations for a 3.3% increase. The latest figure remained close to a decade-high of 3.8% registered in November 2021 as higher prices of oil and other raw materials, as well as agricultural goods kept adding to inflationary pressure. South Korea’s inflation also held above 3% since October, well in excess of the central bank’s 2% target, keeping the pressure on the Bank of Korea despite having raised interest rates three times since August to 1.25%. The BOK holds its next rate decision on Feb. 24. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-03/roaring-oil-market-heads-for-seventh-weekly-gain-as-wti-tops-90?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-04 07:37:12 </td>
   <td style="text-align:left;"> Roaring Oil Market Heads for Seventh Weekly Gain as WTI Tops $90 </td>
   <td style="text-align:left;"> Elizabeth Low                                                                                                                                                                                                                     , Oil headed for a seventh weekly gain as investors fret over a fast-tightening market, geopolitical tensions and freezing weather in the U.S.                                                                                      , West Texas Intermediate hit a fresh seven-year high near $91 a barrel, set for a jump of more than 4% this week. Brent has surged 18% since the year began and banks including Goldman Sachs Group Inc. forecast it’ll reach $100. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-03/amazon-adds-to-a-huge-faang-season-with-meta-mauling-an-outlier?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-04 07:35:23 </td>
   <td style="text-align:left;"> Amazon Adds to a Huge Season for Faangs, While Meta’s Meltdown Is the Outlier </td>
   <td style="text-align:left;"> Lu Wang                                                                                                                                                                                                                                                                                                                                                                                                             ,  and Vildana Hajric                                                                                                                                                                                                                                                                                                                                                                                                 , Yes the market got shanked Thursday, and yes Mark Zuckerberg just saw his personal wealth reduced by an amount roughly equal to Consolidated Edison. But none of it amounted to a repudiation of risk-taking at the peak of earnings season.                                                                                                                                                                        , Quite the opposite. For all the ink spilled as the former Facebook fell Thursday, moves in equity volatility indexes -- proxies for investor nerves -- were relatively contained, particularly compared with past blowups. Gains in the price of bearish options on the biggest tech ETF were similarly muted -- a sign that bulls kept their cool and had purchased hedges before the Meta Platforms Inc. massacre. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60252907?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-04 07:04:57 </td>
   <td style="text-align:left;"> Amazon raises US price for Prime as profits jump </td>
   <td style="text-align:left;"> Amazon is raising the price of its Prime service for US customers after reporting record sales and profits.                                                                                                                                                                                          , The e-commerce giant said it was hiking the price by 17% to $139 for annual membership.                                                                                                                                                                                                              , The firm, which cited increased wage and shipping costs, said it had no announcements to make about other countries "at this time".                                                                                                                                                                  , It is the first increase since 2018 for Prime, which gives subscribers access to benefits like faster shipping.                                                                                                                                                                                      , More than 200 million people globally pay for the service, many of them in the US.                                                                                                                                                                                                                   , Amazon shares soared almost 15% in after hours trade on the news, which accompanied the release of its end of 2021 performance.                                                                                                                                                                      , Sales for the last three months of 2021 expanded by 10% year-on-year to $137.4bn. But those gains were driven by growth in areas like its cloud computing division, Amazon Web Services, and advertising, while its e-commerce sales dipped from 2020, when the pandemic propelled blockbuster gains., The firm's profits in the quarter also jumped, to $14.3bn - almost double the prior year. Its investment in electric vehicle maker Rivian, which floated on the stock market in November, drove those increases.                                                                                     , For the year, sales rose 22% to $469.8 billion, sending profits to $33.4bn.                                                                                                                                                                                                                          , Analysts had been worried about how the firm would fare, after executives warned last year they were seeing higher costs due to supply issues and difficulty hiring workers.                                                                                                                         , Amazon said those challenges had hurt - and were likely to continue this year. It forecast sales growth of 3%-8% in the first three months of 2022.                                                                                                                                                  , "As expected over the holidays, we saw higher costs driven by labour supply shortages and inflationary pressures, and these issues persisted into the first quarter due to Omicron," chief executive Andy Jassy said.                                                                                , "Despite these short-term challenges, we continue to feel optimistic and excited about the business as we emerge from the pandemic."                                                                                                                                                                 , The company said inflation, including higher wages, drove $4bn more in costs in the final months of 2021. With the increase in the Prime fees, the firm is moving to shift some of those costs to customers.                                                                                         , Mr Jassy said some may quit Prime due to the fee increase, which goes into effect on 18 February for new members and will apply after 25 March to existing subscribers.                                                                                                                              , But he said that hadn't been a problem in the past.                                                                                                                                                                                                                                                  , Consumer spending in the US has remained strong, despite prices rising at a 7% rate last year - the fastest inflation in nearly four decades.                                                                                                                                                        , When Ruby Wax met Pamela Anderson...                                                                                                                                                                                                                                                                 , Russell Kane and guests explore the life of Queen Elizabeth I...                                                                                                                                                                                                                                     , The story of the Holocaust through the eyes of remarkable 106-year-old Boris Pahor                                                                                                                                                                                                                   , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/03/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-02-04 07:03:09 </td>
   <td style="text-align:left;"> U.S. stock futures rally after earnings reports from Amazon and Snapchat </td>
   <td style="text-align:left;"> , Stock futures rose in overnight trading Thursday as investors digested a slew of corporate earnings reports after the Nasdaq Composite posted its worst day in more than a year.                                                                                                                                                               , Futures on the Dow Jones Industrial Average gained about 195 points, or 0.6%. S&amp;P 500 futures added 1.1%, and Nasdaq 100 futures rallied 1.9%.                                                                                                                                                                                                 , Several technology stocks posted huge after-hours gains following strong quarterly results. Amazon jumped more than 14%, Pinterest surged more than 19% and Snap rocketed up roughly 58% after reporting earnings.                                                                                                                             , The moves come after a disappointing earnings report from Facebook parent Meta sent the mega-cap tech stock lower and weighed on equity markets.                                                                                                                                                                                               , After Facebook's quarterly results, "everyone just gave up and sold the whole sector. That was clearly the wrong read," Rich Greenfield of Lightshed Partners told CNBC's "Closing Bell" on Thursday. "What's going to be really interesting is how investors start to look at these companies more individually versus ... this whole sector.", Alpha is back with most hedge funds outperforming in January, Bank of America says                                                                                                                                                                                                                                                             , Retail investors are buying the January dip in force, especially these four stocks                                                                                                                                                                                                                                                             , The struggles now for Facebook are similar to 2018, so analysts think the stock should bounce back                                                                                                                                                                                                                                             , On Thursday, the tech-heavy Nasdaq Composite fell 3.7% for its worst daily performance since September 2020. The S&amp;P 500 had its worst day in nearly a year, sliding 2.4%. The Dow Jones Industrial Average fell 518.17 points.                                                                                                                , "The sharp drop in FB market cap today and the accompanying drag on the S&amp;P500 index is ... a stark reminder of the high concentration of mega-cap Tech stocks in the S&amp;P 500 — and the vulnerabilities that such concentration brings," Goldman Sachs' Chris Hussey said in a note Thursday.                                                  , Meanwhile, U.S. oil prices topped $90 per barrel for the first time since 2014, heightening inflation concerns.                                                                                                                                                                                                                                , Investors also eyed economic data. U.S. jobless claims came in at 238,000 last week, the Labor Department reported Thursday, slightly fewer than expected.                                                                                                                                                                                     , The focus now turns to the January jobs report set for release Friday morning. Economists surveyed by Dow Jones expect a gain of 150,000 jobs, but some losses as large as 400,000.                                                                                                                                                            , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                         , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                         , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                               , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                               , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                             , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-03/tech-led-u-s-stock-slump-may-weigh-on-asia-open-markets-wrap </td>
   <td style="text-align:left;"> 2022-02-04 06:32:54 </td>
   <td style="text-align:left;"> U.S. Futures Up on Amazon, Hong Kong Steadies Asia: Markets Wrap </td>
   <td style="text-align:left;"> Sunil Jagtiani                                                                                                                                                                                                                                                                                               , U.S. equity futures rose Friday as Amazon.com Inc. earnings soothed nerves, while a climb in Hong Kong shares aided Asia. Bonds fell on an ever-louder hawkish chorus from key central banks.                                                                                                                , Contracts on the tech-heavy Nasdaq 100 were up about 1.5% after e-commerce titan Amazon and Snap Inc. soared in late trading on strong earnings. A tech index advanced in Hong Kong -- which reopened from a prolonged holiday -- helping to steady MSCI Inc.’s Asia-Pacific gauge. Japanese equities dipped. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/02/03/aftermath-of-us-raid-syria-arwa-damon-dnt-lead-intl-vpx.cnn </td>
   <td style="text-align:left;"> 2022-02-04 06:25:48 </td>
   <td style="text-align:left;"> Video shows grim reality of US raid in Syria  - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/03/stocks-making-the-biggest-moves-after-hours-snap-amazon-ford-and-more.html </td>
   <td style="text-align:left;"> 2022-02-04 06:05:05 </td>
   <td style="text-align:left;"> Stocks making the biggest moves after hours: Snap, Amazon, Ford and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                            , Check out the companies making headlines after the bell:                                                                                                                                                                                                                                                                                                                                                                   , Amazon — Shares of Amazon popped more than 18% after hours following a strong quarterly report. The company reported its investment in electric vehicle company Rivian gained almost $12 billion in the fourth quarter. Amazon also announced it would increase the price of Prime by nearly 17%. Amazon Web Services also delivered almost 40% year-over-year growth in the fourth quarter, beating Wall Street estimates., Ford Motor — Ford fell 3.9% in extended trading after a weaker-than-expected quarterly report. The automaker posted earnings of 26 cents per share on revenue of $35.3 billion. Analysts were looking for a profit of 45 cents per share on revenue of $35.52 billion, according to Refinitv.                                                                                                                              , Snap — Snap shares rocketed more than 54% in after-hours trading after the social media company reported its first-ever quarterly net profit. The company posted adjusted profit of 22 cents per share compared with the Refinitiv consensus of 10 cents per share.                                                                                                                                                        , Pinterest — Pinterest jumped 27.7% after hours following a better-than-expected quarterly report. The social media platform posted earnings of 49 cents per share, 4 cents above the Refinitv consensus estimate. Revenue also topped expectations on the Street.                                                                                                                                                          , Clorox — Shares of Clorox dropped 8.4% after an earnings miss. The consumer products company posted a profit of 66 cents per share, versus the Refinitiv consensus of 18 cents per share. Clorox also issued fiscal year earnings-per-share outlook below estimates.                                                                                                                                                       , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                     , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                     , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                           , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                           , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                         , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-03/amazon-lifts-tech-stocks-bringing-hope-of-a-market-rebound?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-04 06:04:36 </td>
   <td style="text-align:left;"> Amazon Lifts Tech Stocks, Bringing Hope of a Market Rebound </td>
   <td style="text-align:left;"> Kristine Owram                                                                                                                                                                                                                                                                                                , The Nasdaq 100 index was primed for a rebound Friday as strong earnings from the likes of Amazon.com Inc., Snap Inc. and Pinterest Inc. helped ease fears after Meta Platforms Inc.’s stock crash.                                                                                                            , The Invesco QQQ Trust Series 1, the biggest exchange-traded fund that tracks the Nasdaq 100, jumped as much as 2.2% in postmarket trading. Amazon drove the gains, surging 19% after the ecommerce giant reported profit that beat estimates and announced that it will hike the price of a Prime membership.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/03/technology/facebook-meta-challenges.html </td>
   <td style="text-align:left;"> 2022-02-04 06:03:42 </td>
   <td style="text-align:left;"> 6 Reasons Meta Is in Trouble - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                         , Supported by                                                                                                                                                                                                                                                                                                                                                                          , The company formerly known as Facebook has hit major turbulence as it suffered its biggest one-day wipeout ever.                                                                                                                                                                                                                                                                      , By Mike Isaac                                                                                                                                                                                                                                                                                                                                                                         , Mike Isaac, who reports from the San Francisco Bay Area, has covered Facebook for more than a decade.                                                                                                                                                                                                                                                                                 , Meta, the company formerly known as Facebook, suffered its biggest one-day wipeout ever on Thursday as its stock plummeted 26 percent and its market value plunged by more than $230 billion.                                                                                                                                                                                         , Its crash followed a dismal earnings report on Wednesday, when Mark Zuckerberg, the chief executive, laid out how the company was navigating a tricky transition from social networking toward the so-called virtual world of the metaverse. On Thursday, a company spokesman reiterated statements from its earnings announcement and declined to comment further.                   , Here are six reasons that Meta is in a difficult spot.                                                                                                                                                                                                                                                                                                                                , The salad days of Facebook’s wild user growth are over.                                                                                                                                                                                                                                                                                                                               , Even though the company on Wednesday recorded modest gains in new users across its so-called family of apps — which includes Instagram, Messenger and WhatsApp — its core Facebook social networking app lost about half a million users over the fourth quarter from the previous quarter.                                                                                           , That’s the first such decline for the company in its 18-year history, during which time it had practically been defined by its ability to bring in more new users. The dip signaled that the core app may have reached its peak. Meta’s quarterly user growth rate was also the slowest it has been in at least three years.                                                          , Meta’s executives have pointed to other growth opportunities, like turning on the money faucet at WhatsApp, the messaging service that has yet to generate substantial revenue. But those efforts are nascent. Investors are likely to next scrutinize whether Meta’s other apps, such as Instagram, might begin to hit their top on user growth.                                     , Last spring, Apple introduced an “App Tracking Transparency” update to its mobile operating system, essentially giving iPhone owners the choice as to whether they would let apps like Facebook monitor their online activities. Those privacy moves have now hurt Meta’s business and are likely to continue doing so.                                                               , Now that Facebook and other apps must explicitly ask people for permission to track their behavior, many users have opted out. That means less user data for Facebook, which makes targeting ads — one of the company’s main ways of making money — more difficult.                                                                                                                   , Doubly painful is that iPhone users are a far more lucrative market to Facebook’s advertisers than, say, Android app users. People who use iPhones to access the internet typically spend more money on products and apps served up to them from mobile ads.                                                                                                                          , Meta said on Wednesday that Apple’s changes would cost it $10 billion in revenue over the next year. The company has railed against Apple’s shifts and said they are bad for small businesses that rely on advertising on the social network to reach customers. But Apple is unlikely to reverse its privacy changes and Meta’s shareholders know it.                                , Meta’s troubles have been its competitors’ good fortune.                                                                                                                                                                                                                                                                                                                              , On Wednesday, David Wehner, Meta’s chief financial officer, noted that as Apple’s changes have given advertisers less visibility into user behaviors, many have started shifting their ad budgets to other platforms. Namely Google.                                                                                                                                                  , In Google’s earnings call this week, the company reported record sales, particularly in its e-commerce search advertising. That was the very same category that tripped up Meta in the last three months of 2021.                                                                                                                                                                     , Unlike Meta, Google is not heavily dependent on Apple for user data. Mr. Wehner said it was likely that Google had “far more third-party data for measurement and optimization purposes” than Meta’s ad platform.                                                                                                                                                                     , Mr. Wehner also pointed to Google’s deal with Apple to be the default search engine for Apple’s Safari browser. That means Google’s search ads tend to appear in more places, taking in more data that can be useful for advertisers. That’s a huge problem for Meta in the long term, especially if more advertisers switch to Google search ads.                                    , For more than a year, Mr. Zuckerberg has pointed to how formidable TikTok has been as a foe. The Chinese-backed app has grown to more than a billion users on the back of its highly shareable and strangely addictive short video posts. And it is fiercely competing with Meta’s Instagram for eyeballs and attention.                                                              , Meta has cloned TikTok with a video product feature called Instagram Reels. Mr. Zuckerberg said on Wednesday that Reels, which is prominently placed in people’s Instagram feeds, was currently the No. 1 driver of engagement across the app.                                                                                                                                        , The problem is that while Reels may be attracting users, it doesn’t make money as effectively as Instagram’s other features, like Stories and the main feed. That’s because it’s slower to make money off video ads, since people tend to skip past them. That means the more that Instagram pushes people toward using Reels, the less money it may make on those users.             , The origins. The word “metaverse” describes a fully realized digital world that exists beyond the one in which we live. It was coined by Neal Stephenson in his 1992 novel “Snow Crash,” and the concept was further explored by Ernest Cline in his novel “Ready Player One.”                                                                                                        , An expanding universe. The metaverse appears to have gained momentum during the online-everything shift of the pandemic. The term today refers to a variety of experiences, environments and assets that exist in the virtual space.                                                                                                                                                  , Some examples. Video games in which players can build their own worlds have metaverse tendencies, as does most social media. If you own a non-fungible token, virtual-reality headset or some cryptocurrency, you’re also part of the metaversal experience.                                                                                                                          , How Big Tech is shifting. Facebook staked its claim to the metaverse last year, after shipping 10 million of its virtual-reality headsets and announcing it had renamed itself Meta. Google, Microsoft and Apple have all been working on metaverse-related technology.                                                                                                               , The future. Many people in tech believe the metaverse will herald an era in which our virtual lives will play as important a role as our physical realities. Some experts warn that it could still turn out to be a fad or even dangerous.                                                                                                                                            , Mr. Zuckerberg compared the situation to a similar time several years ago when Instagram introduced its Stories feature, which was a clone of Snapchat. That product also did not make as much money for the company when it debuted, though the ad dollars eventually followed. Still, there’s no guarantee Instagram Reels can repeat that magic.                                   , Mr. Zuckerberg believes so much that the internet’s next generation is the metaverse — a still fuzzy and theoretical concept that involves people moving across different virtual- and augmented-reality worlds — that he is willing to spend big on it.                                                                                                                              , So big that the spending amounted to more than $10 billion last year. Mr. Zuckerberg expects to spend even more in the future.                                                                                                                                                                                                                                                        , Yet there is no evidence the bet will pay off. Unlike Facebook’s shift to mobile devices in 2012, virtual reality use is still the province of niche hobbyists and has yet to really break into the mainstream. Widespread augmented-reality headsets are also months — if not years — away.                                                                                          , In essence, Mr. Zuckerberg is asking employees, users and investors to have faith in him and his metaverse vision. That’s a big ask for something that will cost the company billions in the coming years and that may never come to fruition.                                                                                                                                        , The threat of regulators in Washington coming for Mr. Zuckerberg’s company is a headache that just won’t go away.                                                                                                                                                                                                                                                                     , Meta faces multiple investigations, including from a newly aggressive Federal Trade Commission and multiple state attorneys general, into whether it acted in an anti-competitive manner. Lawmakers have also coalesced around congressional efforts to pass antitrust bills.                                                                                                         , Mr. Zuckerberg has argued that Meta is not a social networking monopoly. He has pointed furiously to what he calls “unprecedented levels of competition,” including from TikTok, Apple, Google and other future opponents.                                                                                                                                                            , But the threat of antitrust action has made it more difficult for Meta to buy its way into new social networking trends. In the past, Facebook bought Instagram and WhatsApp with little scrutiny as those services gained billions of users. Now even some of Meta’s seemingly less contentious acquisitions in virtual reality and GIFs have been challenged by regulators globally., With deal-making less likely, the onus is on Meta to innovate its way out of any challenges.                                                                                                                                                                                                                                                                                          , In the past, Mr. Zuckerberg might have been given the benefit of the doubt that he would be able to do so. But on Thursday at least, faith was in short supply on Wall Street.                                                                                                                                                                                                        , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/clorox-stock-drops-after-company/story.aspx?guid={82D26593-FA54-449E-981D-D95B6B43B4BF}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-04 05:59:04 </td>
   <td style="text-align:left;"> Clorox stock drops after company hit by lower margins, inflation - MarketWatch </td>
   <td style="text-align:left;"> Clorox Co. 
        CLX,
        -0.99%
       shares fell nearly 9% in the extended session Thursday after the maker of cleaning and other products got hit by lower margins and fewer sales amid "challenging" costs and inflation. Clorox said it earned $69 million, or 56 cents a share, in the fiscal second quarter, compared with $259 million, or $2.03 a share, in the year-ago quarter, mostly thanks to lower gross margin and lower net sales. Adjusted for one-time items, Clorox earned 66 cents a share. Net sales declined 8% to $1.69 billion, a far cry from a 27% increase in the year-ago quarter. Analysts polled by FactSet expected Clorox to report adjusted earnings of 84 cents a share on sales of $1.66 billion. "In the face of a challenging cost environment, we're executing well on the factors we control. We're driving cost savings and pricing to mitigate inflationary headwinds, while also continuing to meet strong demand across our portfolio," Chief Executive Linda Rendle said in a statement. The company tweaked its fiscal 2022 outlook to call for a sales decline of between 1% and 4% and adjusted EPS between $4.25 a share and $4.50 a share, down between 41% and 38%. Clorox stock ended the regular trading day down 1%., More than seven months after he died in a Spanish prison, John McAfee’s body remains in a prison morgue freezer somewhere in or near Barcelona.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/building-permits </td>
   <td style="text-align:left;"> 2022-02-04 05:50:48 </td>
   <td style="text-align:left;"> New Zealand New Building Permits At a Record High in 2021 </td>
   <td style="text-align:left;"> The number of building consents issued for new dwellings in New Zealand rose 0.6 percent month-over-month to 4,231 in December of 2021, following a 0.6 percent increase in the previous month. Meanwhile, for the whole year of 2021, a record number of 48,899 new homes were consented, recording an increase of 24 percent in comparison to 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-03/u-s-soybeans-are-in-high-demand-as-brazil-s-crop-falls-short?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-04 05:45:06 </td>
   <td style="text-align:left;"> U.S. Soybeans Are in High Demand as Brazil’s Crop Falls Short </td>
   <td style="text-align:left;"> Tarso Veloso Ribeiro                                                                                                                                                                                                                                                                                                                                                                                                                  , Soybean buyers stung by a smaller and slower harvest than expected in Brazil are turning to the U.S. for supply, driving up prices and threatening to worsen food inflation.                                                                                                                                                                                                                                                          , What was expected to be a record crop in Brazil is now looking far smaller, with lower yields and harvest delays due to adverse weather catching traders and end-users shorthanded. The uncertainty has driven buyers into the U.S. market. More than 110 ships have been chartered on a preliminary basis to load crops at ports in the Pacific Northwest, according to Bill Tierney, chief economist for AgResource Co. in Chicago.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/skechers-stock-rallies-9-after/story.aspx?guid={EAC43C80-5086-4582-BD2C-A919A56B1681}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-04 05:44:58 </td>
   <td style="text-align:left;"> Skechers stock rallies 9% after company's bet on comfortable shoes pays off - MarketWatch </td>
   <td style="text-align:left;"> Shares of Skechers USA Inc. 
        SKX,
        -1.86%
       rallied nearly 8% in the extended session Thursday after the footwear retailer reported fourth-quarter earnings and sales above Wall Street expectations, saying its bet on comfortable styles paid off. Skechers said it earned $402 million, or $2.56 a share, in the quarter, compared with $53.3 million, or 34 cents a share, in the year-ago period. Adjusted for one-time items, the company earned 43 cents a share. Sales rose 24% to $1.65 billion, with direct-to-consumer sales up 30% and wholesale international sales also a highlight, the company said. Analysts polled by FactSet expected the company to report adjusted earnings of 33 cents a share on sales of $1.6 billion. "We believe our accomplishments in 2021, including several comfort-focused new product launches and the further expansion of our global footprint, position Skechers for continued growth toward our goal of $10 billion in sales," Chief Executive Robert Greenberg said in a statement. Skechers stock ended the regular trading day down 1.9%. , Here's what the chief executive of ARK Invest had to say.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-02-04 05:43:32 </td>
   <td style="text-align:left;"> Canada Stocks Snap 4-Day Rally </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, dropped almost 1.3% to close at 21,094 on Thursday mostly weighed down by tech stocks (-4.7%) after downbeat earnings from US tech giant Meta Platforms rattled markets, and also healthcare stocks. Meanwhile, Bank of Canada Governor Macklem said there was uncertainty over when inflation would decline to the central bank’s comfort zone, due to the unique nature of the pandemic. On the earnings front, Suncor Energy missed Q4 FY21 profit expectations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-02-04 05:40:41 </td>
   <td style="text-align:left;"> Brazilian Stocks Extend Losses For 2nd Day </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, slipped 0.2% to close at 111,696 on Thursday, tracking international stock markets lower, and extending losses for a second consecutive session. Cyclical sectors, such as retailers and construction companies, retreated after a strong start, tracking international markets. Meanwhile, investors continued digesting the latest monetary policy decision from the Brazilian central bank to raise the Selic by 150 basis points to 10.75%, as expected, but signaling that it should reduce the pace of the hike for the next meetings. On the data front, a Markit PMI survey showed Brazil's private sector growth slowed to a nine-month low, as a faster expansion in services was not enough to counteract another contraction in manufacturing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/snap:us </td>
   <td style="text-align:left;"> 2022-02-04 05:24:33 </td>
   <td style="text-align:left;"> Snap earnings above expectations at 0.22 USD </td>
   <td style="text-align:left;"> Snap (SNAP) released earnings per share at 0.22 USD, compared to market expectations of 0.09 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mchp:us </td>
   <td style="text-align:left;"> 2022-02-04 05:23:52 </td>
   <td style="text-align:left;"> Microchip Technology earnings above expectations at 1.2 USD </td>
   <td style="text-align:left;"> Microchip Technology (MCHP) released earnings per share at 1.2 USD, compared to market expectations of 1.17 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/pru:us </td>
   <td style="text-align:left;"> 2022-02-04 05:23:39 </td>
   <td style="text-align:left;"> Prudential Financial earnings above expectations at 3.18 USD </td>
   <td style="text-align:left;"> Prudential Financial (PRU) released earnings per share at 3.18 USD, compared to market expectations of 2.36 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ftnt:us </td>
   <td style="text-align:left;"> 2022-02-04 05:22:26 </td>
   <td style="text-align:left;"> Fortinet earnings above expectations at 1.23 USD </td>
   <td style="text-align:left;"> Fortinet (FTNT) released earnings per share at 1.23 USD, compared to market expectations of 1.15 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/atvi:us </td>
   <td style="text-align:left;"> 2022-02-04 05:21:51 </td>
   <td style="text-align:left;"> Activision Blizzard earnings below expectations at 1.25 USD </td>
   <td style="text-align:left;"> Activision Blizzard (ATVI) released earnings per share at 1.25 USD, compared to market expectations of 1.31 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/f:us </td>
   <td style="text-align:left;"> 2022-02-04 05:14:05 </td>
   <td style="text-align:left;"> Ford Motor earnings below expectations at 0.26 USD </td>
   <td style="text-align:left;"> Ford Motor (F) released earnings per share at 0.26 USD, compared to market expectations of 0.44 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/amzn:us </td>
   <td style="text-align:left;"> 2022-02-04 05:07:21 </td>
   <td style="text-align:left;"> Amazon earnings above expectations at 27.75 USD </td>
   <td style="text-align:left;"> Amazon (AMZN) released earnings per share at 27.75 USD, compared to market expectations of 3.63 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/amazon-earnings-report </td>
   <td style="text-align:left;"> 2022-02-04 05:02:51 </td>
   <td style="text-align:left;"> Inflation hits Amazon: Price of Prime memberships going up </td>
   <td style="text-align:left;"> Circle Squared Alternative Investments Jeff Sica provides analysis into the Amazon markets report on 'Varney &amp; Co.'                                                                                                                                                                                                                                                                                    , Amazon announced Thursday that it would be boosting the price of its Prime membership for U.S. customers, citing rising costs as the reason behind the decision.                                                                                                                                                                                                                                       , In a letter to investors outlining its fourth quarter earnings, the company stated that increased wage and transportation costs along with its expansion of membership benefits has led the online retail giant to increase its Prime fees for the first time since 2018.                                                                                                                              , FILE PHOTO: Logos of Amazon and Amazon Prime are pictured on vehicles outside the Amazon Fulfilment Centre in Altrincham, near Manchester, Britain, November 26, 2021. REUTERS/Carl Recine/File Photo  (Reuters / Reuters Photos)                                                                                                                                                                      , STATEN ISLAND AMAZON WAREHOUSE GAINS ENOUGH SUPPORT FOR UNION ELECTION, LABOR BOARD SAYS                                                                                                                                                                                                                                                                                                               , Monthly Prime memberships will go from $12.99 to $14.99, and annual memberships will be hiked to $139 from the current $119. The price change will go into effect for new members starting Feb. 18, and existing members will see their fees go up on the date of their next renewal after March 25.                                                                                                   , For the quarter ending Dec. 31, Amazon blew earnings per share projections out of the water. Wall Street had expected EPS of $3.44, but the retailer delivered a staggering $27.75. Investors appeared to like the results, as the company's stock shot up more than 18% in after-hours trading following the report.                                                                                  , Andy Jassy, chief executive officer of Amazon.  (David Paul Morris/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                          , "A big thank you to employees across Amazon who overcame another quarter of COVID-related challenges and delivered for customers this holiday season," CEO Andy Jassy said in a statement.                                                                                                                                                                                                             , ACQUCO HELPS BRANDS EXPAND BEYOND AMAZON'S GRASP                                                                                                                                                                                                                                                                                                                                                       , "Given the extraordinary growth we saw in 2020 when customers predominantly stayed home, and the fact that we’ve continued to grow on top of that in 2021, our Retail teammates have effectively operated in peak mode for almost two years," Jassy said. "It’s been a tremendous effort, and I’m appreciative and proud of how hard our teams have worked to serve customers."                        , An employee wearing a protective mask scans a package at an Amazon.com Inc. fulfillment center in Kegworth, U.K., on Monday, Oct. 12, 2020. (Chris Ratcliffe/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                , "Amazon delivered a blowout quarter, defying the odds and in the process saving the tech sector from further losses," Investing.com senior analyst Jesse Cohen said in a statement FOX Business following the results. "The company beat expectations on the performance of almost all business units, overcoming supply chain issues and labor shortages."                                            , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                            , "Despite the positive reaction, Amazon faces a challenging period ahead as it deals with slowing sales growth and rising costs in the post-pandemic environment," Cohen continued."That said, Amazon's impressive results are just what the tech sector needed to stop the bleeding," he added. "The e-commerce giant's big beat could be the much-needed catalyst to spark a rally in the tech space." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/stocks-tumble-close-thursday-halting/story.aspx?guid={CD6A5536-F383-444E-8FB5-C3B1E741386C}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-04 05:01:37 </td>
   <td style="text-align:left;"> Stocks tumble into the close Thursday, halting a 4-session climb - MarketWatch </td>
   <td style="text-align:left;"> U.S. stocks halted a four-day advance on Thursday, with the rate-sensitive Nasdaq Composite Index leading the way lower as equity benchmarks tumbled in the final hour of trade. The Nasdaq Composite 
        COMP,
        -3.74%
       skid 3.7%, shedding about 540 points, to finish near 13,878. The S&amp;P 500 index 
        SPX,
        -2.44%
       fell 2.4%, while the Dow Jones Industrial Average 
        DJIA,
        -1.45%
       closed down 1.5%. Stocks got off to a shakier start after Meta Platforms 
        FB,
        -26.39%
       missed sales and growth estimates for the fourth quarter. In Europe, the ECB President Christine Lagarde also declined to rule out a rate increase in 2022 and acknowledged that inflation risks for the eurozone are "tilted to the upside," signaling that policy makers were likely to offer more detailed guidance when they meet in March. That's also when many on Wall Street now expect the first U.S. rate hike by the Federal Reserve since 2018., PayPal’s fourth-quarter earnings, and particularly its disappointing outlook, are spooking investors.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Joy Wiltermuth is a news editor and senior markets reporter based in San Francisco. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-03/boe-hike-leaves-bailey-on-brink-of-fastest-tightening-since-1997?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-04 05:00:00 </td>
   <td style="text-align:left;"> BOE Hike Leaves Bailey on Brink of Fastest Tightening Since 1997 </td>
   <td style="text-align:left;"> David Goodman                                                                                                                                                                                                                                                              ,  and Greg Ritchie                                                                                                                                                                                                                                                          , The Bank of England is on the cusp of the fastest tightening of monetary policy since it gained independence in 1997 as it leads the way among major central banks in fighting inflation.                                                                                  , The central bank delivered its second consecutive interest-rate increase and warned more moves are on the way. Policy makers are alarmed inflation is set to top 7%, more than triple their target and over a full percentage point higher than they forecast in December.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/technology-60250956?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-04 04:50:19 </td>
   <td style="text-align:left;"> European oil facilities hit by cyber-attacks </td>
   <td style="text-align:left;"> Multiple oil transport and storage companies across Europe are dealing with cyber-attacks.                                                                                                                                                                                       , IT systems have been disrupted at Oiltanking in Germany, SEA-Invest in Belgium and Evos in the Netherlands.                                                                                                                                                                      , In total dozens of terminals with oil storage and transport around the world have been affected, with firms reporting that the attacks occurred over the weekend.                                                                                                                , But experts caution against assuming this is a co-ordinated attack.                                                                                                                                                                                                              , The BBC understands that all three companies' IT systems went down or were severely disrupted.                                                                                                                                                                                   , Belgian prosecutors say they are investigating the cyber-attack that's affected SEA-Invest terminals including the company's largest in Antwerp, called SEA-Tank.                                                                                                                , A spokeswoman for the company said they were hit on Sunday with every port they run in Europe and Africa affected.                                                                                                                                                               , The company is working to get a back-up IT system online but says that most liquid transportation is operational.                                                                                                                                                                , The spokeswoman said SEA-Invest is aware of the cyber-attacks against other companies but investigations have not determined if there is a link.                                                                                                                                 , A spokesperson for Evos in the Netherlands told the BBC that IT services at terminals in Terneuzen, Ghent and Malta have "caused some delays in execution".                                                                                                                      , On Monday Oiltanking Deutschland GmbH &amp; Co. KG, which stores and transports oil, vehicle fuels and other petroleum products, said it had been hacked.                                                                                                                            , The company was forced to operate at a "limited capacity" and was investigating the incident, it said.                                                                                                                                                                           , Some reports suggest the attack on Oiltanking is ransomware, where hackers scramble data and make computer systems inoperable until they get paid a ransom.                                                                                                                      , In May last year a ransomware attack on US oil supplier Colonial Pipeline saw supplies tighten across the US and multiple states declaring an emergency.                                                                                                                         , An employee of a major barging company in the Netherlands told the BBC that port supply chains were disrupted.                                                                                                                                                                   , The worker said they first noticed problems on Tuesday when oil deliveries started slowing down. He said "things are moving but much slower than normal".                                                                                                                        , The disruption comes as tensions remain high between Ukraine and Russia and as concern over rising energy prices grows.                                                                                                                                                          , But cyber-security experts caution against jumping to the conclusion that the multiple incidents are the result of a co-ordinated effort to disrupt the European energy sector.                                                                                                  , "Some types of malware scoop up emails and contact lists and use them to automatically spam malicious attachments or links, so companies with shared connections can sometimes be hit in quick succession," said Brett Callow, Threat Analyst at cyber-security company Emsisoft., "This is why you sometimes see sector-based or geographic-based clusters of incidents."                                                                                                                                                                                          , Another possible explanation could be that all the companies use the same software for operations that may have been compromised by hackers.                                                                                                                                     , When Ruby Wax met Pamela Anderson...                                                                                                                                                                                                                                             , Russell Kane and guests explore the life of Queen Elizabeth I...                                                                                                                                                                                                                 , The story of the Holocaust through the eyes of remarkable 106-year-old Boris Pahor                                                                                                                                                                                               , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/charles-takeaway-amazon-stock-doesnt-wow-but-snapchat-may-impress </td>
   <td style="text-align:left;"> 2022-02-04 04:43:13 </td>
   <td style="text-align:left;"> Charles' Takeaway: Amazon stock doesn't wow, but Snapchat may impress </td>
   <td style="text-align:left;"> FOX Business host gives his take on investing in Amazon and Snapchat on 'Making Money.'                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , FOX Business' Charles Payne gives his take on big tech stocks like Amazon and Snapchat. The 'Making Money' host explains why investors may want to hold on buying the former, and why the latter might surprise those looking to invest.                                                                                                                                                                                                                                                                                                                                                                                                                                                       , CHARLES PAYNE: Now, after they [Amazon] missed and got it lower in the prior quarter there was already angst here, right, that’s been brought up. Moreover, there are serious questions, the degree of the supply chain issues, labor force issues. We know that’s impacted their business and normally you would say, well, bad news is probably built into the stock which has been an under performer for more than a year, but, as we know right now, a miss could ...see a big hit to the stock. On that note, it’s a name that I would not sell. If it’s in my long-term account, I keep it in my long-term account. If you want to be a buyer, you probably could wait until tomorrow. …, Then there’s, of course, Snapchat. After years of being a drip - there was a series of mistakes the CEO made - the company’s finally got its act together, and the stock became an absolute juggernaut over the past five quarters… everyone jumped on the bandwagon, but it ran dry September 24th, the stock hit 83. What killed the stock was that growth slowed to its slowest pace since the third quarter of 2020, but it was up 50%. That’s how much it’s expected. Listen, we think the company will be impressive at $25…CLICK HERE TO READ MORE ON FOX BUSINESS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-04 04:27:00 </td>
   <td style="text-align:left;"> Wall Street Tumbles, Meta Shares Plunge 26% </td>
   <td style="text-align:left;"> US Stocks sank on Thursday, snapping a 4-day rally as tech and social media stocks weighed on investors’ mood. The Nasdaq Composite dropped 3.7%, dragged down by a 26.4% plunge in shares of Meta Platforms after earnings and outlook from the Facebook parent company disappointed. Also, other social media shares tracked Meta shares lower with Snap dipping 22% and Twitter dropping 6%. Meanwhile, mixed quarterly results from other companies including Honeywell, Biogen, T-Mobile, and Spotify also weighed on the indexes' performance. The S&amp;P 500 slid 2.5% and the Dow Jones lost more than 500 points. Amazon and Ford are due to report quarterly results after markets close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/03/going-abroad-your-destination-may-require-travel-insurance.html </td>
   <td style="text-align:left;"> 2022-02-04 04:01:30 </td>
   <td style="text-align:left;"> Going abroad? Your destination may require travel insurance </td>
   <td style="text-align:left;"> , Are you planning a trip abroad? You may need to buy travel insurance to visit your destination country.                                                                                                                                                                                                                                                                                                       , Many countries had insurance requirements even before the pandemic. But about a dozen more have since added rules, typically to cover Covid-19 medical expenses and other costs like lodging in the event of quarantine overseas, according to Clayton Coomer, vice president at WorldTrips, an insurer.                                                                                                      , Argentina, Aruba, the Bahamas, Bermuda, Bolivia, the British Virgin Islands, Cayman Islands, Chile, Costa Rica, Jamaica, Jordan and Lebanon are among the ones with pandemic-era mandates, Coomer said.                                                                                                                                                                                                       , More from Personal Finance:Americans are ready to travel as their omicron fears fadeHere's where Americans want to travel abroadHere's how to insure your trip amid airline cancellations                                                                                                                                                                                                                     , Belize also recently announced a new requirement for all tourists that starts Feb. 15.                                                                                                                                                                                                                                                                                                                        , "Countries are doing it so they don't have to absorb any financial burden for treating uninsured tourists who may contract Covid-19," Coomer said.                                                                                                                                                                                                                                                            , "[The situation] is evolving so much, especially with omicron," he added, referring to the highly contagious Covid-19 variant.                                                                                                                                                                                                                                                                                , In all, 60 countries mandate travel insurance for tourists, according to InsureMyTrip data as of Jan. 27.                                                                                                                                                                                                                                                                                                     , Requirements sometimes apply only to tourists who need a visa for entry, which means Americans may be exempt. (The 26 Schengen Area countries in Europe don't impose rules on Americans, for example.)                                                                                                                                                                                                        , The coverage rules are fluid and vary widely.                                                                                                                                                                                                                                                                                                                                                                 , For instance, Costa Rica requires insurance only for unvaccinated travelers. Belize will let travelers buy coverage upon arrival (though officials recommend buying ahead of time). Although both are technically part of the same European Union, the Dutch half (Sint Maarten) of Caribbean island Saint Martin does require insurance coverage, while the French-administered part (Saint-Martin) does not., These quirks increasingly make such research necessary before travel — in addition to any other entry rules, like those for testing and vaccination. Some countries, such as Japan, still haven't opened their borders to American tourists.                                                                                                                                                                  , The type and amount of covered costs will vary by country.                                                                                                                                                                                                                                                                                                                                                    , "Many countries require travel medical insurance that covers medical treatment for Covid-19 if a traveler contracts it during their trip," said Angela Borden, product marketing strategist with insurance firm Seven Corners. "Some countries require a specific policy amount while others do not."                                                                                                         , Some locations ask travelers to cover costs for food and lodging, too, if they must quarantine in the destination country due to Covid, Borden said.                                                                                                                                                                                                                                                          , The mandatory Belize Travel Health Insurance, for example, costs $18 and provides coverage for up to $50,000 in medical expenses related to Covid-19 treatment for 21 days. In addition, it covers lodging costs up to $2,000 (and $300 per day) for a quarantine, and trip cancellations and expenses due to an extended stay.                                                                               , Travelers to Jamaica pay a $40 mandatory fee for coverage that includes $50,000 of on-island health coverage and $5,000 for trip interruption.                                                                                                                                                                                                                                                                , Chile requires proof of a health insurance policy that "provides coverage for Covid-19 and related health issues during the traveler's stay," according to the U.S. Department of State.                                                                                                                                                                                                                      , Travelers must be covered for at least $30,000 and present documentation when boarding their flight. The Chilean capital of Santiago is the third-highest trending international destination for Americans, according to Hopper, a travel site.                                                                                                                                                               , Most standard travel-insurance policies have been designed to meet the requirements for most, if not all, countries, according to Coomer at WorldTrips. However, consumers should make sure a policy's coverage aligns with the destination's mandate before buying.                                                                                                                                          , (Six of the seven different travel insurance policies Seven Corners sells retail consumers include Covid-related coverage, for example, Borden said.)                                                                                                                                                                                                                                                         , Insurers also offer optional add-ons, like "cancel for any reason" coverage — which is more expensive but lets consumers recoup funds in a broader variety of circumstances, though conditions still apply.                                                                                                                                                                                                   , U.S. health plans may — but may not — also offer coverage overseas. (Medicare and Medicaid, for example, generally don't cover medical costs for international travelers, according to the State Department.) If they do, the policy may not meet a country's standards.                                                                                                                                      , Travelers may also get some coverage via a credit card. (However, it may not be as comprehensive as a separate insurance policy. Travelers must also generally use the card to buy all or part of the trip for the coverage to apply.)                                                                                                                                                                        , The State Department has a list of insurance-option considerations for Americans going abroad.                                                                                                                                                                                                                                                                                                                , "Travelers must understand the importance of travel insurance for international trips," Borden said. "Their insurance at home may not follow them abroad, and foreign medical facilities may require payment upfront before they provide care."                                                                                                                                                               , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                        , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                        , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                              , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                              , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                            , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-oil-futures-settle-above/story.aspx?guid={35F2BB6B-4690-49DC-9BF3-8C5C7D7FF784}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-04 03:49:34 </td>
   <td style="text-align:left;"> U.S. oil futures settle above $90 a barrel for the first time in over 7 years - MarketWatch </td>
   <td style="text-align:left;"> Oil futures rallied on Thursday, with U.S. prices settling above $90 a barrel to mark another settlement at their highest since October 2014, buoyed by worries surrounding risks to global supplies, despite a decision by major oil producers to lift crude production in March. There is no doubt that the winter storms in parts of the U.S. will impact oil production, said Phil Flynn, senior market analyst at The Price Futures Group. Freezing weather can hurt oil production as well as boost demand for heating fuels. West Texas Intermediate crude for March delivery 
        CLH22,
        +0.71%
       rose $2.01, or 2.3%, to settle at $90.27 a barrel on the New York Mercantile Exchange. That was the highest finish for a front-month contract since Oct. 6, 2014, according to FactSet data., The Communications Services Select SPDR has one of the highest exposures among funds to the former Facebook and to Alphabet.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/03/politics/trump-endorsements-down-ballot-races/index.html </td>
   <td style="text-align:left;"> 2022-02-04 03:42:05 </td>
   <td style="text-align:left;"> Some Trump endorsements spark frustration and fractures in GOP - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)Donald Trump recently extended an enticing offer to Vernon Jones: drop your flailing gubernatorial bid to run for a US House seat in Georgia, and you'll earn the former President's endorsement.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Jones is still debating whether to stick with the uphill race against former Sen. David Perdue, who is backed by Trump, and incumbent Republican Gov. Brian Kemp, who has drawn the former President's wrath for refusing to flout the law and overturn his loss in 2020.                                                                                                                                                                                                                                                                                                                                                                                                                 , But either way, his decision could pose an awkward problem for Trump. If Jones runs for the 10th congressional district, which is one of the seats he is considering, it would put Trump directly at odds with several members of the conservative House Freedom Caucus who have already endorsed a different candidate in that contest. One Georgia Republican said the delegation would be frustrated if Jones launches a congressional bid there with Trump's official blessing.                                                                                                                                                                                                       , And if Jones rejects Trump's overture, it would be the second time in as many weeks that the former President has failed to clear the field for his preferred candidate. Trump attempted a similar maneuver in North Carolina, Trump-backed Rep. Ted Budd has failed to emerge as the definitive front-runner in a US Senate primary race against former Gov. Pat McCrory and former Rep. Mark Walker. Trump offered to endorse Walker if he dropped out and ran for a House seat, but the former congressman declined, leaving the contest a three-way race.                                                                                                                             , Those primary struggles are only adding to the growing frustrations that some of Trump's endorsements have created in certain corners of the GOP. With end-of-the-year finance reports now public, it's clear some of Trump's candidates have struggled to raise cash or pull ahead in the polls — even as the former President built a massive war chest of his own last year.                                                                                                                                                                                                                                                                                                           , Some of his staunchest allies have also expressed concern that the former President is choosing the wrong candidate in certain races. Trump sparked a rare backlash among some of his staunchest allies last week when he threw his weight behind Morgan Ortagus, a former State Department spokesperson during the Trump administration, for a Tennessee congressional district. That put Trump directly at odds with a number of prominent conservatives, including Reps. Marjorie Taylor Greene of Georgia and Madison Cawthorn of North Carolina, who are backing another candidate -- Robby Starbuck -- for the seat instead.                                                        , Greene said that during a visit last week to Florida, she explained to Trump why she thought Starbuck was the better choice over Ortagus.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , "He's really a good representative of the base. And he's been so loyal to President Trump," Greene said. "But what bothered me about Morgan Ortagus is, she sent an email on January 19, 2021, and it was saying goodbye to everybody. And she said, 'I look forward to faithfully serving the incoming Biden administration.' "                                                                                                                                                                                                                                                                                                                                                          , Greene, however, defended Trump's decision-making: "He didn't know about that email. I seriously don't think she would have had his support had he known about that email. ... She doesn't deserve his endorsement."                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Trump told Newsmax on Tuesday that he knew Ortagus, a former spokesperson for Trump's State Department, and did not know social media influencer Starbuck. "I've done a lot of things that were somewhat controversial and they've worked out," Trump said. "She's solid."                                                                                                                                                                                                                                                                                                                                                                                                                , Ortagus has not yet officially announced her House campaign. But she went on Newsmax Tuesday and called Trump "the greatest president in my lifetime, especially on foreign policy."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , While Trump is the most powerful force in the GOP, the latest flare-ups surrounding some of his endorsements are threatening to create fractures among his core base of supporters and raising fresh questions about how many of his hand-picked candidates will ultimately make it across the finish line in November. It comes at a vulnerable time for Trump, with potential 2024 presidential GOP candidates swirling and investigations into him and his businesses escalating from New York to Georgia to Washington, DC.                                                                                                                                                           , But Trump's supporters say that the former President's stamp of approval remains the most coveted endorsement in the GOP and will greatly help his candidates win their primaries.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , "President Trump will be campaigning aggressively throughout the midterms to ensure the MAGA ticket sweeps on Election Day," said Trump spokesman Taylor Budowich. "This includes providing a platform for candidates at his massive Save America rallies and appearing in campaign commercials and fundraising solicitations."                                                                                                                                                                                                                                                                                                                                                           , "Republican candidates are also flocking to Mar-A-Lago to seek the President's support and raise money," added Budowich, referring to Trump's Florida resort. "There has never been an endorsement as powerful and consequential as President Trump's."                                                                                                                                                                                                                                                                                                                                                                                                                                   , Some Trump's allies upset over endorsements -- or lack thereof                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , ​​Inside Trump's orbit, his hasty endorsement of Ortagus after a meeting with her left some advisers worried that he was reverting to old habits. When the former President first arrived in Florida last January, he lacked a thorough vetting process for candidates seeking his support and was persuaded on more than one occasion to endorse candidates following a single conversation with them or one of their Trump-aligned consultants.                                                                                                                                                                                                                                           , "The Ortagus announcement gave me déjà vu," said one Trump ally, who has been involved in previous endorsement decisions made by Trump.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Impulsive as it was, Trump's endorsement of Ortagus, who has yet to formally declare her candidacy, was even more shocking to allies who had grown accustomed to a more orderly vetting process that was recently put into place by one of his top aides, Susie Wiles, amid a flood of requests from 2022 Republican hopefuls. Recently, Trump has been briefed on the latest polling, demographic makeup of a district and past and present statements by candidates before meeting with them at his Florida estate. Endorsement decisions are then discussed among his team and rolled out "when the timing is right," said a person familiar with the process.                         , The dustup over the Tennessee race wasn't the first time in recent months that Trump's endorsement -- or lack thereof -- has unnerved those around him. In Texas, the former President's July endorsement of incumbent Attorney General Ken Paxton drew criticism from some allies who worry that Paxton's ongoing legal troubles could haunt him in a general election and tarnish Trump's endorsement record. It harkened back to Trump's endorsement of Sean Parnell, who had to drop out of the Senate primary race in Pennsylvania after a judge ordered his estranged wife primary custody over their children.                                                                     , The scandal-plagued Paxton, who was indicted in 2015 on securities fraud charges, currently faces a professional misconduct investigation by the Texas Bar Association for his lawsuit challenging the 2020 election results. Last Thursday, the Travis County District Attorney's office also ruled that Paxton had violated the state's open records law by failing to turn over his communications from a visit to Washington, DC, last January, when he attended Trump's "Stop the Steal" rally before rioters stormed the US Capitol.                                                                                                                                                , "They all have my complete and total endorsement," Trump said at a rally near Houston last Saturday, name-checking Paxton.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , In Georgia, if Jones transitions to a campaign for one of two congressional districts -- either the 6th or 10th -- it could help Perdue close the gap with Kemp, in a big boon for Trump. But it could also create new issues for Trump in the Peach State: in the 10th district, half a dozen members of the Freedom Caucus, including the seat's current occupant, GOP Rep. Jody Hice, have already endorsed Timothy Barr in the race.                                                                                                                                                                                                                                                  , Meanwhile, in Missouri, Trump's lack of endorsement in the crowded Senate primary has also become a source of consternation for some in his circle. Like Paxton, former Missouri Gov. Eric Greitens, who is leading the pack in most polls, has significant baggage that could alienate certain voters in a general election contest. Greitens resigned from office in 2018 in the midst of sexual misconduct allegations, an ethics probe and two criminal charges. Trump has heard from multiple allies who warn that Greitens could win the August primary if he doesn't intervene soon, according to a person familiar with the matter.                                               , So far, however, Trump doesn't appear to be interested in endorsing an alternative candidate in the primary. One of the Trump allies who spoke with him about the race said he spoke positively of Missouri Rep. Billy Long and Missouri Attorney General Eric Schmitt during a recent conversation but "wasn't gushing about either in a way that suggested he plans to endorse." In a statement to CNN, Greitens' campaign manager Dylan Johnson said the former Missouri governor "is the only true America First candidate in the race who will fight for President Trump's agenda." Johnson declined to address the pressure Trump is facing to endorse someone other than Greitens. ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Many Trump candidates struggling in money race                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Adding to Trump's endorsement heartburn, many of his congressional candidates are struggling to raise money -- whether they're challengers taking on members who voted to impeach or convict the former president for inciting the attack on the Capitol year, or incumbents like Rep. Alex Mooney of West Virginia or Mary Miller of Illinois, who are taking on GOP colleagues in redistricting battles.                                                                                                                                                                                                                                                                                , Harriet Hageman in Wyoming, Kelly Tshibaka in Alaska, John Gibbs and Steve Carra in Michigan, Joe Kent in Washington, Rep. Mo Brooks in Alabama, Miller and Mooney all lagged behind their GOP opponents' fourth quarter fundraising efforts. The Trump-aligned Save America PAC has donated $5,000 to Trump-endorsed candidates, but it has not made up the gap.                                                                                                                                                                                                                                                                                                                         , Tim Murtaugh, an adviser to the Trump-endorsed candidates Hageman and Tshibaka, said his candidates will have the resources required to win and dismissed their opponents' fundraising edge as war chests bankrolled by outsiders and elites.                                                                                                                                                                                                                                                                                                                                                                                                                                             , Other Trump allies said the endorsement alone is invaluable to a Republican candidate.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , "I think the value of the Trump endorsement through earned media, including his rallies and his name, will far outweigh whatever money they need to raise," said Randy Evans, Trump's former ambassador to Luxembourg.                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Meanwhile, Trump and his family have been ramping up their fundraising efforts. Last week, Donald Trump, Jr. held a fundraiser for Hageman. And on February 10, Trump will host a fundraiser for Tshibaka.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , While Trump has already hit the campaign trail to boost a few candidates whom he's endorsed, his rallies haven't had the overwhelming impact that some of those candidates had hoped.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , After Trump appeared alongside Brooks last August, one Alabama Republican said the event didn't result in a noticeable increase to Brooks' poll numbers nor did it seem to boost the number of Alabama voters who are aware that Brooks is Trump's preferred candidate in the Senate primary.                                                                                                                                                                                                                                                                                                                                                                                             , "Trump's biggest issue is letting people know who he has endorsed. The statements [from his Save America PAC] don't do all that much," said a second Trump ally, adding that "people care a lot less when you're no longer president."                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Brooks, however, said he's undoubtedly seen the benefits of being backed by Trump.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , "It is a Republican primary, and a President Trump endorsement is like gold and platinum put together," he told CNN.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Yet Trump's endorsement has not scared off other ambitious Republicans seeking higher office. Walker last week held a rally saying he's continuing to run for Senate, publicly refuting what he said was Trump's offer to drop out of the Senate race and run again for the House.                                                                                                                                                                                                                                                                                                                                                                                                        , "I don't look for places to draw points of contention," added Walker. "But I am my own guide when it comes to doing what we feel like is best or is in our heart."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , The lines for North Carolina House seats haven't been set, as the redistricting process has been tied up in court, creating uncertainty for any potential House candidate.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , One outside adviser to Trump said the former President was "annoyed" by Walker's refusal to exit the Senate primary but also understood that he was placed in a difficult spot.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , "Everyone kind of gets it," the Trump adviser said. "What's the guy supposed to do?"                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/milk </td>
   <td style="text-align:left;"> 2022-02-04 03:40:01 </td>
   <td style="text-align:left;"> Milk Hits 4-week High </td>
   <td style="text-align:left;"> Milk increased to a 4-week high of 20.49 USD/CWT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-02-04 03:32:56 </td>
   <td style="text-align:left;"> Crude Oil is up by 2.01% </td>
   <td style="text-align:left;"> Crude Oil WTI increased 2.01% to 90.03 USD/Bbl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/senate-committee-passes-bill-aimed/story.aspx?guid={6C9EE346-5CB5-47C9-B567-ABA4DC0D4098}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-04 03:30:07 </td>
   <td style="text-align:left;"> Senate committee passes bill aimed at Apple, Google's app stores - MarketWatch </td>
   <td style="text-align:left;"> The Senate Judiciary Committee on Thursday overwhelmingly passed a bill aimed at curtailing the market power of Apple Inc.'s 
        AAPL,
        -1.67%
       and Google parent Alphabet Inc.'s 
        GOOGL,
        -3.32%
        GOOG,
        -3.64%
       app stores. By a 20-2 vote, the committee pushed along the Open App Markets Act, with only Sens. John Cornyn, R-Texas, and Thom Tillis, R-N.C., in opposition. It is the second tech competition bill passed by the committee this year. Last month, the panel advanced the American Innovation and Choice Online Act, which would accomplish some of the same goals but is broader and could apply to Amazon.com Inc. 
        AMZN,
        -7.81%
       and Meta Platforms Inc. 
        FB,
        -26.39%
       as well. Both bills, which go to the full Senate, are intended to help developers led by advocates such as Epic Games Inc., Spotify Technology 
        SPOT,
        -16.76%,
       and Match Group Inc. 
        MTCH,
        -5.11%.
      , Here's what the chief executive of ARK Invest had to say.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Jon Swartz is a senior reporter for MarketWatch in San Francisco, covering many of the biggest players in tech, including Netflix, Facebook and Google. Jon has covered technology for more than 20 years, and previously worked for Barron's and USA Today. Follow him on Twitter @jswartz. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/03/technology/apple-privacy-changes-meta.html </td>
   <td style="text-align:left;"> 2022-02-04 03:18:59 </td>
   <td style="text-align:left;"> Meta Says Apple’s Privacy Changes Could Cost the Company $10 Billion - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Meta’s stock prices plunged after the company reported that Apple’s privacy features would cost it billions this year. It’s not the only tech giant to take a hit.                                                                                                                                                                                                                                                                                                                                                                   , Source: FactSet                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , By The New York Times                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , By Kate Conger and Brian X. Chen                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Apple’s vision of a more private web is not necessarily a more profitable one for internet companies that depend on advertising revenue.                                                                                                                                                                                                                                                                                                                                                                                             , That lesson was clear on Wednesday in an earnings report from Meta, the company that Mark Zuckerberg founded as Facebook. Meta said that privacy features introduced by Apple last year could cost Mr. Zuckerberg’s company $10 billion in lost sales this year.                                                                                                                                                                                                                                                                     , The news, along with increased spending as Meta tries to focus on the new idea of a metaverse, dropped Meta’s stock price more than 26 percent on Thursday morning. Mr. Zuckerberg said Wednesday that Apple’s changes and new privacy regulations in Europe represented “a clear trend where less data is available to deliver personalized ads.”                                                                                                                                                                                   , Meta’s warning and its cratering stock price were reminders that even among tech giants, Apple holds extraordinary sway because of its control of the iPhone. And the tech industry received a clear notice that a long-planned shift in how people’s information may be used online was having a dramatic impact on Madison Avenue and internet companies that have spent years building businesses around selling ads.                                                                                                             , “People can’t really be targeted the way they were before,” said Eric Seufert, a media strategist and author of Mobile Dev Memo, a blog about mobile advertising. “That breaks the model. It’s not just an inconvenience that can be fixed with a couple of tweaks. It requires rebuilding the foundation of the business.”                                                                                                                                                                                                          , Other internet companies that depend on ads felt the tremors, too. But smaller outfits appear to have been more nimble than Meta in their response to Apple’s changes.                                                                                                                                                                                                                                                                                                                                                               , Shares in Snap, which reported its fourth-quarter results on Thursday afternoon, fell about 17 percent earlier in the day. But prices bounced back in after-hours trading after the company said it made its first profit. The share prices of Twitter and Pinterest also dropped after Meta’s earnings report, but recovered in after-hours trading Thursday after Pinterest also reported better-than-expected earnings.                                                                                                           , Apple’s changes have far-reaching repercussions that may hurt consumers’ wallets, Mr. Seufert said, though consumers are overwhelmingly choosing not to be tracked. While Meta and other big media companies have developed new methods to target people with ads, some smaller brands, whose ads can no longer reach new customers, have found a different solution to the problem: raise prices.                                                                                                                                   , Apple made significant changes to the privacy settings of its mobile operating system last year, allowing iPhone users to choose whether advertisers could track them. Since Apple introduced the feature, a vast majority of iPhone users have opted to block tracking.                                                                                                                                                                                                                                                             , Only 24 percent of iPhone users around the world have consented to being tracked by advertisers, according to data published in December by the analytics company Flurry. That means that a broad swath of iPhone users are evading the personal tracking preferred by advertisers.                                                                                                                                                                                                                                                  , It has been a dismaying shift for advertisers, which have for years tracked people online in order to determine how many sales their clients were making. Advertisers also rely on tracking to resurface products that consumers have viewed but not yet purchased, reminding them that it might be time to buy. But for privacy activists, the change is a welcome check against surveillance that puts power back into the hands of everyday technology users.                                                                     , “We believe the impact of iOS overall is a headwind on our business in 2022,” said Dave Wehner, Meta’s chief financial officer, during a call with analysts on Wednesday. “It’s on the order of $10 billion, so it’s a pretty significant headwind for our business.”                                                                                                                                                                                                                                                                , Google has also made moves that disrupt the advertising industry. Last month, it announced a proposal for how Chrome, the world’s most widely used web browser, might eventually eliminate traditional tracking mechanisms for serving ads. It introduced a new system, Topics, which would inform advertisers of a user’s areas of interest — such as “fitness” or “autos and vehicles” — based on the last three weeks of the user’s web browsing history.                                                                         , Meta’s estimated loss because of these limits is comparable to what the company is losing on the metaverse. Meta said its pivot to the metaverse — which could in theory help it step away from Apple’s influence — was eating into its profit. The company views the metaverse as the next generation of the internet, in which people will share virtual experiences. It lost more than $10 billion in 2021 as it built the virtual reality goggles and smart glasses that will make it possible for users to access the metaverse., Although Meta said revenue rose 20 percent in the three months ending in December, to $33.7 billion, compared with the same period a year earlier, the company’s quarterly profits fell 8 percent, to $10.3 billion.                                                                                                                                                                                                                                                                                                                 , Mr. Wehner added that Apple’s iOS changes buoyed the ad business of Google, which is not dependent on Apple for advertising data.                                                                                                                                                                                                                                                                                                                                                                                                    , Snap, the maker of the Snapchat app and the augmented reality glasses Spectacles, said during its third-quarter earnings report in October that Apple’s privacy changes were having an unexpected impact on its business. But the company is adapting, Snap said in its fourth-quarter earnings report on Thursday, and the biggest impacts from Apple’s change may be behind it.                                                                                                                                                    , The origins. The word “metaverse” describes a fully realized digital world that exists beyond the one in which we live. It was coined by Neal Stephenson in his 1992 novel “Snow Crash,” and the concept was further explored by Ernest Cline in his novel “Ready Player One.”                                                                                                                                                                                                                                                       , An expanding universe. The metaverse appears to have gained momentum during the online-everything shift of the pandemic. The term today refers to a variety of experiences, environments and assets that exist in the virtual space.                                                                                                                                                                                                                                                                                                 , Some examples. Video games in which players can build their own worlds have metaverse tendencies, as does most social media. If you own a non-fungible token, virtual-reality headset or some cryptocurrency, you’re also part of the metaversal experience.                                                                                                                                                                                                                                                                         , How Big Tech is shifting. Facebook staked its claim to the metaverse last year, after shipping 10 million of its virtual-reality headsets and announcing it had renamed itself Meta. Google, Microsoft and Apple have all been working on metaverse-related technology.                                                                                                                                                                                                                                                              , The future. Many people in tech believe the metaverse will herald an era in which our virtual lives will play as important a role as our physical realities. Some experts warn that it could still turn out to be a fad or even dangerous.                                                                                                                                                                                                                                                                                           , “We are making solid progress,” said Jeremi Gorman, Snap’s chief business officer. The company offers its own measurement tools to advertisers to gauge the impact of their ads, and those tools are now used by more than 75 percent of its direct-response advertisers, Ms. Gorman said.                                                                                                                                                                                                                                           , In its earnings report, Snap said that it had exceeded analyst expectations for revenue and user growth. In the last three months of 2021, Snap’s revenue was $1.3 billion, a 42 percent increase from the same period a year ago. Daily active users grew to 319 million, a 20 percent increase. The company profit was $22.5 million.                                                                                                                                                                                              , Snap’s share price rebounded after the news, shooting up more than 50 percent in after-hours trading on Thursday.                                                                                                                                                                                                                                                                                                                                                                                                                    , In the last three months of the year, Pinterest’s revenue increased to $847 million, up 20 percent from the same period a year ago, the company said on Thursday. Its profit was $175 million, a 16 percent drop from 2020. Pinterest’s share price was up 29 percent in after-hours trading.                                                                                                                                                                                                                                        , In the past, Twitter has said that Apple’s privacy push caused minimal disruptions to its business because much of its advertising came from brand awareness campaigns and large events, like the Olympics, rather than targeted advertising. Twitter is set to report its fourth-quarter earnings on Feb. 10.                                                                                                                                                                                                                       , But Apple, which reported its fourth-quarter earnings last week, indicated that privacy was profitable. Despite supply chain disruptions, Apple said that sales of iPhones totaled $71.6 billion, up 9 percent from a year earlier. The smartphone maker reported an 11 percent increase in revenue and a 20 percent jump in profit.                                                                                                                                                                                                 , Apple has made privacy a key part of its marketing for the iPhone and other products, giving customers the ability to opt out of tracking and providing steps to make tracking more difficult in its browser, Safari. But Apple has continued to allow apps like Facebook to track users in aggregate, as long as they do not seek to personally identify users.                                                                                                                                                                     , Last year, Timothy D. Cook, Apple’s chief executive, making his company’s message clear, said that the advertising industry had become an ecosystem of “trackers and hucksters just looking to make a quick buck.”                                                                                                                                                                                                                                                                                                                   , Erin Griffith contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/oil-tops-90-7-year-high-gas-prices-aaa </td>
   <td style="text-align:left;"> 2022-02-04 03:15:13 </td>
   <td style="text-align:left;"> Oil tops $90, 7-year high </td>
   <td style="text-align:left;"> GasBuddy Head of Petroleum Analysis Patrick De Haan weighs in on rising energy prices and what that can mean for consumers.                                                                                                                                  , U.S. crude oil broke the $90-per-barrel mark Wednesday, the highest since October 2014.                                                                                                                                                                      , BIDEN ADMINISTRATION IS STOKING HIGH ENERGY PRICES                                                                                                                                                                                                           , Brent crude, the global benchmark, rose to $91 per barrel.                                                                                                                                                                                                   , Nationally, the average gas price reached $3.41 per gallon, a 7-year high, and energy experts, including GasBuddy's Patrick De Haan, say prices have a good chance of hitting $4 at the pumps.                                                               , The move comes one day after OPEC again snubbed requests from the United States to increase production to help quell inflation. The cartel determined at its January meeting it would continue along its path of a 400,000 barrel-a-day production increase. , INFLATION FUELS CAR PRICES AS INVENTORY FALLS                                                                                                                                                                                                                , ExxonMobil, Chevron and ConocoPhilips remained lower with the broader equity selloff.                                                                                                                                                                        , OIL HITS $89 AS OPEC STAYS CAGEY                                                                                                                                                                                                                             , Unrest between Russia and Ukraine is also pressuring prices, despite reports from the Biden Administration that a potential conflict was not likely "imminent."                                                                                              , CLICK HERE TO READ MORE ON FOX BUSINESS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-02-04 03:13:00 </td>
   <td style="text-align:left;"> Oil Above $90 For 1st Since 2014 </td>
   <td style="text-align:left;"> WTI crude futures pared early losses to jump more than 2% and traded above $90 per barrel on Thursday for the first time since September 2014 as investors expect that supply will tighten further even with OPEC+ announced it will stick with the plan of moderate increase their output. On Wednesday, OPEC+ agreed to raise oil output by 400,000 barrels per day in March, as widely expected, but analysts are increasingly doubtful that all its members will be able to meet their production targets. Investors are also closely monitoring developments over Ukraine, as a conflict between Russia and the West can potentially upend energy flows. Also, demand is upswing after the Omicron variant shock has just briefly dented the consumption in major economies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/03/business/media/olympics-nbc.html </td>
   <td style="text-align:left;"> 2022-02-04 03:11:34 </td>
   <td style="text-align:left;"> NBC Opens Olympics With ‘Worst Hand Imaginable’ - The New York Times </td>
   <td style="text-align:left;"> , The control room at NBC Sports studios in Stamford, Conn., where NBC is broadcasting its 2022 Winter Olympics coverage.Credit...Landon Speers for The New York Times                                                                                                                                                                                                                                                                                                                                            , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , By John Koblin                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , John Koblin has covered the media industry for more than a decade.                                                                                                                                                                                                                                                                                                                                                                                                                                              , Follow our latest coverage of the 2022 Winter Olympics.                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Last year, NBC Sports executives called the Tokyo Olympics their most challenging undertaking ever.                                                                                                                                                                                                                                                                                                                                                                                                             , Now that experience is starting to look like a cakewalk.                                                                                                                                                                                                                                                                                                                                                                                                                                                        , For this month's Winter Games in Beijing, NBC confronts an even trickier mix of challenges, threatening to diminish one of the network’s signature products and one of the last major draws to broadcast television.                                                                                                                                                                                                                                                                                            , The list of headaches is long: an event nearly free of spectators, draining excitement from the arena and ski slopes; the threat of star athletes testing positive for Covid, potentially dashing their Olympic dreams; and the vast majority of its announcers, including Johnny Weir and Tara Lipinski, offering color commentary from a network compound in Stamford, Conn., instead of China.                                                                                                               , The rising political tensions between the United States and China, including over China’s human rights abuses, add a troubling cloud to a typically feel-good spectacle.                                                                                                                                                                                                                                                                                                                                        , “My friends and colleagues at NBC have been dealt the worst hand imaginable,” said Bob Costas, who served as the network’s Olympics prime-time host for more than two decades.                                                                                                                                                                                                                                                                                                                                  , The success of the Games is critical to NBC. Even as streaming services like Netflix and Disney+ have lured millions of people from broadcast networks, sports have remained a reliable moneymaker. The company has exclusive broadcast rights to the Olympics through 2032, at a cost of $7.75 billion.                                                                                                                                                                                                        , Ratings for the Olympics have dipped in recent years — and fell sharply during last year’s Summer Olympics. NBC has told advertisers to expect the ratings to be lower than the 2018 Winter Olympics, according to three people familiar with the network’s ratings estimates.                                                                                                                                                                                                                                  , The Olympics, however, remain so central to the NBC brand that the five-rings logo has been affixed to the bottom-right-hand corner of its broadcasts for much of the last year.                                                                                                                                                                                                                                                                                                                                , And NBC Sports executives said they were up to the challenge to produce a compelling event.                                                                                                                                                                                                                                                                                                                                                                                                                     , “The good news, if there is good news, in dealing with live sports in a pandemic, is we have a ton of experience at this point,” said Pete Bevacqua, the chairman of NBC Sports. “Think about the last two years across our portfolio. We have become skilled out of necessity. We saw that in Tokyo, where we had an unbelievably large presence in Stamford.”                                                                                                                                                 , Mike Tirico, an NBC Sports anchor, is in Beijing and will host the first few days of coverage from China. Craig Melvin, an NBC News anchor, will be in Beijing as well, along with 600 other staff members on the ground.                                                                                                                                                                                                                                                                                       , But because of China’s Covid-19 restrictions, most of the sports commentators will be in Stamford, part of a crew of about 1,500 people there. And NBC will not have access to many aspects of the Games that viewers are accustomed to: charming travelogue segments about a host city; live shots of an athlete’s family and friends, who have traveled to a foreign country to see a loved one compete; commentators rushing up to a competitor who just scored gold.                                        , NBC will deploy workarounds, including setting up cameras in the homes of athletes’ family members to try to replicate a celebratory television moment that viewers expect to see. And in interviews, producers and executives said that NBC’s wealth of Olympic production experience would only help matters.                                                                                                                                                                                                 , “The replays will be there, the slow motion will be there, the graphics, all of that will be visually spectacular,” said Mike Weisman, a former longtime executive producer for NBC Sports who oversaw coverage of the 1988 Summer Olympics.                                                                                                                                                                                                                                                                    , Still, because of China’s strict virus-testing policy, there are many promotional benefits to other parts of NBC Universal that the company will have to forgo this year. For years, the NBC morning franchise, “Today,” as well as the “NBC Nightly News,” moved their broadcasts to the Olympic host city, providing a ratings lift in the process.                                                                                                                                                           , But this year, the “Today” anchors, Savannah Guthrie and Hoda Kotb, will stay in New York, the first time in nearly two decades that the morning show has not traveled for the Olympics. Lester Holt, the “NBC Nightly News” anchor, will also remain in New York.                                                                                                                                                                                                                                              , “Would you rather have ‘Today’ there? Yes,” said Jim Bell, a former executive producer of “Today,” as well NBC’s Olympics coverage from 2012 to 2018. “Would you rather have fans in the stands? You bet. Would you rather have Johnny and Tara and set them loose on the streets of Beijing? Of course. But if it comes down to you can’t have the Olympics because of the pandemic, it’s better than not having it.”                                                                                          , Politics is adding another twist. NBC executives usually bank on the Olympics as a politics-proof treat for viewers that transcends ideological differences. But even that bubble has been pierced. Last week, House Republicans sent a letter to NBC executives asking about the “the extent of influence” that the Chinese government will have over the network’s broadcast of the Games. In December, President Biden announced a diplomatic boycott of the Olympics because of China’s human rights abuses., “The circumstances put an inevitable damper on the whole thing,” Mr. Costas said. “The average person now fully understands the nature of the Chinese regime. It’s not something that just news nerds are aware of. This is broadly understood.”                                                                                                                                                                                                                                                                , Mr. Weisman, the former NBC Sports producer, said, “Especially being in China, I think it may not have the same feel-good celebration that had made the Olympics so special in the past.”                                                                                                                                                                                                                                                                                                                       , NBC said it would use Andrew Browne, an editorial director at Bloomberg and formerly the China editor at The Wall Street Journal, and Jing Tsu, a professor at Yale, to help provide analysis on China during the broadcasts.                                                                                                                                                                                                                                                                                   , “The world, as we all know, is a really complicated place right now,” Molly Solomon, the executive producer of NBC’s Olympics coverage, said in a news media briefing in January. “And we understand that there’s some difficult issues regarding the host nation. So our coverage will provide perspective on China’s place in the world and the geopolitical context in which these games are being held.”                                                                                                    , “But,” she continued, “the athletes do remain the centerpiece of our coverage.”                                                                                                                                                                                                                                                                                                                                                                                                                                 , NBC is also hoping that the Games can provide a boost for its fledgling streaming app, Peacock. The company is encouraging people to sign up for a paid version of the app that will show all the Olympic events live.                                                                                                                                                                                                                                                                                          , Executives have vowed to make Peacock easier to use this year after an outcry from subscribers who complained the streamer was a baffling mess for last year’s Summer Games.                                                                                                                                                                                                                                                                                                                                    , There is a bright spot for NBC: The network is guaranteed to get a ratings boost in the middle of the Olympics. On Feb. 13, NBC will broadcast the Super Bowl, and immediately after the presentation of the Vince Lombardi trophy, the network will go straight to Olympic coverage. In recent years, programs that followed the Super Bowl generally have drawn more than 20 million viewers.                                                                                                                 , With the Super Bowl gradually drifting later into February, this will be the first time that the two signature sporting events will overlap. NBC switched its spot with CBS in the Super Bowl broadcast rotation to ensure it could broadcast both events on the same day. NBC executives are calling it Super Gold Sunday.                                                                                                                                                                                     , “A once-in-a-lifetime moment,” Jenny Storms, NBCUniversal’s chief marketing officer for entertainment and sports, said last month.                                                                                                                                                                                                                                                                                                                                                                              , Mr. Bevacqua, the NBC Sports chairman, said he was hopeful that the Olympics, instead of being a downer, would be a tonic to viewers exhausted by the pandemic.                                                                                                                                                                                                                                                                                                                                                 , “Certainly there are challenges, and certainly there are harsh realities,” he said. “But I think the beauty of sports and the beauty of Olympic sports is really needed right now more than ever, and that’s the story we want to tell.”                                                                                                                                                                                                                                                                        , Mr. Costas said he expected NBC to be smart and resourceful. “But inevitably, no matter how good a job they do, those circumstances are going to have an impact,” he said.                                                                                                                                                                                                                                                                                                                                      , Tiffany Hsu contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60206564?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-04 03:09:39 </td>
   <td style="text-align:left;"> Don't ask for a big pay rise, warns Bank of England boss </td>
   <td style="text-align:left;"> This video can not be played                                                                                                                                                                                                                  , Workers should not ask for big pay rises, to try and stop prices rising out of control, the Bank of England governor has told the BBC.                                                                                                        , Prices are expected to climb faster than pay, putting the biggest squeeze on household finances in decades.                                                                                                                                   , Andrew Bailey said the Bank raised rates to 0.5% from 0.25% to prevent rising prices becoming "ingrained".                                                                                                                                    , Asked if the Bank was also implicitly asking workers not to demand big pay rises, he said: "Broadly, yes".                                                                                                                                    , Inflation is on course to rise above 7% this year, leaving households facing the biggest income squeeze in decades.                                                                                                                           , Post-tax incomes are forecast to fall 2% this year, after taking into account the rising cost of living.                                                                                                                                      , This represents the biggest fall in living standards since records began in 1990.                                                                                                                                                             , Workers are currently enjoying pay rises of just below 5% on average, according to a Bank survey.                                                                                                                                             , However, in sectors with big labour shortages, such as IT, construction and engineering firms have started paying workers "ad-hoc" bonuses in order to keep them.                                                                             , Mr Bailey said that while it would be "painful" for workers to accept that prices would rise faster than their wages, he added that some "moderation of wage rises" was needed to prevent inflation becoming entrenched.                      , Mr Bailey said: "In the sense of saying, we do need to see a moderation of wage rises, now that's painful. I don't want to in any sense sugar that, it is painful. But we need to see that in order to get through this problem more quickly.", In the year from 1 March 2020, Mr Bailey was paid £575,538 including pension.                                                                                                                                                                 , That is more than 18 times higher than the median annual pay for full-time employees of £31,285 for the tax year ending 5 April 2021.                                                                                                         , Inflation, as measured by the consumer prices index (CPI), is expected to peak at 7.25% in April, and average close to 6% in 2022.                                                                                                            , This would be the fastest price growth since 1991 and is well above the Bank's 2% target.                                                                                                                                                     , There are also increasing signs of broader price pressures across the economy.                                                                                                                                                                , Prices of household appliances such as fridges climbed almost 10% over the past year.                                                                                                                                                         , Goods shortages also meant retailers were offering fewer bargains in the January sales compared with previous years.                                                                                                                          , The price of services such as getting a haircut or a trip to the vet had also become more expensive as companies passed on higher wage costs to consumers, the Bank warned.                                                                   , Mr Bailey described the jobs market as "extraordinarily tight", adding that labour shortages were the "first, second and third thing people want to talk about" when he visited businesses across the country.                                , The Bank's Monetary Policy Committee that sets interest rates suggested that further rate rises would be needed "in the coming months" if the economy continued to bounce back from the slowdown caused by the Omicron variant,.              , However, Mr Bailey cautioned that the economic outlook was particularly "uncertain"                                                                                                                                                           , This may not necessarily be the start of a "long march upwards" in interest rates, he added.                                                                                                                                                  , The worst squeeze on the income of households since 1990 is what the Bank predicts.                                                                                                                                                           , Record energy bill rises from April will take inflation to a peak of 7.25% in April, more than treble the Bank's normal target.                                                                                                               , Some have called it "Black Thursday" for living standards.                                                                                                                                                                                    , In raising interest rates again and signalling more rate rises in the coming months, and nearly voting for even more on Thursday, the Bank is putting the nation on the couch in an exercise in mass psychology.                              , Inflation rises can be self-fulfilling. If workers, consumers and businesses expect 7% rises to persist, they will pre-emptively put up prices and ask for wage rises that then bring this about.                                             , What the Bank is trying to do is to confine what is happening right now to being a one-off shock.                                                                                                                                             , To stop the inflation becoming "ingrained" as Bank governor Andrew Bailey put it today.                                                                                                                                                       , There is a presentational issue here.                                                                                                                                                                                                         , In ordinary circumstances interest rates are raised to temper booming or bubbly growth - to take the punch bowl away from the party. But there is no punch bowl. There is no party.                                                           , In fact the Bank lowered its forecasts for growth of the economy to 3.75% from 5%, even though Omicron was not as damaging as feared.                                                                                                         , The Bank's answer is that this series of rate rises will be enough to stop a spiral of inflation, but will not go so high as to kill off the recovery. It is a delicate balancing act indeed.                                                 , When Ruby Wax met Pamela Anderson...                                                                                                                                                                                                          , Russell Kane and guests explore the life of Queen Elizabeth I...                                                                                                                                                                              , The story of the Holocaust through the eyes of remarkable 106-year-old Boris Pahor                                                                                                                                                            , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/russia-has-plan-faked-video/story.aspx?guid={614E642A-2B03-42A2-B2D7-D3AF1D01944D}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-04 02:14:43 </td>
   <td style="text-align:left;"> Russia has plan for faked video that would give pretext for invasion of Ukraine: reports - MarketWatch </td>
   <td style="text-align:left;"> U.S. officials have evidence that Russia has developed a plan to use a faked video to create a pretext for an invasion of Ukraine, according to multiple published reports Thursday citing unnamed American officials. The video likely would depict graphic scenes of a staged false explosion with corpses, actors depicting mourners, and images of destroyed locations and military equipment, and gear used in the fabricated attack will be made to look like it's Ukrainian or from allied nations, said a USA Today report. The White House last month had said Russia was mapping out a "false flag" incident in eastern Ukraine as a pretext to invade., Cryptocurrencies have taken a beating in the market in recent months, but the steady march toward an economy greased by virtual money continues apace.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Victor Reklaitis is MarketWatch's Money &amp; Politics reporter and is based in Washington, D.C. Prior to joining MarketWatch, he served as an assistant editor and reporter at Investor's Business Daily. Before IBD, he worked for several newspapers in Virginia. Follow Victor on Twitter at: @vicrek. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/03/republicans-grill-fed-nominee-raskin-over-past-views-on-climate-and-big-energy-companies.html </td>
   <td style="text-align:left;"> 2022-02-04 02:05:05 </td>
   <td style="text-align:left;"> Republicans grill Fed nominee Raskin over past views on climate and big energy companies </td>
   <td style="text-align:left;"> , Senate Republicans on Thursday peppered the nominee to be the Federal Reserve's top banking watchdog with questions over whether she would steer the institution into climate change and other areas outside of its mandate.                                                                                                                                                                                      , President Joe Biden put up Sarah Bloom Raskin to the post of vice chair for banking supervision, arguably the most important regulator for the industry.                                                                                                                                                                                                                                                          , Though Raskin said that previous writings from her that cast fossil fuels in an unfavorable light would not cause her to put the Fed "in the business of choosing winners and losers," GOP members of the Senate banking panel weren't convinced.                                                                                                                                                                 , "With respect to Ms. Raskin, I have to say this is one of the most remarkable cases of confirmation conversion I have ever seen, although she doesn't acknowledge the contradiction of what she has said today compared to the things she has been saying and writing for years," ranking Republican Sen. Patrick Toomey of Pennsylvania said.                                                                    , Toomey specifically pointed to commentary pieces Raskin authored that spoke of allocating capital away from fossil fuels businesses. In one May 2020 piece for The New York Times titled "Why Is the Fed Spending So Much Money on a Dying Industry?" Raskin discouraged the central bank from using its emergency lending powers deployed at the beginning of the Covid-19 pandemic to help big energy companies., "Climate change threatens financial stability; addressing it can create economic opportunity and more jobs," Rasking wrote then. "The decisions the Fed makes on our behalf should build toward a stronger economy with more jobs in innovative industries — not prop up and enrich dying ones."                                                                                                                  , Asked repeatedly whether her writings meant she would push banks not to lend money to fossil fuel companies, Raskin said doing so is beyond the Fed's purview.                                                                                                                                                                                                                                                    , Fed officials have said they are working with banks to update their planning to include financial impacts from climate-related events. There are no plans as of now to include those provisions in stress tests for large institutions.                                                                                                                                                                           , "It is not the role of the Federal Reserve to get engaged in favoring one sector," Raskin said. "I'm saying I view it as outside the bounds of the law. The Federal Reserve was set up by Congress and with particular mandates, and as a lawyer I live within those mandates."                                                                                                                                   , The hearing also was held to question economists Lisa Cook and Philip Jefferson, whom Biden also nominated to fill vacant positions on the Fed's Board of Governors.                                                                                                                                                                                                                                              , Cook in particular faced questions on her views on inflation and her resume, which Sen. Bill Hagerty, R-Tenn., accused Cook of embellishing.                                                                                                                                                                                                                                                                      , "Today's hearing is not just about vetting them," Toomey said. "It's really about the Fed's independence and whether or not we're going to abandon a core part of our democracy."                                                                                                                                                                                                                                 , But committee Chair Sen. Sherrod Brown, D-Ohio, said the Republican criticisms were politically fueled. He pointed out that Raskin, who already has served as a Fed governor, has breezed through previous confirmation hearings with bipartisan support.                                                                                                                                                         , "We have seen a coordinated effort by some to paint her as a radical," Brown said. "That characterization requires a suspension of common sense."                                                                                                                                                                                                                                                                 , The committee is expected to vote on the nominations, along with those of current Fed Chair Jerome Powell and Lael Brainard, a governor whom Biden seeks to promote to vice chair, later this month.                                                                                                                                                                                                              , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                            , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                            , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                  , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                  , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/nasdaq-selling-broad-heavy-calm/story.aspx?guid={A9731075-B879-48F4-BC74-37DA4DFEE961}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-04 01:40:07 </td>
   <td style="text-align:left;"> Nasdaq selling is broad and heavy but as calm as can be, Arms Index shows - MarketWatch </td>
   <td style="text-align:left;"> The selling on the Nasdaq exchange is certainly broad-based and heavy, as the Nasdaq Composite 
        COMP,
        -3.74%
       sinks 2.5%, but the Nasdaq Arms Index suggests sellers are fairly cool and collected. The Arms is a volume-weighted breadth measure that tends to rise above zero during down markets, as sellers often disproportionately focus on declining stocks. Many believe a rise above 2.000 in the Arms depicts panic-like behavior. For example, when the Nasdaq Composite tumbled 2.3% on Jan. 25, the Arms rose to 1.760; the last close above 2.000 was Dec. 7, 2018 when it closed at 2.200 and the Nasdaq Comp dropped 3.1%. Currently, the Arms is up to just 1.069; on Jan. 26, when the Nasdaq Comp rose less than 0.1%, the Arms was at 1.08. Currently, the number of declining stocks on the Nasdaq outnumbered advancers by 3.63 to 1, and volume in declining stocks outpaced advancing volume by 3.88 to 1., Yves Lamoureux, president of Lamoureux &amp; Co.  is back with a new call. Investors should start buying certain hard-hit stocks again, but be prepared for plenty of ups and downs.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-02-04 01:32:01 </td>
   <td style="text-align:left;"> Madrid Stocks Drop on Thursday </td>
   <td style="text-align:left;"> The IBEX 35 Index closed 0.3% lower at 8,689 on Thursday, as investors weighed hawkish stances in the ECB and BoE meetings. The ECB board signaled hawkish stances on the back of unanimous concerns of higher inflation, noting inflation outlook risk is on the upside, as President Lagarde declined to rule out rate hikes this year. The bank left its benchmark rate unchanged, while confirming its December decisions of reducing the pace of bond purchases under the PEPP and discontinuing the programme in March. Meanwhile, the BoE raised its benchmark rate by 25bps to 0.5% and voted to begin to reduce the stock of bond purchases. On the corporate front, BBVA (-21%) led the losses after reporting EUR 4.653 billion in profits during 2021, below market expectations while its fully loaded CET1 ratio came at 12.75%, a 173bps decrease from the previous quarter. At the same time, Siemens Gamesa fell 1.8% after reporting losses of EUR 400 million during the three months leading to December. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/belgium/producer-prices-change </td>
   <td style="text-align:left;"> 2022-02-04 01:24:09 </td>
   <td style="text-align:left;"> Belgium December Producer Inflation Slows </td>
   <td style="text-align:left;"> Belgium’s producer prices rose 30.8 percent year-on-year in December of 2021, down from a record 31.4 percent jump in the previous month. Prices slowed down for both the domestic market (38.8 percent vs 39 percent in November) and the foreign market (19.9 percent vs 20.9 percent). On a monthly basis, producer prices went up by 0.5 percent slowing from a 2.9 percent increase in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/uruguay/inflation-cpi </td>
   <td style="text-align:left;"> 2022-02-04 01:18:35 </td>
   <td style="text-align:left;"> Uruguay Inflation Rate Accelerates to 10-Month High </td>
   <td style="text-align:left;"> The annual inflation rate in Uruguay accelerated to 8.15 percent in January of 2022 from 7.96 percent in the previous month, marking the highest inflation rate since March of 2021. The main contribution came from prices of transport (13.16 percent), alcoholic beverages &amp; tobacco (11.86 percent), furniture &amp; articles for home (9.89 percent), miscellaneous of goods &amp; services (9.13 percent), and restaurants &amp; hotels (8.46 percent). On a monthly basis, consumer prices jumped 1.78 percent, after edging down 0.1 percent in the previous period. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/bce:cn </td>
   <td style="text-align:left;"> 2022-02-04 01:17:04 </td>
   <td style="text-align:left;"> BCE earnings above expectations at 0.76 CAD </td>
   <td style="text-align:left;"> BCE (BCE) released earnings per share at 0.76 CAD, compared to market expectations of 0.73 CAD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-02-04 01:14:00 </td>
   <td style="text-align:left;"> South African Stocks Snap 3-Day Winning Run </td>
   <td style="text-align:left;"> The FTSE/JSE All Share Index closed 0.2% down at 75,022 after a choppy session on Thursday, following three straight sessions of gains, pulled down by miners amid weaker commodity prices. Meanwhile, investors digested a mixed batch of earnings reports from US companies and concerns over tighter monetary policies along with geopolitical tensions. Domestically, investors continued to monitor South Africa's power situation, after state-owned utility Eskom had said on Wednesday it would implement power cuts until Monday because of breakdowns at some coal plants. On the data front, a Markit PMI survey showed South Africa's private sector returned to growth in January, after two straight months of declines. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-02-04 01:02:27 </td>
   <td style="text-align:left;"> Canada Stocks Down on Thursday </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, slipped almost 1% on Thursday mostly weighed down by tech stocks after downbeat earnings from US tech giant Meta Platforms rattled markets. Meanwhile, Bank of Canada Governor Macklem said there was uncertainty over when inflation would decline to the central bank’s comfort zone, due to the unique nature of the pandemic. On the earnings front, Suncor Energy missed Q4 FY21 profit expectations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/sarah-bloom-raskin-climate-views-confirmation-hearing </td>
   <td style="text-align:left;"> 2022-02-04 00:59:14 </td>
   <td style="text-align:left;"> Sarah Bloom Raskin grilled over controversial climate views during fiery confirmation hearing </td>
   <td style="text-align:left;"> Former Trump senior economic adviser Steve Moore discusses Fed nominee Sarah Bloom Raskin's belief that regulators have to take account of climate change.                                                                                                                                                                                                                                                                                                                                      , Republicans skewered Sarah Bloom Raskin, President Biden’s nominee to become the Federal Reserve's top banking regulator, over her climate regulation views, expressing concern that she could endanger the independence of the U.S. central bank.                                                                                                                                                                                                                                              , Raskin, who was formally tapped last month by Biden to serve as the Federal Reserve's vice chairwoman for supervision, faced a contentious hearing on Thursday before the Senate Banking Committee, where Republicans united in opposition against her nomination. She was joined by two academic economists – Lisa Cook and Philip Jefferson – who have been nominated to join the Fed's seven-person board.                                                                                   , REP. JAMIE RASKIN FAILED TO REPORT HUGE STOCK PAYOUT FOR HIS WIFE, A BIDEN FED NOMINEE                                                                                                                                                                                                                                                                                                                                                                                                          , GOP lawmakers pressed Raskin over some of her more controversial statements on challenges that climate change poses to the current financial system – and how she believes the Fed needs to respond.                                                                                                                                                                                                                                                                                            , Raskin has previously argued that all financial institutions should re-evaluate their relationships with energy companies and has advocated for a push toward sustainable investments that do not depend on carbon and fossil fuels. If banks and other financial institutions do not take these steps to distance themselves from fossil-fuel companies, Raskin has said, the Fed should penalize them.                                                                                        , Sen. Pat Toomey, the top Republican on the Senate Banking Committee, has long said that climate change falls under the purview of elected officials – not central banks – and warned of a "mission creep" in which the Fed starts operating beyond its defined mandate of stable prices and full employment. The Pennsylvania senator called the hearing on Thursday a "referendum" on the central bank's independence and ripped Raskin for her climate views, which he called "disqualifying.", Sarah Bloom Raskin, nominated to be vice chairman for supervision and a member of the Federal Reserve Board of Governors, is sworn in before a Senate Banking, Housing and Urban Affairs Committee confirmation hearing on Capitol Hill in Washington, Feb (Bill Clark/Pool via Reuters / Reuters Photos)                                                                                                                                                                                       , "Ms. Raskin’s proposals would have devastating consequences not just for energy workers, but also consumers, who’d pay much more for energy. On what basis could she justify this idea that the Fed exercise these extraordinary powers?" Toomey asked.                                                                                                                                                                                                                                         , Raskin appeared to try to get ahead of the criticism by stressing in her opening remarks that the role has no power to direct banks to make loans only to specific sectors, or to avoid making loans to particular sectors.                                                                                                                                                                                                                                                                     , But that didn't stop the unrelenting wave of criticisms lobbed at her by Republicans, who pushed her to explain her past remarks suggesting the Fed should penalize certain companies.                                                                                                                                                                                                                                                                                                          , "I've heard what you said this morning from your testimony," Toomey told her. "But from your repeated speeches, op-eds, podcasts, all kinds of sources, it seems very clear to me that you believe climate change is a very, very dire imminent threat… And that for those reasons, it is necessary and appropriate for financial regulators, including the Fed, to allocate capital away from those companies that are contributing the most to carbon in the atmosphere. Isn't that true?"    , Raskin maintained that she believed it is "inappropriate" for the Fed to make credit decisions and allocations based on "choosing winners and losers."                                                                                                                                                                                                                                                                                                                                          , "Banks choose their borrowers. The Fed does not," she told Toomey. "It is inappropriate for the Fed to choose winners and losers, and to do so is not the proper institutional role of the Fed. That is a cardinal principle of Fed supervision."                                                                                                                                                                                                                                               , Sarah Bloom Raskin is greeted by Sen. Pat Toomey prior to testifying before a Senate Banking, Housing and Urban Affairs Committee confirmation hearing on Capitol Hill in Washington, Feb. 3, 2022. (Reuters/Ken Cedeno/Pool / Reuters Photos)                                                                                                                                                                                                                                                  , The Washington policy stalwart faced a similar line of questioning from Sen. John Kennedy, R-La., who sounded the alarm over a May 2020 New York Times op-ed that Raskin penned titled "Why Is the Fed Spending So Much Money on a Dying Industry?" In the op-ed, Raskin criticized the federal government for including the oil and gas industries in initial $2.2 trillion coronavirus relief package and said the Fed should adopt a long-term approach that shifted away from fossil fuels. , "Did you mean it?" Kennedy asked.                                                                                                                                                                                                                                                                                                                                                                                                                                                               , SARAH BLOOM RASKIN OPPOSED BY 24 STATE FINANCIAL OFFICERS OVER 'RADICAL' VIEWS                                                                                                                                                                                                                                                                                                                                                                                                                  , Raskin repeated that the Fed should not be in the business of "picking winners and losers."                                                                                                                                                                                                                                                                                                                                                                                                     , As vice chair for supervision, Raskin – a Duke University law professor who has held high-level jobs at both the Treasury Department and the Fed – would oversee annual stress tests that review bank safety and liquidity. Her nomination has been welcomed by progressive senators and advocacy groups, who think she will take a tougher stance against Wall Street than her predecessor, Randal Quarles, a Trump nominee who stepped down last month.                                       , Raskin served on the Fed's board from 2010 to 2014 and was tapped by former President Barack Obama to serve as assistant Treasury secretary.                                                                                                                                                                                                                                                                                                                                                    , Sen. John Kennedy speaks during a Senate Banking, Housing and Urban Affairs Committee hearing on Sept. 28, 2021, in Washington. (Kevin Dietsch/Pool via AP / AP Images)                                                                                                                                                                                                                                                                                                                         , The White House has defended the nomination, with press secretary Jen Psaki telling reporters on Monday that Raskin brings "unprecedented experience and the support of economic experts across the spectrum" to this role.                                                                                                                                                                                                                                                                     , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                         , "She believes, and she has said she believes firmly in the independent role of the Federal Reserve and will work in concert with her colleagues to identify and mitigate a range of risks," Psaki said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/egypt/interest-rate </td>
   <td style="text-align:left;"> 2022-02-04 00:52:00 </td>
   <td style="text-align:left;"> Egypt Leaves Key Interest Rate Steady at 8.25% </td>
   <td style="text-align:left;"> The Central Bank of Egypt left its key overnight deposit rate steady at 8.25% on February 3rd, 2022, as expected. The policymakers noted that the rate remains consistent with achieving the inflation target of 7 percent (±2 percentage points) on average in 2022 Q4 and price stability over the medium term. Policymakers noted that annual inflation increased to 5.9% in December from 5.6% in November, resuming its upward trend since May 2021, but remained within the central bank's target range of 5-9%. The committee said that leading indicators point towards a continued expansion across most economic sectors and that domestic economic activity over the near-term is expected to be mainly driven by domestic demand and, in specific, gross domestic investments. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-02-04 00:50:23 </td>
   <td style="text-align:left;"> London Stocks Snap 2-Day Rally after BoE, ECB </td>
   <td style="text-align:left;"> The FTSE 100 fell 0.7% to close at 7,529 on Thursday, as investors digested a more hawkish policy stance from both the BoE and the ECB. The BoE raised rates by 25 bps as expected, including four votes for a steeper 50 bps hike, and will be tapering its £875 billion QE program by ceasing the reinvestment of proceeds from gilts and hiving off its stock of corporate bonds by next year. The ECB decided to stick to the slow tapering of bond purchases after the end of the PEPP in March, and dismissed any rate hike before the tapering ends, however, during the press conference, Lagarde declined to rule out an interest rate rise this year saying the bank would assess conditions very carefully. Reporting before the bell, communications firm BT showed a 2% decrease in 9M FY21 revenues, while profits after tax fell 31% to £886 million. Also, Shell reported better-than-expected full-year adjusted earnings billion and announced a share buyback program in the first half of the year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-02-04 00:47:00 </td>
   <td style="text-align:left;"> Italian Stocks Close Lower After ECB Meeting </td>
   <td style="text-align:left;"> The FTSE MIB Index fell 1.1% to close at 27,089 level on Thursday, amid hawkish stances by the ECB and BoE, while traders digested earning reports from Meta and Spotify in the United States. ECB policymakers signaled more hawkish stances on the back of unanimous concerns of higher inflation, as President Lagarde declined to rule out rate hikes this year. The central bank left its benchmark rate unchanged, while confirming its December decisions of reducing the pace of bond purchases under the PEPP and closing the programme in March. Meanwhile, the BoE hiked its benchmark rate by 25bps to 0.5% and announced a reduction in its bond purchases. On the corporate front, tech shares took the biggest losses from Meta’s earnings spillovers, led by STMicroelectronics (-4.1%). At the same time, Saipem (-6.4%) shares continued to plunge following its profit warning in the beginning of the week, amid new rumors that the oil refinery service provider could merge with Maire Tecnimont. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-02-04 00:46:00 </td>
   <td style="text-align:left;"> European Shares End Lower after ECB, BoE Meetings </td>
   <td style="text-align:left;"> European stocks closed lower on Thursday, as traders digested the monetary policy meetings from the European Central Bank and the Bank of England. The DAX lost 1.5% and the Stoxx 600 erased 1.8%, dragged down by a 3.4% drop in tech stocks, as downbeat earnings from US tech giant Meta rattled the sector. The ECB decided to stick to the slow tapering of bond purchases after the end of the PEPP in March, and dismissed any rate hike before the tapering ends, despite Eurozone inflation hitting a record high on Wednesday. The BoE raised interest rates 25 bps as expected, including four votes for a 50 bps hike, and announced the end of the QE program. On the earnings front, Shell beat full-year profit forecasts on higher oil prices and also announced share buybacks and raised dividends. Strong earnings also came from Germany’s Infineon, profiting from the global semiconductor chip shortage, and COVID-19 rapid test maker Siemens Healthineers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-02-04 00:45:00 </td>
   <td style="text-align:left;"> French Stocks Halt Rally </td>
   <td style="text-align:left;"> The CAC 40 Index closed 1.5% lower at 7,006 on Thursday, halting three consecutive sessions of gains, as traders weighed on hawkish stances from the ECB amid disappointing earnings from tech giants in the US. Comments from ECB policymakers signaled a hawkish turn by the bank amid unanimous concerns over higher inflation across the ECB’s board, while President Lagarde declined to rule out a rate hike this year stating future conditions would be carefully evaluated and be data dependent. The bank confirmed its policy decisions from its December meeting, reducing the pace of PEPP purchases before ending it in March. On the corporate front, Dassault Systemes lost 3.8% lower after the design software producer announced that 2022 revenue is forecasted to grow by EUR 5.3-5.35 billion, below market forecasts of EUR 5.36 billion. At the same time, Kering fell 2.9% after Jefferies downgraded its recommendation from “buy” to “hold”. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gasoline </td>
   <td style="text-align:left;"> 2022-02-04 00:45:00 </td>
   <td style="text-align:left;"> Gasoline at 7-year High </td>
   <td style="text-align:left;"> US gasoline futures extended a rally beyond $2.6 per gallon, following crude oil futures higher and touching the highest level since September 2014, on prospects of robust global demand. World stocks of oil products, which include gasoline, are at multi-year lows for this time of the year, which help boost gasoline refiners profit margins above the seasonal norm. Demand for the motor fuel is expected to reach pre-pandemic levels this year amid an increase in the number of cars circulating. Meanwhile, OPEC+ countries are expected to raise production targets by 400,000 bpd in March, despite failing to meet output existing targets in January. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/03/ken-griffins-citadel-flagship-hedge-fund-gains-nearly-5percent-during-januarys-tech-rout.html </td>
   <td style="text-align:left;"> 2022-02-04 00:42:25 </td>
   <td style="text-align:left;"> Ken Griffin’s Citadel flagship hedge fund gains nearly 5% during January's tech rout </td>
   <td style="text-align:left;"> , Billionaire investor Ken Griffin's hedge funds scored gains in January despite the tech rout that crushed the market, as the spike in volatility and steep sell-off in growth stocks created an ideal environment for fast-money traders.                                                                                                , Citadel's multistrategy flagship fund Wellington increased 4.71% last month, according to a person familiar with the returns.                                                                                                                                                                                                            , Citadel's global fixed income fund did even better with a 4.91% return, while its equities fund added 0.89% and its tactical trading strategy fund rose 1.79%, according to the source.                                                                                                                                                  , The firm's stellar performance came when wild price swings, driven in part by the Federal Reserve's hawkish policy pivot, gripped Wall Street. The S&amp;P 500 dropped more than 5% for its worst month since March 2020, while the tech-heavy Nasdaq Composite dipped into correction territory, falling more than 10% from its record high., In fact, the hedge fund industry as a whole fared well in the volatile January. All major hedge fund categories outperformed the overall market last month, with funds least correlated with the market delivering the strongest returns, according to data from Bank of America.                                                        , At the beginning of 2022, surging bond yields triggered hedge funds to sell growth-focused technology shares at a speed not seen in the past decade, according to Goldman Sachs' prime brokerage data.                                                                                                                                   , Tech stocks are seen as sensitive to rising yields because increased debt costs can hinder their growth and can make their future cash flows appear less valuable.                                                                                                                                                                       , Alpha is back with most hedge funds outperforming in January, Bank of America says                                                                                                                                                                                                                                                       , Retail investors are buying the January dip in force, especially these four stocks                                                                                                                                                                                                                                                       , The struggles now for Facebook are similar to 2018, so analysts think the stock should bounce back                                                                                                                                                                                                                                       , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                   , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                   , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                         , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                         , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                       , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-04 00:38:19 </td>
   <td style="text-align:left;"> French 10Y Bond Yield Rises to 2-Year High </td>
   <td style="text-align:left;"> The yield on the French 10-year OAT extended its rise to 0.6%, the highest in over two years, and in line with a general bond sell-off in Europe, amid hawkish stances by the ECB and the BoE. Comments from ECB policymakers signaled a hawkish turn by the bank amid unanimous concerns over higher inflation across the ECB’s board, while President Lagarde declined to rule out a rate hike this year stating future conditions would be carefully evaluated and be data dependent. The central bank confirmed decisions from December and will reduce bond purchases until the end of the PEPP in March. In the meantime, the Bank of England hiked its key Bank Rate by 25bps to 0.5%, as expected, and voted to reduce the stock of UK government bond purchases. Meanwhile, France’s government budget deficit shrank to EUR 171 billion in 2021 from EUR 178 billion the previous year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ghana/composite-pmi </td>
   <td style="text-align:left;"> 2022-02-04 00:34:00 </td>
   <td style="text-align:left;"> Ghana Private Sector Activity Growth Slows </td>
   <td style="text-align:left;"> The IHS Markit Ghana PMI decreased to 50.8 in January of 2022, from 51.8 in December, but still signaling an improvement in business conditions at the start of the year. New order growth remained solid, slowing only slightly from that seen in December as demand continued to improve. Employment and purchasing activity also rose further but output shrank for the first time in five months. Moreover, suppliers’ delivery times continued to improve amid competition among suppliers and clear requirements provided to vendors in terms of delivery needs. On the price front, inflationary pressure remained elevated. Looking ahead, sentiment improved to the second-highest in 15 months amid positive expectations regarding new orders. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-04 00:33:00 </td>
   <td style="text-align:left;"> Italian 10Y Bond Yield at 20-Month High </td>
   <td style="text-align:left;"> The yield on the Italian 10-year BTP soared to 1.6%, the highest since May of 2020, amid hawkish stances by the ECB and BoE. Comments from ECB policymakers signaled a hawkish turn by the bank amid unanimous concerns over higher inflation across the ECB’s board. In a press conference after the bank's decision, President Lagarde declined to rule out the possibility of hikes this year, as there are "no pledges without conditionalities". The central bank confirmed decisions from December and will reduce bond purchases until the end of the PEPP in March. In the meantime, the Bank of England hiked its key Bank Rate by 25bps to 0.5%, as expected, and voted to reduce the stock of UK government bond purchases. Meanwhile, Italy’s parliamentary budget office said it expects the Italian economy to expand by 3.9% in 2022, well below the entity’s previous forecast of 4.7% in September, mainly due to pandemic related restrictions implemented in the start of the year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/inflation-fuels-car-prices-as-inventory-dwindles </td>
   <td style="text-align:left;"> 2022-02-04 00:29:00 </td>
   <td style="text-align:left;"> Inflation fuels car prices as inventory dwindles </td>
   <td style="text-align:left;"> Lexus of Route 10 in New Jersey owner Tomas Maoli on what causing record-high new car prices.                                                                                                                                                                                                                                                                                                                    , After a year of record prices and fewer choices, the new car market is far from pumping the brakes in 2022.                                                                                                                                                                                                                                                                                                      , Not only are dealerships facing record-low inventory, but their customers are waiting six to nine months to get behind the wheel of their pricey new ride.                                                                                                                                                                                                                                                       , "They have no choice. They have to wait," Lexus of Route 10 owner Tomas Maoli told FOX Business’ Lydia Hu Thursday. "Most of the cars that we sell are not even delivered to the dealership yet."                                                                                                                                                                                                                , The average transaction price of new vehicles was expected to hit a record high in December, according to J.D. Power, of $45,743, the first time ever above $45,000 and 20% higher than the previous year.                                                                                                                                                                                                       , TESLA'S LATEST PRODUCT IS SOLD OUT                                                                                                                                                                                                                                                                                                                                                                               , "They're paying anywhere from 5 to $10,000 over MSRP because they need a vehicle," Maoli explained. "It's part of their lifestyle, right? And they need it, and so they're paying for it."                                                                                                                                                                                                                       , New car dealers have barely one-third of the normal number of car units – around 2 to 2.5 million, JD Power data shows.                                                                                                                                                                                                                                                                                          , FOX Business' Lydia Hu heads to NJ to talk with Lexus of Route 10 owner Tom Maoli about production and pricing issues in the auto industry.                                                                                                                                                                                                                                                                      , As surging car prices and growing inflation concerns push some buyers out of their budget comfort zone, semiconductor makers have been largely hindered by the pandemic.                                                                                                                                                                                                                                         , Orders for chips were canceled when automakers temporarily shut down factories at the height of the pandemic. In addition, the demand for chips increased at the same time in other industries because people were staying at home and needed additional electronics for work and play. The surge of microchip demand started when automakers restarted production, leaving chip manufacturers unable to keep up., GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                      , FOX Business' Lydia Hu visits Lexus of Route 10 in New Jersey where new car buyers can expect to wait up to a year for their new ride.                                                                                                                                                                                                                                                                           , Maoli said he believes car prices won’t slow down until 2023. This comes as Biden is accusing Republicans of wanting people to be too poor to afford cars.                                                                                                                                                                                                                                                       , The president’s proposal to fix the problem is to "increase the supply of cars by making more of them," but global supply chain backlogs continue to drag chip and auto production.                                                                                                                                                                                                                              , READ MORE FROM FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                      , The Associated Press contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-02-04 00:28:55 </td>
   <td style="text-align:left;"> Oil Erases Early Losses but Volatility is Set to Continue </td>
   <td style="text-align:left;"> WTI crude futures pared early losses to trade around $88 per barrel on Thursday but volatility is set to continue as investors weigh the outlook for production and possible interruptions to supply. OPEC+ agreed on Wednesday to raise oil output by 400,000 barrels per day in March, as widely expected, but analysts are increasingly doubtful that all its members will be able to meet their production targets. Investors are also closely monitoring developments over Ukraine, as a conflict between Russia and the West can potentially upend energy flows. Meanwhile, data showed US crude inventories fell last week while gasoline inventories were up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/03/business/media/jeff-zucker-allison-gollust-cnn.html </td>
   <td style="text-align:left;"> 2022-02-04 00:24:08 </td>
   <td style="text-align:left;"> ‘Joined at the Hip’: Jeff Zucker’s Relationship With a Top CNN Executive - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Allison Gollust, an executive vice president, has worked alongside Mr. Zucker for two decades. He cited their relationship as he abruptly resigned.                                                                                                                                                                                                                                                                                                                                                                                                                          , By John Koblin and Michael M. Grynbaum                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Jeff Zucker’s tenure as president of CNN ended in an abrupt fashion on Wednesday just days after he acknowledged to company lawyers what had long been rumored in television news circles: He was in a romantic relationship with the person he has described as his closest professional colleague, Allison Gollust.                                                                                                                                                                                                                                                        , Ms. Gollust, 49, is CNN’s executive vice president and chief marketing officer, although those titles only hint at her influence: As one of the network’s senior leaders, she is closely involved in business and communications strategy. She also served as Mr. Zucker’s chief spokeswoman, fiercely defending him as he battled then-President Donald J. Trump, contended with corporate rivals and navigated ethics scandals.                                                                                                                                            , She has worked alongside Mr. Zucker for more than 20 years, starting as a senior publicist at NBC’s “Today” show in 1997, when Mr. Zucker — then a wunderkind executive producer in his early 30s — was sending the morning program to phenomenal ratings heights.                                                                                                                                                                                                                                                                                                           , Their relationship is now central to the question of why Mr. Zucker, 56, was forced by WarnerMedia, CNN’s parent company, to step down so suddenly from his job of nine years. CNN is weeks away from starting a subscription streaming platform, and WarnerMedia is on the verge of a major acquisition by Discovery Inc.                                                                                                                                                                                                                                                   , For CNN staff members, Mr. Zucker’s resignation after failing to disclose the relationship, as required by the company’s standards policy, was a surprise. Many journalists and producers at CNN have expressed confusion, even on the air, about why a consensual relationship between two divorced colleagues — one a network president, the other a high-ranking executive — would precipitate the dramatic move.                                                                                                                                                         , WarnerMedia’s standards policy states that personal relationships must be disclosed immediately to “avoid a conflict of interest,” particularly if one of the people is in a “position to influence” a career track.                                                                                                                                                                                                                                                                                                                                                         , It was abundantly clear to colleagues and friends that Mr. Zucker and Ms. Gollust often traveled and functioned together as a unit.                                                                                                                                                                                                                                                                                                                                                                                                                                          , In recent years, it was rare for Mr. Zucker to appear at public events without Ms. Gollust at his side. They sat beside one another at White House Correspondents’ Association dinners, industry galas like the Peabody Awards, glitzy events at the old Four Seasons restaurant, and, last fall, a Billy Joel concert at Madison Square Garden, which they attended with a group of CNN colleagues, including the hosts Don Lemon and Fareed Zakaria.                                                                                                                       , Colleagues who encountered Mr. Zucker in the halls of CNN’s Midtown Manhattan offices would be sure to see Ms. Gollust following a few feet behind, if not already engaged in a “West Wing”-style walk-and-talk with Mr. Zucker. The impression, colleagues said, was that the two ran the network more or less as a unit, puzzling together over most major decisions affecting the future of CNN.                                                                                                                                                                          , It was a pattern that dated back to earlier chapters of Mr. Zucker’s career at NBCUniversal, where Ms. Gollust first emerged as his most trusted aide-de-camp.                                                                                                                                                                                                                                                                                                                                                                                                               , “They were joined at the hip,” the former “Today” anchor Katie Couric wrote about Mr. Zucker and Ms. Gollust in her 2021 memoir, “Going There.”                                                                                                                                                                                                                                                                                                                                                                                                                              , When both were still married to their respective spouses, Mr. Zucker and Ms. Gollust lived for several years in the same luxury co-op apartment building on Manhattan’s Upper East Side; Ms. Gollust and her family lived one floor above the Zuckers.                                                                                                                                                                                                                                                                                                                       , Office relationships are not uncommon in the high-pressure world of TV news, and rumors of a potential romance between the two proliferated, especially after their divorces. Mr. Zucker and his wife, Caryn, divorced in 2017; The New York Post reported that Ms. Gollust and her husband filed for divorce in 2015.                                                                                                                                                                                                                                                       , But the rumors stayed only rumors, until Wednesday.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Jason Kilar, the chief executive of WarnerMedia who informed Mr. Zucker that he would have to resign, told CNN journalists at a meeting in its Washington bureau on Wednesday that he was “not aware of the relationship” before the recent events. Mr. Kilar would not specify when he first learned of it, but he acknowledged that the relationship emerged as part of CNN’s investigation into the tenure of Chris Cuomo, the star anchor who was fired last year for advising his brother, then-Gov. Andrew M. Cuomo, on how to deal with sexual harassment accusations., In his memo on Wednesday announcing his resignation, Mr. Zucker put it this way: “The relationship evolved in recent years.” Ms. Gollust, in her own statement, wrote: “Recently, our relationship changed during Covid.”                                                                                                                                                                                                                                                                                                                                                    , Ms. Gollust said she would remain at CNN.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , At NBC — where Mr. Zucker was first president of its entertainment division, and then chief executive of NBCUniversal — Ms. Gollust took on significant responsibilities. She oversaw communications for NBC News, MSNBC, CNBC and the Weather Channel, and then moved into an executive communications role at NBC Universal.                                                                                                                                                                                                                                               , In 2011, after Mr. Zucker was ousted from NBC Universal, he became an executive producer for a new daytime talk show being developed for Ms. Couric at ABC. Mr. Zucker made a “huge push to bring on” Ms. Gollust to handle public relations for the show, Ms. Couric wrote in her book. She recalled telling Mr. Zucker that she had already hired someone for the role, and that Mr. Zucker urged her to meet with Ms. Gollust anyway.                                                                                                                                     , “I had to wonder why Jeff was angling so hard to bring Allison on board,” Ms. Couric wrote. “She and her husband and kids had moved into the apartment right above Jeff and Caryn’s — everyone who heard about the cozy arrangement thought it was super-strange. By that point, Caryn had become a close friend and it made me really uncomfortable.”                                                                                                                                                                                                                       , Ms. Couric wrote that she told Ms. Gollust that there was no job for her.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , By late 2012, Ms. Gollust had signed on to become communications director for Andrew Cuomo, then New York’s governor.                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Shortly after she started working with Mr. Cuomo, Mr. Zucker was named the next president for CNN. Ms. Gollust left her job with Mr. Cuomo after four months to rejoin Mr. Zucker and lead communications for CNN.                                                                                                                                                                                                                                                                                                                                                           , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/uk-natural-gas </td>
   <td style="text-align:left;"> 2022-02-04 00:14:46 </td>
   <td style="text-align:left;"> UK Gas is up by 5.18% </td>
   <td style="text-align:left;"> Natural Gas UK GBP increased 5.18% to 193.43 GBp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/vista-outdoor-stock-rises-after/story.aspx?guid={45FA7D90-CD29-41E3-8391-5577BB752870}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-04 00:10:04 </td>
   <td style="text-align:left;"> Vista Outdoor stock rises after record sales, guidance increase, $200 million share buyback program - MarketWatch </td>
   <td style="text-align:left;"> Vista Outdoor Inc. 
        VSTO,
        -0.18%
       shares rose 1.3% in Thursday trading after the outdoor and sporting company reported record fiscal third-quarter sales. Net income totaled $118.1 million, or $2.00 per share, up from $78.9 million, or $1.31 per share, last year. Adjusted EPS of $2.10 beat the FactSet consensus of $1.92. Sales of $794.7 million reached a record, according to the company. The result was up from $574.7 million last year and exceeded the FactSet consensus of $748.1 million. "Two years into the pandemic, people continue to find enjoyment in their newly acquired and rediscovered outdoor passions," said chief Executive Chris Metz in a statement. "We continue to see increasing levels of activity and participation across outdoor recreation whether it be golfing, camping, hiking, biking, hunting or recreational shooting." Vista brands include CamelBak, Bushnell and Camp Chef. The company recently acquired Stone Glacier, a hunting gear company. This marks the seventh acquisition in 18 months. Vista has reorganized its reporting segments, with Sports Protection, Cycling and Hydration part of the Outdoor Products segment, and the Sporting Products segment comprised of ammunition-related businesses. Vista has authorized a new $200 million share buyback program, which comes nearly at the completion of the previous program. For fiscal 2022, Vista is guiding for sales in the range of $2.97 billion to $3.00 billion, EPS in the range of $7.82 to $7.92 and adjusted EPS of $8.00 to $8.10. The FactSet consensus is for sales of $2.94 billion and EPS of $7.92. Vista stock is up 27.8% over the last year while the S&amp;P 500 index 
        SPX,
        -2.44%
       is up 18.4%., A dismal outlook and weaker-than-expected earnings from Facebook's parent company is weighing on other social-media and tech stocks.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Tonya Garcia is a MarketWatch reporter covering retail and consumer-oriented companies. You can follow her on Twitter @tgarcianyc. She is based in New York. Tonya joined MarketWatch from Moguldom Media, where she was business editor for MadameNoire, a website targeting African-American women with a range of content from personal finance to economics, politics, education and lifestyle and entertainment.  She also worked at Mediabistro, and previously handled media relations for MSLGroup’s consumer practice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2022-02-04 00:07:57 </td>
   <td style="text-align:left;"> Gold Holds around $1800 on Hawkish ECB and BoE </td>
   <td style="text-align:left;"> Gold prices hovered around $1800 an ounce for the third session on Thursday as investors weigh prospects of a faster tightening from central banks around the world against jitters of persistently high inflation and geopolitical concerns in Ukraine. The ECB set a more hawkish tone during its February meeting and President Lagarde did not rule out a rate hike this year. Also, the BoE delivered another rate hike but almost half of policymakers wanted an even bigger increase and the Fed will likely start raising the fed funds rate next month. At the same time, central banks noted inflation is likely to remain hot for longer than expected. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/malawi/interest-rate </td>
   <td style="text-align:left;"> 2022-02-04 00:04:00 </td>
   <td style="text-align:left;"> Malawi Holds Interest Rate Steady at 12% </td>
   <td style="text-align:left;"> The Reserve Bank of Malawi kept its benchmark policy rate unchanged at a record low of 12% at its first meeting of 2022 held on 2nd and 3rd February, saying the decision was appropriate at this time, to allow for continued economic recovery. Meanwhile, policymakers noted that, although inflation pressures are mounting, the sources were considered transitory and likely to dissipate. The annual inflation rate in Malawi quickened to a two-year high of 11.5% in December of 2021, driven by both food and non-food prices. Pressures on inflation are likely to continue, mainly arising from a seasonal increase in prices of domestically produced food items, and imported inflation. Accordingly, the central bank revised upwards its inflation forecasts for 2022 to 10.4%, from an earlier forecast of 8.9%. The economy is projected to grow by 4.1% in 2022, driven by both the agricultural and non-agricultural sectors, despite the uncertainty regarding the COVID-19 pandemic and the recent cyclone Ana. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2022-02-04 00:00:00 </td>
   <td style="text-align:left;"> Dollar Weakens Further After ECB, BoE Meetings </td>
   <td style="text-align:left;"> The dollar index weakened further to around 95.4 on Thursday, extending losses for 4th consecutive session after a more hawkish policy stance from both BoE and ECB.  The BoE hiked its borrowing costs by 25 bps, as expected, although almost half of its policymakers voted to a bigger increase of 50 bps to tame inflation. Meanwhile, the ECB maintained key interest rates at record low levels in February 2022 and pledged to reduce steady its bond purchases this year, despite a record rise in inflation. Still, during the press conference, Lagarde declined to rule out an interest rate rise this year saying the bank would assess conditions very carefully. Domestically, investors await the highly-anticipated US nonfarm payroll report due tomorrow, while new job claims data fell more than expected as COVID-19 infections subsided, suggesting an anticipated slowdown in job growth in January was likely temporary. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-03 23:59:00 </td>
   <td style="text-align:left;"> UK Bond Yields Soar after BoE Decision </td>
   <td style="text-align:left;"> The yield on the UK 10-year government bond soared to 1.37%, the highest since December of 2018 after the BoE delivered another interest rate hike as expected but nearly half of policymakers voted for an even bigger rate increase. The Bank of England Governor said "We have not raised interest rates today because the economy is roaring away. An increase in Bank Rate is necessary because it is unlikely that inflation will return to target without it". UK inflation soared to 30-year highs in December. Money markets now expect the central bank to raise the bank rate by a total of 1.5% this year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/currency </td>
   <td style="text-align:left;"> 2022-02-03 23:55:00 </td>
   <td style="text-align:left;"> South African Rand Recovers </td>
   <td style="text-align:left;"> The South African rand was slightly higher around 15.3 against USD on Thursday, after having hit 15.4 early in the session, its lowest since January 31, amid a softer dollar and despite heightened domestic risks due to continued scheduled power cuts. South Africa’s economy has been hit by energy shortages as power utility Eskom struggles to address long-standing operational and financial challenges, with the emergency program to add generation from private producers experiencing multiple delays. At the same time, the country's economic outlook remains fragile amid ongoing concerns around the evolution of the pandemic, higher inflation and interest rates and policy uncertainty. Also, the prospect of a faster policy tightening by the US Federal Reserve and worries about a potential military conflict in Eastern Europe limited further gains. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/eu-natural-gas </td>
   <td style="text-align:left;"> 2022-02-03 23:45:30 </td>
   <td style="text-align:left;"> EU Natural Gas Stable as Supply Woes Fade </td>
   <td style="text-align:left;"> EU natural gas prices hovered below €80 per megawatt-hour on Thursday, as traders continued to monitor the bloc’s contingency plans regarding supplies, while milder weather provided relief to regional inventories. Oil and gas Dutch giant, Shell, pledged to help ease a potential energy crisis if Russian energy exports are halted, admitting to also diverting cargoes headed elsewhere to Europe. Meanwhile, warmer temperatures throughout the continente dampened heating demand, taking pressure off of utilities as LNG imports continued to arrive at European ports, giving firms a chance to possibly restock up to normal levels by the end of the month. Strong winds have also boosted power generation from alternative sources, with the UK’s wind farms producing record amounts of electricity in recent days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/paraguay/inflation-cpi </td>
   <td style="text-align:left;"> 2022-02-03 23:43:52 </td>
   <td style="text-align:left;"> Paraguay Inflation Rate at Over 10-Year High </td>
   <td style="text-align:left;"> The annual inflation rate in Paraguay accelerated to 7.9 percent in January of 2022 from 6.4 percent in the previous month and marked the highest inflation rate since May of 2011 when consumer prices rose 10.2 percent. Costs rose at a faster pace for food (14.1 percent vs 12.3 percent), services (2.8 percent vs 2.2 percent), and housing (1.2 percent vs 1.1 percent). On a monthly basis, consumer prices jumped 1.5 percent after being unchanged in the previous period. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/eia-reports-smaller-than-expected-weekly-fall/story.aspx?guid={454919DE-DA7B-422E-BF2A-E6DE42DF9BFA}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-03 23:40:04 </td>
   <td style="text-align:left;"> EIA reports a smaller-than-expected weekly fall in U.S. natural-gas supplies - MarketWatch </td>
   <td style="text-align:left;"> The U.S. Energy Information Administration reported on Thursday that domestic natural-gas supplies fell by 268 billion cubic feet for the week ended Jan. 28. That compared with the average decline of 274 billion cubic feet forecast by analysts polled by S&amp;P Global Platts, which pegged the five-year average supply fall for the period at 150 billion cubic feet. Total stocks now stand at 2.323 trillion cubic feet, down 393 billion cubic feet from a year ago and 143 billion cubic feet below the five-year average, the government said. Following the data, March natural gas 
        NGH22,
        +2.93%
      extended its decline, trading down by 56 cents, or 10.2%, at $4.941 per million British thermal units. Prices were at $4.989 shortly before the data. , Amazon.com Inc. is increasing the price of its Prime subscription service for the first time since 2018.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-02-03 23:39:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index Edges Up </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index went up 0.4% to 1,425 on Thursday, after a 1.5% drop in the previous session, amid an uptick in demand across all its vessel segments. "The Chinese New Year and the celebration of the Tiger has put a lid on activity levels, but expectations are positive for the near future when the holiday comes to an end," shipbroker Fearnleys said. The capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, rose 0.9% to 1,291; and the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, increased 6 points to 1,771, ending a seven-session losing streak. Among smaller vessels, the supramax index rose 1 point to 1,571, the first gain since December 13th. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/03/politics/military-soldiers-vaccine-mandate-discharge/index.html </td>
   <td style="text-align:left;"> 2022-02-03 23:36:42 </td>
   <td style="text-align:left;"> US Army to begin discharging soldiers who refuse Covid-19 vaccination - CNNPolitics </td>
   <td style="text-align:left;"> Washington (CNN)The US Army will begin discharging soldiers who refuse to be vaccinated against the coronavirus, unless the service member has an approved exemption or pending request.                                                                                                                                                                                                             , "Army readiness depends on Soldiers who are prepared to train, deploy, fight and win our nation's wars," Army Secretary Christine Wormuth said in a statement Wednesday. "Unvaccinated Soldiers present risk to the force and jeopardize readiness. We will begin involuntary separation proceedings for Soldiers who refuse the vaccine order and are not pending a final decision on an exemption.", The order applies to "Army Soldiers, reserve component Soldiers serving on Title 10 active-duty, and cadets," according to the Army.                                                                                                                                                                                                                                                                 , Soldiers discharged due to vaccine refusal "will not be eligible for involuntary separation pay and may be subject to recoupment of any unearned special or incentive pays," the Army said.                                                                                                                                                                                                          , The Army reported a 96% vaccine completion rate for active duty soldiers and a 79% completion rate for reservists as of January 26. Data released at the time showed that six regular Army leaders, including two battalion commanders, were relieved of duty and 3,073 soldiers were issued written reprimands for refusing the vaccination order.                                                  , The recent move is the latest in the military's efforts to bolster its vaccine mandate that was first introduced by the Pentagon in August 2021. CNN previously reported in December that the US Marine Corps had discharged 103 service members for refusing to take the Covid-19 vaccine.                                                                                                          , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/03/football/honduras-players-forced-off-world-cup-qualifier-usmnt-spt-intl/index.html </td>
   <td style="text-align:left;"> 2022-02-03 23:36:14 </td>
   <td style="text-align:left;"> Honduras players forced off due to 'extreme climate conditions' in World Cup qualifier against US - CNN </td>
   <td style="text-align:left;"> (CNN)Two players for the Honduras national team were forced off at halftime in Wednesday's 3-0 World Cup qualifying defeat to the US due to "extreme climate conditions," the federation said.                                                                                                                                                  , In total, three players -- Luis Lopez, Romell Quioto and Diego Rodriguez -- were substituted during the interval as the temperature at Minnesota's Allianz Field stadium reportedly dropped to one degree Fahrenheit (minus 17 degrees Celsius) when the match kicked off, with a wind chill of minus 14 degrees Fahrenheit (minus 25.5 Celsius)., "Two players of the national team did not return to the second half of the qualifying game against the USA due to the extreme weather conditions prevailing in the stadium," the Honduras football federation wrote on Twitter.                                                                                                                  , The US has come in for criticism for moving the match to Minnesota, with Honduras head coach Hernan Dario Gomez calling it an "inconceivable" decision.                                                                                                                                                                                          , READ: Christian Eriksen joins Brentford after suffering cardiac arrest at Euro 2020                                                                                                                                                                                                                                                              , "It's a match that is not going to dictate many things to me," Gomez said after the game. "It's unusual, inconceivable that a powerful team in every sense of the word would bring you here to play a match to get a result.                                                                                                                     , "I have the boys in the dressing room in discomfort, there are some on IV drips. Football is not for suffering. Playing like this is no good."                                                                                                                                                                                                   , However, US head coach Gregg Berhalter said that his players regularly have to contend with stifling conditions when they travel abroad to play World Cup qualifiers.                                                                                                                                                                            , "When we go down to those countries, it's 90 degrees and 90% dew point and it's unbearable humidity and guys are getting dehydrated and cramping up and getting heat exhaustion, that's the nature of our competition," he said.                                                                                                                 , "When we schedule this game in this location, you have to go by average temperatures, daily average temperatures, and it was the best guess. We want to minimize travel. We knew we were going to be playing in cold weather in two of the games and we figured to do it in the third game as well, instead of switching climates.               , "The cold spell came through and it's something we can't control but all we can do once that happens is try to mitigate the risk by having warm weather gear and going out there and competing and we did that."                                                                                                                                 , Berhalter added that the federation provided Honduras' players and staff -- and the officiating team -- with warm weather gear "to make it a safe environment for them to play."                                                                                                                                                                 , The result was a much-needed win for the US as it remains in the second automatic qualifying spot, extending its lead over Panama -- which lost to Mexico -- in the playoff place to four points.                                                                                                                                                , Honduras remains bottom of the CONCACAF group with just three points.                                                                                                                                                                                                                                                                            , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/currency </td>
   <td style="text-align:left;"> 2022-02-03 23:24:17 </td>
   <td style="text-align:left;"> South Korean Won Holds Ground Near 20-Month Low </td>
   <td style="text-align:left;"> The South Korean won traded around the 1,200 per USD mark, not far from a 20-month low of 1,209.56 per USD reached on January 28th, underperforming its regional peers. The won’s performance reflects the culmination of a 13-month long bearish run fueled by prospects that the US Fed will outpace the Bank of Korea’s tightening cycle. Looking ahead, the easing of global semiconductor chip shortage, likely to unfold in the latter half of 2022, could further pressure the won, as foreign holders of shares in the Korean chip manufacturing industry sell their positions. Conversely, expectations that more developed nations will classify the coronavirus as endemic could lift risk appetite and provide some support to the currency. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/factory-orders </td>
   <td style="text-align:left;"> 2022-02-03 23:12:00 </td>
   <td style="text-align:left;"> US Factory Orders Fall More than Expected </td>
   <td style="text-align:left;"> New orders for US manufactured goods dropped by 0.4 percent from a month earlier in December of 2021, the first monthly decrease since April 2021 and the steepest since April of 2020, above market expectations of a 0.2 percent decline. Demand for transport equipment was down by 3.7 percent (vs 8.2 percent in November), pressured by civilian aircraft (-14.4 percent vs 42 percent), defense aircraft (-11.2 percent vs 7.6 percent), and motor vehicle bodies, parts, and trailers (-1.1 percent vs 0.2 percent). Orders also fell for computers and electronic products (-2.7 percent vs 4.2 percent), led by nondefense communications equipment (-6.6 percent vs 11.4 percent) and electronic components (-1.7 percent vs 1.8 percent). Excluding transportation, factory orders edged up 0.1 percent, easing from a 0.8 percent increase in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/non-manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-02-03 23:05:00 </td>
   <td style="text-align:left;"> US Services Sector Slows Less than Expected: ISM </td>
   <td style="text-align:left;"> The ISM Services PMI for the US fell to 59.9 in January of 2022 from 62.3 in December, pointing to the slowest growth in the services sector since February of 2021. Still, figures came slightly above market forecasts and remained well above the long-run average of 55. Smaller increases were seen in production (59.9 vs 68.3), new orders (61.7 vs 62.1), employment (52.3 vs 54.7) and supplier deliveries (65.7 vs 63.9) while price pressures also eased (82.3 vs 83.9). "Companies continue to be impacted by coronavirus pandemic-related supply chain issues, including capacity constraints, demand-pull inflation, logistical challenges and labor shortages. Moreover, the COVID-19 omicron variant has disrupted operations, especially through reduced staffing levels. Despite these impediments, business activity and economic growth continue”, Anthony Nieves, Chair of the ISM said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/composite-pmi </td>
   <td style="text-align:left;"> 2022-02-03 22:58:56 </td>
   <td style="text-align:left;"> US Composite PMI Falls Less than Anticipated </td>
   <td style="text-align:left;"> The IHS Markit US Composite PMI was revised slightly higher to 51.1 in January of 2022 from a preliminary of 50.8, but continued to point to the smallest increase in private sector activity since July of 2020, as both manufacturers (55.5 vs 57.7) and service providers (51.2 vs 57.6) registered a considerable slowdown. The expansion in new business also softened to the slowest since December 2020 as the Omicron wave weighed on demand conditions. A decline in manufacturing export orders dampened private sector growth in new business from abroad. Cost pressures eased, as the pace of input price inflation softened to the slowest since March 2021. The rate of output charge inflation, however, was broadly unchanged from December, and marked overall. Despite reports of challenges retaining and finding staff, private sector firms continued to add to their workforce numbers during January. Subsequently, the rate of growth in backlogs of work eased to the slowest since June 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/03/citigroup-ceo-faces-disgruntled-workers-regulators-demands-in-tough-first-year.html </td>
   <td style="text-align:left;"> 2022-02-03 22:57:43 </td>
   <td style="text-align:left;"> Citigroup CEO Jane Fraser faces disgruntled employees, regulators’ demands in difficult first year </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                                                , Frustration has been building within parts of Citigroup over delayed bonuses and tight budgets, two impacts of the bank's response to its regulatory oversight, according to people with direct knowledge of the situation.                                                                                                                                                                                                                    , Workers from junior salespeople to senior executives have been ensnared in monthslong reviews stemming from an anonymous complaint portal for employees, according to the sources. The bank freezes bonuses and performance reviews for staff under investigation, even if claims are baseless, according to the people, who asked for anonymity out of fear of reprisals.                                                                     , The cumbersome internal reviews are a surprising fact of life at Citigroup, where CEO Jane Fraser has garnered headlines for talking about work-life balance and other ways to get a recruiting edge versus competitors. They illustrate how regulatory scrutiny has weighed on employee morale, making the already-difficult task of turning around Citigroup even harder as Fraser, 54, approaches her one-year anniversary leading the firm., Fraser, the first female chief of a major U.S. bank, finds herself in a tricky balancing act: To overhaul a company that has deeply underperformed U.S. rivals for years, she has to improve returns and grow businesses while keeping a lid on expenses and plowing money into appeasing regulators.                                                                                                                                          , Investors have been skeptical so far. While 2021 was the best year for the banking industry in more than two decades because of rising interest rates, Citigroup didn't participate in the rally. Since Fraser took over in March 2021, the bank's stock has climbed 2.7%, while Bank of America jumped 38% and Wells Fargo, also a turnaround project, rose 56% in that period.                                                               , Fraser, a former McKinsey partner who took over after predecessor Mike Corbat accelerated his retirement timeline, kicked off her tenure with a bang: In April, she announced that the bank was exiting 13 markets in Asia and Europe. The strategy was to simplify the bank and focus on its strengths in global corporate cash management and U.S. credit cards, and to grow in wealth management.                                           , The exits, including the announcement last month that Citigroup was leaving retail banking in Mexico, were applauded by analysts, who saw it as a sign that Fraser would leave no stone unturned in her quest to remake Citigroup. After all, her predecessors had resisted calls to shrink the bank's global footprint, and Fraser herself had managed some of the operations being pruned.                                                   , But while rival banks saw their stocks surge last year and fintech players like Block's Cash App gained millions of users, Citigroup struggled. The company's revenue sagged 5% to $71.9 billion in 2021 while expenses jumped 9% to $48 billion – a dynamic analysts call "negative operating leverage" and the exact opposite of what banks typically aim to accomplish.                                                                     , Part of the leap in expenses came from addressing its consent orders. Regulators hit the bank with a $400 million fine and a pair of consent orders in late 2020, demanding sweeping improvements to risk management and controls after the bank accidentally wired $900 million to Revlon creditors. One of the edicts in the orders was for Citigroup to enhance the way it tracks and addresses employee complaints.                        , "Executing on the plan while working on the consent order, that's the hard part," said Glenn Schorr, banking analyst at Evercore. "Every business they're in is uber competitive, every one of them has neobanks and fintechs and other banks and private credit managers all nipping on their heels. It's hard to execute on all those fronts at the same time."                                                                              , Making matters worse, large investor ValueAct, which had played a role in accelerating Corbat's decision to leave, seemed to lose conviction in its wager, trimming its position over the course of the year. Then, in December, the bank revealed that it would pause share buybacks for months to boost capital for international standards, the only major U.S. bank to do so.                                                              , Citigroup's low stock price means it is the only bank among the six biggest U.S. institutions that trades for below its tangible book value, a key metric in the banking world that essentially means that the bank is seen as destroying shareholder value rather than creating it. Rivals JPMorgan Chase and Bank of America trade at more than twice their tangible book value.                                                             , The developments last year, including a tone-deaf compensation plan that critics say rewards executives for merely doing their jobs, prompted bank analyst Mike Mayo of Wells Fargo to pen a scathing report in October titled "Will Citi Reach Book Value in our Lifetime?"                                                                                                                                                                   , "Coming into this year, Citigroup was the most-hated bank stock by a wide margin," said Mayo, who admitted in a phone interview that he'd been "long and wrong" on the company after naming it a buy. "Hopefully I won't be on my deathbed and still waiting for Citi to get to book value."                                                                                                                                                   , In response to this article, Citigroup spokeswoman Jennifer Lowney had this statement:                                                                                                                                                                                                                                                                                                                                                         , "We believe our stakeholders understand there aren't any quick fixes and want to see us create real value over time," Lowney said in an email. "We're proud of the early progress we've made, and are committed to putting in the hard work needed to get the right results."                                                                                                                                                                  , Many of Fraser's challenges stem from structural disadvantages she inherited from Citigroup's genesis as the original megabank two decades ago.                                                                                                                                                                                                                                                                                                , The bank owes its current design to former Chairman and CEO Sandy Weill, who led Citicorp into a merger with Travelers in 1998 to create the world's biggest financial services company. His vision: a financial supermarket that spanned the globe, cobbled together though countless acquisitions.                                                                                                                                           , The three men who succeeded Weill over the next two decades at Citigroup — Chuck Prince, Vikram Pandit and Mike Corbat — all struggled to make the disparate parts of the sprawling enterprise work.                                                                                                                                                                                                                                           , A pivotal moment in the bank's history happened during the 2008 financial crisis, when a massive reordering of the financial hierarchy resulted in winners and losers. Stronger institutions like JPMorgan swallowed the weaker ones, growing by leaps and bounds.                                                                                                                                                                             , At first, Citigroup looked like one of the former: It had a potential deal, brokered by regulators, to acquire the retail banking operations of Wachovia, which was the fourth-biggest U.S. bank by assets at the time. But it lost out to Wells Fargo, which offered to buy all of Wachovia for a far larger price.                                                                                                                           , As the crisis dragged on, Citigroup's soured assets and risky bets forced it to take the biggest public bailout among U.S. banks. To raise money, it heavily diluted shareholders by raising new stock and sold its retail brokerage Smith Barney, with its massive army of financial advisors, to Morgan Stanley. The move would haunt Citigroup as Morgan Stanley's focus on wealth management won plaudits from investors.                  , While Citigroup muddled through the decade after the crisis, it never gained the traction in U.S. retail banking that the Wachovia deal would've given it.                                                                                                                                                                                                                                                                                     , The bank has just 689 branches in the U.S., compared with well over 4,000 each for JPMorgan, Bank of America and Wells Fargo. As a result, Citigroup doesn't soak up low-cost deposits from U.S. customers like competitors do, making its funding costs the highest among rivals.                                                                                                                                                             , One by one, as formerly battered banks like Bank of America and Morgan Stanley began to turn into high performers after the crisis, only Citigroup was left behind. Its stock, currently at around $66, is a far cry from its all-time high of $588.80 from August 2000.                                                                                                                                                                       , Meanwhile, the synergies from the bank's global sprawl after Weill acquired companies from Sao Paulo to Tokyo never materialized. Instead, overseas operations suffered from poor oversight and underinvestment, according to a former senior Citigroup executive.                                                                                                                                                                             , "Citi missed its chance to be big in the U.S. retail market," the former leader said. "They wasted a lot of money pursuing a global strategy, when fundamentally it's a wholesale bank, which has lower returns than retail banking."                                                                                                                                                                                                          , The executive called the non-U.S. businesses "melting ice cubes" because as Citigroup underinvested in far-flung markets like Taiwan or Malaysia, local competitors continued to get sharper, leaving the bank further behind.                                                                                                                                                                                                                 , For instance, Banamex, a storied name in Mexico, was the country's No. 2 bank when it was acquired by Citigroup for $12.5 billion in 2001. By the time Citigroup announced it was exiting retail banking in the country this year, the unit's market share had fallen by nearly half.                                                                                                                                                          , Fraser has said that she's completed her pruning of Citigroup and will present investors with a new strategic vision and multiyear plan on March 2, the bank's first investor day in years. Analysts expect her to give medium- and long-term targets for return on tangible common equity — a key industry metric calculated by dividing a bank's earnings with its shareholders' equity.                                                     , To win, the bank needs to break a cycle of underinvestment that leads to subpar returns.                                                                                                                                                                                                                                                                                                                                                       , Citigroup is picking its spots, adding 500 front office workers in its wealth business, 200 corporate and investment bankers, and working to digitize parts of its flagship corporate cash management business, CFO Mark Mason said in October.                                                                                                                                                                                                , But some managers at the retail bank claim that while the mandate is for growth, resources are limited because of the attention and money pouring into addressing the firm's consent orders. Citigroup has dedicated more than 4,000 workers spread over six projects to the sweeping mandate to fix risk management systems while pouring billions of dollars into technology upgrades.                                                       , That has left some frustrated that both traditional and fintech competitors have a funding advantage, giving them an edge in hyper-competitive markets. Venture capital investors poured $134 billion into fintech start-ups last year, prompting traditional players including JPMorgan to pump up their investment budget to compete.                                                                                                        , Lacking the physical network of its peers, Citigroup has been boxed into a strategy that emphasized partnerships, which can be an efficient way to boost a bank's reach. However, it also leaves the bank exposed to the whims of its partners: Its deal with Google to offer bank accounts to users – a move that initially had sent waves of elation through Citi – ended up nowhere after the tech giant killed the project.                , Few things have frustrated employees, however, as much as the internal investigations, which can stretch for months as the bank works through a backlog of complaints lodged by its own workforce.                                                                                                                                                                                                                                             , Complaints can be made to the internal employee relations portal anonymously, forcing human resources staff and lawyers to deal with a deluge of issues ranging from legitimate allegations of wrongdoing to petty disagreements or opinions on business strategy. (One person likened the complaint line to New York's 311 service.) One of the more common complaints is tied to the bank's Covid vaccine policy, said this person.          , Another person familiar with the program said that the complaint line and bonus policy was viewed as necessary after the bank's employees were involved in ethical failures like the Libor and foreign exchange trading scandals.                                                                                                                                                                                                              , While this person said that not all complaints result in withholding bonuses, only those that cross a threshold of seriousness, others said that they've been instructed to withhold year-end performance reviews and compensation discussions for anyone under investigation.                                                                                                                                                                 , Citigroup declined to say how many internal complaints it gathers or what percentage of investigations results in vindicated employees.                                                                                                                                                                                                                                                                                                        , The policy to withhold bonuses, which began about three years ago, has tripped up employees. For senior workers, incentive compensation can make up the majority of their annual compensation. One employee had a review held up for longer than a year before ultimately getting paid. Another threatened to depart unless their case was fast-tracked.                                                                                       , "I asked HR, 'Why does it take so long?'" one of the people said. "They said 'We have so many complaints, we can't get ahead of this.'"                                                                                                                                                                                                                                                                                                        , The dynamic contributes to an atmosphere of second-guessing and a resistance to change, said the people. The bank also takes too long to approve new products and sometimes fails to communicate changes to key internal stakeholders before announcements are made public, the people said.                                                                                                                                                   , These factors may contribute to defections as competitors across finance dangle pay raises to leave Citigroup, according to the people. In the past few months, the bank's U.S. retail banking chief and chief marketing officer have left for competitors.                                                                                                                                                                                    , Still, Fraser has also managed to lure her share of outside talent, picking up a former Treasury official as general counsel and hiring Goldman's chief diversity officer and JPMorgan's chief data officer for key positions.                                                                                                                                                                                                                 , This year may not be much smoother than last for Citigroup. Last month, the bank's CFO conceded that the bank's returns — already the lowest among the top six U.S. banks — are likely to decline this year as Wall Street revenue slows down and the benefit from reserve releases recedes.                                                                                                                                                   , Just one year into her tenure, however, nobody is counting Fraser out. If her March investor day plan is seen as credible and she starts to make progress toward her goals, the stock should recover, according to analysts. If anything, the extreme pessimism embedded in the stock means shares can't fall much lower.                                                                                                                      , "It's a tough job, I don't envy her," said a former executive. "If there's someone who can do it, she's the one."                                                                                                                                                                                                                                                                                                                              , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                         , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                         , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                               , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                               , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                             , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/services-pmi </td>
   <td style="text-align:left;"> 2022-02-03 22:51:00 </td>
   <td style="text-align:left;"> US Markit Services PMI Remains Lowest since 2020 </td>
   <td style="text-align:left;"> The IHS Markit US Services PMI was revised slightly higher to 51.2 in January of 2022 from a preliminary of 50.9, but still pointed to the slowest growth in the services sector since July of 2020. The spread of the omicron variant hampered the upturn in new business and domestic and foreign demand conditions weakened. Firms were able to expand their workforce numbers further, however, which helped to soften the degree of pressure on business capacity. As a result, backlogs of work rose at the slowest pace since August 2021. Although there were signs that cost pressures eased during January, companies were able to pass on higher costs to clients through the fastest rise in output charges for three months. Meanwhile, business confidence fell from December but still was the second-highest since June 2021, linked to hopes of a further uptick in client demand and a reduction in disruption caused by new COVID-19 variants. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/composite-pmi </td>
   <td style="text-align:left;"> 2022-02-03 22:49:52 </td>
   <td style="text-align:left;"> Brazil Private Sector Marginally Grows </td>
   <td style="text-align:left;"> The IHS Markit Brazil Composite PMI decreased to 50.9 in January of 2022 from 52 in the previous month, signaling marginal growth in the country’s private sector, the slowest in its current nine-month period of expansion. The positive change was supported by the services sector (PMI at 53.6 vs 52.8 in December of 2021), offsetting the contraction in manufacturing (PMI at 47.8 vs 49.8). Aggregate new orders and business activity quickened in Brazil’s private sector, although at a softer pace, largely due to the new wave of Covid infections. At the same time, job creation expanded at a softened pace for service providers, while manufacturers shed jobs in January. On the price sector, inflationary pressure intensified for both sectors, with more pronounced increase among service providers. Lastly, business confidence increased for both sectors amid hopes that the pandemic wave will soon wane and expectations of price stability. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-02-03 22:49:00 </td>
   <td style="text-align:left;"> Brazilian Stocks Edge Lower </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, was down 0.4% to around 111,445 on Thursday, mainly dragged down by heavyweight Petrobras. Also, cyclical sectors, such as retailers and construction companies, retreated after a strong start, tracking international markets. Meanwhile, investors continued digesting the latest monetary policy decision from the Brazilian central bank to raise the Selic by 150 basis points to 10.75%, as expected, but signaling that it should reduce the pace of the hike for the next meetings. On the data front, a Markit PMI survey showed Brazil's private sector growth slowed to a nine-month low, as a faster expansion in services was not enough to counteract another contraction in manufacturing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/euro-area/currency </td>
   <td style="text-align:left;"> 2022-02-03 22:40:00 </td>
   <td style="text-align:left;"> Euro Strengthens Following ECB Press Conference </td>
   <td style="text-align:left;"> The euro strengthened to $1.14, moving further away from the 20-month lows of $1.11 touched earlier this week after comments from ECB policymakers signaled a hawkish stance on the back of unanimous concerns over higher inflation across the ECB's board. During the ECB press conference, President Lagarde ruled out keeping the rates stable this year saying the bank would assess conditions very carefully and there were "no pledges without conditionalities". Money markets now bet the ECB will raise rates by 40bps this year instead of a 30bps increase before the February monetary policy decision. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-03 22:34:00 </td>
   <td style="text-align:left;"> US Stocks Sink, Meta Shares Plunge 25% </td>
   <td style="text-align:left;"> The Nasdaq sank more than 2% on Thursday, dragged down by a 25% plunge in shares of Meta Platforms, after earnings and outlook from the Facebook parent company disappointed. Mixed quarterly results from other companies including Honeywell, Biogen, T-Mobile and Spotify also weighed on investors' mood. The S&amp;P 500 was down more than 1% and the Dow Jones lost around 300 points. The 3 benchmark stock indexes ended a 4-day winning streak as the earnings season has seen some surprises on the downside. Amazon and Ford are also due to report quarterly results today after markets close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60197463?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-03 22:33:44 </td>
   <td style="text-align:left;"> Interest rates rise again in bid to cool soaring prices </td>
   <td style="text-align:left;"> Interest rates have risen for the second time in three months as the Bank of England tries to curb a rapid rise in the cost of living.                                                                                                   , The hike to 0.5% from 0.25% came as the Bank warned that price rises could speed up.                                                                                                                                                     , Prices are expected to climb faster than pay, putting the biggest squeeze on household finances in decades.                                                                                                                              , It comes as the chancellor unveiled a support package to help households cope with a 54% jump in energy bills.                                                                                                                           , Rising gas and electricity costs are the main factors pushing up prices across the economy.                                                                                                                                              , Inflation, as measured by the consumer prices index (CPI), is expected to peak at 7.25% in April, and average close to 6% in 2022.                                                                                                       , This would be the fastest price growth since 1991 and is well above the Bank's 2% target.                                                                                                                                                , Despite that, the Bank of England governor Andrew Bailey has suggested workers need to accept pay restraint, and should not ask for higher wages, in order for inflation to be tamed more quickly.                                       , There are also increasing signs of broader price pressures across the economy.                                                                                                                                                           , Prices of household appliances such as fridges climbed almost 10% over the past year.                                                                                                                                                    , Goods shortages also meant retailers were offering fewer bargains in the January sales compared with previous years.                                                                                                                     , Food prices and rents were also likely to creep up in the short term, the Bank warned.                                                                                                                                                   , Pay increases are not expected to keep pace with rising prices.                                                                                                                                                                          , Post-tax incomes are forecast to fall 2% this year, after taking into account the rising cost of living.                                                                                                                                 , This represents the biggest fall in take-home pay since records began in 1990.                                                                                                                                                           , Despite this, the Bank said there had been a "material pick-up in pay settlements" this year, with the average worker enjoying a 5% pay rise.                                                                                            , "Acute" staff shortages in sectors such as hospitality, engineering, construction and IT also meant many employers were offering staff "ad-hoc" bonuses to keep them.                                                                    , The pandemic meant other workers had retired early, stayed in education or cut down their hours for a better work life balance. The Bank said this had created other labour shortages that could take "many years to be resolved".       , Bank of England governor Andrew Bailey said the jobs market was "extraordinarily tight", adding that when he speaks to businesses up and down the UK, labour shortages are the "first, second and third thing people want to talk about"., The Bank's decision to raise interest rates will make borrowing more expensive, potentially hitting some households harder.                                                                                                              , The Bank cannot do much to ease the energy price shock or rapid price rises in some consumer goods, so it is sticking to its job by trying to keep inflation stable, the Bank's deputy governor for monetary policy Ben Broadbent said.  , The rates rise coupled with soaring prices will make it more difficult for some people to afford mortgage repayments.                                                                                                                    , Naomi Mellor, a vet who lives in Hatfield with her husband, sold their house in April, but their next purchase fell through, so they're renting.                                                                                         , She said rising mortgage rates have had a big impact on what they can afford.                                                                                                                                                            , "We're looking at a rise in our energy bills, a rise in our fuel bills and a rise in our mortgage repayments, which altogether is going to contribute to probably £200 to £300 a month more in our monthly bills.                        , "We're trying to buy a house and the rising mortgage rates have had a big impact on what we can afford and how much we're going to be repaying on a monthly basis," she said.                                                            , The Bank's rates decision will add just over £25 to the typical monthly repayment for people on a tracker mortgage.                                                                                                                      , Those who have a standard variable rate mortgage will pay an extra £15 per month on average.                                                                                                                                             , Nearly two million people in the UK have one of these two types of mortgage.                                                                                                                                                             , While savers will hope for higher returns, many big banks failed to pass on the full increase in December, when interest rates were increased from a record low of 0.1%.                                                                 , The worst squeeze on the income of households since 1990 is what the Bank predicts.                                                                                                                                                      , Record energy bill rises from April will take inflation to a peak of 7.25% in April, more than treble the Bank's normal target.                                                                                                          , Some have called it "Black Thursday" for living standards.                                                                                                                                                                               , In raising interest rates again and signalling more rate rises in the coming months, and nearly voting for even more on Thursday, the Bank is putting the nation on the couch in an exercise in mass psychology.                         , Inflation rises can be self-fulfilling. If workers, consumers and businesses expect 7% rises to persist, they will pre-emptively put up prices and ask for wage rises that then bring this about.                                        , What the Bank is trying to do is to confine what is happening right now to being a one-off shock.                                                                                                                                        , To stop the inflation becoming "ingrained" as Bank governor Andrew Bailey put it today.                                                                                                                                                  , There is a presentational issue here.                                                                                                                                                                                                    , In ordinary circumstances interest rates are raised to temper booming or bubbly growth - to take the punch bowl away from the party. But there is no punch bowl. There is no party.                                                      , In fact the Bank lowered its forecasts for growth of the economy to 3.75% from 5%, even though Omicron was not as damaging as feared.                                                                                                    , The Bank's answer is that this series of rate rises will be enough to stop a spiral of inflation, but will not go so high as to kill off the recovery. It is a delicate balancing act indeed.                                            , The recent rapid rise in prices led to some members of the Bank's Monetary Policy Committee (MPC) to call for a bigger rate rise.                                                                                                        , Four of the nine members voted to increase rates to 0.75% to ward off fears that price rises could become more sustained.                                                                                                                , The MPC voted unanimously to end new purchases as part of its £895bn bond buying programme to support the economy.                                                                                                                       , The Bank also forecast that the rapid spread of the Omicron Covid variant will hit growth this year.                                                                                                                                     , The economy is forecast to stagnate in the first three months of this year, while the Bank also cut its annual growth forecast for 2022 from 5% to 3.75%.                                                                                , Policymakers expect the economy to grow by around 1.25% in 2023.                                                                                                                                                                         , While consumers are expected to dip into their savings to maintain living standards, this is expected to slow down later this year, weighing on growth.                                                                                  , When Ruby Wax met Pamela Anderson...                                                                                                                                                                                                     , Russell Kane and guests explore the life of Queen Elizabeth I...                                                                                                                                                                         , The story of the Holocaust through the eyes of remarkable 106-year-old Boris Pahor                                                                                                                                                       , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-02-04 10:40:19 UTC +8

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
   <td style="text-align:left;"> 2022-02-04 10:39:49 </td>
   <td style="text-align:left;"> $SPY lmao prices surging </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:39:47 </td>
   <td style="text-align:left;"> $SPY Yields about to breakout of the yearly chart $AMD $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:39:37 </td>
   <td style="text-align:left;"> $SPY “Amazon’s quarter has a catch though. Net income hit $14.3 billion for the quarter, but that included a pretax gain of about $11.3 billion on Amazon’s holding of Rivian (RIVN) stock. Looking ahead, Amazon and Ford have a problem with their Rivian holdings. Rivian shares were about $104 at the end of 2021. That’s the measurement date for calculating fourth-quarter gains. Now they are about $60 a piece. That means Amazon is sitting on a pretax loss of about $6.4 billion” 🩸🩸☠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:39:31 </td>
   <td style="text-align:left;"> $SPY 2008+2010 Crash and 2020+2022 Preview </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:39:22 </td>
   <td style="text-align:left;"> $SPY jobs numbers could shatter this bounce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:39:14 </td>
   <td style="text-align:left;"> $SPY Congrats if u held puts through today!
Discord link in bio!🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:38:58 </td>
   <td style="text-align:left;"> $SPY futes rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:38:56 </td>
   <td style="text-align:left;"> $SPY this last month has just been so fucked up. It’s great. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:38:48 </td>
   <td style="text-align:left;"> $SPY it seems many people on this board don&amp;#39;t understand the effect of catalysts on the market.  
Let me give you an example; we have a JOB REPORT tomorrow; during the pandemic, when the job report was good, it was a bullish signal for the market. But RIGHT NOW, it&amp;#39;s the opposite; based on FED&amp;#39;s new policy, they will withdraw economic support (printing) when unemployment falls (good news). Simple. You should expect wrong numbers if you are bullish, but estimates show good numbers for tomorrow, so expect a bearish price action.  
https://www.nytimes.com/2022/01/07/business/economy/jobs-interest-rates-federal-reserve.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:38:19 </td>
   <td style="text-align:left;"> $SPY 470 incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:38:10 </td>
   <td style="text-align:left;"> $SPY Probably an easy ES long play to 4560 tonight. What a joke. I’m going back to futes 

They don’t matter anyways </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:38:09 </td>
   <td style="text-align:left;"> $SPY olympics rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:37:12 </td>
   <td style="text-align:left;"> $SPY UUUUHHHH TIME TO START PLAYING VOL 
$UVXY 
WHATS UP YALL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:37:12 </td>
   <td style="text-align:left;"> $SPY Calls printed today and will print even more tomorrow!🤑💰
Discord link in bio!🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:37:11 </td>
   <td style="text-align:left;"> $AMZN I mean I’m happy for the overall market sentiment here but I really hope my $spy puts are still up at open 🤨🚀✌🏽🐻🪤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:37:10 </td>
   <td style="text-align:left;"> $AMZN $SPY  
 
https://news.sky.com/story/amazon-reveals-17-hike-in-prime-membership-fee-to-offset-rising-costs-as-profits-surge-12532217 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:37:08 </td>
   <td style="text-align:left;"> $SPY stay sexy my Transmephadites 😩😂😎 we are gonna be doing the lumbada in LAMBOS and have beautiful gals. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:36:50 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:36:46 </td>
   <td style="text-align:left;"> $SPY Everyone wants nukes lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:36:41 </td>
   <td style="text-align:left;"> $SPY futes are bearish until 14850 breaks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:36:37 </td>
   <td style="text-align:left;"> $F chip shortage is easing for $GM, but not for Ford?   Even $TSLA delaying new models due to chip shortage.   things that make you go hm.... $SPY $RIVN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:36:29 </td>
   <td style="text-align:left;"> $SPY when people go back to work and their applications state recent work history as ‘yolo calls’ 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:36:26 </td>
   <td style="text-align:left;"> $SPY Looks NASDAQ heading for 13000. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:35:49 </td>
   <td style="text-align:left;"> $SPY  
 
I dont want to tell any tales out of school but as a key contributer to the HJI, I can assure you that jobs are up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:35:31 </td>
   <td style="text-align:left;"> $SPY break down.vix all night.lets take out support at 24.30 don&amp;#39;t be a idiot btfd </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:35:27 </td>
   <td style="text-align:left;"> $AMZN cooked the books with Revrion (something like that) 
$SPY was dropping like a fly so BS $AMZN to the rescue? 
Don&amp;#39;t personally own either but this shit is like Jerry Springer🙄 
I don&amp;#39;t care if they go ⬆️ or ⬇️ but I am going to watch the show 
I agree with ⬇️⬇️⬇️⬇️⬇️⬇️⬇️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:35:23 </td>
   <td style="text-align:left;"> $SPY it’s hilarious cause job reports are going to be super bearish tomorrow and I know people loaded calls after a corrupt Amazon beat 🤡 I hope Amazon plummets tomorrow $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:35:04 </td>
   <td style="text-align:left;"> The Fed has $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:35:04 </td>
   <td style="text-align:left;"> $SPY my little Transmephadites get ready for the amc squeeze And sundial run. You’re all gonna be dancing like this. The market must go down for us memes to rise. Luna and the duck is gone, just us retail now, like family. Lots of money coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:35:01 </td>
   <td style="text-align:left;"> $AMZN the only way for market to go up is have healthy economy. But when report showing slow spending, high labor cost, making number up you know economy is bad. No way you can hide it. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:34:59 </td>
   <td style="text-align:left;"> $SPY Backed outta 20k worth of puts at 3:59. Amzn had me paranoid. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:34:56 </td>
   <td style="text-align:left;"> $FB y’all may dislike suckerberg  because he’s an automaton passing for human but $FB seems like a steal.  Currently trading at a 2022 P/E of 16 vs. $SPY @ 20.  You’re basically getting a value stock with a massive growth engine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:34:55 </td>
   <td style="text-align:left;"> $SPY Futes rippin again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:34:45 </td>
   <td style="text-align:left;"> $SPY Hang Seng rocking!!! Bring that music this way tomorrow !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:34:30 </td>
   <td style="text-align:left;"> $SPY SPY 2022-02-03 Daily Forecast Video: 
https://www.youtube.com/watch?v=MBRgFrxolJM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:34:28 </td>
   <td style="text-align:left;"> $SPY 460+ open !!!! LFG then red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:33:51 </td>
   <td style="text-align:left;"> Did you miss out on some money! Come see where we make killer calls. Joke Around and look out for each other. Alerts time stamped and reviewed regularly! Free community so join now. Link is in bio! $pins $INDO $DOGE.X $F $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:33:50 </td>
   <td style="text-align:left;"> $SPY I love how global warming was changed to climate change. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:33:48 </td>
   <td style="text-align:left;"> $SPY China tearing to the upside. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:33:30 </td>
   <td style="text-align:left;"> $SPY War is bullish for the military industrial complex </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:33:25 </td>
   <td style="text-align:left;"> $SPY $SPX Low key where’s the liquidity imbalance today, but more importantly they seem aggregating across industries . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:33:24 </td>
   <td style="text-align:left;"> $SPY jpow already hinted during last meeting that jobs were looking good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:33:04 </td>
   <td style="text-align:left;"> $SPY Bears doubled down big today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:33:03 </td>
   <td style="text-align:left;"> $SPY Dear Diary,
I hope tomorrow isn’t a theta 🔥.  This week has been amazing.
I got to cry manipulation for most of the week (agaiiin)…had a great day today playing I told you so (finally!)…and we almost had that crash, we were this close👌!
All in all it’s been another great week being a bear.
-cg 2/3/22 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:33:00 </td>
   <td style="text-align:left;"> $SPY job report at 8:30 am 

Be ready for another interesting day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:32:57 </td>
   <td style="text-align:left;"> $SPY lol

https://www.shtfplan.com/headline-news/perpetual-covid-vccinations-mayo-clinic-thinks-jabs-will-be-necessary-for-at-least-a-century </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:32:57 </td>
   <td style="text-align:left;"> $SPY I’m sorry my little Transmephadites, Luna was grabbed the hedgies. 🔪🇨🇳🇨🇳🇨🇳chop chop!  Find Luna the cat!😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:32:51 </td>
   <td style="text-align:left;"> $SPY when Hong Kong rips we sell lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:32:29 </td>
   <td style="text-align:left;"> $SPY futes rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:32:22 </td>
   <td style="text-align:left;"> $SPY No way MM pay out the call premiums tomorrow lmao, definitely more likely to be red than green tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:32:20 </td>
   <td style="text-align:left;"> $SPY hong kong rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:32:18 </td>
   <td style="text-align:left;"> $SPY didn’t y’all hear that Amazon has to pay higher wages to attract more workers   C’on man </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:32:11 </td>
   <td style="text-align:left;"> $SPY big rally coming soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:32:00 </td>
   <td style="text-align:left;"> $SPY fuk me Nikkei just woke up lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:31:54 </td>
   <td style="text-align:left;"> $SPY Hong Kong going nutty out the gate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:31:31 </td>
   <td style="text-align:left;"> $SPY notice once everyone got comfortable they tanked it 4% this will be a slow death until March then we get rug pulled MMs are out for youre money and you will lose </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:31:09 </td>
   <td style="text-align:left;"> $SPY bruh lottery tickets plus powerball.cost $3 now. 

They inflating even lotto tix lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:31:09 </td>
   <td style="text-align:left;"> $SPY Well RSI is saying bullish tomorrow so probably a bounce. But I&amp;#39;ll be eyeing that $454 level at the close. If we claim it I am looking for $460 up to the 50DMA, if it closes under $454 then yikes watch out below from the daily H&amp;amp;S . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:30:42 </td>
   <td style="text-align:left;"> $SPY $QQQ futes sweet bounce of VWAP ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:30:39 </td>
   <td style="text-align:left;"> $SPY  
 
If you are not 110% confident in your position, this will help 
 
SPY $500  
 
https://youtu.be/xbIG_b2IMO0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:30:34 </td>
   <td style="text-align:left;"> $SPY futes rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:30:23 </td>
   <td style="text-align:left;"> $SPY would be hilarious if this went red tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:30:06 </td>
   <td style="text-align:left;"> $SPY IM NOT A LIBERAL! BUT I WILL BLOCK THOSE WHO POST “FUTES RIPPING” AND WHAT NOT… CUZ YOU GUYS ARE MENTALLY ILL… ILL GO CHECK AND THEY WILL BE -0.03% AND YOU GUYS SPAMMING FUTURES RIPPPING ON HERE NO WONDER YOUR ACCOUNTS ARE DOWN 95% ALL TIME….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:29:58 </td>
   <td style="text-align:left;"> $SPY  
 
Guide to understanding futures activity on ST: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:29:58 </td>
   <td style="text-align:left;"> $SPY ugh I wish there was a free discord I could join, someone transparent would be ideal! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:29:51 </td>
   <td style="text-align:left;"> $SPY Hard believe,  still in Bullish Trend.  They have managed to keep this up MA50 on Weekly. 

I have been too focused on Daily.  Extending focus for further study. 

Study, every night. Dam you PYPL wish death upon you. Jk, played it wrong, still hurts. This happens to any investor.  Those that can&amp;#39;t admit to mistakes,  is their biggest mistake.  

I needed be slapped. I was getting too confident.  Traders need corrections too.  

One trader that remains high on my list to follow 👉 @RicoElite with honest and humbke posts..  Much respect 🍺 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:29:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $USO $UCO super long term chart of oil.  Yellow is where we are going.  Who wants at least a 20% gain relatively quickly? 😏🤘 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:29:38 </td>
   <td style="text-align:left;"> $SPY $QQQ the market is not done tanking but your weekly puts are for sure fucked. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:28:56 </td>
   <td style="text-align:left;"> $SPY huuuaaaaaa chop chop chop😂🦆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:28:50 </td>
   <td style="text-align:left;"> $AMZN Most here have little to no knowledge of the amount of liquid cash being poured into equity market, and how options dictate SP. Call it rigged, a script, a WS narrative… end of day, it is your fault for being on the wrong side. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:28:50 </td>
   <td style="text-align:left;"> $SPY Most days short volume is greater than long shares, like around  90% of days I would say, so liquidity is there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:28:42 </td>
   <td style="text-align:left;"> $AMZN the state of economy is what we want to see in the report. It’s bad. Next quarter is going to be terrible $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:28:36 </td>
   <td style="text-align:left;"> $SPY the duck is getting chopped tomorrow 🦆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:28:36 </td>
   <td style="text-align:left;"> $SPY I wish you could still comment on Yahoo articles. Can&amp;#39;t red pill the libtards anymore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:28:02 </td>
   <td style="text-align:left;"> $QQQ $SPY $SNAP $FB 

WHOES NEXT?!? Anyone else eying the earnings calendar for our next victim?!?!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:27:41 </td>
   <td style="text-align:left;"> $SPY fake testing kits 

https://www.usatoday.com/story/news/nation/2022/01/23/center-covid-control-office-searched-fbi/6600802001/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:27:05 </td>
   <td style="text-align:left;"> $SPY When ER is moving the market AND $BTC more than inflation data….k.

We are in a bear market. Make no mistake about it. Wish they would drop this shit already, rip the bandaid off instead of burning out retail on all sides 😐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:26:59 </td>
   <td style="text-align:left;"> $SPY 🦆🔪🇨🇳😬😂 chop chop tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:26:55 </td>
   <td style="text-align:left;"> $SPY I was told futures were being crushed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:26:42 </td>
   <td style="text-align:left;"> $SPY who gives a f*ck about job numbers……

Y’all see the market got a mind of its own…..

Charts matter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:26:23 </td>
   <td style="text-align:left;"> $SPY Is the job report gonna make a big impact? I do not know such news ahead else I would close all positions. Such news and things always shifts momentum. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:26:17 </td>
   <td style="text-align:left;"> $SPY  
 
We spent all of 2020 pumping on both good news and bad news.  We just received a CPI report using 2019-2020 data. 
 
If you haven&amp;#39;t figured out that at this point, numbers are 100% meaningless, I don&amp;#39;t know what to tell you.  Bear that in mind (hee hee) for things like upcoming job reports and so on. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:26:04 </td>
   <td style="text-align:left;"> $SPY Friday&amp;#39;s jobs report could be a brutal one. The average estimate of Wall Street economists is for a gain of 150,000 jobs. Yet some think the Labor Department data could be as bad or even worse than the 301,000 loss estimated by Wednesday&amp;#39;s ADP employment report. https://www.investors.com/news/economy/fridays-jobs-report-will-be-awful-will-stock-market-notice/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:25:59 </td>
   <td style="text-align:left;"> $QQQ $SPY 

Put me on the bench
Cause I ain’t playing withchu dummies 

https://music.apple.com/us/album/abnb/1606729791?i=1606730189 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:25:42 </td>
   <td style="text-align:left;"> $SPY huge numbers of people unemployed.  back to 336. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:25:40 </td>
   <td style="text-align:left;"> $XLE $SPY when is the next variant scheduled to crush oil prices? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:25:40 </td>
   <td style="text-align:left;"> $SPY Whatever you do don&amp;#39;t look at the gaymf or bbw board. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:25:18 </td>
   <td style="text-align:left;"> $SPY Rivian in tmrw job report </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:25:04 </td>
   <td style="text-align:left;"> $SPY the green is grasser on the other side. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:24:53 </td>
   <td style="text-align:left;"> $SPY Don’t forget folks: cash IS a position. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:24:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $FB $DWAC #TRUMPB42024 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:24:51 </td>
   <td style="text-align:left;"> $SPY we gotta eliminate market makers, put stock market on blockchain, fuck liquidity, no bids wait till you get one, 2 days 3 days whatever, clean, transparent fuck options too actually as much as I love them lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:24:46 </td>
   <td style="text-align:left;"> $BTC.X  $SPY still more pain to come </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:24:27 </td>
   <td style="text-align:left;"> $SPY fake jobs numbers to prop market tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:24:27 </td>
   <td style="text-align:left;"> $SPY Bears are praying job #s  are bad lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:24:19 </td>
   <td style="text-align:left;"> $spy bot the shit out of 446 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:24:17 </td>
   <td style="text-align:left;"> $SPY what a brutal fuking AH… the close was perfect… futures up almost 1% and fuking BTC is up over 1% FML! Die mofo die </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:23:35 </td>
   <td style="text-align:left;"> $SPY jobs numbers could shatter this bounce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:23:20 </td>
   <td style="text-align:left;"> 90% of people are financially illiterate $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:23:06 </td>
   <td style="text-align:left;"> $SPY can we have $465 tomorrow and then let the bears have their fun? Thx </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:23:04 </td>
   <td style="text-align:left;"> $SPY tomorrow we bull trap and next week we&amp;#39;ll see blood. Some of tech starting to look cheap but i want cheaper </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:23:01 </td>
   <td style="text-align:left;"> $SPY futes looking good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:22:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $SPXL Bears WILL take over soon, and, contrary to many&amp;#39;s understanding, BEARS are superior at understanding markets over bulls in a downtrend. 
They understand what&amp;#39;s going on, because they are betting on that understanding and the ones MAKING THE RIGHT ENTRIES AND NAILING RIGHT DIRECTIONAL MOVES OF MARKET.

Now bears are bulls too, keep in mind, a lot, they are both superior chartists as well as full envelopers of the macro picture and why markets popping ir dropping. 

They will question you too by moving market directionallh.
Often in futures they give us resistance and support clues. They trade NIGHT &amp;amp; DAY, you might think it is Tutes moving market but it is really the highly intelligent bears. , they. are. that. good. at what they do. $ES_F 
@sonicmerlin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:22:30 </td>
   <td style="text-align:left;"> $SPY btc; a more reliable indicator of next trading day than futes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:22:20 </td>
   <td style="text-align:left;"> $SPY Pop to 455 and back to 441 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:22:00 </td>
   <td style="text-align:left;"> $SPY this is a buy every day of your life. Bear accounts going to get liquidated again. Stupid asses deserve it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:21:56 </td>
   <td style="text-align:left;"> $SPY Breakout on Futes, tomorrow will be interesting. Grabbed a cheap $454 Call on $SPY . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:21:46 </td>
   <td style="text-align:left;"> $SPY Don’t throw glass if you live in a rock house. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:21:41 </td>
   <td style="text-align:left;"> $SPY FUTES RIPPIN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:21:31 </td>
   <td style="text-align:left;"> $SPY I believe Donald Trump app Truth will be so big it will get S&amp;amp;P 500 inclusion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:21:25 </td>
   <td style="text-align:left;"> $AMZN $SPY 
I don&amp;#39;t understand why these Bull tards act like Bears lost their houses or something. Most of our money are cash on the side for stupid convictionless events like this. 😕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:21:25 </td>
   <td style="text-align:left;"> $SPY $442.. $AAPL $170 $amzn $3100 tomorrow. Bulls got bamboozled. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:20:45 </td>
   <td style="text-align:left;"> $SPY $QQQ So $FB drives the entire market down but $AMZN picks it up? What is this bullshit? What are these retarded algorithms? What the fuck actually goes on on the market? It&amp;#39;s fucking senseless. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:20:36 </td>
   <td style="text-align:left;"> $SPY Puts or Calls.  Thats all i&amp;#39;m playing for now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:20:29 </td>
   <td style="text-align:left;"> $SPY big moves in either direction usually follow this candle pattern. I&amp;#39;m sure it has a name ima call it the Kobeyashi-big-in-either-direction pattern. But yeah, big moves usually follow in a continuation. I&amp;#39;m expecting a big green day tomorrow because that&amp;#39;s what&amp;#39;s being printed on the chart. 

I got some bear positions to close in the morning. If in wrong ill reopen them. It&amp;#39;s that simple! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:20:15 </td>
   <td style="text-align:left;"> $SPY When I trade contrarian and it works..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:20:02 </td>
   <td style="text-align:left;"> $SPY &amp;quot;Too many transgender Ukrainians of color are being hit with propaganda by the Russians.&amp;quot; 
 
-Joe Biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:19:51 </td>
   <td style="text-align:left;"> $SPY HOUSING MARKET is gonna crash this winter ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:19:36 </td>
   <td style="text-align:left;"> $SPY $MRNA 

https://msyc1.wordpress.com/2022/01/26/analysis-by-german-prof-thousands-of-hidden-deaths-daily-may-be-greatest-medical-debacle-in-human-history/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:19:33 </td>
   <td style="text-align:left;"> $spy give it up bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:19:29 </td>
   <td style="text-align:left;"> $SPY HAHAHAH DUMMIES!!! YOU DON’t SEE THE INVERTED HAMMER HEAD SHARK ON THE 4 HOUR… 😅 LEARN HOW TO DO TA BEFORE YOU START TRADING 🤡🤡🤡🤡🤷‍♀️🤷‍♀️🤷‍♀️🤷‍♀️🤦‍♀️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:19:20 </td>
   <td style="text-align:left;"> $SPY 🦆👀🔪 💥🔪💥🔪 🇨🇳😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:19:19 </td>
   <td style="text-align:left;"> $SPY Remember, people in glass houses sink ships. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:19:15 </td>
   <td style="text-align:left;"> $SPY $QQQ funny how bulls still don’t understand what a bear market is..it’s many trapped bulls looking to gtfo on any rip. Stop buying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:19:13 </td>
   <td style="text-align:left;"> $SPY 

Fed recession probability </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:19:05 </td>
   <td style="text-align:left;"> A true hero 🙏🙏🙏 all is good guys!! $SPY $AMZN $FB $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:18:49 </td>
   <td style="text-align:left;"> $AMZN going to bed ladies, and gents. 4300 or 4400 open is all I can think about. Anything else is bullshit hope. Big pay day for me, and few others. 🤘🤘🤘 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:18:35 </td>
   <td style="text-align:left;"> $SPY I miss the Ole days when  we though covid was from bat soup lol that was fun times. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:18:32 </td>
   <td style="text-align:left;"> $SPY BEAR EXTINCTION </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:18:30 </td>
   <td style="text-align:left;"> $SPY $QQQ Worst case there will be just one rate hike in March &amp;amp; back off, pmi plummeting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:18:21 </td>
   <td style="text-align:left;"> $SPY marketmakers call the shots to make the most money and screw everybody, they don’t give a shit what we here post or what HF blows up tmrw actually. Truth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:18:09 </td>
   <td style="text-align:left;"> $SPY Bulls went from crying to saying we&amp;#39;ll see 500$ SPY eom ☠️ what  Fundamentally changed this morning to now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:17:47 </td>
   <td style="text-align:left;"> $AMZN $SNAP $QQQ $SPY   i&amp;#39;m a bear, a swing trader and i love dead cat bounces </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:17:43 </td>
   <td style="text-align:left;"> $SPY my dear puts RIP 🥲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:17:34 </td>
   <td style="text-align:left;"> Options  Watchlist:  Let&amp;#39;s Make Cash 💵💵 
   
1) $SNAP 
2) $AMZN  
3) $PYPL  
4) $EBAY  
5) $SPY  
 
#WEteam #Daytrading #Stockstowatch #StocksWatchlist #Trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:17:21 </td>
   <td style="text-align:left;"> $SPY Asia ripping 

https://www.cnbc.com/2022/02/04/asia-markets-overnight-wall-street-tumble-technology-stocks-currencies-oil.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:17:17 </td>
   <td style="text-align:left;"> $SPY yeah this mobile update is a disaster </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:17:17 </td>
   <td style="text-align:left;"> $SPY DCA over the long term is key to wealth building </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:17:08 </td>
   <td style="text-align:left;"> $SPY step up so I can knee you in the ear dog </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:16:52 </td>
   <td style="text-align:left;"> $spy everyone and their ex shorted todsy? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:16:47 </td>
   <td style="text-align:left;"> $SPY Eff it😩😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:16:39 </td>
   <td style="text-align:left;"> $SPY bears r gonna get cucked tmrw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:16:36 </td>
   <td style="text-align:left;"> $QQQ $SPY  every paid basher is out in their 15 accounts… you know big money wants those fear shares badly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:16:28 </td>
   <td style="text-align:left;"> $SPY https://www.investopedia.com/articles/analyst/030102.asp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:16:20 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

tesla fanboys after fomo’ing in and buying elon’s bags... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:16:18 </td>
   <td style="text-align:left;"> $SPY sorry cucks, tomorrow&amp;#39;s jobs report will have you sobbing on the floor while my puts print mucho dolarinos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:16:18 </td>
   <td style="text-align:left;"> $SPY crude oil and energy trajectory is concerning. Recession is near. Crash is coming. Less than 6 months this market is getting obliterated </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:16:15 </td>
   <td style="text-align:left;"> $SPY I support a stockmarket crash... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:16:07 </td>
   <td style="text-align:left;"> $SPY $DWAC 

https://newspunch.com/austrian-constitutional-court-puts-govt-on-notice-prove-pandemic-is-not-a-scam-or-end-restrictions/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:15:56 </td>
   <td style="text-align:left;"> $SPY tomorrow’s action will be totally determined by options &amp;amp; how MMs are going to fuck the holders 
If you see green no matter how small take it eventually all will be worthless </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:15:48 </td>
   <td style="text-align:left;"> $SPY Scalping SPY with this volatility has been tremendous. I hope volatility continues 🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:15:33 </td>
   <td style="text-align:left;"> $SPY if it’s green now then red in PM … we all know the drill </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:15:27 </td>
   <td style="text-align:left;"> $SPY I bet whoever is been shorting buys puts first, spread fud and reports and bans the other side lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:15:00 </td>
   <td style="text-align:left;"> $SPY cost money to feed  a 130 thousand soldiers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:14:55 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $AMZN

Dollar a very good tell now, keep 👀 it.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:14:51 </td>
   <td style="text-align:left;"> $SPY 

https://www.lifesitenews.com/blogs/french-resistance-to-covid-tyranny-grows-spreads-to-alpine-mayors/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:14:42 </td>
   <td style="text-align:left;"> $SPY interest rates are just noise this time around....wait...I think😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:14:39 </td>
   <td style="text-align:left;"> $SPY 460 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:14:39 </td>
   <td style="text-align:left;"> $SPY $AMZN $GOOG $AAPL $MSFT 

Most of the big tech earnings are out the way now so they’re not being propped up watch out below 📉 sell into the rally take profits or look for shorts 📉 we are not liking the pump and dumps! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:14:06 </td>
   <td style="text-align:left;"> $SPY wake </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:13:48 </td>
   <td style="text-align:left;"> $SPY AOC is probably the 3rd dumbest person on earth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:13:41 </td>
   <td style="text-align:left;"> $SPY this is testing 9ema on daily bet it holds then retraces to test the big downtrend then goes back and forth till it’s squeezed out and up for a long drawn out low volume pump into q.e. And through all your bs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:13:35 </td>
   <td style="text-align:left;"> $SPY it looks like the ground  is frozen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:13:33 </td>
   <td style="text-align:left;"> S&amp;amp;P Futures 
4,506.75 
+37.75(+0.84%) 
Dow Futures 
35,088.00 
+117.00(+0.33%) 
Nasdaq Futures 
14,720.25 
+228.00(+1.57%) 
Russell 2000 Futures 
1,993.90 
+7.50(+0.38%) 
 
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:13:18 </td>
   <td style="text-align:left;"> $SPY 

Yield curve </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:13:08 </td>
   <td style="text-align:left;"> $SPY $QQQ  Tomorrow should be wild. Bearish/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:13:04 </td>
   <td style="text-align:left;"> $SPY amazon snubbed the report to save the stock. Truth will be out tomorrow when the whistle blower comes out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:12:59 </td>
   <td style="text-align:left;"> $DAX Here is a 4 Hour chart from Jan 27th to members at https://elliottwave-forecast.com, showing the path lower and also reaction higher. Very nice. $FTSE $SPX $SPY $ES_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:12:36 </td>
   <td style="text-align:left;"> $SPY stops at 450 ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:12:28 </td>
   <td style="text-align:left;"> $SPY rippin again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:12:03 </td>
   <td style="text-align:left;"> $SPY is it true that Biden speaks tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:11:59 </td>
   <td style="text-align:left;"> $SPY 460 tomorrow after all who knew </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:11:59 </td>
   <td style="text-align:left;"> $SPY #chatwiththetraderslivesessions TWITCH (OTWSTEAM) Go to meeting: https://global.gotomeeting.com/join/849329269 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:11:49 </td>
   <td style="text-align:left;"> $AMZN if you read the report you will know the state of the economy. 7% inflation, labor cost up, spending down. 1Q is going to be really bad $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:11:48 </td>
   <td style="text-align:left;"> $DAX The Index is reacting higher off the Blue Box area. Here is early on the year 4 Hour chart to members at elliottwave-forecast.com, showing the proposed buying area lower. #elliottwave #trading $FTSE $SPY $SPX $ES_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:11:33 </td>
   <td style="text-align:left;"> $SPY $AMZN $GOOG $AAPL Jobs report a 8:30. I think the price is baked in, but MM will look for any excuse to have some volatility, as they are making money on each swing because they know what&amp;#39;s coming. (Criminal, actually.) Definitely some fuckery with green Fridays lately. Tomorrow will be interesting heading into another week of earnings with some likely surprise beats to keep things nice and choppy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:11:11 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:10:43 </td>
   <td style="text-align:left;"> $SPY holy poop, HSI&amp;#39;s ripping like a betch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:10:31 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

“To ThE MoOoOoOoN!!!!” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:10:04 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA FUTES SLIPPIN HIDE YO CANOES 🛶🛶🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:09:48 </td>
   <td style="text-align:left;"> $SPY 🦆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:09:33 </td>
   <td style="text-align:left;"> $SPY $QQQ Who had puts printing today and then had everything reverse on them? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:09:28 </td>
   <td style="text-align:left;"> $SPY What do i buy? With the money i make from poots? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:09:20 </td>
   <td style="text-align:left;"> $SPY futures are 42 points higher than the close. but red from the open. spy closed after hours only being 0.30 points higher (not percentage) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:09:13 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA tmrw is prolly the last day to truly get out of the speculation and into the profits. Everything will take a hit of course because of leveraging and margins and other dynamics but fact remains we got a lot of downside risk and appetite with very little upside as far as equities go but either way. For 20 Years the US stock market has had a bullish run but in between those years was lots of brutal battles that was topped off with the biggest money printing in history. We shall see where the chips may fall but this sure looks like a multi-year top to me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:09:06 </td>
   <td style="text-align:left;"> $SPY all of you complaining about volatility praying you’re on the right side of things; are not ready to trade catalyst-driven seasons. You need to study up. You should know your option Greeks and use them as a tool to limit gamma exposure. 457.50-460 obviously was gonna be heavy resistance. It was like the third major point in a multi month trend. Everyone playing same stock,same indicators. Reacting to losing money just like you. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:09:06 </td>
   <td style="text-align:left;"> $SPY bruh the way they doing retail is just wrong🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:08:47 </td>
   <td style="text-align:left;"> $SPY Just sitting here, clowning around. Might get a hooker. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:08:41 </td>
   <td style="text-align:left;"> $SPY I think bears are looking at yesterdays futures chart or I am going nuts which one is it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:08:41 </td>
   <td style="text-align:left;"> $SPY $AMZN 

Huge fan of Amazon but let’s be honest, missed on everything including GUIDANCE. EPS was pumped only by $RIVN 

Be careful and smart out there ppl. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:08:37 </td>
   <td style="text-align:left;"> $SPY $MRNA if you die it means it works … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:08:35 </td>
   <td style="text-align:left;"> $PINS $NVAX $SPY ;;;&amp;#39;&amp;#39;&amp;#39; 
 
 
Account Challenge Update:-  
Start Date: Jan 3, 2022  
Starting Balance: $1,700  
Current Balance: $74,729 
Goal: $100,000 by end of February.  
Strategy: Swing Trade Options, Stocks  
  
Watch out for next play👓 amazing-chat-room.stocksboss.xyz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:08:21 </td>
   <td style="text-align:left;"> $SPY Without any trolling, Cathy definitely has to change something in her strategy. Maybe more patience and technical analysis needed. 
Ark Invest ETF: 
Snap Inc. SNAP February 3, 2022 SELL 
Twitter TWTR February 3, 2022 SELL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:07:53 </td>
   <td style="text-align:left;"> $SPY if futes aren’t up at least 2% Idgaf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:07:31 </td>
   <td style="text-align:left;"> $SPY those guys sleep with their sister⬇️⬇️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:07:15 </td>
   <td style="text-align:left;"> $SPY can I get a yerrrrr!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:07:07 </td>
   <td style="text-align:left;"> $SPY If you don&amp;#39;t know what Elliot Ness waves are, you shouldn&amp;#39;t be trading. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:07:02 </td>
   <td style="text-align:left;"> $SPY I got a dream last night. I bought 1 put and it made a billion. I woke struggling to know exact number </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:06:55 </td>
   <td style="text-align:left;"> $SPY $QQQ &amp;quot;Omicron-Related Absenteeism May Have Lowered January Nonfarm Payrolls by 1 Million&amp;quot; 
lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:06:45 </td>
   <td style="text-align:left;"> $SPY  
Bunk beds? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:06:43 </td>
   <td style="text-align:left;"> $SPY 😩😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:06:42 </td>
   <td style="text-align:left;"> $SPY $QQQ Short $CL_F @ $90.80 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:06:29 </td>
   <td style="text-align:left;"> $SPY no I don’t ⬇️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:06:17 </td>
   <td style="text-align:left;"> More $TCEHY $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:05:52 </td>
   <td style="text-align:left;"> $SPY this guy sleeps with his sister⬆️⬆️⬆️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:05:50 </td>
   <td style="text-align:left;"> $SPY I was bear yesterday and turned to bull into close, identity crisis but next week who knows I think we‘ll tank but tmrw should be a nice g___n new deal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:05:05 </td>
   <td style="text-align:left;"> $SPY i like physical silver </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:05:03 </td>
   <td style="text-align:left;"> $SPY bulls finna eat good tmrw 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:04:57 </td>
   <td style="text-align:left;"> $AMZN $SPY $QQQ “the stock market isnt the economy! the economy isnt the stock market” but the stock market is only apple google facebook and amazon! those are the only companies! so when amazon goes up that means airlines and oil should go up! when apple goes up that mean biotech goes up! makes a lot of sense. 
i mean at least with facebook, it brought down tech stocks.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:04:48 </td>
   <td style="text-align:left;"> $SPY let the selloff begin 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:04:38 </td>
   <td style="text-align:left;"> $SPY $QQQ BULLS = REPUBLICANS 🇺🇸🦅
BEARS = DEMONCRAPS 👹💩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:04:10 </td>
   <td style="text-align:left;"> $SPY If you take a non aggressive stand against somebody fading you, bulls will sell too </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:04:10 </td>
   <td style="text-align:left;"> $SPY 

State Dept.: Russia is going to launch a false flag attack as a pretext to invade Ukraine.

Reporter: What&amp;#39;s your evidence?

State Dept.: I just gave it to you.

Reporter: No, you made an allegation.

State Dept.: Yes, that&amp;#39;s the evidence.

Reporter 🙄

No matter what you think about politics, this is comical!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:03:53 </td>
   <td style="text-align:left;"> $SPY 🌻🦆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:03:47 </td>
   <td style="text-align:left;"> $SPY where&amp;#39;s my shame? Here&amp;#39;s another shameless pump. Yes I own shares. 

$MDMP 84 million barrels of proven oil reserves. Fracking operation is days away from starting up (from what I heard, Im the world&amp;#39;s laziest researcher outside of chart patterns and trading strategies). 

It&amp;#39;s Pink sheeit so who knows how many shares are out but QuestTrade says around 250 million. 

Ran to just under $1 last year. It&amp;#39;s moving. If this chart doesn&amp;#39;t excite you then you are a brainless zombie with shit for brains. 

😂 

Do your own diligence. In fact dig deep and share cause im too lazy too. 

Can I get a high five for my honesty? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:03:46 </td>
   <td style="text-align:left;"> $SPY every bull in here deserve to have a step-sis 🤝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:03:37 </td>
   <td style="text-align:left;"> $SPY 

&amp;quot;Noem signs bill banning transgender participation in girls sports

Noem positioned her signing of the bill as a defense of Title IX&amp;quot;

Well at least someone is standing up for women and it isn&amp;#39;t the feminists on the left who do nothing but harm women and girls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:02:26 </td>
   <td style="text-align:left;"> $SPY All of you futures watchers are just setting yourself up for disappointment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:02:20 </td>
   <td style="text-align:left;"> $SPY wish all you want, anything is possible in this ungodly volatility. pray to be on the right side. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:02:00 </td>
   <td style="text-align:left;"> $SPY those worthless puts will be 0.01  instead of 1.80  when you wake up they won’t come back miraculously, I had that dream so many times so I can relate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:01:23 </td>
   <td style="text-align:left;"> $SPY my neighbor sold his used car. Within 30 mins, 40 messages to buy. What’s going on? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:00:40 </td>
   <td style="text-align:left;"> $SPY  
 
I feel like MM is a team of 3 people and a cat.  It used to be a larger group before &amp;quot;they&amp;quot; and darkpool splintered off.  Been like watching game of thrones. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:00:28 </td>
   <td style="text-align:left;"> $SPY crazy to think we’ll hit $457 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:00:22 </td>
   <td style="text-align:left;"> Futures going wild $spy $amzn $qqq $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 10:00:18 </td>
   <td style="text-align:left;"> $SPY 

GD hold your bezo gains until morning. 

Need a higher price for entry. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:59:58 </td>
   <td style="text-align:left;"> $SPY do you think we’ll be using plastic credit cards in 2050? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:59:36 </td>
   <td style="text-align:left;"> $SPY panic shorting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:59:14 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m glad I exited my 454 calls on that Amazon pump at EOD, but I&amp;#39;m afraid my $FB 240 calls may be fooked tomorrow... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:59:11 </td>
   <td style="text-align:left;"> $FB . Just a couple calls. We made. In past couple days. That were on point. You could banked like us. We time stamp alerts and review plays. And look out for each other. Like calling pump and dumps by big furus. Come join free community. Link in bio. We bank hard and joke around! $MTEK $KAVL $XELA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:59:00 </td>
   <td style="text-align:left;"> $SPY really leaning towards an ABC corrective wave completion around $460-$470 before panic dump to lower lows… such a move would be a true confirmation of a downtrend… and we’d probably be seeing sub $400 before spring. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:58:58 </td>
   <td style="text-align:left;"> $SPY $QQQ  jobs report don’t matter tomorrow cuz $AMZN right? 
lets piggy back like we did with apple microsoft google and facebook lmao. very healthy stock market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:58:38 </td>
   <td style="text-align:left;"> $SPY inverse this guy 😂 👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:58:38 </td>
   <td style="text-align:left;"> $TSLA $amzn $spy puts be like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:58:20 </td>
   <td style="text-align:left;"> $SPY any dip I&amp;#39;m just gonna buy google before the split for real. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:58:15 </td>
   <td style="text-align:left;"> $SPY 
$AMZ numbers fishy

Amazon’s overall operating income, which did not reflect the increased value of the Rivian stake, was cut nearly in half, to $3.5 billion, from $6.9 billion the fourth quarter of the prior year, providing a more telling view of the state of the company’s business. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:58:14 </td>
   <td style="text-align:left;"> $SPY  
 
I&amp;#39;ll reiterate:  Leaving Facebook and flocking to Amazon, is like leaving AIG and fleeing to Bear Sterns. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:58:04 </td>
   <td style="text-align:left;"> $SPY  
 
What if there is more than one MM tho? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:57:46 </td>
   <td style="text-align:left;"> $MWWC $SPY shameless micropenny pump. Yes I own shares. Coming to a conclusion in the triangle AND next week management is going on a PR blitz starting on the 8th. 

It&amp;#39;s a baby crypto miner with a with some other cool feature that I don&amp;#39;t understand or really care about. What I do know is that the CEO got a multimillion dollar loan to get the crypto operation going and had been retiring shares to reduce the share count. .

If you like long shots with above average odds jump in board before the hype. When your grandma talks about thats my cue to sell 😂

Holding for .07 price target. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:57:43 </td>
   <td style="text-align:left;"> $SPY  just volatility welcome to markets 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:57:21 </td>
   <td style="text-align:left;"> $SPY anyone have how many calls to puts expiring tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:57:20 </td>
   <td style="text-align:left;"> $SPY This all you need to know ,To be bear 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:57:15 </td>
   <td style="text-align:left;"> $SPY rookie mistake 1: unless you&amp;#39;re selling, never fuck with near term options. Both puts and calls. Why? Because you don&amp;#39;t fuck with the mm. The MM always wins. 

Rookie mistake 2: close your positions at least 10 days before the option expires. Why? Because, you don&amp;#39;t fuck with the MM. The mm always wins. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:57:13 </td>
   <td style="text-align:left;"> $SPY &amp;quot;Gay, lesbian adults report higher COVID vaccination rates&amp;quot; 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:57:10 </td>
   <td style="text-align:left;"> $SPY Futes about to be red by midnight 🤣

Amazon about to drop 300 by market open 

Tomorrows gonna be a wild day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:56:56 </td>
   <td style="text-align:left;"> $SPY futures ripin and bears all out full panic mode starring at the numbers on the display celebrating every red candle after 4 green. Go to bed you are fucked it happens to me all the time sometimes I even like it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:56:39 </td>
   <td style="text-align:left;"> $SPY to keep it a stack thoe, this update trash asf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:56:08 </td>
   <td style="text-align:left;"> $SPY scratch-off have better trading and probabilities </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:56:02 </td>
   <td style="text-align:left;"> $SPY those last three candles tho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:56:01 </td>
   <td style="text-align:left;"> $AMZN forward looking investors will sell this asap tomorrow. Really bad report if you dig deeper $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:55:52 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:55:41 </td>
   <td style="text-align:left;"> $PFE Justin Castreau faking vaccination $MRNA $SPY  still he got Covid. after being fully vaccinated. 
https://www.bitchute.com/video/0buuHGUx2oiw/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:55:41 </td>
   <td style="text-align:left;"> $SPY 458 retest before selling off? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:55:31 </td>
   <td style="text-align:left;"> $SPY Futes aren&amp;#39;t doing anything special </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:55:26 </td>
   <td style="text-align:left;"> $AMZN $SPY $QQQ $DIA Market gave us the perfect short entry after close. Market direction is simply down since Fed is no longer pumping money into the economy. Take cue from bond yields not Amazon whose multiple will have to come down. I am perfectly happy with my short and Put spreads. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:54:56 </td>
   <td style="text-align:left;"> $SPY I support this chart so I’m buying puts in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:54:50 </td>
   <td style="text-align:left;"> $SPY pump fake </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:54:41 </td>
   <td style="text-align:left;"> $SPY $QQQ $XLK Dollar heading to 94, yet, more bearish market understanding for you. 

Less $ means more spending globally, hence, more inflation. . And, ra....

Dollar is foretelling a coming rate hike March + QE ending.

Also, a weak dollar means foreign sales diminish for American companies and we are such a global world for sales , from industrial to manufacturing to SHOPPING, this weakening dollar like NOW leads to less profit per foreign customer, that really adds up--quickly-- when you consider we have over 8000 businesses in USA on stock exchange and daily that the dollar is weak--in &amp;quot;a global economy&amp;quot;. 

Following me yet? 😉

#Rates go up w/ weakening dollar because more domestic buys done and so rates go up to curtail this American consumer spending.....🛑

So, Amazon ER was weak for many reasons past Rivian and since a global company and weak dollar OCTOBER AND NOVEMBER, Bezos decided non-operating income needed, so bought Rivian stake 15%. 
But, that is INORGANIC GROWTH1🚨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:54:21 </td>
   <td style="text-align:left;"> $SPY suspicious those PPT fauks did very little today … 1 V all day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:54:17 </td>
   <td style="text-align:left;"> Green Goose Course time!
We stack $AAPL &amp;amp; $SPY in this strategy!
Been killing it since 2015💪😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:53:24 </td>
   <td style="text-align:left;"> $SPY I would feel much better about this if the day didn&amp;#39;t end the way that it did. Felt like everyone was rushing for door all at once </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:53:20 </td>
   <td style="text-align:left;"> $SPY $FB your boy liberal leader and Zuck are leading you further down. Nice logic citing for this clown. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:52:59 </td>
   <td style="text-align:left;"> $SPY 453 open would be hilarious </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:52:52 </td>
   <td style="text-align:left;"> $SPY $457 is a key resistance if we break it look in the rear mirror and say bye 👋 #slaterthepigs/bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:52:25 </td>
   <td style="text-align:left;"> $PALI we warned so many people pali was a pump and dump by zack and others. some other calls we made in past couple days. not mentioning  other mega calls we made. we time stamp and review alerts and joke around and watch out for each other. come join free community. link is in bio. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:52:24 </td>
   <td style="text-align:left;"> $SPY  I lost money on the option sold at loss </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:52:10 </td>
   <td style="text-align:left;"> $SPY if futures go red remember this song.

Bad job data and bad inflation data?

Enjoy the win of the battle this week because the war next week will be ugly.

https://youtu.be/yWabGQBnzKo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:52:09 </td>
   <td style="text-align:left;"> $SPY damp it … stuck with poots expiring tomorrow fml </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:52:09 </td>
   <td style="text-align:left;"> $SPY this will tank </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:52:05 </td>
   <td style="text-align:left;"> $SPY Just make walls and let bears fight each other, they aren&amp;#39;t that loyal to hold long term </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:51:51 </td>
   <td style="text-align:left;"> $SPY $QQQ “Biden will address tomorrow’s job report at 10:45am ET”
lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:51:39 </td>
   <td style="text-align:left;"> $SPY Futes Loosing steam </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:51:34 </td>
   <td style="text-align:left;"> $SPY uh oh futes ain&amp;#39;t looking so hot... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:51:31 </td>
   <td style="text-align:left;"> $SPY red futures yikes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:51:23 </td>
   <td style="text-align:left;"> $SPY Bears on here thinking they gonna be the next Jesse Livermore at 8 pm ..... then 8 am comes...... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:51:20 </td>
   <td style="text-align:left;"> $SPY The U.S. Government now mostly relies on private industry to silence dissent. Many of these companies, which are ideologically aligned with the Marxist Globalist regime, now have more power than the federal government can ever dream of. Facebook is introducing messages that ask users to snitch on their potentially “extremist” friends, which considering the platform’s bias seems mainly to target the political right. 
https://rumble.com/vtyr34-democrats-are-pressuring-companies-to-censor-for-them-a-violation-of-the-fi.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:50:55 </td>
   <td style="text-align:left;"> $SPY Worst thing bulls could do is panic sell, so bears make more money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:50:53 </td>
   <td style="text-align:left;"> $SPY Crude oil never ending pump🤡🤡🤡🤡😒😒🤬🤬🤬🤬🤬🤬🤬🤬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:50:49 </td>
   <td style="text-align:left;"> $SPY A lot of retail bears on here sound like crack heads...chill the hell out. You lost today. Long term the market should correct but thinking you will get a daily correction is just plain retarded. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:50:41 </td>
   <td style="text-align:left;"> $SPY man can the opening bell come any sooner? I’m antsy to see my gains from AMZN calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:50:27 </td>
   <td style="text-align:left;"> $SPY bears the head n shoulder is already priced in, get over it 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:50:24 </td>
   <td style="text-align:left;"> $SPY $AMZN $F 

Don’t y’all find it interesting how the same “analysis” who are praising Amazon about their investment in RIVN calling it bold are the same one’s who are bashing Ford saying that investing in RIVN was a risky investment. I swear we really do live in a clown world... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:50:22 </td>
   <td style="text-align:left;"> $SPY futures already dripping a bit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:50:10 </td>
   <td style="text-align:left;"> $SPY monthly MACD .01 points away from crossing bearish.  Waiting a while for that to happen.  The US dollar index left the same exact gap @ 95.25.  There is a gap on the daily at 453.  This could rally to 453 tomorrow.  Or.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:50:05 </td>
   <td style="text-align:left;"> $SPY  
 
That, ladies and gentlemen, is a down channel.    
 
Glad to see the censorship nannies get hurt today.  The ones who left Facebook and fled to Amazon, are about to learn why, when a major sector component takes a -26% shot to the head, you leave the entire sector immediately. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:50:04 </td>
   <td style="text-align:left;"> $SPY 
I bought calls 2 calls on snap
And 1 on spy at close...probably peanuts to some but I&amp;#39;m excited....big win for my little portfolio. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:49:47 </td>
   <td style="text-align:left;"> $SPY all gains evaporating </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:49:32 </td>
   <td style="text-align:left;"> $DWAC $SPY $AMZN $BTC.X WASHINGTON, D.C—The National Debt has skyrocketed up to $30 trillion, years before expected. Desperate to solve this crisis, President Biden has called 877-CASH-NOW to cover the debt and hopefully score a much needed political win.

“Listen here, Jack, I’m as serious as a heart attack. No monkey business, for real. Now, can you provide me with CASH NOW or not?” said the President. “I need a clean slate, a total debt cancellation here. The American people are counting on me.”

https://babylonbee.com/news/biden-calls-877-cash-now-to-solve-30-trillion-national-debt-crisis </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:49:29 </td>
   <td style="text-align:left;"> $SPY I wouldn&amp;#39;t be surprised that I&amp;#39;ll be surprised tomorrow. 🤷 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:49:26 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures surging as expected, probably will go up all night long on the strong Amazon earnings and also in anticipation of a strong jobs report tomorrow morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:49:20 </td>
   <td style="text-align:left;"> $SPY Kill them with kindness .. and then fart as you walk away. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:49:07 </td>
   <td style="text-align:left;"> $SPY 

The new update makes me keep updating.

Somebody’s fired. Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:49:03 </td>
   <td style="text-align:left;"> $SPY bruh Amazon pumped this thing so much, even natural gas is rising. 

Wtf does Amazon have to do with natural gas Please somebody, anybody explain . 

Smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:48:55 </td>
   <td style="text-align:left;"> $SPY futures keep dropping. May just open around flat 450 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:48:28 </td>
   <td style="text-align:left;"> $SPY stocks selling, crypto selling, bonds selling, dollar down - where does it go? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:48:22 </td>
   <td style="text-align:left;"> $SPY I am glad I sat out today, was gonna buy a put this morning, would be happy all day, then bam, big loss.  Not sure where the market is going. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:48:17 </td>
   <td style="text-align:left;"> $SPY time for the night shift.  Can you guess who’s on the left? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:47:52 </td>
   <td style="text-align:left;"> $SPY fuck I hope I can close my $460 calls for a slight profit at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:47:45 </td>
   <td style="text-align:left;"> $SPY adding to my puts tomorrow from my $snap profits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:47:45 </td>
   <td style="text-align:left;"> $SPY I think we get bad news over night or tomorrow to retest 447… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-04 09:47:36 </td>
   <td style="text-align:left;"> $SPY I feel like market’s gonna sell off tomorrow, open green end blood red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:35:42 </td>
   <td style="text-align:left;"> $QQQ Tech futures:  
 
Can we close the week above the 50 week MA?   AMZN says YES but there&amp;#39;s also the job report pre-market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:32:35 </td>
   <td style="text-align:left;"> $QQQ $NQ_F y’all see these pristine bull flag right lol. Price is getting ready to execute on it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:32:00 </td>
   <td style="text-align:left;"> $QQQ if I could see 5 minutes into the future I wouldn’t bought fb puts 🤓 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:31:13 </td>
   <td style="text-align:left;"> $QQQ the short play tomorrow is AMZN if enough of the market gets ticked on the rivian EPS scandal. Likelihood algo buying came in after hours. Who knows though markets can always remain irrational. Let’s see that jobs report as well in the AM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:30:42 </td>
   <td style="text-align:left;"> $SPY $QQQ futes sweet bounce of VWAP ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:29:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $USO $UCO super long term chart of oil.  Yellow is where we are going.  Who wants at least a 20% gain relatively quickly? 😏🤘 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:29:38 </td>
   <td style="text-align:left;"> $SPY $QQQ the market is not done tanking but your weekly puts are for sure fucked. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:28:02 </td>
   <td style="text-align:left;"> $QQQ $SPY $SNAP $FB 

WHOES NEXT?!? Anyone else eying the earnings calendar for our next victim?!?!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:27:41 </td>
   <td style="text-align:left;"> $TSLA $GOOGL $QQQ $F now I&amp;#39;m used to losing money left and right in the mkt but good luck to bears and &amp;quot;bulls with big balls&amp;quot; amen 🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:27:34 </td>
   <td style="text-align:left;"> $QQQ Oh my, bears everywhere... I better get my 30 30 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:25:59 </td>
   <td style="text-align:left;"> $QQQ $SPY 

Put me on the bench
Cause I ain’t playing withchu dummies 

https://music.apple.com/us/album/abnb/1606729791?i=1606730189 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:25:46 </td>
   <td style="text-align:left;"> $QQQ this rollercoaster probably won&amp;#39;t end soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:24:51 </td>
   <td style="text-align:left;"> $SPY $QQQ $FB $DWAC #TRUMPB42024 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:22:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $SPXL Bears WILL take over soon, and, contrary to many&amp;#39;s understanding, BEARS are superior at understanding markets over bulls in a downtrend. 
They understand what&amp;#39;s going on, because they are betting on that understanding and the ones MAKING THE RIGHT ENTRIES AND NAILING RIGHT DIRECTIONAL MOVES OF MARKET.

Now bears are bulls too, keep in mind, a lot, they are both superior chartists as well as full envelopers of the macro picture and why markets popping ir dropping. 

They will question you too by moving market directionallh.
Often in futures they give us resistance and support clues. They trade NIGHT &amp;amp; DAY, you might think it is Tutes moving market but it is really the highly intelligent bears. , they. are. that. good. at what they do. $ES_F 
@sonicmerlin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:21:47 </td>
   <td style="text-align:left;"> $QQQ Sell the rip, it will dip! 💵
Biden
Russia
J Powell raising fed funds rate
Inflation
Unemployment number better,3.6%, green light for Powell to raise 50 bps in March

Buy Puts! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:20:45 </td>
   <td style="text-align:left;"> $SPY $QQQ So $FB drives the entire market down but $AMZN picks it up? What is this bullshit? What are these retarded algorithms? What the fuck actually goes on on the market? It&amp;#39;s fucking senseless. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:19:15 </td>
   <td style="text-align:left;"> $SPY $QQQ funny how bulls still don’t understand what a bear market is..it’s many trapped bulls looking to gtfo on any rip. Stop buying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:19:03 </td>
   <td style="text-align:left;"> $AMZN you Know Right ... they made up Number from selling  $RIVN at $100  poor $tsla bulls  
$qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:18:30 </td>
   <td style="text-align:left;"> $SPY $QQQ Worst case there will be just one rate hike in March &amp;amp; back off, pmi plummeting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:17:47 </td>
   <td style="text-align:left;"> $AMZN $SNAP $QQQ $SPY   i&amp;#39;m a bear, a swing trader and i love dead cat bounces </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:16:43 </td>
   <td style="text-align:left;"> $AAPL $amzn $snap $qqq

Thanks to amzn and snap which market will be so bullish tomorrow unlike fking stupid fb!!!

Everyone beat er they the only one drop pos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:16:36 </td>
   <td style="text-align:left;"> $QQQ $SPY  every paid basher is out in their 15 accounts… you know big money wants those fear shares badly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:16:20 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

tesla fanboys after fomo’ing in and buying elon’s bags... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:15:59 </td>
   <td style="text-align:left;"> $QQQ job report will be better than expected per usual and this gains all ground lost today + more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:14:55 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $AMZN

Dollar a very good tell now, keep 👀 it.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:14:29 </td>
   <td style="text-align:left;"> $QQQ alot of emotion out there in the markets now!  Hence FB wayyyyy overdone.  I bought heavy in $TQQQ.  Money printer going brrrrrrrrr over next few Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:13:08 </td>
   <td style="text-align:left;"> $SPY $QQQ  Tomorrow should be wild. Bearish/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:11:07 </td>
   <td style="text-align:left;"> $QQQ Amazon pe is 60….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:10:31 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

“To ThE MoOoOoOoN!!!!” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:10:04 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA FUTES SLIPPIN HIDE YO CANOES 🛶🛶🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:09:33 </td>
   <td style="text-align:left;"> $SPY $QQQ Who had puts printing today and then had everything reverse on them? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:09:13 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA tmrw is prolly the last day to truly get out of the speculation and into the profits. Everything will take a hit of course because of leveraging and margins and other dynamics but fact remains we got a lot of downside risk and appetite with very little upside as far as equities go but either way. For 20 Years the US stock market has had a bullish run but in between those years was lots of brutal battles that was topped off with the biggest money printing in history. We shall see where the chips may fall but this sure looks like a multi-year top to me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:09:01 </td>
   <td style="text-align:left;"> $QQQ stock is trade for future. Amazon will have a big trouble for the next quarter…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:06:55 </td>
   <td style="text-align:left;"> $SPY $QQQ &amp;quot;Omicron-Related Absenteeism May Have Lowered January Nonfarm Payrolls by 1 Million&amp;quot; 
lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:06:42 </td>
   <td style="text-align:left;"> $SPY $QQQ Short $CL_F @ $90.80 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:04:57 </td>
   <td style="text-align:left;"> $AMZN $SPY $QQQ “the stock market isnt the economy! the economy isnt the stock market” but the stock market is only apple google facebook and amazon! those are the only companies! so when amazon goes up that means airlines and oil should go up! when apple goes up that mean biotech goes up! makes a lot of sense. 
i mean at least with facebook, it brought down tech stocks.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:04:38 </td>
   <td style="text-align:left;"> $SPY $QQQ BULLS = REPUBLICANS 🇺🇸🦅
BEARS = DEMONCRAPS 👹💩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:04:08 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 10:00:22 </td>
   <td style="text-align:left;"> Futures going wild $spy $amzn $qqq $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:59:44 </td>
   <td style="text-align:left;"> $QQQ looks like this will fade in the morning lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:59:39 </td>
   <td style="text-align:left;"> Trade alert on $SQQQ delivered today at 10:58AM CDT on 2/3/2022 🎯

Server link in the bio for winning alerts and for those eager to learn. $TQQQ $QQQ $NQ_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:59:24 </td>
   <td style="text-align:left;"> $AMZN $QQQ strip out the retail sales from Amazon, and you have AWS at $71 billion run rate growing at 40%, and ads ar $38.8 billion run rate on advertising growing at 32%.  If retail was worth zero, this alone is worth more than the entire market cap. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:58:58 </td>
   <td style="text-align:left;"> $SPY $QQQ  jobs report don’t matter tomorrow cuz $AMZN right? 
lets piggy back like we did with apple microsoft google and facebook lmao. very healthy stock market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:56:50 </td>
   <td style="text-align:left;"> $QQQ bears tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:55:26 </td>
   <td style="text-align:left;"> $AMZN $SPY $QQQ $DIA Market gave us the perfect short entry after close. Market direction is simply down since Fed is no longer pumping money into the economy. Take cue from bond yields not Amazon whose multiple will have to come down. I am perfectly happy with my short and Put spreads. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:54:41 </td>
   <td style="text-align:left;"> $SPY $QQQ $XLK Dollar heading to 94, yet, more bearish market understanding for you. 

Less $ means more spending globally, hence, more inflation. . And, ra....

Dollar is foretelling a coming rate hike March + QE ending.

Also, a weak dollar means foreign sales diminish for American companies and we are such a global world for sales , from industrial to manufacturing to SHOPPING, this weakening dollar like NOW leads to less profit per foreign customer, that really adds up--quickly-- when you consider we have over 8000 businesses in USA on stock exchange and daily that the dollar is weak--in &amp;quot;a global economy&amp;quot;. 

Following me yet? 😉

#Rates go up w/ weakening dollar because more domestic buys done and so rates go up to curtail this American consumer spending.....🛑

So, Amazon ER was weak for many reasons past Rivian and since a global company and weak dollar OCTOBER AND NOVEMBER, Bezos decided non-operating income needed, so bought Rivian stake 15%. 
But, that is INORGANIC GROWTH1🚨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:54:37 </td>
   <td style="text-align:left;"> $QQQ After seeing what happened with all the other beats I’ll wait until tomorrow afternoon to figure out bias. Bears have been holding the key resistance levels so far so it’s their game until they lose it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:51:51 </td>
   <td style="text-align:left;"> $SPY $QQQ “Biden will address tomorrow’s job report at 10:45am ET”
lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:49:46 </td>
   <td style="text-align:left;"> $AMZN THIS ABOUT AS UNETHICAL AS CAN GET FOR AN ER SOME GAAP VIOLATIONS IN THERE FINANCIAL ENGINEERING AT ITS MOST OBVIOUS  $QQQ WEL SEE IF MY PUTS DONT PRINT TOMORROW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:49:26 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures surging as expected, probably will go up all night long on the strong Amazon earnings and also in anticipation of a strong jobs report tomorrow morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:47:24 </td>
   <td style="text-align:left;"> $SPY $QQQ Cathie Woods sold $SNAP and $TWTR before the pop tonight, oh god she is such a bad trader 🥲 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:47:21 </td>
   <td style="text-align:left;"> $QQQ face ripper tomorrow after a shit job report confirms no rate hikes. 
 
the fed is very onvious in their thinking and basically say as much: they won’t raise rates if employment isnt great </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:46:44 </td>
   <td style="text-align:left;"> $QQQ $SPY the market is sorting through the winners and the losers in a big way right now.  Every earnings miss is punished with a 30% loss, and most beats will erase a good chunk of the correction thus far. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:46:12 </td>
   <td style="text-align:left;"> $QQQ retest of today&amp;#39;s high and then retest of last week lows.

Byeee </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:46:03 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ $VIX
 
You should’ve at least learned one thing over the last few weeks: DO THE OPPOSITE OF WHATEVER SEEMS OBVIOUS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:45:40 </td>
   <td style="text-align:left;"> FUTES GREEN AF!!! $QQQ $SPY $AMZN $AMD $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:45:26 </td>
   <td style="text-align:left;"> $AMZN $TSLA $AAPL $SPY $QQQ  
 NASDQ and S&amp;amp;P futures:  
Unable to break supply line even with AMZN earnings. 
Bearish divergence about to be confirmed on RSI and MACD for 15 mins. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:44:10 </td>
   <td style="text-align:left;"> $FNGU $QQQ $SPY Market is not looking good! We could see roller coaster down! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:42:37 </td>
   <td style="text-align:left;"> It’s looking to me like a gap n crap. This was the last big earnings. There’s no more to save the market when it’s in decline. There’s just the tightening fed now. $spy $qqq $amzn $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:42:14 </td>
   <td style="text-align:left;"> $AMZN Alright....so this Rivian thing isn&amp;#39;t as crazy as it sounds at a glance.

So Stocks are valued based on Operating Income. Rivian was Non Operating Income as the had not sold the shares. 

That&amp;#39;s not enough for the bears, I understand. So add to this that their next EPS will not be affected by RIVN drawdown from ATHs because Extraordinary stock gains or losses are not included in &amp;quot;Operating Earnings&amp;#39; which are far more important than &amp;quot;non operating earnings&amp;quot;.

So when you really think about this it does make sense. Especially when you consider that  the only thing that matters is how a companies business is doing. In this case; Doubled profit margins. Saw an AWS growth rate of 40%, Ad revs are so massive that the SEC is requiring them to actually disclose these revenues separately. An area in which FB failed miserably in. With other reports today (snap) the market sees that companies are doing well without cookies. 

Business is a booming. This is a bullish report.
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:41:57 </td>
   <td style="text-align:left;"> $QQQ Still in cash for a bit longer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:41:18 </td>
   <td style="text-align:left;"> $QQQ back to 14500 like that fake pump never happened. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:41:17 </td>
   <td style="text-align:left;"> $SPY $QQQ $SOXL Rates-rates-rates. And, oil over $90 a barrel, now, in what world is this going to be a good outcome? 

#INFLATION
#FEDFORCEDQEENDMARCH
#0.75% 1st rate hike, March, one of EIGHT

$AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:41:10 </td>
   <td style="text-align:left;"> $QQQ graph spiking doesn’t mean increase in growth exponentially from previous years. Every three years same growth. In the future we’ll be in the thousands and you’ll wish you bought. American economy is expanding. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:39:59 </td>
   <td style="text-align:left;"> $BX What are you up to America?

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:39:18 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

That’s some cute futes, it’d be a shame if I use this shinny infinity gauntlet to snap them away... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:37:30 </td>
   <td style="text-align:left;"> $QQQ the amazon eps is basically fake...this is feeling so bad look at all my past posts im almolst never bearish this market smells fiiiishhhyyyy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:36:13 </td>
   <td style="text-align:left;"> $AMZN $FB $GOOGL $SPY $QQQ Imagine a trader who got long Facebook off Google&amp;#39;s strong print, then got short Amazon off FB&amp;#39;s weak print. #whiplash #careerrisk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:34:56 </td>
   <td style="text-align:left;"> $WIMI  🔥WlIMI ranks first in the Holographic AR industry in China in terms of revenue, number of customers, holographic AR content, holographic AR patents and software Copyrights. WIMI owned about 4,654 AR holographic contents, 325 software   and 195 technology patents. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:34:24 </td>
   <td style="text-align:left;"> $QQQ im not nervous im selling all ur </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:34:14 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN $FB $SNAP the stock market has officially turn into shitcoin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:32:00 </td>
   <td style="text-align:left;"> $QQQ haven’t seen 🐻 this nervous in a while </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:31:12 </td>
   <td style="text-align:left;"> $SPY $QQQ $ES_F  Honestly not much pop, don&amp;#39;t perceive any real more than a pump/dump even if job&amp;#39;s report bullish tomorrow, it is just tooooo important for inflationary leading indicator per FED mandate👌
Then, CPi Tuesday 🥶
Jobs? 200, 000 hired because everyone already working + 3.8% unemployment rate. More and more want to work over GAMING, MOVIES, SOCIAL MEDIA, &amp;amp; YES, Amazon shopping got bored for girls cuz just forced on damn laptop internet virtual shopping so much during Covid-19 March-May 2020,  so then Delta and Omicron . Just 🤮 to all things tech by Jan. 2021 of this year. 

So am I surprised by $MSFT pc sales $20B, game pass high #s, Google? 

No, no, and no. 

Covid killing tech started Delta wave October and then forced inside Dec. for Omicron is what killed consumers liking tech AS A MAJORITY. 

Highly doubt though, employment so high ADP private jobs report had -300,000 and jobless claims going down cuz people finding work, adjusted it was 35000, not the 8000 #. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:31:03 </td>
   <td style="text-align:left;"> According to $GS we are didn&amp;#39;t gain any jobs last Month $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:30:35 </td>
   <td style="text-align:left;"> $AMZN $12bn profit from Rivian to pump earning, are you fking kidding? the most manipulated mega cap pump I’ve ever seen, despite woeful numbers and guidance. After $FB &amp;amp; $NFLX, Amazon is headed towards declining growth.  
$QQQ  $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:29:52 </td>
   <td style="text-align:left;"> REMINDOOR: It&amp;#39;s Still Over - Dr. Fly https://ibankcoin.com/flyblog/2022/02/03/remindoor-its-still-over/ $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:29:35 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AMZN 

FRAUD ON EVERY LEVEL... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:28:28 </td>
   <td style="text-align:left;"> $SPY $QQQ 13 years....damn near 13 years at near zero rates. 13 fucking years. If you think there won’t be repercussions for this you are naive. Good grief </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:27:48 </td>
   <td style="text-align:left;"> $SPY $QQQ so all these companies are just passing on all the inflation to us...this is going to end well 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:26:20 </td>
   <td style="text-align:left;"> $QQQ this might close under 350 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:25:34 </td>
   <td style="text-align:left;"> $AMZN The market owes Bezos a giant Beer. Dodged the biggest bullet this week 😂 $SPY $QQQ $DIA . Next week though not so sure. 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:24:54 </td>
   <td style="text-align:left;"> $QQQ they are expecting a negative job growth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:21:39 </td>
   <td style="text-align:left;"> $QQQ Game over, decline can resume </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:20:58 </td>
   <td style="text-align:left;"> $FB $AMZN $SPY $QQQ $DJIA It is absolutely incredible how much FAANG moves the market. lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:20:51 </td>
   <td style="text-align:left;"> $SPY $QQQ Headless chicken market 🐓 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:19:09 </td>
   <td style="text-align:left;"> $QQQ bears are trippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:19:01 </td>
   <td style="text-align:left;"> $QQQ The bloodbath that typically comes with the jobs report that’ll be as horrendous as this one will be canceled out by the DOD ramping up with the mere mention of war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:17:52 </td>
   <td style="text-align:left;"> $AMZN $SPY $QQQ $AAPL ya now what? all the big guy earnings are in? whats gonna drive the market now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:13:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN All big earnings are in… let’s proceed with the 🐻🔪🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:13:57 </td>
   <td style="text-align:left;"> $qqq bears n bulls in this 🐑 tape!  🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:13:45 </td>
   <td style="text-align:left;"> $QQQ Who&amp;#39;s adding puts tomorrow morning? Looks like Amazon included Rivians valuation I to the EPS amd jobless numbers out tomorrow.  Recipe for a bloody friday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:13:24 </td>
   <td style="text-align:left;"> $QQq  east goes green east goes green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:12:47 </td>
   <td style="text-align:left;"> $QQQ Fading throughout the night. Red by morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:11:33 </td>
   <td style="text-align:left;"> $QQQ True test Asia ...if they dig it if not .... They go green then we hold for Friday untill or if the data goes hellish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:11:06 </td>
   <td style="text-align:left;"> $SPY Anyone &amp;quot;care&amp;quot; to unpack this right by the AM? 

$QQQ $SOXX $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:10:52 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN Stoked for tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:07:52 </td>
   <td style="text-align:left;"> $QQQ Is it going to be like last Friday where Futes start green then market goes red then goes green again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:07:39 </td>
   <td style="text-align:left;"> $AMZN $QQQ $SPY still no split? For real? MM still out to get options players, that’s what that means. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:07:33 </td>
   <td style="text-align:left;"> U.S. stock futures rally after earnings reports from Amazon and Snapchat

$SPY $QQQ $AMZN $SNAP $DJIA

https://www.cnbc.com/2022/02/03/stock-market-futures-open-to-close-news.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:05:43 </td>
   <td style="text-align:left;"> $QQQ 😳😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:02:54 </td>
   <td style="text-align:left;"> $QQQ  the QQQ should close tomorrow above $360…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:02:50 </td>
   <td style="text-align:left;"> $QQQ stock analysis based on today&amp;#39;s closing price 

https://youtu.be/WZVufNs-LFo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:02:27 </td>
   <td style="text-align:left;"> $QQQ y&amp;#39;all even small caps be up ..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:01:58 </td>
   <td style="text-align:left;"> $BFRI Not the best angle. But to update the state of the Nasdaq and the bear trap I was talking about yesterday. They used facebooks massacre to help fuel tech selling across the board, enough to drop this 3-4%. Then used Amazon in order to hold the backtested support. They will use Facebook being oversold also as a way to fuel the Nasdaq going forward. Gigantic bear trap. A lot bigger of a bear trap than I had even thought. They spiked this much lower than I anticipated just to use Amazon to keep support held. What&amp;#39;s good for us at BFRI is that we didnt have to deal with too much of the blow today from the Nasdaq. But I suspect tomorrow and next week we will reap the rewards with the way our chart looks. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:01:44 </td>
   <td style="text-align:left;"> $QQQ out of our hands rio them futes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:01:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN  payroll numbers tomorrow 
does it even matter cuz amazon right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:01:35 </td>
   <td style="text-align:left;"> $QQQ MOONING TM, 3% up eod!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:01:08 </td>
   <td style="text-align:left;"> $QQQ focus on tomorrow.  a few things.  anyone that sold today that own mutual funds is literally devastated.  they are market on close buyers tomorrow if the rally holds.  for many folks friday is pay day and 401k market on close buyers early in the year is a massive tailwind. 
 
that said, the rally from the bottom will naturally bring out some short term folks that bought the dip and profit. 
 
net net it feels pretty strong for tomorrow all things considered so i probably wouldn&amp;#39;t sell anything until 4pm or maybe 8pm. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:00:54 </td>
   <td style="text-align:left;"> $QQQ Volatility is King!! Simulated Weekly $360.0 CALLS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:00:47 </td>
   <td style="text-align:left;"> $QQQ Closed my put this afternoon, so I have no stake in tomorrows direction. That being said, we&amp;#39;re right at the downtrend line right now. Without continued gas tomorrow, I see this as a very real possibility. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:00:38 </td>
   <td style="text-align:left;"> $SPY fun fact, $QQQ dropped 3% by FB, PYPL earnings and is up 1% by AMZN earning. 
This is a very clear signal about the direction. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:00:15 </td>
   <td style="text-align:left;"> $QQQ $SPY so is this nearly filled gap effectively closed, or is there unfinished business?  The only thing that can fill that gap now is Russia 🇷🇺 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 09:00:05 </td>
   <td style="text-align:left;"> $FB Look at the value destruction today! Oh my goodness, it&amp;#39;s one for the record books... smh 
 
Every analyst including the Fast Money pumpers in CNBC were always propping up $FB every chance they get and today, it&amp;#39;s a different story altogether.  lol 
 
Same story with $PYPL.  RIP to the call buyers as the carnage is unreal!  Moral of the story is to stick with stocks as they will recover eventually, at least most of them do, imho. 
 
$QQQ $SPY $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:59:13 </td>
   <td style="text-align:left;"> $QQQ PUMP CITY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:58:02 </td>
   <td style="text-align:left;"> $QQQ I am in some $360 Calls expiration 2/7/ looking to open with a gap upward at open tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:57:30 </td>
   <td style="text-align:left;"> $QQQ if jobs report is bad tomorrow , which is expected to be based on omicron.. this might get pushed back down a bit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:57:12 </td>
   <td style="text-align:left;"> $QQQ i have made a lot of mistakes in my trading/investing career but i am not sure i could recover from selling SNAP at 25 only to see it at 39 an hour later (i pray for those who did, no joke) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:56:30 </td>
   <td style="text-align:left;"> $QQQ amzn is bull narrative is equal but more playable than bear backtrack ukrain war narrative. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:55:50 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY easy to understand analysis  
 
https://youtu.be/lxbroXc5itI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:55:30 </td>
   <td style="text-align:left;"> $FB $QQQ Mark Zuckerberg consistently sold his Facebook shares ahead of the last 3 times the stock crashed. Last one out has to turn the lights off. 🐳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:54:52 </td>
   <td style="text-align:left;"> $DIA $SPY $IWM $QQQ $XBI https://www.fidelity.com/learning-center/trading-investing/out-of-the-woods </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:54:50 </td>
   <td style="text-align:left;"> $SPY imagine everyone buying AMZN SNAP etc at these elevated levels and come morning to find the market had limit-down due to active war.  $UVXY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:48:51 </td>
   <td style="text-align:left;"> $AMZN This has slow bleed written all over it. I stayed away from ER. But played $QQQ and $SPY calls. Profits will be secured first thing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:48:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 72651000. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:47:29 </td>
   <td style="text-align:left;"> $AMC $SPY $QQQ Futures are green. Hoping for a bounce tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:47:12 </td>
   <td style="text-align:left;"> $QQQ what rich-white-grand-daddy manipulation is going on here?!?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:46:14 </td>
   <td style="text-align:left;"> $QQQ $TQQQ $SQQQ Green support, Red resistance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:45:15 </td>
   <td style="text-align:left;"> $QQQ bearlish is dead. Bull newborn today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:43:13 </td>
   <td style="text-align:left;"> Stocks Tank Of February 3, Ahead Of What Is Likely To Be A Wild Friday $QQQ $AMZN $TIP $SPX https://talkmarkets.com/content/stocks--equities/stocks-tank-of-february-3-ahead-of-what-is-likely-to-be-a-wild-friday?post=343544 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:41:49 </td>
   <td style="text-align:left;"> $SPY target hit 445’s on short side. Surge after $AMZN earnings.  Now need above 4530 for short squeeze to 456 which opens the door to 466 $QQQ $IWM $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:40:59 </td>
   <td style="text-align:left;"> $BTC.X $spy $qqq now that earnings is out of the way and we have guidance, FUD should dissipate. We should start seeing money flowing back into the market and back into more speculative (perceived risk) investments.

small cap market has been in a bear market for almost 6 months, Bitcoin for 3 months and it’s time for a reversal. 

Far to many stocks are down 50%, 60%, 70%. A year ago market was overbought. Today we are oversold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:40:57 </td>
   <td style="text-align:left;"> $AMZN And I thought FB a bit of an overreaction,  to the downside, but Amazon makes that move pedestrian, as $11B of REVENUE is non-operating income from Rivian 15% stake.

Unbelievable.
Nothing to report, guided lower Q1, and, CEO jassey even expressed uncertainty of what lies ahead.

Hint to Jassey: Raising Prime Membership $20 will turn folks OFF of their Covid shopping habits.

I have already called Netflix out one of 1st, and, FB was expected, so that is MOVIES and SOCIAL MEDIA to fade to black, we know.

But, tech--killed by Covid overplay and overuse? GAMING and, wait for it...

w-a-a-it for it: SHOPPING ONLINE! 

Just expect people to do a whole lot LESS TIME TO DO WITH TECH which was forced on us, thru lockdowns, March-May 2020. Then Delta virus variant, Oct. &amp;#39;21 . Then, just when got our asses outside AND FREE OF TECH, Biden sent us back couple weeks more with the &amp;quot;Stay home if not vaccinated&amp;quot; spiel, which , in my opinion, cuz tech ERs suffer if not Om &amp;amp; Del.
$QQQ $SOXX $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:38:57 </td>
   <td style="text-align:left;"> $SPY $QQQ bears are so screwed tomorrow morning.  EVERYONE will be looking to unload their “hedges” in the morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:32:04 </td>
   <td style="text-align:left;"> $NQ_F #NQ_F as expected trapped Bears 🐻 under 14500 😝 was expecting to hold 14440+ need to see what NFP will do before open. Let’s get to 15500 all my lotto $QQQ calls will be golden 🥸 then in March-April  we hit 12K 😝 $AMZN was used to punish ultra shorts 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:31:58 </td>
   <td style="text-align:left;"> $SPY $QQQ Cash sessions no longer matter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:31:29 </td>
   <td style="text-align:left;"> $SPY $QQQ What a massive beat for $AMZN on the EPS, the EPS came in at $27.25 vs $3.58 estimated, it is just a massive beat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:31:06 </td>
   <td style="text-align:left;"> $spy $qqq Market was desperate to bounce AH after horrible drop with $fb .. therefore $amzn earning was just a excuse .. As a result I expect the fade this AH pump following days ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:30:30 </td>
   <td style="text-align:left;"> $AMZN @illiquid @dman6  &amp;quot;It&amp;#39;s inexcusable for AMZN to raise the price of Prime Membership to make up some lost revenue.&amp;quot; 
 
Not sure where to start but let me say that it is a profound statement.  lol 
 
Companies cannot raise prices because of content creation + inflation, etc.?  That&amp;#39;s not how capitalism works bud!   
 
In any case, $AMZN earnings is NOT great... In fact, they missed the revenues as well as Q1 guidance. Yet, the stock jumped because of AWS + Prime fee increase. Markets always look ahead and they see that it&amp;#39;s a positive effect. As simple as that!   
 
$QQQ shouldn&amp;#39;t have dumped 3+% today because of $FB but it did. Now, $AMZN will help it to go higher as the alogs are in control and it&amp;#39;s decimating lots of option buyers and the lemmings are happy to give it back to MM ($SPY).  lol 
 
OTOH, $ARKK will start it&amp;#39;s run now as the Unity and the other high fliers are starting to deliver good results, imo. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:29:59 </td>
   <td style="text-align:left;"> $QQQ going up from here.  fb had bad earnings.  but the rest of fang blew the doors off.   qqq is weight Ed to the fang. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:29:53 </td>
   <td style="text-align:left;"> $BTC.X surged after $AMZN beat lol. Turning into a proxy for the $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:29:32 </td>
   <td style="text-align:left;"> $SPY $SNAP $AMZN $QQQ 

HEY BEARS WHAT HAPPENED TO THE CRASH ??!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:28:26 </td>
   <td style="text-align:left;"> For jobs tomorrow: good report = bad for stocks. Bad report = good for stocks. All about fed.. 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:27:44 </td>
   <td style="text-align:left;"> $QQQ won’t hold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:27:23 </td>
   <td style="text-align:left;"> $QQQ Don’t know how you can post and laugh at bears or bulls right now.....let’s face it.....nobody knows wtf is going on right now $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:27:06 </td>
   <td style="text-align:left;"> $SPY  $QQQ  like tech set themselves a pretty high bar for next quarter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:23:19 </td>
   <td style="text-align:left;"> $QQQ bear trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:22:54 </td>
   <td style="text-align:left;"> $QQQ down 14 up 6.  all meaningless.  what i want to know is whether this goes to 250 or 500 in 2022 cuz either is plausible. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:20:41 </td>
   <td style="text-align:left;"> Watchlist 📝👀

$TSLA $AAPL $BA $UPS $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:19:10 </td>
   <td style="text-align:left;"> $QQQ Sell while you can. You have been warned!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:18:17 </td>
   <td style="text-align:left;"> $SPY $QQQ Are any gamblers shorting $FB here? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:16:22 </td>
   <td style="text-align:left;"> $QQQ lotto calls gonna print? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:14:36 </td>
   <td style="text-align:left;"> $QQQ Sold all puts before close and loaded the boat with calls. Back to full bull lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:12:50 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM dont forget about GOLD and SILVER 
https://youtu.be/zQ3L_WswrbE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:12:29 </td>
   <td style="text-align:left;"> $QQQ Earnings soon out of sight, what narrative will the bulls cling onto now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:09:44 </td>
   <td style="text-align:left;"> $QQQ bidding up these stocks based of the $AMZN action after market is a bigly mistake.. You fade this move.  More work below $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:09:22 </td>
   <td style="text-align:left;"> $qqq $spy good thing or not that it&amp;#39;s raising the price- doesn&amp;#39;t that mean inflation is high and it&amp;#39;s willing to sacrifice some potential growth in memberships to pay for costs. it&amp;#39;s an interesting discussion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:07:17 </td>
   <td style="text-align:left;"> $SHOP  $amzn has AWS.. what does shopify have ?? Amazons would have reported loss if not for AWS. Does shopify have a high margin BU like that ??  Hanging on Amazon coat tails won&amp;#39;t last this cycle. $qqq $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:05:20 </td>
   <td style="text-align:left;"> $AMZN what a ripper after hours! 
Free trade idea for tomorrow - Short the rip! 
Stop: 3300 
If $AMZN gets below $2960, that means risk off for $QQQ again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:05:10 </td>
   <td style="text-align:left;"> $SPY $QQQ lol volaTITity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:05:00 </td>
   <td style="text-align:left;"> $QQQ pay no attention to the amateurs in AH/PM, the big boys are now short, so down we go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:04:15 </td>
   <td style="text-align:left;"> $QQQ $AMZN Too many people equated $FB&amp;#39;s earnings with Amazon&amp;#39;s, and the two have nothing to do with each other! You have to evaluate each FAANG stock separately </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:04:14 </td>
   <td style="text-align:left;"> $SPY $QQQ trend is down, enjoy the violent rallies but shorts here to make money for some time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:03:25 </td>
   <td style="text-align:left;"> $QQQ open at 361 tomorrow , run to 370 by noon peas and carrots </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:02:34 </td>
   <td style="text-align:left;"> $SPY $QQQ Bear market rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:02:25 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-02-03 Trade Analysis Video: 
https://www.youtube.com/watch?v=CUntnYRpk38 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 08:00:38 </td>
   <td style="text-align:left;"> $AMZN Jeez, if this sells off tomorrow then bulls are screwed. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:59:31 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:59:07 </td>
   <td style="text-align:left;"> $QQQ take out your blie chips before HF throws you under the bus... learn from 2008 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:58:48 </td>
   <td style="text-align:left;"> $AMZN 2 of 2: look at margins shrinking as well. The lowest In 3 years. We could see a fade tomorrow. But price is king so always follow the price action. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:58:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA It looks like a bullish candle for tomorrow traders, I hope everybody bought calls or shares today! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:56:46 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN $SNAP $QQQ  
 
GOD BLESS AMERICA! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:56:34 </td>
   <td style="text-align:left;"> $AMZN 1 of 2:  The sentiment was so bearish going into report it was able to generate a big pop due to &amp;quot;not as bad&amp;quot; earnings. However the report was poor considering the multiple you pay on this stock. Revenue growth slowing dramatically $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:55:11 </td>
   <td style="text-align:left;"> $QQQ y’all better pull my XBI got a couple otm calls I need to ditch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:54:52 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:53:23 </td>
   <td style="text-align:left;"> $QQQ 
Got QQQ Balled ! its Almost like a Tea Bag to the Chin . WACK ASS STOCK MARKET </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:52:54 </td>
   <td style="text-align:left;"> MarketWatch - Facebook $FB wasn’t Thursday’s only big loser — these 16 other Nasdaq-100 stocks dropped at least 5% $QQQ
 https://t.co/Su5sD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:52:35 </td>
   <td style="text-align:left;"> $QQQ another opportunity to take profits tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:52:19 </td>
   <td style="text-align:left;"> $SPY Amazon earnings?  done.  Next?  war.  $uvxy $qqq $sqqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:52:13 </td>
   <td style="text-align:left;"> $spy $qqq Job reports in morning !!!  
$amzn $snap market pump might fade easily .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:50:51 </td>
   <td style="text-align:left;"> $AABB $SPY $SPX $QQQ $AABB is going to $NASDAQ and the RSI is in oversold territory ROI https://www.globenewswire.com/news-release/2022/02/02/2377870/0/en/Asia-Broadband-Corporate-Update.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:50:43 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $AMZN $TSLA  
 
A few things Gen X would like Millennials to remember as they continue to buy stocks and take the baton from retiring boomers. 
 
1) Stock valuations don&amp;#39;t matter....buy stocks! 
2) Fiscal debt doesn&amp;#39;t matter....buy stocks! 
3) Fed balance sheet doesn&amp;#39;t matter...buy stocks! 
4) ATH housing prices don&amp;#39;t matter....buy stocks! 
5) Student loans are good...buy stocks! 
 
Summary....&amp;quot;buy stocks!&amp;quot; 
 
You got this! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:49:44 </td>
   <td style="text-align:left;"> MOVES HAPPENING NOW (6:49pm)

⦿ $QQQ is down 0.1% in the last 5 mins. 

⦿ There are 18 stocks that are up more than 3% in the last 5 mins. 

⦿ The top gainer is up 22.2% in the last 5 mins. 

 See the stocks that are moving the most right now via link in bio (wallstreetodds .com). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:48:31 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:48:26 </td>
   <td style="text-align:left;"> Compare your portfolio to Buffet/Munger $BABA pick since 1/5/22.  This is why they&amp;#39;re multi-billionaires and we&amp;#39;re not. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:48:11 </td>
   <td style="text-align:left;"> $SPY $QQQ whats more important amazon earnings or the job data that will be coming out lmao! i didnt know amazon was the economy and the stock market! lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:47:09 </td>
   <td style="text-align:left;"> $SPY $QQQ so price doesn’t matter? We just instantly set a mark and trade around it…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:46:36 </td>
   <td style="text-align:left;"> $QQQ super rise coming !!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:45:06 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
https://www.cnbc.com/2022/02/03/stock-market-futures-open-to-close-news.html 
 
A big party for the bulls tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:42:51 </td>
   <td style="text-align:left;"> $AMZN is an excuse for MM and Big money to pump the market. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:41:55 </td>
   <td style="text-align:left;"> $QQQ Market logic: FB tanks 22% during after hours and world market is red. AMZN is up 14% and market is barely green. I don&amp;#39;t get it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:41:48 </td>
   <td style="text-align:left;"> $QQQ after amzn rugged you dopey retail shorts now you want war in Ukraine. Keep losing money. 
 
citadel and me are long tech. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:41:37 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM  can’t get shit done😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:40:54 </td>
   <td style="text-align:left;"> $QQQ deflect deflect deflect run it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:40:22 </td>
   <td style="text-align:left;"> $QQQ $spy jobs report in the AM Gonna kill this?🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:40:15 </td>
   <td style="text-align:left;"> $QQQ no reason this won&amp;#39;t go back to 365 tomorrow.   Facebook was the only real loser of the fang stocks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:39:24 </td>
   <td style="text-align:left;"> $QQQ Trump chant. &amp;quot;fuc your wall&amp;quot; run it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:37:51 </td>
   <td style="text-align:left;"> $QQQ weekly not a good look </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:37:42 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $AMZN 
 
Listen up JDADDY!...she has message for you and all your endless meddling in the financial markets. 
 
The younger generations don&amp;#39;t like you printing away their futures. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:36:19 </td>
   <td style="text-align:left;"> Futes.  $SPY $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:36:07 </td>
   <td style="text-align:left;"> NASDAQ100 $QQQ Earnings Calendar for the next week $AMGN $FISV $ORLY $SGEN  
 
Learn more: https://www.finscreener.org/earnings/earnings-calendar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:35:55 </td>
   <td style="text-align:left;"> $SPY $QQQ  good thing I was away from my desk most of the day 😂 yikes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:34:55 </td>
   <td style="text-align:left;"> $QQQ $SPY When mega caps trade like penny stocks that’s an indication this market has lost its direction and people simply swing trade. Not worthy of long term buys atm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:34:43 </td>
   <td style="text-align:left;"> $QQQ bears went from $fb to UKRAINE very quickly huh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:34:39 </td>
   <td style="text-align:left;"> $QQQ that under me is a bear meat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:34:34 </td>
   <td style="text-align:left;"> $SPY $TWTR $FB $DIA $QQQ 
 
Joe Biden&amp;#39;s response when asked about China </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:34:14 </td>
   <td style="text-align:left;"> $QQQ Learn https://fair.org/home/what-you-should-really-know-about-ukraine/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:33:59 </td>
   <td style="text-align:left;"> NASDAQ100 $QQQ Oversold stocks $PYPL $EXC $GILD  
 
Learn more: https://www.finscreener.org/screener/oversold-stocks/nq100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:33:52 </td>
   <td style="text-align:left;"> $QQQ let her rip fuck it stop the doom and gloom I know but let it reverse just as strong as Facebook inverse.  Then tell me about jobs and Russia this and that.  Give it a day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:33:49 </td>
   <td style="text-align:left;"> $SPY Nightly News has stories on $fb drop so,... thats the signal its getting to the end of the dip, few more days maybe but,.. 
 
$qqq $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:31:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN $SNAP $PINS  
 
How many accounts got blown up today? Never bet against America. 4%+ across the board tomorrow baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:31:34 </td>
   <td style="text-align:left;"> $AMZN $RIVN $SPY $QQQ  
 
&amp;quot;Amazon posted profits of $14.3 billion thanks to strong gain of $11.8 billion in the value of its stake in Rivian Automotive.&amp;quot; 
 
So 82.5% of Amazon&amp;#39;s profits were due to a stake in an unproven EV company. 
 
lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:30:19 </td>
   <td style="text-align:left;"> $QQQ today the pump
Tomorrow the dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:28:24 </td>
   <td style="text-align:left;"> $AMZN $SPY $QQQ are we seriously still feeling the downtrend resistance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:28:09 </td>
   <td style="text-align:left;"> $QQQ genuinely confused. Amazon missed pretty badly, guidance was poor,  and the stock rips 15%…makes no sense. poor jobs report tomorrow, an even worse CPI coming next week, interest rates up in March, everything seems to indicate rough times ahead so I will stay short. The correction is coming, just hope you time it right! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:26:00 </td>
   <td style="text-align:left;"> GAP N CRAP or RALLY HOLDS just a massive day tomorrow $spy $qqq $amzn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:25:43 </td>
   <td style="text-align:left;"> $shop getting that $amzn pin action - too bad I chose the wrong direction 
 
It is still possible that we GAP N CRAP tomorrow on jobs report and proft taking............... 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:24:56 </td>
   <td style="text-align:left;"> $QQQ whatever the futes end at buy the opposite color at the end of the day😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:24:51 </td>
   <td style="text-align:left;"> $IWM $QQQ $SPY  
Thanks Allie 🔥🔥🔥🧸 
https://www.missallieskitchen.com/bear-roast/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:24:36 </td>
   <td style="text-align:left;"> It is now practically LAW that every dip is a buying opportunity WOW what a day $spy $qqq $amzn $fb $ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:23:50 </td>
   <td style="text-align:left;"> STONKS 
 
ONLY  
 
GO  
 
UP 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:23:33 </td>
   <td style="text-align:left;"> $QQQ f...my puts... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:20:04 </td>
   <td style="text-align:left;"> $QQQ Volatility is King!! Simulated Weekly $360.0 CALLS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:17:35 </td>
   <td style="text-align:left;"> $ATER $SPY $TSLA $QQQ $AMZN see why $ATER is a sympathy play on AMZN earnings. 💥💥💥💥💣💣💣💣💣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:17:35 </td>
   <td style="text-align:left;"> $AMZN I dont know when Ive heard so many Bears have so many reasons why $amzn is up,  
Sounds like too many bought Puts &amp;amp; realize they maybe on trouble 
 
$qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:17:03 </td>
   <td style="text-align:left;"> $QQQ $SPY $UVXY  
What happened to @oldfknguy ?  
Silver Alert or Wellness Check ? 
Hope he stayed away from booster #4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:13:58 </td>
   <td style="text-align:left;"> $FB They will buyback plenty at these prices..
17 pe. One day they will split Facebook off from metaverse.  I&amp;#39;m sure there is a positive note coming out from mgmt next week. Would not be surprised to see this over 250 tomorrow.  $NFLX was left for dead a week ago. Up 100 since.  This one of the 5 nasdaq horsemen.  One of the top 20 companies in the markets right now. I wouldn&amp;#39;t bet against it. $DIA $AMZN $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:13:16 </td>
   <td style="text-align:left;"> $QQQ greetings nerds and virgins :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:12:11 </td>
   <td style="text-align:left;"> $QQQ im curious does anyone buy weekly or daily &amp;amp; for how long what’s your gain ytd. Ty </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:11:32 </td>
   <td style="text-align:left;"> $QQQ I hope it will Spike at the open I missed today&amp;#39;s dump tomorrow morning I want a good entry point to sqqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:09:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM
CNBC needs to add subtitles for Cramer.  That guy’s harder to understand than Bane. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:08:07 </td>
   <td style="text-align:left;"> $QQQ puts are fried </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:07:53 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 2/3/2022 $SPY $XLF $QQQ $FB $AMZN https://www.chartguys.com/daily-market-videos/4125/how-the-market-is-dominated-by-individual-tickers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:06:18 </td>
   <td style="text-align:left;"> $QQQ sexy futures almost as good as getting head. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:05:13 </td>
   <td style="text-align:left;"> $QQQ  
 
Let&amp;#39;s wait until morning futures...I see us going green but turning red later on a selloff  Friday. 
 
I will be shocked if its not green in the morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:05:10 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
https://www.youtube.com/watch?v=NrQ0tGxYbyQ 
 
Jim Cramer still like $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:05:08 </td>
   <td style="text-align:left;"> $QQQ people act like amazon isn&amp;#39;t retardedly overvalueded...😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:04:55 </td>
   <td style="text-align:left;"> $AMZN $QQQ $SPY 

Nothing better then seeing the arrogant bears who just hammer the hate all day drown in their own tears , take the L have some self respect and move on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:04:37 </td>
   <td style="text-align:left;"> $qqq 👀 around da 🐑 of fintwat.  They are all hopeful now!!  First they scare YO out. Then they wear YO out!  🍿.     Bahhhish tag </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:03:07 </td>
   <td style="text-align:left;"> $QQQ Tomorrow is no different …..Stay the course. Sell the rip 

PUTS!😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:02:40 </td>
   <td style="text-align:left;"> $SPY $AMZN $SNAP $QQQ

Hey guys how’s futes? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:00:46 </td>
   <td style="text-align:left;"> $QQQ Amazon earning report is misleading, unbelievable for a trillion dollar company。 not as honest and upfront as Facebook,   intentional or unintentional…….  ？ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:00:34 </td>
   <td style="text-align:left;"> $QQQ I want $365 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:00:21 </td>
   <td style="text-align:left;"> $AMZN $FB $QQQ $SNAP Amazon might have saved the market. Lets see how long it lasts.  
 
https://marketcrier.com/markets/blog/market-digest/117e07ae-756d-409d-aca1-fb27cba9545d </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 07:00:03 </td>
   <td style="text-align:left;"> $AMZN  # 1 online retailer... cloud services... package delivery company... logistics... air freight... streaming service... movie studio... etc...  
 
Amazon is a must-have stock for any portfolio and they had fantastic quarterly earnings, new 52-week high incoming here 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:59:45 </td>
   <td style="text-align:left;"> $SPY $QQQ After $AMZN blowing past the earnings estimates, I would be pretty surprised if we don&amp;#39;t ease the losses that we had today by tomorrow or next Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:59:33 </td>
   <td style="text-align:left;"> $QQQ face outs everywhere </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:56:49 </td>
   <td style="text-align:left;"> $QQQ this will be bloody as fuck tomorrow … amazon will fade and people will sell for profits … there’s a lot more shit than a bullshit earnings to prop this … for tomorrow .. another 8 point drop tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:56:16 </td>
   <td style="text-align:left;"> $qqq that was in reuters news, feels like these bounces are faded. agree with one of the earlier points. $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:55:03 </td>
   <td style="text-align:left;"> I doubt fishy $AMZN EPS beat will be enough to save the Markets, they didn&amp;#39;t have a good quarter if you take that Investment out $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:54:58 </td>
   <td style="text-align:left;"> $QQQ $AMZN  Looking good !!!  
 
🤡🤡🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:52:06 </td>
   <td style="text-align:left;"> $QQQ I hear $FB is trending on WallStreetBets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:51:36 </td>
   <td style="text-align:left;"> $QQQ Private payrolls tumbled by 301,000 in January, posting their biggest drop-off since the onset of the pandemic, as the omicron variant set off a spike in coronavirus cases, according to data released Wednesday. 
 
The unexpected findings by ADP — which had forecast a gain of 200,000 jobs for the month — represent the first time the payrolls processing firm has reported negative employment growth since December 2020 and the biggest decline in employment since spring 2020 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:50:34 </td>
   <td style="text-align:left;"> $QQQ sexual evening. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:50:04 </td>
   <td style="text-align:left;"> $QQQ amzn… wow. 
 
up tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:48:39 </td>
   <td style="text-align:left;"> U.S. job market faces reshuffling as workers quit at near record rates

https://www.reuters.com/business/us-job-market-faces-reshuffling-workers-quit-near-record-rates-2022-02-03/

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:47:04 </td>
   <td style="text-align:left;"> $QQQ bull market is back!!!!~~~ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:47:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 72651000. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:46:56 </td>
   <td style="text-align:left;"> $QQQ $AMZN Amazon increasing their Prime membership 17% is gonna be a huge boost to the bottom line💸💸💸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:46:31 </td>
   <td style="text-align:left;"> $QQQ Amazon ‘s main profit in this earning report was not from its core business….. will hit back very soon…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:45:30 </td>
   <td style="text-align:left;"> $AMZN Tomorrow will be epic recovery for bulls. Non farm payroll data will be overshadowed, assuming it is bad. Got early warning, so information was baked in on today&amp;#39;s pullback. CPI data next week is the big hurdle, if inflation percentage is below estimate - as Tom Lee said - cancel your valentines day this Feb, we will be spending our money on &amp;quot;violent&amp;quot; V rally. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:45:09 </td>
   <td style="text-align:left;"> As Inflation Soars, Central Banks Scramble to Lift Rates

https://www.google.com/amp/s/www.wsj.com/amp/articles/bank-of-england-raises-interest-rates-for-second-straight-meeting-11643890280

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:44:09 </td>
   <td style="text-align:left;"> $QQQ huge price increase lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:43:00 </td>
   <td style="text-align:left;"> $QQQ shit bears back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:42:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $FNGU Technically we could see 10 to 12% downside on SPY? See the Chart below! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:42:37 </td>
   <td style="text-align:left;"> $AMZN $SPY $QQQ Earnings Helium Scam PUMP🔴🔴🔴 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:42:12 </td>
   <td style="text-align:left;"> $amzn  $spy $qqq https://www.youtube.com/watch?v=kGwRDQ4lus4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:42:11 </td>
   <td style="text-align:left;"> $QQQ $SPY 👀

https://news.sky.com/story/ukraine-russia-tensions-moscows-alleged-plan-for-fake-attack-to-justify-invasion-is-shocking-evidence-of-its-aggression-warns-truss-12532225 Ukraine-Russia tensions: Moscow&amp;#39;s alleged plan for fake attack to justify invasion is &amp;#39;shocking evidence of its aggression&amp;#39;, warns Foreign Secretary Liz Truss </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:41:54 </td>
   <td style="text-align:left;"> $amd $qqq $pypl $ndx https://www.youtube.com/watch?v=g5n1r19_VpM&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:41:09 </td>
   <td style="text-align:left;"> $spy $qqq $tqqq $upro https://www.youtube.com/watch?v=JZ63GccJBAY&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:40:18 </td>
   <td style="text-align:left;"> $VXX is forming a head and shoulders pattern. More upside on the way. $NDX $SPX  $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:39:23 </td>
   <td style="text-align:left;"> Get to know me...I talk about how I got started, the markets in the 90&amp;#39;s (original YOLO market) 
 
the markets today public and private and being an emtrepreneur 
 
https://www.youtube.com/watch?v=vqb3FlxEJvs&amp;amp;t=2s&amp;amp;ab_channel=TraderLion 
 
$qqq $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:39:08 </td>
   <td style="text-align:left;"> $QQQ reminds me of Nov 2018 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:37:25 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA Looks like we are about to see huge BEAR MARKET </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:37:10 </td>
   <td style="text-align:left;"> $QQQ so we gunna run tomorrow or just drop barcode </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:37:03 </td>
   <td style="text-align:left;"> $QQQ $AMZN You&amp;#39;ve gotta luv institutional buying, amazing👏😘 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:35:25 </td>
   <td style="text-align:left;"> $SPY $QQQ plenty of rally needed to invalidate the count. the bulls only need to break into the red box </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:35:14 </td>
   <td style="text-align:left;"> $QQQ 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:35:02 </td>
   <td style="text-align:left;"> $AMZN $SNAP Well done bulls, tomorrow we rip even higher! Huzzah! $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:34:27 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA 

Stocks are crashing and jumping 20%+ in one day and people still say crypto is volatile </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:34:25 </td>
   <td style="text-align:left;"> $SPY $QQQ $SNAP $AMZN $PINS 
 
Bears: short stocks into the dirt, then scramble to cover creating massive price swings/volatility 
 
Also Bears: WTF tHiS mArKeT iS bRoKeN 
 
Saw this play out last year with gamestop. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:34:24 </td>
   <td style="text-align:left;"> $QQQ -Just like GOOG had a great earnings call and sold off, AMZN will too 

Tough inflation numbers next week CPI and inflation, all of which should be red hot and give J Powell more fuel for a 50 bps rate hike </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:30:19 </td>
   <td style="text-align:left;"> $SPY $QQQ  $DIA  The $VIX tho 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:30:12 </td>
   <td style="text-align:left;"> $QQQ likely to fade all night. Too much uncertainty with war to be bullish here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:29:59 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:29:00 </td>
   <td style="text-align:left;"> $SPY $AMZN &amp;quot;only Bezos could pull this kind of report off.&amp;quot; A bull

 @ashbourne442 nah, average, ER, Rivian was 2/3 EPS, $17B, unrealized gain. That makes REV 10.75B 👍

Sneaky, massaged accounting, that is what it was, by Bezos.

THAT MARKET SUFFERED AND SHOWED MAJOT WEAKNESS, Inwon&amp;#39;r be surprised by Amazon @ 7% premarket, making today A COMPLETE WASH.

However, congrats to valley buyers and the rest. 

God bless your trades. 

Be careful too, frightening macro data streams to markets next 3 business days....

$QQQ $SOXX $ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:27:03 </td>
   <td style="text-align:left;"> $QQQ algo check last 3 days.  Pink is previously mentioned zone. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:26:03 </td>
   <td style="text-align:left;"> $QQQ Fake pump 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:25:51 </td>
   <td style="text-align:left;"> $qqq just a bounce that&amp;#39;ll likely be faded, forecast for operating income less than half of this quarter, sales less than this quarter.  $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:25:49 </td>
   <td style="text-align:left;"> $QQQ I THOUGHT AH DOESNT MATTER LOL WATCH THIS BE RED TOMORROW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:25:15 </td>
   <td style="text-align:left;"> $XELA watch for .85 AH and tomorrow we will gap up hard and push to 1.00+ if $QQQ keeps pumping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:24:21 </td>
   <td style="text-align:left;"> $QQQ with amazon fading, looks like we are going back to reality again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:24:02 </td>
   <td style="text-align:left;"> $QQQ fake pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:23:49 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN $FB

Honestly, this outcome makes perfect sense in hindsight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:22:24 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $AMZN $GOOG 

Good evening

Swing - qqq 2/7 360 c  $2 

Enjoy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:21:39 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Mark went to his MD …

After checking his ass his MD : you must be Mark Zuckerberg…

Mark : how did you know ??

MD : because your ass  has turned into charcoal. 

Ha ha ha ha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:21:03 </td>
   <td style="text-align:left;"> $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:20:34 </td>
   <td style="text-align:left;"> $qqq Welp.  Dan Nathan doesn’t think this tape will rip into da close on a 🖕🐑 FRYDAY!!!!   🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:20:27 </td>
   <td style="text-align:left;"> $AMZN EPS beat includes pre tax gain of their stock in $RIVN !!!  
 
Plus horrible guidance... MM wanted to pump the market for them to get out and short more...  
 
Anything close to 3,300 or above will get big short ...  
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:19:31 </td>
   <td style="text-align:left;"> $AMZN $QQQ  called it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-04 06:18:50 </td>
   <td style="text-align:left;"> $QQQ $IXIC $AMD With the anticipated bump in the morning, it looks to me like the pull back will be behind us. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 10:37:49 </td>
   <td style="text-align:left;"> $AMZN Thank you amzn bulls. Proves why $AMZN still hangs with $AAPL $MSFT $GOOGL . Easily the best 4 large cap! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 10:31:38 </td>
   <td style="text-align:left;"> $AMZN Don&amp;#39;t listen to the Bears who will pick through the bones of this amazing report. The fact is that they all thought this would be a disappointing quarter...even though the stock price already had 12 months of being oversold already built in. Look at AWS, look at advertising! Read it and weep...and well done to latexec9e6346daf7c487b596978f666da65eF 1.104m (53% call/47% put)
$SNAP 995k (57% call/43% put)

Lynk in bayo for option trading ideas and alerts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 10:21:25 </td>
   <td style="text-align:left;"> $SPY $442.. $AAPL $170 $amzn $3100 tomorrow. Bulls got bamboozled. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 10:19:05 </td>
   <td style="text-align:left;"> A true hero 🙏🙏🙏 all is good guys!! $SPY $AMZN $FB $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 10:16:43 </td>
   <td style="text-align:left;"> $AAPL $amzn $snap $qqq

Thanks to amzn and snap which market will be so bullish tomorrow unlike fking stupid fb!!!

Everyone beat er they the only one drop pos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 10:14:55 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $AMZN

Dollar a very good tell now, keep 👀 it.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 10:14:39 </td>
   <td style="text-align:left;"> $SPY $AMZN $GOOG $AAPL $MSFT 

Most of the big tech earnings are out the way now so they’re not being propped up watch out below 📉 sell into the rally take profits or look for shorts 📉 we are not liking the pump and dumps! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 10:14:34 </td>
   <td style="text-align:left;"> $GOOGL $msft $aapl $blk
Will go good green tmr.

Only invest in the above 4 stocks 

Growth stocks are not ready to go yet

Expect more blood in the market 
Tomorrow.  After hour was a bull trap for the growth stocks. 

Btc is an early indicator for the growth stocks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 10:11:33 </td>
   <td style="text-align:left;"> $SPY $AMZN $GOOG $AAPL Jobs report a 8:30. I think the price is baked in, but MM will look for any excuse to have some volatility, as they are making money on each swing because they know what&amp;#39;s coming. (Criminal, actually.) Definitely some fuckery with green Fridays lately. Tomorrow will be interesting heading into another week of earnings with some likely surprise beats to keep things nice and choppy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 10:08:57 </td>
   <td style="text-align:left;"> $AAPL anyone else get the letter for the proxy to vote in March. I vote against having Al Gore on the Board of Directors. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 10:00:22 </td>
   <td style="text-align:left;"> Futures going wild $spy $amzn $qqq $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 09:56:49 </td>
   <td style="text-align:left;"> $AAPL will be interesting to see what happens on ex div date tomorrow on AAPL. Even with the huge upswing in markets in AH with AMZN earnings this couldn’t break 174.5. Tomorrow will tell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 09:55:02 </td>
   <td style="text-align:left;"> $AAPL  futes will flip to red by am!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 09:54:17 </td>
   <td style="text-align:left;"> Green Goose Course time!
We stack $AAPL &amp;amp; $SPY in this strategy!
Been killing it since 2015💪😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 09:45:26 </td>
   <td style="text-align:left;"> $AMZN $TSLA $AAPL $SPY $QQQ  
 NASDQ and S&amp;amp;P futures:  
Unable to break supply line even with AMZN earnings. 
Bearish divergence about to be confirmed on RSI and MACD for 15 mins. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 09:42:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 49 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 09:39:18 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

That’s some cute futes, it’d be a shame if I use this shinny infinity gauntlet to snap them away... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 09:36:10 </td>
   <td style="text-align:left;"> $AAPL god I hope that Amazon helps the whole market go up tomorrow. I seriously need a win </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 09:33:51 </td>
   <td style="text-align:left;"> $AAPL I have to give it up for the Short term Bulls, I  was here when Apple hit the 3 trillion dollar mark.. The market was buzzing with optimism. Now you&amp;#39;re walking around think J.Daddy Powell won&amp;#39;t raise the interest rate.. GLTA. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 09:30:34 </td>
   <td style="text-align:left;"> $AMZN damn shorts got fuked pretty bad here $AAPL $GOOGL $ABB  the only ones you need to get right
Bears falling to ☠️🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 09:28:18 </td>
   <td style="text-align:left;"> $BTC.X $AAPL $ETH.X The episode you DONT want to miss… Here’s why!

https://youtu.be/A8xrPd6aW7I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 09:20:32 </td>
   <td style="text-align:left;"> $SPY $AAPL $FB $TSLA For Harambe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 09:20:30 </td>
   <td style="text-align:left;"> $AAPL $$180 tomorrow f*** this shiiiit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 09:17:52 </td>
   <td style="text-align:left;"> $AMZN $SPY $QQQ $AAPL ya now what? all the big guy earnings are in? whats gonna drive the market now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 09:16:16 </td>
   <td style="text-align:left;"> Facebook (now Meta) plunges 26% today after a disappointing Earnings call. Apple privacy changes has really affected Facebook Ads revenue. With Google also caring more about user&amp;#39;s privacy the Ad department might continue to suffer more. 
 
Can the shift into the #metaverse be what saves Meta? Or make it drop even faster? 
 
$FB $AAPL $GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 09:14:23 </td>
   <td style="text-align:left;"> $FB $AMZN $AAPL $NFLX $GOOGL  
 
So I guess FAANG is now just AAG .... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 09:12:17 </td>
   <td style="text-align:left;"> $AAPL bears bend and bite tomorrow $180.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 09:11:43 </td>
   <td style="text-align:left;"> $AMZN   Amzn position looks solid. First thing to do is sell tomo and chill $SPX  $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 09:10:44 </td>
   <td style="text-align:left;"> $AMD stock market trades like Shit coin pump and dumps now. I think it’s safest to keep your money in companies like $AMD $CAT and $AAPL after weeks like this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 09:10:20 </td>
   <td style="text-align:left;"> Facebook and Google stocks have diverged, and the reason is Apple

$FB $GOOG $AAPL

https://www.cnbc.com/2022/02/03/facebook-and-google-stocks-have-diverged-and-the-reason-is-apple.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 09:09:09 </td>
   <td style="text-align:left;"> Apple Inc. (NASDAQ: $AAPL) – Yet Another Israeli Firm Apart From NSO Group Had Hacked iPhones https://www.billionaireclubcollc.com/apple-inc-nasdaqaapl-yet-another-israeli-firm-apart-from-nso-group-had-hacked-iphones/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 09:06:57 </td>
   <td style="text-align:left;"> $AMZN $FB $SPY $AAPL $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 09:02:05 </td>
   <td style="text-align:left;"> $AAPL Apple, a single tech company is worth nearly $3 trillion.

$BTC.X Meanwhile Bitcoin, an entire global decentralized currency is worth only $700 billion.

We are still so so so early. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 09:00:48 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $175.0 CALLS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:58:22 </td>
   <td style="text-align:left;"> $AAPL disappointed with this move </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:49:47 </td>
   <td style="text-align:left;"> $AMZN $TSLA $FB $AAPL 👣🐇➿⚪ https://markets.businessinsider.com/news/stocks/this-marijuana-penny-stock-had-a-better-1-year-return-than-tesla-apple-facebook-and-amazon-1030991696 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:48:17 </td>
   <td style="text-align:left;"> $AAPL What to know about the Apple privacy changes that crushed Facebook parent Meta… https://finance.yahoo.com/news/how-apple-app-tracking-transparency-works-162225922-220141435.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:47:46 </td>
   <td style="text-align:left;"> $AMZN NDX has become manic, +3% after $AAPL beat and -4% today after FB guided lower. Tonight $AMZN missed on 4Q Revs and guided to 1Q Rev growth of +3-8%, its worst growth ever (WS +11%E). But AMZN +15% AH after raising Prime fees, and recording a one-time $11B gain on Rivian’s IPO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:45:51 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMZN $TSLA $ARKK 
  
As a GenX I hope Millennial keep bidding up my stocks to all time high prices and valuations like the Boomers did with Trillions of FED liquidity for their retirement.  
   
Please don&amp;#39;t drop the baton Millennial! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:43:45 </td>
   <td style="text-align:left;"> $AAPL So, where do we go tomorrow? ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:42:42 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:42:30 </td>
   <td style="text-align:left;"> $AMZN  To all Y’all Bears I know you are hoping  to be able cover your shorts in the morning before you will have to soon mortgage YO MAMA house to convert the margins calls. . This is an Honest opinion, I am sorry Your PUTs are totally fcked… $FB $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:29:47 </td>
   <td style="text-align:left;"> $AAPL great dip to buy, blockbuster earnings, great technicals, and big relative strength. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:29:10 </td>
   <td style="text-align:left;"> $AAPL im guessing 176 tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:27:16 </td>
   <td style="text-align:left;"> $SPY..  #Mentos  
 
 the DOW30 index $DIA  white kijusen 26 candle average line  retest  support . on explosion watch over ichimoku cloud!! $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:24:54 </td>
   <td style="text-align:left;"> $AAPL me betting against this bitch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:20:41 </td>
   <td style="text-align:left;"> Watchlist 📝👀

$TSLA $AAPL $BA $UPS $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:20:31 </td>
   <td style="text-align:left;"> $AAPL 180 thisweek？ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:16:03 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMZN $TSLA $ARKK  
 
JPOW and his Boomers STILL running the show and printing themselves Trillions right up into retirement! 
 
Wen Millennials? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:15:17 </td>
   <td style="text-align:left;"> $AAPL [15s. delayed] filed SEC form 4: Director Gorsky Alex: 
Converted securities 486 of Common Stock at price $0 on 2022-02-01, holding  https://s.flashalert.me/omkc3J </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:12:08 </td>
   <td style="text-align:left;"> $AAPL [15s. delayed] filed SEC form 4: Director JUNG ANDREA: 
Converted securities 1,986 of Common Stock at price $0 on 2022-02-01, increa https://s.flashalert.me/ZdBOjp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:11:27 </td>
   <td style="text-align:left;"> $AAPL 🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣👑👑👑👑👑👑👑👑👑👑👑👑👑THE APPLE POWER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:08:42 </td>
   <td style="text-align:left;"> $AAPL so 205 shares just pumped it .50 cents after hours lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:08:19 </td>
   <td style="text-align:left;"> $AAPL [15s. delayed] filed SEC form 4: Director SUGAR RONALD D: 
Converted securities 1,986 of Common Stock at price $0 on 2022-02-01, inc https://s.flashalert.me/90ixG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:07:41 </td>
   <td style="text-align:left;"> $AAPL     🍏😎👆  Futures:   Wayyyy early…but looking, oh so sweet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:06:55 </td>
   <td style="text-align:left;"> $AAPL [15s. delayed] filed SEC form 4: Director WAGNER SUSAN: 
Converted securities 1,986 of Common Stock at price $0 on 2022-02-01, incre https://s.flashalert.me/x0ha2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:03:40 </td>
   <td style="text-align:left;"> $AAPL It wasn&amp;#39;t no accident, the price dropped to 172.13  toward the end of the session. Don&amp;#39;t ignore the signs.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:03:06 </td>
   <td style="text-align:left;"> $AAPL look at Apple being a stalwart. Shit single handily holding up the nasdaq the last 2 weeks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:03:00 </td>
   <td style="text-align:left;"> $AAPL [15s. delayed] filed SEC form 4: Director LOZANO MONICA C: 
Converted securities 1,986 of Common Stock at price $0 on 2022-02-01, in https://s.flashalert.me/JneqIx </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:02:51 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #4 ticker with sweep activity where institutions are trading options urgently with 33.1K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 08:02:14 </td>
   <td style="text-align:left;"> $AAPL got pump faked lol held off the last few days but fell for that one when it happened at 3:55 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:59:32 </td>
   <td style="text-align:left;"> $AAPL $176 tomorrow unless option kings want to pin at $175 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:59:02 </td>
   <td style="text-align:left;"> Retail Investors ‘Buy the Dip’ 
 
#WallStreet #stocks #options #investors #buy 
 
$SPY $FB $AAPL 
 
“Shares of Facebook owner Meta Platforms drove a surge of options trading Thursday, as some investors positioned for a quick rebound in the company’s stock“–Paul Ebeling 
 
Thursday, retail investors enthusiastically are buying the dip in Wall Street’s biggest growth companies as the US stock market dove following Facebook owner Meta Platforms Inc’s disappointing Quarterly report... 
 
https://www.livetradingnews.com/retail-investors-buy-the-dip-215421.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:58:30 </td>
   <td style="text-align:left;"> $AAPL [15s. delayed] filed SEC form 4: Director BELL JAMES A: 
Converted securities 1,986 of Common Stock at price $0 on 2022-02-01, incre https://s.flashalert.me/BXB0L </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:57:54 </td>
   <td style="text-align:left;"> $AAPL [15s. delayed] filed SEC form 4: Director LEVINSON ARTHUR D: 
Disposed 1,986 of Common Stock at price $173.29 and Converted securiti https://s.flashalert.me/BWmcP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:56:32 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $AAPL How to Monetize Your NFTs… This and MORE on this episode of Whats Next Wallstreet!
Read the comments and share YOURS too -
Like and Subscribe cause you won’t want to miss the next episode tomorrow!

https://youtu.be/lZClebgYsHg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:56:08 </td>
   <td style="text-align:left;"> $AAPL 
🍏🔜🔝🆙
TOMORROW INTRADAY NASDAQ +600 Points 

INCOME $AMZN … I Can’t Believe It!! 
Inusual. The $AAPL GO TO $180 Tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:50:43 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $AMZN $TSLA  
 
A few things Gen X would like Millennials to remember as they continue to buy stocks and take the baton from retiring boomers. 
 
1) Stock valuations don&amp;#39;t matter....buy stocks! 
2) Fiscal debt doesn&amp;#39;t matter....buy stocks! 
3) Fed balance sheet doesn&amp;#39;t matter...buy stocks! 
4) ATH housing prices don&amp;#39;t matter....buy stocks! 
5) Student loans are good...buy stocks! 
 
Summary....&amp;quot;buy stocks!&amp;quot; 
 
You got this! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:50:31 </td>
   <td style="text-align:left;"> $SPY  $AAPL  ..  the #QQQ Nasdaq chart  .. ichimoku.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:50:17 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : App-store bill targeting Apple, Google is approved by Senate panel https://www.stck.pro/news/AAPL/22471155 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:49:04 </td>
   <td style="text-align:left;"> Insiders Trades﻿: $AAPL - Director Sold 1,986.0 shares
-- </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:48:17 </td>
   <td style="text-align:left;"> $AAPL I just want it to touch 172 then I’ll go back long to calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:47:40 </td>
   <td style="text-align:left;"> $AAPL keep on goin’ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:46:38 </td>
   <td style="text-align:left;"> $AAPL here kitty kitty </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:46:37 </td>
   <td style="text-align:left;"> &amp;gt; https://www.crn.com/slide-shows/components-peripherals/the-10-hottest-semiconductor-companies-to-watch-in-2022
🤑🚂💨all aboard… $INTC
$AMD ↗️➕ $XLNX 

$NVDA  | $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:46:23 </td>
   <td style="text-align:left;"> $AAPL [15s. delayed] filed SEC form 4: Director GORE ALBERT JR: 
Converted securities 1,986 of Common Stock at price $0 on 2022-02-01, inc https://s.flashalert.me/oJQZd </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:44:54 </td>
   <td style="text-align:left;"> $AAPL 1,986 shares acquired by Wagner Susan (Director), reported in a new form 4 filed with the SEC  https://newsfilter.io/a/983aa091ffc93208273cf3a9e9aa4bd7 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:44:51 </td>
   <td style="text-align:left;"> $AAPL ex dividend tomorrow for apple $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:43:43 </td>
   <td style="text-align:left;"> $AAPL NEWS - AAPL Reports First Quarter Results: 
https://www.youtube.com/watch?v=B2e7yheNg_E </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:41:02 </td>
   <td style="text-align:left;"> The industry average ROE is 22.20%. $AAPL outperforms 94% of its industry peers. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:39:25 </td>
   <td style="text-align:left;"> $AAPL 1,986 shares acquired by Sugar Ronald D (Director), reported in a new form 4 filed with the SEC  

https://newsfilter.io/a/a8e615482cd598863d4db183221c7517 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:37:48 </td>
   <td style="text-align:left;"> $AAPL reported 5 new insider trades to the SEC in the last 2 minutes.

1,986 shares acquired by Gore Albert Jr (Director)   https://newsfilter.io/articles/4-form-6e729ab9ebc1e1c8eb0fe0770cd89197
$344,153.94 of shares sold by Levinson Arthur D (Director)   https://newsfilter.io/articles/4-form-d677ef949710a19289254305ad92063b
486 shares acquired by Gorsky Alex (Director)   https://newsfilter.io/articles/4-form-5015e6172af8ddb71fe1dd8fdfe5a1b7
1,986 shares acquired by Jung Andrea (Director)   https://newsfilter.io/articles/4-form-21af0cbe7f88027e29bf96e1787782f3
1,986 shares acquired by Lozano Monica C (Director)   https://newsfilter.io/articles/4-form-f2623510095d44015fde4b7c1da897c8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:37:42 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $AMZN 
 
Listen up JDADDY!...she has message for you and all your endless meddling in the financial markets. 
 
The younger generations don&amp;#39;t like you printing away their futures. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:36:52 </td>
   <td style="text-align:left;"> Insider Arthur D Levinson reports selling 1,986 shares of $AAPL for a total cost of $344,153.94 https://fintel.io/n/us/aapl/levinson-arthur-d?utm_source=stocktwits.com&amp;amp;utm_medium=Referral&amp;amp;utm_campaign=insider </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:36:47 </td>
   <td style="text-align:left;"> $AAPL TOMORROW WE SEE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:34:16 </td>
   <td style="text-align:left;"> $AAPL will this stock go to 500 ever? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:33:49 </td>
   <td style="text-align:left;"> $SPY Nightly News has stories on $fb drop so,... thats the signal its getting to the end of the dip, few more days maybe but,.. 
 
$qqq $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:32:44 </td>
   <td style="text-align:left;"> $AAPL I took an L on a stock in my Roth IRA. Small one lol putting the 2500
Here once funds settle 

Apple to 1,000 by the time I’m 50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:32:33 </td>
   <td style="text-align:left;"> $AAPL 📜 SEC Form 4: Bell James A converted options into 1,986 shares, increasing direct ownership by 6% to 36,266 units

https://quantisnow.com/insight/2353774?s=s

45 seconds delayed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:32:05 </td>
   <td style="text-align:left;"> Most Active stocks during last session $FB $SNAP $AMD $F $AAPL  
 
Learn more: https://www.finscreener.org/screener/most-active </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:31:44 </td>
   <td style="text-align:left;"> $AAPL 1,986 shares acquired by Bell James A (Director), reported in a new form 4 filed with the SEC  

https://newsfilter.io/a/1067c3404fcb0fc6019231f342f1ee31 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:30:46 </td>
   <td style="text-align:left;"> MOVES HAPPENING NOW (6:30pm)

⦿ $AAPL is down 0.0% in the last 5 mins. 

⦿ There are 8 stocks that are up more than 3% in the last 5 mins. 

⦿ The top gainer is up 8.9% in the last 5 mins. 

 See the stocks that are moving the most right now via link in bio (wallstreetodds .com). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:27:53 </td>
   <td style="text-align:left;"> $AAPL so as $FB brought tech down today, does $AMZN bring tech back up tomorrow???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:23:32 </td>
   <td style="text-align:left;"> $SPY $AMZN $FB $AAPL $PYPL 
 
Trillion dollar companies flopping around like penny stonks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:21:35 </td>
   <td style="text-align:left;"> $AMZN $spy $aapl $msft 

Congrats 🍾🎈🎉 tomorrow we keep going up 🚀🚀🚀🚀🍾

Done for the day !!! Bye ✌️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:20:50 </td>
   <td style="text-align:left;"> $BKKT soon $AAPL  deal? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:20:45 </td>
   <td style="text-align:left;"> $aapl that was one of its suppliers which forecast its rev 375-405 versus 446 this quarter (lumentum). it was in dow jones/barrons news. perhaps a slowdown, thoughts on that? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:19:56 </td>
   <td style="text-align:left;"> latex3d34874ab17b820a5eeea19c1ed51d38GOOG 
$AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:18:13 </td>
   <td style="text-align:left;"> $F Farley&amp;#39;s tone suggests that Ford can be acquired by $AAPL or a joint venture acquisition with $AAPL &amp;amp; $RIVN . His tone was most divergent from the PR Bravado building into this ER! Thoughts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:10:36 </td>
   <td style="text-align:left;"> Unusual Options Activity: $AAPL is the #19 ticker with unusual activity from institutional traders with an average of 18% out of the money, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:06:30 </td>
   <td style="text-align:left;"> $MSFT $AAPL $SPY $GOOGL $AMZN USA always wins in everything!  US will be 500+ years strong! fuck china and russia 🖕😡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:06:23 </td>
   <td style="text-align:left;"> $AAPL climb!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:06:18 </td>
   <td style="text-align:left;"> $AAPL I fucked up and fell for the dump lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:05:51 </td>
   <td style="text-align:left;"> $AAPL gap up $180.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:05:08 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Snap recovers from Apple privacy changes, shares surge 50% https://www.stck.pro/news/AAPL/22470736 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:03:10 </td>
   <td style="text-align:left;"> $AAPL JIM CRAMER... BUY $AMZN $AAPL $GOOG 
good luck $SPY 🤣🤔.. ive seen him hit that buy button and remember the Dumps that follow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:02:14 </td>
   <td style="text-align:left;"> $AAPL squeeze $180 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:01:27 </td>
   <td style="text-align:left;"> $AAPL JIM CRAMER GONA SAY BUY BUY BUY $AMZN ??? ID LAUGH MY BALLZ OFF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 07:00:12 </td>
   <td style="text-align:left;"> $AAPL pelosi sold! $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:55:30 </td>
   <td style="text-align:left;"> $AAPL  AAPL tomorrow.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:55:12 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $AMZN $FB 

My thoughts on the mkt action today/AHrs .... 

Yesterday I had sent out an email to members that I was going short at the 458 level on the SPY as we hit the 50 day EMA (SEE BELOW) It was the first short alert I have sent out since we had our capitulation Monday. Today I sent an email out when we were just below 450 suggesting the possibility that AMZN and the jobs data could possibly put a short term halt to the mkt selling. 

I believe we are heading a bit lower. The mistake a lot of traders/investors are making are believing things materialize overnight. Plenty of headfakes happen in between - like FB and AMZN which caught an enormous amount of people offsides. Like the late day surge yesterday into the 458 level. Like the capitulation last Monday. Both bull and bear traps will be set. 

I  teach technical analysis in order to pick entry/exit points for stks and indexes. If interested in joining, feel free to email me at

 jessielivermore1929@gmail.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:54:07 </td>
   <td style="text-align:left;"> $aapl bullish today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:53:40 </td>
   <td style="text-align:left;"> $AAPL such a manipulation.. shit stock $fb drops with bad earnings , whole market comes down but $amzn had killer earnings , shit won’t move.. MMs were really counting on bad er second day in a row 🤣😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:53:09 </td>
   <td style="text-align:left;"> $FB 🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣.  
Buy it pre earnings they said 😂 
I love $AAPL for fuking low lives scumbags Meta sh*t 
$200 soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:52:04 </td>
   <td style="text-align:left;"> $ASO my locks for option trading for this year: $PLAY is in a really good position to move higher, ASO, $GM is in a solid position after a rough patch, $DIS is a sure bet for decent earnings the next 4Q, don’t bet against disney, they have money coming in from everywhere, like $AAPL, their EPS is steadily rising. Good luck to everyone, and buy shares with your options! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:51:46 </td>
   <td style="text-align:left;"> $AAPL https://stocks.apple.com/A1-0_QikWTHqRGEga5Z_LbQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:50:02 </td>
   <td style="text-align:left;"> $SPY $SPX $AAPl  #BotWaldo shows where we ar in the 5 wave count..  a Gap over the $352 equilibirum level would be primed for very fast run higher. Gap n Go. 
 
 
  the extended 5th wave to pepsi blow off fizz fizz top into rate hikes. 
 
the powerful Wave 3 higher  from Lows $4200 after saw the 10&amp;#39;s of Billions in Darkpools mentioned was relentless rally as Wave 3&amp;#39;s are..  today was the Brutal wave 4 down to frustrate and wreck before the fast and powerful Wave 5 higher to ichimoku cloud at $465 1st target.. very possible of cloud top breakout and extend higher into blow off top...  opinion. will watch further data to confirm. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:48:01 </td>
   <td style="text-align:left;"> $AMZN LMAO I can&amp;#39;t believe amazon is up AH from Q4 $RIVN stake. Dude look at the stake now... $60 they got RIVN at $78. Q4 RIVN was +$100. The number shown now should not be a good sign. Their Earnings were all misses and if not for including RIVN into earnings they would have lost 11.8 billion in revenue. SHEEEESSSHH. Lol This is some crazy pump fake. $SPY $AAPL $ETSY https://www.investing.com/news/stock-market-news/amazon-hikes-prime-membership-fees-in-us-2756633 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:41:35 </td>
   <td style="text-align:left;"> $AAPL I expect lots of short squeezes tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:39:56 </td>
   <td style="text-align:left;"> $SPY Under the hood of earnings is showing pretty steep growth contractions, in a time of zero rates and growth should be at its peak $AMZN $NVDA $AAPL $AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:38:03 </td>
   <td style="text-align:left;"> $AMZN getting carried by $RIVN 11.8 billion attributed to the company&amp;#39;s investment in Rivian. When they had price of $100+ than their current price $60. Not only that they clearly didn&amp;#39;t meet the estimates. Funny earnings lol now we know amazon is now a spac like $ARKK and becoming Cathie Woods 2.0 lmao 🤣 😆  idk how we shot up, but retail investors clearly jumping the gun on this. Good luck $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:32:10 </td>
   <td style="text-align:left;"> $aapl $mp $tsla $nvda    
 
Highly recommended, it&amp;#39;s a free joining: ❤❤https://unlimitedtraderscomm.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:31:47 </td>
   <td style="text-align:left;"> $AAPL 178 open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:29:15 </td>
   <td style="text-align:left;"> $AAPL $AMZN $AMD Are you ready?

https://www.instagram.com/reel/CZiAWKXL0Ac/?utm_medium=copy_link </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:28:11 </td>
   <td style="text-align:left;"> $AAPL this thing could see 179-180 tomorrow for real thou! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:27:30 </td>
   <td style="text-align:left;"> $AAPL 112 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:27:17 </td>
   <td style="text-align:left;"> $AAPL 175-177.50 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:27:14 </td>
   <td style="text-align:left;"> $AAPL Why are  the Media Head. CNBC talking points lean towards the BEARISH side.. this is suspicious. Should we buy toilet paper to prepare for the reaming..$NFLX $MSFT  Facebook already buried the bone🍆🍆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:27:06 </td>
   <td style="text-align:left;"> $AAPL lets Rip Im very Bullish here tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:26:55 </td>
   <td style="text-align:left;"> $AAPL it held up well....hope i can buy it back cheaper </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:26:21 </td>
   <td style="text-align:left;"> $SPY Theres no way rivians stock boost account for 85% of amazon&amp;#39;s income. If so.... that&amp;#39;s a pretty scary earnings report $AAPL $TSLA $NVDA $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:25:44 </td>
   <td style="text-align:left;"> $FB Facebook’s $237.6B fall sets record for largest one-day value drop in stock market history. The previous record for amount of market capitalization lost in one day was $AAPL $182 billion loss in September 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:24:39 </td>
   <td style="text-align:left;"> $SPY Puts literally never pay, why do y&amp;#39;all keep buying them.... Better ways to short the market $AAPL $MSFT $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:24:22 </td>
   <td style="text-align:left;"> $AAPL it was shown this week that Apple protected all of us from Facebooks spying. To me, that&amp;#39;s bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:23:26 </td>
   <td style="text-align:left;"> $SPY Lol tech does well to &amp;quot;increase revenue&amp;quot; but creates massive wastes and pollution. at what cost $AAPL $AMZN $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:23:22 </td>
   <td style="text-align:left;"> $AAPL safe space and profitable tech stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:22:12 </td>
   <td style="text-align:left;"> $SPY 2 stocks keeping this afloat. And if it wasn’t for $AMZN today $AAPL was about to drag this to the dirt. Bulls are delusional buying these levels, if any really are which I doubt. Just holding and hoping, nobody sane would buy anything here lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:21:56 </td>
   <td style="text-align:left;"> $AAPL $TSLA $SPY what time is job report tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:20:33 </td>
   <td style="text-align:left;"> $AAPL pelosi sold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:20:33 </td>
   <td style="text-align:left;"> $AAPL has no business being above $174 again especially with AMZN selling off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:19:43 </td>
   <td style="text-align:left;"> $AMZN increasing prime membership sounds great for consumers. You gotta adjust to inflation am I right rich folks?? Or am I right? Or sales Rev and eps are misses but atleast we got $RIVN $SPY $ETSY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:16:33 </td>
   <td style="text-align:left;"> Snap Delivers a Surprise Profit. It Doesn&amp;#39;t Have All of Facebook&amp;#39;s Problems.  $SNAP $FB $AAPL 

https://newsfilter.io/a/2ee6f46b207eb6cf5ef204c241ad3f78 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:14:25 </td>
   <td style="text-align:left;"> $NFLX If Ackman was a smart dip buyer, he would buy $AMZN or $AAPL not buying expensive  junk stocks 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:11:53 </td>
   <td style="text-align:left;"> $SPY $AAPL $QQQ $AMZN We turn $ into $$$$ everyday team learn how to play earnings  this Sunday 2pm via zoom! https://www.eventbrite.com/e/play-earnings-turn-50-into-500-overnite-using-vertical-options-tickets-252561236457 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:11:38 </td>
   <td style="text-align:left;"> $AAPL next iphone they better raise the PPI. I want a more sharper screen lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:10:11 </td>
   <td style="text-align:left;"> like it or not my target will be $amzn $tsla $aapl shorts at tomorrow pump .. but job report might not let enough pump tomorrow... 
 
BUY THE DIPS ; SHORT THE RIPS... $spy  .. of course there must be reason for it.. dont buy or short company you dont know !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:09:14 </td>
   <td style="text-align:left;"> $AAPL $AMZN  up $427.00 Bezos Bucks since the opening,  and  my amazon prime account subscription increased in price also,follow the money..  Im cooking with Crisco.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:07:44 </td>
   <td style="text-align:left;"> $AAPL Holy shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:04:42 </td>
   <td style="text-align:left;"> $AAPL Shut up CNBC bears! You are wrong as usual! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:04:35 </td>
   <td style="text-align:left;"> $SPY Amazon will continue to have terrible margins for years to fuel growth and take more market share. But their ecosystem (Prime) is where the real value is at. $MSFT and $AAPL should outperform them for some time but I would use that to buy $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:03:17 </td>
   <td style="text-align:left;"> $AMZN, $AAPL saved the whole market before and I hope AMZN , too. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 06:02:51 </td>
   <td style="text-align:left;"> $AAPL Bears deserved to be squeezed like this! AMZN, SNAP, PINS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:59:54 </td>
   <td style="text-align:left;"> $AAPL not the way I was hoping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:59:50 </td>
   <td style="text-align:left;"> I HAVE BEEN PREACHING TO STUDENTS all week.. find a better discord that is alerting out of the money strangle CALL AND PUTS.. THESE moves I have not seen ever out of companies 500-1bil* market caps going up 25% or down 25%. The best way to play right now is through this strategy for me. FB we netted over 1500%+. AMZN should be another 1500%+. CRAZINESS. $AMZN $FB $SNAP $AAPL $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:59:34 </td>
   <td style="text-align:left;"> $AAPL Volatility is King!! Simulated Weekly $175.0 CALLS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:59:25 </td>
   <td style="text-align:left;"> $AAPL People forget so fast that meta is down because aaple wanted it to be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:59:22 </td>
   <td style="text-align:left;"> $BKKT biggest POS I ever owned. In at 20. If this was worth anything they would be bought out. Mgmt sucks. False misleading comments about closing in on a deal w $aapl Ben shirts to $3. Painful. No bounce. Losers running this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:59:12 </td>
   <td style="text-align:left;"> $AAPL 

I don’t feel sorry for all the week hands bailing on quality stocks like Apple and Microsoft. Bunch of dummy’s. Good luck real investors </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:58:54 </td>
   <td style="text-align:left;"> $AAPL $AMZN I gotta get me one of those high frequency trading things. Maybe Amazon has them. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:58:08 </td>
   <td style="text-align:left;"> $AAPL  LFG🌈🌈🌈🎯Who&amp;#39;s your daddy..$AMZN🍆 $$FB🍆 $GOOG 🍆3T in coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:57:51 </td>
   <td style="text-align:left;"> $AAPL instutional ownership always tells a story https://stockilluminati.com/aapl/institutional.php </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:57:26 </td>
   <td style="text-align:left;"> $FB Facebook releasing the best phone this summer and take all of $AAPL and samsung market share???  This is fuckin war on Apple and Tim Crooks!!! Zuck rules.  Also, releasing Electric truck capable of 5,000 miles on a single charge.  Coast to coast domination.  Fuck $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:57:14 </td>
   <td style="text-align:left;"> $FB $AMC $AAPL $BTC.X $TSLA Marky   Cuckleberg 🦍🦍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:56:28 </td>
   <td style="text-align:left;"> $AAPL why not much movement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:54:53 </td>
   <td style="text-align:left;"> $AAPL wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:53:44 </td>
   <td style="text-align:left;"> $SPY $AMZN $AAPL $QQQ come on laugh a little </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:53:32 </td>
   <td style="text-align:left;"> $AAPL Has been very technical off the Jan 24 low.  We still are favouring more upside before a pullback against the Jan 24 low takes place.  We don’t prefer to trade the middle area right now, members are already risk free from the blue box further down and holding for higher.   #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:52:05 </td>
   <td style="text-align:left;"> $AAPL now I hope $amzn with it’s 20% run Ah takes all tech stocks higher with it.. 5% higher tomorrow will be fine with me.. just want to see $aapl $baba make new highs….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:49:53 </td>
   <td style="text-align:left;"> $BB $FB $AAPL 🍎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:49:01 </td>
   <td style="text-align:left;"> $BTC.X $AAPL , $GOOGL , now $AMZN! I bet $FB would have made it, too if not for privacy  changes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:48:39 </td>
   <td style="text-align:left;"> $AAPL Bought 100 snap and it’s up over $1 wow! Guess I didn’t totally miss it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:48:17 </td>
   <td style="text-align:left;"> $AAPL Amazon saved the market, this market is a joke, bubble bubble </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:47:54 </td>
   <td style="text-align:left;"> $AAPL Timmy is the Man...🌈🚀LFG~ 2 zero. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:47:30 </td>
   <td style="text-align:left;"> $AAPL  Pump to 175s or 176s again ; i ll short it:) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:47:08 </td>
   <td style="text-align:left;"> triumphant stocks ($AMD, $AMZN, $AAPL, GOOG, MSFT) set a new bottom after a significant pullback. good development for long term investors! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:46:50 </td>
   <td style="text-align:left;"> $SNAP boom baby boom!  You all seeing this at $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:44:44 </td>
   <td style="text-align:left;"> $AAPL any reason for the green lag AH? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:43:28 </td>
   <td style="text-align:left;"> $AAPL $AMZN Massive selling in Apple at the close before a big jump in Amazon... interesting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:43:06 </td>
   <td style="text-align:left;"> $AAPL go up pussy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:42:25 </td>
   <td style="text-align:left;"> $AAPL come on Apple .. move your ass to 180$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:42:09 </td>
   <td style="text-align:left;"> $AAPL IS BIDEN SERIOUS??  🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:42:08 </td>
   <td style="text-align:left;"> $AAPL don’t get caught to short tactics and they are trying to cover. Let the fuckers squeeze to $180.00 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:41:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $UVXY $AMZN 
 
                            Amazon is to EPS  
 
                                       like 
 
                             Jesus is to Water </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:41:22 </td>
   <td style="text-align:left;"> $PINS $SNAP this is huge. 🤞🚀💰

My personal play of the year so far.💰💰

Placed 20 mins before mkt close.

Congrats to whomever followed the play. 

Enjoy the fireworks.

Easily 3x gains.

$FB $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:40:16 </td>
   <td style="text-align:left;"> $AAPL $GOOGL $AMZN $NVDA only up from here, there was too much fear baked in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:40:06 </td>
   <td style="text-align:left;"> $AMZN $AAPL $GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:39:33 </td>
   <td style="text-align:left;"> $AAPL please please stay flat and open at 174 so I can snag 175 calls for a qtr and sell them at EOD for 5+. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:38:50 </td>
   <td style="text-align:left;"> $SWKS main customer is $aapl....and apple had a good beat...not getting it ??? any experts ??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:38:11 </td>
   <td style="text-align:left;"> $spy So we know when Futures Open the  Nas will be taking back those FB losses. 
Insane how feeble WS is, rush to Sell on any little fear &amp;amp; then buy back in 
 
$baba $qqq $aapl $msft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:37:04 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 482.0K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:36:54 </td>
   <td style="text-align:left;"> $SHOP taking my $AMZN  profits here for earning next week! Been a very profitable earning season! thank you $AMZN $AAPL $AMD $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:36:12 </td>
   <td style="text-align:left;"> $AAPL I want 180$ tomorrow to celebrate the weekend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:36:06 </td>
   <td style="text-align:left;"> $AMZN  follow me for more of this confidence and Study. $FB $AAPL https://stocktwits.com/greenthoughts/message/433097200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:35:49 </td>
   <td style="text-align:left;"> $AAPL $AMZN $SPY 
 
We&amp;#39;ve reached a point where 2 companies = &amp;quot;the market&amp;quot; 
 
lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:34:56 </td>
   <td style="text-align:left;"> $AAPL  🍏 For the Bull’s eyes only:  In the “final second” of the Close, 12.9 Million AAPL Shares traded to the “Buy Side”.  Pro Traders know, what that may mean. Strong Closing Volume…all before, AMZN reported After the Bell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:34:34 </td>
   <td style="text-align:left;"> $AAPL shorts get the fuck out of here. Tomorrow $178.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:34:16 </td>
   <td style="text-align:left;"> $GOOGL Can&amp;#39;t wait for this, $AAPL AND $MSFT to green $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:34:00 </td>
   <td style="text-align:left;"> $AAPL: Both the short term and long term trends are positive. This is a very positive sign. https://www.chartmill.com/stock/analyzer/stock/AAPL?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:33:45 </td>
   <td style="text-align:left;"> $AAPL 

Tmw will be a new day for more rally ..

Today was a huge dip! Congrats whoever bought the dip! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:33:41 </td>
   <td style="text-align:left;"> $AAPL Rip to those 1dte 170Ps I bought and held . They were up 140% , for sure to open -99% Lolll </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:32:01 </td>
   <td style="text-align:left;"> $AAPL all the bulls on here expecting a huge gap up, ignoring all the market fundamentals that caused this to sink. hilarious. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:31:52 </td>
   <td style="text-align:left;"> The mega giants keep thriving $AAPL $AMZN $GOOGL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:30:40 </td>
   <td style="text-align:left;"> $AAPL  Did you guys just see SNAP?
Missed that boat. Just shot up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:30:34 </td>
   <td style="text-align:left;"> $MSFT $AAPL $AMZN $NFLX $GOOGL no more faang, call then maang </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:30:17 </td>
   <td style="text-align:left;"> $PYPL nervous $AAPL will buy them out for $250B </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:30:08 </td>
   <td style="text-align:left;"> $AAPL ER tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:29:23 </td>
   <td style="text-align:left;"> $AAPL nasdaq will be huge gap up tomorrow $178.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:29:12 </td>
   <td style="text-align:left;"> $AAPL For all devoted 🐻 
As I posted before you choose the wrong stock. Here is Neil Cybart tweet: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:28:42 </td>
   <td style="text-align:left;"> $AAPL $200 by June. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:28:19 </td>
   <td style="text-align:left;"> $SPY Amazon earnings were pretty light for several quarters of Zero Rates... idk  $AAPL $AMZN $TSLA $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:26:43 </td>
   <td style="text-align:left;"> $AAPL   🍏😎 👆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:26:08 </td>
   <td style="text-align:left;"> $F I got March calls $25.00 .. should have grabbed sone for $amzn 😞 too.. it’s alright just want to see $aapl $baba $f fly in Falcon tomorrow….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:25:58 </td>
   <td style="text-align:left;"> $AAPL How people over look the EOD 11 million dollar sell order.. 🌈 Dumb money purge continues. Buy High then ,sell Lower </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:25:32 </td>
   <td style="text-align:left;"> $AAPL Heck $180 on the way! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:25:28 </td>
   <td style="text-align:left;"> $AMZN $MSFT $AAPL $GOOG 

FAANG is now MAGA 

Microsoft 
Apple
Google 
Amazon

Load up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:24:34 </td>
   <td style="text-align:left;"> $AAPL 176 tomorrow ✅✅🍏🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:24:14 </td>
   <td style="text-align:left;"> $AAPL MAGA SUPREMACY WOOOOO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:24:12 </td>
   <td style="text-align:left;"> $AAPL Looks like apple won’t sink tomorrow, Shorts pull up your pants 👖! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:24:02 </td>
   <td style="text-align:left;"> $PINS this will hold.

And no i got no insiders.

Also i don&amp;#39;t respond to dms. 

Discord still private &amp;quot;invites only&amp;quot;

I just share free money plays.

Holding 260 calls. 🚀🤞💰

$AAPL $FB $TSLA $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:23:06 </td>
   <td style="text-align:left;"> $AMC $GME $TSLA $AAPL somebody get sleepy Joe an Uber to the old folks house and not the White House. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:23:05 </td>
   <td style="text-align:left;"> $SPY $MSFT $AAPL $GOOGL $AMZN 

Damn Amazon !!! 🚀🚀🚀 question let’s say I work for them ? Can I ask for a raise 😂😂😂.  Look at those numbers !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:22:55 </td>
   <td style="text-align:left;"> $aapl $fb a few reasons why amazon&amp;#39;s bounce will likely be faded quickly, operating income weaker by half from last quarter and forecast has sales slowing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:22:53 </td>
   <td style="text-align:left;"> $WWE record results and beat everything by far!! Let’s freaking $AAPL $AMZN $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:22:47 </td>
   <td style="text-align:left;"> $AAPL my Apple strangle is fuked&amp;gt;&amp;lt;! That dip eod worry me that if Amazon beat er bad apple gonna open at 175 tomorrow  which is where i bought my 172.5/177.5 strangle and fked me over :( it came true. Im so sad rn. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:21:52 </td>
   <td style="text-align:left;"> $BABA till this morning morobs we’re bashing $amzn abd $baba abd $aapl saying amzn revenues will be shit 🤣😂 fucking sob stock is up whole $500.00 ah.. what else do we want.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:21:09 </td>
   <td style="text-align:left;"> $GOOG congrats $GOOGL, you are the only split on the block!  Time for $3,800-$4,000 by July. $AMZN $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:21:02 </td>
   <td style="text-align:left;"> $AAPL Same idiots that sold Apple on FB earnings are now buying Apple on Amazon earnings! 
What has price of cigarets has to do with the price of milk 😂😂😂😂😂😂😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:18:57 </td>
   <td style="text-align:left;"> $AMZN $GOOGL $AAPL $MSFT called all of them correctly :) 

The last one left for me is $NVDA - massive beat incoming 300+ easy ¯\_(ツ)_/¯ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:18:33 </td>
   <td style="text-align:left;"> $AAPL can we all agree that $FB blows ? Worst company on the planet! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:18:09 </td>
   <td style="text-align:left;"> $SPY well I shit you not it’s MAGA 

$MSFT $AAPL $GOOGL $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:16:50 </td>
   <td style="text-align:left;"> $SPY From FAANGM, the real leaders now stand out $AAPL $AMZN $MSFT $GOOG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:16:36 </td>
   <td style="text-align:left;"> $AAPL So much for my cheap lotto puts. My Mar18 calls are still safe though (for now). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:16:35 </td>
   <td style="text-align:left;"> $AAPL - gotta love that daily chart double top Apple turnover. My puts are looking delicious. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:15:56 </td>
   <td style="text-align:left;"> $AAPL tomorrow $178.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:13:52 </td>
   <td style="text-align:left;"> $AMZN $MSFT $AAPL Poor bears...gambled their future...and now (again) BEARS R FUUUUCD 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:13:38 </td>
   <td style="text-align:left;"> $AMZN $AAPL $FB $MSFT $GOOGL 
Lol. Amazon missed it. Lol 😂 https://www.google.com/amp/s/www.zdnet.com/google-amp/article/amazon-stock-soars-q4-results-outlook-miss-expectations-raising-prime-price/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:13:07 </td>
   <td style="text-align:left;"> $SPY Petition to change FAANG to MAAG. $MSFT $AAPL $AMZN latex9a907cf9a9d01f4bbce87aa66ba4c640AMZN   
$googl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:09:03 </td>
   <td style="text-align:left;"> $AAPL people earlier. But but we shouldn&amp;#39;t follow amazon we are apple. Amzn up on initial read right now. When Apple goes down over the next two weeks none of this will matter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:08:37 </td>
   <td style="text-align:left;"> $AAPL we have a horrible jobs report coming tomorrow. not out of the woods here. this wasn&amp;#39;t down just because of FB or AMZN. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:08:26 </td>
   <td style="text-align:left;"> $SPY the $FB censorship losses scared everyone into thinking we are in a recession.  But it is a $fb and $AAPL issue only.  $AMZN proves it!!!! $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:08:19 </td>
   <td style="text-align:left;"> $AAPL Eh, I was hoping this would wait until I after I could buy back my covered call. Ah well, i guess me gains be capped. Gains is gains, grats all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:08:04 </td>
   <td style="text-align:left;"> $aapl wowwww so i guess $amzn bezos is gonna take a hot shit on $tsla Musk for being the richest man again SHEEESH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:07:52 </td>
   <td style="text-align:left;"> $AAPL So Amazon misses on revenue and its up 13% and this fucker is stuck in the mud again ..Apple can buy amazon with its petty cash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:07:47 </td>
   <td style="text-align:left;"> buffett stocks holding this all up $AMZN $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:07:46 </td>
   <td style="text-align:left;"> $AAPL better open at 176 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:07:46 </td>
   <td style="text-align:left;"> $AMZN everyone going up on AMZN. Getting carried hard. $ETSY $SPY $AAPL $msft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:07:31 </td>
   <td style="text-align:left;"> $AAPL  $180 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:06:54 </td>
   <td style="text-align:left;"> $AAPL The other A crushed it.  do we see 180 tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:05:42 </td>
   <td style="text-align:left;"> $AAPL Thank you AMZN! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:05:42 </td>
   <td style="text-align:left;"> $AMZN thanks guys! I’m a software engineer I know how this shit works lmao 🤣 

Follow for alerts congrats those that followed :) $SPY $GOOGL $AAPL 

Also fb is trash short it more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:05:34 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $AMZN AMAZON!!!!💎💎💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:05:32 </td>
   <td style="text-align:left;"> $AMZN it’s time for MAGA, not faang anymore $AAPL $GOOG $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:05:25 </td>
   <td style="text-align:left;"> $AAPL Check out $AMZN! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:05:17 </td>
   <td style="text-align:left;"> $AAPL   🍏 Amazon, massive Beat.  Congratulations, to those “in the know” as AAPL dipped into the Close”.  Hope you bought the “Dip”. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:04:39 </td>
   <td style="text-align:left;"> $AAPL someone bought 10 million shres in one minute!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:04:08 </td>
   <td style="text-align:left;"> $SPY $qqq $aapl bear extinction level event $amzn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:04:08 </td>
   <td style="text-align:left;"> $AAPL KICKING MY SELF FOR NOT ROLLING OUT THE SHORTS EVEN FURTHER AAAAGH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:04:00 </td>
   <td style="text-align:left;"> $AMZN $AAPL $GOOGL - Don&amp;#39;t ever bet against any of them ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:03:57 </td>
   <td style="text-align:left;"> $AAPL well……..$AMZN happened. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:03:02 </td>
   <td style="text-align:left;"> $AMZN LETS GOOO

$GOOGL $AAPL $MSFT $AMZN LEAD THE WAY. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:02:06 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL 💩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:01:15 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ $SLV $GOLD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:01:04 </td>
   <td style="text-align:left;"> $SPY $AAPL &amp;quot;Technicals don&amp;#39;t work..blah blah blah...&amp;quot;   
 
... 🤷‍♂️😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:00:28 </td>
   <td style="text-align:left;"> $TQQQ 

Amazon is gonna cause the same kind of market bounce we saw from $AAPL $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 05:00:19 </td>
   <td style="text-align:left;"> $TSLA $AMZN $AAPL $GOOG $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:59:53 </td>
   <td style="text-align:left;"> $AAPL why? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:59:40 </td>
   <td style="text-align:left;"> $AAPL come on apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:59:30 </td>
   <td style="text-align:left;"> $AAPL all of you options gamblers are the ones ruining the stock market. They should go back to making people pay per trade. Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:59:03 </td>
   <td style="text-align:left;"> $AAPL I was wrong today; I didn&amp;#39;t think we&amp;#39;d get lower than $174. GG bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:58:14 </td>
   <td style="text-align:left;"> $AAPL you think aapl can live alone?! you cant be going up while the rest of the FAANG go down. you the best bro?! you&amp;#39;ll be ganged up by all other stocks and you&amp;#39;ll be dropping to oblivion! just crash 20% too aapl bitch! hahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:58:13 </td>
   <td style="text-align:left;"> $AAPL Everyone is APPLES bitch... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:57:33 </td>
   <td style="text-align:left;"> Ticker: $AAPL 
Buy: February 04, 2022 $175.00 Calls 
Entry Price: $0.83 - $0.83 
Exit Price: $1.04 
Stop Loss: $0.73 
Potential ROI: 25% 
Estimated Hold Time: 34 Minutes 
Alert Courtesy Of: https://www.fastscalp.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:57:29 </td>
   <td style="text-align:left;"> Unusual Option Alert on $AAPL $2,515,143 call sweep traded with $100.0 strike expiring on 2022-02-18. Via: https://www.stockgrid.io/optionsflowcumulativestats/AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:57:07 </td>
   <td style="text-align:left;"> $spy if $fb could do so much psychological damage to so many stocks $PINS $SNAP .  Can you imagine what $AAPL would have done to the market had earnings been disappointing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:57:02 </td>
   <td style="text-align:left;"> $AAPL adding this dip $SPY 180 tomm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:57:02 </td>
   <td style="text-align:left;"> $AAPL alright close the market now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:56:57 </td>
   <td style="text-align:left;"> $AAPL Long puts. It looks tired up here... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:56:55 </td>
   <td style="text-align:left;"> $AAPL 77$ PER CONTRACT!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:56:54 </td>
   <td style="text-align:left;"> $AAPL nice fade into the close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:56:29 </td>
   <td style="text-align:left;"> $AAPL will make me a million :) with the apple car. GL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:56:29 </td>
   <td style="text-align:left;"> $AAPL hell going on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:56:20 </td>
   <td style="text-align:left;"> $AAPL and now you see the bull trap closing down on you. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:56:05 </td>
   <td style="text-align:left;"> $AMZN $GOOGL $AAPL Remember, bulls make money, bears make money, and hogs get slaughtered </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:55:50 </td>
   <td style="text-align:left;"> $AAPL let’s get that $170 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:55:37 </td>
   <td style="text-align:left;"> $AAPL 200 smacked on the 5. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:55:17 </td>
   <td style="text-align:left;"> $AAPL 1/3 wish came true half buy Apple $173.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:55:11 </td>
   <td style="text-align:left;"> $AAPL f you apple :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:55:09 </td>
   <td style="text-align:left;"> $AMZN $FB $AAPL $SPY hedges I&amp;#39;m. Today is either BTFD or Bye 👋 puts and calls are up. I&amp;#39;ve gone wild lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:55:07 </td>
   <td style="text-align:left;"> $AAPL I like Blonde from cnbc getting her smile taking away on red days… hahahah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:55:05 </td>
   <td style="text-align:left;"> $SPY 

Holy shit $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:54:47 </td>
   <td style="text-align:left;"> $SPY Took you long enough $aapl. Now let&amp;#39;s see that nice sell algo in there like it&amp;#39;s in $msft  =) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:53:23 </td>
   <td style="text-align:left;"> Facebook has always been able to pivot/adapt to trends or changes in the market to sustain its core business.. why should this time be any different?  $FB $GOOGL $AAPL $U https://youtu.be/AEKrQICFFJY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:53:12 </td>
   <td style="text-align:left;"> $AAPL gave the big boys all day to get out then dumped it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:52:40 </td>
   <td style="text-align:left;"> $AAPL sold 1/3 of my puts and will hold the rest. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:52:15 </td>
   <td style="text-align:left;"> $AAPL DANG! if FB, TSLA, DOCU can drop by 25%, why can&amp;#39;t this shit drop?! hahaha.. 10% drop of this will make shit ton of money! dont tell this shit aint affected by inflation. no money, no iphone! hahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-04 04:52:04 </td>
   <td style="text-align:left;"> $AAPL the big winner. Facebook and Google stocks have diverged, and the reason is Apple

https://www.cnbc.com/2022/02/03/facebook-and-google-stocks-have-diverged-and-the-reason-is-apple.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 10:37:31 </td>
   <td style="text-align:left;"> $TSLA  I told you today,  this stock trading almost green over with nasdaq 3% negative was a bullish sign for what&amp;#39;s coming tomorrow I hope u bought some call </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 10:36:37 </td>
   <td style="text-align:left;"> $F chip shortage is easing for $GM, but not for Ford?   Even $TSLA delaying new models due to chip shortage.   things that make you go hm.... latexf91e361009e78289a0c53833d5256e4eF 1.104m (53% call/47% put)
$SNAP 995k (57% call/43% put)

Lynk in bayo for option trading ideas and alerts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 10:27:41 </td>
   <td style="text-align:left;"> $TSLA $GOOGL $QQQ $F now I&amp;#39;m used to losing money left and right in the mkt but good luck to bears and &amp;quot;bulls with big balls&amp;quot; amen 🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 10:27:03 </td>
   <td style="text-align:left;"> $TSLA stock is going to skyrocket tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 10:25:39 </td>
   <td style="text-align:left;"> Biden-appointed Commerce Sec. calls on Tesla for chip help: &amp;#39;Too important to have...feelings hurt&amp;#39;

$TSLA https://www.teslarati.com/tesla-shunned-biden-us-government-chip-shortage-consulted/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 10:23:11 </td>
   <td style="text-align:left;"> $TSLA So been thinking of moves on the macroeconomic level and feel the bears have a point this could impact the market if we get a bad inflation read again and a hawkish Fed. However, if you stay cash heavy over the next 6 to 8 months what will you be missing at $TSLA? Not sure I want to miss those moments including: Austin Opening, Berlin Opening, Biden EV Credit, 4680 Launch, Next Factory announcement and more... could this be enough to offset the macrotrend or does the saying &amp;quot;Don&amp;#39;t fight the Fed&amp;quot; beat Tesla in the first half of 2022. 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 10:22:22 </td>
   <td style="text-align:left;"> $TSLA bears after selloff tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 10:22:06 </td>
   <td style="text-align:left;"> $TSLA with this much negativity you know this is going go rocket tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 10:21:10 </td>
   <td style="text-align:left;"> $TSLA a wen moon? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 10:20:27 </td>
   <td style="text-align:left;"> $TSLA bulls tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 10:20:16 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 10:20:07 </td>
   <td style="text-align:left;"> $TSLA Elra and NFT merger </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 10:19:51 </td>
   <td style="text-align:left;"> $TSLA Bears looking at their (PUTS) in the morning. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 10:19:03 </td>
   <td style="text-align:left;"> $AMZN you Know Right ... they made up Number from selling  $RIVN at $100  poor $tsla bulls  
$qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 10:16:47 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 10:16:20 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

tesla fanboys after fomo’ing in and buying elon’s bags... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 10:14:10 </td>
   <td style="text-align:left;"> $TSLA to the moon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 10:10:54 </td>
   <td style="text-align:left;"> $AMZN $FB $TSLA $F $NFLX 

www.dovewoodcapital.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 10:10:31 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

“To ThE MoOoOoOoN!!!!” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 10:06:47 </td>
   <td style="text-align:left;"> $SOFI Hong Kong up big time and US futures are pretty green. Let&amp;#39;s see if job numbers kill the market tomorrow. $LCID $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 10:06:22 </td>
   <td style="text-align:left;"> $ANY welcome to the new $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 10:05:07 </td>
   <td style="text-align:left;"> $TSLA DAMNNN DANIELLL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 10:04:50 </td>
   <td style="text-align:left;"> $TSLA  I told you today,  this stock trading almost green over with nasdaq 3% negative was a bullish sign for what&amp;#39;s coming tomorrow I hope u bought some call </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 10:03:44 </td>
   <td style="text-align:left;"> $TSLA did Pepsi get its Semis from Tesla last month? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:59:21 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:58:38 </td>
   <td style="text-align:left;"> $TSLA $amzn $spy puts be like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:57:02 </td>
   <td style="text-align:left;"> $TSLA 
The future addition of software revenues will push their margins to 75%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:54:46 </td>
   <td style="text-align:left;"> $TSLA Green to red move:  +3.46% to -1.83%  
 https://www.sleekoptions.com/sleekscan.aspx?sub1=dscan&amp;amp;type=greentoredDaily </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:52:02 </td>
   <td style="text-align:left;"> $TSLA $1250 2/28/&amp;#39;22 
$4750 12/31/&amp;#39;25 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:47:59 </td>
   <td style="text-align:left;"> $TSLA 2/11 $1000c on my radar… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:45:26 </td>
   <td style="text-align:left;"> $AMZN $TSLA $AAPL $SPY $QQQ  
 NASDQ and S&amp;amp;P futures:  
Unable to break supply line even with AMZN earnings. 
Bearish divergence about to be confirmed on RSI and MACD for 15 mins. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:44:32 </td>
   <td style="text-align:left;"> $TSLA anyone have their average change? Mine went up after market closed. 😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:42:37 </td>
   <td style="text-align:left;"> It’s looking to me like a gap n crap. This was the last big earnings. There’s no more to save the market when it’s in decline. There’s just the tightening fed now. $spy $qqq $amzn $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:39:18 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

That’s some cute futes, it’d be a shame if I use this shinny infinity gauntlet to snap them away... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:37:55 </td>
   <td style="text-align:left;"> $TSLA https://www.businessinsider.com/tesla-karaoke-microphones-teslamic-sold-out-hour-launch-2022-2?international=true&amp;amp;r=US&amp;amp;IR=T </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:36:25 </td>
   <td style="text-align:left;"> $TSLA $NVDA Time to turn negative Nelly off and by the dips </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:34:15 </td>
   <td style="text-align:left;"> Top UOA of the day 🔮
$FB two orders totaling $26.8 Million bought the 6/17 220 calls 
$GOOGL buyer $10 Million worth of the 2/18 2700 calls 
$AMD buyer $1.9 Million worth of the 4/14 115 calls 
$TSLA buyer $3.8 Million worth of the 6/17 900 calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:32:24 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-03 Options Analysis Video: 
https://www.youtube.com/watch?v=xGiwyt5o5Vg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:32:00 </td>
   <td style="text-align:left;"> $TSLA 920 at pre market tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:31:09 </td>
   <td style="text-align:left;"> $TSLA 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:30:04 </td>
   <td style="text-align:left;"> $TSLA I cant wait to buy puts on this garbage </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:29:35 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AMZN 

FRAUD ON EVERY LEVEL... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:28:48 </td>
   <td style="text-align:left;"> $TSLA grabbed a 3/18 $1050C for $25 today…what’s gonna happen 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:28:29 </td>
   <td style="text-align:left;"> $TSLA here comes the dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:26:19 </td>
   <td style="text-align:left;"> $TSLA https://eletric-vehicles.com/2022/02/03/morgan-stanley-says-tesla-will-surpass-gm-plus-ford-combined-revenue-by-2027/?fbclid=IwAR1vYVLaBLHtkPg2Csv014opGAwCLEcKE6QaLScqiXt9nTVvxx9ZieqhAEs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:25:10 </td>
   <td style="text-align:left;"> $TSLA wen moon?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:24:11 </td>
   <td style="text-align:left;"> $TSLA still trading at 135 x earnings …. The market is self correcting. Is this next??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:22:13 </td>
   <td style="text-align:left;"> $TSLA 

$F owe almost half of their 2021 GAAP Net Income to their Rivian investment.

Excluding the Rivian special item, $F GAAP Net Income per wholesale delivery was $2,470 in 2021.

Tesla 2021 GAAP Net Income per delivery was $5,892. 

Credit to @Icannot_Enough 
🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:20:32 </td>
   <td style="text-align:left;"> $SPY $AAPL $FB $TSLA For Harambe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:20:30 </td>
   <td style="text-align:left;"> $TSLA futes rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:10:27 </td>
   <td style="text-align:left;"> $SPY  
 
$TSLA  3rd retest of support. on huge move watch..  
 that $1000 Call Sweeper for Feb 11 active . 11k volume today.  
50k volume on $950 that expire feb  4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:09:18 </td>
   <td style="text-align:left;"> $TSLA a lot of wild moves will happen tomorrow, could see 1000 tomorrow, crazy how unpredictable this market is </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:08:35 </td>
   <td style="text-align:left;"> $TSLA Cathie can’t stop selling 🐻🐻🐻🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:07:03 </td>
   <td style="text-align:left;"> $TSLA futs already beginning to dump. Nothing like a good after hours bull trap. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:03:56 </td>
   <td style="text-align:left;"> $TSLA stock analysis based on today&amp;#39;s closing price 

https://youtu.be/rrrs2bDuhso </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:00:45 </td>
   <td style="text-align:left;"> $NFLX $TSLA  tinyurl.com/2p958rre </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:00:31 </td>
   <td style="text-align:left;"> $TSLA SEC Whistleblower </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 09:00:10 </td>
   <td style="text-align:left;"> $TSLA Volatility is King!! Simulated Weekly $895.0 CALLS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:59:17 </td>
   <td style="text-align:left;"> $TSLA we should see $1000 tomorrow, great to see market recovering!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:58:55 </td>
   <td style="text-align:left;"> $TSLA Not looking good 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:58:21 </td>
   <td style="text-align:left;"> $TSLA Shorts panicking. Bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:58:04 </td>
   <td style="text-align:left;"> $TSLA Let us see $915 soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:57:35 </td>
   <td style="text-align:left;"> $TSLA $AMZN $SNAP  bullish to moon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:57:29 </td>
   <td style="text-align:left;"> $TSLA This is a bump up in a down trend. AMZN did nothing other than pump up the indexes tonight due to its rise.  pump n dump Friday..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:57:21 </td>
   <td style="text-align:left;"> $TSLA 

Just FYI !

Today Zuckerberg lost nearly ~30b the biggest individual loss in a single day in history ! $FB 
(That’s excessive) 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:57:02 </td>
   <td style="text-align:left;"> $TSLA Squeeze the shorts. Let us see $915 tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:56:29 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:56:18 </td>
   <td style="text-align:left;"> $TSLA Slap the ask and let us close at $915 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:55:57 </td>
   <td style="text-align:left;"> $TSLA Squeeze baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:55:38 </td>
   <td style="text-align:left;"> $TSLA Closing strong . Let’s us see $1000 by tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:55:21 </td>
   <td style="text-align:left;"> $TSLA I am bullish but wtf does $AMZN &amp;amp; $FB  have to do with $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:55:06 </td>
   <td style="text-align:left;"> $TSLA Squeeze all bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:54:51 </td>
   <td style="text-align:left;"> $TSLA Squeeze All shorts. Let us close the AH at $915 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:54:47 </td>
   <td style="text-align:left;"> $TSLA  
 
TSLA Interesting movement in the market today and after hours - seeing a significant increase in number of impressions leading up to close. Twitter is one of the best &amp;quot;live&amp;quot; sources of investment information  
  
We built the Social Dashboard to track it in real-time - you can use it to stay ahead of the trends and movements.  We want to give individual investors the chance to beat the market with tools and information usually reserved for &amp;quot;hedgies&amp;quot;  
  
Check it out and let me know if you have any questions.  
  
utradea.com/pricing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:53:19 </td>
   <td style="text-align:left;"> $TSLA lmao why is this up AH 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:52:13 </td>
   <td style="text-align:left;"> $TSLA $AMZN $SNAP squeeze all shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:51:42 </td>
   <td style="text-align:left;"> $TSLA Lot of shorts are panicking. Bullish to $930. Let’s squeeze them </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:51:12 </td>
   <td style="text-align:left;"> $TSLA if Elon joins truth social $DWAC I&amp;#39;m buying a cyber truck and some shares </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:50:53 </td>
   <td style="text-align:left;"> $TSLA are teslemmings starting to wake up? 
Seen on a Discord of bulls: &amp;quot;the only excuse I can think of is that they are in the beginning of the S curve. If that’s the case, then when can we see a take-off? It’d better be soon, after seeing AutoX and Cruise performance&amp;quot; #FSDBeta </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:50:51 </td>
   <td style="text-align:left;"> $TSLA will be down tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:49:47 </td>
   <td style="text-align:left;"> $AMZN $TSLA $FB $AAPL 👣🐇➿⚪ https://markets.businessinsider.com/news/stocks/this-marijuana-penny-stock-had-a-better-1-year-return-than-tesla-apple-facebook-and-amazon-1030991696 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:49:33 </td>
   <td style="text-align:left;"> $TSLA people say Elon is like Tony Stark, but he’s probably more like Dr. Evil… trying to take over the Earth in plain sight 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:49:23 </td>
   <td style="text-align:left;"> $TSLA  beware when insiders selling. I have learnt hard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:47:35 </td>
   <td style="text-align:left;"> $TSLA Guys please sell before it’s too late. Massive gamma dump in bound. The bears love the bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:47:34 </td>
   <td style="text-align:left;"> $TSLA beware when insiders selling. I  learnt hard way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:46:31 </td>
   <td style="text-align:left;"> $TSLA overvalued. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:46:00 </td>
   <td style="text-align:left;"> $TSLA is expected to show a strong growth in EPS. In the coming 5 years, the EPS will grow by 33.36% yearly. https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:45:51 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMZN $TSLA $ARKK 
  
As a GenX I hope Millennial keep bidding up my stocks to all time high prices and valuations like the Boomers did with Trillions of FED liquidity for their retirement.  
   
Please don&amp;#39;t drop the baton Millennial! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:44:16 </td>
   <td style="text-align:left;"> $TSLA odtes milly milly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:40:20 </td>
   <td style="text-align:left;"> $TSLA 📜 SEC Form 4 filed by Tesla Inc.

https://quantisnow.com/insight/2353999?s=s

45 seconds delayed. Real-time feed at 🚆 https://quantisnow.com/feed 🚆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:40:09 </td>
   <td style="text-align:left;"> $TSLA [15s. delayed] filed SEC form 4: Director DENHOLM ROBYN M: 
Disposed 25,000 of Common Stock at average price $923.57 and Converted s https://s.flashalert.me/r1ji7 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:39:34 </td>
   <td style="text-align:left;"> $TSLA dump continues tomorrow at opening bell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:39:34 </td>
   <td style="text-align:left;"> Insider Robyn M Denholm reports selling 25,000 shares of $TSLA for a total cost of $23,089,129.20 https://fintel.io/n/us/tsla/denholm-robyn-m?utm_source=stocktwits.com&amp;amp;utm_medium=Referral&amp;amp;utm_campaign=insider </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:39:18 </td>
   <td style="text-align:left;"> $TSLA $21,779,589.70 of shares sold by Denholm Robyn M (Director), reported in a new form 4 filed with the SEC  

https://newsfilter.io/a/e752e679c0d668e3165a31466bfbe200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:37:48 </td>
   <td style="text-align:left;"> $NVDA $TSLA WE BANK TOGETHER TOMORROW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:37:39 </td>
   <td style="text-align:left;"> $TSLA 1050 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:37:38 </td>
   <td style="text-align:left;"> $TSLA This is going parabolic soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:36:35 </td>
   <td style="text-align:left;"> $TSLA robot shovel my snow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:36:08 </td>
   <td style="text-align:left;"> $TSLA We need all the Meet Kevin sheep who panic sold to buy back in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:34:37 </td>
   <td style="text-align:left;"> ➜ US Stocks Watchlist - 3 February 2022  
 
There were 28 stocks for the US stocks watchlist today. Here&amp;#39;s a small sample from the list:  
 
$TSLA, $JOAN, $DSKE, $JNPR + 24 more...  
 
#stocks #trading #investing #money  
 
https://www.stageanalysis.net/blog/97811/us-stocks-watchlist-3-february-2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:34:23 </td>
   <td style="text-align:left;"> $TSLA Elon should use his robot to track down and destroys spam callers. 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:34:18 </td>
   <td style="text-align:left;"> $TSLA 

930-940  tomorrow then a controlled descent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:32:31 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-03 Technical Analysis Video: 
https://www.youtube.com/watch?v=BUOWWlZcM0A </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:31:55 </td>
   <td style="text-align:left;"> $SPY $TSLA $FB $SNAP 

Fortunes won and lost in minutes. 

This market is OFFICIALLY BROKEN. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:30:51 </td>
   <td style="text-align:left;"> $TSLA This is going parabolic soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:30:18 </td>
   <td style="text-align:left;"> $TSLA 4hr view from 1/09 weekend update. Can see another blue box area where buyers should be waiting to appear again #elliottwave #tading #Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:30:05 </td>
   <td style="text-align:left;"> $TSLA Tesla Blue Box Area Provided The Minimum Reaction Higher. How we see the stock last November #elliottwave #tading #tesla #ondaselliott </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:27:50 </td>
   <td style="text-align:left;"> $TSLA 

Teslas shares could have surged on earnings like Amazon today. 

Just that analysts were not ready to figure out how much money Tesla was going to make selling/leAsing humanoids. 

Sounds logical—- </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:26:26 </td>
   <td style="text-align:left;"> $TSLA 1500 in 6 months or less. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:26:04 </td>
   <td style="text-align:left;"> $TSLA NASDAQ will soar tomorrow due to Amazon earnings. QQQ will rocket. Tesla will follow suit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:24:38 </td>
   <td style="text-align:left;"> $ORTX $GME $amc $tsla like Elon musk said *medicine is the next key discovery* let squeeze orchid tomorrow. Let&amp;#39;s go boys. 200% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:24:04 </td>
   <td style="text-align:left;"> $TSLA giga texas opening when? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:23:58 </td>
   <td style="text-align:left;"> $TSLA will be shorting the faux bounce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:23:23 </td>
   <td style="text-align:left;"> $TSLA   are these 817,143 are additional recalls (we are aware they recall 54000 ?  so total recalls  822,543? OMG......  
 
https://www.cbsnews.com/news/tesla-recall-2022-self-driving-software-rolling-stop-54000-vehicles/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:21:18 </td>
   <td style="text-align:left;"> $SNAP Next $GOOGL and $TSLA 

innovation in social media is just starting. 

People who sold $FB today will buy snap tomorrow morning.  

This is could be $500 in 2025 target 🎯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:20:41 </td>
   <td style="text-align:left;"> Watchlist 📝👀

$TSLA $AAPL $BA $UPS $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:19:40 </td>
   <td style="text-align:left;"> $TSLA Friday is generally for the theta gang, burning the remaining options premiums </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:19:39 </td>
   <td style="text-align:left;"> $TSLA Dark Pool getting ready for tomorrow.  No real buying going on in after hours. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:19:05 </td>
   <td style="text-align:left;"> latex3981ab4d6a756c3b524b1ab647d26eacGM 💩 
$TSLA 👑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:18:46 </td>
   <td style="text-align:left;"> $TSLA idk. I just sense flat day tomorrow. Friday option expiry. We’ll see though. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:17:47 </td>
   <td style="text-align:left;"> $TSLA  
over 940 965-980 possible 
under 875 835-850 possible 
chart:https://www.tradingview.com/chart/TSLA/J1DAR31j-TSLA-trading-it-2-4/ 
#intradayoptionstrading #stockmarket 
NO bias, plan for red or green day. chop/ranging = hand sitting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:16:31 </td>
   <td style="text-align:left;"> $TSLA  you guys are missing the point the amount of bear in USA will never never never cover the amount of bull worldwide! Everyone want a piece of the best car tech in the world... Kid nowadays feel Mercedes bmw audi Ferrari are all obsolete they want mommy to buy tesla to be the Cool. On the school! Wake up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:16:03 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMZN $TSLA $ARKK  
 
JPOW and his Boomers STILL running the show and printing themselves Trillions right up into retirement! 
 
Wen Millennials? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:14:51 </td>
   <td style="text-align:left;"> $TSLA https://www.youtube.com/watch?v=hZE1lxhq26A Good vid discussing how Tesla&amp;#39;s earnings call hints at bullish signs for other companies entering the FSD space, like $FUV...Tesla is gonna make so much bank licensing their FSD tech.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:12:56 </td>
   <td style="text-align:left;"> $SEV Excellent informative company meeting today. Thank you Sono Motors Team for providing an great view of the future of the Sion and Solar EV. Tomorrow is going to be a big up day for EV specifically $SEV $ZEV $NIO $TSLA $RIDE I endorse loading up pre-market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:11:09 </td>
   <td style="text-align:left;"> $TSLA Starlink: Not an ideal internet solution
 https://www.theverge.com/22435030/starlink-satellite-internet-spacex-review </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:10:32 </td>
   <td style="text-align:left;"> $TSLA Cathie is shorted every breath she takes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:10:27 </td>
   <td style="text-align:left;"> $TSLA this will dump tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:09:59 </td>
   <td style="text-align:left;"> $TSLA Good explanation https://youtu.be/9ZF6fYL-3JM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:08:08 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X i remember when people shorted $TSLA too during its inextricable March higher. Those guy got destroyed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:07:40 </td>
   <td style="text-align:left;"> $AMZN $GOOGL $NVDA $TSLA 

Don’t ever let them steal ur shares!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:07:35 </td>
   <td style="text-align:left;"> Turns out $F is much worse at dealing w the supply chain problems than $TSLA which somewhat surprises me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:06:42 </td>
   <td style="text-align:left;"> $TSLA Dont have the big money for Tesla stocks. So bought some Nikola. Itss the Tesla stock for poor people )))) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:06:35 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #5 ticker with sweep activity where institutions are trading options urgently with 21.6K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:06:25 </td>
   <td style="text-align:left;"> $AMC Check this Diagio guy, he has been sending messages every 10 minutes during 24 hours (night in Europe and Night in America)
 Probably he&amp;#39;s on Asia, maybe India, China or Russia.
 How we can find his ip ???? 
$GME $TSLA . 
Bot finder </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:06:06 </td>
   <td style="text-align:left;"> $TSLA    Queen Cathie would like a Big green hammer! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:05:53 </td>
   <td style="text-align:left;"> $TSLA https://www.cnn.com/2022/02/03/cars/tesla-racism-lawsuit/index.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:03:44 </td>
   <td style="text-align:left;"> $TSLA     HERE&amp;#39;S SOMETHING I WANT BEARS TO THINK ABOUT EVERY FRIDAY FROM NOW ON: 
 
What stops Elon from putting out a Tweet with news about gigaTexas opening?     And there you&amp;#39;ll be, fully leveraged against Tesla, as the entire world prepares to pile in at the open on Monday.  
 
Enjoy, bitches.  Because the &amp;quot;next big leg up&amp;quot; is coming your way soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:03:43 </td>
   <td style="text-align:left;"> $TSLA im not celebrating yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:02:39 </td>
   <td style="text-align:left;"> $TSLA Yea y’all can follow me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:02:33 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-03 Trade Analysis Video: 
https://www.youtube.com/watch?v=Xy8RZCtuur0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:02:29 </td>
   <td style="text-align:left;"> $TSLA Thoughts on Toyota’s upcoming earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:01:28 </td>
   <td style="text-align:left;"> $TSLA https://fortune.com/2022/02/02/tsla-stock-valuation-predictions-2022/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:00:50 </td>
   <td style="text-align:left;"> $TSLA https://www.yahoo.com/autos/tesla-recalls-over-817-000-131300594.html  Musk, you sloth looking dog…what’s with all the problems </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:00:35 </td>
   <td style="text-align:left;"> How Much Money Did Mark Zuckerberg Lose ? He&amp;#39;s No Longer A Top 10 Billionaire  $FB $TSLA $AMZN 

https://newsfilter.io/a/37fffbddcb7c8b194e554544919ab54c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:00:27 </td>
   <td style="text-align:left;"> $TSLA  $LCID big green dicks tomorrow!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 08:00:11 </td>
   <td style="text-align:left;"> $TSLA    DEAR BEARS:  Elon can post a Tweet about the gigafactories without notice and send TSLA stock soaring.   
 
That news could well be a squeeze like you never imagined.  
 
Because TSLA stock price can get an Over-the-Air update from Elon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:58:18 </td>
   <td style="text-align:left;"> $amzn $tsla $msft $GOOG  new option traders don’t listen to everybody on Stocktwits or Twitter , don’t fall in love with stocks get your money and run. Don’t pay for subscriptions at least ask for free trial . Don’t be cocky karmas a bitch .. good luck on your journey </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:57:03 </td>
   <td style="text-align:left;"> $TSLA There it is. FB miss and down we go huge. Amazon beat and back up we go. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:55:44 </td>
   <td style="text-align:left;"> $TSLA I need a big green day here so it&amp;#39;s going to happen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:54:26 </td>
   <td style="text-align:left;"> How Much Money Did Mark Zuckerberg Lose Today? He&amp;#39;s No Longer A Top 10 Billionaire $FB $AMZN $TSLA https://benzinga.com/z/25412739#.YfxrGbFJsLc.twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:52:53 </td>
   <td style="text-align:left;"> $TSLA long over/short under 890 once again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:52:44 </td>
   <td style="text-align:left;"> $TSLA Rose and held up nicely today despite the negative sentiment of the overall market.  AH speaks for itself.  To new ATH soon 😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:52:11 </td>
   <td style="text-align:left;"> $F they really ditching this and pumping $tsla? what a joke, F truck still the most bought up truck !!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:51:24 </td>
   <td style="text-align:left;"> $TSLA pump this up to 950 please. I need to load more puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:51:14 </td>
   <td style="text-align:left;"> It’s sadly apparent that Biden still thinks this is the roaring 20s buy only mentioning $F and $GM and refusing to acknowledge $TSLA as the LEADER in the AMERICAN EV space. Disgraceful </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:50:43 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $AMZN $TSLA  
 
A few things Gen X would like Millennials to remember as they continue to buy stocks and take the baton from retiring boomers. 
 
1) Stock valuations don&amp;#39;t matter....buy stocks! 
2) Fiscal debt doesn&amp;#39;t matter....buy stocks! 
3) Fed balance sheet doesn&amp;#39;t matter...buy stocks! 
4) ATH housing prices don&amp;#39;t matter....buy stocks! 
5) Student loans are good...buy stocks! 
 
Summary....&amp;quot;buy stocks!&amp;quot; 
 
You got this! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:50:39 </td>
   <td style="text-align:left;"> $SOFI Are we back to normal? Southwest to resume alcohol sales on flights starting February 16 per CNBC  $LUV $LCID $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:45:57 </td>
   <td style="text-align:left;"> $TSLA bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:45:37 </td>
   <td style="text-align:left;"> $TSLA why this is big news worldwide? just over air software update 
just like windows update. 
https://www.reuters.com/business/autos-transportation/tesla-recalls-817000-vehicles-us-over-seat-belt-reminder-alert-2022-02-03/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:45:08 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:43:22 </td>
   <td style="text-align:left;"> $TSLA     
ATTENTION BEARS 
SAVE YOURSELVES 
PROCEED NOW TO THE NEAREST EXIT IN AN ORDERLY FASHION 
MAINTAIN YOUR SHORT POSITIONS AT YOUR OWN RISK 
 
Elon can post a single Tweet about GigaTexas or the 4680 cell and ruin your lives at any time.  We bulls can&amp;#39;t wait until he does. 
 
This is the only stock in the world with Over The Air Updates.   
 
Stay short TSLA at your own very grave risk. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:42:28 </td>
   <td style="text-align:left;"> $TSLA just Alzheimer. 
https://www.youtube.com/watch?v=wSP-eyrpnyg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:42:10 </td>
   <td style="text-align:left;"> $AMZN $TSLA Massive pay day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:42:07 </td>
   <td style="text-align:left;"> $TSLA 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:41:17 </td>
   <td style="text-align:left;"> $TSLA where is Gordon these days. Haven’t seen him on cnbc lately. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:39:55 </td>
   <td style="text-align:left;"> $TSLA Let&amp;#39;s Tsla shine next week 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:38:06 </td>
   <td style="text-align:left;"> Instead of going to the circus with the family,decided we&amp;#39;ll watch the market. 

We saved a lot of money and it was much more $TSLA $AMZN $GOOGL $SNAP $F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:35:08 </td>
   <td style="text-align:left;"> $TSLA https://teslanorth.com/2022/02/03/tesla-applied-for-cathode-building-permit-at-giga-texas-confirms-city/ 🏎🚀🤖🔋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:35:02 </td>
   <td style="text-align:left;"> TSLA Earnings Review: How Did Tesla Perform In Q4 of 2021? 
 
Tesla (NASDAQ: $TSLA) reported its fourth-quarter and full-year 2021 earnings last week. The California-based electric automaker beat analysts&amp;#39;... 
 
Read more: https://www.finscreener.org/blog/tsla-earnings-review-how-did-tesla-perform-in-q4-of-2021-530b </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:33:10 </td>
   <td style="text-align:left;"> $TSLA TSLA $1100 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:30:51 </td>
   <td style="text-align:left;"> $TSLA Squeeze the short sellers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:29:29 </td>
   <td style="text-align:left;"> MOVES HAPPENING NOW (6:29pm)

⦿ $TSLA is down 0.1% in the last 5 mins. 

⦿ There are 9 stocks that are up more than 3% in the last 5 mins. 

⦿ The top gainer is up 8.9% in the last 5 mins. 

 See the stocks that are moving the most right now via link in bio (wallstreetodds .com). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:28:03 </td>
   <td style="text-align:left;"> $TSLA Shorts! 
 
Up +14 points 905.06 Marketwatch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:26:16 </td>
   <td style="text-align:left;"> $TSLA Biden is messing up with the wrong person…. Elon is mad now.  Watch tomorrow he is going to announce some craze news.  Be prepared guys.. $1000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:25:06 </td>
   <td style="text-align:left;"> $FTNT $INMD $TSLA $LULU These four stocks were pumped up from Oct to Nov, and then took a massive drop. The crash actually happened already, and I sold before it did. Now, my next prediction is that Apple will pull an $NVDA in 2022. Apple will likely surge past $245 this year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:24:47 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:23:22 </td>
   <td style="text-align:left;"> $TSLA today we opened at $879 and at one point went to $937 on a day the entire market was doing.. tomorrow if we open at $920, wouldn’t be slightly touch $1000.  Especially on a green day.  Let’s go bulls.  Elon will never disappoint u, but we got to stick together.  Let’s gooooo elooonnnnnn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:22:10 </td>
   <td style="text-align:left;"> $TSLA Let us see $915 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:21:37 </td>
   <td style="text-align:left;"> $TSLA  I still don’t trust this market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:21:15 </td>
   <td style="text-align:left;"> $AMC $GME $BBIG $BB $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:20:57 </td>
   <td style="text-align:left;"> $TSLA 

It’s just sickening to hear these YouTube Experts and others  about how mega caps growth stocks when they miss Q earning gets cut by 20-26% by the “MARKET” Allegedly !! 

Like I said in my previous posts and I’m going to repeat it again :

It’s NOT the market that puts out such abusive discount of BILLIONS it’s the function of front running by HFs &amp;amp; Short Sellers abusively shorting (naked) the stock to substantiate their option puts gains !! 

My math stands at 2:1 so $FB 26% ~16%  Short selling ~8% Funds and investors reducing their holding ETF or Stocks ! 

Now that’s Abusive and criminal per SEC chapter of manipulation and it’s more profound this yr especially during Biden Administration that’s allowing such massive actions - no audit no Enforcement.. 

Facts only 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:20:55 </td>
   <td style="text-align:left;"> $DOGE.X $BTC.X crude price about to drive up. The real money maker. Spread over everything! Gas still drives the economy $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:19:19 </td>
   <td style="text-align:left;"> $TSLA Volatility is King!! Simulated Weekly $895.0 CALLS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:17:56 </td>
   <td style="text-align:left;"> $TSLA $NVDA Snapchat up 54% AH because why the fuck not lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:17:44 </td>
   <td style="text-align:left;"> $TSLA plans to build cathode building at Texas Gigafactory. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:17:35 </td>
   <td style="text-align:left;"> $ATER $SPY $TSLA $QQQ $AMZN see why $ATER is a sympathy play on AMZN earnings. 💥💥💥💥💣💣💣💣💣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:16:23 </td>
   <td style="text-align:left;"> $KSCP shoutout to Elon $TSLA $PLTR and Trump $DWAC https://youtu.be/03PF5sHhPHQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:14:43 </td>
   <td style="text-align:left;"> $TSLA ....Giga 3.....Giga 4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:14:32 </td>
   <td style="text-align:left;"> $NIO come on powells rewards the EV sector $xpev $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:12:07 </td>
   <td style="text-align:left;"> Have my faith on $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:11:58 </td>
   <td style="text-align:left;"> $TSLA Big up day tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:11:40 </td>
   <td style="text-align:left;"> $TSLA Video clip  https://twitter.com/jacobavolio/status/1489322347509256192?s=21 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:11:28 </td>
   <td style="text-align:left;"> $TSLA beware here tomorro, Amazon ER results are shady, but algos are unable to figure it out. This could lead to huge pump of the whole Nasdaq before mkt opens and yuge dump right after that, because humans are not so stupid. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:09:50 </td>
   <td style="text-align:left;"> $F Supply chain issues are hurting this company but it is a short term problem. $F and $GM are cheap value stocks here and they are a great play for EV. $TSLA is trading at a crazy valuation and eventually GM and Ford will catch up to Tesla on EV </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:09:47 </td>
   <td style="text-align:left;"> $FB did double $TSLA revenue and lost $200B off the cap in a day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:09:08 </td>
   <td style="text-align:left;"> $TSLA any chance for 940 calls tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:08:03 </td>
   <td style="text-align:left;"> $TSLA https://www.wallstreetsnaps.com/collections/snaps/products/tesla-ticker-symbol-charging-snapback </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:05:26 </td>
   <td style="text-align:left;"> $TSLA Trapped shorts better cover . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:04:02 </td>
   <td style="text-align:left;"> $TSLA If Joe Byron says Testa we&amp;#39;re good! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:04:01 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/1DijsK4ki2g </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:04:00 </td>
   <td style="text-align:left;"> $TSLA Too many shorts are trapped before closing . Bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:03:35 </td>
   <td style="text-align:left;"> $TSLA  Wow ! Jim Cramer is a complete fool . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:03:12 </td>
   <td style="text-align:left;"> $TSLA before investing here, go and try a tesla.
You will understand after you try a plaid s. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:03:12 </td>
   <td style="text-align:left;"> $TSLA Half the revenue of $F and 10X the market cap.

As an aside, do any of you use Altair or Commodore PCs? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:02:32 </td>
   <td style="text-align:left;"> $TSLA Tesla plans to build cathode building at Texas Gigafactory https://www.reuters.com/business/autos-transportation/tesla-plans-build-cathode-building-texas-gigafactory-2022-02-03/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 07:02:05 </td>
   <td style="text-align:left;"> $TSLA what&amp;#39;s this I hear about Tesla and subscription based braking? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:59:09 </td>
   <td style="text-align:left;"> $TSLA Leg up . Bullish  $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:57:37 </td>
   <td style="text-align:left;"> $TSLA the bubble is about to pop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:57:11 </td>
   <td style="text-align:left;"> $TSLA Notice how the price is trapped below where Elon dumped his shares. That’s the market’s way of punishing the shareholders for Elon’s greed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:55:12 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $AMZN $FB 

My thoughts on the mkt action today/AHrs .... 

Yesterday I had sent out an email to members that I was going short at the 458 level on the SPY as we hit the 50 day EMA (SEE BELOW) It was the first short alert I have sent out since we had our capitulation Monday. Today I sent an email out when we were just below 450 suggesting the possibility that AMZN and the jobs data could possibly put a short term halt to the mkt selling. 

I believe we are heading a bit lower. The mistake a lot of traders/investors are making are believing things materialize overnight. Plenty of headfakes happen in between - like FB and AMZN which caught an enormous amount of people offsides. Like the late day surge yesterday into the 458 level. Like the capitulation last Monday. Both bull and bear traps will be set. 

I  teach technical analysis in order to pick entry/exit points for stks and indexes. If interested in joining, feel free to email me at

 jessielivermore1929@gmail.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:54:00 </td>
   <td style="text-align:left;"> $TSLA  someone or whomever attempted to initiate the itm weekly call buying manipulation today, which explained the surge in the share price during the morning.  I believe the SEC actually followed through on the tip and the manipulation came to a screeching halt by 11:45 a.m.  Otherwise, this stock would have been up 3-4% on no news when the entire market was literally melting down.  That is not market effeciency and no small group of individuals should profit from manipulating a stock.  This is precisely the reason the Fed needs to tighten the money supply ASAP.  Once it becomes too expensive to borrow funds, crooks are less likely to run the risk in playing these games. As the money supply tightens, this stock will continue to trend downward.   If you observe any suspicious trading or suspect securities fraud, file a complaint with the SEC the same day.    https://www.sec.gov/complaint/select.shtml </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:53:52 </td>
   <td style="text-align:left;"> $TSLA big-ass miss, like i said monday… chip &amp;amp; part shortages.  Dealerships are vacant </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:52:35 </td>
   <td style="text-align:left;"> $TSLA This is like RCA stock before the Great Depression. Everyone was thinking it’s going to rule the world. Where is RCA today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:52:32 </td>
   <td style="text-align:left;"> $TSLA Next leg up this year 1500-1600$, fuck bears😄😄😄🚀🚀🚀✈️✈️✈️📈📈💰💰💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:52:05 </td>
   <td style="text-align:left;"> $TSLA New ticker: $POS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:51:12 </td>
   <td style="text-align:left;"> $TSLA hate this stock always get trap at a higher price. Hard to make money for me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:51:08 </td>
   <td style="text-align:left;"> $TSLA this is pathetic.   This should be up to $980 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:50:25 </td>
   <td style="text-align:left;"> $F lmao .26 EPS and people compare them to $TSLA …hilarious! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:49:57 </td>
   <td style="text-align:left;"> $TSLA https://www.reuters.com/business/autos-transportation/tesla-plans-build-cathode-building-texas-gigafactory-2022-02-03/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:49:33 </td>
   <td style="text-align:left;"> $TSLA Some idiotic billboard pumps the stock. Biden responds with I’m a union guy, shut up already. 
I’m going to lmao when Musk get Biden to respond with “ Tesla isn’t a union company. I stand behind workers.” Backfire. 
May you get what you ask for Musk. Lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:49:21 </td>
   <td style="text-align:left;"> $TSLA time for a full body massage, then sell my calls for major profits in the AM ;) let’s fucking go! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:49:16 </td>
   <td style="text-align:left;"> $SPY $TSLA 
So when do the robots eat the humans </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:47:00 </td>
   <td style="text-align:left;"> $TSLA  trolls wrong again- Ford shares fall on fourth-quarter earnings and 2022 guidance https://www.cnbc.com/2022/02/03/ford-f-earnings-q4-2021.html?__source=iosappshare%7Ccom.stocktwits.StockTwits.STShareExtension </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:46:46 </td>
   <td style="text-align:left;"> $TSLA look at that 4% pump AH at $BRK.A  $BRK.B  
 
people feeling to safety.. going to be shit until we hear if .25 or .5 rate hike in March. Powell tanking us harder? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:46:33 </td>
   <td style="text-align:left;"> $TSLA  one guarantee in the market TSLA will be pumped AH/PM then dumped.    6:14 am. $938.00.  Opened at $888.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:44:30 </td>
   <td style="text-align:left;"> Unusual Options Activity: $TSLA is the #12 ticker with unusual activity from institutional traders with an average of 25% out of the money, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:44:24 </td>
   <td style="text-align:left;"> $TSLA never seen before PE ratio. 90% crash is bound to happen. You only see these crazy PE ratio before crisis and wipe out everyone. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:44:13 </td>
   <td style="text-align:left;"> $TSLA slow bleed to 850 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:44:03 </td>
   <td style="text-align:left;"> $TSLA has a Profit Margin of 10.25%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:41:50 </td>
   <td style="text-align:left;"> $TSLA dear folks we have huge market swings !
Mega caps trading like penny stocks this behavior is very typical in a BEAR MARKET !!!

AMAZON did not saved you , it tricked you so you don’t see that they barely made forecast Real casino starts tmrw.

Won’t be pretty !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:40:28 </td>
   <td style="text-align:left;"> $TSLA so Tesla didn’t go up on earnings because of the owner speaking on call? What a loser! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:39:54 </td>
   <td style="text-align:left;"> $TSLA $12 eps in ‘22 at 120 peak P/E during the year possible imo.  Macro could go down the 💩 🚽. 🤷🏼‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:39:39 </td>
   <td style="text-align:left;"> $TSLA wow. Everything else exploded back and this didn&amp;#39;t, what a pos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:38:17 </td>
   <td style="text-align:left;"> $TSLA this will fill the gap this year at $86/share. Optimus won&amp;#39;t be able to save this garbage. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:37:47 </td>
   <td style="text-align:left;"> $TSLA also this Stocktwits update sucks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:37:47 </td>
   <td style="text-align:left;"> $TSLA you know I get that Elon loves his rockets but if he even tweeted a fraction about Tesla that he does about SpaceX we would be 🌙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:37:28 </td>
   <td style="text-align:left;"> $TSLA  
 
https://www.benzinga.com/government/22/02/25400255/tesla-fans-buy-times-square-billboard-promoting-tweet-from-elon-musk-will-president-biden-notice 
BZ Pro: https://benzinga.grsm.io/gxjhpowx7zks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:37:12 </td>
   <td style="text-align:left;"> $TSLA I think around 900 is a real value. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:36:33 </td>
   <td style="text-align:left;"> $TSLA  
*Walter Bloomberg 
@DeItaone 
· 
56m 
TWITTER UP ALMOST 10% IN EXTENDED TRADE FOLLOWING QTRLY RESULTS FROM SNAP AND PINTEREST 
$TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:36:24 </td>
   <td style="text-align:left;"> $TSLA the bears failed over at $AMZN so they’re coming over to Tesla. This stock will ride the green wave tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:32:10 </td>
   <td style="text-align:left;"> $aapl $mp $tsla $nvda    
 
Highly recommended, it&amp;#39;s a free joining: ❤❤https://unlimitedtraderscomm.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:31:52 </td>
   <td style="text-align:left;"> $TSLA Buy puts tomorrow. You&amp;#39;re welcome. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:31:38 </td>
   <td style="text-align:left;"> $TSLA $AMZN nice! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:31:24 </td>
   <td style="text-align:left;"> $TSLA bears should be VERY nervous for tomorrow. Amazon failed you. Shorting Tesla won’t help you tomorrow when it opens +5% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:30:45 </td>
   <td style="text-align:left;"> $TSLA 

$F 
EBT Adj: 11.5-12.5b
EBT Margin: 8% 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:30:29 </td>
   <td style="text-align:left;"> $TSLA same problem exists: 
 
P/E </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:30:02 </td>
   <td style="text-align:left;"> $TSLA ARRY - over 10.63% of shares float shorted. Potential shortsqueeze. 
Goldman Sachs List ARRY as 1 of 5 Solar Stocks to Buy Now With 40% to Over 100% Upside Potential https://247wallst.com/investing/2022/02/02/goldman-sachs-has-5-solar-stocks-to-buy-now-with-40-to-over-100-upside-potential </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:29:20 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:29:13 </td>
   <td style="text-align:left;"> $TSLA 846 gap fill tmr? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:28:44 </td>
   <td style="text-align:left;"> $TSLA bears are going to get SLAUGHTERED tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:28:41 </td>
   <td style="text-align:left;"> $TSLA when are the monthly car numbers come out? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:27:41 </td>
   <td style="text-align:left;"> $TSLA hey shortys. How do you feel right now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:27:11 </td>
   <td style="text-align:left;"> $TSLA annnnd so much for the AH rally that was fast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:26:44 </td>
   <td style="text-align:left;"> $FB  $TSLA  $LXRX  $MSFT  $T    GIVE ME MORE, LET&amp;#39;S GO AND WIN!!! 
 
VICTORY IS AHEAD OF US AND GLORY IS TASTY !!!!!!!!!!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:26:40 </td>
   <td style="text-align:left;"> $TSLA fading already ; remember today 930-935 short alert .. covered under 900 but i am expecting more pump to resistant to short again.. you can do opposite ; buy supports 880s area and sell 930-950 areas.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:26:23 </td>
   <td style="text-align:left;"> $TSLA tesla&amp;gt;&amp;lt;ford </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:26:21 </td>
   <td style="text-align:left;"> $SPY Theres no way rivians stock boost account for 85% of amazon&amp;#39;s income. If so.... that&amp;#39;s a pretty scary earnings report $AAPL $TSLA $NVDA $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:25:53 </td>
   <td style="text-align:left;"> $TSLA Ford Motor (F) Misses Q4 EPS by 16c http://www.streetinsider.com/Earnings/Ford+Motor+%28F%29+Misses+Q4+EPS+by+16c/19555326.html via @Street_Insider Ford Motor reported Q4 EPS of $0.26, $0.16 worse than the analyst estimate of $0.42. Revenue for the quarter came in at $37.7 billion versus the consensus estimate of $35.77 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:25:23 </td>
   <td style="text-align:left;"> $TSLA https://driveteslacanada.ca/news/tesla-applies-to-build-cathode-factory-next-to-giga-texas/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:24:00 </td>
   <td style="text-align:left;"> $TSLA $AMZN $SNAP bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:22:14 </td>
   <td style="text-align:left;"> $TSLA 

LETS TAKE AN AUTONOMOUS DRIVE BACK TO $1200!

BUY DIPS/REMOVE STOPS/REPEAT!

🦍🦍💰💰🦍🦍💰💰🚀🙏❤️🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:21:56 </td>
   <td style="text-align:left;"> $AAPL $TSLA $SPY what time is job report tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:21:44 </td>
   <td style="text-align:left;"> $TSLA 777,665? Wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:21:14 </td>
   <td style="text-align:left;"> $TSLA Bulls/Longs will get a bump off Aamzon EPS beat 
 
Jobs report on Friday, unless algos shrugg it off because of Aamzon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:17:54 </td>
   <td style="text-align:left;"> $TSLA this is going to go parabolic tomorrow. Wouldn’t be shocked to see the high 900s tomorrow. Market was worried about Amazon’s earnings but we’ll ride the green wave with them
Tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:14:01 </td>
   <td style="text-align:left;"> $AMZN Do people not realize the business made -50% less than Q4-20? This is exactly the scenario when $TSLA bolstered eps with Bitcoin gains, yet Amazon didn’t sell rivian and it’s down 40% since quarter-end </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:11:53 </td>
   <td style="text-align:left;"> $TSLA I think she drops for the first 30 minutes to 1 hour folding its trajectory pattern but  hits that 880 or 860 then reverses and goes to 950 because of the amazon beat. 2 way play it will be glorious for all bears and bulls if played correctly. Cheers! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:11:21 </td>
   <td style="text-align:left;"> $TSLA realistically with this even affect Tesla much tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:10:14 </td>
   <td style="text-align:left;"> Palisades Hudson Asset Management L.P.,has filed Form 13F for Q4 2021.Opened NEW positions in $AZO $BRK/B $IAU $NUSC $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:10:11 </td>
   <td style="text-align:left;"> like it or not my target will be $amzn $tsla $aapl shorts at tomorrow pump .. but job report might not let enough pump tomorrow... 
 
BUY THE DIPS ; SHORT THE RIPS... $spy  .. of course there must be reason for it.. dont buy or short company you dont know !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:09:57 </td>
   <td style="text-align:left;"> $TSLA option chain points to a slight rise in price https://stockilluminati.com/tsla/options.php </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:09:32 </td>
   <td style="text-align:left;"> $TSLA super glad I decided to hedge my puts with some calls before close. If she stays below 920 until open I should able to exit puts with a profit still. Hope All the good earnings have ripple affect here. Without volume though MM could pump this back up just enough to kill put premiums and then chop it. Jobs report could definitely slow market euphoria as well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:09:11 </td>
   <td style="text-align:left;"> $HITI  Taking a portion of my profs from today’s trading of $TSLA and $HEXO and throwing them here ASAP. See you mob in the morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:07:47 </td>
   <td style="text-align:left;"> $TSLA I don&amp;#39;t know why but we got too much flow mm will bring it back down under 900 tomorrow possible 880 sucks 910s are burned real bad. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:07:11 </td>
   <td style="text-align:left;"> $TSLA 😜 https://youtu.be/L-FqqWxaN0Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:05:44 </td>
   <td style="text-align:left;"> $SPY  did jeff dethone musk as richest guy  ? $AMZN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:04:07 </td>
   <td style="text-align:left;"> $PLTR $TSLA $AMZN $QQQ $SPY 

Jeff Bezos thank you for saving the market lemme give you top </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:04:00 </td>
   <td style="text-align:left;"> $F It is a buy here. Ask yourself why would you want to pay so much more premium to buy $TSLA shares when you can buy Ford at much cheaper valuations when both companies are making EVs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:03:25 </td>
   <td style="text-align:left;"> $tsla is going to go insane tomorrow +60 $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:03:17 </td>
   <td style="text-align:left;"> $TSLA - can we run over $1K tomorrow. Looks like Naz will be running tomorrow. Loaded up on calls at close, just in case AMZN came through and they did. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:02:46 </td>
   <td style="text-align:left;"> $AMZN $SPY $QQQ $TSLA get cheap shares on $ATER for sympathy squeeze on AMZN great earnings. AMZN sellers uses ATER AI DealMojo to get even more sales on their AMAZON storefront. SYMPATHY PLAY is ATER! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:02:41 </td>
   <td style="text-align:left;"> $TSLA we will see $950+ tomorrow easily. Market is going to rally huge with Amazon ER beat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:01:08 </td>
   <td style="text-align:left;"> $TSLA come on. We need more than 16 points. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:01:07 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:00:48 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-03 Options Analysis Video: 
https://www.youtube.com/watch?v=xGiwyt5o5Vg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 06:00:08 </td>
   <td style="text-align:left;"> $TSLA 

Today was one of my favorite days n most profitable !! 
Called out the move to $950 - fell short by $13 !! Trapped many shorts then got ‘em destroyed back n forth !! 

This consolidation is significantly important at this level (bullet prof)  if y’all want to see $1425-$1500 !! IMO 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 05:59:28 </td>
   <td style="text-align:left;"> $TSLA come on tsla go 910.....fly fly fly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 05:58:57 </td>
   <td style="text-align:left;"> $TSLA Volatility is King!! Simulated Weekly $895.0 CALLS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 05:58:42 </td>
   <td style="text-align:left;"> $TSLA are my 950 calls going to print tomorrow or what? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 05:58:12 </td>
   <td style="text-align:left;"> $TSLA what’s next target? 

https://invescohood.com/cathie-woods-top-5-stock-pick/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 05:57:26 </td>
   <td style="text-align:left;"> $FB Facebook releasing the best phone this summer and take all of $AAPL and samsung market share???  This is fuckin war on Apple and Tim Crooks!!! Zuck rules.  Also, releasing Electric truck capable of 5,000 miles on a single charge.  Coast to coast domination.  Fuck $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 05:57:14 </td>
   <td style="text-align:left;"> $FB $AMC $AAPL $BTC.X $TSLA Marky   Cuckleberg 🦍🦍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 05:57:03 </td>
   <td style="text-align:left;"> $TSLA this should be above 1k after ER imo. I didn’t care for the call. IMO they’re better served focusing on product ramp with an afterthought of robot publicly, but Musk gonna do Musk and that’s why many of us are here. Anybody got the weird nerds defend Elon meme? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 05:56:06 </td>
   <td style="text-align:left;"> $TSLA  If we finish below $1200 tomorrow, I will stop having sex. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 05:55:02 </td>
   <td style="text-align:left;"> $TSLA How long will $900 be a battle ground? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 05:54:39 </td>
   <td style="text-align:left;"> $TSLA $950 tomorrow please! Been hold my CALL for 2 weeks now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-04 05:54:39 </td>
   <td style="text-align:left;"> $TSLA Tesla Fans Buy Times Square Billboard Promoting Tweet From Elon Musk: Will President Biden Notice? 
4:38 pm ET February 3, 2022 (Benzinga) </td>
  </tr>
</tbody>
</table></div>

---
