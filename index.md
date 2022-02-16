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



Last Updated: 2022-02-16 08:51:43 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/unemployment-rate </td>
   <td style="text-align:left;"> 2022-02-16 08:20:51 </td>
   <td style="text-align:left;"> South Korea Adds Most Jobs Since 2000 </td>
   <td style="text-align:left;"> The seasonally adjusted unemployment rate in South Korea improved to 3.6% in January 2022 from 3.8% in the previous month, as the economy withstood a surge in virus infections and the resulting government-imposed curbs. The country added 1,135,000 jobs in January from a year earlier, for the 11th straight month of gains and the highest increase since March 2000. A low base effect also likely contributed to the annual hiring strength, as South Korea’s economy shed 982,000 jobs in January 2021, the biggest drop since 1998. The latest figures support the view that the economy could withstand another rate hike as the Bank of Korea tries to rein in inflation and normalize monetary policy. The medical &amp; welfare industries led the employment gains, followed by construction, lodging and information technology. On the other hand, the financial &amp; insurance industries and wholesale &amp; retail sectors saw a decline in employment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/15/business/jeff-zucker-cnn.html </td>
   <td style="text-align:left;"> 2022-02-16 08:09:02 </td>
   <td style="text-align:left;"> How a Secret Assault Allegation Against an Anchor Upended CNN - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                , Supported by                                                                                                                                                                                                                                                                                                                                                                                 , The network’s top-rated host and its president were forced out following ethical lapses, an office romance and a letter from a lawyer for “Jane Doe.”                                                                                                                                                                                                                                        , By Emily Steel, Jodi Kantor, Michael M. Grynbaum, James B. Stewart and John Koblin                                                                                                                                                                                                                                                                                                           , Late in the day on Nov. 30, Jeff Zucker, the president of CNN Worldwide, summoned his star anchor and friend, Chris Cuomo, to a meeting in the network’s skyscraper overlooking the Hudson River.                                                                                                                                                                                            , Mr. Zucker was joined by the network’s chief marketing officer — and his secret romantic partner — Allison Gollust. They had to deliver a delicate message.                                                                                                                                                                                                                                  , Mr. Zucker told Mr. Cuomo that CNN was suspending him because of his unethical interactions with his brother, New York’s governor. Mr. Cuomo was shocked and offered to resign. Mr. Zucker countered that the anchor might be able to return at some point, according to people with knowledge of the conversation.                                                                          , Mr. Cuomo felt reassured. He and Mr. Zucker were confidants, their fortunes entwined. Mr. Cuomo didn’t bother to consult a lawyer.                                                                                                                                                                                                                                                           , Barely 24 hours later, a letter arrived at CNN. It was from a lawyer representing a woman who had worked with Mr. Cuomo years earlier at ABC News. She said he had sexually assaulted her and that, in the heat of the #MeToo movement, Mr. Cuomo had tried to keep her quiet by arranging a flattering CNN segment about her employer at the time.                                          , The letter described it as an “abuse of power at CNN to attempt to silence my client.”                                                                                                                                                                                                                                                                                                       , While a spokesman for Mr. Cuomo denied the allegations in the letter, it set in motion a chain of events that would quickly upend one of the world’s most powerful news networks.                                                                                                                                                                                                            , By week’s end, Mr. Zucker had fired Mr. Cuomo, telling him that a drumbeat of scandals had become “too much for us.”                                                                                                                                                                                                                                                                         , Two months later, Mr. Zucker was forced to resign. On Tuesday, CNN announced that Ms. Gollust, too, was leaving the network.                                                                                                                                                                                                                                                                 , Publicly, Mr. Zucker blamed the failure to disclose his relationship with Ms. Gollust. But other forces had set the stage for his downfall.                                                                                                                                                                                                                                                  , CNN had skidded into third place in cable news ratings. A key investor had criticized the network’s opinionated, personality-driven programming. Mr. Zucker had clashed with a top executive at CNN’s parent company. And he had made powerful enemies out of Mr. Cuomo and his brother, the former New York governor.                                                                       , By the time of Mr. Cuomo’s ouster, the law firm that had been hired to investigate his behavior had turned its attention to Mr. Zucker and his management of a network where his intimacy with sources and employees had been both his calling card and Achilles’ heel.                                                                                                                      , Mr. Zucker’s abrupt departure has thrown the future of CNN into chaos, just as it was poised to introduce a highly anticipated streaming service and to come under new corporate ownership.                                                                                                                                                                                                  , Mr. Cuomo is hoping to extract tens of millions of dollars from CNN. Star anchors are revolting. Employees are wondering whether, without Mr. Zucker at the helm, the network’s soon-to-be-owners at Discovery Inc. will fundamentally change CNN’s sprawling news operations.                                                                                                               , In a memo on Tuesday evening announcing Ms. Gollust’s resignation, Jason Kilar, the chief executive of CNN’s parent company, said an internal investigation “found violations of company policies,” including CNN’s news standards and practices, by Mr. Cuomo, Mr. Zucker and Ms. Gollust. “I realize this news is troubling, disappointing, and frankly, painful to read,” Mr. Kilar wrote., Risa Heller, a spokeswoman for Mr. Zucker, said, “Jeff was never aware of the full extent of what Chris Cuomo was doing for his brother, which is why Chris was fired.”                                                                                                                                                                                                                      , Steven Goldberg, a spokesman for Chris Cuomo, said, “Mr. Cuomo felt very close personally and professionally to Mr. Zucker, which is part of what makes this so difficult and hurtful.”                                                                                                                                                                                                      , Ms. Heller and Ms. Gollust didn’t have an immediate comment on Mr. Kilar’s memo. Mr. Goldberg declined to comment.                                                                                                                                                                                                                                                                           , More than 30 people familiar with the recent tumult — including the woman on whose behalf the letter was written to CNN — described the events and ethical violations that led to a leadership collapse at “the most trusted name in news.”                                                                                                                                                  , The ties between Mr. Zucker, Ms. Gollust and Mr. Cuomo — as well as Andrew Cuomo, who resigned as governor last August — ran deep.                                                                                                                                                                                                                                                           , Mr. Zucker had met Ms. Gollust at NBC, when she was a young publicist for the “Today” show and he was its 26-year-old executive producer. As he climbed the ranks, eventually becoming NBCUniversal’s chief executive, the pair continued to work closely together. Ms. Gollust even moved her family to the floor above Mr. Zucker’s in an Upper East Side building.                        , Then, in 2011, NBC’s new parent company forced Mr. Zucker out.                                                                                                                                                                                                                                                                                                                               , Around then, Governor Cuomo was planning to throw a birthday party for his girlfriend, the lifestyle impresario Sandra Lee. He asked Ms. Lee to recommend someone to organize the event. She suggested Ms. Gollust.                                                                                                                                                                          , The resulting party — a clambake on a Hamptons beach — was such a resounding success that Mr. Cuomo decided Ms. Gollust should work for him. In 2012 she became the governor’s communications director.                                                                                                                                                                                      , A few months later, in January 2013, CNN hired Mr. Zucker. The next month, Ms. Gollust left Mr. Cuomo and Albany and rejoined her former boss as the network’s head of communications.                                                                                                                                                                                                       , CNN was struggling. Once the leader in 24/7 news, its ratings had fallen, its programming seen as stale. Mr. Zucker’s mission was to rejuvenate the network.                                                                                                                                                                                                                                 , At NBC, he had turned around the moribund “Today” show by embracing feel-good news and nurturing stars like Katie Couric. More triumphs followed for Mr. Zucker, as shows like “The Apprentice” and “Fear Factor” were hits with viewers and helped elevate Donald J. Trump and Joe Rogan into cultural touchstones.                                                                         , At CNN, one of Mr. Zucker’s first creations was a peppy morning show called “New Day.” To co-host the show, Mr. Zucker recruited Chris Cuomo, an ABC News correspondent who had shined in reporting from war and disaster zones.                                                                                                                                                             , Within months of his arrival, Mr. Cuomo began pushing ethical boundaries.                                                                                                                                                                                                                                                                                                                    , In December 2013, he interviewed Governor Cuomo about a train crash in the Bronx. Media critics objected that it was impossible for someone to impartially report on their sibling.                                                                                                                                                                                                          , Afterward, Mr. Zucker barred Chris from interviewing or covering Andrew.                                                                                                                                                                                                                                                                                                                     , “New Day” was a modest hit. But Mr. Cuomo was polarizing. Some colleagues said he could go from charming to bullying in a flash. More than once, he sent emails and text messages that colleagues considered rude and even threatening.                                                                                                                                                      , Yet Mr. Zucker was loyal. In 2018 he awarded Mr. Cuomo his own show in the coveted 9 p.m. slot, competing with stars like Rachel Maddow at MSNBC and Sean Hannity at Fox News.                                                                                                                                                                                                               , Mr. Cuomo’s combative style made him an ideal on-air foil for President Trump. “Cuomo Prime Time” quickly became CNN’s highest-rated show. The success only strengthened Mr. Cuomo’s bond with Mr. Zucker.                                                                                                                                                                                   , After Mr. Zucker underwent heart surgery in 2018, he and Mr. Cuomo spent hours talking during long walks in Central Park.                                                                                                                                                                                                                                                                    , Mr. Zucker soon signed off on a multiyear contract that paid Mr. Cuomo more than $6 million annually.                                                                                                                                                                                                                                                                                        , The onset of the pandemic stoked Mr. Zucker’s hypercompetitive instincts, on display since his days as a high school tennis champion. During the Trump years, he had led CNN to record-high ratings and roughly $1 billion in annual profit.                                                                                                                                                 , Now, in the Cuomo brothers, he saw a singular opportunity.                                                                                                                                                                                                                                                                                                                                   , Governor Cuomo was having a moment. His televised briefings were calm and filled with data, a stark contrast to the often baffling pronouncements from the Trump administration. There was talk of him running for president.                                                                                                                                                                , Then Chris Cuomo contracted Covid. He quarantined in and broadcast from the basement of his 6,000-square-foot home in East Hampton, N.Y. His ratings soared.                                                                                                                                                                                                                                 , With his eye for spectacle, Mr. Zucker lifted the ban on Chris Cuomo interviewing his brother. Beginning in April 2020, the Cuomos ruminated on air about how the virus had disrupted society and their lives.                                                                                                                                                                               , Mr. Zucker loved it. “Authenticity and relatability and vulnerability — that’s what the brothers Cuomo are giving us right now,” he gushed to The New York Times in April 2020.                                                                                                                                                                                                              , But their on-air bonding looked less charming after The Washington Post reported that Governor Cuomo had helped his brother get preferential access to scarce Covid tests, with state troopers escorting his nasal swabs to a lab.                                                                                                                                                           , CNN defended its anchor, saying he had “turned to anyone he could for advice and assistance, as any human being would.”                                                                                                                                                                                                                                                                      , One evening in March 2021, Chris Cuomo made a remark on live television that helped precipitate his downfall — and eventually Mr. Zucker’s.                                                                                                                                                                                                                                                  , The New York attorney general had just announced that her office was investigating sexual harassment allegations against Andrew Cuomo.                                                                                                                                                                                                                                                       , With the governor in trouble, Mr. Zucker reimposed the ban on Chris Cuomo covering him. As Mr. Cuomo explained to his viewers that he would be stepping away from the story, he gazed into the camera and denounced sexual harassment.                                                                                                                                                       , “I have always cared very deeply about these issues and profoundly so,” he declared.                                                                                                                                                                                                                                                                                                         , The woman who had worked with him at ABC News watched in disbelief.                                                                                                                                                                                                                                                                                                                          , She said in an interview with The Times that she was haunted by the similarities between her experience and those of the governor’s accusers. She wanted to protect other women but didn’t want to go public, fearing retaliation and the loss of her privacy.                                                                                                                               , Soon, though, she would hire a lawyer.                                                                                                                                                                                                                                                                                                                                                       , The governor’s rise had fueled his brother’s. Now, as Andrew Cuomo’s position worsened, so did Chris’s.                                                                                                                                                                                                                                                                                      , In May 2021, The Washington Post reported that Chris Cuomo had been advising the governor’s staff on how to fend off the harassment scandal. CNN — whose parent company had just announced plans to merge the network with Discovery — said the conversations were “inappropriate” but didn’t discipline him.                                                                                , Some CNN employees were aghast. An anchor, Jake Tapper, told The Times that Mr. Cuomo “put us in a bad spot.”                                                                                                                                                                                                                                                                                , Then, on Aug. 3, the New York attorney general, Letitia James, released a damning report about Andrew Cuomo’s sexual harassment. The news was covered throughout the day on CNN — until 9 p.m., when Chris Cuomo came on air.                                                                                                                                                                , He didn’t mention the scandal.                                                                                                                                                                                                                                                                                                                                                               , A week later, the governor resigned.                                                                                                                                                                                                                                                                                                                                                         , Complaints soon began surfacing about the younger Mr. Cuomo.                                                                                                                                                                                                                                                                                                                                 , Shelley Ross, a longtime TV news executive and Mr. Cuomo’s former boss at ABC, wrote in a Times opinion piece in September that Mr. Cuomo had groped her at a 2005 party. (Mr. Cuomo apologized.)                                                                                                                                                                                            , Around the same time, The New York Post reported that Mr. Cuomo’s former producer, Melanie Buck, had asked to be removed from “Cuomo Prime Time” because she found his conduct to be threatening.                                                                                                                                                                                            , CNN executives grew concerned. They asked the network’s longtime law firm, Cravath Swaine &amp; Moore, to look into the matter, according to a person familiar with the investigation.                                                                                                                                                                                                           , In late November, Ms. James’s office released a fresh crop of emails and text messages that revealed how Chris Cuomo had collected information about forthcoming articles about his brother and tried to undermine the credibility of one of his brother’s accusers.                                                                                                                         , The next day, Nov. 30, Mr. Cuomo was chauffeured to CNN’s Manhattan headquarters to sketch out that evening’s show. Mr. Zucker asked him to come to a meeting.                                                                                                                                                                                                                               , The network president had spent years standing by his anchor. Now, feeling that Mr. Cuomo had misled him, Mr. Zucker was losing patience. He had initially planned to fire Mr. Cuomo, before deciding to hold off.                                                                                                                                                                           , Mr. Zucker tried to be diplomatic as he broke the news that Mr. Cuomo was suspended. He suggested there was a chance he could return after the network’s investigation ran its course, according to people familiar with the conversation.                                                                                                                                                   , CNN went back to Cravath and asked the firm to examine the new information about the interactions between the Cuomo brothers.                                                                                                                                                                                                                                                                , The next morning, Dec. 1, the CNN reporter Brian Stelter said on-air that Mr. Cuomo could “be back in January.”                                                                                                                                                                                                                                                                              , That night, the fateful letter arrived at CNN. It was from Debra S. Katz, a prominent sexual harassment lawyer, and it was addressed to David Vigilante, CNN’s general counsel.                                                                                                                                                                                                              , The letter was on behalf of the woman who had worked with Mr. Cuomo at ABC News.                                                                                                                                                                                                                                                                                                             , It relayed a story that had begun in 2011 when the woman, who was referred to as Jane Doe, was a young temporary ABC employee hoping for a full-time job. One day, after Mr. Cuomo, an anchor, had offered her career advice, he invited her to lunch in his office, according to the letter, interviews with the woman and emails between her and Mr. Cuomo.                                , When she arrived, there was no food. Instead, Mr. Cuomo badgered her for sex, and after she declined, he assaulted her, she said. She ran out of the room.                                                                                                                                                                                                                                   , Later that day, the woman, who was still seeking a job, tried to smooth things over by writing Mr. Cuomo friendly emails.                                                                                                                                                                                                                                                                    , The Times interviewed five friends and former colleagues who said the woman told them Mr. Cuomo had made unwelcome sexual requests. She said that only in the past year did she begin to tell people that Mr. Cuomo had also assaulted her, which she hadn’t previously divulged because it was private and painful.                                                                         , The encounter in Mr. Cuomo’s office at ABC was not the end of her story.                                                                                                                                                                                                                                                                                                                     , Ms. Katz’s letter said that at the height of the #MeToo uprising, after TV personalities like Charlie Rose and Matt Lauer were felled by misconduct allegations, Mr. Cuomo contacted the woman, seemingly out of the blue.                                                                                                                                                                   , Mr. Cuomo proposed arranging a CNN segment about the company where she worked doing public relations. The woman tried to avoid any contact with Mr. Cuomo, but CNN ultimately broadcast a segment anyway.                                                                                                                                                                                    , “After years without any substantive communication from Mr. Cuomo whatsoever, Ms. Doe suspected he was concerned about her coming forward publicly with her allegations and wanted to use the proposed segment as an opportunity to ‘test the waters’ and discourage her from going on the record about his sexual misconduct,” Ms. Katz wrote.                                              , The Times reviewed Mr. Cuomo’s messages to the woman and the segment and spoke with her boss at the time. Her boss said that after the segment aired, the woman shared some of the details of the encounter and Mr. Cuomo’s subsequent outreach.                                                                                                                                             , Ms. Katz said the woman, who has been “deeply traumatized,” doesn’t want to become “a pawn in an internecine war between Zucker, Chris Cuomo and CNN” and won’t be saying anything further. She “deserves and requests privacy,” Ms. Katz said.                                                                                                                                              , On Friday, Dec. 3, two days after Ms. Katz sent the letter, she and a lawyer for CNN made plans for her to hand over evidence to substantiate the woman’s claims.                                                                                                                                                                                                                            , Before that even happened, Mr. Zucker fired Mr. Cuomo the next afternoon.                                                                                                                                                                                                                                                                                                                    , From Mr. Cuomo’s perspective, Mr. Zucker had fired him without due process, fearful that the woman’s allegations might appear in the media, according to a person familiar with his thinking.                                                                                                                                                                                                , Mr. Goldberg, the spokesman for Mr. Cuomo, said the allegations in Ms. Katz’s letter “are false. He was never asked about the allegations prior to being terminated or given an opportunity to respond.” He refused to elaborate.                                                                                                                                                            , The day after he was fired, Mr. Cuomo hired Bryan Freedman, a Hollywood litigator known for tough negotiating tactics and for securing multimillion-dollar settlements for aggrieved television stars. (In Mr. Cuomo’s case, he planned to seek money owed under the anchor’s contract and compensation for future lost earnings.)                                                           , On Dec. 5, Mr. Freedman sent a letter to CNN demanding that the network preserve all documents related to any dealings between any CNN employee and anyone in the governor’s office.                                                                                                                                                                                                         , It was a clear signal that a key element of Mr. Cuomo’s defense would be that Mr. Zucker and others at CNN had acted similarly to Mr. Cuomo in communicating with the governor, with no repercussions.                                                                                                                                                                                       , People in Mr. Cuomo’s camp soon began whispering to reporters that Mr. Zucker had coached Governor Cuomo on how to use his televised briefings to go after Mr. Trump.                                                                                                                                                                                                                        , Ms. Heller, the spokeswoman for Mr. Zucker, said he only spoke to the governor about appearing on CNN. “He never gave Andrew Cuomo advice,” she said.                                                                                                                                                                                                                                        , Soon, an article appeared on the gossip site Radar. It asserted that Mr. Zucker and Ms. Gollust had been engaged in a yearslong romantic relationship. The CNN president’s career was about to unravel.                                                                                                                                                                                      , Mr. Zucker commanded loyalty from star anchors, and he had won the respect of many CNN journalists for standing up to Mr. Trump, who repeatedly attacked the network.                                                                                                                                                                                                                        , But by late last year, his standing with his corporate superiors had wavered. The ugly situation with Mr. Cuomo was only the latest blow.                                                                                                                                                                                                                                                    , In mid-November, John Malone, a leading shareholder in Discovery, appeared on CNBC. “I would like to see CNN evolve back to the kind of journalism that it started with and actually have journalists, which would be unique and refreshing,” Mr. Malone said.                                                                                                                               , The barb raised questions about whether the network’s future owners would seek major editorial changes.                                                                                                                                                                                                                                                                                      , Plus, the network’s ratings were down. And Mr. Zucker had a testy relationship with Mr. Kilar, the WarnerMedia chief executive.                                                                                                                                                                                                                                                              , In August 2020, Mr. Kilar announced changes to CNN’s corporate structure without consulting Mr. Zucker. Days later, Mr. Zucker was noticeably absent from a virtual “town hall” meeting that Mr. Kilar hosted.                                                                                                                                                                               , Instead, the CNN president attended a 50th birthday party for Chris Cuomo in the Hamptons, according to two people familiar with the matter.                                                                                                                                                                                                                                                 , By early January, Cravath’s investigation was moving forward, and the tenor of its questions had begun to shift.                                                                                                                                                                                                                                                                             , What had started with a focus on Mr. Cuomo’s behavior was morphing into a broader look at Mr. Zucker’s handling of the anchor and his interactions with the Cuomos.                                                                                                                                                                                                                          , Among other things, the lawyers asked CNN employees about how Mr. Zucker had handled Mr. Cuomo’s suspension and firing, what he knew about Chris Cuomo’s interactions with his brother — and whether any employees were aware of communications between Mr. Zucker and Andrew Cuomo.                                                                                                         , When the lawyers questioned Mr. Zucker and Ms. Gollust, they asked about their romance. Mr. Zucker told them that the relationship had turned sexual during the pandemic.                                                                                                                                                                                                                    , Mr. Zucker didn’t disclose it to anyone in human resources or his superiors at WarnerMedia, including Mr. Kilar.                                                                                                                                                                                                                                                                             , The affair violated the company’s code of conduct, which prohibited employees from supervising anyone with whom they have a personal relationship.                                                                                                                                                                                                                                           , On Monday, Jan. 31, Mr. Zucker was absent from his usual role leading CNN’s daily 9 a.m. news meeting. He didn’t show up on Tuesday or Wednesday mornings, either.                                                                                                                                                                                                                           , At 11 a.m. on Wednesday, Mr. Zucker emailed CNN staff with shocking news: He was resigning.                                                                                                                                                                                                                                                                                                  , Mr. Zucker said he was leaving because he hadn’t disclosed the romantic relationship when it began. “I was wrong,” he wrote.                                                                                                                                                                                                                                                                 , Mr. Kilar had approached Mr. Zucker a few days earlier, shortly after he was interviewed by the Cravath lawyers, and told him he had to go. Mr. Zucker asked to stay until the Discovery merger was complete in a few months.                                                                                                                                                                , Mr. Kilar said no.                                                                                                                                                                                                                                                                                                                                                                           , Ben Smith contributed reporting. Sheelagh McNeill and Susan Beachy contributed research.                                                                                                                                                                                                                                                                                                     , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/dominican-republic/inflation-cpi </td>
   <td style="text-align:left;"> 2022-02-16 08:08:27 </td>
   <td style="text-align:left;"> Dominican Republic Inflation Rate at 7-Month High </td>
   <td style="text-align:left;"> Consumer prices in the Dominican Republic jumped to 8.7 percent year-on-year in January of 2022, quickening from a 8.5 percent increase in the previous month, the highest inflation rate since June of 2021. Main upward pressure came from food &amp; non-alcoholic beverages (9.3 percent vs 9.2 percent in December); housing &amp; utilities (9.2 percent vs 6.7 percent); transportation (14.9 percent vs 16.2 percent); alcoholic beverages &amp; tobacco (12.5 percent, the same as in December), miscellaneous goods &amp; services (7.0 percent vs 6.8 percent); furniture (6.8 percent vs 6.6 percent); and restaurants &amp; hotels (9.7 percent vs 9.9 percent). On a monthly basis, consumer prices rose 1.2 percent, following a 0.7 percent advance in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/reuters-tankan-index </td>
   <td style="text-align:left;"> 2022-02-16 07:58:23 </td>
   <td style="text-align:left;"> Japan Manufacturers’ Mood Drops to 11-Month Low </td>
   <td style="text-align:left;"> The Reuters Tankan sentiment index for manufacturers in Japan dropped to 6 in February 2022 from 17 in the previous month, hitting its lowest since March 2021 as pandemic-related curbs and rising raw material costs dented sentiment. Managers specifically cited several concerns including the omicron variant’s rapid spread, an ongoing semiconductor shortage, surging commodity prices and a weak yen. Among manufacturers, only firms in the oil refinery and ceramics sub-sector saw an improvement in business conditions, while sentiment in the other sub-sectors held steady or worsened. The poll, which tracks the Bank of Japan’s closely “tankan” quarterly survey, also showed manufacturers were less optimistic about the three months ahead than they were in January. Meanwhile, the service-sector index slipped for the first time in five months, but the outlook for the sector held up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/argentina/inflation-rate-mom </td>
   <td style="text-align:left;"> 2022-02-16 07:40:07 </td>
   <td style="text-align:left;"> Argentina Inflation Rate at 9-Month High </td>
   <td style="text-align:left;"> The monthly inflation rate in Argentina inched up to 3.9 percent in January of 2022, from 3.8 percent in the previous month and barely missed market expectations of 4.0 percent. It was the highest monthly inflation rate since April of last year. Prices rose the most for communications (7.5 percent vs 1.8 percent in December); restaurants &amp; hotels (5.7 percent vs 5.9 percent); food &amp; non-alcoholic beverages (4.9 percent vs 4.3 percent); miscellaneous goods &amp; services (4.3 percent vs 3.2 percent); culture &amp; recreation (4.2 percent vs 4.0 percent); and healthcare (4.1 percent vs 0.5 percent). On an annual basis, consumer prices soared 50.7 percent, easing slightly from a 50.9 percent increase in December of 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/15/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-02-16 07:05:45 </td>
   <td style="text-align:left;"> Stock futures inch lower after major averages snap 3-day losing streak </td>
   <td style="text-align:left;"> , U.S. stock index futures were slightly lower during overnight trading Tuesday, after registering gains on the session amid signs of tensions easing between Russia and Ukraine.                                                                                                                                                                                                                              , Futures contracts tied to the Dow Jones Industrial Average shed 39 points. S&amp;P 500 futures were down 0.16%, while Nasdaq 100 futures dipped 0.2%.                                                                                                                                                                                                                                                            , The major averages advanced during regular trading, snapping a three-day losing streak. The Dow gained 422 points, or 1.2%. The S&amp;P added 1.58%, while the Nasdaq Composite rose 2.5%.                                                                                                                                                                                                                       , President Joe Biden addressed the latest developments between Russia and Ukraine Tuesday afternoon, reiterating that the U.S. will defend NATO territory.                                                                                                                                                                                                                                                    , "If Russia proceeds, we will rally the world," he said, adding that Washington's allies were ready to impose powerful sanctions that will "undermine Russia's ability to compete economically and strategically."                                                                                                                                                                                            , The comments came after the Russian government said earlier in the day that some troops who had been on the Ukrainian border had returned to their bases.                                                                                                                                                                                                                                                    , This helped boost sentiment on Wall Street. The yield on the benchmark 10-year Treasury topped 2% as a risk-on tone returned to the market.                                                                                                                                                                                                                                                                  , Technology was the top-performing S&amp;P 500 sector, with nine out of the 11 groups registering gains on the day. Utilities and energy stocks were the two sectors in the red, dipping 0.6% and 1.4%, respectively.                                                                                                                                                                                             , "U.S. stocks rallied on optimism that it doesn't seem like Russia will invade Ukraine this week and despite another hot PPI report, as many on Wall Street are still not convinced the Fed will be as aggressive as some are calling for this year," said Oanda's Ed Moya.                                                                                                                                   , Here are Warren Buffett's latest moves, including increasing this energy bet by more than a third                                                                                                                                                                                                                                                                                                            , ‘The Big Short’ investor Michael Burry places a bet on electric motorcycles                                                                                                                                                                                                                                                                                                                                  , Fund manager likes a NYSE-listed Asia tech stock that's 60% off highs — and not based in China                                                                                                                                                                                                                                                                                                               , The Labor Department said Tuesday that wholesale prices jumped 1% in January, bringing the gain over the past 12 months to 9.7% on an unadjusted basis.                                                                                                                                                                                                                                                      , As inflation runs hot, Wall Street is looking ahead to the minutes from the Federal Reserve's January meeting, which will be released Wednesday at 2 p.m. ET.                                                                                                                                                                                                                                                , "The latest inflation data continue to decimate the 'inflation is purely transitory' theory,'" said Michael Cembalest, chairman of market and investment strategy at J.P. Morgan Asset Management. "After pricing in less than one Fed hike as of last September, markets and Fed watchers now expect between 6 and 7 hikes over the next year, with some arguing for a 50 basis point move and not just 25.", Retail sales data will also be released Wednesday at 8:30 a.m. on Wall Street. Economists are expecting the print to show that sales rose 2.1% in January. That compares to a 1.9% decline in December.                                                                                                                                                                                                      , Earnings season continues on Wednesday, with a number of companies slated to provide quarterly updates, including Applied Materials, Hyatt, AMC, Nvidia and Cisco Systems.                                                                                                                                                                                                                                   , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                       , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                       , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                             , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                             , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                           , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-16 07:01:04 </td>
   <td style="text-align:left;"> Australia 10Y Bond Yield Hits 3-year High </td>
   <td style="text-align:left;"> Australia 10 Year Government Bond Yeld increased to a 3-year high of 2.247% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/currency </td>
   <td style="text-align:left;"> 2022-02-16 06:49:07 </td>
   <td style="text-align:left;"> Canadian Dollar Firms as War Fears Calm </td>
   <td style="text-align:left;"> The Canadian dollar gained some ground to 1.27 against the greenback amid improved risk appetite due to de-escalating tensions in Eastern Europe, although lower oil prices capped some of the upward momentum. The scenario of imminent war in Ukraine seemed less likely after President Putin said he aimed to negotiate security guarantees with the West through diplomatic channels. Earlier, Russian troops from some military districts went back to their bases after the end of exercises near Ukraine. Now, traders await January inflation data for clues on the Bank of Canada’s rate hike outlook, after data showed home prices in Canada jumped 4.9% last month to new record highs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-steel-cfo-leave-post/story.aspx?guid={B3FD51C5-14AD-449F-9F32-97536BF0A282}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-16 06:44:45 </td>
   <td style="text-align:left;"> U.S. Steel CFO to leave post this year - MarketWatch </td>
   <td style="text-align:left;"> U.S. Steel Corp. 
        X,
        +6.35%
       said late Tuesday that Chief Financial Officer Christine S. Breves intends to leave the company this year, after nine years of service. Breves will continue to serve as CFO while the steel maker searches for a permanent replacement, the company said. Breves has agreed to stay on the whole year, however, as an executive vice president to support the company's strategies. "We have too much important work before us not to take full advantage of her capabilities. That's why I'm so pleased that Christie elected to remain for the full year and our Board of Directors agreed to elevate her to Executive Vice President," Chief Executive David B. Burritt said in a statement. Breves joined U.S. Steel in 2013 as chief procurement officer and led the company's financial and procurement teams since 2019. Shares of U.S. Steel dropped 0.7% in the extended session Tuesday after ending the regular trading day up 6.4%., Kamila Valieva took first place in the women's short program on Tuesday. The figure skating competition resumes Thursday.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/colombia/gdp-growth-annual </td>
   <td style="text-align:left;"> 2022-02-16 06:33:00 </td>
   <td style="text-align:left;"> Colombia Q4 GDP Growth Beats Forecasts </td>
   <td style="text-align:left;"> Colombia’s economic output advanced 10.8 percent year-on-year in the final quarter of 2021, following an upwardly revised 13.5 percent expansion in the previous period and above market expectations of 8.7 percent. The strongest growth rates were seen in entertainment, arts &amp; recreational activities (31.6 percent vs 31.7 percent in Q3); wholesale &amp; retail trade (21.2 percent vs 34.6 percent); information &amp; communication (18.1 percent vs 13.1 percent); manufacturing activities (11.7 percent vs 18.6 percent); and support &amp; administrative services and technical, scientific &amp; professional activities (10.1 percent vs 12.4 percent). On a seasonal and calendar adjusted quarterly basis, the economy expanded 4.3 percent, slowing from a 6.1 percent expansion in the prior period. Considering 2021 as a whole, GDP jumped 10.3 percent, rebounding solidly from a 7.3 percent contraction in the previous year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60393986?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-16 06:29:17 </td>
   <td style="text-align:left;"> Airbnb: City travel almost at pre-pandemic level </td>
   <td style="text-align:left;"> Online accommodation booking platform Airbnb says travellers are starting to return to cities, after staying away since the start of the pandemic.                                                                       , Globally, the number of nights booked in cities in the last three months of last year nearly matched 2019 levels, the lodging website said.                                                                              , In the US, urban bookings have fully rebounded, it said.                                                                                                                                                                 , The booking company reported a record $55m (£40.6m) profit for the fourth quarter.                                                                                                                                       , Cities were important destinations for Airbnb's business, but during the pandemic non-urban areas have proven more popular, as people focus on outdoor activities free of crowds.                                        , Bookings in urban areas are starting to grow, however, accounting for 49% of nights reserved in the three months to 1 January, the company said.                                                                         , "While travel to top cities has not yet entirely recovered to 2019 levels, we are seeing signs of travellers returning," it said.                                                                                        , The company also said it expected total nights booked in the first three months of 2022 to exceed pre-pandemic levels for the first time.                                                                                , Airbnb said the pandemic-driven expansion of remote work continues to shape its business, driving an explosion in long-term stays.                                                                                       , Nearly a quarter of nights booked in the last three months of 2021 were for four weeks or longer, it said.                                                                                                               , "Nearly two years into the pandemic, it's now clear that we are undergoing the biggest change to travel since the advent of commercial flying," the company said in a letter to shareholders.                            , "Remote work has untethered many people from the need to be in an office every day. As a result, people are spreading out."                                                                                              , Domestic and shorter distance stays remain more popular than international travel, but the San Francisco-based company said there are increasing signs that the virus has become less of a consideration for travellers. , For example, the platform had fewer cancellations during the wave of Omicron infections than during previous surges. And reservations for this summer at the end of January were up 25% compared to 2019.                , Revenue in the three months to 1 January rose 75% year-on-year to $1.5bn, propelled in part by higher rates, which jumped 20% compared to last year.                                                                     , Airbnb said it expected revenue of $1.4bn to $1.48bn in the first three months of 2022 which is higher than analysts had forecast.                                                                                       , For 2021 overall, Airbnb reported $6bn in revenue, while losses narrowed to $352m.                                                                                                                                       , "Overall, 2021 has proven to be an incredible year demonstrating the resiliency of the business," it said.                                                                                                               , Shares jumped 4% in after-hours trade, after rising 6% earlier in the day,                                                                                                                                               , Behind the faces leading US far right political movements online                                                                                                                                                         , Can her obsession drive her to finish what he couldn't?                                                                                                                                                                  , Whitney Houston's extraordinary life story with insights from those closest to her                                                                                                                                       , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-02-16 06:11:00 </td>
   <td style="text-align:left;"> Brazil Stocks End at 5-Month High </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, closed 0.8% higher at 114,828 on Tuesday, a level not seen since September 15th of last year, as appetite for risk returned amid de-escalating tensions between Russia and Ukraine, with new earnings and the US Fed’s looming tightening cycle in the backseat. At the top of the index were cloud provider Locaweb (+15.3%), Banco Pan (+10.4%), and airliner Azul (+8.5%), more than offsetting steep losses in heavyweight Vale (-3.0%) and Petrobras (-1.6%). Banco do Brasil (+4.7%) posted higher-than-expected fourth-quarter profit and announced ambitious 2022 goals. Itaúsa (+1.2%) and Raízen (0%) also surprised positively. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-02-16 05:49:00 </td>
   <td style="text-align:left;"> Toronto Stocks Close Higher, Robust Rebound </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, closed 0.7% or 150 points higher at 21,503 on Tuesday, tracking upbeat global sentiment, amid easing concerns about geopolitical risks. Across sectors, strong performances in academic &amp; educational, healthcare, and consumer cyclicals more than offset losses in heavyweight energy and mining stocks. Markets welcomed Russian President Putin’s remarks on his willingness to negotiate security guarantees through diplomatic channels and earlier reports that some Russian troops were returning to their bases following the end of military drills near Ukraine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/la-z-boy-stock-drops-after-furniture/story.aspx?guid={6E074F8A-32DD-4664-848F-73E6869ECBF8}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-16 05:46:57 </td>
   <td style="text-align:left;"> La-Z-Boy stock drops after furniture maker reveals multiple supply-chain snags - MarketWatch </td>
   <td style="text-align:left;"> Shares of La-Z-Boy Inc. 
        LZB,
        +2.71%
       dropped more than 8% in the extended session Tuesday after the furniture maker reported mixed fiscal third-quarter results and detailed multiple COVID-19 snags that hindered production amid ongoing high demand for its furniture items, which include its well-known recliners. La-Z-Boy said it earned $28.5 million, or 65 cents a share, in the quarter, compared with $29.2 million, or 63 cents a share, in the year-ago quarter. Sales rose to $572 million from $470 million a year ago. Analysts polled by FactSet expected fiscal third-quarter earnings of 89 cents a share on sales of $570 million. "Demand continues unabated across the La-Z-Boy enterprise and remains well above pre-pandemic levels," Chief Executive Melinda D. Whittington said in a statement. The quarter, however, "was marked by greater-than-expected supply-chain volatility, which had significant near-term impact on the efficiency of our manufacturing capacity ramp plans, dampening delivered sales growth and profit margins." The company also faced shortages of component parts, "record levels" of COVID-related employee absences in January, and the "challenge" of hiring and training new employees at its plants. A 14-week COVID-related shutdown in Vietnam also "temporarily and dramatically impacted sales and profitability for our casegoods import business, with minimal product available to ship to customers and high freight costs," the company said. La-Z-Boy stock ended the regular trading day up 2.7%. , Intel Corp. announced a $5.4 billion deal to acquire Tower Semiconductor.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/api-data-reportedly-show-weekly/story.aspx?guid={B1ED9C25-44A0-462A-8E3D-D692167BE7D5}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-16 05:42:41 </td>
   <td style="text-align:left;"> API data reportedly show weekly declines in U.S. crude, gasoline and distillate inventories - MarketWatch </td>
   <td style="text-align:left;"> The American Petroleum Institute reported late Tuesday that U.S. crude supplies fell by 1.1 million barrels for the week ended Feb. 11, according to sources. The API also reportedly showed weekly inventory declines of 923,000 barrels for gasoline and 546,000 barrels for distillates. Crude stocks at the Cushing, Okla., delivery were down by 2.4 million barrels last week, sources said. Inventory data from the Energy Information Administration will be released Wednesday. On average, the EIA is expected to show crude inventories down by 200,000 barrels, according to a survey of analysts conducted by S&amp;P Global Platts. The survey also calls for weekly supply declines of 900,000 barrels for gasoline and 1 million barrels for distillates. Oil prices extended their losses into the electronic trading session after the API data. March West Texas Intermediate crude 
        CLH22,
        +0.40%
       was at $91.97 a barrel in electronic trading, after settling Tuesday at $92.07 on the New York Mercantile., An environmental conservation group and two dozen outdoor recreation companies, including Patagonia, REI and The North Face, announced Monday they would boycott the Outdoor Retailer trade show if it's moved from Denver back to Salt Lake City.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/15/stocks-making-the-biggest-moves-after-hours-airbnb-roblox-wynn-resorts-more.html </td>
   <td style="text-align:left;"> 2022-02-16 05:41:21 </td>
   <td style="text-align:left;"> Stocks making the biggest moves after-hours: Airbnb, Roblox, Wynn Resorts &amp; more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                            , Check out the companies making headlines in after-hours trading:                                                                                                                                                                                                                                                                                                                           , Airbnb — Shares of the property rental company advanced 5% during extended trading Tuesday following the company's fourth-quarter results. Airbnb earned 8 cents during the period on $1.53 billion in revenue. Analysts surveyed by Refinitiv were expecting the company to earn 3 cents on $1.46 billion in sales. The company also gave strong guidance.                                , Wynn Resorts — The hotel company's stock slid more than 2% after Wynn missed earnings estimates for the fourth quarter. Wynn lost $1.37 per share excluding items, which was a wider loss than analysts had been expecting. Revenue, however, topped expectations. The company reported sales of $1.05 billion, compared to the $994 million analysts surveyed by Refinitiv were expecting., Roblox — Shares of the gaming company dropped more than 12% after Roblox's fourth-quarter results missed expectations on the top and bottom line. The company lost 25 cents per share during the period and reported sales of $770 million. Wall Street was expecting the company to lose 13 cents per share on $772 million in revenue, according to estimates from Refintiv.             , Denny's — Shares of Denny's dropped 10% after the company's fourth-quarter results disappointed Wall Street. Denny's earned 16 cents per share on $107.6 million in revenue. Analysts surveyed by Refinitiv were expecting the company to earn 17 cents on $111.8 million in revenue.                                                                                                      , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                     , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                     , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                           , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                           , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                         , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/15/health/hiv-third-person-remission/index.html </td>
   <td style="text-align:left;"> 2022-02-16 05:31:34 </td>
   <td style="text-align:left;"> Researchers report third case of HIV remission after stem cell transplant using umbilical cord blood - CNN </td>
   <td style="text-align:left;"> (CNN)A US woman has become the third known person who's gone into HIV remission, and the first mixed-race woman, thanks to a transplant of stem cells from umbilical cord blood, according to research presented at a conference Tuesday.                                                                                                                                                                                                                                                     , The woman, whom the researchers described as middle-aged and of mixed race, was diagnosed with acute myeloid leukemia four years after an HIV diagnosis, according to an abstract from the Conference on Retroviruses and Opportunistic Infections.                                                                                                                                                                                                                                            , After the leukemia diagnosis, she received high-dose chemotherapy that destroyed her blood cells. Later, she got a transplant of stem cells from an adult family member to replenish her own blood cell levels. This served as a bridge to maintain her blood cells while she received stem cells through umbilical cord blood from an unrelated newborn, which can take up to a month to start producing cells. The cord blood had a mutation that makes cells resistant to HIV infection.    ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Just over three years after her 2017 transplant, she stopped taking HIV meds, known as antiretroviral therapy, and had no detectable virus 14 months later.                                                                                                                                                                                                                                                                                                                                    , According to Dr. Marshall Glesby, associate chief of the Division of Infectious Diseases at Weill Cornell Medicine and a member of the research team, the advantage of using cord blood is that it is taken from a national repository that allows scientists to identify blood the HIV-resistant mutation.                                                                                                                                                                                    , This was also the mutation involved in the other two known cases of HIV cured in people who had stem cell transplants.                                                                                                                                                                                                                                                                                                                                                                         , This mutation is predominantly found in people of northern European descent, limiting the ability to transplant to people who aren't White. Yet although the patient in this study identified as mixed-race, she was still a match for the transplant, indicating a wider pool of possible transplant recipients from diverse racial backgrounds. Cord blood does not need to be as rigorously matched as adult donor stem cells.                                                              , "So [cord blood] would potentially be more widely available to people who need a transplant who have HIV, because of this lack of a necessity for as rigorous matching," Glesby told CNN.                                                                                                                                                                                                                                                                                                      , Dr. Yvonne Bryson, chief of pediatric infectious diseases at the David Geffen School of Medicine at UCLA and principal investigator of the study, said a man who was initially included in the study died of cancer recurrence before his results could be assessed.                                                                                                                                                                                                                           , The woman has also been in remission from cancer for 4½ years now. She did not have graft vs. host disease -- when donor cells attack the recipient's cells after a transplant -- unlike the two other people cured of HIV. Those previous experiences had led researchers to assume that graft vs. host disease was important to the cure. But the woman's case disproves it, Glesby said.                                                                                                    , However, researchers warn that this development applies only to a small fraction of people with HIV.                                                                                                                                                                                                                                                                                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , About 50 people a year who have HIV and blood cancer may benefit from this approach, according to Bryson.                                                                                                                                                                                                                                                                                                                                                                                      , Glesby agreed: "This is not the type of treatment that would be appropriate for somebody who does not have a medical need to have a transplant." This type of transplant can be fatal in up to 20% of people, he said, or it might cause other health problems.                                                                                                                                                                                                                                , "This person happened to have an underlying disease which required a stem cell transplant so I don't want people to think that now this is something that can be applied to the 36 million people who are living with HIV," Dr. Anthony Fauci, director of the National Institute on Allergy and Infectious Diseases, said Tuesday in an interview on the "Conversations on Health Care" radio show. "It is not practical to think that this is something that's going to be widely available.", CNN's Michael Nedelman contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/dvn:us </td>
   <td style="text-align:left;"> 2022-02-16 05:27:45 </td>
   <td style="text-align:left;"> Devon Energy earnings above expectations at 1.39 USD </td>
   <td style="text-align:left;"> Devon Energy (DVN) released earnings per share at 1.39 USD, compared to market expectations of 1.24 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/toast-stock-falls-more-11/story.aspx?guid={346C848B-0B74-416E-8202-F5FA0E5CBFA5}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-16 05:26:36 </td>
   <td style="text-align:left;"> Toast stock falls more than 11% after wider quarterly loss  - MarketWatch </td>
   <td style="text-align:left;"> Shares of Toast Inc. 
        TOST,
        +2.48%
       fell more than 11% in the extended session Tuesday after the restaurant-focused payments company reported a mixed quarter, showing a wider per-share loss in the fourth quarter than Wall Street expected but higher revenue. Toast said it earned $2 million, swinging from a net loss of $61 million in the fourth quarter of 2020. That resulted in a diluted per-share loss of 23 cents a share, compared with a loss of 31 cents a share in the year-ago quarter. Sales rose 111% to $512 million, Toast said. FactSet consensus called for an adjusted loss of 12 cents a share on sales of $488 million in the quarter. "The restaurant industry was tested again in 2021, but as evidenced by our growth there is tremendous demand for the Toast platform as restaurant operators navigate the new normal," Chief Executive Chris Comparato said in a statement. Toast guided for first-quarter revenue between $469 million and $499 million, and an adjusted loss between $65 million and $55 million. The analysts surveyed by FactSet call for first-quarter sales of $477 million. Toast became a public company in September.  


, Tesla Inc. Chief Executive Elon Musk donated more than 5 million Tesla shares to charity in November, days after the U.N. World Food Program outlined a plan to potentially use a $6 billion donation from the world's richest man, but the group has not received anything.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60393985?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-16 05:24:49 </td>
   <td style="text-align:left;"> Markets rally on hopes of Ukraine de-escalation </td>
   <td style="text-align:left;"> Global markets have rallied on hopes that military tensions over Ukraine could ease after Russia said it was recalling some of its troops from the country's border.                                                                         , Exchanges in Italy and Germany climbed roughly 2%, France's CAC 40 jumped 1.8% and London's FTSE 100 gained 1%.                                                                                                                              , The three major US indexes also closed more than 1% higher.                                                                                                                                                                                  , The gains follow a sell-off on  Monday after the US warned that Russia could invade Ukraine at any time.                                                                                                                                     , On Tuesday, US President Joe Biden said the reported troop withdrawals "would be good" but they had not been independently confirmed. He called a Russian attack "still very much a possibility".                                            , During his remarks, US markets dipped only to spring back. The Dow Jones Industrial Average gained 1.2%, while the S&amp;P 500 closed up more than 1.5% and the Nasdaq up nearly 2.6%.                                                           , The market rally comes after concerns about the conflict prompted shares to tumble.                                                                                                                                                          , The FTSE 100 plunged 1.7% on Monday, its worst session in three weeks, led by shares in travel companies, among the firms most exposed should Western sanctions on Russia or a war lead to higher oil prices.                                , On Tuesday, oil prices retreated, falling more than 4% at one point.                                                                                                                                                                         , In the US, aeroplane maker Boeing was one of the biggest winners on the Dow, up more than 3%. Travel companies, such as Expedia, United Airlines and American Airlines, helped power the rally on the S&amp;P 500.                               , The gains came despite new data showing worse-than-expected increases in producer prices, which could lead the Federal Reserve to move more aggressively to combat inflation.                                                                , In London, AstraZeneca led the market gains, rising more than 5% after saying it had seen positive results in trials for a drug in development, while mining giant Evraz, which has operations in Russia, was also up more than 4%.          , German Chancellor Olaf Scholz and Russian President Vladimir Putin met on Tuesday and discussed the Nord Stream 2 gas pipeline, which has been completed but not approved to open amid stiff opposition from the US and some European states., In comments at a press conference following the meeting, Mr Scholz said Germany was committed to ensuring that transit of gas works according to "according to the agreements we have," he said.                                             , He added: "We also want to ensure peaceful development in Europe, that there will be no military confrontation in Ukraine. If that is the case, it will have far-reaching consequences."                                                     , Behind the faces leading US far right political movements online                                                                                                                                                                             , Can her obsession drive her to finish what he couldn't?                                                                                                                                                                                      , Whitney Houston's extraordinary life story with insights from those closest to her                                                                                                                                                           , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/02/15/biden-russia-ukraine-not-a-threat-diplomacy-sot-vpx.cnn </td>
   <td style="text-align:left;"> 2022-02-16 05:14:37 </td>
   <td style="text-align:left;"> Video: Biden delivers message to Russia, says Ukraine is not a threat - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/bird-flu-outbreaks-put-us-poultry-farms-on-high-alert </td>
   <td style="text-align:left;"> 2022-02-16 05:09:33 </td>
   <td style="text-align:left;"> Bird flu outbreaks put US poultry farms on high alert </td>
   <td style="text-align:left;"> FAT Brands Inc. CEO Andrew Wiederhorn argues that he’s ‘hopeful’ chicken wing prices will go down after the Super Bowl and discusses how inflation is impacting the restaurant industry.                                                                                                                                                                                                                                       , U.S. poultry producers are on high alert after cases of highly pathogenic avian influenza (HPAI) have cropped up in multiple states, sparking fears that further outbreaks could cause significant losses.                                                                                                                                                                                                                     , Turkeys on a farm in Orefield, Pennsylvania, U.S., on Wednesday, Nov. 10, 2021. ( Photographer: Hannah Beier/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                                                                                        , The United States Department of Agriculture confirmed Feb. 9 that a commercial turkey flock in Indiana was hit with avian flu, the first case in the U.S. since 2020. The entire flock of nearly 30,000 birds was euthanized in an effort to stop the spread.                                                                                                                                                                  , Then on Feb. 14, the agency confirmed that a commercial flock of broiler chickens was hit with bird flu in Kentucky, and a backyard flock of mixed species fowl also tested positive in Virginia. Both flocks were culled.                                                                                                                                                                                                     , Tom Super, senior vice president of the National Chicken Council, told FOX Business that while any detection of bird flu "in poultry is a concern and the industry remains on high alert," the U.S. "has the most robust monitoring and surveillance program in the world – and detailed plans are in place to control spreading among flocks and eliminate the virus completely."                                             , Chickens at a farm in Gonzales, Texas, U.S., on Wednesday, May 5, 2021. (Photographer: Mary Kang/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                    , National Turkey Federation Vice President of Communications Beth Breeding told FOX Business that producers "are focused on farm security every day" and that "members remain vigilant and practice all biosecurity protocols."                                                                                                                                                                                                 , She said that "for farms within a 10km control zone of confirmed [bird flu] cases, regular testing is taking place to monitor the health of flocks."                                                                                                                                                                                                                                                                           , WITH MEAT PRICES RISING AGAIN, GROCERY CHAIN BUYS DIRECT FROM PRODUCERS                                                                                                                                                                                                                                                                                                                                                        , A spokesperson from the USDA told FOX Business that the agency recently expanded its wild bird surveillance after the first detection of HPAI in a wild bird in the U.S., and that the surveillance of wild birds ensures that both the agency and the poultry industry "are able to enhance biosecurity measures and rapidly respond to reduce the risk of disease spread."                                                   , The spokesperson said that "bird owners (whether it’s commercial or backyard poultry, or pet or hobby birds), should take some simple steps to protect their birds from the virus: In addition to practicing good biosecurity, all bird owners should prevent contact between their birds and wild birds and report sick birds or unusual bird deaths to state or federal officials."                                          , Freshly-laid chicken eggs in baskets before being washed and packaged for sale at a farm in Pleasureville, Kentucky, U.S., on Wednesday, Jan. 8, 2020. (Photographer: Luke Sharrett/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                 , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                    , The risk of humans contracting bird flu is very low, and any flock found to have an infected bird does not enter the food chain. The virus also does not present a food safety risk as long as food is properly cooked, but it has the potential of being deadly to domestic fowl and threatens to spark shortages of chicken, turkey and eggs – along with a further increase in prices for such items amid soaring inflation., According to the Associated Press, the bird flu strain currently circulating in the U.S. is H5N1, and is related to the 2015 avian virus that killed 50 million birds across 15 states and cost the federal government nearly $1 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-16 05:09:00 </td>
   <td style="text-align:left;"> US Stocks Rebound Solidly on Tuesday </td>
   <td style="text-align:left;"> All three major US stock indexes rebounded after three straight sessions of losses on Tuesday, with the Dow Jones closing 421 points higher, the S&amp;P 500 up 1.6%, and the Nasdaq outperformed with a 2.5% gain, as fears of an imminent war in Europe eased. President Putin said he intends to negotiate security guarantees through diplomatic channels, while some Russian military districts units have completed their exercises and started pulling back to bases. Meanwhile, the Fed’s looming tightening cycle took a secondary stage, even as producer prices rose faster than expected. Across sectors, industrials, tech, and basic materials led gains, while energy stocks and utilities ended lower. On the earnings front, Marriott International Inc. Q4 results beat market expectations, underpinned by leisure travel. Traders are now awaiting the FOMC minutes on Wednesday for clues about the timing and scale of future rate hikes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/stocks-end-sharply-higher-ukraine/story.aspx?guid={D05365BE-1C99-4E4B-A75B-81DD3F4E2CE0}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-16 05:06:14 </td>
   <td style="text-align:left;"> Stocks end sharply higher as Ukraine tensions show tentative signs of easing - MarketWatch </td>
   <td style="text-align:left;"> Stocks finished sharply higher Tuesday, with major indexes snapping a three-day losing streak, as Russia said it was pulling back some troops from the border with Ukraine after concluding military exercises. The Dow Jones Industrial Average 
        DJIA,
        +1.22%
       rose around 422 points, or 1.2%, to finish near 34,988, according to preliminary figures, while the S&amp;P 500 
        SPX,
        +1.58%
       gained around 69 points, or 1.6%, to close near 4,471. The Nasdaq Composite 
        COMP,
        +2.53%
       jumped nearly 350 points, or 2.5%, ending near 14,140. Worries over a potential Russian invasion of Ukraine had dogged equities in recent sessions. Analysts said it was too soon to sound the all-clear signal on Ukraine. Speaking at the White House, President Joe Biden said that the U.S. had not verified that Russian units had returned home. An invasion remains "distinctly possible," the president said., The world's biggest hedge fund boosted its bet on Chinese companies in the fourth quarter.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , William Watts is MarketWatch’s senior markets writer. Based in New York, Watts writes about stocks, bonds, currencies and commodities, including oil. He also writes about global macro issues and trading strategies. Before moving to New York, he reported for MarketWatch from Frankfurt, London and Washington, D.C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/capital-flows </td>
   <td style="text-align:left;"> 2022-02-16 05:03:00 </td>
   <td style="text-align:left;"> US Net Capital Flows Fall the Most in 15 Months </td>
   <td style="text-align:left;"> The United States recorded a capital and financial account deficit of USD 52.4 billion in December of 2021, following a downwardly revised USD 216.8 billion in the previous month. It was the largest capital outflow since September of 2020. Foreign investors bought USD 12.0 billion in Treasuries, compared with an inflow of USD 12.8 billion in November. Meanwhile, foreigners bought USD 76.9 billion of long-term US securities, after purchasing USD 103.4 billion in the previous month. Additionally, US residents acquired USD 37.6 billion in foreign securities, USD 3.1 billion more than in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-16 04:30:15 </td>
   <td style="text-align:left;"> The Dow Jones Index rising 1.11% </td>
   <td style="text-align:left;"> United States Stock Market is gaining 383 points. Leading the gains are Boeing (3.42%), Salesforce.com (3.32%) and Nike (2.65%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/us-natural-gas-producer-says-prices-surging-due-to-lack-of-adequate-pipeline-structure </td>
   <td style="text-align:left;"> 2022-02-16 04:01:24 </td>
   <td style="text-align:left;"> US natural gas producer says prices are surging due to lack of adequate pipeline structure </td>
   <td style="text-align:left;"> FOX Business' Lydia Hu explores the impact of rising gas prices as EQT CEO Toby Rice argues the solution is more infrastructure.                                                                                                                                                                                           , As tension between Russia and Ukraine intensifies, Europe’s natural gas supply is especially vulnerable, leaving U.S. prices at risk of escalating.                                                                                                                                                                        , FOX Business’ Lydia Hu visited independent natural gas producer EQT in East Millsboro, Pennsylvania, Tuesday, where she spoke with CEO Toby Rice, who suggested the fix to high natural gas prices is increased production and investment in ‘adequate’ infrastructure.                                                    , "It’s because of the lack of adequate pipeline infrastructure," he said. "People need to be aware that we want to do more. Natural gas prices here in Pennsylvania -- $3.50 – well below what anybody’s paying in the northeast. We need more pipeline infrastructure."                                                    , WARMER WEATHER WILL SEND GAS PRICES SOARING ‘A LOT HIGHER,’ ANALYST WARNS                                                                                                                                                                                                                                                  , EQT pointed to four pipeline projects that have been canceled since 2016, which could have served more than 25 million homes. According to Rice, these nixed projects have restricted nearly 10% of the nation’s natural gas.                                                                                              , The CMA CGM SA Jacques Saade liquid natural gas (LNG) powered container ship docked with cargo at the Port of Le Havre in Le Havre, France, on Thursday, Jan. 21, 2021. Photographer: Nathan Laine/Bloomberg via Getty Images                                                                                              , Rice expressed that people should be "very upset" about the price they’re paying to heat their homes, and that failing to implement more U.S. infrastructure will only strengthen America’s dependence on foreign energy.                                                                                                  , Sen. Elizabeth Warren, D-Mass., alongside other Democratic lawmakers, have recently called on the Department of Energy to cut exports of liquefied natural gas in an attempt to calm pricing.                                                                                                                              , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                , "We can’t let energy companies squeeze American consumers with unaffordable energy bills at home while reaping record profits through LNG exports abroad," Warren said in a statement. "The Department of Energy needs to reevaluate its LNG export policies and figure out how to keep prices low for American consumers.", Snow covered transfer lines leading to storage tanks at the Dominion Cove Point Liquefied Natural Gas (LNG) terminal in Lusby, Maryland, March 18, 2014. REUTERS/Gary Cameron                                                                                                                                              , But Rice and other energy analysts tell Hu that this approach is not right as prices are set regionally, so most exports occurring from the Gulf Coast would have no impact on sky-high prices in New England.                                                                                                             , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                    , According to the U.S. Bureau of Labor Statistics [BLS], consumers are spending nearly 24% more on natural gas compared to last year while storage volumes are about 17% lower year over year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/marriotts-2021-workforce-declined-1000/story.aspx?guid={16C2EFAD-F636-4FC8-AF74-20B4F8BB6E61}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-16 03:56:34 </td>
   <td style="text-align:left;"> Marriott's 2021 workforce declined by 1,000 employees, has dropped 31% in two years - MarketWatch </td>
   <td style="text-align:left;"> Marriott International Inc. 
        MAR,
        +5.76%
       disclosed Tuesday that it had 120,000 employees at the end of 2021, including 97,000 employees in the U.S., according to the hotel operators 10-K filing with the Securities and Exchange Commission. That's down 0.8% from 121,000 employees at the end of 2020, which included 98,000 U.S. employees. The hotel operator's workforce has now declined 31.0% in two years, from 174,000 in pre-pandemic 2019. The company also reported earlier Tuesday 2021 revenue of $13.86 billion, up 31.1% from 2020 but down 33.9% from 2019. The stock surged 5.0% in afternoon trading toward a record close. It has run up 15.6% over the past three months, while the S&amp;P 500 
        SPX,
        +1.58%
       has lost 4.7%., An environmental conservation group and two dozen outdoor recreation companies, including Patagonia, REI and The North Face, announced Monday they would boycott the Outdoor Retailer trade show if it's moved from Denver back to Salt Lake City.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-oil-futures-drop-nearly/story.aspx?guid={1F564D67-8004-44BC-BEE8-6B86AA0F47B8}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-16 03:39:13 </td>
   <td style="text-align:left;"> U.S. oil futures drop by nearly 4% - MarketWatch </td>
   <td style="text-align:left;"> Oil futures declined on Tuesday, as some concerns over the Russia-Ukraine crisis eased, pulling U.S. prices down by almost 4%. "We estimate that oil prices are $10-$20 higher than they should be because of uncertainty surrounding Russia/Ukraine," said David Bahnsen, chief investment officer at The Bahnsen Group. "With oil prices in the $90s, demand may start to erode." Still, prices in the mid-$70s per barrel "could become a new baseline, given the current supply and demand dynamic," he said in market commentary. West Texas Intermediate crude for March delivery 
        CLH22,
        +0.40%
       fell $3.39, or nearly 3.6%, to settle at $92.07 a barrel on the New York Mercantile Exchange., President Volodymyr Zelensky of Ukraine had downplayed reports that Russia could attack Ukraine "any day now."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/heating-oil </td>
   <td style="text-align:left;"> 2022-02-16 03:37:44 </td>
   <td style="text-align:left;"> Heating Oil Futures Fall from 2014 Highs </td>
   <td style="text-align:left;"> Heating oil futures fell more than 3% from 7-1/2-year highs to $2.9 a gallon on Tuesday, in line with crude oil futures, as investors digested de-escalating tensions over Eastern Europe. President Putin told German Chancellor Olaf Scholz that his country intends to negotiate with its Western partners on security guarantees through diplomatic channels, following news that Russia pulled back some military district units that have completed exercises. Still, oil producing nations’ inability to meet agreed output targets limited losses. Elsewhere, the Iran nuclear talks seemed to have advanced according to Russia’s Foreign Minister, which could allow millions of barrels of Iranian oil to return to global markets, if the 2015 deal is brought back. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/carnival-ceo-arnold-donalds-total/story.aspx?guid={0F0E5785-6398-40F3-84DC-508BA0D7F312}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-16 03:25:25 </td>
   <td style="text-align:left;"> Carnival CEO Arnold Donald's total compensation increased 13% in 2021, and 35% the past 2 years - MarketWatch </td>
   <td style="text-align:left;"> Cruise operator Carnival Corp. 
        CCL,
        +6.65%
        CCL,
        +3.12%
       disclosed Tuesday that Chief Executive Arnold Donald's total compensation in 2021 was $15.06 million, including $1.50 million in salary, $7.45 million in stock awards and $6.00 million in non-equity incentive plan compensation. Donald's total compensation increased 13.2% from $13.31 million in 2020, which included $857,413 in salary and $12.23 million in stock awards. Donald's 2020 salary was down from $1.5 million in 2019 as the COVID-19 pandemic led to salary reductions, but his total 2020 compensation was up 19.3% from $11.15 million in pre-pandemic 2019. Meanwhile, Carnival's stock fell 7.1% in 2021 and tumbled 57.4% in 2020, for a total two-year decline of 60.4%. In comparison, Donald's total compensation increased 35.1% over the past two years. Carnival's stock, which surged 6.4% in afternoon trading, is now up 12.9% year to date, while the S&amp;P 500 
        SPX,
        +1.58%
       has slipped 6.4% this year., An environmental conservation group and two dozen outdoor recreation companies, including Patagonia, REI and The North Face, announced Monday they would boycott the Outdoor Retailer trade show if it's moved from Denver back to Salt Lake City.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-02-16 03:24:00 </td>
   <td style="text-align:left;"> WTI Futures Slip from Over 7-Year Highs </td>
   <td style="text-align:left;"> Oil markets fell from over seven-year highs on Tuesday, with WTI futures losing as much as 4.5% before paring losses at $91.8 per barrel, as tensions on the Russia Ukraine border started to de-escalate. President Putin told German Chancellor Olaf Scholz that his country intends to negotiate with its Western partners on security guarantees through diplomatic channels, while Russia’s Defense Minister stated that troops of the Southern and Western districts were heading back to their bases. Elsewhere, the Iran nuclear talks seemed to have advanced according to Russia’s Foreign Minister, as a potential deal could release about 1.3 million supply barrels. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-futures-fall-back-day/story.aspx?guid={63D6FE84-A0F2-4503-A635-D52A8294C20B}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-16 02:42:35 </td>
   <td style="text-align:left;"> Gold futures fall back a day after posting a 3-month high - MarketWatch </td>
   <td style="text-align:left;"> Gold futures declined on Tuesday as some concerns surrounding a possible Russian invasion of Ukraine eased, dulling demand for the metal as a haven investment. Gold prices fell, in part, due to a possible Russia-Ukraine "pullback from brink of war, but one day does not end a crisis of this magnitude," said Jeff Wright, chief investment officer at Wolfpack Capital. April gold 
        GCJ22,
        -0.15%
       fell $13.20, or 0.7%, to settle at $1,856.20 an ounce. , President Volodymyr Zelensky of Ukraine had downplayed reports that Russia could attack Ukraine "any day now."                                                                                                                                                                                                                                                                                                                                                                            , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/financials/donald-trumps-annual-financial-statements-unreliable-accounting-firm-says </td>
   <td style="text-align:left;"> 2022-02-16 02:18:56 </td>
   <td style="text-align:left;"> Donald Trump’s annual financial statements ‘should no longer be relied upon,’ accounting firm says </td>
   <td style="text-align:left;"> Rep. Ted Budd, R-N.C., addresses new Durham investigation evidence accusing Hillary Clinton of spying on Trump.                                                                                                                                                                                                                                                                                                            , The accounting firm that prepared former President Donald Trump’s annual financial statements says the documents, used to secure lucrative loans and burnish Trump's image as a wealthy businessman, "should no longer be relied upon" after New York's attorney general said they regularly misstated the value of assets.                                                                                                , In a letter to the Trump Organization's lawyer Feb. 9, Mazars USA LLP advised the company to inform anyone who had gotten the documents not to use them when assessing the financial health of the company and the ex-president. The firm also said it was cutting ties with Trump, its highest-profile client.                                                                                                            , Mazars' letter, made public in a court filing Monday, came just weeks after New York Attorney General Letitia James said her civil investigation uncovered evidence that Trump and his company used "fraudulent or misleading" valuations of its golf clubs, skyscrapers and other properties to get loans and tax benefits.                                                                                               , Former President Donald Trump holds up papers as he speaks about the coronavirus in the James Brady Press Briefing Room of the White House on April 20, 2020, in Washington, D.C. (Associated Press)                                                                                                                                                                                                                       , TRUMP ‘TRUTH SOCIAL’ APP LAUNCH EXPECTED BY END OF MARCH, SOURCES SAY                                                                                                                                                                                                                                                                                                                                                      , "While we have not concluded that the various financial statements, as a whole, contain material discrepancies, based upon the totality of the circumstances, we believe our advice to you to no longer rely upon those financial statements is appropriate," Mazars General Counsel William J. Kelly wrote to his Trump Organization counterpart, Alan Garten.                                                            , Kelly told Garten that Mazars could no longer work with Trump because of a conflict of interest and urged him to find another tax preparer. Kelly said several Trump-related tax returns still needed to be finished, including those of the former president and first lady.                                                                                                                                              , The Trump Organization said in a statement it was "disappointed that Mazars has chosen to part ways," but took Kelly's letter as a positive because the accounting firm hadn’t found material discrepancies in Trump’s financial statements.                                                                                                                                                                               , The letter "confirms that after conducting a subsequent review of all prior statements of financial condition, Mazars’ work was performed in accordance with all applicable accounting standards and principles and that such statements of financial condition do not contain any material discrepancies," the Trump Organization said. "This confirmation effectively renders the investigations by the DA and AG moot." , Kelly said Mazars performed its work on Trump’s financial statements "in accordance with professional standards" but that it could no longer stand by the documents in light of James’ findings and its own investigation. Kelly said Mazars’ conclusions applied to Trump’s 2011-2020 financial statements. Another firm handled Trump’s 2021 financial statement.                                                        , Former White House deputy press secretary Hogan Gidley and ex-strategic communications director Mercedes Schlapp react to the Durham probe findings that Trump was spied on on 'Kudlow.'                                                                                                                                                                                                                                   , TRUMP SAYS GETTING TOUGH ON CRIME IS NO. 1 ISSUE                                                                                                                                                                                                                                                                                                                                                                           , James' office included a copy of Kelly's letter in a court filing as she seeks to enforce a subpoena to have Trump and his two eldest children, Donald Jr. and Ivanka, testify under oath. A state court judge, Arthur Engoron, is scheduled to hear arguments Thursday in the subpoena dispute.                                                                                                                           , James, a Democrat, said Monday that given the evidence, "there should be no doubt that this is a lawful investigation and that we have legitimate reason" to question Trump, a Republican, and his children, both of whom have been Trump Organization executives.                                                                                                                                                         , Trump’s lawyers have argued that any testimony they give could be used against them in a parallel criminal investigation being overseen by the Manhattan district attorney’s office — a probe that led to tax fraud charges last year against the Trump Organization and Allen Weisselberg, its longtime chief financial officer.                                                                                          , Trump has given his Statement of Financial Condition — a yearly snapshot of his holdings — to banks to secure hundreds of millions of dollars worth of loans on properties such as a Wall Street office building and a Florida golf course, and to financial magazines to justify his place among the world's billionaires.                                                                                                , In a court filing last month, James’ office detailed several instances in which Trump misstated the value of assets on financial statements given to banks.                                                                                                                                                                                                                                                                , A woman walks past the Trump Building in New York's financial district on Jan. 13, 2021.  (AP/Mark Lennihan)                                                                                                                                                                                                                                                                                                               , CHINA STIFFED US ON TRUMP PHASE 1 TRADE AGREEMENT, FAILED TO BUY EXTRA $200 BILLION IN EXPORTS                                                                                                                                                                                                                                                                                                                             , Deutsche Bank accepted Trump’s financial statements without objection in a deal for $300 million in loans for three of his properties and, in internal memoranda, emphasized Trump’s reported financial strength as a factor in lending to him, James’ office said.                                                                                                                                                        , Another bank said it received financial statements in 2014 stating Trump had a net worth of $5.8 billion and liquidity of $302 million. A bank official involved in that deal told James’ office that if he were aware of misstatements on Trump’s statement of financial condition, he would have killed the deal.                                                                                                        , James office said its investigation started after Trump's former personal lawyer, Michael Cohen, told Congress in 2019 that Trump had a history of misrepresenting the value of assets to gain favorable loan terms and tax benefits.                                                                                                                                                                                      , Cohen gave copies of three of Trump’s financial statements to the House Committee on Oversight and Reform. Cohen said Trump gave the statements to Deutsche Bank to inquire about a loan to buy the NFL’s Buffalo Bills and to Forbes magazine to substantiate his claim to a spot on its list of the world’s wealthiest people.                                                                                           , Cohen served time in federal prison after pleading guilty in 2018 to tax crimes, lying to Congress and campaign finance violations, some of which involved his role in orchestrating payments to two women to keep them from talking about alleged affairs with Trump.                                                                                                                                                     , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                    , Trump's lawyers have portrayed Cohen as having a vendetta against Trump and said in a recent court filing that it "stretches all credibility to believe that" James' office put "any legitimate stock" in his testimony.                                                                                                                                                                                                   , James' office responded Monday that not only did it rely on Cohen's testimony, but that his testimony is "vindicated by the evidence obtained to date and Mazars’s notification that those statements should not be relied upon."  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ireland/balance-of-trade </td>
   <td style="text-align:left;"> 2022-02-16 02:04:00 </td>
   <td style="text-align:left;"> Irish Trade Surplus Narrows in December </td>
   <td style="text-align:left;"> Ireland’s trade surplus narrowed to EUR 2.45 billion in December 2021, the lowest since November of 2014 from EUR 3.35 billion in the corresponding period of 2020. Imports increased by 18 percent to EUR 10.61 billion, the highest on record, mainly driven by transport equipment, including aircraft (19 percent to EUR 345 million), petroleum (139 percent to EUR 261 million), organic chemicals (55 percent to EUR 393) and electrical machinery, appliances, apparatus, and parts (124 percent to EUR 704 million). Purchases from the EU rose by 33 percent, while those from Great Britain fell by 13 percent. In the meantime, exports rose at a softer 6 percent to EUR 10.09 billion, driven by medical and pharmaceutical products (11 percent to EUR 4.6 million), and electrical machinery, appliances, and parts (58 percent to EUR 1.16 million). Sales to the EU rose by 6 percent, while those to Great Britain fell 5 percent. Considering the full 2021, Ireland recorded a trade surplus of EUR 67.522 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/inflations-grip-tightens-in-mountain-states-midwest-as-consumer-prices-surge </td>
   <td style="text-align:left;"> 2022-02-16 01:55:42 </td>
   <td style="text-align:left;"> Inflation's grip tightens in Mountain states, Midwest as consumer prices surge higher </td>
   <td style="text-align:left;"> Congressional correspondent Chad Pergram has the details on 'Cavuto: Coast to Coast.'                                                                                                                                                                                                                                                                                                                , American consumers are grappling with the hottest inflation in a generation, and some parts of the country are seeing steeper price increases than others.                                                                                                                                                                                                                                           , The consumer price index rose 7.5% in January from a year ago, according to a Labor Department report released last week, marking the fastest increase since February 1982, when inflation hit 7.6%. The CPI – which measures a bevy of goods, ranging from gasoline and health care to groceries and rents – jumped 0.6% in the one-month period from December.                                     , JANUARY INFLATION BREAKDOWN: WHERE ARE PRICES RISING THE FASTEST?                                                                                                                                                                                                                                                                                                                                    , But the increase was starkest in the region that encompasses Montana, Wyoming, Idaho, Nevada, Utah, Colorado, Arizona and New Mexico, with prices surging by a staggering 9%.                                                                                                                                                                                                                        , Other states are also experiencing inflation that's well above the national average: Prices were up 7.9% in a slew of states, including North Dakota, South Dakota, Nebraska, Kansas, Minnesota, Iowa, Maryland, West Virginia, North Carolina, South Carolina, Georgia, Florida, Texas, Oklahoma, Louisiana, Arkansas, Missouri, Illinois, Wisconsin, Indiana, Michigan and Ohio.                   , By comparison, prices in the mid-Atlantic – New York, New Jersey and Pennsylvania – were far lower, climbing 6.1% in January from the year-ago period. The New England region experienced the next-lowest rates with 6.6% inflation.                                                                                                                                                                 , Rising inflation is eating away at strong wage gains that American workers have seen in recent months: Real average hourly earnings rose just 0.1% in January from the previous month, as the 0.6% inflation increase eroded the 0.7% total wage gain, according to the Labor Department. On an annual basis, real earnings actually declined 1.7% in January.                                       , The average American is shelling out an extra $276 a month on goods and services because of inflation, according to a new Moody's Analytics analysis.                                                                                                                                                                                                                                                , The inflation spike has been bad news for President Biden, who has seen his approval rating plunge as consumer prices rose. The White House has blamed the price increases on supply-chain bottlenecks and other pandemic-induced disruptions in the economy, while Republicans have pinned it on the president's massive spending agenda.                                                           , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                          , Following the data release, Biden acknowledged that higher inflation is creating more financial stress for American families. But he claimed there are "signs that we will make it through this challenge."                                                                                                                                                                                          , "It's a real bump in the road," he told reporters at the White House. "It does affect families when you walk into a grocery store and you're paying more for whatever you're purchasing. It matters to people when you're paying more for gas, although in some states we've got the price down below three bucks a gallon, but the point is it's not gone down quickly enough. But I think it will." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/facebook-owner-meta-changes-news/story.aspx?guid={296DB9B9-5F8A-47AD-BD64-E73A6EEEE610}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-16 01:54:18 </td>
   <td style="text-align:left;"> Facebook owner Meta changes News Feed to 'Feed' - MarketWatch </td>
   <td style="text-align:left;"> Facebook parent Meta Platforms Inc. 
        FB,
        +1.52%
       on Tuesday said it has shortened the name of its News Feed to Feed. "This is just a name change to better reflect the diverse content people see on their Feeds," a company spokesperson said in an email to MarketWatch. "This is just a name change and does not impact the app experience more broadly." Meta announced the name change in a tweet on Twitter Inc. 
        TWTR,
        +3.61%.
      , Tesla Inc. Chief Executive Elon Musk donated more than 5 million Tesla shares to charity in November, days after the U.N. World Food Program outlined a plan to potentially use a $6 billion donation from the world's richest man, but the group has not received anything.                                                                                                                                                                                                            , Jon Swartz is a senior reporter for MarketWatch in San Francisco, covering many of the biggest players in tech, including Netflix, Facebook and Google. Jon has covered technology for more than 20 years, and previously worked for Barron's and USA Today. Follow him on Twitter @jswartz. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/15/stocks-making-the-biggest-moves-midday-moneygram-constellation-brands-marriott-and-more-.html </td>
   <td style="text-align:left;"> 2022-02-16 01:46:16 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: MoneyGram, Constellation Brands, Marriott and more </td>
   <td style="text-align:left;"> , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                                                                                                          , MoneyGram International — The global remittance company's shares surged by 19.5% following news that the private equity firm Madison Dearborn Partners will acquire MoneyGram in a deal valued at about $1.8 billion.                                                                                                                                                                                , Fidelity National Information — Financial services technology firm FIS fell more than 7.8% and was one of the top decliners in the S&amp;P 500 after reporting results for the most recent quarter. Revenue came in at $3.67 billion, compared to FactSet estimates of $3.71 billion. Current-quarter earnings and revenue guidance fell short of estimates as well.                                     , Constellation Brands — The alcoholic beverage maker's shares fell 6% following a Bloomberg News report that discussions of a merger with Monster Beverage are progressing and that an agreement between the two companies could be reached within weeks. Monster shares ticked up slightly.                                                                                                          , Arista Networks — Shares jumped 5.8% after the software company reported quarterly earnings of 82 cents per share, which was 9 cents higher than analysts' estimates. The company also reported a revenue beat and issued an upbeat forecast.                                                                                                                                                        , Marriott International — Shares of the hotel chain jumped 5.7% after Marriott beat estimates on the top and bottom lines for the fourth quarter. The company reported $1.30 in adjusted earnings per share on $4.45 billion of revenue, powered by the continued recovery in global travel. Analysts surveyed by Refinitiv were expecting 99 cents in earnings per share on $3.96 billion of revenue., Avis Budget Group — The car rental company saw its shares fall 12% even after it posted a better-than-expected profit and revenue for its latest quarter and showed increases in rental activity and in revenue per day that helped offset higher expenses. For the quarter, Avis earned $7.08 per share, beating a Refinitiv estimate of $6.15 per share.                                           , General Electric — Shares of the industrial conglomerate rose 4.4% after Bank of America reiterated its buy rating on the stock, as GE continues to make progress in reducing legacy issues, the firm said Tuesday. Those issues include the end of factoring repayment, normal pension levels, lower long-term care risks, declining corporate costs and decreased cash restructuring.              , Airbnb — The stock rose 6.1% after KeyBanc reiterated its overweight rating on the company ahead of its earnings report Tuesday afternoon. "While we believe there is some risk to near-term bookings growth from omicron headwinds, we believe pent-up demand for U.S. and international travel can lead to further revenue and EBITDA upside in 2022E," analysts at KeyBanc said.                  , Restaurant Brands International — Shares of the restaurant operator gained 3.5% after the company reported its most recent quarterly results. Its earnings came in at 74 cents per share, beating estimates by 4 cents, and it scored a revenue beat. The company also reported a beat in comparable-store sales for Burger King.                                                                    , Oil stocks — Shares of oil companies were some of the top decliners Tuesday as oil prices dropped from a 7-year high on a report that tensions between Ukraine and Russia appeared to be easing. Occidental fell 3.3%, while Marathon lost 2.8%. Diamondback and Devon Energy each slipped by more than 1%.                                                                                          ,  — CNBC's Hannah Miao and Jesse Pound contributed reporting.                                                                                                                                                                                                                                                                                                                                         , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                               , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                               , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                     , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                     , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                   , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-02-16 01:36:48 </td>
   <td style="text-align:left;"> Madrid Shares Close Higher on Tuesday </td>
   <td style="text-align:left;"> The Ibex 35 rose 1.7% to close at 8,721 on Tuesday, partially rebounding from the last session’s 2.6% decline as investors weighed on signs of eased military risk in the Russian border with Ukraine after the Kremlin said that some of its units were returning to their bases. On the corporate front, gains were led by Siemens Gamesa (6.7%) as investors weighed on the restructuring efforts by the wind turbine manufacturer. At the same time, Rovi shares jumped 4.8% after the European Commission authorized the marketing for Okedi, the drug maker’s new schizophrenia treatment. On the data front, January's domestic consumer inflation was revised higher to 6.1%, although still easing from December's near 30-year high of 6.5% and the first decrease in price growth since February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-16 01:28:00 </td>
   <td style="text-align:left;"> Canada 10Y Bond Yield Hits 3-year High </td>
   <td style="text-align:left;"> The yield on Canada's 10-year government bond extended gains towards 2% in mid-February, a level not seen since January of 2019 and tracking global peers, as traders digested economic data and de-escalating tensions in Eastern Europe. On the data front, Canadian home prices rose to unprecedented levels in January, despite seeing fewer new listings, while US producer prices rose faster than expected in the same period. Traders now await Canada’s headline inflation reading for January, which will offer some insight into the Bank of Canada’s monetary policy outlook. Market participants bet on a rate hike next month, the first out of six already priced in for the whole year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gasoline </td>
   <td style="text-align:left;"> 2022-02-16 01:23:09 </td>
   <td style="text-align:left;"> Gasoline Futures Ease from Over 7-Year High </td>
   <td style="text-align:left;"> US gasoline futures pulled back below $2.7 a gallon on Tuesday from an over seven-year high of $2.79 reached last session, amid a broad rout in commodities, as tensions at the Russia-Ukraine border eased. President Putin told German Chancellor Olaf Scholz that his country intends to negotiate with its Western partners on security guarantees through diplomatic channels, while Russia’s Foreign Minister stated that troops of the Southern and Western districts were heading back to their bases. Still, oil producing nations’ inability to meet agreed output targets limited losses. Elsewhere, traders continued to monitor US-Iran talks about the revival of the 2015 nuclear deal, which could allow millions of barrels of Iranian oil to return to global markets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/israel/inflation-cpi </td>
   <td style="text-align:left;"> 2022-02-16 01:14:00 </td>
   <td style="text-align:left;"> Israel January Inflation Rate at Near 10-1/2-Year High </td>
   <td style="text-align:left;"> Israel’s annual inflation rate quickened for the third straight month to 3.1% in January of 2022, from 2.8% in December, above market expectations of 2.9% and the Bank of Israel's annual target range for inflation of 1% to 3%. It was the highest rate since August of 2011, due to upward pressure from furnishings (8.3%); food excluding vegetables &amp; fruits (4.5%); housing (3.2%); transport (3.2%); and education, culture and entertainment (2.9%). On the other hand, prices fell for clothing &amp; footwear (-2.5%). On a monthly basis, consumer prices edged up 0.2%, following a 0.3% rise in December and against market forecasts of a 0.1% drop. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/15/education-department-wont-seize-tax-refunds-for-overdue-student-loans.html </td>
   <td style="text-align:left;"> 2022-02-16 01:07:54 </td>
   <td style="text-align:left;"> Education Department suspends seizure of tax refunds, Social Security for overdue student loans until November </td>
   <td style="text-align:left;"> , The U.S. Department of Education has suspended the seizure of tax refunds, Social Security and other government payments to satisfy defaulted student loans until November, the agency said.                                                                                                                                     , About 9 million people have a federal student loan in default, which means they've fallen at least 270 days behind on payments.                                                                                                                                                                                                  , The Education Department — as well as other federal and state agencies — can collect on delinquent debt via the Treasury Offset Program, which intercepts certain payments to recover the owed funds.                                                                                                                            , Borrowers have gotten a reprieve during the Covid-19 pandemic due to a federal pause on loan payments, interest and collection.                                                                                                                                                                                                  , But that policy ends after May 1, fueling concern among consumer advocates that the government would seize tax refunds issued after that date, including benefits like the earned income, child and Recovery Rebate tax credits aimed at low-income households.                                                                  , However, the Education Department will not restart collection via the Treasury Offset Program for six months after the Covid-19 payment pause ends, according to its Federal Student Aid website. That would be after Nov. 1, if the pause isn't extended again.                                                                 , More from Personal Finance:Is college really worth it? Why it's hard to figure out the return on investmentWhy your tax return may get rejected if last year's is still pending3 timely ways to spend your tax refund this year                                                                                                  , It appears the department updated its policy last week, though the precise timing is unclear. An agency spokesperson didn't respond to a request for comment.                                                                                                                                                                    , "This policy means you won't lose money from certain government payments, such as the child tax credit, Social Security payments, and tax refunds for the 2022 tax season," according to the agency website.                                                                                                                     , It builds on a narrower policy announcement last week that applied only to payments of the child tax credit. After a CNBC inquiry, Education Secretary Miguel Cardona said Feb. 8 that the agency wouldn't withhold any tax refunds attributed to the child tax credit, even after May 1.                                        , "The intent of these social safety net programs is to protect and prevent people in the U.S. from experiencing crushing poverty — not a reconciliation system for the federal government to use for the student loan portfolio," said Abigail Seldin, who runs a charitable foundation that focuses on access to public services., In 2019, the Treasury Offset Program collected nearly $4.9 billion to service debts held by the Education Department, according to a foundation analysis of publicly available data.                                                                                                                                             , That would be about 78% of the total $6.3 billion in delinquent nontax debt collected that fiscal year.                                                                                                                                                                                                                          , The government is allowed to seize 100% of federal tax refunds to collect debts associated with child support, unemployment insurance and state income taxes. It can also withhold up to 65% of federal salaries and up to 15% of Social Security payments, for example.                                                         , However, certain payments, including those of many means-tested programs, are exempt from offset. The Treasury must also provide 60-day prior notice to the debtor of the intent to offset.                                                                                                                                      , Student borrowers in default will remain vulnerable past Nov. 1, added Seldin, who was a candidate to oversee student loans for the Biden administration.                                                                                                                                                                        , Default disproportionately impacts borrowers of color, particularly African Americans, as well as students with children, Pell Grant recipients and veterans, according to the Center for American Progress.                                                                                                                     , Seizing tax refunds from borrowers in default would have run contrary to the poverty-fighting measures of the American Rescue Plan, according to consumer advocates. The pandemic-relief law, which President Joe Biden signed in March, enhanced tax benefits like the earned-income and child tax credits.                     , Even prepandemic, withholding the earned-income credit, which goes to low-income working families, causes or exacerbates housing and financial instability and impairs workers' ability to get and keep jobs, according to the National Consumer Law Center.                                                                     , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                           , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                           , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                 , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                 , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                               , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/us/2022/02/15/prince-andrew-virginia-giuffre-sexual-abuse-lawsuit-settlement-vpx.cnn </td>
   <td style="text-align:left;"> 2022-02-16 01:03:14 </td>
   <td style="text-align:left;"> Prince Andrew settles sexual abuse lawsuit with Jeffrey Epstein accuser Virginia Giuffre - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/15/tech/3g-network-shut-down/index.html </td>
   <td style="text-align:left;"> 2022-02-16 00:57:47 </td>
   <td style="text-align:left;"> The 3G network shutdown will impact more than just phones - CNN </td>
   <td style="text-align:left;"> (CNN)The looming shutdown of 3G networks won't just impact older phones.                                                                                                                                                                                                                                                                                                                                                                                                                  , With AT&amp;T's 3G network shutting down next week, and other carriers following suit later this year, a range of products require updates to continue working, including some home alarm systems, medical devices such as fall detectors, and in-car crash notification and roadside assistance systems such as General Motors' OnStar.                                                                                                                                                       , Just as many mobile carriers have urged customers to swap their older 3G iPhones, Android phones, e-readers and other handheld devices for newer models ahead of the shutdown, other businesses are urging customers to upgrade or replace some of the everyday products and services in their homes and cars before they drop connectivity.                                                                                                                                               , If left unaddressed, the stakes could be high in certain cases. Millions of cars, for example, may no longer have the ability to contact first responders after a collision or receive updates such as location or traffic alerts for built-in GPS systems. Some vehicles, including Chevrolet, Buick and Cadillac, have software upgrades for drivers to connect their systems to a 4G network, but other models will reportedly lose this feature for good.                              , The introduction of 3G in 2002 allowed some early car infotainment systems and home security services -- pioneers in the smart home space -- to connect to the networks. But over time, wireless companies moved on to 4G and more recently 5G networks.                                                                                                                                                                                                                                   , Now, the major carriers are phasing out 3G technology in the United States and some markets abroad. AT&amp;T (T), which owns CNN's parent company, is shutting it down on February 22; T-Mobile (TMUS) is doing so in the third quarter; and Verizon (VZ) will take this step by the end of the year. As the technology officially becomes obsolete, a scramble is underway to help consumers avoid a disruption.                                                                              , What companies are doing about it                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Some industries are better set up to handle the change. Many home security companies, for example, have been migrating their subscriber bases from 3G to 4G over the past two years. "From the most recent industry discussions I've participated in, it appears most US home security dealers have migrated 100% or very close to 100% of their subscribers so it's not on most providers' to-do lists any longer," said Jack Narcotta, principal industry analyst at Strategy Analytics. , He said the home security industry's effort to transition to 4G wasn't overly complicated because it simply involved having a technician install a box or panel for a newer model. Some companies such as ADT have also put additional resources into the transition. In 2020, the home security company acquired Cellbounce, which makes a device that converts 3G signals to 4G for AT&amp;T's network.                                                                                      , Security businesses, such as My Alarm Center, have been clear in their messaging to customers that replacement units were needed ahead of the shutdown, too. "Even if your alarm appears to function, it will no longer communicate with our central service station to notify us that emergency services are needed," My Alarm Center states on its website.                                                                                                                              , But even with these efforts, some customers and systems will likely get left behind -- and not just home security and car assistance services.                                                                                                                                                                                                                                                                                                                                             , "A few million connected devices in the smart home space still need to be replaced, including my meter for my solar panels," said Roger Entner, analyst and founder of Recon Analytics. "Some companies started reaching out to their customers over the past 2 years informing them that service would soon shut off, but as of 6 months ago, many products still haven't gotten around to replacing them yet."                                                                           , The auto industry is in more of a gray area. In addition to software upgrades, some automakers are offering consumers newer parts to add to existing technologies to get them running on 4G. But some are offering no accommodation at all. This is compounded by consumers likely being less aware of which network their car systems use than which network their phones use.                                                                                                            , "A fair number of people are going to be surprised," said Sam Abuelsamid, principal analyst with Guidehouse Insights, a market research firm focused on emerging technologies. "But if they're currently a paying subscriber to a connectivity service, they most certainly have been notified at this point."                                                                                                                                                                             , What you can do about it                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , As a general rule, most cars built in the last five years with connectivity are using 4G modems, according to Abuelsamid. Anyone who isn't sure if their vehicle is going to lose connectivity can call their local dealer for more information.                                                                                                                                                                                                                                           , If the car does use 3G, Abuelsamid recommended customers ask the manufacturer if there is an upgrade program and, failing that, contact the carriers, which can provide an adapter with a modem that can be plugged into a vehicle.                                                                                                                                                                                                                                                        , For those who are unsure if their home alarm system runs on 3G, the security company likely has an FAQ page on its website with a list of impacted model numbers. Customers can also call the company directly to ask and arrange for next steps.                                                                                                                                                                                                                                          , Ultimately, it's much easier to replace some items that run on 3G than others. "It's easier to replace a 3G e-reader if you want to keep cellular connectivity than it is to replace a car system, so some folks have an expensive decision to make if they want to keep their older auto connected with cellular," said Bill Menezes, director at market research firm Gartner.                                                                                                           , Future disruptions                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , It's not the first time a network has been phased out nor will it be the last. The 3G shutdown is primarily intended to re-use the spectrum for 4G and 5G, which are newer standards, better technologies and more efficient. The same thing happened with 2G, which AT&amp;T and Verizon shut down around the end of 2017; T-Mobile plans to shut its 2G network in December.                                                                                                                 , Last month, AT&amp;T and Verizon turned on C-band 5G networks, an important set of higher radio frequencies that will supercharge the internet. The change will allow users to, for example, stream a Netflix movie in 4K resolution or download a movie in seconds. (Verizon said its C-band speeds reach nearly one gigabyte per second, about 10 times as fast as 4G LTE.)                                                                                                                  , In the home security world, 5G would give the ability to stream high-definition video or interactive mapping with motion detection so an alarm company could see where on a 3D map an alarm went off and track anything moving through the area. Moreover, 4G enables more sophisticated features, such as the ability to communicate with alarm companies faster and share pictures and rich videos over the network.                                                                     , For those worried about seeing 4G household devices phased out, don't be. Dimitris Mavrakis, a senior director at market research firm ABI Research, said the shut down of 4G networks won't happen anytime soon, noting "other generations will likely remain in the market for a very long time." Because 2G introduced mobile voice and 4G introduced mobile broadband, he calls 3G "somewhere in between" and "not ideal for either voice or mobile broadband."                        , "Ultimately, 4G is a lot better than 3G," he said. "This is why it's being phased out."                                                                                                                                                                                                                                                                                                                                                                                                    , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/federal-gas-tax-prices-democratic-senators-suspend </td>
   <td style="text-align:left;"> 2022-02-16 00:56:35 </td>
   <td style="text-align:left;"> With prices soaring, Democratic senators facing tough re-elections push to temporarily scrap federal gas tax </td>
   <td style="text-align:left;"> GasBuddy head of petroleum analysis Patrick De Haan weighs in on rising energy prices and what that can mean for consumers.                                                                                                                                                                                                                                                                                                                                                                     , With the average national price for regular gasoline nearing $3.50 per gallon, two Democratic senators from key battleground states a proposing to temporarily eliminated the federal gas tax.                                                                                                                                                                                                                                                                                                  , And a bill co-authored by Sens. Maggie Hassan of New Hampshire and Mark Kelly of Arizona, who are being targeted by Republicans as they run for re-election this year, appears to be gaining some traction with their Senate Democratic colleagues.                                                                                                                                                                                                                                             , The Hassan/Kelly bill, which they titled the Gas Prices Relief Act, would scrap the 18.4 cents per gallon federal tax through the rest of 2022 and calls for the Treasury Department to make sure the savings are passed on to consumers rather than the oil and gas companies.                                                                                                                                                                                                                 , SENATE DEMOCRATS PROPOSE SUSPENDING FEDERAL GAS TAX                                                                                                                                                                                                                                                                                                                                                                                                                                             , And the measure, if passed into law, would also require the federal government to transfer money into the Highway Trust Fund, which is used for road construction and maintenance and supporting mass transit, to make up for the lost revenues.                                                                                                                                                                                                                                                , Alex Reyes, 28, filled his gas tank, Nov. 15, 2021, in Los Angeles. (Al Seib / Los Angeles Times via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                                                               , "This legislation is about making sure that we get Granite Staters relief at the gas pump. People are feeling a real pinch on everyday goods, and we must do more to help address rising costs, particularly the price of gas," Hassan said last week in a statement introducing the bill.                                                                                                                                                                                                      , NEW PREDICTION ON WHEN INFLATION WILL EASE                                                                                                                                                                                                                                                                                                                                                                                                                                                      , And Kelly, noting the "strain on families who need to fill up the tank to get to work and school," emphasized that "this bill will lower gas prices by suspending the federal gas tax through the end of the year to help Arizona families struggling with high costs for everything from gas to groceries."                                                                                                                                                                                    , The Hassan/Kelly bill, called the Gas Prices Relief Act, would scrap the 18.4 cents per gallon federal tax through the rest of 2022. (Zeng Hui/Xinhua via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                          , The new bill was quickly co-sponsored by Democratic Sens. Catherine Cortez Masto of Nevada and Raphael Warnock of Georgia, who along with Hassan and Kelly hail from general election battleground states and are also viewed by the GOP as vulnerable in November’s midterms. Sens. Debbie Stabenow of Michigan and Jackie Rosen of Nevada also signed onto the legislation.                                                                                                                   , The announcement by Hassan and Kelly came the day before new federal government figures showed consumer prices surging last month to their highest levels in four decades.                                                                                                                                                                                                                                                                                                                      , The unrelenting impact of inflation comes with nine months to go until November’s elections, when the Democrats hope to retain their razor-thin majorities in the U.S. House of Representatives and the Senate.                                                                                                                                                                                                                                                                                 , The new bill was quickly co-sponsored by Democratic Sens. Catherine Cortez Masto of Nevada and Raphael Warnock of Georgia. (AP Photo/Lynne Sladky, File / AP Newsroom)                                                                                                                                                                                                                                                                                                                          , Democrats are facing historical headwinds – the party that wins the White House traditionally suffers setbacks in the ensuing midterms – and they’re facing a brutal political climate compounded by the president’s flagging approval ratings. Partially fueling the adverse conditions and the consistent decline in President Biden’s standing among Americans has been the steep rise in consumer prices as the nation’s economy rebounds after being flattened by the coronavirus pandemic., Poll after poll shows that inflation is a top concern among Americans. And for eight months, Republicans have been blaming the massive government spending bills, that were passed first under then-President Donald Trump and over the past year under Biden, for fueling the rise in prices. And they’re using inflation as a campaign weapon against Democrats running for reelection this year.                                                                                             , CLICK HERE FOR THE LATEST FOX BUSINESS REPORTING ON INFLATION                                                                                                                                                                                                                                                                                                                                                                                                                                   , The Hassan-Kelly bill is expected to be discussed on Tuesday afternoon as the Senate Democratic conference gathers for their weekly policy lunch.                                                                                                                                                                                                                                                                                                                                               , "For the past few weeks, I've heard from my colleagues about a number of proposals they've been working on aimed squarely at helping Americans better afford the basics," Senate Majority Leader Chuck Schumer said ahead of the meeting." Democrats will use our weekly caucus lunch to talk more about some of the ideas my colleagues are working on."                                                                                                                                       , The temporary scrapping of the gas tax is an idea that some leading Republicans have also suggested.                                                                                                                                                                                                                                                                                                                                                                                            , Among them is GOP Gov. Ron DeSantis of Florida, who's pushing to suspend his state's gas tax for five months this summer and fall. But his proposal is facing resistance from top leaders in Florida's Republican dominated legislature."                                                                                                                                                                                                                                                       , But the Hassan-Kelly bill was quickly criticized by some of the Republican candidates hoping to face off in November's midterms against the Democratic senators.                                                                                                                                                                                                                                                                                                                                , "Real leadership would have been not spending trillions of dollars in the first place and causing prices to skyrocket!" Arizona Attorney General Mark Brnovich, one of the leading GOP Senate contenders, argued.                                                                                                                                                                                                                                                                               , And New Hampshire Senate president Chuck Morse, one of the three Republicans running this year to take on Hassan, claimed that "all this does is kick the can down the road – this is a phony gimmick that won’t lower gas prices; more supply will. We need to produce more American energy."                                                                                                                                                                                                  , National Republican Senatorial Committee (NRSC) spokeswoman Katharine Cooksey Noyes told Fox News that "you don’t ask an arsonist to put out a fire, and American families shouldn’t ask Senate Democrats to curb rising prices."                                                                                                                                                                                                                                                               , "Democrats like Mark Kelly, Maggie Hassan, Raphael Warnock, and Catherine Cortez Masto have spent their entire time in the Senate passing trillions in reckless spending that has made everything more expensive," Cooksey charged. "If these Senate Democrats really cared, they wouldn’t have approved Biden’s reckless spending spree in the first place."                                                                                                                                   , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                     , But the NRSC's counterpart, the Democratic Senatorial Campaign Committee (DSCC), argued that GOP opposition to the bill will backfire.                                                                                                                                                                                                                                                                                                                                                          , "Senate Democrats are fighting to address working families’ top concerns head on — and the fact that GOP Senate candidates are opposing this Democratic effort to cut gas prices is not only bad policy, it’s idiotic politics," DSCC communications director David Bergstein charged. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-02-16 00:55:25 </td>
   <td style="text-align:left;"> South Africa Stocks End Slightly Higher </td>
   <td style="text-align:left;"> The JSE FTSE All Share index pared early gains to close marginally higher at 75,853 on Tuesday, following a 0.8% decline in the previous session, led by banks, financials and retailers. At the same time, shares of Glencore firmed after the mining giant said it will set aside $1.5 billion for probes into bribery and market manipulation, which it expects to resolve in 2022, as it announced record earnings from booming raw materials prices. Meanwhile, investors welcomed signs of easing geopolitical tensions between Russia and Ukraine, while also bracing for monetary tightening in the US. On the domestic data front, January consumer inflation figures and December retail sales will be in focus on Wednesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-02-16 00:48:00 </td>
   <td style="text-align:left;"> Italian Shares Rebound </td>
   <td style="text-align:left;"> The FTSE MIB Index closed 2.1% higher at 26,968, lifted by good performances among banks, while investors weighed on signs of easing geopolitical concerns amid reports that the Kremlin is withdrawing some troops from near the Ukrainian border. Financial stocks jumped 2.7%, led by Bper Banca (9.2%) after the lender secured a deal for the acquisition of Banca Carige. After having previous acquisition bids denied during November 2021, Bper stated it would acquire Carige for 1 euro, given Carige’s majority stake owner, the Italian Interbank Deposit Protection Fund, injects EUR 530 million into the Ligurian lender to cover restructuring costs. The auto manufacturing sector also traded in the green, led by Stellantis (4.1%) and Iveco (2%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-02-16 00:47:00 </td>
   <td style="text-align:left;"> European Stocks Rebound Sharply </td>
   <td style="text-align:left;"> European bourses have managed to regain ground on Tuesday, with the STOXX 600 benchmark snapping a three-day losing streak on news that some Russian troops started returning to headquarters. Russian Defence minister's said that some Southern and Western military districts units have completed their exercises and begun returning to bases, signalling some de-escalation of the military build-up on Ukraine's border. On the data front, the UK jobs report showed that the job market remained strong, with staff on businesses' payrolls up by 108,000 in January from the prior month despite Omicron. Delivery Hero rallied nearly 14%, the most on the STOXX index. In contrast, at the bottom of the European blue-chip index, Swiss banking software company Temenos fell by around 8% after missing fourth-quarter earnings expectations. Domestically, the benchmark DAX 30 advanced almost 2% to above the 15,400 level. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-02-16 00:46:00 </td>
   <td style="text-align:left;"> French Stocks Firmly Rebound </td>
   <td style="text-align:left;"> The CAC 40 Index closed 1.9% higher at 6,980 level on Tuesday, partially rebounding from last session’s 2.3% loss, amid signs of de-escalation in the Russia-Ukraine crisis as leaders briefly signaled efforts of diplomacy with talks between President Putin and Chancellor Scholz, while investors digested fresh corporate earnings. Gains among the blue chips were led by LVMH (3.6%) after the luxury group announced that their retail prices will be raised globally due to higher manufacturing and transportation costs, with gains spilling over to Hermes (5.4%). Meanwhile, Pernod Ricard rose 2% after Citi raised its recommendation to “buy” from “neutral”, citing that its medium-term growth forecasts seem positive. On the other hand, Michelin traded 3.5% lower after announcing revenue from some of its markets will not return to their 2019 levels, despite beating Q4 profit estimates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-02-16 00:45:00 </td>
   <td style="text-align:left;"> UK Stocks Close Higher, Confirm Rebound </td>
   <td style="text-align:left;"> The FTSE 100 closed 1.0% or 78 points higher at 7,609 on Tuesday, after a 1.7% decline in the previous session, as tensions regarding a Russian invasion of Ukraine eased, while investors eyed jobs data and earnings. President Putin said in talks with Germany’s Chancellor that his country intends to negotiate with its Western partners on security guarantees through diplomatic channels, following Russia’s Foreign Ministry’s statement that it had begun pulling back some troops. The latest data showed the UK job market remained strong, with staff on businesses' payrolls up by 108,000 in January from the prior month despite Omicron. On the corporate front, Glencore reported record earnings and set aside $1.5bn for the costs of settling investigations into bribery and corruption in the UK, US and Brazil, which it expects to resolve this year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/qatar/inflation-cpi </td>
   <td style="text-align:left;"> 2022-02-16 00:42:16 </td>
   <td style="text-align:left;"> Qatar Inflation Rate Slows in January </td>
   <td style="text-align:left;"> The annual inflation rate in Qatar slowed to 4.16% in January of 2022 from 6.47% in the previous month which was the highest level since December of 2008. Prices declined for housing &amp; utilities (-1.31% vs -2.71% in December); while eased for transport (6.58% vs 11.28%); recreation &amp; culture (26.42% vs 37.31%); and furnishings (0.34% vs 3.64%). On the other hand, inflation quickened for food &amp; beverages (7.23% vs 6.73%). On a monthly basis, consumer prices were down 0.97 percent, the least in one year, compared to a 0.65% rise in the prior month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/currency </td>
   <td style="text-align:left;"> 2022-02-16 00:36:00 </td>
   <td style="text-align:left;"> British Pound Remains Strong </td>
   <td style="text-align:left;"> The British pound hovered above $1.35, after the jobs report strengthened expectations of higher interest rates from the Bank of England. Data showed the UK job market remained strong, with staff on businesses' payrolls up by 108,000 in January from the prior month despite Omicron. Moreover, annual pay growth in Britain in the final quarter of 2021 edged up to 4.3% from 4.2% in the three months to November, amid bigger Christmas bonuses than a year ago. Money markets price in a 25bps rate increase in March and 125bps by December 2022, but some analysts have warned about the risks of excessive expectations following comments from some BoE officials saying it was not granted the BoE was embarking on a rate hiking cycle. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/euro-area/currency </td>
   <td style="text-align:left;"> 2022-02-16 00:25:00 </td>
   <td style="text-align:left;"> Euro Rebounds from 1-Week Low </td>
   <td style="text-align:left;"> The Euro rose to $1.136 from an over 1-week low of $1.128 as investors damped safe-haven assets on signs of de-escalated tensions in Ukraine’s border as some Russian troops pulled back. Russian President Vladimir Putin said the country does not want a war in Europe and that he was ready to work further with the West on missiles and other security issues. Meanwhile, European Central Bank President Christine Lagarde reinforced that any change in the bank's policy will be gradual. Money markets see a 10bps rate hike at the June meeting and anticipate about 50bps in increases by year-end. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/15/us/prince-andrew-virginia-giuffre/index.html </td>
   <td style="text-align:left;"> 2022-02-16 00:22:29 </td>
   <td style="text-align:left;"> Prince Andrew and Virginia Giuffre agree to settle sex abuse lawsuit - CNN </td>
   <td style="text-align:left;"> (CNN)Prince Andrew and Virginia Giuffre have reached an out-of-court settlement in her sexual abuse lawsuit against him, according to a court document filed by her attorneys Tuesday.                                                                                                                                                                                                                                                  , The parties anticipate filing a stipulation of dismissal of the case within 30 days, according to the letter addressed to federal Judge Lewis Kaplan.                                                                                                                                                                                                                                                                                    , The sum of the settlement will not be disclosed, the letter says.                                                                                                                                                                                                                                                                                                                                                                        , "Prince Andrew intends to make a substantial donation to Ms. Giuffre's charity in support of victims' rights. Prince Andrew has never intended to malign Ms. Giuffre's character, and he accepts that she has suffered both as an established victim of abuse and as a result of unfair public attacks," the letter states.                                                                                                              , The civil suit stemmed from the sprawling and disturbing allegations against Jeffrey Epstein, the wealthy sex offender who befriended a series of powerful men despite a sketchy history.                                                                                                                                                                                                                                                , "It is known that Jeffrey Epstein trafficked countless young girls over many years," the letter continues. "Prince Andrew regrets his association with Epstein, and commends the bravery of Ms. Giuffre and other survivors in standing up for themselves and others. He pledges to demonstrate his regret for his association with Epstein by supporting the fight against the evils of sex trafficking, and by supporting its victims.", In the lawsuit, Giuffre alleged Epstein trafficked her and forced her to have sex with his friends, including Prince Andrew, and that Andrew was aware she was underage in the US at the time. She alleged Andrew sexually abused her at Epstein's private island in the US Virgin Islands, at his mansion in Manhattan and at his former girlfriend Ghislaine Maxwell's home in London.                                                 , The prince, also known as the Duke of York, has repeatedly and flatly denied the abuse.                                                                                                                                                                                                                                                                                                                                                  , "Prince Andrew denies that he was a co-conspirator of Epstein or that Epstein trafficked girls to him," his attorneys Andrew B. Brettler and Melissa Y. Lerner wrote in a legal filing last month.                                                                                                                                                                                                                                       , How we got here                                                                                                                                                                                                                                                                                                                                                                                                                          , Giuffre brought her case under the Child Victims Act, a New York state law enacted in 2019 that temporarily expanded the statute of limitations in child sex abuse cases.                                                                                                                                                                                                                                                                , Last month, Judge Kaplan denied a motion to dismiss the lawsuit. Prince Andrew had been scheduled to give a statement under oath on March 10, a source told CNN last week.                                                                                                                                                                                                                                                               , The long-running allegations against Andrew, 61, have already dramatically tarnished his public standing, and he stepped back from royal duties in late 2019. In the wake of the judge's decision last month, Andrew was stripped of his military titles and charities, Buckingham Palace announced.                                                                                                                                     , A Buckingham Palace spokesperson told CNN that the palace will not comment on the settlement. It's a matter for the Duke and his legal team, the spokesperson added.                                                                                                                                                                                                                                                                     , One of Giuffre's attorneys said Tuesday she was "very pleased" with the resolution of the lawsuit.                                                                                                                                                                                                                                                                                                                                       , "As a managing partner at a firm that has from its beginning acted upon the belief that the law should be marshalled to bring justice to the most vulnerable, I can say, without hesitation, that our representation of survivors upholds that tradition," attorney Sigrid McCawley said in a statement.                                                                                                                                 , Epstein pleaded guilty in 2008 to state prostitution charges and in July 2019 was indicted on federal sex trafficking charges. Prosecutors accused him of carrying out a decades-long scheme of sexual abuse of underage girls, flying them on private planes to his properties in Florida, New York, New Mexico and the US Virgin Islands. He died by suicide in prison before he could face trial.                                     , Maxwell, his former girlfriend and close associate, was arrested in 2020 and accused of facilitating the abuse scheme. A federal jury convicted her in December on five federal counts, including sex trafficking a minor and conspiracy.                                                                                                                                                                                                , Sign up for CNN's Royal News, a weekly dispatch bringing you the inside track on the royal family, what they are up to in public and what's happening behind palace walls.                                                                                                                                                                                                                                                               , CNN's Max Foster and Sonia Moghe contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-16 00:17:00 </td>
   <td style="text-align:left;"> Wall Street Rally Gains Steam </td>
   <td style="text-align:left;"> All three major US stock indexes regained ground on Tuesday, with the Dow Jones adding more than 400 points, S&amp;P 500 up 1.5%, and Nasdaq surging over 2% as concerns of an imminent war in Europe eased. Russian Defence minister's said that some Southern and Western military districts units have completed their exercises and started returning to bases, signalling some de-escalation of the military build-up on Ukraine's border. Aside from the Russia-Ukraine crisis, investors continue to digest the Fed's narrative of a looming policy tightening cycle. They are now awaiting the FOMC minutes on Wednesday for clues about the timing and scale of future rate hikes. Gains were most pronounced in the industrials and financial sectors, while heavyweight energy stocks came under heavy selling pressure due to a sharp drop in oil prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/azerbaijan/monthly-gdp-yoy </td>
   <td style="text-align:left;"> 2022-02-16 00:16:32 </td>
   <td style="text-align:left;"> Azerbaijan GDP Expands 5.8% YoY in January </td>
   <td style="text-align:left;"> The economy of Azerbaijan expanded 5.8% year-on-year in January of 2022, the strongest expansion since December of 2013. Both oil and gas (0.6 percent) and the non-oil and gas (8.8 percent) sectors of the economy expanded as the economy continued to recover from the pandemic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/somalia/inflation-cpi </td>
   <td style="text-align:left;"> 2022-02-16 00:11:59 </td>
   <td style="text-align:left;"> Somalia January Inflation Rate at 2-½-Year High </td>
   <td style="text-align:left;"> The annual inflation rate in Somalia rose to 6.84 percent in January of 2022, from 5.67 percent in the previous month. It was the highest inflation rate since July of 2019, underpinned by prices of food &amp; non-alcoholic beverages (11.63 percent vs 7.39 percent in December); housing &amp; utilities (4.5 percent vs 5.49 percent) and health (13.45 percent vs 14.09 percent). On a monthly basis, consumer prices went down 0.06 percent, after a 0.22 percent decrease in December. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/moldova/interest-rate </td>
   <td style="text-align:left;"> 2022-02-16 00:04:00 </td>
   <td style="text-align:left;"> Moldova Hikes Key Rate to 10.5% </td>
   <td style="text-align:left;"> The National Bank of Moldova raised its benchmark interest rate by 200 bps to 10.5 percent on February 15th, 2022 to curb inflation and bring it down to its targeted range of 5 +/- 1.5% in order to stabilize the economy. It was the fifth consecutive hike in base rate. Consumer prices increased by 16.6% on the year in January, the highest since May of 2008 and far above the Central Bank’s target, pushed up by expensive energy imports. At the same time, the overnight deposit rate rose by 200bps to 8.5 percent, its highest level since 2016, while overnight credits also rose by 200bps to 12.5 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/cheese </td>
   <td style="text-align:left;"> 2022-02-15 23:53:19 </td>
   <td style="text-align:left;"> Cheese Hits 4-week High </td>
   <td style="text-align:left;"> Cheese increased to a 4-week high of 1.911 USD/Lbs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/inflation-will-moderate-as-covid-fades-moodys-economist-mark-zandi </td>
   <td style="text-align:left;"> 2022-02-15 23:48:24 </td>
   <td style="text-align:left;"> Inflation will ‘moderate’ as COVID fades: Moody’s economist Mark Zandi </td>
   <td style="text-align:left;"> Moody's Analytics chief economist Mark Zandi joined 'Mornings with Maria' to discuss inflation, the producer price index, and the possibility of a recession.                                                                                                                                                                                                                                      , Moody’s Analytics chief economist Mark Zandi discussed his economic outlook on "Mornings with Maria" Tuesday, forecasting that Americans won’t have to worry about inflationary prices for much longer.                                                                                                                                                                                            , Zandi, a trusted adviser to policymakers at the congressional level, suggested inflation already hit its peak back in the fall of 2021 when the coronavirus pandemic was disrupting labor markets and global supply chains.                                                                                                                                                                        , "Things are still scrambled, it’s taking a while to get things back in order, but they’re moving in the right direction," he said. "I do think that it’s a pandemic phase and that’s the most likely scenario going forward."                                                                                                                                                                      , WHOLESALE PRICES JUMP 9.7% IN JANUARY, FURTHER EVIDENCE OF RED-HOT INFLATION                                                                                                                                                                                                                                                                                                                       , "We’ll start to see supply chains, labor markets, product markets start to iron things out and inflation moderate."                                                                                                                                                                                                                                                                                , A sign is seen on the shelf at a CVS store in Queens, New York. (Photo by: Lindsey Nicholson/Universal Images Group via Getty Images)                                                                                                                                                                                                                                                              , Host Maria Bartiromo pushed back on Zandi, pointing to the high PPI projection, consumer inflation concerns and the looming threat of recession. The economist responded that even though he does not expect a recession in 2023, the possibility can never be ruled out.                                                                                                                          , The Labor Department said Tuesday that its producer price index, which measures inflation at the wholesale level before it reaches consumers, surged 9.7% in January from the year-ago period, slightly below the 12-year high of 9.8% notched in November and December. But in an unexpected turn, prices rose 1% in January on a monthly basis – well above the revised gain of 0.4% in December., The surge in wholesale prices comes on the heels of a separate Labor Department report released last week that showed consumer prices climbed 7.5% in January from the previous year, the biggest increase since February 1982, when inflation hit 7.6%. Consumers are paying more for everyday necessities, including groceries, gasoline and cars.                                               , According to Zandi, inflation should be tapering off within the next six months based on rate of increase year-over-year.                                                                                                                                                                                                                                                                          , Bartiromo questioned what’s supporting Zandi’s positivity after previously claiming inflation was transitory. Zandi doubled down on his statement that inflation is, in fact, temporary which Bartiromo rejected.                                                                                                                                                                                  , The Biden administration weighs in on the January CPI report as inflation plagues U.S. FOX Business' Ed Lawrence with the latest.                                                                                                                                                                                                                                                                  , "But it hasn’t been transitory," she said. "Consumer inflation is at a 40-year high right now. You don’t think now’s the peak?"                                                                                                                                                                                                                                                                    , "Prices are rising, there’s no doubt about it," he countered. "I’m just saying… the increase in price you paid this month, Maria, is less than the rate you paid back six months ago. To me, that means inflation is moving in the right direction."                                                                                                                                               , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                        , Zandi explained that there’s still a "long way to go" in order to correct inflationary damage, but his forecast is still optimistic.                                                                                                                                                                                                                                                               , A man fuels a car at a gas station in New York, on Oct. 13, 2021. (Photo by Xinhua via Getty Images)                                                                                                                                                                                                                                                                                               , "My sense is the underlying cause of inflation is the pandemic and as that goes away inflation should moderate," he said. "When you go buy some meat, or you go to fill your gas tank six months from now, you’ll be feeling better about things."                                                                                                                                                 , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                            , FOX Business' Megan Henney contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/trp:cn </td>
   <td style="text-align:left;"> 2022-02-15 23:44:41 </td>
   <td style="text-align:left;"> TransCanada earnings above expectations at 1.06 CAD </td>
   <td style="text-align:left;"> TransCanada (TRP) released earnings per share at 1.06 CAD, compared to market expectations of 1.05 CAD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/portugal/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-15 23:27:23 </td>
   <td style="text-align:left;"> Portugal 10Y Bond Yield Hits 21-month High </td>
   <td style="text-align:left;"> Portugal 10 Year Government Bond Yeld increased to a 21-month high of 1.208% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/eu-natural-gas </td>
   <td style="text-align:left;"> 2022-02-15 23:10:00 </td>
   <td style="text-align:left;"> TTF Gas Hits 4-Month Low </td>
   <td style="text-align:left;"> Europe Gas futures linked to TTF fell to below €68 per megawatt-hour, the lowest since November as Russia-Ukraine tensions started to ease. President Putin told German Chancellor Olaf Scholz that his country intends to negotiate with its Western partners on security guarantees through diplomatic channels. Earlier, the Russian Defence minister's said that some Southern and Western military districts units have completed their exercises and started returning to bases. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-15 23:07:27 </td>
   <td style="text-align:left;"> Japan 10Y Bond Yield Hits 6-year High </td>
   <td style="text-align:left;"> Japan 10 Year Government Bond Yeld increased to a 6-year high of 0.229% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/uk-natural-gas </td>
   <td style="text-align:left;"> 2022-02-15 23:07:00 </td>
   <td style="text-align:left;"> UK Gas Hits 6-week Low </td>
   <td style="text-align:left;"> UK natural gas prices touched a six-week low of 167.3 pence a therm on Tuesday, in line with the Dutch contract, on signs of easing tensions between Russia and the West. President Putin told German Chancellor Olaf Scholz that his country intends to negotiate with the its Western partners on security guarantees through diplomatic channels and that Russia is ready to maintain natural gas flows through Ukraine after 2024, given demand justifies so. Meanwhile, Chancellor Scholz said Ukraine membership to NATO was not on the agenda. Earlier, Putin said energy cooperation with Germany was a top priority ahead of bilateral talks in Moscow, and reiterated that Russia has been a reliable exporter for decades. Meanwhile, steady flows of LNG cargoes arriving at UK’s ports and milder temperatures have been also lifting some pressure off natural gas prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-02-15 23:00:27 </td>
   <td style="text-align:left;"> Canadian Shares Rise on Tuesday </td>
   <td style="text-align:left;"> Canadian stocks were higher around the 21450 level on Tuesday, tracking upbeat global sentiment, amid easing concerns about geopolitical risks in Ukraine after reports that some Russian troops were returning to their bases. On the other hand, energy shares were under pressure amid a fall in oil prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/warren-buffett-berkshire-hathaway-activision </td>
   <td style="text-align:left;"> 2022-02-15 22:46:37 </td>
   <td style="text-align:left;"> Warren Buffett's Berkshire Hathaway buys Activision stock </td>
   <td style="text-align:left;"> Ironsides Macroeconomics director of research Barry Knapp provides insight into escalating tensions between Russia and Ukraine and the markets.                                                                                                                                                                                                                                                                                                                                                                                                , Warren Buffett's Berkshire Hathaway has loaded up on Activision Blizzard stock.                                                                                                                                                                                                                                                                                                                                                                                                                                                                , According to a 13F filing, Berkshire Hathaway bought approximately 14.66 million Activision Blizzard shares valued at $975 million as of the end of 2021. As of Tuesday morning, Activision Blizzard shares are up more than 20% year-to-date.                                                                                                                                                                                                                                                                                                 , BUFFETT'S BERKSHIRE HATHAWAY WILL HOS ANNUAL MEETING IN PERSON                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , The purchase came ahead of Microsoft's announcement that it would acquire the embattled video game publisher for $68.7 billion.                                                                                                                                                                                                                                                                                                                                                                                                                , The deal, which values Activision at approximately $95 per share, is expected to close in fiscal year 2023, pending regulatory approval and completion of other customary closing conditions. Once the deal closes, the Activision Blizzard business will report to Microsoft Gaming CEO Phil Spencer.                                                                                                                                                                                                                                         , Bill Gates and Warren Buffett ( )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Microsoft was co-founded by Buffett's long-time friend Bill Gates, who stepped down from the boards of Berkshire and the tech giant in 2020. Gates and Buffett rank fourth and sixth, respectively, among the world's richest people, according to real-time tracking by Forbes.                                                                                                                                                                                                                                                               , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Activision Blizzard shares fell as low as $56.40 last year following allegations from California's Department of Fair Employment and Housing (CDFEH) that the company paid its female employees less than their male counterparts, provided them with fewer opportunities to advance, fostered a "frat boy workplace culture" and ignored complaints of blatant harassment, discrimination and retaliation.                                                                                                                                    , The Activision Blizzard Booth during the Electronic Entertainment Expo in Los Angeles. (AP Photo/Jae C. Hong / AP Newsroom)                                                                                                                                                                                                                                                                                                                                                                                                                    , In the months that have followed, Activision Blizzard employees have called for the firing of chief executive officer Bobby Kotick for failing to disclose his full knowledge of employee sexual harassment and discrimination complaints to the company's board of directors. They have also accused the company of worker intimidation and engaging in union-busting tactics.                                                                                                                                                                , Robert "Bobby" Kotick, chief executive officer of Activision Blizzard Inc., smiles during the annual Milken Institute Global Conference in Beverly Hills, California, on Monday, May 2, 2016.  ( Patrick T. Fallon/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                  , In order to address employee concerns, Activision announced it would increase its hiring of women or nonbinary employees, invest millions in accelerating and expanding opportunities for diverse talent and underrepresented communities, waive required arbitration of sexual harassment and discrimination claims and increase transparency related to pay equity. It also formed a workplace responsibility committee to oversee the workplace culture transformation and work in tandem with the Equal Employment Opportunity Commission. , Over 20 employees have exited the company, including former Blizzard President J. Allen Brack, and another 20 employees have faced other types of disciplinary action since CDFEH's lawsuit in July.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-15 22:35:00 </td>
   <td style="text-align:left;"> Wall Street Rallies as Russia Pulls Troops </td>
   <td style="text-align:left;"> Wall Street rallied on Tuesday with Dow up more than 400 points, S&amp;P 500 adding 1.5% and Nasdaq surging almost 2% as concerns of an imminent war in Europe eased. The Russian government has said it began to return troops at the Ukrainian border to their bases. At the same time, Fed's tightening plans remain in the spotlight as traders await the FOMC minutes tomorrow for further clarification if the central bank will deliver a 50bps rate hike next month. Financial and consumer discretionary were among the best performing sectors while energy shares were in the red amid a fall in oil prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-02-15 22:34:24 </td>
   <td style="text-align:left;"> Natural Gas Hits 1-Week High </td>
   <td style="text-align:left;"> NYMEX natural gas futures climbed to a one-week high of $4.40/MMBtu, buoyed by expectations for colder weather in the coming weeks that would boost demand for the fuel. Still, the slow return of US production from weather-related disruptions over the past month limited more upside momentum in the near term. Investors now await Thursday’s EIA storage report for a clear picture of the supply/demand balance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-02-15 22:21:00 </td>
   <td style="text-align:left;"> Brazilian Equities at Near 4-Month High </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, was up 0.4% to around 114,400 on Tuesday, a high level not seen since October 18th, 2021, with Locaweb, Petz and Azul among the top performers. Meanwhile, investors weighed upbeat corporate earnings and signs of easing tensions between Russia and Ukraine against concerns over the Fed's monetary policy tightening. Banco do Brasil posted higher-than-expected fourth-quarter profit and announced ambitious 2022 goals. Itaúsa and Raízen also positively surprised. Traders now wait for corporate reports of PetroRio, Caixa Seguridade, Carrefour and Banrisul later in the day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/sri-lanka/services-pmi </td>
   <td style="text-align:left;"> 2022-02-15 22:18:15 </td>
   <td style="text-align:left;"> Sri Lanka Services PMI at 4-Month Low </td>
   <td style="text-align:left;"> The Services PMI in Sri Lanka fell to a 4-month low of 57.5 in January of 2022 from 62.4 in the previous month, marking the softest pace of growth in the services sector since September of 2021. Both new businesses (57.5 vs 67.8) and business activities (62 vs 72.8) expanded at a slower rate amid continuation of relaxed pandemic related restrictions. Also, employment increased for the third month in a row, although at a softer rate (52 vs 53) as companies continued recruitments in order to support the increase in business activities while backlogs of work continued to decline at a slower pace (47.4 vs 45.7) as most of the staff reported to work as usual. Finally, expectations on future business activity eased significantly (68.5 vs 72.8) as respondents worry about the negative impacts of import related restrictions and inflationary pressure on their business activities. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-02-15 22:08:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index Snaps 5-Day Winning Run </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index fell 0.8% to 1,968 on Tuesday, its highest since January 12th, after five consecutive sessions of gains, amid weaker demand for its capesize and panamax vessels segments. The capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, slumped 4.6% to 1,713, falling for the fourth straight session; and the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, went down 0.7% to 2,400. Meanwhile, the supramax index increased 49 points to 2,277. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/saudi-arabia/stock-market </td>
   <td style="text-align:left;"> 2022-02-15 22:04:03 </td>
   <td style="text-align:left;"> Saudi Arabian Stocks Climb to Highest since 2006 </td>
   <td style="text-align:left;"> Saudi Arabia’s TASI stock index added 1.2% to 12,351 on Tuesday, the highest closing level since July 2006 and extending year-to-date gains to over 9% boosted by strong earnings results and high commodity prices in particular oil. The banking sector led gains, with Al Rajhi Bank up 4% after reporting a 39% jump in 2021 net profit. Other lenders such as Saudi National Bank, Bank AlBilad and Riyad Bank also advanced on the prospects of higher interest rates. On the other hand, Sahara International Petrochemical Company fell over 2% on the announcement that its plants Al Waha and SAMAPCO would go on scheduled maintenance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/15/business/office-return-lobby-security.html </td>
   <td style="text-align:left;"> 2022-02-15 22:00:12 </td>
   <td style="text-align:left;"> Office Lobbies Are Going Contactless Because of Covid - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Square Feet                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Subtle changes — like mobile apps that will replace ID badges for workers and visitors — are meant to ease the flow at the turnstile while minimizing contact.                                                                                                                                                                                                                                                                                                                                                 , By Joe Gose                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , After Sept. 11, the lobbies in many U.S. office buildings permanently changed as landlords beefed up security, adding cameras, turnstiles, programmable elevators and other technological tools. All who entered were required to have identification, and guards recorded who came and went.                                                                                                                                                                                                                  , Now, as pandemic restrictions ease and workers begin to trickle back into the office, the lobby is changing again, this time with an emphasis on health and safety. But the changes are subtle, and they are primarily meant to ease the flow at the turnstile.                                                                                                                                                                                                                                                , Most notably, mobile applications tied to building security or operating systems are replacing plastic ID badges for workers and the check-in process for visitors. The goal is to digitally connect anyone entering the building while minimizing direct contact. Body scanners and air sensors are expected to become more prominent in the future.                                                                                                                                                          , Unlike the extra security measures of the post-9/11 world, which were plain to see, the latest changes will go largely unnoticed, said Jurgen Timperman, president of fire and security at Carrier Global, a provider of building operating systems based in Palm Beach Gardens, Fla.                                                                                                                                                                                                                          , “With these applications, we have all the information we need about someone before they get to the building,” he said. “So the days where somebody sits behind a desk with a big book and pen are all but over.”                                                                                                                                                                                                                                                                                               , Building apps allow users to upload identification and other credentials, like their vaccine status, and offer the flexibility to add functions like health questionnaires that prescreen employees or visitors before their arrival. The apps can also track users throughout a building, which can help companies use space more efficiently or close areas to reduce occupancy.                                                                                                                             , Vendors are tight-lipped when it comes to how much building systems cost, as are the landlords who have installed them. One problem, they say, is that price varies with a building’s size and layout and the number of people, sensors and functions on the system.                                                                                                                                                                                                                                           , The behind-the-scenes overhaul of security systems is catching on in office buildings and even at universities. Students and faculty at the Rochester Institute of Technology in upstate New York, for example, use a system from Carrier for mobile entry to buildings on campus.                                                                                                                                                                                                                             , The New York developer Silverstein Properties has introduced a contactless entry system for tenants at 7 World Trade Center in Manhattan that allows employees to use badges stored in Apple Wallet to gain access to office and amenity spaces. And at Deutsche Bank’s new offices in the former Time Warner Center, vaccination status is loaded onto employee badges for entry through its turnstiles, a spokesman said.                                                                                    , In August, Rubenstein Partners rolled out a platform and app from HqO, a provider of building operating systems, at a 500,000-square-foot office building known as 25 Kent in Brooklyn, about 16 months after it opened. Rubenstein had decided before the pandemic to use the technology in the new development, but the desire to create a contactless entry hastened the timing.                                                                                                                            , “In the past, when someone visited an office, you’d hand your ID to a security person. But with Covid, distance became a concern,” said Salvatore Dragone, director of property management for Rubenstein, which is based in Philadelphia. “Now you can preregister, and your phone opens a turnstile or elevator door. It gives us a lot more control as to who comes into the building.”                                                                                                                     , In addition to the apps, permanent but discreet temperature and body scanners and air sensors in lobbies and elsewhere could become more commonplace, especially if other airborne viruses or more coronavirus variants emerge.                                                                                                                                                                                                                                                                                , As property managers continue to reimagine the office lobby, tenants and visitors can also expect a “concierge feel” in addition to basic security, Mr. Dragone said, as music, HVAC fragrance diffusers, art and other experiential elements become more commonplace.                                                                                                                                                                                                                                         , And those plexiglass dividers? “I don’t think they’re there for good,” he added, “nor do we want them to stay longer than need be.”                                                                                                                                                                                                                                                                                                                                                                            , The technology continues a movement to automate manual processes across industries. But in commercial real estate, it is also part of a trend to create a more hospitable and inviting atmosphere by borrowing ideas from hotel lobbies, like seating lounges and meeting areas, said Lenny Beaudoin, who oversees workplace, design and occupancy for CBRE, a commercial real estate brokerage firm. CBRE also created Host, an app for tenants and landlords, and other digital building operating solutions., “What owners are providing in lobbies is largely a response to what tenants want, and ultimately that’s a more connected experience,” said Sandeep Davé, the chief digital and technology officer at CBRE. “The focus now is on the convergence of functions on a smartphone that will provide a contactless experience and encourage people to return to work, and to return safely.”                                                                                                                         , The pandemic has accelerated interest in contactless solutions, said James Scott, the lead researcher at the Real Estate Innovation Lab at the Massachusetts Institute of Technology.                                                                                                                                                                                                                                                                                                                          , “In light of Covid, the acceptance of new technology and its implementation became extremely important,” he said. “The adoption rate has accelerated by anywhere from three to five years.”                                                                                                                                                                                                                                                                                                                    , U.S. Covid restrictions easing. Officials in​​ Washington, D.C., and Maryland joined a growing list of leaders to announce the loosening of pandemic rules. But mask mandates remain in some cities and school districts, creating a patchwork of restrictions.                                                                                                                                                                                                                                                  , Around the world. Prime Minister Justin Trudeau of Canada took the rare step of declaring a national emergency in a push to end the trucker-led protests that have roiled the country. In China, new Covid cases within the closed Olympic “loop” have dropped to almost nothing.                                                                                                                                                                                                                              , N.Y.C.’s vaccine mandate. New York City fired about 1,430 workers for failing to comply with its vaccine mandate. The figure represents less than 1 percent of the city’s work force, but it is likely the nation’s largest mass termination of municipal employees in response to such a mandate.                                                                                                                                                                                                             , Novak Djokovic. The Serbian tennis star said he was prepared to miss the French Open and  Wimbledon if he was required to get a Covid vaccine. Last month, Mr. Djokovic was blocked from competing in the Australia Open over his vaccination stance.                                                                                                                                                                                                                                                          , In a 2021 global survey, nearly two-thirds of 250 respondents said they had either adopted mobile credentialing to control building access or planned to over the next two years, according to IFSEC Global, an international security and fire safety news and conference organization in London.                                                                                                                                                                                                             , Despite the urgency created by the pandemic, some landlords and property managers are still mulling how to best strengthen their lobby safety and security, and by how much.                                                                                                                                                                                                                                                                                                                                   , Complicating matters is the lack of a unified system. The sector for building software solutions remains fragmented, with several property technology companies competing. And the abilities are still being explored. For instance, apps have been developed to automatically call an elevator when a person enters a building, but technology providers have yet to roll out the feature in a significant way, Mr. Scott said.                                                                               , The same is true for the deployment of automated temperature scanners, he added. In many cases, temporary temperature-taking stations disappeared in 2021, before the Omicron variant of the coronavirus took hold.                                                                                                                                                                                                                                                                                            , “Once a pandemic loses its steam, these types of temporary measures tend to gather dust in a storage room unless they have been integrated into the framework of the building management system,” Mr. Scott said.                                                                                                                                                                                                                                                                                              , Expense is also a consideration, particularly in older buildings that lack a robust technology foundation, said W.A. Watts IV, president of the Institute of Real Estate Management, an international organization for property and asset managers.                                                                                                                                                                                                                                                            , For example, a project to retrofit an 18-year-old, 25,000-square-foot building in Birmingham, Ala., costs around $5 a square foot just to install base infrastructure, said Mr. Watts, who goes by Chip. He and other industry observers question whether low-density suburban offices in smaller markets even need to install such intensive security and safety measures.                                                                                                                                    , But technological innovation is on its way, said Dawn M. Carpenter, the founder of Dawning Real Estate and a broker who manages about five million square feet of commercial real estate in New York.                                                                                                                                                                                                                                                                                                          , In her 200,000-square-foot office building on Staten Island, security guards at the lobby desk still call tenants when visitors arrive, Ms. Carpenter said. The guests then wait until someone takes the elevator down to fetch them. Since Omicron hit, however, no visitors have been allowed.                                                                                                                                                                                                               , “Adding a building operating system is a big capital expenditure, and owners have to buy into it,” she said. “There’s not one in this building yet, but it will be coming.”                                                                                                                                                                                                                                                                                                                                    , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/15/a-lack-of-diversity-still-persists-in-the-financial-planning-industry.html </td>
   <td style="text-align:left;"> 2022-02-15 22:00:01 </td>
   <td style="text-align:left;"> While slowly improving, a lack of diversity in the financial planning industry persists </td>
   <td style="text-align:left;"> , Financial planning — and the financial services industry, more broadly — has long been an arena of predominantly white men.                                                                                                                                                                                                                                                                            , Industry leaders have been working to boost diversity, and while progress has been slow, it seems to be bearing some fruit. Still, 83% of certified financial planners in 2021 were white, and 77% were men, according to the CFP Board.                                                                                                                                                               , CNBC spoke with Dennis Moore, CFP, the new volunteer president of the Financial Planning Association, to discuss diversity roadblocks and what the trade group is doing to foster a more inclusive culture. Moore, who will serve a one-year term as FPA president, is chief operating officer of Dallas-based Quest Capital Management.                                                               , Greg Iacurci: Is diversity a core issue for the FPA?                                                                                                                                                                                                                                                                                                                                                   , Dennis Moore: It is. Our industry has a long way to go to increase the diversity of our practitioner community. The American public is becoming more diverse, and our profession is falling short of matching that growth.                                                                                                                                                                             , GI: How might more diversity benefit consumers, too?                                                                                                                                                                                                                                                                                                                                                   , DM: Financial planning is for everybody; everybody needs competent and ethical financial advice. At the same time, they're looking for someone that they have some commonalities with. If we really want the public to thrive and engage in financial planning, we need to be sure that our financial planners reflect the diversity that is within America.                                           , More from Personal Finance:New guaranteed income experiments inspired by MLK Jr.More than 70% of Black Americans don't have a willFirst-generation Black wealth builders must put themselves first                                                                                                                                                                                                     , We're also hoping to make financial planning a career choice that's more known. That goes from everything from outreach on college campuses to encouraging mentorships to diversity scholarships to attend some of our FPA events. It's important for the profession and important for the consumer.                                                                                                   , GI: How do you gauge success?                                                                                                                                                                                                                                                                                                                                                                          , DM: If we can basically mirror the diversity that's in the U.S., I think that's a great target.                                                                                                                                                                                                                                                                                                        , GI: How is the FPA fostering that?                                                                                                                                                                                                                                                                                                                                                                     , DM: We have a Diversity and Inclusion Committee at FPA that works closely with the board and helps us look for opportunities to support our diverse membership.                                                                                                                                                                                                                                        , We have what we call "knowledge circles," [for example]. They're seven different community-based circles [for] diverse parts of our membership, from women in finance to African Americans, Asian Americans, Pacific Islanders. Just over the last year, we've had a 22% growth in these communities. That's one way we're reaching out to existing members and hopefully encouraging more to join FPA., GI: What do they do?                                                                                                                                                                                                                                                                                                                                                                                   , DM: Each one may have a different cadence but [generally have] monthly meetings. [Participants] have an opportunity to engage in discussion, hear from experts, build relationships throughout FPA.                                                                                                                                                                                                    , We're [also] developing a plan for more diversity, equity and inclusion training for the board and the staff. Our goal is to expand that training out to all our FPA volunteers. We've been working with our conference task forces to feature D&amp;I thought leaders [and] host different events to celebrate diverse membership at our events.                                                          , We also have The Journal of Financial Planning. We've had entire issues dedicated specifically to diversity and inclusion, with our next one coming up this fall.                                                                                                                                                                                                                                      , GI: Why has diversity been an issue for the profession?                                                                                                                                                                                                                                                                                                                                                , DM: I think some of it is lack of awareness of this being a vital career path. There are still a lot of people who don't know what financial planning really is. Whether they're starting out in college in a financial planning program somewhere or are career changers — whatever it may be — I think we've got to get better about showing that opportunity.                                       , GI: What if you're not going to college? It may be even harder to become aware of it as an option.                                                                                                                                                                                                                                                                                                     , DM: Right.                                                                                                                                                                                                                                                                                                                                                                                             , GI: So it kind of starts in high school — which is a challenging proposition.                                                                                                                                                                                                                                                                                                                          , DM: It is. Even financial literacy and just that type of education in high schools. People aren't seeing that as a path, don't even know what it is. Hopefully they at least see it in college. But a lot of times, you know, they don't see it before that.                                                                                                                                           , GI: What do you see as some other big challenges for the industry?                                                                                                                                                                                                                                                                                                                                     , DM: We have more demand than we have supply of financial planners. And so that's where for me it's like, OK, we've got to get people more aware of financial planning, get them into the profession in order to meet the demands of the consumer.                                                                                                                                                      , GI: How have pandemic-related disruptions affected to the normal course of business for advisors and clients?                                                                                                                                                                                                                                                                                          , DM: I think it's changing how planners are doing what they do. There's a lot more remote work, hybrid setups, which is really opening up where people can live and work. I think that dynamic is probably going to continue. We can't replace being in-person, so the in-person pieces will start coming back.                                                                                         , GI: As advisors and planners have done stuff more digitally there are probably some opportunities and challenges that come along with that. Like, you could reach more clients but other advisors could reach into your geographic market, too.                                                                                                                                                        , DM: I think the tools are there to make some of that reach a little bit stronger than it was before. But it's got to be tied back to the service and the value [planners] provide.                                                                                                                                                                                                                     , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                 , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                 , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                       , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                       , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                     , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/sri-lanka/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-02-15 22:00:00 </td>
   <td style="text-align:left;"> Sri Lanka Factory Activity Growth Advances in January </td>
   <td style="text-align:left;"> The Manufacturing PMI in Sri Lanka increased to 58.7 in January of 2022 from 58.1 in the previous month, amid expansions in production (59.8 vs 58 in December) and new orders (62.2 vs 65.5), although at a softer rate, mainly in the manufacture of textile &amp; wearing apparel and food &amp; beverage sectors coupled with a recovery in employment (55.2 vs 48). Also, stock of purchases increased (55.7 vs 52) in line with the expansion in new orders and production. In addition, supplier’s delivery time lengthened at a slower pace (56.6 vs 61.1) although many stressed that they experienced delays in receiving import consignments, partly due to the impediments in the clearance of shipping documents, opening of letters of credit, and congestions at the port. In the next three months, manufacturer's expectations remained at elevated levels anticipating continuous improvements in economic condition, locally and globally.
. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ecl:us </td>
   <td style="text-align:left;"> 2022-02-15 21:40:09 </td>
   <td style="text-align:left;"> Ecolab earnings below expectations at 1.28 USD </td>
   <td style="text-align:left;"> Ecolab (ECL) released earnings per share at 1.28 USD, compared to market expectations of 1.32 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/15/business/media/sarah-palin-new-york-times-jurors.html </td>
   <td style="text-align:left;"> 2022-02-15 21:38:38 </td>
   <td style="text-align:left;"> Sarah Palin’s Libel Claim Against The Times Is Rejected by a Jury - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , The verdict came a day after the judge said he planned to dismiss the case, ruling that Ms. Palin’s legal team had failed to prove that the newspaper defamed her.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , By Jeremy W. Peters                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , A jury rejected Sarah Palin’s libel suit against The New York Times on Tuesday, finding that there was insufficient evidence to prove the newspaper had defamed her in a 2017 editorial that erroneously linked her political rhetoric to a mass shooting.                                                                                                                                                                                                                                                                                                                                                                                                                                     , The jury’s verdict, which First Amendment advocates applauded as a victory for the longstanding legal precedent that considers an occasional journalistic mistake a necessary cost of discourse in a free society, was the second time this week that Ms. Palin’s case was dealt a significant setback. On Monday, the presiding judge in federal court in Lower Manhattan, Jed S. Rakoff, reached a similar finding as the jury. He said that he would dismiss the case if the jury found in her favor because she had not demonstrated The Times acted with the level of recklessness and ill intent required to meet the high constitutional burden for public figures who claim defamation., Ms. Palin is expected to appeal.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , The case set up a high-stakes test of First Amendment law and the extremely high legal bar that the Supreme Court has set for proving a defamation claim against journalists. Lawyers for Ms. Palin, the former governor of Alaska and 2008 Republican vice-presidential nominee, argued that the longstanding legal protections in place to shield journalists from liability for almost any error that wasn’t intentional are outdated and overly broad. A public figure like Ms. Palin has to prove that a news organization acted with “actual malice” in publishing false information, meaning it displayed a reckless disregard for the truth or knew the information was false.         , The Times has not lost a libel case in an American courtroom in at least 50 years.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , “It is gratifying that the jury and the judge understood the legal protections for the news media and our vital role in American society,” a spokeswoman for The Times, Danielle Rhoades Ha, said in a statement, adding that the verdict upheld “a fundamental tenet of American law.”                                                                                                                                                                                                                                                                                                                                                                                                        , Ms. Palin’s lawyers may get another chance to argue why those protections should be pared back on appeal. Legal experts said that one avenue for asking an appeals court to reconsider the case is to ask that the courts revisit the broad manner in which the law defines a public figure.                                                                                                                                                                                                                                                                                                                                                                                                   , Ms. Palin’s suit claimed that The Times defamed her with an editorial that incorrectly asserted a link between her political rhetoric and a mass shooting near Tucson, Ariz., in 2011 that left six people dead and 14 wounded, including Gabrielle Giffords, then a Democratic member of Congress. Ms. Giffords’s district had been one of 20 singled out on a map circulated by Ms. Palin’s political action committee underneath digitized cross hairs. There was no evidence the shooter had seen or was motivated by the map.                                                                                                                                                             , The editorial was published on June 14, 2017, the same day that a gunman opened fire at a baseball field in Virginia where Republican congressmen were practicing, injuring several people, including Representative Steve Scalise of Louisiana. The headline was “America’s Lethal Politics,” and the editorial asked whether the Virginia shooting was evidence of how vicious American politics had become. The Times corrected the editorial the morning after it was published after readers pointed out the mistake.                                                                                                                                                                     , On the witness stand, the former Times editor who inserted the erroneous wording into the article, James Bennet, testified that the incident left him racked with guilt and that he had thought about it almost every day since. “It was just a terrible mistake,” he said.                                                                                                                                                                                                                                                                                                                                                                                                                    , Ms. Palin and her lawyers attempted to convince the jury that Mr. Bennet had acted out of animus toward her and, regardless of any contrition he later showed, was reckless in rushing to judgment about her.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Judge Rakoff rejected those claims in his ruling on Monday, saying that Ms. Palin had not produced evidence to support the idea that Mr. Bennet disregarded the truth either willfully or through his own recklessness. The ruling came in response to a routine procedural motion by Times lawyers to rule in its favor, which defendants have a right to do after the plaintiff has presented all of its evidence to the jury.                                                                                                                                                                                                                                                               , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/ny-empire-state-manufacturing-index </td>
   <td style="text-align:left;"> 2022-02-15 21:38:14 </td>
   <td style="text-align:left;"> NY Business Activity Returns to Growth in February </td>
   <td style="text-align:left;"> The New York Empire State Manufacturing Index rose to 3.1 in February of 2022 from -0.7 in January, but below market expectations of 12.15. New orders and shipments held steady, and unfilled orders increased. Delivery times continued to lengthen. Labor market indicators pointed to a solid increase in employment and a longer average workweek. The prices paid index remained near its recent peak, and the prices received index reached a new record high. Plans for capital and technology spending remained strong. Looking ahead, while firms generally expect conditions to improve over the next six months, optimism dipped to its lowest level since mid-2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/producer-price-inflation-mom </td>
   <td style="text-align:left;"> 2022-02-15 21:37:00 </td>
   <td style="text-align:left;"> US Monthly Producer Inflation Rises to 1% </td>
   <td style="text-align:left;"> Producer prices in the US jumped 1% month-over-month in January of 2022, following an upwardly revised 0.4% rise in December and the double of market forecasts of 0.5% as robust demand, labor and material shortages, and transportation disruptions were carried over to 2022. Cost of goods surged 1.3%, rebounding from a 0.1% fall in December, mainly due to motor vehicles and equipment (0.7%), food (1.6%) and energy (2.5%). Also, prices for services advanced 0.7%, the same as in the previous month, namely hospital outpatient care prices (1.6%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/currency </td>
   <td style="text-align:left;"> 2022-02-15 21:34:09 </td>
   <td style="text-align:left;"> Indian Rupee Strengthens Slightly </td>
   <td style="text-align:left;"> The Indian rupee strengthened towards 75.3 per USD, tracking the gain in domestic equities and a retreat in crude oil prices amid optimism of easing geopolitical tensions between Russia and Ukraine. Meanwhile, on the domestic front, India’s producer inflation came at a 4-month low of 12.96% in January while its consumer inflation rose to a 7-month high of 6.01%, topping Central Bank’s upper target of 2-6%. However, the RBI said that such a high figure should not create any panic as it is mostly due to a base effect while maintaining the interest rate at a record low of 4% for the 10th time in a row in February to support economic recovery from the health crisis in contrast to faster Fed rate-hike bets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/lieberman-on-russia-ukraine-crisis-conflict-cant-end-without-putin-doing-something-aggressive </td>
   <td style="text-align:left;"> 2022-02-15 21:32:57 </td>
   <td style="text-align:left;"> Lieberman on Russia-Ukraine crisis: Conflict ‘can’t end’ without Putin ‘doing something aggressive’ </td>
   <td style="text-align:left;"> Former Sen. Joe Lieberman argues Vladimir Putin still has 120,000 troops on Ukraine border and 'it's hard to imagine that he's not going to do something.'                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Former Sen. Joe Lieberman joined "Mornings with Maria" Tuesday to voice his concerns over the Russia-Ukraine conflict, despite President Vladimir Putin withdrawing some troops from the border, arguing the crisis "can't end without [Putin] doing something aggressive."                                                                                                                                                                                                                                                                                                                                                                                             , JOE LIEBERMAN: Well, Putin is a fox. He's calculating and he's not to be trusted. We've seen it before, so I don't take anything but a kind of curious interest in the fact that he has moved 10,000 of his troops back from the Ukrainian border. He still has 120,000 there, and it's hard to imagine that he's not going to do something. He has a choice now, he is either going to move into parts of Ukraine to justify all the money he's spent to bring his troops to the Ukrainian border, or he's going to try to extract the promise from the US and NATO, all the provinces we should not give him. So I continue to be very concerned about the situation. , RUSSIA CONFLICT STOKES ENERGY CONCERNS AS GAS PRICES CONTINUE TO CLIMB                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , It can't end without [Putin] doing something aggressive. I think the U.S. and NATO right now ought to tell him if he goes into eastern Ukraine, he is also going to be suffering great economic penalties from the U.S. In my opinion, if he [Putin] does that, one of the things we got to do right afterward is move to bring Ukraine into NATO. So that Putin will never be able to menace the Ukrainian people, which don't want him to lead them again.                                                                                                                                                                                                            , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , WATCH THE FULL INTERVIEW BELOW:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Former Sen. Joe Lieberman discusses the Russia-Ukraine conflict as Putin withdraws troops from border, and the U.S. returning to Iran Nuclear Deal talks following the Afghanistan withdrawal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/housing-starts </td>
   <td style="text-align:left;"> 2022-02-15 21:22:46 </td>
   <td style="text-align:left;"> Canada Housing Starts Unexpectedly Fall in January </td>
   <td style="text-align:left;"> Housing starts in Canada decreased 3 percent over a month earlier to 230,754 units in January of 2022, missing market expectations of 245,000 units, according to the Canada Mortgage and Housing Corporation (CHMC). Urban starts decreased by 5 percent, mostly due to a 9 percent drop in multiple urban starts to 144,332 units, while single-detached urban starts declined a softer 7 percent to 60,096 units. Rural starts were estimated at a seasonally adjusted annual rate of 26,326 units. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/kazakhstan/industrial-production </td>
   <td style="text-align:left;"> 2022-02-15 21:19:30 </td>
   <td style="text-align:left;"> Kazakhstan Industrial Output Slows in January </td>
   <td style="text-align:left;"> Industrial production in Kazakhstan rose 2.9 percent year-on-year, slowing from a 8.9 percent rise in the previous month which was the highest gain since August of 2017. Output slowed for mining &amp; quarrying (7.2 percent vs 11.6 percent in December); while declined for both manufacturing (-0.7 percent vs 8.5 percent) and electricity, gas, steam and air conditioning supply (-3.3 percent vs -5.8 percent). On a monthly basis, industrial production shrank 18.9 percent , compared to a 10.8 percent increase in December. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/trp:us </td>
   <td style="text-align:left;"> 2022-02-15 21:08:55 </td>
   <td style="text-align:left;"> Transcanada USA earnings above expectations at 1.06 USD </td>
   <td style="text-align:left;"> Transcanada USA (TRP) released earnings per share at 1.06 USD, compared to market expectations of 0.84 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/botswana/inflation-cpi </td>
   <td style="text-align:left;"> 2022-02-15 20:45:00 </td>
   <td style="text-align:left;"> Botswana January Inflation Rate Highest since 2009 </td>
   <td style="text-align:left;"> Botswana’s annual inflation rate quickened to 10.6 percent in January of 2022 from 8.7 percent in the previous month. That was the highest rate since March of 2009. Main upward pressure came from prices of transport (26.7 percent vs 18.3 percent in December); alcoholic beverages &amp; tobacco (9.7 percent vs 9.4 percent); housing &amp; utilities (8.1 percent vs 8.2 percent); miscellaneous goods &amp; services (7.7 percent vs 7.2 percent) and food &amp; non-alcoholic beverages (7 percent vs 7.2 percent). On a monthly basis, consumer prices inched up 2.2 percent, the steepest increase since last April. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/15/stocks-making-the-biggest-moves-in-the-premarket-monster-beverage-constellation-brands-arista-networks-and-more-.html </td>
   <td style="text-align:left;"> 2022-02-15 20:41:57 </td>
   <td style="text-align:left;"> Stocks making the biggest moves in the premarket: Monster Beverage, Constellation Brands, Arista Networks and more </td>
   <td style="text-align:left;"> , Take a look at some of the biggest movers in the premarket:                                                                                                                                                                                                                                                                                                                                               , Monster Beverage (MNST), Constellation Brands (STZ) – Merger talks between Monster Beverage and Constellation Brands are progressing, according to people familiar with the matter who spoke to Bloomberg. Those people say an agreement between the two companies could be reached within weeks if the talks go smoothly. Constellation gained 2.2% in the premarket while Monster Beverage rallied 3.1%., Arista Networks (ANET) – Arista Networks reported quarterly earnings of 82 cents per share, 9 cents a share above estimates. The networking software and services company's revenue topped Wall Street forecasts as well. Arista also issued an upbeat forecast, helping its shares surge 10.1% in the premarket.                                                                                         , Restaurant Brands (QSR) – The restaurant operator beat estimates by 4 cents a share, with quarterly earnings of 74 cents per share. Revenue came in above estimates as well. Burger King's comparable-store sales beat analysts' forecasts, helping to offset misses at the Tim Hortons and Popeyes chains.                                                                                               , BorgWarner (BWA) – The automotive components maker reported quarterly profit of $1.06 per share, well above the 75 cents a share consensus estimate. Revenue also came in above forecasts. BorgWarner's full-year earnings forecast is shy of analysts' estimates, however, despite an expected improvement in organic sales. BorgWarner rose 1% in premarket trading.                                    , Marriott (MAR) – Marriott shares jumped 3% in the premarket after the hotel operator beat top- and bottom-line forecasts for its latest quarter. Marriott earned $1.30 per share, 31 cents a share above estimates as occupancy rates increased amid a rise in vaccinations.                                                                                                                              , Zoetis (ZTS) – Zoetis was up 2% in premarket trading on better-than-expected quarterly results. Zoetis beat estimates by 4 cents a share, with quarterly earnings of $1.00 per share as improvement in its pet products business offset tepid results for livestock product sales.                                                                                                                        , Tower Semiconductor (TSEM) – Intel (INTC) announced a deal to buy the Israeli chipmaker for $53 per share, or $5.4 billion, a 60% premium over Tower's Monday closing price. Tower makes chips for a wide variety of industries including medical, automotive and consumer products. Tower Semiconductor soared 44.6% in premarket action, while Intel added 1.6%.                                        , Advance Auto Parts (AAP) – Advance Auto Parts beat estimates by 10 cents a share, with quarterly profit of $2.07 per share. The auto parts retailer's revenue also beat analysts' forecasts. Advance Auto's sales were higher than a year before, but profit was lower as it dealt with inflationary headwinds. Shares fell 1% in premarket action.                                                       , Avis Budget (CAR) – The company reported better-than-expected profit and revenue for its latest quarter, as increases in rental activity and in revenue per day helped offset higher expenses.                                                                                                                                                                                                            , Intuit (INTU) – Intuit lowered its current-quarter forecast as tax season gets off to a slow start. The maker of the popular TurboTax software maintained its full-year forecast, however, suggesting the company believes revenue was simply be pushed to a later quarter. Intuit fell 1% in premarket trading.                                                                                          , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                    , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                    , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                          , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                          , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                        , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/iqv:us </td>
   <td style="text-align:left;"> 2022-02-15 20:11:10 </td>
   <td style="text-align:left;"> IQVIA Holdings Inc earnings above expectations at 2.55 USD </td>
   <td style="text-align:left;"> IQVIA Holdings Inc (IQV) released earnings per share at 2.55 USD, compared to market expectations of 2.43 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mar:us </td>
   <td style="text-align:left;"> 2022-02-15 20:11:04 </td>
   <td style="text-align:left;"> Marriott International earnings above expectations at 1.30 USD </td>
   <td style="text-align:left;"> Marriott International (MAR) released earnings per share at 1.30 USD, compared to market expectations of 1.00 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/fis:us </td>
   <td style="text-align:left;"> 2022-02-15 20:10:57 </td>
   <td style="text-align:left;"> Fidelity National Information Services earnings above expectations at 1.92 USD </td>
   <td style="text-align:left;"> Fidelity National Information Services (FIS) released earnings per share at 1.92 USD, compared to market expectations of 1.90 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/zts:us </td>
   <td style="text-align:left;"> 2022-02-15 20:10:50 </td>
   <td style="text-align:left;"> Zoetis earnings above expectations at 1.00 USD </td>
   <td style="text-align:left;"> Zoetis (ZTS) released earnings per share at 1.00 USD, compared to market expectations of 0.96 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/kyrgyzstan/inflation-cpi </td>
   <td style="text-align:left;"> 2022-02-15 20:08:00 </td>
   <td style="text-align:left;"> Kyrgyzstan January Inflation Rate Holds at 11.2% </td>
   <td style="text-align:left;"> Kyrgyzstan’s annual inflation rate remained steady at 11.2 percent in January of 2022, same as that of the previous month. It was the smallest increase in consumer prices since May of 2021 amid a slowdown in cost of food &amp; non-alcoholic beverages (12.5 percent vs 13.3 percent); housing and utilities (6.2 percent vs 6.6 percent) and household items &amp; appliances (10.2 percent vs 10.4 percent). Meanwhile, prices advanced at a faster pace for clothing and footwear (6.8 percent vs 6.5 percent), alcoholic beverages &amp; tobacco (14.7 percent vs 11.4 percent) and transport (27.7 percent vs 25.8 percent). On a monthly basis, consumer prices went up 1 percent, slowing from a 1.3 percent rise in December. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60373405?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-15 20:02:21 </td>
   <td style="text-align:left;"> UK wage growth lags rising cost of living </td>
   <td style="text-align:left;"> UK wage growth continued to lag behind the rising cost of living between October and December, figures show.                                                                                                                                                                                                                                                            , Wages rose, but when taking inflation into account, pay showed a 0.8% fall from a year earlier, said the Office for National Statistics (ONS).                                                                                                                                                                                                                          , Latest figures also show that the unemployment rate fell to 4.1% while job vacancies hit a fresh record high.                                                                                                                                                                                                                                                           , There are signs that these pressures might feed through to faster wage growth in the coming months.                                                                                                                                                                                                                                                                     , According to the ONS, employees' regular pay, excluding bonuses, grew by 3.7% between October and December from a year earlier - which is high compared with rates seen over the last decade.                                                                                                                                                                           , However, the rising cost of food, energy and household goods has pushed inflation up by 5.4% in the 12 months to December. The ONS said real wages in the October to December period fell by 0.8% from a year earlier.                                                                                                                                                  , The Bank of England has warned this squeeze on workers will get worse, with inflation set to rise above 7% this year.                                                                                                                                                                                                                                                   , But the ONS said early estimates suggest employers are starting to push up wages further and faster in response.                                                                                                                                                                                                                                                        , It said that for workers on payrolls in January, median monthly wages increased by 6.3% compared with the same month last year, and they were 10.3% higher than before the pandemic in February 2020.                                                                                                                                                                   , It added that wage rises for payrolled workers last month appeared to easily outpace inflation in some industries, such as science, finance and insurance, information and communication, and hotels.                                                                                                                                                                   , Employers are having to increase salaries as they face a continuing shortage of workers.                                                                                                                                                                                                                                                                                , Meanwhile the number of job vacancies between November and January hit another record of 1.3 million, the ONS said, with most industries finding it harder to recruit.                                                                                                                                                                                                  , "The good news is that the UK economy is continuing to create jobs," said Matthew Percival, director for people and skills at the CBI.                                                                                                                                                                                                                                  , "The bad news is that businesses are struggling to hire and pay is failing to keep up with inflation."                                                                                                                                                                                                                                                                  , Lee Powell, chief executive of GMI Construction Group, which employs 200 people in Leeds, told the BBC that the combination of inflation and skills shortages was a "headache at the moment".                                                                                                                                                                           , "In the construction industry we've seen unbelievably rapid inflation across materials... and we're in a situation now where the demands for wage increases are somewhat eye-watering.                                                                                                                                                                                  , "You'd automatically assume you could pass those prices straight on to the developer or to the end user but it's not as easy as that."                                                                                                                                                                                                                                  , The governor of the Bank of England recently sparked controversy when he urged workers not to ask for big pay rises, to help stop inflation from rising out of control.                                                                                                                                                                                                 , Andrew Bailey said that while it would be "painful" for workers to accept that prices would rise faster than their wages, he added that some "moderation of wage rises" was needed to prevent inflation becoming entrenched.                                                                                                                                            , The GMB union branded the idea a "sick joke" while the government distanced itself from the comments.                                                                                                                                                                                                                                                                   , Earlier this month, the Bank of England raised interest rates to 0.5% in an attempt to tame inflation.                                                                                                                                                                                                                                                                  , Paul Dales, chief UK economist for Capital Economics, said the Bank was likely to take a more aggressive approach to rate increases this year and next given the economic picture.                                                                                                                                                                                      , "Employment has recouped the falls after the furlough scheme, the unemployment rate has fallen to pre-Covid levels, job vacancies are at a record high and wage growth is rising," he said.                                                                                                                                                                             , "That's a recipe for more interest rate hikes, perhaps from 0.5% now to 1.25% this year and to 2% next year."                                                                                                                                                                                                                                                           , The latest estimates of wage increases for payrolled employees appear to confirm the Bank of England's fear that pay rises are taking off - one of the biggest reasons they've raised interest rates twice in a row.                                                                                                                                                    , While they are early estimates and subject to revision, they suggest that pay in January was up by just over 10% compared with February 2020. That is the first time we've heard of double-digit pay rises, even over two years, in a very long time.                                                                                                                   , Part of the reason is the tightest labour market we've had in living memory. Staff quit their jobs at record rates to take a better offer from another employer. Firms that want to keep people are having to pay more to retain them.                                                                                                                                  , This is hard to reconcile with the more reliable but less up-to-date quarterly figures, showing pay rises at 3.7%, lagging price inflation. But statistical confusion will work itself out over time. Meanwhile, these figures will do nothing to discourage the Bank of England from raising interest rates a third time the next time its interest rate setters meet. , Behind the faces leading US far right political movements online                                                                                                                                                                                                                                                                                                        , Can her obsession drive her to finish what he couldn't?                                                                                                                                                                                                                                                                                                                 , Whitney Houston's extraordinary life story with insights from those closest to her                                                                                                                                                                                                                                                                                      , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/namibia/inflation-cpi </td>
   <td style="text-align:left;"> 2022-02-15 19:58:01 </td>
   <td style="text-align:left;"> Namibia January Inflation Rate at 3-Year High </td>
   <td style="text-align:left;"> The annual inflation rate in Namibia edged up to 4.6 percent in January of 2022, from 4.5 percent in December. It was the highest level since January of 2019. Upward pressure came from prices of transport (13.5 percent vs 14.3 percent); food &amp; non-alcoholic beverages (5.6 percent vs 5.1 percent in December), such as meat (10.6 percent), oils &amp; fats (12.7 percent), and fruits (12.8 percent); furnishings (8.9 percent vs 4.3 percent); alcoholic beverages &amp; tobacco (3.9 percent vs 3.8 percent); housing &amp; utilities (1.3 percent vs 1.2 percent); hotels &amp; restaurants (9 percent vs 1.9 percent), in particular accommodation services (14.6 percent); and education (3.3 percent vs 0.8 percent). On a monthly basis, consumer prices were up 1.1 percent, accelerating from a 0.4 percent gain in the prior month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-02-15 19:56:05 </td>
   <td style="text-align:left;"> Madrid Shares Rebound on Tuesday </td>
   <td style="text-align:left;"> The Ibex 35 rose 1.3% to trade around the 8,680 on Tuesday, partially rebounding from the last session’s 2.6% decline as investors weighed on signs of military de-escalation in the Russian border with Ukraine after the Kremlin said that some of its units were returning to their bases, ahead of German Chancellor Scholz’s meeting with President Putin. On the corporate front, gains were led by Siemens Gamesa (5%) as investors weighed on the restructuring efforts by the wind turbine manufacturer. At the same time, Rovi shares jumped 4.4% after the European Commission authorized the marketing for Okedi, the drug maker’s new schizophrenia treatment. On the data front, January's domestic consumer inflation was revised higher to 6.1%, although still easing from December's near 30-year high of 6.5% and the first decrease in price growth since February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2022-02-15 19:52:00 </td>
   <td style="text-align:left;"> Dollar Eases Back from Two-Week Highs </td>
   <td style="text-align:left;"> The dollar index bottomed around the 96 level, moving away from a two-week peak of 96.44 touched in the prior session as the risk-on mood, backed by easing geopolitical tensions involving the West, Russia, and Ukraine, spooked investors away from the safe-haven currency. Russian foreign minister said that while large-scale drills across the country continued, some Southern and Western military districts units have completed their exercises and started returning to bases. Putting a floor under prices were recent remarks from Louis Fed president James Bullard that the central bank needs to be aggressive in fighting inflation after calling for a 100bps in an interest rate hike by July. Investors now await the FOMC minutes on Wednesday and speeches from several Fed officials this week for fresh clues on the timing and magnitude of rate hikes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hungary/gdp-growth-annual </td>
   <td style="text-align:left;"> 2022-02-15 19:51:00 </td>
   <td style="text-align:left;"> Hungary GDP Grows More than Expected in Q4 </td>
   <td style="text-align:left;"> Hungary’s gross domestic product expanded 7.2 percent from a year earlier in the fourth quarter of 2021, above market expectations of a 5.5 percent advance, preliminary data showed. On a seasonally adjusted quarterly basis, the economy grew 2.1 percent, accelerating from an upwardly revised 0.9 percent increase in Q3. Considering full 2021, Hungary's GDP advanced by a record 7.1 percent, rebounding from a 4.9 contraction in 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/palladium </td>
   <td style="text-align:left;"> 2022-02-15 19:50:00 </td>
   <td style="text-align:left;"> Palladium Falls on Easing Russia-Ukraine Tensions </td>
   <td style="text-align:left;"> Palladium futures traded around $2250 an ounce in mid-February, falling from its 4-month high of $2376 hit on January 27th amid easing supply concerns. Fears of export disruption from Russia, the metal’s top supplier temporarily eased after some Russian troops started returning to their bases from the Ukrainian border. A Russian invasion of Ukraine could hamper exports from Russia as both the US and EU were thinking of imposing further sanctions on Russia’s biggest banks, restricting the country’s ability to convert rubles for dollars. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/netherlands/personal-spending </td>
   <td style="text-align:left;"> 2022-02-15 19:35:31 </td>
   <td style="text-align:left;"> Dutch Household Spending Continues to Rise </td>
   <td style="text-align:left;"> Household consumption in the Netherlands increased 4.5% year-on-year in December of 2021, prompted by gains in spending on both services (7.1%) and durable goods (5.3%). Within services, consumption increased for telephone and internet subscriptions, insurance, hairdresser, restaurants and football matches. The catering industry, amusement parks, theatres, Cinemas, zoos and swimming pools had to close their doors from December 19, but in December 2020 these companies were closed for the entire month. Spending was also higher for clothing, shoes, home furnishings and electrical equipment. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-02-16 08:51:58 UTC +8

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
   <td style="text-align:left;"> 2022-02-16 08:51:11 </td>
   <td style="text-align:left;"> $SPY https://www.youtube.com/watch?v=YoYoDiRRuIg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:50:49 </td>
   <td style="text-align:left;"> latex1a1ab8030100852fabe1172fbcddcc32BKKT +40.65%  
💎$CSCW +38.34% 💎$CIDM +17.81%  
Wishing everyone success this week...💫❤️🕊️ 
 
⭐️ $KAVL Momentum Alert   
🚀 Increase from alert: +269.55% 
Options: 
Closed $SPY Calls 448 Feb 18 at 2.10 Returns +52.88% 
Closed $SPY Calls 448 Feb 16 at 1.24 Returns +52.34% 
⭐️ $BKKT Momentum Alert 
🚀 Increase from alert: +40.65% 
⭐️ $CSCW Momentum Alert 
🚀 Increase from alert: +38.34% 
⭐️ $CIDM Momentum Alert 
🚀 Increase from alert: +17.81% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:50:22 </td>
   <td style="text-align:left;"> $SPY are we killing this tomorrow or giving it mouth to mouth? Asking for a friend. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:50:19 </td>
   <td style="text-align:left;"> $SPY literally zero reason to be red after hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:50:01 </td>
   <td style="text-align:left;"> $SPY Inverse Cramer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:49:39 </td>
   <td style="text-align:left;"> $SPY $SQQQ $TZA  $dow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:49:34 </td>
   <td style="text-align:left;"> $SPY $QQQ 

No lie, and not trying to gaslight, but if ever there were a spot for a limit down day it’s tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:49:34 </td>
   <td style="text-align:left;"> $SPY hey guys….  If Russia invades the world tomorrow…. I will miss all you bulls and all you bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:49:29 </td>
   <td style="text-align:left;"> $SPY Cramer said you guys should buy. That’s all you need to know 🏃🏽‍♂️🏃🏽‍♂️🏃🏽‍♂️🏃🏽‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:48:06 </td>
   <td style="text-align:left;"> $MRNA despite the price moving up today, the options flow was incredibly $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:47:34 </td>
   <td style="text-align:left;"> $SPY most stocks were bigly up today but indexes 1-2% and whatever moved happened was 40 mins this AM .

? Some big fish likely  planned it to come out of their pos . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:47:24 </td>
   <td style="text-align:left;"> $SPY more blood tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:47:22 </td>
   <td style="text-align:left;"> $SPY 

   FED&amp;#39;s Will be running
Off their balance sheet
Faster than anyone realises
And THATs what will make the
Markets sell off with
Tomorrow&amp;#39;s FED minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:46:28 </td>
   <td style="text-align:left;"> $SPY holding put after hours after biden speech lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:46:25 </td>
   <td style="text-align:left;"> $SPY bear mad if gap gets closed overnight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:46:25 </td>
   <td style="text-align:left;"> $DWAC My wife is home watching the kids tonight while I go out with my girlfriend $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:46:17 </td>
   <td style="text-align:left;"> $SPY 🧠 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:46:16 </td>
   <td style="text-align:left;"> $SPY wtf?? Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:46:06 </td>
   <td style="text-align:left;"> $SPY so we pump EOD just to deflate AH. 

Ah how the premium sellers are undefeated, Neva loss. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:45:54 </td>
   <td style="text-align:left;"> $SPY none of these companies that interesting, I am only interested in getting rich playing short term options </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:45:49 </td>
   <td style="text-align:left;"> $SPY there are literally people -- CURRENTLY -- in solitaire confinement for doing LESS... 
 
LET THAT SINK IN! 
 
https://www.foxnews.com/politics/hillary-clinton-dodges-questions-durham-probe-developments </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:45:43 </td>
   <td style="text-align:left;"> $SPY This price action today caught me off guard.  We did bounce off .618 Fib yesterday but MACD Histo looked like about to flip negative. I thought down to .786 (428) consolidate for 3-4 days then up.... What are you guys seeing? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:45:30 </td>
   <td style="text-align:left;"> $SPY oh no -.3% drop🥴 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:45:30 </td>
   <td style="text-align:left;"> $SPY I felt bullish but now I don&amp;#39;t know </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:45:13 </td>
   <td style="text-align:left;"> $SPY 🤣🤣🔥🔥 I have mad respect for internet characters that gained sizeable following representing either perma bear or bull on ST SPY board. Especially bears for risking account ban.

Must maintain bull status when spx drips 2%

Must maintain bear status when spx rips 2% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:44:53 </td>
   <td style="text-align:left;"> $SPY is it possible to see 450+ anytime in the next few months or was today it? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:44:45 </td>
   <td style="text-align:left;"> $SPY Please open at $446 and sell off afterwards, I’m not interested in buying calls until the gap is filled and price closes above $446 with a continuation for a few days after. That seems like a lot to ask for in this market which is why I’m not interested in taking calls…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:44:32 </td>
   <td style="text-align:left;"> $SPY BEARS ARE NOTHING MORE THAN CHINA BOOTLICKERS GETTING FUCKED FOR OVER 100 YEARS BETTING AGAINST MURICA LOL THEY NEVER LEARN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:43:50 </td>
   <td style="text-align:left;"> $SPY you guys really relying on an app that’s available to the public nobody to track a war plan that can cause a world war?💀
What’s the logic bears?😂💀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:43:30 </td>
   <td style="text-align:left;"> $SPY It’s me. I want to get rich with short term options. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:43:15 </td>
   <td style="text-align:left;"> $SPY i felt like doing something weird yesterday and sold puts on arkk.  worked out anyway. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:42:28 </td>
   <td style="text-align:left;"> $SPY Lets be honest. No one wants to buy this. Everyone just trying to get rich quick with short term options </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:42:26 </td>
   <td style="text-align:left;"> $SPY it must have been you dumbass bulls that bought this at 1.30a.m. this morning to bring this thing up. Who else in they&amp;#39;re right mind would buy this p.o.s right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:42:16 </td>
   <td style="text-align:left;"> $SPY 🔥 gap down premarket </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:42:05 </td>
   <td style="text-align:left;"> $SPY dip little more I want to go long.. 460 coming right up .. opex friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:42:04 </td>
   <td style="text-align:left;"> $SPY I think I should pay brad Pitt to play me on fast money. Go over my charts and joke around with the CNBC guys in Ben Rickert character. This is what I would do if I was a billionaire. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:42:01 </td>
   <td style="text-align:left;"> $SPY so it begins </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:41:47 </td>
   <td style="text-align:left;"> $SPY looks like Alex Baldwin is getting sued. Only reason I’d be bearish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:41:42 </td>
   <td style="text-align:left;"> Excellent, welcome to Crash Wednesday, this post is approved by my good friends at Seeking Alpha moderating my posts for my profits, hopefully for you too. Carry on sticking forks in the stock markets at large overpriced sincenthe beginning of the recession in 2009, quite realistically 1999 imho re due diligence. Good health and trading to all. https://www.investing.com/indices/indices-futures  Thank dog that I am here to help 🐻❤😈✔👍😁 @Profit_Maker https://stocktwits.com/Profit_Maker 🤑 $djia $SPX $NDX $spy $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:41:37 </td>
   <td style="text-align:left;"> $SPY nobody believes this fake after hours dump 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:41:33 </td>
   <td style="text-align:left;"> $SPY I got (was?) accused of being a &amp;quot;bot&amp;quot; earlier, lmao...   
 
And then another guy said (implied) my P&amp;amp;L&amp;#39;s (and strategies) are &amp;quot;worthless,&amp;quot; because some of my trading (about 10%) involves penny-stocks (pump &amp;amp; dumps). 
 
I asked my kids if they care that 10% of my trades come from &amp;quot;low-float-penny-stocks,&amp;quot; and they glared back with a confused look on their faces 🤷‍♂️ 
 
ps:  called the $SPCE long (you&amp;#39;re welcome); saw $TISI coming from a mile away; plan on trading $RBLX all day tomorrow (both ways; but mostly short at/under 65), and can&amp;#39;t wait to take advantage of the volatility in $NVDA (and AMD).   
 
ps...  discord link NOT in the description below 🙊🙊🙊 
 
-- --- -  
pps...  anybody wanna&amp;#39; bet I catch at least a few off guard with the &amp;quot;discord&amp;quot; comment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:41:25 </td>
   <td style="text-align:left;"> $SPY 

   Can I get a Limit 👇 Down???

... I&amp;#39;m pumped up on 
Hopium </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:41:20 </td>
   <td style="text-align:left;"> $SPY $QQQ futes basically crashing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:40:59 </td>
   <td style="text-align:left;"> $SPY Think about it. If you were worth 100s of billions and also president of the 3rd most power nation on earth…. You can make some serious cash playing the markets. Especially the oil markets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:40:41 </td>
   <td style="text-align:left;"> latex48f387973cac9cf8fc6fb1641ac500b5ARKW) and ARK Fintech Innovation ETF ($ARKF) took part in the buying as ARKW grabbed 97K shares and ARKF purchased 48K shares. 
 
On the other hand, Snell feels that the pandemic has unfairly hurt SE, and the drop in its share price does not have to do with the company&amp;#39;s fundamentals. 
 
Snell also noted that SE currently owns the e-commerce platform Shopee, which is the leading shopping app in Indonesia. 
 
https://seekingalpha.com/news/3800337-cathie-wood-roderick-snell-are-bullish-on-sea-limited </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:40:23 </td>
   <td style="text-align:left;"> Get into assets $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:39:50 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $TQQQ $SOXL 

When experts talk, you shut up and listen. 🤫 

👇🏿👇🏿👇🏿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:39:29 </td>
   <td style="text-align:left;"> $SPY https://abcnews.go.com 😑😬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:39:21 </td>
   <td style="text-align:left;"> $SPY 

  It&amp;#39;s okay 🐻 Bears

They take the stairs...☝️

    ... We take the WINDOW 🪟 👇

          ... FAST we will go! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:39:12 </td>
   <td style="text-align:left;"> $SPY Current futes outlook:

a. Limit up / 18% chance
b. Limit down / 0.01% chance
c. Green / 94% chance
d. Red / 1% chance
e. Flat / 5% chance

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:39:06 </td>
   <td style="text-align:left;"> $SPY when lambo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:39:02 </td>
   <td style="text-align:left;"> $SPY want to know how you can tell things are getting bad? $AMZN is sending workers home with pay because they don&amp;#39;t have enough work for them. If no one is buying from Amazon everyone else is definitely screwed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:39:01 </td>
   <td style="text-align:left;"> $SPY China and Russia are the unbeatable team. One has the smarts and weaponry, the other has the people. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:38:46 </td>
   <td style="text-align:left;"> $GME $SPY  Blatant corruption-

https://www.reddit.com/r/Superstonk/comments/st33ng/what_confounds_me_is_how_we_are_at_100/?utm_medium=android_app&amp;amp;utm_source=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:38:44 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:38:43 </td>
   <td style="text-align:left;"> $SPY Putin spends 50 billion shorting the global markets, then invades Ukraine making 100s of billions to pay for war. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:38:42 </td>
   <td style="text-align:left;"> $SPY This will move higher tomorrow, but top out at 450$. Vix will start moving higher after tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:38:38 </td>
   <td style="text-align:left;"> $SPY don&amp;#39;t you think guys that tomorrow we need at first to close  todays gap up and  even move lower and then we could be at 450-460 price range by Friday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:38:38 </td>
   <td style="text-align:left;"> $SPY Pat Voss up next on Mad Money? The Vix session and looking at the s&amp;amp;p. Ends segment with &amp;quot;fuk your opinion insert CNBC coworker name&amp;quot;? Then I refute his chart how wrong his thesis is. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:38:37 </td>
   <td style="text-align:left;"> $SPY Russia is just pumping and dumping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:38:04 </td>
   <td style="text-align:left;"> $SPY 🐂🇺🇸🐂🇺🇸🐂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:37:55 </td>
   <td style="text-align:left;"> $SPY since 11am EST to now, price has been flat like pancakes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:37:32 </td>
   <td style="text-align:left;"> $SPY major boobage </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:37:24 </td>
   <td style="text-align:left;"> $SPY This invasion shit is for the low IQ 
Putin could shutoff oil to the EU tomorrow if he wanted - there’re so many things not only he could he do but don’t let him get china 🇨🇳 involved- that’s his only Ally since Trump got screwed - they would much rather be on our team but democrats don’t want that because China 🇨🇳 is their #1 Contributor </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:37:13 </td>
   <td style="text-align:left;"> $SPY Volume sucked today… and now we have a gap to fill. GOOD LUCK 😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:37:09 </td>
   <td style="text-align:left;"> $SPY 
Is the Ukraine part of the United States? I went to public school. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:37:00 </td>
   <td style="text-align:left;"> $SPY let’s see if China goes and makes a move. After Russia goes ahead. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:36:34 </td>
   <td style="text-align:left;"> $SPY Holding these into tomorrow. Average is $1.13. Usually don&amp;#39;t hold overnight because of the Theta. But I&amp;#39;m up big today so I let them ride. Have a great night y&amp;#39;all. Hope you caught a couple trades today. God bless. ✌️😊🧑‍🎓🎯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:36:32 </td>
   <td style="text-align:left;"> $DWAC when truth social goes live I will be dumping my washed up wife for a new and improved girlfriend $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:36:30 </td>
   <td style="text-align:left;"> $SPY suspense is killing me... Hopefully we get that gap down tomorrow because this news was phony this morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:36:05 </td>
   <td style="text-align:left;"> $SPY so... who went long into top today? ya&amp;#39;ll ready for tomorrows 3am news cycle? any takers on ww3 announcement? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:35:59 </td>
   <td style="text-align:left;"> $SPY bears becareful, you know spy is a sleeping gaint, you will be stumped soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:35:53 </td>
   <td style="text-align:left;"> $QQQ $SPY 
The biggest mistake 99.9% of people make is having STRONG views on market directionality.  Strong convictions lead to excessive size and that’s what causes losses because everybody is wrong majority of the time 
But it’s ok to be generally long most of the time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:35:40 </td>
   <td style="text-align:left;"> $SPY Putin bought cheap puts with fake troop withdrawal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:35:35 </td>
   <td style="text-align:left;"> $SPY 👀
UH-OH: Whopping Percentage Of Dem Voters Want Hillary Investigated For Russiagate Scandal | The Daily Wire https://www.dailywire.com/news/uh-oh-whopping-percentage-of-dem-voters-want-hillary-investigated-for-russiagate-scandal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:35:33 </td>
   <td style="text-align:left;"> $SPY  
 
I promise to vote Joe Biden 2024 if this closes up 2% tmrw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:34:46 </td>
   <td style="text-align:left;"> $SPY bears wen crash…no fr I need to know </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:34:44 </td>
   <td style="text-align:left;"> $SPY the only gap I fill is when  I have to put the mattress back in place after my wife’s bf is done </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:34:24 </td>
   <td style="text-align:left;"> $SPY starting to see reports that anytime now Russia may make the call to invade. I’ll believe it when I see it but boy that would really make things interesting tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:34:18 </td>
   <td style="text-align:left;"> $SPY  BarChart Spy opinion is 8% Buy↘️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:34:18 </td>
   <td style="text-align:left;"> $SPY who buying this trash lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:34:11 </td>
   <td style="text-align:left;"> $SPY slept all day so I can shit post all night who’s with me baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:34:04 </td>
   <td style="text-align:left;"> $SPY who cares if Russia goes into Ukraine? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:33:41 </td>
   <td style="text-align:left;"> $SPY 40 year bull market in bonds coming to an end along with the consequences of suppressing rates for so long and ppl think they’re gonna replicate the boomer gains in the stock market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:33:34 </td>
   <td style="text-align:left;"> $SPY I can&amp;#39;t believe people try to chart this phoney bullshit yeah it might help your target but it&amp;#39;s a fucking ham sandwich </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:33:19 </td>
   <td style="text-align:left;"> $SPY probably sleeping in till 1:30 then hitting that fomc banger💯💯💯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:33:01 </td>
   <td style="text-align:left;"> $spy chart is screaming low 400s, several models back this analysis, it’s not a matter of if, it’s a matter of when? 👁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:32:59 </td>
   <td style="text-align:left;"> $SPY how does $FDX text me my package 📦 will be here Thursday and 10 min later I get a text  it’s now Monday 🤷‍♂️ get your shit together </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:32:52 </td>
   <td style="text-align:left;"> $SPY Biden running his mouth again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:32:35 </td>
   <td style="text-align:left;"> US $SPY ZeroHedge 😭 Where else am I going to get my doom/gloom news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:32:06 </td>
   <td style="text-align:left;"> $SPY Putin delivers troops from barracks to front lines and COVID test can&amp;#39;t be delivered. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:31:56 </td>
   <td style="text-align:left;"> $SPY  #DIA   the indexes retesting 9 and 26 day candle average line resistance..  buyers couldnt break them today and  closed right at resistance.   a retest of nearest support now in cards (blue line of $442 needed, to gain momentum to try and break above, unless can GAP over it)..  in the chop zone. worst case is channel down to stronger flat cloud support levels. will see how US Data  moves markets. 
 
. ichimoku cloud shows old flat cloud bottoms which = where price averages were. price tends to react to them as you can see all the levels with green lines..  this chart likely makes zero sense but i drew the lines to show price action at cloud levels.   
 
Wednesday has lots of things to  move market.  
VIX monthly option expiration,Full Moon, Fed Minutes, Retail sales, Housing data.  
 
GL.  knowing future and  past flat cloud levels are is nice imo.. support and resistance. just draw lines at anything flat on ichimoku cloud indicator. :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:31:46 </td>
   <td style="text-align:left;"> $SPY Death cross on the hourly. Potential for $438 tomorrow barring any hiccups. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:31:30 </td>
   <td style="text-align:left;"> $SPY we’re in the everything bubble. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:31:29 </td>
   <td style="text-align:left;"> $SPY knock knock call holders @_Ziggy_ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:31:13 </td>
   <td style="text-align:left;"> $SPY Bears cried for gap fill all day. MM will do you dirty and fill it overnight and gap up before morning. 🤣🤙🔥🔥🔥

The script. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:31:04 </td>
   <td style="text-align:left;"> $SPY I love you guys, it’s so funny seeing different people being specialists en every aspect of life
Military generals, historians, Marco economics, micro economics, pornstars, Christians, etc… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:30:51 </td>
   <td style="text-align:left;"> $SPY bloodbath tomorrow 🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:30:46 </td>
   <td style="text-align:left;"> $SPY anything less than a limit down would be anticlimactic at this point. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:30:09 </td>
   <td style="text-align:left;"> $SPY What happen After Hours ? My 443 puts might have a chance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:30:01 </td>
   <td style="text-align:left;"> $SPY just a few years ago Yellen was saying we’d never encounter another financial crisis in her lifetime.  Retard. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:29:56 </td>
   <td style="text-align:left;"> $SPY biggest head and shoulders in history forming on the SPY. Fed going to have to step in and buy indexes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:29:56 </td>
   <td style="text-align:left;"> Trade Recap: The Higher High Higher Low Setup $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/trade-recap-the-higher-high-higher-low-setup </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:29:50 </td>
   <td style="text-align:left;"> $SPY P.O.V of Brandon on his way to Europe after he was anonymously invited </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:29:32 </td>
   <td style="text-align:left;"> $SPY will be pretty nasty if futures gap  down below $441 and trap all call buyers from today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:29:15 </td>
   <td style="text-align:left;"> $SPY vix could retest near 23 tomorrow then markets crash after 2pm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:29:11 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX 
Are we no longer capable of pulling from darkness a future worthy of our efforts? Must we forever be lost in a sea of aimless misery? We should seek to go beyond our current plights. How much would men lying beneath the ground give just to feel the warmth of the sun one more time? We have no excuse not to continue on with our heads held high. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:29:02 </td>
   <td style="text-align:left;"> $SPY 

Bulls aka call holders to Bears aka put holders when futures are red this early: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:28:53 </td>
   <td style="text-align:left;"> $SPY I totally thought PPI was tomorrow. Why did we rip with worsening numbers? Maybe tomorrow will be the delayed reaction. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:28:49 </td>
   <td style="text-align:left;"> $SPY you know what’s funny is I’m not even trying to make fun of these “financial leaders”.  They embarrass themselves every day.  They’re a walking clown show of ignorance and failure.  And yet everyone trusts their life savings to them.  It’s mind boggling. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:28:37 </td>
   <td style="text-align:left;"> $SPY futures have already sold off over half of todays gains.. wow. trick n trap co really out there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:28:32 </td>
   <td style="text-align:left;"> $SPY 

Seems like a huge number  of course but actually not a good sign for NFL  in the sense that relative to the current population it&amp;#39;s a shrinking audience. 

&amp;quot;Super Bowl 2022 attracted more than 112 million viewers, but failed to top record&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:28:32 </td>
   <td style="text-align:left;"> $SPY $BTC.X $ETH.X 

 Keep The Fear Alive Cnn 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:27:57 </td>
   <td style="text-align:left;"> Daily Recap 405% total gains. 
 
Top gainers $SPY $NVDA $RBLX  
 
Analysts; 
u.trhub.net/noob 
u.trhub.net/vocaloid 
u.trhub.net/dcharts 
 
linktr.ee/thetradehub 
 
SPY closed +1.61% 
NVDA closed +9.18% 
RBLX closed +7.16% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:27:43 </td>
   <td style="text-align:left;"> $SPY Bulls if you leave this gap open it’s going to be like 1 step forward and 2 steps back…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:27:36 </td>
   <td style="text-align:left;"> $SPY Why stop at raising rates at 10%. Let’s go for the high score. This is America. Go for 100! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:27:35 </td>
   <td style="text-align:left;"> $SPY A couple months ago the White House was saying they can’t do anything about gas prices, today Biden said the Russia sanctions could shoot gas prices up but they’re taking steps to prevent that. Bad move, obvious bluff. Don’t give Putin a reason to prove countries are unwilling to tolerate a spike in gas prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:27:26 </td>
   <td style="text-align:left;"> $SPY https://gettr.com/post/purpnac943 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:27:13 </td>
   <td style="text-align:left;"> $spy so wait, can I get promoted to US treasury secretary or head of the federal reserve if I’m a total moron? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:27:12 </td>
   <td style="text-align:left;"> $TLT $SPY bonds or blondes? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:27:04 </td>
   <td style="text-align:left;"> $SPY fed raising 10% rates </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:26:53 </td>
   <td style="text-align:left;"> $SPY that pump right before close to load cheaper puts before tomorrow... could end up being a wicked bull trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:26:29 </td>
   <td style="text-align:left;"> $SPY So you are telling me if Bullard and Biden never said a word last Thursday &amp;amp; Friday…my calls exp Fri woulda printed ??

25 bsp and no war 

They should be imprisoned for treason </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:26:28 </td>
   <td style="text-align:left;"> $SPY spy’s biggest earnings come out tmw , good luck shorting this tmw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:26:06 </td>
   <td style="text-align:left;"> $SPY  Enjoy your 1.5% on half the normal volume.  The neckline will break once the Fed starts hiking rates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:25:56 </td>
   <td style="text-align:left;"> $DJIA even a broken clock is right twice a day. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:25:55 </td>
   <td style="text-align:left;"> $SPY buying the rip in this environment is like being hammered and eating Taco Bell. It’s awesome until the next morning hits. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:25:53 </td>
   <td style="text-align:left;"> $SPY glad I actually have a brain and held my puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:25:49 </td>
   <td style="text-align:left;"> $SPY frick, it’ll went up .25....I just lost everything </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:25:24 </td>
   <td style="text-align:left;"> $SPY fed minutes tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:25:13 </td>
   <td style="text-align:left;"> $SPY war cancelled </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:25:12 </td>
   <td style="text-align:left;"> $SPY just saying he’s going in. Bozo will do nothing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:25:11 </td>
   <td style="text-align:left;"> $SPY If all the posts are red, you short. If all the posts are green, you still short. Because THIS MARKET IS MADE UP. $400 TOMORROW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:24:47 </td>
   <td style="text-align:left;"> $SPY Biden can’t even speak 🗣 but democrats ignore that part but god.  forbid you spell something wrong - Dems will come for you ! 😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:24:44 </td>
   <td style="text-align:left;"> $SPY $BTC.X $ETH.X 

Financial Freedom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:24:33 </td>
   <td style="text-align:left;"> $SPY Everyone knows the best confirmation is to check Stocktwits. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:24:05 </td>
   <td style="text-align:left;"> $SPY fuck. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:24:03 </td>
   <td style="text-align:left;"> $SPY $QQQ buy $lmt $rtx .. see satellite images </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:23:54 </td>
   <td style="text-align:left;"> $SPY vlad is shorting and then going into calls....manipulation and financial terrorism to the max. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:23:53 </td>
   <td style="text-align:left;"> $SPY I got a feeling .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:23:44 </td>
   <td style="text-align:left;"> $SPY who watches the &amp;quot;invicta wathes: up to 80% off&amp;quot; show on channel 244? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:23:37 </td>
   <td style="text-align:left;"> $SPY  under the hood  - hourly chart 
 
just chop chop action... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:23:24 </td>
   <td style="text-align:left;"> $spy hey look guys it’s peak inflation!  Now you can look forward to only 8% a year from now on! Yay! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:23:18 </td>
   <td style="text-align:left;"> $SPY All I see is some Island boys bulltards abd their trying to make it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:23:05 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:23:04 </td>
   <td style="text-align:left;"> $SPY $QQQ Know what is ironic compared to Volcker era....politicians were crying to ease the hawkishness. Now it seems the yelling is for more hawkishness and fed just may not do that. They either lowered their inflation expectations Monday because they are hiking hard or they really convinced inflation has peaked 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:22:55 </td>
   <td style="text-align:left;"> $SPY What if I said to sell the dip? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:22:35 </td>
   <td style="text-align:left;"> $SPY I think when jp Morgan starts saying btd, time to start buying the rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:22:31 </td>
   <td style="text-align:left;"> $spy $QQQ  buy $XLE $CVX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:22:20 </td>
   <td style="text-align:left;"> $SPY 2% raise, market May run but not the real economy when we are all dead from starvation. Load up on brass! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:22:14 </td>
   <td style="text-align:left;"> $SPY mfs with stupid ass charts as if they mean anything when this market has been driven the whole month just by news. Like tell me where was your TA today? All heard was “break out” “double top” “double bottom” “cock and balls” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:21:51 </td>
   <td style="text-align:left;"> $SPY Anyone tried Dance Battling Putin yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:21:24 </td>
   <td style="text-align:left;"> $SPY Nikkei closed 2-day gap nicely </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:21:09 </td>
   <td style="text-align:left;"> $QQQ $DIA $SPY $IWM why the hell does anyone believe what Biden has to say? Futures went red from his announcement earlier…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:21:01 </td>
   <td style="text-align:left;"> $SPY Nah, I’m just a sack full of kittens </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:20:59 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:20:46 </td>
   <td style="text-align:left;"> $SPY 

Wow.  I think many had hope that Adams would be more sensible and better than Deblasio.  It&amp;#39;s sad to see now that he&amp;#39;s a moron.   NYC won&amp;#39;t recover.  Very unfortunate. 

&amp;quot;NYC Mayor Eric Adams says media covering him through different &amp;#39;prism&amp;#39; because he&amp;#39;s Black
Adams says his story is being interpreted by &amp;#39;people who don&amp;#39;t look like me&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:20:38 </td>
   <td style="text-align:left;"> $SPY anyone else a russian bot in here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:20:33 </td>
   <td style="text-align:left;"> $SPY no fed rates confirmed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:20:24 </td>
   <td style="text-align:left;"> $SPY $SPX Vixpiration about to rekt bears 
$VIX $VXX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:20:22 </td>
   <td style="text-align:left;"> $SPY tomorrow should be wild.. watch out for that whiplash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:20:20 </td>
   <td style="text-align:left;"> $SPY This is messed up, can someone investigate them? Same way as they doing with Zerohedge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:19:53 </td>
   <td style="text-align:left;"> $SPY market is fooked look at this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:19:45 </td>
   <td style="text-align:left;"> $SPY we rallying tomorrow right ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:19:34 </td>
   <td style="text-align:left;"> Fed $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:19:23 </td>
   <td style="text-align:left;"> $SPY 🙌🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:19:22 </td>
   <td style="text-align:left;"> $SPY This battle will not be fought in the present, but in the futures... Gonna DUMP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:19:11 </td>
   <td style="text-align:left;"> $SPY you guys should rethink life for a second.
Sick in the head to wish for war </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:19:02 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $SPY $DWAC $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:18:55 </td>
   <td style="text-align:left;"> $SPY can we get that see saw action like yesterday again that was fun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:18:52 </td>
   <td style="text-align:left;"> $SPY https://t.co/1dmelcFQam
❗Russian national anthem can now be heard on the Reuters livestream from Kyiv...

🔗 SOURCE YT [LIVE] 

Subscribe to @WW3INFO ⚡⚔⚡. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:18:37 </td>
   <td style="text-align:left;"> $SPY If this rallies tomorrow I’m gonna look at myself as the biggest pussy that ever walked the face of the earth 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:18:29 </td>
   <td style="text-align:left;"> $SPY The Fed is now expected to raise rates by 25 basis points in March </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:17:57 </td>
   <td style="text-align:left;"> $SPY got to love bulls calling out White house&amp;#39;s comments about invasion soon as bs but they are more than willing to believe Russia? Because it fits their narrative obviously </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:17:55 </td>
   <td style="text-align:left;"> $SPY that PPI today must’ve scared the Fed badly.  Those retards are finally encountering the consequences of their lies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:17:53 </td>
   <td style="text-align:left;"> $SPY 452 close tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:17:43 </td>
   <td style="text-align:left;"> $SPY 

Some say the Market is pricing in Six or seven hikes.   If that&amp;#39;s true that means massive relief rallies are coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:17:41 </td>
   <td style="text-align:left;"> $SPY looking for that invasion gap-down———— </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:17:39 </td>
   <td style="text-align:left;"> $SPY   When does the Russian invasion sell off begin? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:17:22 </td>
   <td style="text-align:left;"> $SPY dont worry.. they are just dropping off more test kits and masks..
Market tested 447 area on low volume today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:17:18 </td>
   <td style="text-align:left;"> $SPY fed meeting/ report tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:17:17 </td>
   <td style="text-align:left;"> $SPY Yo fr though… 

If things pop off tomorrow.. 

What’s our Clan Tag going to be? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:17:01 </td>
   <td style="text-align:left;"> $SPY 😂😂😂😂😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:16:55 </td>
   <td style="text-align:left;"> $SPY 😭😭😭😭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:16:53 </td>
   <td style="text-align:left;"> $SPY tomorrow is going to be very bearish… the last day like today was followed by righteous dumping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:16:51 </td>
   <td style="text-align:left;"> $SPY they’re gonna rug pull this thing so fracking hard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:16:40 </td>
   <td style="text-align:left;"> $SPY 😩😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:16:40 </td>
   <td style="text-align:left;"> $SPY I’m going to bed.
Someone wake up me up wt 4am when this is 2%+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:16:23 </td>
   <td style="text-align:left;"> $SPY WTF?🤷
https://www.google.com/amp/s/abcnews.go.com/amp/Politics/russian-troops-moved-firing-positions-ukraine-putin-ready/story%3fid=82909721 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:16:21 </td>
   <td style="text-align:left;"> $SPY what’s the fed releasing tomorrow again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:16:03 </td>
   <td style="text-align:left;"> $IWM $QQQ $SPY $SVXY $VXX  
Today was a gift. 
Proper hedging means you get to keep it. 💰💰💰🍯🤠 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:16:01 </td>
   <td style="text-align:left;"> $SPY back to 440 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:15:52 </td>
   <td style="text-align:left;"> $SPY ❗Russian national anthem can now be heard on the Reuters livestream from Kyiv...

🔗 SOURCE YT [LIVE] 

Subscribe to @WW3INFO ⚡⚔⚡
https://t.co/1dmelcFQam you won&amp;#39;t hear this in mainstream news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:15:51 </td>
   <td style="text-align:left;"> $SPY I remember all the times the police call the drug dealer to tell them they will be stopping by with guns in there face at 3am lol you bears are special kind of stupid </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:15:42 </td>
   <td style="text-align:left;"> $SPY sleep well my friends </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:15:34 </td>
   <td style="text-align:left;"> $SPY Confirmed bomber in Ukraine according to this guy below 👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:15:25 </td>
   <td style="text-align:left;"> $SPY $QQQ When that QE ends @bighaas @CactusPicksEm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:15:07 </td>
   <td style="text-align:left;"> $SPY looks sus to me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:15:05 </td>
   <td style="text-align:left;"> $SPY $440 tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:14:53 </td>
   <td style="text-align:left;"> $SPY if you’re a citizen of Ukraine, please stay away from Stocktwits. We just single clowns in our mid-20s with no social life </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:14:43 </td>
   <td style="text-align:left;"> $SPY black swan 🦆🔪🤝💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:14:19 </td>
   <td style="text-align:left;"> $SPY Thank you Trudeau for making us realize Bitcoin and any monetary system outside of Globalist baker scum hands is the future …with Trudeau freezing private citizens banks why isn’t Gold and a Bitcoin up 50% today ??? Answer??? American’s are morons 🇨🇦 🍁 🇨🇦 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:14:16 </td>
   <td style="text-align:left;"> $SPY we’ll they did say 3am invasion…
Where? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:14:03 </td>
   <td style="text-align:left;"> $SPY Guys it’s Wednesday in Ukraine now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:13:55 </td>
   <td style="text-align:left;"> $SPY ew futures not green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:13:44 </td>
   <td style="text-align:left;"> $SPY Is Biden talking again 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:13:37 </td>
   <td style="text-align:left;"> $SPY breaking.
https://t.co/1dmelcFQam
https://t.me/WW3INFO/13225
❗Russian national anthem can now be heard on the Reuters livestream from Kyiv...

🔗 SOURCE YT [LIVE] 

Subscribe to @WW3INFO ⚡⚔⚡ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:13:28 </td>
   <td style="text-align:left;"> $SPY Current time in Ukraine - 3:12AM, February 16... 🤣🤣🤣 bears will be clocking every hour for an invasion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:13:22 </td>
   <td style="text-align:left;"> $SPY we mooning right?
No war
FOMC can wipe my ass
Biden= Brandon 
Brandon= daddy
Daddy= Jpow
Jpow= printer goes brrr 3/10 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:13:16 </td>
   <td style="text-align:left;"> $SPY  over all interesting channel throughout the session with volume Stick near the close, Need those retail sales # for continuation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:13:01 </td>
   <td style="text-align:left;"> $SPY We need a concensus boys. Markets don&amp;#39;t tread water forever. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:12:43 </td>
   <td style="text-align:left;"> $SPY A lot of growth stocks that have been decimated are flattening out or starting the curl…setting up… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:12:36 </td>
   <td style="text-align:left;"> $SPY Just because something was mentioned it doesn’t mean it was in good light </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:12:35 </td>
   <td style="text-align:left;"> $SPY why we tanking ah?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:12:30 </td>
   <td style="text-align:left;"> $SPY So if Russia doesn’t invade tomirrow we close green? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:11:50 </td>
   <td style="text-align:left;"> $SPY was the 14th most mentioned on twitch over the last 7 days

Via topstonks.com/stocks/SPY?st_spy

#spy    #twitch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:11:23 </td>
   <td style="text-align:left;"> $SPY KHALD1 call sign near Ukraine border. flightradar24.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:11:13 </td>
   <td style="text-align:left;"> $SPY I’m a Russian bot. Also, in my spare time I like to shill for hedgies on the $AMC board. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:11:01 </td>
   <td style="text-align:left;"> $SPY bring back @ShortyMcFly and @George_Devore </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:10:45 </td>
   <td style="text-align:left;"> $SPY i want to hear your thoughts on the SPY closing over its 200d in a bearish environment 👁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:10:36 </td>
   <td style="text-align:left;"> $SPY  Wishing 2 things for you tonight, 

1) that you make money 

2) that you put yourself in the position to make more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:10:35 </td>
   <td style="text-align:left;"> $SPY bulls got dooped </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:10:30 </td>
   <td style="text-align:left;"> $SPY Get ready for the next 30 days lads. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:10:07 </td>
   <td style="text-align:left;"> $SPY watching the bullish and bearish sentiments on here is so funny to me. Like dude you better learn how to switch teams like it was a light switch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:10:05 </td>
   <td style="text-align:left;"> $SPY 😎🔪🦆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:10:02 </td>
   <td style="text-align:left;"> $SPY watch upst give it all back by opening 🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:09:56 </td>
   <td style="text-align:left;"> $SPY healthy economy with the swings. Love it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:09:56 </td>
   <td style="text-align:left;"> $SPY futes hanging on by a thread. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:09:48 </td>
   <td style="text-align:left;"> $SPY some action in 50 min, for now nothing to watch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:09:45 </td>
   <td style="text-align:left;"> $SPY  waiting for the move 
https://www.labelsoftwaredirect.com/2022/02/16/could-be-hitting-resistance/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:09:06 </td>
   <td style="text-align:left;"> $SPY 4 more hours … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:09:01 </td>
   <td style="text-align:left;"> $SPY cant we just air bomb the Ukrainian/Russian border with COVID and get them all sick and that will stop all this non sense once and for all?
Market rallied to 447 area before flagging out with itself all day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:08:50 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m waiting for Meet Kevin to say &amp;quot;that&amp;#39;s it I&amp;#39;m liquidating everything&amp;quot; and then it limit ups on him lmao. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:08:49 </td>
   <td style="text-align:left;"> $SPY dips at (WED 1:30PM, Feb 16) US Inflation Data, Retail Sales </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:08:42 </td>
   <td style="text-align:left;"> $SPY s&amp;amp;p batman head on 1 month. Massive. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:08:41 </td>
   <td style="text-align:left;"> $SPY Is that Putin riding a Ritz cracker… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:08:28 </td>
   <td style="text-align:left;"> $SPY Putin always leads from the front </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:08:23 </td>
   <td style="text-align:left;"> Stocks open higher $SPY, $QQQ, $DJIA  $WTI oil prices fall as Ukraine tensions ease https://www.billionaireclubcollc.com/stocks-open-higher-oil-prices-fall-as-ukraine-tensions-ease/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:08:11 </td>
   <td style="text-align:left;"> $SPY what else does bulls need in order for it to be a bear market. These are textbook reasons </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:07:38 </td>
   <td style="text-align:left;"> $SPY I had so much fun today shitting on dogshit traders who have no idea what they’re doing (bears)

They couldn’t even drop the market AT ALL. 
V rally opex tomorrow doesn’t get much better baby, any dip immediate bid watch this time bears maybe you’ll learn 🤷🏻‍♀️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:07:31 </td>
   <td style="text-align:left;"> $SPY inflation/invasion/…..
Let’s check the next 🐻 thesis.. must end in an “ion” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:07:30 </td>
   <td style="text-align:left;"> $SPY shit…4 military choppers just passed by house…hehehe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:07:29 </td>
   <td style="text-align:left;"> $SPY breaking: when asked if he&amp;#39;ll attack on February 16? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:07:23 </td>
   <td style="text-align:left;"> $SPY my puts are dead, yikes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:07:20 </td>
   <td style="text-align:left;"> $SPY cyberattacks at banks and gov offices today. First I heard of that today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:07:11 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX -

I repair, then, fellow-citizens, to the post you have assigned me. With experience enough in subordinate offices to have seen the difficulties of this the greatest of all, I have learnt to expect that it will rarely fall to the lot of imperfect man to retire from this station with the reputation and the favor which bring him into it. Without pretensions to that high confidence you reposed in our first and greatest revolutionary character, whose preeminent services had entitled him to the first place in his country&amp;#39;s love and destined for him the fairest page in the volume of faithful history. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:07:02 </td>
   <td style="text-align:left;"> $SPY did Russia plan on invading 16th est time? Or European time? If so we’re they going to do it breakfast, lunch or dinner? 
Bears seem to know all of this info </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:06:57 </td>
   <td style="text-align:left;"> $SPY this war shit is insane </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:06:44 </td>
   <td style="text-align:left;"> $SPY why is a russian ministry for emergency situations plane flying to an undisclosed location near the ukrainian border from moscow right now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:06:42 </td>
   <td style="text-align:left;"> $SPY I’m Bullish on gifs of puppies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:06:26 </td>
   <td style="text-align:left;"> $SPY Some of you hold a lot of anger. So here… my gift to you. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:06:13 </td>
   <td style="text-align:left;"> $SPY should I show S**** my gains from today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:05:58 </td>
   <td style="text-align:left;"> $SPY limit down futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:05:32 </td>
   <td style="text-align:left;"> $SPY did I tell you the night at the club when a hedge fund manager offered me a job? My life is like Roadhouse, Cocktail, and Wall street mixed together. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:05:31 </td>
   <td style="text-align:left;"> $SPY if we went to a real war, do you think these cucked liberal losers would bitch about the diversity of the fighting force? Not enough transgender infantry-they attacking the enemy? Not enough black females driving tanks? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:05:19 </td>
   <td style="text-align:left;"> $SPY how stupid do you have to be to hope for nuclear war so your puts make money. That’s like wishing for cancer so you can get morphine. Dumb ass bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:05:18 </td>
   <td style="text-align:left;"> $SPY here is everyone important within our government- does this wanting war shit make sense yet ? 🤷‍♂️🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:05:14 </td>
   <td style="text-align:left;"> $SPY I’m going to call Putin to see what the plan for tonight is.
We were support get chipotle after invasion but I guess that plan is off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:04:45 </td>
   <td style="text-align:left;"> $SPY Putin has a plan ..he’ll mail it to mainstream media </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:04:31 </td>
   <td style="text-align:left;"> $SPY Fake red futures.. But im very stupid. Dont Listen to me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:04:28 </td>
   <td style="text-align:left;"> $SPY No more Covid talk thanks to Russia&amp;#39;s invasion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:04:24 </td>
   <td style="text-align:left;"> $SPY it’s like everyone’s forgetting we have the highest inflation in 40 years and upcoming interest rate hikes . Putin has invaded invaded Ukraine in 2014 to take over the Crimean peninsula  .We are being distracted folks .  This is a day traders dream .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:04:07 </td>
   <td style="text-align:left;"> $SPY a wise man once told me, you want forgiveness, get religion </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:04:06 </td>
   <td style="text-align:left;"> $SPY See… it’s be really scary if AUSTRALIA was invading Ukraine. All they’d have to do is bag up all their creepy creatures and drop them in. Whole country burned down overnight. 

Ez win. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:04:02 </td>
   <td style="text-align:left;"> $SPY Putin playing games that Biden couldn’t possibly understand…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:03:58 </td>
   <td style="text-align:left;"> $SPY I went to the gym and they told me to put on a mask when on the tile floor. I said I can’t I have a medical condition. They asked, what is it? I said, I’m allergic to bullshit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:03:55 </td>
   <td style="text-align:left;"> $SPY BREAKING NEWS: RUSSIA SAYS THEY’RE NOT INTERESTED ON MAKING A NEW COD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:03:41 </td>
   <td style="text-align:left;"> $SPY No lie the funny stuff is funny but i&amp;#39;m here to make money lol hard sifting thru the nonsense so i just join em usually. But all in all you can learn stuff here if you listen 🎧 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:03:40 </td>
   <td style="text-align:left;"> $SPY  I don&amp;#39;t think Russia is invading tonight because Putin hasn&amp;#39;t posted his plan to Stocktwits yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:03:36 </td>
   <td style="text-align:left;"> $SPY Who is our secretary of defense again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:03:32 </td>
   <td style="text-align:left;"> $SPY 🐻 seem to be too focussed on media events… fundamentals of the economy are strong… don’t chase headlines </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:03:09 </td>
   <td style="text-align:left;"> $SPY I predicted Brexit using demographics and polls. I read charts better than if  Cramer and Carter worth and Tim Seymour had a baby. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:03:04 </td>
   <td style="text-align:left;"> $SPY bout to air fry these carrots. Any tips? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:02:56 </td>
   <td style="text-align:left;"> $SPY 341 on 3/22 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:02:56 </td>
   <td style="text-align:left;"> $SPY MMs need volume &amp;amp; they’re not getting it on the rips </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:02:41 </td>
   <td style="text-align:left;"> $SPY bears buy PUTS. Bulls use that premium to buy stocks and pushes prices higher. Rinse and repeat. It’s a self fulfilling prophesy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:02:38 </td>
   <td style="text-align:left;"> $SPY was is canceled right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:02:36 </td>
   <td style="text-align:left;"> $SPY Uf it goes in a bull run. Which i personally think is not that likely right now then it would honestly be a good time to open a long short position. I mean Feds are hiking rates in March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:02:13 </td>
   <td style="text-align:left;"> $SPY how many of you sold your shares or bought puts hoping for an invasion? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:02:01 </td>
   <td style="text-align:left;"> $SPY $QQQ be very careful for next 4 weeks..!!

GL! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:01:59 </td>
   <td style="text-align:left;"> $SPY you held puts through the pump? My god you must be hung like a goddamn sea lion </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:01:46 </td>
   <td style="text-align:left;"> $SPY troops are irrelevant, we  are attacking from the sea lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:01:36 </td>
   <td style="text-align:left;"> $SPY how did they go from russia invades within 24-48 hours to russia is now receding?   must the the false flag they were talking about... giving everyone a sense of security and then they strike.  horrible. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:01:32 </td>
   <td style="text-align:left;"> $SPY bears are still in control. Simple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:01:28 </td>
   <td style="text-align:left;"> $SPY Cramer says inflation has peaked. You know what that means... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:01:25 </td>
   <td style="text-align:left;"> $dis $dia $spy https://www.youtube.com/watch?v=-O2hez8JZIQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:01:20 </td>
   <td style="text-align:left;"> $AMD $spy  $btc.x   $aapl  $TSLA  
Impact of Fed rate changes on the S&amp;amp;P 500 
----------------------------------------- 
Impact of Fed interest rate changes on S&amp;amp;P 500 since 2017 
The chart below tracks the S&amp;amp;P 500, along with the dates that Fed rate cuts and hikes were announced over a three-year period. It’s apparent to see that trends are not always clear cut: following a quarter point rate hike in December 2017, the S&amp;amp;P 500 went on to defy expectations and climb almost 6% in January 2018. 
 
The chart also shows there can be significant shifts in stock prices around the time of Federal Open Market Committee announcements. Ahead of the rate cut in October 2019, there was a period of significant volatility; after it was announced, the S&amp;amp;P 500 closed at a record high. It’s important to monitor news, be aware of economic events that could affect stock prices and build these into the trading plan. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:01:16 </td>
   <td style="text-align:left;"> $SPY  🐻 waiting for an invasion … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:01:09 </td>
   <td style="text-align:left;"> $spy $qqq $dxy https://www.youtube.com/watch?v=ST8c5iqmFcQ&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:01:02 </td>
   <td style="text-align:left;"> $SPY starting to slow things down a bit - bought 500 shares of SBUX PT 100 but I swear this stock can’t catch a break 🤦‍♂️ position is green but FACK mm is a degenerate himself </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:00:22 </td>
   <td style="text-align:left;"> $spy $qqq $fb https://www.youtube.com/watch?v=WeaUKa9lDTc&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 08:00:01 </td>
   <td style="text-align:left;"> $SPY theoretically if Russia was to invade. How low do we drop? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 07:59:55 </td>
   <td style="text-align:left;"> $SPY All that stim money from the little $$$ bulls are going to the bears by the end of the week   =) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 07:59:54 </td>
   <td style="text-align:left;"> $SPY https://dailyexpose.uk/2022/02/13/the-covid-19-vaccines-cause-aids/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 07:59:44 </td>
   <td style="text-align:left;"> $SPY Gonna run smack into that downtrend 🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-16 07:59:43 </td>
   <td style="text-align:left;"> $SPY Futes dipping but not tripping because that Feb 16 invasion FUD is still bugging. 💥🔥🔥🔥 Bulls can comfortably sleep and wake up to bright green. Them bears will be up all night waiting for smoke. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:50:55 </td>
   <td style="text-align:left;"> $QQQ Time to inverse Cramer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:49:34 </td>
   <td style="text-align:left;"> $SPY $QQQ 

No lie, and not trying to gaslight, but if ever there were a spot for a limit down day it’s tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:42:01 </td>
   <td style="text-align:left;"> $QQQ https://www.reuters.com/world/us/fed-raise-rates-25-bps-march-calls-50-bps-grow-louder-2022-02-16/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:41:46 </td>
   <td style="text-align:left;"> $QQQ Here&amp;#39;s a 4 HR Candle Trend Channel Chart for NAS 100 the channels going back to Nov.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:41:42 </td>
   <td style="text-align:left;"> Excellent, welcome to Crash Wednesday, this post is approved by my good friends at Seeking Alpha moderating my posts for my profits, hopefully for you too. Carry on sticking forks in the stock markets at large overpriced sincenthe beginning of the recession in 2009, quite realistically 1999 imho re due diligence. Good health and trading to all. https://www.investing.com/indices/indices-futures  Thank dog that I am here to help 🐻❤😈✔👍😁 @Profit_Maker https://stocktwits.com/Profit_Maker 🤑 $djia $SPX $NDX $spy $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:41:20 </td>
   <td style="text-align:left;"> $SPY $QQQ futes basically crashing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:40:36 </td>
   <td style="text-align:left;"> $QQQ $XBI $FB Longs, if you were hurt by the mass media&amp;#39;s latest fear campaigns - War, Runaway Inflation &amp;amp; Omnicron CV Variant, you might appreciate a sure winner or two. I&amp;#39;m a researcher &amp;amp; investor and my picks are: BBIG (TYDE SPINOFF DIVIDEND SHARES SOON &amp;amp; 2 MB$ INCOME STREAMS!!!), XBI, SENS, NLY, FRLN, GEVO &amp;amp; BB. Attached is a sample of my research and there is much more info on my prior posts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:39:53 </td>
   <td style="text-align:left;"> $NVDA $QQQ not seeing many posting their progress these day. wonder why? Looking to hold a small size of NVDA through earnings fully reading to buy a drop or deal with having to add higher. This month so far been tricky </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:39:50 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $TQQQ $SOXL 

When experts talk, you shut up and listen. 🤫 

👇🏿👇🏿👇🏿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:37:40 </td>
   <td style="text-align:left;"> $QQQ don’t be too hard on yourself if you are struggling recently 

Nobody knows anything 

Learn to make money without knowing daily or weekly directionally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:37:36 </td>
   <td style="text-align:left;"> $QQQ probably bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:35:53 </td>
   <td style="text-align:left;"> $QQQ $SPY 
The biggest mistake 99.9% of people make is having STRONG views on market directionality.  Strong convictions lead to excessive size and that’s what causes losses because everybody is wrong majority of the time 
But it’s ok to be generally long most of the time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:30:26 </td>
   <td style="text-align:left;"> $QQQ Let’s there be WAR or let’s there be MARKET crash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:29:56 </td>
   <td style="text-align:left;"> Trade Recap: The Higher High Higher Low Setup $SPY $QQQ $DJIA https://www.billionaireclubcollc.com/trade-recap-the-higher-high-higher-low-setup </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:29:11 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX 
Are we no longer capable of pulling from darkness a future worthy of our efforts? Must we forever be lost in a sea of aimless misery? We should seek to go beyond our current plights. How much would men lying beneath the ground give just to feel the warmth of the sun one more time? We have no excuse not to continue on with our heads held high. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:28:18 </td>
   <td style="text-align:left;"> $QQQ need the qqq at 275 so my puts put my port back in the green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:28:02 </td>
   <td style="text-align:left;"> $QQQ Tomorrow should be another doozy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:24:03 </td>
   <td style="text-align:left;"> $SPY $QQQ buy $lmt $rtx .. see satellite images </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:23:04 </td>
   <td style="text-align:left;"> $SPY $QQQ Know what is ironic compared to Volcker era....politicians were crying to ease the hawkishness. Now it seems the yelling is for more hawkishness and fed just may not do that. They either lowered their inflation expectations Monday because they are hiking hard or they really convinced inflation has peaked 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:22:31 </td>
   <td style="text-align:left;"> $spy $QQQ  buy $XLE $CVX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:21:09 </td>
   <td style="text-align:left;"> $QQQ $DIA $SPY $IWM why the hell does anyone believe what Biden has to say? Futures went red from his announcement earlier…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:17:04 </td>
   <td style="text-align:left;"> $QQQ I feel some pain coming…..😛 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:16:03 </td>
   <td style="text-align:left;"> $IWM $QQQ $SPY $SVXY $VXX  
Today was a gift. 
Proper hedging means you get to keep it. 💰💰💰🍯🤠 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:15:25 </td>
   <td style="text-align:left;"> $SPY $QQQ When that QE ends @bighaas @CactusPicksEm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:13:38 </td>
   <td style="text-align:left;"> $QQQ Where is the big red flush candle will it come while we are sleeping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:10:17 </td>
   <td style="text-align:left;"> $QQQ Invesco QQQ Trust Series 1 Option Alert: Feb 28 $314 Calls at the Bid: 12 vs 0 OI🐂 |🥇 Learn more and get details on  ➡️ SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:10:03 </td>
   <td style="text-align:left;"> $QQQ Well the futures are red. We all know what that means. Haha crazy market logic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:08:23 </td>
   <td style="text-align:left;"> Stocks open higher $SPY, $QQQ, $DJIA  $WTI oil prices fall as Ukraine tensions ease https://www.billionaireclubcollc.com/stocks-open-higher-oil-prices-fall-as-ukraine-tensions-ease/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:07:11 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX -

I repair, then, fellow-citizens, to the post you have assigned me. With experience enough in subordinate offices to have seen the difficulties of this the greatest of all, I have learnt to expect that it will rarely fall to the lot of imperfect man to retire from this station with the reputation and the favor which bring him into it. Without pretensions to that high confidence you reposed in our first and greatest revolutionary character, whose preeminent services had entitled him to the first place in his country&amp;#39;s love and destined for him the fairest page in the volume of faithful history. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:02:54 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-02-15 Trade Analysis Video: 
https://www.youtube.com/watch?v=ci0oWmFDRz8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:02:26 </td>
   <td style="text-align:left;"> $QQQ Did anyone get in last night ? 
 
Let&amp;#39;s see how this plays out... 
Op-ex on friday [day 4] </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:02:01 </td>
   <td style="text-align:left;"> $SPY $QQQ be very careful for next 4 weeks..!!

GL! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:01:09 </td>
   <td style="text-align:left;"> $spy $qqq $dxy https://www.youtube.com/watch?v=ST8c5iqmFcQ&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 08:00:22 </td>
   <td style="text-align:left;"> $spy $qqq $fb https://www.youtube.com/watch?v=WeaUKa9lDTc&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:58:52 </td>
   <td style="text-align:left;"> $SPY $QQQ “fake Russian invasion” uptrend reversal, back to PPI and reversal back to downtrend (full circles) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:54:17 </td>
   <td style="text-align:left;"> $QQQ is ukraine the one next to home depot or costco </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:54:11 </td>
   <td style="text-align:left;"> $QQQ look at the charts, everyone thinks were out of the woods and now going to all time highs, the volume today was despicable. everyone thinks its a bed of roses and sunshine and roses. fed is still accommodating which is so dumb. suppose to raise rates but they’re afraid to crash the market and hurt the 1% but dont give a shit about the middle and low class. i forgot everything is priced in forever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:53:44 </td>
   <td style="text-align:left;"> $QQQ why didn’t I go all in puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:52:58 </td>
   <td style="text-align:left;"> $SPY $QQQ this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:51:22 </td>
   <td style="text-align:left;"> $SPY $QQQ https://www.youtube.com/watch?v=pzvbUpKU4eE&amp;amp;ab_channel=TheInfographicsShow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:49:51 </td>
   <td style="text-align:left;"> $QQQ always higher by 8pm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:43:48 </td>
   <td style="text-align:left;"> latex3f71a5027c9fa9a85806de880e6b424a$es down NO WAR except in dems heads get it!!! $QQQ and $IWM tomorrow the main thing to look for is FEDs mins @ 2pm EST </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:42:16 </td>
   <td style="text-align:left;"> $QQQ $SPY $RBLX $TSLA $UPST can’t tell if this market is about to go dumb dumb or if it’s done done. What do you queef kings think? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:41:56 </td>
   <td style="text-align:left;"> $QQQ omg futes going down 😢 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:36:27 </td>
   <td style="text-align:left;"> $QQQ I REGRET TO INFORM YOU ALL THAT TOMORROW AND THE REST OF THE WEEK WILL BE QUITE RED WITH OR WITHOUT A RUSSIAN INVASION. I DOUBLED
DOWN ON PUTS AT
CLOSE
TODAY AND IF
IM WRONG ILL
TAKE THAT L BUT I DONT THINK I AM. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:36:13 </td>
   <td style="text-align:left;"> $QQQ what your seeing on the media is a lie, myself and 10,000 other troops are still on standby in regards to Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:34:46 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $IWM popped at the open + stayed up all day + closed at the high = bullish (I&amp;#39;m still long) 
Let&amp;#39;s see if we can carry this momentum into tomorrow...so far this year, we had 1 step forward &amp;amp; 2 steps back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:33:31 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA Interesting that the &amp;quot;cry wolf&amp;quot; strategy by the US administration actually worked... Forcing Germany to meet with Russia... The Putin team probably had never thought about that childish strategy would be thrown at them... lol... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:33:14 </td>
   <td style="text-align:left;"> $QQQ - All those Russian troops and the multitude of equipment that is very visible from satellite sure does make for a really rich target environment 😁

Wake up Joey, Trump would have ready been launching </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:31:36 </td>
   <td style="text-align:left;"> $SPY $QQQ Roblox is a Metaverse play and it dropped like a rock after earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:29:27 </td>
   <td style="text-align:left;"> $QQQ Puts creaming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:27:49 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $BTC.X  … ⚠️ just a reminder

Stick to your own gut feelings 🔹 instead of some subway rider with high follower count </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:26:23 </td>
   <td style="text-align:left;"> $QQQ earnings are pretty much over for most major comps. De-escalation of Russia is priced in now. What&amp;#39;s staring the markets right in the face is inflation now. There is no way around it.. after the euphoria goes away and reality kicks in we will revisit January lows soon and dip lower next month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:25:12 </td>
   <td style="text-align:left;"> $SPY Fundamentally nothing has changed. This is a fragile market where you see a relief rally once in a blue moon. Be careful $IWM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:25:05 </td>
   <td style="text-align:left;"> $QQQ get ready for yet another rug pull!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:24:05 </td>
   <td style="text-align:left;"> $QQQ They finally catching on. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:20:23 </td>
   <td style="text-align:left;"> $QQQ https://www.nbcnews.com/politics/white-house/biden-make-remarks-growing-threat-russian-invasion-ukraine-rcna16335 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:17:42 </td>
   <td style="text-align:left;"> $QQQ my puts got railed today but luckily they don’t expire
For
3 more weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:15:25 </td>
   <td style="text-align:left;"> $UPST 💥BOOM💥Did anyone catch this over at my Discord 🔥🔥🔥  
  
Follow me for more alerts, or join our growing group!  
  
Don&amp;#39;t miss out. 👈🏻 💎  $SPY $ABNB $QQQ $RBLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:15:16 </td>
   <td style="text-align:left;"> $QQQ anyone else think QQQ is gonna hit 339 this week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:14:04 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
https://www.youtube.com/watch?v=YmaRStA8Qlc&amp;amp;t=116s 
 
That&amp;#39;s how a US President should speak like, if it were Trump he would just say what a great guy and great friend Putin is lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:12:08 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL why you always lyin, you always lying, media always lyin! russians never lyin! lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:11:52 </td>
   <td style="text-align:left;"> $QQQ US President Biden Delivers Speech 2022 Legislative Conference in Regards to Recent Bipartisan Efforts 
 
https://youtu.be/qspN719QQ5c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:11:16 </td>
   <td style="text-align:left;"> $QQQ FULL VID: US President Biden Speech in Regards To Russia Invasion into Ukraine &amp;amp; The Diplomacy with NATO 
 
 
https://youtu.be/DB6U6BCLh7E </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:09:36 </td>
   <td style="text-align:left;"> Although the technical rating is bad, $QQQ does present a nice setup opportunity. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:07:50 </td>
   <td style="text-align:left;"> $HOOK Loaded some for tomorrow.  Watching to load more. Still seems cheap, 50dma alone is at $2.15 and this has HUGE news.  Checkout HOOK 👍 👌  🕺 🍻 Also watching $SPY $QQQ $UPST $NDAQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:07:12 </td>
   <td style="text-align:left;"> $QQQ we will bottom again in late march..for now the coast is clear for a little rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:05:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL 

Listen, all I’m saying is that Elon wasn’t donating billions of dollars of stock when Tesla (and the market in general) was fairly valued 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:04:12 </td>
   <td style="text-align:left;"> $SPY $QQQ love the fact everyone is so focus kn the Russia news and not what&amp;#39;s happening in the bond market and rates </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:03:06 </td>
   <td style="text-align:left;"> $SPY $QQQ Is it just me? I had trouble loading the Stocktwits page for the last hour or two. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:02:44 </td>
   <td style="text-align:left;"> $QQQ even if it was a bs low volume melt up you know we’ve seen this too many times while in a downtrend therefore why not take advantage. Nothing has changed rates are not priced in they can’t be yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:02:39 </td>
   <td style="text-align:left;"> $QQQ Go america go!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:01:49 </td>
   <td style="text-align:left;"> $QQQ technical analysis for tomorrow. 
 
https://youtu.be/tGKwIL9dcMM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 07:00:08 </td>
   <td style="text-align:left;"> $UPST $TTD $QQQ $FB $AAPL  my portfolio is god damn awesome. F y’all shorts. 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:59:52 </td>
   <td style="text-align:left;"> $QQQ next focus is rate and PE…. Others are irrelevant….  With 10 year rate exceeding 2%… it’s the time to think about its impact on PE…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:58:23 </td>
   <td style="text-align:left;"> All the trades from the past 2 days. Not to mention my top tier “Insider alerts” whole team has been banking. 
$QQQ $AAPL $NIO $SPCE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:56:41 </td>
   <td style="text-align:left;"> $SPY you heard the man, it’s time

$QQQ $DIA $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:53:17 </td>
   <td style="text-align:left;"> $QQQ $TLT 20 week correlation back up to .75 zone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:46:37 </td>
   <td style="text-align:left;"> $TSM  US plant in construction  and Expansion of Japan plant ... Production 🛫🚀
ER $26/ share ... for $125 /Share  very Underpriced compared to  $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:45:31 </td>
   <td style="text-align:left;"> $TSLA $QQQ 36.2 Million dollars over 1K tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:44:54 </td>
   <td style="text-align:left;"> $QQQ analysis based on today&amp;#39;s closing price 

https://youtu.be/6SpdC-IrIt4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:43:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $XBI Please disregard my previous post.  
So scenario 1 from Monday continues to play. Two possibilities that I see having good chances of happening. In My Opinion of course. I am split 50%  
1- We go to $SPX 4590-4520 we stall, we reverse ot even end the day at the highs without breaking 4527. In this case we will go down to 4240-4290 before turning back in a strong rally to go to 4780. 
2- We go to $SPX 4520 and break 4527. In this case yesterday&amp;#39;s low should hold until we reach 4780. If it turns lower than Monday low then January lows are likely to break.  
When/If we get to 4500 we will see how it acts and act accordingly.  
$XBI can go as low as 89 without breaking the daily trend; It has some leeway. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:41:02 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX - </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:40:16 </td>
   <td style="text-align:left;"> $QQQ  according to rsotc.com next resistance on $QQQ is $359.36 support at $353.95 breakout above support= going to hit resistance $DIA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:40:11 </td>
   <td style="text-align:left;"> $QQQ today might have been objectively the stupidest time ever to be a buyer.

time will tell whether it was just a stupid time to buy, or full on peak downs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:39:12 </td>
   <td style="text-align:left;"> $UVXY $FB $QQQ  
 
Account Challenge Update:-  
Start Date: Jan 3, 2022  
Starting Balance: $1,700  
Current Balance: $84,969 
Goal: $100,000 by end of February.  
Strategy: Swing Trade Options, Stocks  
  
Watch out for next play👓 top.stocksboss.xyz/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:35:51 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 2/15/2022 $SPY $XLF $QQQ $NIO $FB https://www.chartguys.com/daily-market-videos/4137/even-more-shenanigans </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:35:05 </td>
   <td style="text-align:left;"> $QQQ has anyone made money trading using the news? Because they always seem to be wrong lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:33:53 </td>
   <td style="text-align:left;"> Pentagon: Contractor mergers hurt national security, economy

https://www.google.com/amp/s/abcnews.go.com/amp/Politics/wireStory/pentagon-contractor-mergers-hurt-national-security-economy-82897370

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:33:03 </td>
   <td style="text-align:left;"> Biden warns of risk to U.S. economy from fallout if Russia invades Ukraine

https://www.google.com/amp/s/www.nbcnews.com/news/amp/rcna16335

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:32:47 </td>
   <td style="text-align:left;"> $QQQ Pootin cyberattack on ST </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:32:44 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMD $QQQ  🐂🐂🐂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:30:31 </td>
   <td style="text-align:left;"> $QQQ There are some bears here posting every 30 seconds, same as some bulls. Lots of desperation in both directions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:27:03 </td>
   <td style="text-align:left;"> $SPY $Qqq When is fed meeting this week?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:26:23 </td>
   <td style="text-align:left;"> $QQQ incase you missed his bearish rant https://youtu.be/k5bglkFSzq4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:23:51 </td>
   <td style="text-align:left;"> $QQQ Soxl nas100 tna what a day. 🤑🥳 
 
Now rugpull me after u turned me into a bull </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:20:58 </td>
   <td style="text-align:left;"> $QQQ yall ready for 300 dollar a barrel oil, more QE and negative fed funds rates? 
 
feds new tgt inflation is 15% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:19:11 </td>
   <td style="text-align:left;"> $SPY $QQQ https://apnews.com/article/russia-ukraine-technology-business-europe-russia-e791990f60841b599f664c34f58403de </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:19:04 </td>
   <td style="text-align:left;"> $QQQ Since $QQQ has been determined to be complete shit on Friday, I would like to post this corresponding chart to hopefully be disproven by the bulls if they have enough balls to keep buying for at least another week..  GLTA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:18:48 </td>
   <td style="text-align:left;"> $SPY $QQQ Fucking futures last two nights had more action than today. 

Flat bitch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:18:06 </td>
   <td style="text-align:left;"> $QQQ I hope that&amp;#39;s a glitch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:16:45 </td>
   <td style="text-align:left;"> Do you realize that there&amp;#39;s still $5.5T in Money Market?

$SPY $QQQ $XOP $SPG $SVIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:16:39 </td>
   <td style="text-align:left;"> $QQQ $SPY tomorrow green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:14:59 </td>
   <td style="text-align:left;"> $QQQ call me crazy..... But I&amp;#39;m shorting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:14:05 </td>
   <td style="text-align:left;"> $QQQ you gotta repect the plunge protection team they had their algos stepping in front of those bids all day even after PPI data &amp;amp; Binden Speach that really sounded like he was calling Putin out again on national t.v. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:13:44 </td>
   <td style="text-align:left;"> $QQQ cnn is playing reruns of the 2014 game between Russia vs Ukraine.  they used that trick in Ocean&amp;#39;s Eleven at the end of the movie. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:13:00 </td>
   <td style="text-align:left;"> $QQQ $RBLX will be the death of the Qs starting at 9:30am tomorrow. 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:12:34 </td>
   <td style="text-align:left;"> $BRK.B $AAPL $QQQ $SPX $SPY MarketWatch - Apple is Berkshire’s largest stock holding, but Buffett and Co. own a bigger share of these companies
 https://on.mktw.net/3JsWetd </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:11:40 </td>
   <td style="text-align:left;"> $SPY $QQQ the market hasn’t priced me in yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:11:19 </td>
   <td style="text-align:left;"> $SPY $QQQ propaganda machine trying to get you to sell all through 2021. Now they&amp;#39;re trying to get you to buy in 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:10:57 </td>
   <td style="text-align:left;"> $QQQ JP&amp;#39;s hiking trip still incoming....I wouldn&amp;#39;t celebrate yet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:10:30 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA FUTES RIPPIN BEAT RAISE SHARE BUYBACK AIRCRAFT CARRIER!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:08:21 </td>
   <td style="text-align:left;"> $QQQ PARIS est magique ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:07:10 </td>
   <td style="text-align:left;"> $QQQ what a day. Needed. Strong earnings reports to boot across multiple names. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:07:05 </td>
   <td style="text-align:left;"> $TSLA $ES $QQQ  
 
 
Account Challenge Update:-     
Start Date: Jan 3, 2022     
Starting Balance: $1,700     
Current Balance: $84,969    
Goal: $100,000 by end of February.     
Strategy: Swing Trade Options, Stocks     
     
Watch out for next play👓 top.stocksboss.xyz/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:07:00 </td>
   <td style="text-align:left;"> NEW POST: Stock Market Recap 02/15/22 {Video} https://marketchess.com/2022/02/15/stock-market-recap-02-15-22-video  $IWM $QQQ $SPY $UPST $USO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:06:52 </td>
   <td style="text-align:left;"> $QQQ nice try :/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:05:37 </td>
   <td style="text-align:left;"> $SPY $QQQ glitch? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:04:35 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY  
 
Get your popcorn ready! 
 
https://www.youtube.com/watch?v=3_JRSioZZyQ&amp;amp;ab_channel=Reuters </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:04:17 </td>
   <td style="text-align:left;"> $SPY $QQQ It looks like we have bottomed for sure, it was a great sign that the market ignored the hotter than expected PPI this morning, it means the market has pretty much priced in higher inflation and the rate hikes. As long as we continue to see strong economic data and strong earnings, the market should continue to head higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:04:09 </td>
   <td style="text-align:left;"> $spy $qqq $RBLX $ABNB $UVXY  
 
SAY GOOD BYE TO YOUR CALLS, INVASION STARTS NOW 
 
https://twitter.com/theinsiderpaper/status/1493706335380197387?s=10 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:03:53 </td>
   <td style="text-align:left;"> $QQQ 

https://app.prizepicks.com/sign-up?invite_code=PR-LOX27BH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:03:25 </td>
   <td style="text-align:left;"> $SPY $QQQ WHAT JUST HAPPENED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:02:31 </td>
   <td style="text-align:left;"> $SPY $QQQ People on this board are just something else 😩

How dumb can you be? @Lewi5 

You realize there are different time zones right?

You realize not everyone is just from the US right?

Fucking idiot you trade the market yet you’re uneducated.

Idiots I swear.

1:00am here now the 16th and the picture I posted was at 12:45am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 06:01:47 </td>
   <td style="text-align:left;"> $SQQQ , $QQQ   Tomorrow, the media will start to confirm that there is no evidence of any troop movements away from the front lines...  https://www.youtube.com/watch?v=hrsRF73SW2Y </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:56:34 </td>
   <td style="text-align:left;"> $RBLX Nancy “Small price to pay for freedom” $SPY $QQQ 😅😅😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:56:12 </td>
   <td style="text-align:left;"> $UVXY Not a bad idea 💡 
 
$SPY $QQQ $VXX $SPCE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:52:50 </td>
   <td style="text-align:left;"> $QQQ Escalating escalating </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:51:04 </td>
   <td style="text-align:left;"> $SPY $QQQ U.S. IS CURRENTLY SEEING RUSSIAN FORCES LEAVING ASSEMBLY AREAS AND HEADING TOWARDS THE UKRAINIAN BORDER : U.S. OFFICIAL -CBS NEWS * </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:50:56 </td>
   <td style="text-align:left;"> 5-Day ETF Sentiment Recap: $QQQ is the #2 ETF that institutions are trading over rolling 5 day window with 870.4K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:49:41 </td>
   <td style="text-align:left;"> $SPY $QQQ Interested to see how it plays out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:49:27 </td>
   <td style="text-align:left;"> $QQQ I’ve seen the most bullish of the bulls turn to bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:48:34 </td>
   <td style="text-align:left;"> $QQQ im seeing batman in the futures. Just sayin. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:47:57 </td>
   <td style="text-align:left;"> $QQQ putin drama is over, back to reality </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:47:20 </td>
   <td style="text-align:left;"> $SPY $QQQ 🧐🤨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:42:10 </td>
   <td style="text-align:left;"> $QQQ If you think this drama is over then I think you might be mistaken </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:38:43 </td>
   <td style="text-align:left;"> $QQQ beautiful move up - the war FUD is now eased. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:38:20 </td>
   <td style="text-align:left;"> $TSLA $QQQ $SPY Where do you trade and why?  What features keep you at your broker?  Is there anything you would want changed?  I am trying to figure out where I should move my money for trading purposes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:36:54 </td>
   <td style="text-align:left;"> $ETH.X $BTC.X $SPY $QQQ $AVAX.X When the New York Stock Exchange - the most venerable equities institution in the world - decides to get into Digital Assets, you simply can no longer call Blockchain a fad or deny its value. 
 
  https://www.bnnbloomberg.ca/nyse-wants-to-be-the-marketplace-for-nfts-just-like-with-stocks-1.1723937 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:36:22 </td>
   <td style="text-align:left;"> $QQQ $NQ_F Nasdaq futures hourly chart - let’s see how this plays out

$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:35:44 </td>
   <td style="text-align:left;"> $QQQ Biden exposed Putin to the class, small attack will confirm it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:34:53 </td>
   <td style="text-align:left;"> $QQQ TANK FASTER THAN MY PANTS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:34:36 </td>
   <td style="text-align:left;"> $QQQ Biden the bishhh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:34:01 </td>
   <td style="text-align:left;"> $QQQ well shit my outs are fucked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:31:48 </td>
   <td style="text-align:left;"> $IWM $QQQ $SPY $SPX ,, More Bearish then Bullish , Sneaky Snake Trading Strategy,, good watch recorded Sunday  GOOD WATCH if you want to learn  https://www.youtube.com/watch?v=Nmcv0LJXlgI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:30:01 </td>
   <td style="text-align:left;"> $QQQ Some dirty bears are gripping the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:28:57 </td>
   <td style="text-align:left;"> $SPY $VIX $DJIA $QQQ  so one day ppl will get so comfortable on buying the dip that they rug pull everyone and their mother....remember 2008...prob not...looks familiar, right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:28:36 </td>
   <td style="text-align:left;"> $QQQ ath tomorrow?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:28:26 </td>
   <td style="text-align:left;"> $QQQ fed minutes released after lunch? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:27:24 </td>
   <td style="text-align:left;"> $QQQ Impact of rates on tech. $TLT latex5f88036623f7d2f7faddee414151c1bfQQQ 14.82% from ATH 📈
$DJIA 5.73% from ATH 📈

***Upcoming FOMC minutes in 21 hours. Don’t get caught with yo pants down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:25:30 </td>
   <td style="text-align:left;"> $QQQ “bUt tHe NeWs sAiD!” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:24:29 </td>
   <td style="text-align:left;"> $UVXY $SPY $QQQ All distraction to reality &amp;gt;&amp;gt;&amp;gt;

 “I do think we need to front-load more of our planned removal of accommodation than we would have previously. We’ve been surprised to the upside on inflation. Bullard told CNBC’s Steve Liesman during an interview earlier this week.

The St. Louis Fed president, who tends to lean more hawkish on monetary policy, previously called for interest rates to be increased by a full percentage point by July 1.

“I’d like to see 100 basis points in the bag by July 1,” Bullard said in an interview with Bloomberg last week.  “I was already more hawkish but I have pulled up dramatically what I think the committee should do.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:23:21 </td>
   <td style="text-align:left;"> $QQQ Clear Skies to $360 $TQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:23:01 </td>
   <td style="text-align:left;"> $Qqq do I cover now and take the loss or wait for overnight and fed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:22:39 </td>
   <td style="text-align:left;"> $QQQ $SPY keep propping b4 fomc everyday same shit prop and dump. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:22:35 </td>
   <td style="text-align:left;"> omg tomorrow is going to be nuts you thought today was big tomorrow is DAY 2 OMG 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:22:03 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:20:52 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $NDX … if u didn’t know about fed minutes tomorrow.. now u know </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:20:20 </td>
   <td style="text-align:left;"> $QQQ everytime sleepy Joe talks the market drops. Thanks Joe you bitch, made my calls hit a stop loss. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:19:48 </td>
   <td style="text-align:left;"> $QQQ this is going to be interesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:19:45 </td>
   <td style="text-align:left;"> How many bears fell for the mid day shakeout - if you have no conviction what are you even trying. Follow PT only one pajama $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:19:44 </td>
   <td style="text-align:left;"> $QQQ why did everyone stop buying??? Don&amp;#39;t we want this higher?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:18:37 </td>
   <td style="text-align:left;"> $SPY $QQQ Earnings this afternoon:  
 
$RBLX down 13%, $UPST up 27%, $ABNB up 4% 
 
Join our discussion over at discord.io/MomentTrading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:17:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN $TSLA $AAPL  
 
&amp;quot;If you&amp;#39;re worried about a few stocks holding up the market, then you clearly don&amp;#39;t own those few stocks that are holding up the market.&amp;quot; 
 
There are things you can control and things you can&amp;#39;t! The solutions are easier than we think! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:16:51 </td>
   <td style="text-align:left;"> $QQQ Folks keep saying inflation is priced in! Have you ever lived through inflation? What happens when people have to start pulling out from their investments to pay the bills? This Market is incredibly unstable right now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:16:29 </td>
   <td style="text-align:left;"> $SPY $QQQ We&amp;#39;ve seen this before. First we gapped up into CPI data. That ended well. Now we are gapping up into FOMC minutes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:15:40 </td>
   <td style="text-align:left;"> $QQQ everyone load up on 400c for next week 🤙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:15:38 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Closing imbalance = ~$146M to the BUY side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:14:35 </td>
   <td style="text-align:left;"> $SPY $QQQ You see what happens after the close😉

As soon as the algos go to sleep

Drop this piece of shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:14:09 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Market momo &amp;amp; activity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:14:04 </td>
   <td style="text-align:left;"> $QQQ Biden acting strong is watching my elderly neighbor scream at the kids to stop skateboarding. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:13:45 </td>
   <td style="text-align:left;"> $UPST Massive win to those who caught this ALERT on my discord   
  
Did you catch it? Join for FREE  
 
discord.io/MomentTrading 
   
$QQQ $SPY $RBLX $ABNB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:13:38 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Fear &amp;amp; Greed Index </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:13:36 </td>
   <td style="text-align:left;"> $QQQ who doesn’t love lower fuel prices!📈📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:13:18 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY Trump&amp;#39;s financial statements are getting looked over with a fine-tooth comb by the NY Attorney General </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:13:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Economic calendar for 2/16 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:12:42 </td>
   <td style="text-align:left;"> $QQQ some of yall just so delusional and clueless, the volume was absolute piss. “bulls in control”
how far away are you guys from the highs?
money printer just keep going, makes zero sense.. im long, but this makes no sense. everything is priced in.. if thats the case, why arent we at all time highs? inconsiderate of whats really going on in the real word. powell has no business being the head or being in the federal reserve, behind raising rates, inflation 40 year high and still printing money! makes alot of sense! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:11:34 </td>
   <td style="text-align:left;"> $QQQ rblx good for tech </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:10:52 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA time to abort now!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:08:51 </td>
   <td style="text-align:left;"> $QQQ li qui di ty

liquidity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:08:39 </td>
   <td style="text-align:left;"> $QQQ It honestly blows my mind how they talk about lowering prices and fighting inflation while at the same time running a fucking money printer.🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:08:25 </td>
   <td style="text-align:left;"> $SPY $QQQ $XBI  We are going up! Today shows the importance of 5 minutes and the close. We may come back fill the gap, but yesterday&amp;#39;s low will hold until we reach $SPX4780 IMO. GL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:08:02 </td>
   <td style="text-align:left;"> $QQQ tomorrow the fed is going to take off the training wheels off the market.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:08:00 </td>
   <td style="text-align:left;"> Although the technical rating is bad, $QQQ does present a nice setup opportunity. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:06:05 </td>
   <td style="text-align:left;"> $RBLX Sold calls an hour before close, for 18% profit.  
 
Did you catch it? Join my FREE discord.discord.io/MomentTrading   
  
$QQQ $SPY $BTC.X $NASDAQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:05:40 </td>
   <td style="text-align:left;"> $QQQ bad news ? $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:05:16 </td>
   <td style="text-align:left;"> $QQQ whyd the printer turn off???! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:04:28 </td>
   <td style="text-align:left;"> $QQQ straight to the poor house for the bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:03:52 </td>
   <td style="text-align:left;"> $SPY $QQQ ya lets buy stonks on the brink of war 🤣 yall a bunch of stupid 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:03:47 </td>
   <td style="text-align:left;"> $QQQ Hard to put my Capitol to work, with market like this. 
Im sure I am the only one who has this problem. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:03:32 </td>
   <td style="text-align:left;"> $QQQ I&amp;#39;d be more excited if this went up half of a percent, but these stupid run ups are nothing but a set up for bad news drop the next day. Good luck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:03:26 </td>
   <td style="text-align:left;"> $QQQ Dropping faster than my pants </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:03:20 </td>
   <td style="text-align:left;"> $QQQ crypto rally&amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:03:16 </td>
   <td style="text-align:left;"> $TECS going to test KUMO &amp;amp; 50dEMA supports tomorrow 👁️ ☕ 👆👇 
$TECL $QQQ   
( Using chart program Pro ☞ https://tinyurl.com/y32cywz4 ) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:03:13 </td>
   <td style="text-align:left;"> $VIX came down a lot into the close, probably at least a couple more days of rally $ARKK $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:02:16 </td>
   <td style="text-align:left;"> $SPY $QQQ People are overreacting every week to the Fed, interest rate hikes are already priced in IMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:01:25 </td>
   <td style="text-align:left;"> $QQQ let’s have a -5% day tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:01:21 </td>
   <td style="text-align:left;"> $QQQ there can only be one loser and this week that’s you bears! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:01:03 </td>
   <td style="text-align:left;"> $QQQ soo much noise on the Russian Ukraine news distracting from rate hike news . Look at rate soon damn high $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:00:40 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ 
 
FED-sponsored bulls BTMFD and WIN AGAIN!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:00:39 </td>
   <td style="text-align:left;"> $QQQ $AAPL  Apple sales at close, Jesus Christ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:00:30 </td>
   <td style="text-align:left;"> $QQQ got a feeling markets gonna be down the next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:00:29 </td>
   <td style="text-align:left;"> $QQQ bears Gone broke </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:00:28 </td>
   <td style="text-align:left;"> $QQQ 375 very strong possibility here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:00:24 </td>
   <td style="text-align:left;"> $QQQ perhaps bears are low IQ .. it is also possible they are dumb AF though </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:00:10 </td>
   <td style="text-align:left;"> $QQQ They can pump it on low volume they can bring it down just as quick when they feel like it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 05:00:01 </td>
   <td style="text-align:left;"> $QQQ $SPY Another low volume rally and still short of reaching the 10 dma. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:59:50 </td>
   <td style="text-align:left;"> $QQQ an invasion remains distinctly possible.

let&amp;#39;s go brandon!

go moon ATHs! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:59:37 </td>
   <td style="text-align:left;"> $NOVT Oi! The $QQQ is up over 2%! What’s going on?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:59:13 </td>
   <td style="text-align:left;"> $QQQ Bears got fooked. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:59:09 </td>
   <td style="text-align:left;"> $QQQ HONK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:58:52 </td>
   <td style="text-align:left;"> If it makes you all feel better, know that it&amp;#39;s next to impossible to trade markets with this elevated volatility.   
 
Of course, I&amp;#39;m sure at least half of you have a perfectly trained market-top parrot that alerts you exactly when you&amp;#39;re supposed to sell.  But for everyone who doesn&amp;#39;t own a perfectly trained trading parrot, good luck trying to flip as fast as price-insensitive hedging programs.   
 
If you&amp;#39;ve been getting chewed up, know that BOTH sides have gotten chewed up recently.  Again, I&amp;#39;m sure 50+% of traders here never make a single mistake thanks to their parrots.   
 
But for everyone else, play past it. 
 
$SPY $QQQ $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:58:35 </td>
   <td style="text-align:left;"> $QQQ Alright I&amp;#39;m putting my horns back on. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:58:29 </td>
   <td style="text-align:left;"> $SPY JUST IN:

@CBSDavidMartin reporting US can see Russia units moving out of assembly areas toward the Ukraine border.

$qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:58:13 </td>
   <td style="text-align:left;"> $QQQ Biden’s just trying to look like a bad ass on camera then sink the markets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:58:05 </td>
   <td style="text-align:left;"> $QQQ lol. so biden shows strength and they still berate him?   so is he weak or strong?  pick one and stick with it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:57:46 </td>
   <td style="text-align:left;"> $QQQ come on, make my 410c expiring tomorrow itm 🤞🤞🤞🤞 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:57:23 </td>
   <td style="text-align:left;"> $SPY $QQQ when will you bears understand that you can’t short Brandon? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:57:09 </td>
   <td style="text-align:left;"> pajama, MARKET GOD 
 
DID YOU LISTEN 
 
$spy $qqq  
 
prepare for blowout chip earnings omg parabolic nobody will even talk about inflation or war anymore the numbers are just that good $nvda </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:57:07 </td>
   <td style="text-align:left;"> $qqq just buy low n sell high every other day!!  Such an easy fookin game!!!  🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:56:59 </td>
   <td style="text-align:left;"> $QQQ Im gonna be nice. If you want you could trade puts until tomorrow at 6am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:56:42 </td>
   <td style="text-align:left;"> $QQQ they literally set it up for &amp;quot;US intelligence agencies were hack by Russians. Time for war&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:56:39 </td>
   <td style="text-align:left;"> $SPY rug pull tomorrow?

$qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:56:35 </td>
   <td style="text-align:left;"> $QQQ lol prop up for tomorrow fed meeting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:56:28 </td>
   <td style="text-align:left;"> $QQQ wow talk about a frothy market lol we just had horrible PPI nums &amp;amp; Biden about to start WW3 for talking out his ass &amp;amp; we are rallying?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:56:14 </td>
   <td style="text-align:left;"> $QQQ deja vu </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:56:00 </td>
   <td style="text-align:left;"> $SPY $QQQ Love it, keep pushing bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:55:46 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA WOWZERS TIME TO VISIT THE SUBMARINE STORE!!! 😏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:55:40 </td>
   <td style="text-align:left;"> $SPY $QQQ we should replace the stock market with an NFT of the stock market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:55:04 </td>
   <td style="text-align:left;"> $QQQ thank god the fed are still putting billions into the market. This is so fucked when 20% of its cap tapers lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:55:03 </td>
   <td style="text-align:left;"> Traderfirstyear - (2 of 2) Investment Note Figuring out the Twin Deficit for 2022 -Twin Deficit Fiscal Deficit (with inflation assumption to stress why Real Value of the deficit is going to present considerable fiscal drag, which will act to both cap growth and eventually slow growth (nominal and real), which is why I&amp;#39;m VERY worried about a RECESSION in 2023 if the Federal Reserve hikes more than once in 2022. I will assume a fixed inflation rate of 5% for 2022 (i showed my estimates of CPI, but I&amp;#39;m going to cautiously use a higher number)  - Data will appear on the next page very important - I am showing you why I am predicting elevated Risk of a Recession in 2023 $SPY $QQQ $VIX  
 
Key Points to take away 
(1.) Fiscal Drag will be extremely heavy this year and will weigh on growth both nominal and real 
(2.) Aggressive rate-hiking stance (monetary policy has an 8 to 12-month lag, so HUGE risk to growth in 2023 from hikes in 2022.) The bond market is screaming RECESSION </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:54:39 </td>
   <td style="text-align:left;"> $QQQ real rally starts AH📈📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:54:19 </td>
   <td style="text-align:left;"> $QQQ don’t be surprised if this cools off quick. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:53:53 </td>
   <td style="text-align:left;"> $QQQ Poor bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:53:49 </td>
   <td style="text-align:left;"> $QQQ Biden and Putin said fuck yo puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:53:46 </td>
   <td style="text-align:left;"> $QQQ bear annihilation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:53:45 </td>
   <td style="text-align:left;"> $QQQ come on I just grabbed 410c expiring tomorrow! Let&amp;#39;s go!! 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:53:41 </td>
   <td style="text-align:left;"> $QQQ there could not be a better time to buy puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:53:38 </td>
   <td style="text-align:left;"> $QQQ bears right now.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:53:36 </td>
   <td style="text-align:left;"> $SPY $QQQ lol nice now they can gap it red again with no damage  overnight wowwww </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:53:32 </td>
   <td style="text-align:left;"> $RBLX Roblox is scheduled to report earnings after the closing bell 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:53:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X short covering everywhere in the market... lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:53:23 </td>
   <td style="text-align:left;"> $SPY $QQQ spring </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:53:21 </td>
   <td style="text-align:left;"> $QQQ $SPY 

Fill that Gap 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:53:17 </td>
   <td style="text-align:left;"> $QQQ Pelosi bought calls and the Market is ripping. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:53:08 </td>
   <td style="text-align:left;"> I unfortunately must interrupt this #BullMarket enthusiasm $SPY $QQQ $DIA $IWM  
With a reminder from our #BearMarket sponsor $LQD  
#investing #stocks #StockMarket </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:53:03 </td>
   <td style="text-align:left;"> $QQQ $SPY $356 calls 3.28-3.90+....gotta play both sides...LIVE ALERT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:52:52 </td>
   <td style="text-align:left;"> $QQQ Buying big Poots here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:52:49 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
FED-sponsored bulls BTMFD and WIN AGAIN!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:52:39 </td>
   <td style="text-align:left;"> $QQQ 🤣🤣 more puts thanks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:52:38 </td>
   <td style="text-align:left;"> $QQQ everyone keeps expecting a stock market collapse next week and for all we know this was just a correction and we are about to go to new all time highs. The market historically behaves very well during rate hikes because the signal that the economy is doing good. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:52:36 </td>
   <td style="text-align:left;"> $QQQ Poots are toast. Game. Set. Match. Bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:52:35 </td>
   <td style="text-align:left;"> $SPY $QQQ Best Bear Market Ever 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:52:29 </td>
   <td style="text-align:left;"> $QQQ moreeeeeeeeeeeee! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:52:22 </td>
   <td style="text-align:left;"> $QQQ What would cause the algos to drop it? they can pump it forever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:52:21 </td>
   <td style="text-align:left;"> $QQQ Lol bears mad again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:51:50 </td>
   <td style="text-align:left;"> $SPY $QQQ Market rips 2% on fake news and now it doesn’t go down?

It’s obvious what’s happening. 

The amount of puts below is unreal and it’s all algos and mms burning them.

Wait once they expire and see what happens. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:51:36 </td>
   <td style="text-align:left;"> $QQQ wasn’t everyone certain yesterday that Russia would invade?? lol give this a few days and it’ll be back down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:51:34 </td>
   <td style="text-align:left;"> $QQQ YES!!! No more inflation! They forgot to put the - sign before the numbers came oout. Technical error they said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:51:28 </td>
   <td style="text-align:left;"> $QQQ FUCK YES THAT BIG 🍆 CANDLE JUST SAVED MY LIFE 🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:51:25 </td>
   <td style="text-align:left;"> $QQQ knew it was coming, pulled down to support then launch.

Shorts in trouble and getting trapped </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:51:23 </td>
   <td style="text-align:left;"> $SPY $QQQ The big guy needs a big war distraction right now to bury his criminality and, um, perversion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:51:16 </td>
   <td style="text-align:left;"> $SPY $QQQ when we put tariffs on cheese Putin made his own cheese. You can’t get your fat foodie out of your house. Send him to Ukraine to fight for democracy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:51:10 </td>
   <td style="text-align:left;"> $SPY $QQQ Merica! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:50:53 </td>
   <td style="text-align:left;"> $QQQ MM&amp;#39;s actually convinced some people that the speech was bullish. Wow... Just wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:50:49 </td>
   <td style="text-align:left;"> $QQQ here come the fireworks 🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:50:49 </td>
   <td style="text-align:left;"> $QQQ all the headlines will be negative tonight after that speach watch, Binden just provoking Putin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:50:38 </td>
   <td style="text-align:left;"> $QQQ russia tensions arent the reason the mkt is in bear territory... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:50:36 </td>
   <td style="text-align:left;"> $QQQ wow this price action is unreal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:50:19 </td>
   <td style="text-align:left;"> $QQQ Biden says “Shorts and Russia have no balls” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:49:16 </td>
   <td style="text-align:left;"> $QQQ huge gap up after hours off that news imo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:49:16 </td>
   <td style="text-align:left;"> Traderfirstyear - (1 of 2) Investment Note Figuring out the Twin Deficit for 2022 - To do this you have to remember the fiscal year in these estimates is not the calendar year. It runs from October to September (starting in October 2021 and ending in September 2022), so to correctly assume or get in the ballpark what I normally do is figure out the monthly average from Sept to Oct then factor in the next year from Oct to Dec to get it into a full calendar year. In the above, you notice the calendar year deficit averaged a little over 215 Billion per month. The estimates for the fiscal year in 2021 are about 80 billion and 70 Billion in 2023 (which starts in Oct of 2022), so using these two numbers I usually assume Jan through Sept at 80 Billion a month and Oct through Dec at 70 Billion to give me a calendar year estimate - This will give me a forecasted estimate for the Fiscal part of the twin deficit $SPY $DIA $QQQ $VIX $TLT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:49:16 </td>
   <td style="text-align:left;"> $QQQ $SPY get ready for tomorrow fed Ted talk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:49:02 </td>
   <td style="text-align:left;"> $QQQ Putin playing games </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:48:59 </td>
   <td style="text-align:left;"> $SPY $QQQ rugpull canceled </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:48:55 </td>
   <td style="text-align:left;"> Dow jumps 300 points, snaps 3-day losing streak as Russia-Ukraine tensions cool a bit

$DJIA $QQQ $SPX 

https://www.cnbc.com/2022/02/14/stock-market-futures-open-to-close-news.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:48:40 </td>
   <td style="text-align:left;"> $QQQ degenerates think that war with Russia is fun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:48:26 </td>
   <td style="text-align:left;"> $QQQ Biden gonna rocket this market 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:48:07 </td>
   <td style="text-align:left;"> $QQQ great speech by Biden Joe, bulls still in control </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:47:44 </td>
   <td style="text-align:left;"> $SPY $QQQ Fight With Russia more fun than Covid </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:47:40 </td>
   <td style="text-align:left;"> $QQQ headlines “ war adverted expect cheaper fuel prices in near future” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:47:36 </td>
   <td style="text-align:left;"> Thanks to this “credible” Fed, we’ve record high inflation, shaky economy,m and a pump &amp;amp; dump stock market. 🤮
$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:47:09 </td>
   <td style="text-align:left;"> $QQQ can someone explain to me how Biden and company are going to lower gas prices? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:46:58 </td>
   <td style="text-align:left;"> $QQQ about to go crazy over the News📈📈📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:46:37 </td>
   <td style="text-align:left;"> $SPY $QQQ Russia got the oil spike it wanted out of this whole ordeal. Was stuck at 80 for a while, the news keep claiming Russia hasn&amp;#39;t gotten anything out of this. Well they do get billions more in profit, probably enough extra cash to offset troop deployment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:46:30 </td>
   <td style="text-align:left;"> $QQQ 352 close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:45:58 </td>
   <td style="text-align:left;"> $QQQ war adverted and Biden is going to lower fuel prices&amp;gt;&amp;gt;&amp;gt;&amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:45:54 </td>
   <td style="text-align:left;"> $SPY $QQQ bears fell for the old wag the dog war tactic for midterms. If bps comes out .50&amp;lt; this is going to be a slaughterhouse fest for bears wanting to profit on war. Lol get what y’all deserve. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:45:53 </td>
   <td style="text-align:left;"> $SPY $QQQ I want to open hot Ukraine dance club. I can not allow this in Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:45:50 </td>
   <td style="text-align:left;"> See the problem is not today but will futes be red or green tomorrow???? $AMD $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:45:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA 
Never Ever Buy Uncertainty </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:45:32 </td>
   <td style="text-align:left;"> $SPY can $QQQ just fuck off now shit drops 0.05% and rallies 2% each time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:45:23 </td>
   <td style="text-align:left;"> $QQQ cheap gas = 📈📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:45:21 </td>
   <td style="text-align:left;"> $UVXY $SPY $QQQ We all know that

Russian attack on Ukraine still possible - Biden https://www.bbc.co.uk/news/world-us-canada-60396947 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:45:21 </td>
   <td style="text-align:left;"> $QQQ bye bye inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:45:17 </td>
   <td style="text-align:left;"> $QQQ Def an unexpected red day tm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:45:16 </td>
   <td style="text-align:left;"> $QQQ Threats are always good. 
Said No One. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:45:12 </td>
   <td style="text-align:left;"> $SPY $QQQ They should have sent out Jen Psaki </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-16 04:45:06 </td>
   <td style="text-align:left;"> $SPY $QQQ calls every biden speech day.. puts for the following day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 08:29:18 </td>
   <td style="text-align:left;"> $AAPL $BCS $COIN  
 
Account Challenge Update:-  
Start Date: Jan 3, 2022  
Starting Balance: $1,700  
Current Balance: $84,969 
Goal: $100,000 by end of February.  
Strategy: Swing Trade Options, Stocks  
  
Watch out for next play👓 top.stocksboss.xyz/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 08:20:01 </td>
   <td style="text-align:left;"> 📊 $AAPL 
🚀 94% Profitable 
🤖 AI-Driven Machine Learning 
🏆 SwingTradePro Strategy 
Join Our Premium Room For Live Trade Alerts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 08:19:41 </td>
   <td style="text-align:left;"> $AAPL Getting into the Metaverse? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 08:13:37 </td>
   <td style="text-align:left;"> $BA $UAL $DAL $AAPL $DIS Russians bluffed !! They are good chess players and they know how and when to move back their figures, but AMERICANS are the GREATEST poker players and they caught Putin’s bluff. Lol 😂 it was all about poker faces and guess what, Mr. Putin, this time you did not play it very well. We will have another great GREEN day tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 08:10:55 </td>
   <td style="text-align:left;"> $IWM  One time for my intuitive trading m************ out there !!!! $AAPL 🤑🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 08:07:32 </td>
   <td style="text-align:left;"> $NVDA announce another aquiassion instead of arm and this will run up. Announce actual metaverse utilization and this flies. Announce plans for your own fabless plant and this soars.  
Now the chances for downside, Announce poor earnings, poor guidance and supply chain LONG term. All of which are very low probability.. 
No other opportunities getting in on an $AAPL or a $MSFT at past 15% but prior to %75 entery point </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 08:02:31 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-02-15 Trade Analysis Video: 
https://www.youtube.com/watch?v=nhvDYe1pCzc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 08:01:20 </td>
   <td style="text-align:left;"> $AMD $spy  $btc.x   $aapl  $TSLA  
Impact of Fed rate changes on the S&amp;amp;P 500 
----------------------------------------- 
Impact of Fed interest rate changes on S&amp;amp;P 500 since 2017 
The chart below tracks the S&amp;amp;P 500, along with the dates that Fed rate cuts and hikes were announced over a three-year period. It’s apparent to see that trends are not always clear cut: following a quarter point rate hike in December 2017, the S&amp;amp;P 500 went on to defy expectations and climb almost 6% in January 2018. 
 
The chart also shows there can be significant shifts in stock prices around the time of Federal Open Market Committee announcements. Ahead of the rate cut in October 2019, there was a period of significant volatility; after it was announced, the S&amp;amp;P 500 closed at a record high. It’s important to monitor news, be aware of economic events that could affect stock prices and build these into the trading plan. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 08:01:17 </td>
   <td style="text-align:left;"> $AAPL 
Super-Setup, Inside-Cloud, Active-Sequence, Crossed-Ema[8,13,21,34]-UP, Crossed-Ema13-UP, Crossed-Sma[50]-UP 
#SuperSetup 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 07:54:37 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #1 ticker with sweep activity where institutions are trading options urgently with 57.2K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 07:52:47 </td>
   <td style="text-align:left;"> $SPY to 420  $AAPL 160 $AMZN  $WhosKnow??? $ES_F  $NQ_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 07:52:40 </td>
   <td style="text-align:left;"> $UPST shorts and bears will get brutally slaughtered here .. monster earnings and guidance.. and $400 M buyback will send the stock to $300 soon… $NVDA $AMD $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 07:45:38 </td>
   <td style="text-align:left;"> $AAPL Calm down guys! 
After all we are still in Feb ! 
Till End of Feb anything possible!  
Short term not sure where this is going, but I would say we will see $155 before the run... 
Long term for sure will jump crazy high </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 07:43:48 </td>
   <td style="text-align:left;"> $FB not touching this for few more quarters! The cash bleeding is very real with their meta investment! $AAPL privacy also changed the game and there are several powerful alternatives out there. They&amp;#39;re not going anywhere but the stock has more bleeding to do imo. no rush to get in this one. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 07:33:00 </td>
   <td style="text-align:left;"> $AAPL 🔥💵🚀 for money for the team </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 07:26:06 </td>
   <td style="text-align:left;"> Apple TV+ buys docuseries &amp;#39;The Dynasty&amp;#39; about the New England Patriots $aapl #nfl $nflx
https://appleinsider.com/articles/22/02/15/apple-tv-buys-docuseries-the-dynasty-about-the-new-england-patriots https://appleinsider.com/articles/22/02/15/apple-tv-buys-docuseries-the-dynasty-about-the-new-england-patriots </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 07:18:49 </td>
   <td style="text-align:left;"> $AAPL stock analysis based on today&amp;#39;s closing price 

https://youtu.be/8l9NGKvYKoM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 07:16:25 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 07:12:08 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL why you always lyin, you always lying, media always lyin! russians never lyin! lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 07:06:00 </td>
   <td style="text-align:left;"> $AAPL seems like the market keeps pushing back up against top resistance and wants to break up. That&amp;#39;s a bullish indicator if I ever saw one. Blue chips don&amp;#39;t want to be held back and this looks like a bear trap that is only just beginning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 07:05:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL 

Listen, all I’m saying is that Elon wasn’t donating billions of dollars of stock when Tesla (and the market in general) was fairly valued 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 07:00:08 </td>
   <td style="text-align:left;"> $UPST $TTD $QQQ $FB $AAPL  my portfolio is god damn awesome. F y’all shorts. 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 06:58:23 </td>
   <td style="text-align:left;"> All the trades from the past 2 days. Not to mention my top tier “Insider alerts” whole team has been banking. 
$QQQ $AAPL $NIO $SPCE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 06:52:43 </td>
   <td style="text-align:left;"> $AAPL Looking at today news about Putin pulling some of his army…

War is usually a catalyst to start buying not selling. It happened through all the wars. Sell the rumors buy the news. 

Only the rumors and uncertainty are pushing the markets down. 

And if there will be no war at all the market will go up even strongly. 

So for all of you that think that war and inflation are going to crash the market - forget it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 06:51:44 </td>
   <td style="text-align:left;"> Ticker: $AAPL 
Buy: February 18, 2022 $175.00 Calls 
Entry Price: $0.66 - $0.68 
Exit Price: $0.92 
Stop Loss: $0.58 
Potential ROI: 40% 
Estimated Hold Time: 58 Minutes 
Alert Courtesy Of: https://www.fastscalp.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 06:42:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 51 analysts. The buy consensus is at 84%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 06:40:09 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 06:38:32 </td>
   <td style="text-align:left;"> $AAPL Has been very technical off the Jan 24 low.  A pullback against Jan 24 low can be complete at the recent lows, we don’t like to sell it short, only like buying at blue boxes in 3, 7 or 11 swing #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 06:36:47 </td>
   <td style="text-align:left;"> $AAPL Data suggest that the overall analyst sentiment for AAPL  is bullish. Simplify the way you research stocks with Invescent   
https://play.google.com/store/apps/details?id=org.invescent.invescent&amp;amp;hl=en_US&amp;amp;gl=US </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 06:35:48 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Bear at a Party </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 06:32:44 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMD $QQQ  🐂🐂🐂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 06:27:40 </td>
   <td style="text-align:left;"> $ABNB  $CCL $AAPL  $AMD  $MSFT  
   There are similar parallels comparing both.   
  You will see that next earnings Carnival will beat exponentially and move possibly above $50.00 a share. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 06:23:05 </td>
   <td style="text-align:left;"> $AAPL 2030 what&amp;#39;s apples price 👀🎲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 06:16:32 </td>
   <td style="text-align:left;"> $AAPL as usual this one paid nicely 💎💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 06:12:34 </td>
   <td style="text-align:left;"> $BRK.B $AAPL $QQQ $SPX $SPY MarketWatch - Apple is Berkshire’s largest stock holding, but Buffett and Co. own a bigger share of these companies
 https://on.mktw.net/3JsWetd </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 06:10:18 </td>
   <td style="text-align:left;"> Peak profit for the last 6 expired option alerts for $AAPL 8.45| 222.38| 138.10| 537.50| 1329.91| 52.17| </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 06:09:35 </td>
   <td style="text-align:left;"> $SWKS next Mergers and acquisitions (M&amp;amp;A) by $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 06:07:56 </td>
   <td style="text-align:left;"> $AAPL closed my calls in the green, phew; will reassess tomorrow with caution. Armies in authoritarian regimes are like work dogs, you keep them busy or they find something to do and you probably won’t like it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:57:00 </td>
   <td style="text-align:left;"> Possible swing trading patterns are detected for $AAPL, $PAYX and $HSY by our stock screener. https://www.chartmill.com/stock/stock-screener?sid=28&amp;amp;f=s_str,s_n20h,etf_none,p_pg20,v1_50b20,cu_b_sm10v,cu_a_sm20v,exch_us&amp;amp;v=3&amp;amp;s=n&amp;amp;sd=ASC&amp;amp;timeframe=DAILY&amp;amp;type=CANDLES&amp;amp;months=3&amp;amp;width=720&amp;amp;cl=F&amp;amp;o1=3&amp;amp;o2=3&amp;amp;op1=10,16711680&amp;amp;op2=30,255&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=screener&amp;amp;utm_content=Stock_Screener:_Swing_Trading&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:55:26 </td>
   <td style="text-align:left;"> MoneyWatch: New Apple Pay features - CBS News $AAPL https://apple.news/Al3YkgKm6Qw6AINAkv4Fp1w </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:53:16 </td>
   <td style="text-align:left;"> $AAPL 🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:51:38 </td>
   <td style="text-align:left;"> $AAPL Just when you think bears couldn’t get any dumber, they shorted AAPL because of Russia/ Ukraine conflict now they are trapped piling up loses upon loses. Too funny! 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:50:24 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:45:59 </td>
   <td style="text-align:left;"> Having said that, there are times when you SHOULD hold certain stocks for several years.  $TSLA, $AAPL, $NVDA, $FTNT are multi-year holds for me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:43:29 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL got pump out of air rsi weak </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:39:22 </td>
   <td style="text-align:left;"> $AAPL Just a couple strong days away from ATH. That makes sense. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:38:35 </td>
   <td style="text-align:left;"> $AAPL 
https://news-static.webullfintech.com/us/news-html/20220215/48952747.html?theme=1&amp;amp;hl=en&amp;amp;color=2&amp;amp;_v=1&amp;amp;tickerId=913256135&amp;amp;disSymbol=AAPL&amp;amp;sp=0&amp;amp;hl=en </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:36:15 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 312.1K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:33:31 </td>
   <td style="text-align:left;"> latex7709f97cb90f3ce6913d0d885f55a032AMD 806k (72% call/27% put)
$TSLA 791k (57% call/43% put)

Lynk in bayo for option trading ideas and alert </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:29:08 </td>
   <td style="text-align:left;"> $AAPL $TSLA $AMZN CLOSE YOUR TD AMERITRADE NOW IF YOU LOVE FREEDOM!!! https://www.google.com/amp/s/www.foxbusiness.com/politics/canadian-freedom-convoy-td-bank-freezes-accounts-with-1-1m-for-trucker-protest.amp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:22:12 </td>
   <td style="text-align:left;"> $AAPL APPLE closed below the EMA. Bearish tomorrow so expect a huge drop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:22:08 </td>
   <td style="text-align:left;"> $ENPH $PLUG $FCEL $AAPL 💪🦬💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:20:29 </td>
   <td style="text-align:left;"> $AAPL Marketing Expert Josh Snow: Mentor On &amp;#39;Going PublicⓇ&amp;#39;s Latest Episode 

https://newsfilter.io/a/6a8ce5f1b94b1678227ba2a773b3e024 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:18:17 </td>
   <td style="text-align:left;"> ( $DKNG), Caesars Entertainment Corporation (NASDAQ: $CZR) –  $AAPL Apple App Store Analysis: FanDuel, $DKNG DraftKings Surge Into The Top 25 Amid Super Bowl LVI https://www.billionaireclubcollc.com/dkng-caesars-entertainment-corporation-nasdaqczr-apple-app-store-analysis-fanduel-draftkings-surge-into-the-top-25-amid-super-bowl-lvi/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:17:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN $TSLA $AAPL  
 
&amp;quot;If you&amp;#39;re worried about a few stocks holding up the market, then you clearly don&amp;#39;t own those few stocks that are holding up the market.&amp;quot; 
 
There are things you can control and things you can&amp;#39;t! The solutions are easier than we think! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:16:01 </td>
   <td style="text-align:left;"> $spy $gme $aapl $rig 

https://podcasts.apple.com/us/podcast/the-chinchilla-picking-podcast/id1557339848?i=1000550908634 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:16:00 </td>
   <td style="text-align:left;"> $AAPL I&amp;#39;ve made $180K with them, By their alert. If you really want to make a huge profit on trading. Choose this professional chat. 
https://linktr.ee/Trading214 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:13:42 </td>
   <td style="text-align:left;"> $AAPL Hello </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:11:45 </td>
   <td style="text-align:left;"> $AAPL - back inside the green zone.  Looking for a move to the middle of the channel initially. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:06:26 </td>
   <td style="text-align:left;"> Is this good for your portfolio? $AAPL in Uptrend: price expected to rise as it breaks its lower Bollinger Band on January 19, 2022. View odds for this and other indicators: https://srnk.us/go/3417442 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:05:50 </td>
   <td style="text-align:left;"> $TSLA $AAPL $MSFT beautiful day 😊🤙💰💰💰💰💰💰💰💰💰💰💰💰💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:05:39 </td>
   <td style="text-align:left;"> $AAPL I don&amp;#39;t kike the gap created over night. But we are not going anywhere but 167 to 180 for the next 2 months anyways 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:04:51 </td>
   <td style="text-align:left;"> $AAPL   🍏😎👍    Very nice day.  Strong, Close.  Chillax, this evening.  Until tomorrow…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:04:30 </td>
   <td style="text-align:left;"> $AAPL 

#EXCELLENTCLOSEAPPLE🍏🔜🆙🔝 
$183 AGAIN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:04:24 </td>
   <td style="text-align:left;"> $AAPL I guess Biden don&amp;#39;t want to answer questions lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:03:32 </td>
   <td style="text-align:left;"> $AAPL So close ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:02:17 </td>
   <td style="text-align:left;"> $AAPL I went long  this fri calls at  the cross of 172.50... just looking for a move to 175.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:00:43 </td>
   <td style="text-align:left;"> $AAPL 
That was a great close in couple of days! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 05:00:39 </td>
   <td style="text-align:left;"> $QQQ $AAPL  Apple sales at close, Jesus Christ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:59:36 </td>
   <td style="text-align:left;"> $AAPL BIG FED MEETING TOMORROW. Whole market tanking $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:58:05 </td>
   <td style="text-align:left;"> $AAPL Timber!!!!! It’s crashing!! 😂 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:58:04 </td>
   <td style="text-align:left;"> $AAPL well that was a damn good day of trading! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:57:39 </td>
   <td style="text-align:left;"> $AAPL $F $BTC.X $DOGE.X    
this is where I have my entire life savings. good to go or am I an idiot? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:57:34 </td>
   <td style="text-align:left;"> $AAPL since 3:30pm volume pouring into aaple to get the Spy up Apple is like viagra for the MKT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:56:15 </td>
   <td style="text-align:left;"> $AAPL BIG day is tomorrow, hoping for peace! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:54:24 </td>
   <td style="text-align:left;"> $AAPL fed meeting tomorrow huge selloff $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:52:47 </td>
   <td style="text-align:left;"> $AAPL 
TURN ON NASDAQ 
——————————-
TURN ON $AAPL +$173 BREAKOUT 
TURN ON $TQQQ +$58 BREAKOUT 
—————————— </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:52:34 </td>
   <td style="text-align:left;"> $AAPL $185 here we come! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:52:31 </td>
   <td style="text-align:left;"> $AAPL the future looks very bright! It&amp;#39;s almost blinding. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:52:29 </td>
   <td style="text-align:left;"> $AAPL Been noticing volume at these stores are way down compared to last year at the is time...Looking forward to a string of large misses throughout 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:51:36 </td>
   <td style="text-align:left;"> $AAPL huge bull trap wow !! 🤣🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:51:09 </td>
   <td style="text-align:left;"> $AAPL 🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:49:25 </td>
   <td style="text-align:left;"> $AAPL watch this 3:50 sell off till close.   Will end close to red. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:47:41 </td>
   <td style="text-align:left;"> $AAPL 176.00 quite possibly tomorrow 
Apple looking to go higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:47:23 </td>
   <td style="text-align:left;"> $AAPL massive buying on the way! ..  dont listen to such troll who are anti Biden .. they learned nothing ... I don&amp;#39;t give a damn if it is Biden or Trump. I want someone to announce with confidently and say and confirm the least good news so we can invest with less worries off the shoulder. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:47:08 </td>
   <td style="text-align:left;"> $AAPL selling into close will be intense </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:45:44 </td>
   <td style="text-align:left;"> $AAPL incredible volatility </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:44:34 </td>
   <td style="text-align:left;"> $AAPL Russia sends warplanes to Syria for naval drills in the Mediterranean Sea https://www.marketwatch.com/story/russia-sends-warplanes-to-syria-for-naval-drills-in-the-mediterranean-sea-01644957760?mod=mw_latestnews </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:44:29 </td>
   <td style="text-align:left;"> $AAPL $AMZN $TSLA $QQQ $SPY Market should be down 3-4% today with 9.1% inflation report. Rally based on lower risk of Russian attack but the real threat has not diminished at all.  Putin will lie to your face saying the sky is red while you both are looking up at a blue sky </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:44:17 </td>
   <td style="text-align:left;"> Top Bearish Flow Today : 

$TSLA $RIOT $NVDA $AMD $AAPL

🤖📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:44:14 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:43:51 </td>
   <td style="text-align:left;"> Top Bullish Flow Today : 

$NVDA $VIX $AMD $TSLA $AAPL 

🤖📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:42:22 </td>
   <td style="text-align:left;"> $AAPL that was the worst way he could have ever delivered that. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:42:04 </td>
   <td style="text-align:left;"> $AAPL market abt to get killed.   30% drop coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:41:43 </td>
   <td style="text-align:left;"> $AAPL Takes no questions. What a leader. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:41:10 </td>
   <td style="text-align:left;"> $AAPL Biden trying to make Putin angry? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:41:00 </td>
   <td style="text-align:left;"> Looking at the yearly performance, $AAPL did better than 90% of all other stocks. https://www.chartmill.com/stock/quote/AAPL/technical-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:40:39 </td>
   <td style="text-align:left;"> $AAPL lies lies lies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:40:24 </td>
   <td style="text-align:left;"> $AAPL brutal!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:39:52 </td>
   <td style="text-align:left;"> $SPY Biden promise to attack and defend Ukraine if attacked by Russia. Since they didn&amp;#39;t withdraw and the media lied this morning. $AAPL $MSFT $TSLA $USO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:39:28 </td>
   <td style="text-align:left;"> $DIA $SPY $IWM $AAPL Pretty sure market goes down literally everytime Sleepy Joe speaks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:38:49 </td>
   <td style="text-align:left;"> $AAPL market is fucked.  Get out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:38:43 </td>
   <td style="text-align:left;"> $BKKT LOL $AAPL clloab </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:38:42 </td>
   <td style="text-align:left;"> $spy Time to make some $aapl sauce   &amp;gt;=) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:38:22 </td>
   <td style="text-align:left;"> $AAPL WHOOPS ! Looks like Russia ain’t off the table, and neither is inflation 💀 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:36:40 </td>
   <td style="text-align:left;"> $AAPL 

Now the shorts are leaving due to very good news … on continued high level diplomacy and further pursuant on de-escalation !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:35:12 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPl  here comes senile guy to crash market...keep ur lid close. and work with russia behind doors </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:34:33 </td>
   <td style="text-align:left;"> $AAPL Biden announced they will pursue high level diplomacy and de-escalation .. this is very good news. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:34:20 </td>
   <td style="text-align:left;"> $AAPL 

Get Biden off the air </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:33:45 </td>
   <td style="text-align:left;"> $RBLX $aapl $snap $qqq

Every damn time president talk, the stock go down and vx go up 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:32:41 </td>
   <td style="text-align:left;"> $AAPL 172 holding like a rock! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:31:32 </td>
   <td style="text-align:left;"> $AAPL attack is still a possibility </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:31:04 </td>
   <td style="text-align:left;"> $AXP learn from American Express $AAPL $V $MA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:30:08 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-02-15 Trade Analysis Video: 
https://www.youtube.com/watch?v=nhvDYe1pCzc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:29:27 </td>
   <td style="text-align:left;"> $RBLX radar close. Biden is going to speak about Russia. He can collapse the market. Or fly up.  $WELL $AAPL. $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:28:41 </td>
   <td style="text-align:left;"> $AAPL GOP senators introduce sanctions package against Russia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:28:07 </td>
   <td style="text-align:left;"> $SPY Dang Yields are cranking

 $AAPL $NFLX $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:24:09 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:23:29 </td>
   <td style="text-align:left;"> $AAPL https://twitter.com/AP/status/1493601284695412745?t=LoqHOvLX52Pw-QZs_mNwSw&amp;amp;s=19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:21:40 </td>
   <td style="text-align:left;"> $AAPL Secured bulls, nothing to worry about. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:20:15 </td>
   <td style="text-align:left;"> $AAPL $QQQ $SPY We love when our members share posts - especially ones like this Green Goose system alert play gain - LOVE IT…. Keep STACKING 💪😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:19:57 </td>
   <td style="text-align:left;"> $AAPL lol get fucked bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:19:03 </td>
   <td style="text-align:left;"> $AAPL CORRUPT MEDIA BIAS...😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:18:36 </td>
   <td style="text-align:left;"> $AAPL $NVDA  positive earning report tomorrow will drag $AAPL to 176-178. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:18:28 </td>
   <td style="text-align:left;"> $QQQ $SPY  $AAPL Updated daily chart of the q’s. More room to upside within this pennant. solid earnings from companies like $RBLX and $NVDA could break us out back to highs in 2021. Though a bearish continuation is possible as well. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:15:34 </td>
   <td style="text-align:left;"> $AAPL bullishhhhhh👊🏼👊🏼👊🏼👊🏼👊🏼🙏🏻🙏🏻🎉🎉🎉👊🏼👊🏼❤️❤️‼️‼️‼️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:15:21 </td>
   <td style="text-align:left;"> $AAPL Consensus price target: $200 to $210. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:13:29 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:12:11 </td>
   <td style="text-align:left;"> $AAPL Get ready for the slide )) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:11:57 </td>
   <td style="text-align:left;"> $AAPL 

Market Cautious, But Up. 
Volume little by little, But Up. 
Go to $173. +Breakout </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:10:07 </td>
   <td style="text-align:left;"> $AMD $AAPL $TSLA $ABNB Anyone find this rally off troops a bit inflated? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:10:05 </td>
   <td style="text-align:left;"> $AAPL Inverted Head and Shoulders forming on 60 minutes chart
Apple Rallies to 176.00 to 177.00 PT 
If it breaks above then $AAPL to 197.00 /200.00
At least in the short term it bodes well for technology sector and the overall market.
$AMD $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:07:45 </td>
   <td style="text-align:left;"> $AAPL A little more bulls.. Nancy needs to sell these Donations 🙈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:05:56 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMD $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:03:52 </td>
   <td style="text-align:left;"> $ETH.X I feel like $AAPL was the most obvious investment of the 2010&amp;#39;s. And ETH is the most obvious investment of the 2020&amp;#39;s. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:03:30 </td>
   <td style="text-align:left;"> $AAPL Ukraine requests international assistance from NATO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:02:56 </td>
   <td style="text-align:left;"> $AAPL 10MA &amp;amp; 50MA acting as resistance 🖖🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:01:38 </td>
   <td style="text-align:left;"> $AAPL Tigris Financial just raised Apple to $210 PT! Mo money Mo money Mo money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 04:01:13 </td>
   <td style="text-align:left;"> $FB 220 break and hold will be big and easy move to 221 $AAPL $AMZN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:58:42 </td>
   <td style="text-align:left;"> $AABB $TSLA $1000  $AAPL $200    $MSFT $350   $GOOG  $3500   $AABB X20-X50 before the up listing on a Major Exchange! https://finance.yahoo.com/news/asia-broadband-corporate-173900628.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:57:43 </td>
   <td style="text-align:left;"> $TLRY $AAPL 
https://twitter.com/tilray/status/1493603840402329607?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:56:15 </td>
   <td style="text-align:left;"> $AAPL - $RBLX - $NVDA 

Congrats to bulls who played with us today - 🤖🤝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:53:44 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL

I added puts to this sucker rally. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:51:13 </td>
   <td style="text-align:left;"> $AAPL EOD all I need is anywhere in 170.. let it be 170.999 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:51:10 </td>
   <td style="text-align:left;"> $AAPL - Here we go bulls - 🤖📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:50:15 </td>
   <td style="text-align:left;"> $AAPL 

$172 Ready. 
Go to $173. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:49:57 </td>
   <td style="text-align:left;"> $SNDL   man for this stock the stats are lining. and I&amp;#39;m getting excited. PH will we VERY NICE
Mine $TSLA $AAPL $MARA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:49:12 </td>
   <td style="text-align:left;"> $AAPL nice try Tim Apple. This ponzu scheme has gone on long enough.  Please enjoy the road down below latex263f1a7ba04379625ad041d1d19ff1c5AMD ↗️

$AAPL $TSLA $MSFT $NVDA  https://www.cdp.net/en/research/global-reports/engaging-the-chain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:46:52 </td>
   <td style="text-align:left;"> $AAPL going down to 125 per share $DJIA $QQQ too many empty stores and overpriced employees … better investments out there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:45:45 </td>
   <td style="text-align:left;"> $AAPL Looks like members of congress are loading up lol $$$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:42:02 </td>
   <td style="text-align:left;"> $AAPL 172! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:41:52 </td>
   <td style="text-align:left;"> Intraday Option Volumes

$AAPL 594k (56% call/44% put)
$TSLA 557k (59% call/41% put)
$AMD 498k (75% call/25% put)
$SPCE 483k (76% call/24% put)

Lynk in bayo for the channel </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:41:15 </td>
   <td style="text-align:left;"> $AAPL rip but still holding on 😥❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:40:50 </td>
   <td style="text-align:left;"> $BP this should be well over 50s at least my goodness. Haha. It will catch on soon. Gas look at the profits people. $AAPL $AMC $SNDL and $AMZN watching. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:39:18 </td>
   <td style="text-align:left;"> $SPY $AMD $NVDA $AAPL $TSLA 
Where’s joe? 
Is he dressing up to talk about putin in 50 minutes? Please!! If he can avoid talking today, all the retail traders will be very happy. 
(But sorry i have no information and not sure if hes coming to pump the market saying ; DEAL REACHED WITH PUTIN!!) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:38:59 </td>
   <td style="text-align:left;"> $AAPL Tell me about this magic Apple product that will allow Apple to continue to beat earnings when people have less buying power. I&amp;#39;m very bullish on Apple long term but I don&amp;#39;t see how Apple can convince people to use a greater percentage of their income on Apple products in the short term when they&amp;#39;re struggling affording food and gas. Luckily we seem to have some of the most fiscally irresponsible people in the word here in the US so it&amp;#39;s possible everyone will just take on more debt so they can upgrade their Apple pencil. I hear the next one will have an eraser! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:38:39 </td>
   <td style="text-align:left;"> $AAPL i loaded qqq puts so mind selling off like 10 bucks so i can buy a new house??? why you guys so selfish, gimmie some of those relentless gains you always be collecting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:38:04 </td>
   <td style="text-align:left;"> $AAPL    🍏 Biden to Speak, in 1 hr. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:37:49 </td>
   <td style="text-align:left;"> $AAPL -- this pattern hasn&amp;#39;t played out the way I thought it would, and it&amp;#39;ll need to hurdle the 50sma to get any traction, but still intact. 
 
We&amp;#39;re long in the DrStoxxTrading Room  Join us! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:35:01 </td>
   <td style="text-align:left;"> $AAPL this  will have a strong close. Lets see tomorrow what happens with the fed announcement. My guess is it will be a dovish tone and stocks will go higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:34:19 </td>
   <td style="text-align:left;"> $AAPL Apple on Sale !!this is a real good Buy right now , ton of runway !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:32:58 </td>
   <td style="text-align:left;"> $AAPL (Free the NET) … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:31:37 </td>
   <td style="text-align:left;"> $FSR $TSLA $LCID $NIO $AAPL you can now reserve Fiskers project pear 🍐 starting under 30k... picture of the Ocean coming this November underneath. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:28:59 </td>
   <td style="text-align:left;"> $AAPL https://www.benzinga.com/news/22/02/25638172/tigress-financial-maintains-strong-buy-on-apple-raises-price-target-to-210 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:26:20 </td>
   <td style="text-align:left;"> $SPY $SPY $AAPL   
 
   &amp;quot;  Uuuuughuhuhuhuhuh Beavis, * break over 26 day candle average line at $447ish, gets a surge to old flat cloud bottom equilibrium leve at $450.  ichimoku shows that level spent a lot of time there..   magnet..  , taqrgeting the armpit of ichimoku cloud ahead shown. that cloud was formed month ago when it twisted bearish.   ichimoku cloud forms 26 candles ahead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:25:56 </td>
   <td style="text-align:left;"> $AAPL $GOOGL $AMZN $MSFT hm, Zero Hedge being a Russian shill? 🤔 

“The officials said Zero Hedge, which has 1.2 million Twitter followers, published articles created by Moscow-controlled media that were then shared by outlets and people unaware of their nexus to Russian intelligence”

https://apnews.com/article/russia-ukraine-coronavirus-pandemic-health-moscow-media-ff4a56b7b08bcdc6adaf02313a85edd9 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:24:07 </td>
   <td style="text-align:left;"> $SPY  $AAPL  #WhosKnow?? $AMZN #NASDAQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:22:41 </td>
   <td style="text-align:left;"> $AAPL $AMD $QQQ $SPY 
$VIX returning to 20 We shall see.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:22:37 </td>
   <td style="text-align:left;"> $PLTR $AAPL $GME $AMC $BB Palantir move has started the run into Earnings on Thursday morning!  February 17, 2022. Should get above $15 before earnings and the same catalyst that hurt us before will assist us on the move to all time highs this year! Price Target adjustment to $32 before May 13, 2022.
 
Revenues should be $420-$425 millions
EPS might be lower .03-.04 because of one time expenses. 
But growth will be over 35%. Margins will expand. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:21:11 </td>
   <td style="text-align:left;"> $AAPL (Siri saw the earth) and (Now mama sues.) Look up those sentences on a reverse speech app….Do you guys think that apple products did this to the population? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:19:42 </td>
   <td style="text-align:left;"> $RIDE HOLY CRAP.  Is it finally happening?  Over a year of epic short attack (70% short volume days regularly) and FTD shorting violations (10x more than TSLA for months even when trading a FRACTION of latexe4d6c91046ce61f9a591535412addbfeFSR just said 250k EV will come out of Lordstown Motors factory in 2024, but that only happens if Lordstown Motors/Foxconn deal is done deal, right?  :D  
 
Not sure if FSR has a CONTRACT for that volume or not.  I believe Lordstown Motors is in 1st position as per the sale agreement terms, so Foxconn is contracted to produce over 100% of stated Lordstown Motors Endurance production goals each quarter.   
 
$AAPL may throw a proverbial wrench in this for anyone W/O a contract in place as I&amp;#39;d guess Foxconn bumps non-contracted parties for $AAPL if opportunity arises. 
 
Just my opinions!  :D </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:19:26 </td>
   <td style="text-align:left;"> $AAPL Tigress Financial Is Bullish On Apple - Read Why 

https://newsfilter.io/a/a9a8701dbea73c48999bee13c3f9d050 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:19:20 </td>
   <td style="text-align:left;"> $XCUR $AAPL ciuff ciuff, train departing last tickets we leave 
 
6 $ tp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:13:37 </td>
   <td style="text-align:left;"> $AAPL $AMZN https://youth-investment-group.com/2022/02/15/heres-wallstreets-top-stock-picks-for-2022/amp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:13:21 </td>
   <td style="text-align:left;"> $AAPL holding 2000 shares </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:12:42 </td>
   <td style="text-align:left;"> $AAPL 160 $SPY 420 #WhosKnow??? #NASDAQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:11:57 </td>
   <td style="text-align:left;"> $AAPL ...$STUDY $QQQ $SPY 📚 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:10:49 </td>
   <td style="text-align:left;"> $djia needs 35000 to crack shut struggling $spy $aapl $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:10:46 </td>
   <td style="text-align:left;"> $AAPL Equity Sentiment: $AAPL is the #1 stock that institutions are trading with 26.4K options contracts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:07:45 </td>
   <td style="text-align:left;"> $AAPL Tim Apple robbing more suckers before you find the worms in his stash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:06:22 </td>
   <td style="text-align:left;"> $VNUE $SPOT $AAPL $SIRI here we go.    Music industry veterens keep joining VNUE.  Something big is brewing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:04:22 </td>
   <td style="text-align:left;"> $SPY I’m shorting $AAPL $NVDA $SPY at 3:30pm Eastern for the BIG BEAR BIDEN speech. Everything’s peaking so it’ll be perfect for a short opportunity then selling it before close. Nice 20 minute play. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:03:58 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:03:12 </td>
   <td style="text-align:left;"> Equity Sentiment: $AAPL is the #1 stock that institutions are trading with 26.4K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 03:01:03 </td>
   <td style="text-align:left;"> $AAPL Low volume pump…get ready for the rug pull! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:58:52 </td>
   <td style="text-align:left;"> $AAPL 

36M traded hands .. the spectators are awaiting for massive buy orders on Biden announcement at 3:30 PM. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:57:28 </td>
   <td style="text-align:left;"> $AAPL shorting this all the way down to 7 dollars a share. I&amp;#39;ll cover around 6.50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:56:13 </td>
   <td style="text-align:left;"> $AAPL Soon 🔜 +$172 Breakout. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:54:56 </td>
   <td style="text-align:left;"> $AAPL another go at 172 incoming 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:49:25 </td>
   <td style="text-align:left;"> $AAPL $TTWO Super Bowl 2022 Halftime Performers Dominate iTunes Charts After The Game 

https://newsfilter.io/a/11ccea6ec5b8d4cc79adbb9358e74b0a </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:44:22 </td>
   <td style="text-align:left;"> $AAPL Oooo... my 170p got filled.. didn&amp;#39;t even noticed. scary though. 170P 03/04 paid $2.95.. can I exit with dollar gain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:42:09 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-02-14 Trade Analysis Video: 
https://www.youtube.com/watch?v=rOWkB7irxsE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:37:46 </td>
   <td style="text-align:left;"> $AAPL Over 172.30, we run to 176-177. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:36:11 </td>
   <td style="text-align:left;"> $AAPL 

https://www.fool.com/investing/2022/02/15/where-will-apple-be-in-10-years/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:36:07 </td>
   <td style="text-align:left;"> $SPY $AAPL $TQQQ  $SOXL $NVDA 
So this would be...
1. 🚀🚀  until Mar 15 Fed FOMC
2. -2% SPY on Mar 15-16 on rate announcement 
3. 🚀🚀🚀  after March 16 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:35:18 </td>
   <td style="text-align:left;"> $AAPL I go long calls if we break  172.5....looking for 175 ish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:35:06 </td>
   <td style="text-align:left;"> $AAPL Bullishness in NASDAQ and Apple again as Russia Ukraine Tensions Ease

$QQQ $AMD $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:34:44 </td>
   <td style="text-align:left;"> $AAPL 

https://www.computerworld.com/article/3649729/the-apple-silicon-transition-is-almost-complete.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:34:44 </td>
   <td style="text-align:left;"> $AAPL upgrade going to $200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:33:51 </td>
   <td style="text-align:left;"> $AAPL The fuckqqq does Ukraine and Russia have to do with the company? Lmaoo 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:33:43 </td>
   <td style="text-align:left;"> $AAPL from oversold to parabolic. Unreal price action </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:32:03 </td>
   <td style="text-align:left;"> $AAPL 
VOLUME UP TREND &amp;gt;200K Per minutes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:31:51 </td>
   <td style="text-align:left;"> $AAPL Bullish 18 Feb 170 puts sold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:31:42 </td>
   <td style="text-align:left;"> $SPY $SPX #ES_F 
growth stocks will do amazing with a flat yield curve 
$AAPL $AMZN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:31:25 </td>
   <td style="text-align:left;"> $AAPL   🍏Now: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:31:16 </td>
   <td style="text-align:left;"> $AAPL +$172 BREAKOUT 🍏🔜🆙🔝☕️. Soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:31:06 </td>
   <td style="text-align:left;"> $AAPL this just ripped higher the last our anything happening? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:31:01 </td>
   <td style="text-align:left;"> $NIO $TSLA $AAPL $SPY 

Our Permabear buddy Dan Niles isn’t doing too well today!

https://m.youtube.com/watch?v=apCU1SnnulA&amp;amp;t=203s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:29:06 </td>
   <td style="text-align:left;"> $AAPL 

Low volume but big buy uptick …

This shows that each is going to take this stock very strong green territory ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:28:47 </td>
   <td style="text-align:left;"> $AAPL  🍏MM’s Flow, is back.  President Biden, will “Speak” at 3:30pm/EDT:  Topic:  Russia-Ukraine Conflict.  Watch for movement in the VIX, &amp;amp; Indices…indicating, “WH News Leaks generating movement ahead of the Event”. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:27:34 </td>
   <td style="text-align:left;"> $AAPL daily RSI from overbought to oversold and now back at overbought levels , hedgies are making money , killing retail at every step </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:26:50 </td>
   <td style="text-align:left;"> $AAPL let it rip Wall Street! $$$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:25:59 </td>
   <td style="text-align:left;"> $FB $NIO $TSLA $AAPL 

Dan Niles said yesterday he was going to “put his shorts back on” Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:24:24 </td>
   <td style="text-align:left;"> Meta Stock Has Never Been Cheaper. Is It Time to Buy?  $FB $AAPL $MSFT $GOOG $AMZN 

https://newsfilter.io/a/b5f4695a9a5f11d5cb3c0affd0c81324 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:23:16 </td>
   <td style="text-align:left;"> Can some one tell when will my 3 trades will be available on Robinhood i lastly traded all of them on Friday all 3 of them ? $SPY $QQQ $AAPL $SOFI $AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:22:33 </td>
   <td style="text-align:left;"> $AAPL that was easy $$$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:21:48 </td>
   <td style="text-align:left;"> $AAPL was a little bit scary there for a sec. lets go 173!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:18:23 </td>
   <td style="text-align:left;"> $SPY $AMD $NVDA $AMZN $AAPL 
If joe can cancel the press conference and can stay away from making any statement at 3:30 pm, i prefer that one
EVEN IF HIS PLAN IS TO PUMP THE MARKET- NO DONT NEED PLS STAY AWAY LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:14:55 </td>
   <td style="text-align:left;"> $AAPL bears i thought that this was crashing down to $150? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:11:55 </td>
   <td style="text-align:left;"> $AAPL 172.84 close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:11:51 </td>
   <td style="text-align:left;"> $AMD is going to be one of those stocks in the next couple of years where people wished they got in the early 100&amp;#39;s like $TSLA $AMZN $AAPL Lisa SU even said it herself &amp;quot;THE BEST IS FUCKING YET TO COME!&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:10:04 </td>
   <td style="text-align:left;"> DO I HAVE TO WAIT TILL FRIDAY NOW? TO DO DAY TRADES SINCLE I TARDED 3 optoions last week on Friday SSPY $Sofi $AAPL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:09:06 </td>
   <td style="text-align:left;"> $SPY expert bear Joe Biden to save the day at 3:30 $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:08:22 </td>
   <td style="text-align:left;"> $AAPL 
NASDAQ MORE STRONG.  237 Points. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:07:20 </td>
   <td style="text-align:left;"> $FSR $TSLA $LCID $RIVN $AAPL Fisker opened up reservations to its project 🍐 starting at under $30k before tax incentives. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:07:01 </td>
   <td style="text-align:left;"> $SPY boutta dump again couldn’t pass resistance $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:05:37 </td>
   <td style="text-align:left;"> $EH wonderfull flying of an EHANG autonomous air taxi with 2 ladies

https://twitter.com/robinbirdmedia/status/1491128638267621378?s=21

5-10 year ahead

Competitors come maybe maybe 😂2024 /25 to market
Piloted 
😩☹️😟😫

🧐

True first mover like $AAPL or $AMZN have been 👊💪🏼

Imho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:04:54 </td>
   <td style="text-align:left;"> $AAPL Apple PT raised at Tigress as products, services set to drive &amp;#39;record performance&amp;#39; New PT $210 - lets gooooooo !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:04:48 </td>
   <td style="text-align:left;"> $AAPL 41.27% gain  
UMGLab.com Highly Profitable Alerts Delivered to Your phone. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:03:10 </td>
   <td style="text-align:left;"> $SPY massive bull trap here $NVDA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 02:01:07 </td>
   <td style="text-align:left;"> $AAPL this is headed to $130. Hedge your position and buy puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:59:33 </td>
   <td style="text-align:left;"> $AAPL $NVDA $AMZN https://youth-investment-group.com/2022/02/15/heres-wallstreets-top-stock-picks-for-2022/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:59:16 </td>
   <td style="text-align:left;"> $AAPL Sit back grab some popcorn watch the manipulation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:56:43 </td>
   <td style="text-align:left;"> Can any one tell the reason for it I day traded 3 options on Friday but haven’t done any trades this week but why is this ? $SPY $Sofi $AAPL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:56:39 </td>
   <td style="text-align:left;"> $AAPL  🍏 Noontime HFund Shorts, hitting the Tape.  They are just playing with each other, now.  MM isn’t indulging, he turned off his “Money/Volume Flow” Order Book.  This is a new, recent MM pattern.  These Naked Shorts can oscillate the price…but, most end up Covering Higher to stimulate enough Volume to “Buy Cover”. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:54:38 </td>
   <td style="text-align:left;"> $AAPL Red eod </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:54:35 </td>
   <td style="text-align:left;"> $AAPL Are they going to kill the iPhone? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:52:09 </td>
   <td style="text-align:left;"> Most Traded Contracts

$AAPL February $175 Call
$AAPL February $172.50 Call
$MGI March $11 Call
$AMD February $120 Call
$SBSW March $20 Call </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:51:51 </td>
   <td style="text-align:left;"> Can any one tell the reason for it I day trades 3 options on Friday but haven’t done any trades this week but why is this ? $SPY $Sofi $AAPL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:51:45 </td>
   <td style="text-align:left;"> $AAPL this is why you don’t trust a man named after a fruit. First he steals your wife, then he steals your money. 

Damn you Tim Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:51:01 </td>
   <td style="text-align:left;"> $AAPL massive marketwide short attack .. sync on dipping!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:50:37 </td>
   <td style="text-align:left;"> $AAPL 🤣🤣🤣🤣 166 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:50:36 </td>
   <td style="text-align:left;"> $AAPL this has been rejecting off lower and lower ceilings, could be a sign </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:50:11 </td>
   <td style="text-align:left;"> $SPY $aapl $tsla $spce $msft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:49:20 </td>
   <td style="text-align:left;"> $MSFT $SPY $BTC.X $AAPL lame all turning red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:49:11 </td>
   <td style="text-align:left;"> $AAPL $MSFT 

Both stocks going much lower … sell both of these … people so done they want their lives back they don’t want more phones more video games, they want reality , they want their family back , they want to laugh , love , big crash is coming …. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:48:37 </td>
   <td style="text-align:left;"> $AXP best stock you can own in this uncertain situation… loser bulls on $AAPL $MSFT $V and $MA and winning bulls in $AXP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:41:00 </td>
   <td style="text-align:left;"> $AAPL Joe Biden giving a speech today at 3:30pm eastern. Prepare for fallout $SPY $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:36:30 </td>
   <td style="text-align:left;"> $AAPL 

Short attack on small volume - that tells you that shorts are very weak.

This is a clear bear trap!

Majority of the shares traded hands are on heavy buy side !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:35:49 </td>
   <td style="text-align:left;"> $SPY $AMD $NVDA $AAPL $RBLX 
Sleepy Joe dipping the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:33:02 </td>
   <td style="text-align:left;"> $AAPL has an excellent technical rating and also presents a decent setup pattern. https://www.chartmill.com/stock/analyzer/stock/AAPL?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:32:01 </td>
   <td style="text-align:left;"> $AAPL another bull trap here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:31:31 </td>
   <td style="text-align:left;"> Buffet slowly pinching his way into tech $ATVI $BRK.B $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:30:09 </td>
   <td style="text-align:left;"> $SPY $AMD $NVDA $AAPL $AMZN 
Every dip is scaring you isn’t it? 
These are challenging times in the market. 
Dunno where a dip ends. Is it gonna be a nasty 2000 points nasdaq selloff in 2 days or a normal dip. 
We will have good times after mid summer i believE
These conditions we had in 2016 often </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:29:17 </td>
   <td style="text-align:left;"> $SPY PPI up 1%. RUSSIA just pulled a just kidding on invasion. NATO showed satellite images of them not pulling out but getting ready for false flag attack! $USO $SPCE $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:28:24 </td>
   <td style="text-align:left;"> $FB Mark is all-in on metaverse.  If that doesn&amp;#39;t work out then facebook will be the next penny stock as facebook itself continues losing users to other platforms.  Oh, and $AAPL is not your friend.  $SNAP $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:27:50 </td>
   <td style="text-align:left;"> $AAPL flat .. flatter then flat azz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:26:47 </td>
   <td style="text-align:left;"> $AAPL 🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:25:39 </td>
   <td style="text-align:left;"> $AAPL $165 possibly $162 coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:25:21 </td>
   <td style="text-align:left;"> $AAPL  🍏 Noontime HFund Shorts, Attacking the Tape. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:24:52 </td>
   <td style="text-align:left;"> $AAPL wow man bucket full of tards up in here. In the morning when i said i dont expect an above 172.5 close EOW , the price action now is in line with that. Thats a reasonable call right? Now with a less than $1 fall from HOD, the bears are here calling for 165 when the price is already $1.8 higher from yesterdays (green, mind you) close. SMh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:24:47 </td>
   <td style="text-align:left;"> $Spy $AAPL $FB $SPCE $TSLA Russia Shows no Sign of De-Escalation on the ground. NATO disputes these claims with Satellite images https://www.youtube.com/watch?v=uz-Zg8-E4aY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:24:45 </td>
   <td style="text-align:left;"> $SPY A good way to tell HFs are losing on Bearish bets is when Mike Wilson is on CNBC, the Perma-Bear who said to not Buy in 2020 :o) 
 
He will suck the life out of the Market from 12-1 w/ his doom &amp;amp; gloom but if anyone listens to this Guy just know, he&amp;#39;s horrible 
 
$aapl $ba $jpm $amzn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:24:09 </td>
   <td style="text-align:left;"> $AAPL CNBC CROOKs only bring bears like Mike Wilson to manipulate the markets! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:24:06 </td>
   <td style="text-align:left;"> $AAPL bulls are running for the fences… they never listen $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:24:01 </td>
   <td style="text-align:left;"> $AAPL weekly pin...172.5-.....175? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:21:40 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL ppi + fomc minutes. you really expect this to go up because Putin teased you? hahahahah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:21:26 </td>
   <td style="text-align:left;"> $AAPL back down to 165 here we go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:21:06 </td>
   <td style="text-align:left;"> $AAPL bought some put gonna sell at close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:20:55 </td>
   <td style="text-align:left;"> $AAPL Massive cyber attacks all over Ukraine. Russia regression is BS. Whole market tank IMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:19:08 </td>
   <td style="text-align:left;"> $AAPL bull trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:19:04 </td>
   <td style="text-align:left;"> $AAPL headed to 6 bucks a share by Friday. Sorry longs. Hey everyone, let&amp;#39;s all short this! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:19:01 </td>
   <td style="text-align:left;"> $AAPL here goes the pullback </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:17:22 </td>
   <td style="text-align:left;"> $AAPL Enjoy the bag bulls, it&amp;#39;s appletizing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:17:11 </td>
   <td style="text-align:left;"> $AAPL Too much instability for this to be green. Tank coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:15:21 </td>
   <td style="text-align:left;"> Top Bullish Flow (a/o12:14pmEST): $CMG $AAPL $UAL $GE $MRNA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:14:06 </td>
   <td style="text-align:left;"> latexb81cf951401e14a071b7ee721897a3fbAAPL  pe 28 
$GOOGL pe 24.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:11:48 </td>
   <td style="text-align:left;"> $AAPL I know I sounds like a broken record but if people have less buying power due to inflation and have run out of stimulus/unemployment money then how do they continue to buy Apple products at the same rate so that Apple can continue to beat earnings? It doesn&amp;#39;t matter if they keep buying Apple if the rate decreases or stays flat, that&amp;#39;s an earnings miss. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:11:30 </td>
   <td style="text-align:left;"> $AAPL you have to love that 40-50 cent difference between calls and puts favoring calls.  hopefully not a theta burn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:09:50 </td>
   <td style="text-align:left;"> $XCUR $AAPL let&amp;#39;s go guys, today we fly, 
6$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:09:17 </td>
   <td style="text-align:left;"> $AAPL 4hr view from 2/01 update. Showing further reaction higher taking place from the blue box area #Elliottwave #Trading #Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:08:19 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:08:02 </td>
   <td style="text-align:left;"> $AAPL latest rating from Tigress Financial on 2022-02-15, setting target price at: USD 210.00 with a rating of Strong-Buy. StockTargetAdvisor&amp;#39;s own view is Slightly Bullish  with an average target price of USD 182.56. Details: https://www.stocktargetadvisor.com/stock/USA/NSD/AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:06:19 </td>
   <td style="text-align:left;"> $XCUR $AAPL let this little girl fly to the moon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:06:00 </td>
   <td style="text-align:left;"> Breakout pattern shown in $AAPL, $ALSN and $GD. https://www.chartmill.com/stock/stock-screener?sid=202&amp;amp;f=v1_50b500,atrpct_a_1,sl_ta_7_X,sl_se_7_X,p_pg20,exch_us&amp;amp;s=se&amp;amp;v=3&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=screener&amp;amp;utm_content=Stock_Screener:_Technical_Breakout_Setups&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:05:27 </td>
   <td style="text-align:left;"> 1250 $AAPL 25FEB2022 $172.5 Cs trade 2.35 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:04:16 </td>
   <td style="text-align:left;"> $XCUR $AAPL it has dropped a lot in the future let&amp;#39;s expect a nice rise suddenly if only they talked a little bit towards $ 6 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:04:09 </td>
   <td style="text-align:left;"> $SPY Damn....$aapl is setup to for the biggest dump of the year  =O </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:01:35 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #1 ticker with sweep activity where institutions are trading options urgently with 26.4K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 01:00:22 </td>
   <td style="text-align:left;"> $AAPL 4hr view from 1/30 weekend update. Found buyers at the blue box area &amp;amp; showing reaction higher taking place from the blue box area. Longs should be risk free by now #Elliottwave #Trading #Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 00:58:07 </td>
   <td style="text-align:left;"> $qqq $goog $amzn https://www.youtube.com/watch?v=CI93IWCx9XQ&amp;amp;ab_channel=UnlimitedOptionsInvesting $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 00:58:04 </td>
   <td style="text-align:left;"> $FB Positive news on their ability to better report due to last years iOS changes - Underreporting of iOS Web Conversions Down to 8% From 15% Last September $SNAP $TWTR $AAPL https://www.adweek.com/programmatic/meta-underreporting-of-ios-web-conversions-down-to-8-from-15-last-september/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 00:56:37 </td>
   <td style="text-align:left;"> $AAPL then managed to reach the blue box area from where buyers were expected to appear  #Elliottwave #Trading #Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 00:50:07 </td>
   <td style="text-align:left;"> $AAPL buy-limit @ 135,76_stop-loss @ 115,76 &amp;amp; target @ 182,94 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-16 00:47:51 </td>
   <td style="text-align:left;"> $AAPL can we market stay green all day for once this year? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:51:45 </td>
   <td style="text-align:left;"> $TSLA BTC not looking great! 🥴 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:51:38 </td>
   <td style="text-align:left;"> $TSLA  4hr view from Feb 1 update. Showing reaction higher taking place from the blue box area #Elliottwave #Trading #Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:50:39 </td>
   <td style="text-align:left;"> $TSLA 4hr view from January 9 update. Bounce failed in a double correction &amp;amp; managed to reach another blue box area where buyers were expected to appear again #Elliottwave #Tading #Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:50:03 </td>
   <td style="text-align:left;"> $TSLA it&amp;#39;s going down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:49:43 </td>
   <td style="text-align:left;"> $TSLA I just want a flash crash to 800... let me collect about 5k put profit and I&amp;#39;ll roll it all into 1100 April calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:49:29 </td>
   <td style="text-align:left;"> $ALGO.X $BTC.X $ETH.X $DOGE.X $TSLA https://cryptosrus.com/musk-family-invests-in-algorand/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:46:59 </td>
   <td style="text-align:left;"> $TSLA https://youth-investment-group.com/2022/02/15/tesla-revenues-to-exceed-gm-and-ford-combined-by-2027-according-to-wallstreet/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:43:15 </td>
   <td style="text-align:left;"> Excellent, welcome to Crash Wednesday, this post is approved by my good friends at Seeking Alpha moderating my posts for my profits, hopefully for you too. Carry on sticking forks in the stock markets at large overpriced sincenthe beginning of the recession in 2009, quite realistically 1999 imho re due diligence. Good health and trading to all. https://www.investing.com/indices/indices-futures Thank dog that I am here to help 🐻❤😈✔👍😁 @Profit_Maker https://stocktwits.com/Profit_Maker 🤑 Welcome to the Autogeddon Depression 🐷 $f $Gm $tm $tsla $stla and more 😃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:43:03 </td>
   <td style="text-align:left;"> $TSLA has a Profit Margin of 10.26%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:40:54 </td>
   <td style="text-align:left;"> latex6d06a9213ff9ff6166ae6c660334a93e by 11 am tomorrow then back to 880$.. STONKKKS!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:40:33 </td>
   <td style="text-align:left;"> $TSLA i am sensing a big stinky dump worse than anything we have seen in a while </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:39:59 </td>
   <td style="text-align:left;"> $TSLA https://www.tesmanian.com/blogs/tesmanian-blog/tesla-model-y-deliveries-have-begun-in-the-uk-and-the-first-cars-have-already-been-handed-over-to-owners 🏎🚀🤖🔋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:38:56 </td>
   <td style="text-align:left;"> $TSLA https://abcnews.go.com/Politics/russian-troops-moved-firing-positions-ukraine-putin-ready/story?id=82909721 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:38:12 </td>
   <td style="text-align:left;"> $TSLA https://www.tesmanian.com/blogs/tesmanian-blog/tesla-model-y-became-the-top-selling-high-end-ev-suv-in-china-in-january-2021 🏎🚀🤖🔋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:37:07 </td>
   <td style="text-align:left;"> $TSLA 4hr view from 2/01 update. Showing reaction higher taking place from the blue box area #Elliottwave #Trading #Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:36:59 </td>
   <td style="text-align:left;"> $TSLA 

He calls himself a beta tester, agrees and Consents to that yet turns around and runs to CNBC for little exchange 💰 to bash the company and talk their skills and talents down !! 

Straight out defamation with malicious intent!!  

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:36:52 </td>
   <td style="text-align:left;"> $TSLA 4hr view from 1/09 weekend update. Bounce failed in a double correction &amp;amp; managed to reach another blue box area where buyers were expected to appear again #Elliottwave #Tading #Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:36:37 </td>
   <td style="text-align:left;"> $TSLA it&amp;#39;s normal for bears to roam around in the night. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:32:18 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-15 Technical Analysis Video: 
https://www.youtube.com/watch?v=dw-_95ODzdY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:30:02 </td>
   <td style="text-align:left;"> $TSLA someone needs to set Biden up on neurolink!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:28:38 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:28:28 </td>
   <td style="text-align:left;"> $TSLA, $VW, $GM, $F Ford Are All Driving Demand In This Sector! https://www.billionaireclubcollc.com/tsla-vw-gm-ford-are-all-driving-demand-in-this-sector/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:26:52 </td>
   <td style="text-align:left;"> More here $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:26:23 </td>
   <td style="text-align:left;"> $MR.X wonder if I&amp;#39;ll be able to buy a $TSLA in the $MR.X game? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:26:18 </td>
   <td style="text-align:left;"> $AMZN $TSLA $INCT  
 
Account Challenge Update:-  
Start Date: Jan 3, 2022  
Starting Balance: $1,700  
Current Balance: $84,969 
Goal: $100,000 by end of February.  
Strategy: Swing Trade Options, Stocks  
  
Watch out for next play👓 top.stocksboss.xyz/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:25:31 </td>
   <td style="text-align:left;"> $TSLA russia Hasn’t pulled back yet. still bearish market. 860 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:19:02 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $SPY $DWAC $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:18:51 </td>
   <td style="text-align:left;"> $TSLA 

Tesla will win the full self driving -regardless !! 

The safety data they have collected and published is the back bone of the company and the winning card, it’s something legacy Auto , competitors and haters don’t understand !! 

60k beta tester with zero accident !! nuff said !!

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:17:31 </td>
   <td style="text-align:left;"> $TSLA  $970 please daddy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:16:42 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:14:03 </td>
   <td style="text-align:left;"> $TSLA is bullish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:11:58 </td>
   <td style="text-align:left;"> $DWAC watch MILLIONS of Canadians move to red states in America - Watch Tens of thousands apply for &amp;quot;amnesty&amp;quot; from a repressive government. Watch hundreds of companies in Canada pick up and move to American soil. If this communist takeover of Canada doesn&amp;#39;t stop the MAGA movement will gain millions of badass canadian patriots, and fyi: they just directed all financial institutions to freeze your account if you support the truckers... $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:05:54 </td>
   <td style="text-align:left;"> $TSLA Phenomenal day bulls. Let&amp;#39;s keep climbing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:05:48 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #4 ticker with sweep activity where institutions are trading options urgently with 24.1K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:05:20 </td>
   <td style="text-align:left;"> $TSLA  Puts will be printing. Gap will be filled! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:02:59 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-15 Trade Analysis Video: 
https://www.youtube.com/watch?v=ugeR8k--eYg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:02:07 </td>
   <td style="text-align:left;"> $TSLA Stock futures inch lower after major averages snap 3-day losing streak https://cnb.cx/3LCaEsD  
 
 Biden addressed the latest developments between Russia and Ukraine Tuesday afternoon, reiterating that the U.S. will defend NATO territory. 
 
“If Russia proceeds, we will rally the world,” he said, adding that Washington’s allies were ready to impose powerful sanctions that will “undermine Russia’s ability to compete economically and strategically.” 
 
The comments came after the Russian government said earlier in the day that some troops who had been on the Ukrainian border had returned to their bases. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:01:20 </td>
   <td style="text-align:left;"> $AMD $spy  $btc.x   $aapl  $TSLA  
Impact of Fed rate changes on the S&amp;amp;P 500 
----------------------------------------- 
Impact of Fed interest rate changes on S&amp;amp;P 500 since 2017 
The chart below tracks the S&amp;amp;P 500, along with the dates that Fed rate cuts and hikes were announced over a three-year period. It’s apparent to see that trends are not always clear cut: following a quarter point rate hike in December 2017, the S&amp;amp;P 500 went on to defy expectations and climb almost 6% in January 2018. 
 
The chart also shows there can be significant shifts in stock prices around the time of Federal Open Market Committee announcements. Ahead of the rate cut in October 2019, there was a period of significant volatility; after it was announced, the S&amp;amp;P 500 closed at a record high. It’s important to monitor news, be aware of economic events that could affect stock prices and build these into the trading plan. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 08:00:37 </td>
   <td style="text-align:left;"> $tsla $ndx $amzn https://www.youtube.com/watch?v=CI93IWCx9XQ&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:57:46 </td>
   <td style="text-align:left;"> $TSLA 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:57:36 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:56:21 </td>
   <td style="text-align:left;"> $TSLA enormous amount of new Teslas in SoCal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:53:46 </td>
   <td style="text-align:left;"> $TSLA Bitcoin on its way to ATH . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:51:48 </td>
   <td style="text-align:left;"> $TSLA it hasn’t been months yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:50:07 </td>
   <td style="text-align:left;"> $TSLA $GGPI https://www.nytimes.com/2022/02/15/climate/california-waiver-emissions.amp.html?referringSource=articleShare </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:48:19 </td>
   <td style="text-align:left;"> $MR.X Off it goes. Do not miss the ruffyworld rocket. Meta Ruffy is the 2022 $TSLA , the 2022 metaverse version of $SHIB.X  on steroids and the real child of $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:48:13 </td>
   <td style="text-align:left;"> $TSLA all dips bought today closed at the high of the day… I’m smelling a big move these next 3 days
$1k+ in the cards for sure </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:47:12 </td>
   <td style="text-align:left;"> $UPST I see the sentiment going into the earning were &amp;quot;too&amp;quot; bearish. Some big bearish bets came in big sizes for weekly 104P and 120P. Ouch. This will now act like $TSLA and Musk. On a squeeze rampage imho. Give this 2-3 weeks and then this should be 159+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:45:41 </td>
   <td style="text-align:left;"> $TSLA Why pay $900 for Tesla today, when you will be able to get it for $50- $100 in less than 5 years? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:45:11 </td>
   <td style="text-align:left;"> $TSLA Biden says it remains possible that Russia will invade Ukraine, and that the U.S. has not yet verified Moscow’s claims that it has withdrawn some forces  
 
 
https://www.bloomberg.com/news/articles/2022-02-15/biden-says-ukraine-invasion-risk-remains-awaits-russia-pullback?sref=pHyhiApD via @bpolitics  
 
 
 Biden said it remains possible that Russia will invade Ukraine because its troops remain in a “threatening position,” and said that the U.S. has not verified Moscow’s claims that it has withdrawn some forces. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:44:09 </td>
   <td style="text-align:left;"> $SAVA $GME $AMC $TSLA who is going to trust a blockchain exchange with Citadel as a primary investor no thanks sure it will be leaking and backdoored like no tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:42:45 </td>
   <td style="text-align:left;"> $TSLA 

CNBC just aired a hit price anti Tesla FSD - similar to CR FSD bashing video !! 

This is misrepresentation and deceiving !! 

Hey Dave is covering it and he’s doing great job !

Again such hit piece  is always sponsored by Tesla Short Sellers &amp;amp; Legacy Autos  as their Anti FSD Anti Tesla program  intensifies as Tesla getting closer to solve Autonomy leaving every Legacy Auto in the dust ! 

🙏🏻🐉🦅

https://youtu.be/5q3YIJhuYvs

🙏🏻🐉🙏🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:42:35 </td>
   <td style="text-align:left;"> $TSLA retest 800 by eow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:42:16 </td>
   <td style="text-align:left;"> $QQQ $SPY $RBLX $TSLA $UPST can’t tell if this market is about to go dumb dumb or if it’s done done. What do you queef kings think? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:41:49 </td>
   <td style="text-align:left;"> $TSLA working its way into the top 20 most mentioned on twitch over the last 7 days

Via topstonks.com/stocks/TSLA?st_tsla

#tsla    #twitch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:41:16 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:39:19 </td>
   <td style="text-align:left;"> $AEI !!! Rockets or reverse split??? $SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:38:22 </td>
   <td style="text-align:left;"> $TSLA 1020 by EOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:37:13 </td>
   <td style="text-align:left;"> $TSLA Puts loaded. Expecting a test of Mondays low this or next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:33:56 </td>
   <td style="text-align:left;"> $TSLA 950 + looking very good EOW! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:31:37 </td>
   <td style="text-align:left;"> $TSLA reaching tipping Point here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:29:25 </td>
   <td style="text-align:left;"> $TSLA Bears are a little salty today, I&amp;#39;ll have to sprinkle some onto my chicken parm tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:29:04 </td>
   <td style="text-align:left;"> $TSLA this is coiled enough gonna break out. you can see this chart different ways triangle breakout is another way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:23:11 </td>
   <td style="text-align:left;"> $TSLA when is the war starting  lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:17:40 </td>
   <td style="text-align:left;"> $TSLA  holy crap.  Just checked my schwab account and found $5.7 billion in TSLA shares! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:12:22 </td>
   <td style="text-align:left;"> $SPY all bad news priced in. $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:11:19 </td>
   <td style="text-align:left;"> $TSLA $2000+ by the end of year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:09:07 </td>
   <td style="text-align:left;"> $TSLA it’s a no for $1000 this week with the fed meeting tomorrow. 🗑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:05:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL 

Listen, all I’m saying is that Elon wasn’t donating billions of dollars of stock when Tesla (and the market in general) was fairly valued 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:05:06 </td>
   <td style="text-align:left;"> $TSLA technical analysis for tomorrow. 
 
https://youtu.be/-I9bor-a_sE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:05:01 </td>
   <td style="text-align:left;"> $TSLA is Meet Kevin still trying to scare everyone into selling? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:04:44 </td>
   <td style="text-align:left;"> $TSLA all those gainz from today lost </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:04:24 </td>
   <td style="text-align:left;"> $TSLA back $850 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:04:00 </td>
   <td style="text-align:left;"> $TSLA above $1k or below $900 by Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:03:13 </td>
   <td style="text-align:left;"> $TSLA Musk donating to charity is not bullish or bearish for a stock wtf same as a stock split isn’t. Utters clowns </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:02:09 </td>
   <td style="text-align:left;"> $TSLA Elon gonna join truth social??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:02:00 </td>
   <td style="text-align:left;"> $TSLA 
Musk practicing altruism and I love to see it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:01:52 </td>
   <td style="text-align:left;"> $F  hi my name is trevor milton and I&amp;#39;m going to start a car company called Henry. $NKLA $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 07:01:14 </td>
   <td style="text-align:left;"> $DWAC watch $twtr do something stupid and ban Jr!!! hey Elon at $tsla you watching this???? https://twitter.com/DonaldJTrumpJr/status/1493713461452410885 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:59:48 </td>
   <td style="text-align:left;"> Ticker: $TSLA 
Buy: February 18, 2022 $925.00 Calls 
Entry Price: $17.00 - $17.25 
Exit Price: $19.04 
Stop Loss: $14.96 
Potential ROI: 12% 
Estimated Hold Time: 88 Minutes 
Alert Courtesy Of: https://www.fastscalp.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:57:19 </td>
   <td style="text-align:left;"> $TSLA 1k soon then $1500 then model s plaid in my driveway </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:56:41 </td>
   <td style="text-align:left;"> $SPY you heard the man, it’s time

$QQQ $DIA $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:55:42 </td>
   <td style="text-align:left;"> $TSLA dip in the morning, unload puts, load calls for the day? Prediction for tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:50:25 </td>
   <td style="text-align:left;"> $SPY $TSLA Great day today bulls let’s get them again tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:50:17 </td>
   <td style="text-align:left;"> $TSLA Thisll be in limbo but still my top choice for 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:47:10 </td>
   <td style="text-align:left;"> $TSLA EV stock boom round 2 coming! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:47:00 </td>
   <td style="text-align:left;"> $TSLA here you guys told ya again. AMC made 10% today. We ballin like Bill Hwang. https://youtu.be/TMO42qkPiio </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:45:31 </td>
   <td style="text-align:left;"> $TSLA $QQQ 36.2 Million dollars over 1K tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:44:29 </td>
   <td style="text-align:left;"> $NVDA Not adding shares above $200, not that bad of an investor $TSLA $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:41:21 </td>
   <td style="text-align:left;"> $ES $TSLA $NVDA  
 
Account Challenge Update:-  
Start Date: Jan 3, 2022  
Starting Balance: $1,700  
Current Balance: $84,969 
Goal: $100,000 by end of February.  
Strategy: Swing Trade Options, Stocks  
  
Watch out for next play👓 top.stocksboss.xyz/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:40:51 </td>
   <td style="text-align:left;"> $TSLA I wish it goes down to 860 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:40:44 </td>
   <td style="text-align:left;"> $TSLA WOW MAJOR TANKAGE.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:40:09 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:40:00 </td>
   <td style="text-align:left;"> Looking at the last year, $TSLA shows a very strong growth in Revenue. The Revenue has grown by 70.67%. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:37:38 </td>
   <td style="text-align:left;"> $TSLA could easily be wrong but bought puts at the end of the day. The run up on a speech that gave really no new info very suspect Imo. It was a good speech however. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:36:39 </td>
   <td style="text-align:left;"> $TSLA ‘Of course we don’t want war in Europe’ says Vladimir Putin.  https://youtu.be/iZlSeoI4HKE 
 
https://www.bbc.com/news/world-europe-60392259 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:35:48 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Bear at a Party </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:35:32 </td>
   <td style="text-align:left;"> $TSLA any think we can get passed 947 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:31:18 </td>
   <td style="text-align:left;"> $TSLA I have my position in TESLA since 2012. 
 
I&amp;#39;m tired of the bearish players who all these years have criticized it. BMW, Porsche, Mercedes will be able to make electric cars but they will not be able to replicate autonomous driving or performance in the short term. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:28:09 </td>
   <td style="text-align:left;"> $DWAC $tsla $twtr $mrna Me after seeing President Trump&amp;#39;s 1st &amp;quot;Truth&amp;quot; on twitter! how ironic https://twitter.com/LawhornJennifer/status/1493709232654458887/photo/1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:24:25 </td>
   <td style="text-align:left;"> $TSLA looks like I called calls correctly. This is so easy! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:24:20 </td>
   <td style="text-align:left;"> FED MEETING tomorrow 2pm and FOMC meeting March 16 !! 
Volatiles coming back  
 
$spy $upst $sofi $tsla $lcid </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:23:16 </td>
   <td style="text-align:left;"> $TSLA yay puts paying tomorrow.  Then buying calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:23:06 </td>
   <td style="text-align:left;"> $UPST lol bears and shorts tonight … those cockroaches going to feel the heat tomorrow when shorts squeeze begins.. not to forget 400 M buyback will have huge impact in stock price …. $250 … $RBLX $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:23:00 </td>
   <td style="text-align:left;"> $TSLA LFG Tank and Healer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:22:29 </td>
   <td style="text-align:left;"> $RBLX $GGPI $TSLA Ross Gerber on Roblox being the Future of the Metaverse, Digital Commerce, Gaming, Youth &amp;amp; More! 🤑✅

WATCH NOW: https://youtu.be/rZgeBAA2yCU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:22:21 </td>
   <td style="text-align:left;"> $TSLA https://m.youtube.com/watch?v=fucU0vARXa0 Your mommy burger </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:22:06 </td>
   <td style="text-align:left;"> $TSLA Does anyone know if you can import 1099 from robinhood into H&amp;amp;R Block? I don’t want to enter those manually. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:21:41 </td>
   <td style="text-align:left;"> $XELA is $TSLA 

Ok, XELANATION. You guys know I don’t spread bull crap rumors. But I remembered this quote and I thought it was interesting that PAR mentioned Tesla today in his tweet. 

I’m not suggesting anyone buy anything. I’m heavily invested here, but you do you. I was just like…. “One of the worlds largest tech companies” 🤷🏻‍♂️. 

Who the heck knows. 

I do know this. Time is a friend of the patient and an enemy of the hurried. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:18:18 </td>
   <td style="text-align:left;"> $TSLA $800-$400 range imminent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:17:24 </td>
   <td style="text-align:left;"> Tesla&amp;#39;s Elon Musk held 21.2% stake in TSLA as of the end of 2021, reveals SEC filing - TESLARATI $TSLA https://apple.news/A_qeEeXYAQ3ymqtLWROqSoA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:16:16 </td>
   <td style="text-align:left;"> I don’t know how these mother fuckers still have jobs. They are hedging or playing with clients’ money. They should be wise to stay away from the path of a rocket or get burned to oblivion  . $TSLA https://www.thestreet.com/investing/einhorn-bearish-tesla-put-options-position </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:15:16 </td>
   <td style="text-align:left;"> Electric Vehicle sales increased 109 percent in 2021, China and Europe set the pace - TESLARATI $TSLA https://apple.news/AVyPqFod6RW2ymKU2fp6PRw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:15:05 </td>
   <td style="text-align:left;"> $TSLA need this bitch to hit 1k by Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:12:31 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/tvfxP13_Avc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:11:42 </td>
   <td style="text-align:left;"> $TSLA https://www.youtube.com/watch?v=uzm7Oq63iG0 Wait not just cars, software and robot, next is Tesla V flying planes and helicopter. Trust in Elon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:08:59 </td>
   <td style="text-align:left;"> $TSLA what’s going to happen with the gap.  Futures gap has to fill at some time. Seemed to be up on air. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:08:28 </td>
   <td style="text-align:left;"> $TSLA An excellent example of the way he&amp;#39;s handled his position as potus... 
https://media2.giphy.com/media/Io4FqkTWHlAt091rye/giphy.gif 
..never get sick of posting this one, or seeing it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:07:05 </td>
   <td style="text-align:left;"> $TSLA $ES $QQQ  
 
 
Account Challenge Update:-     
Start Date: Jan 3, 2022     
Starting Balance: $1,700     
Current Balance: $84,969    
Goal: $100,000 by end of February.     
Strategy: Swing Trade Options, Stocks     
     
Watch out for next play👓 top.stocksboss.xyz/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:04:11 </td>
   <td style="text-align:left;"> $TSLA Gonna fall back a ways before it goes higher. Don’t get discouraged. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:02:25 </td>
   <td style="text-align:left;"> $TSLA Stock Just Popped Despite Hedge Fund Diss. Here&amp;#39;s Why. https://investorplace.com/2022/02/tsla-stock-just-popped-despite-hedge-fund-diss-heres-why/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:02:05 </td>
   <td style="text-align:left;"> $TSLA Will be irrelevant in 3 years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:01:53 </td>
   <td style="text-align:left;"> $TSLA $1000 soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:01:01 </td>
   <td style="text-align:left;"> $TSLA most likely gonna retest $900 short term but don’t get it twisted $1000 is coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:01:00 </td>
   <td style="text-align:left;"> $VIAC 
$36.20 short &amp;amp; I was laughed at told me to short $TSLA (lol) up today $46
Hmmn???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:00:32 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-15 Options Analysis Video: 
https://www.youtube.com/watch?v=Hee0o_KyBQ0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 06:00:18 </td>
   <td style="text-align:left;"> $TSLA hey wait a minute where did all the bears go I don’t remember blocking all of them😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:59:21 </td>
   <td style="text-align:left;"> $TSLA money gone call buyers from today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:59:08 </td>
   <td style="text-align:left;"> $TSLA everyone talks about Tesla being overvalued and yea it may be true Atleast for now but none of that matters when a company like Tesla is truly changing the way we live there hasn’t been a public company with such incredible innovation probably since Apple came out with the Mac or IPhone for the first time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:54:34 </td>
   <td style="text-align:left;"> $TSLA Muskonomy by Adam Jonas on CNBC - Tesla to grow as both  vertically and horizontally , as integrated with AI, Robotics, SpaceX, Starlinks satellites, Battery expansion   with Boring co transport - bears will find it difficult to comprehend the scale of progress to come </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:53:32 </td>
   <td style="text-align:left;"> $TSLA Now, are you all ready? 
Are y&amp;#39;all ready? 
Now TEsla gonna do it with the fever 
Yeah, Come on 
Ain&amp;#39;t no stoppin&amp;#39; Tesla now 
We&amp;#39;re on the move (yeah-ee-a, yeah-ee-a) 
Ain&amp;#39;t no stoppin&amp;#39; Tesla now 
We&amp;#39;ve got the groove </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:53:21 </td>
   <td style="text-align:left;"> $TSLA shorts and puts, you are.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:53:13 </td>
   <td style="text-align:left;"> $UPST OMG monster earning and now CEO decided to buyback shares worth of $400M.. $FB $TSLA $GME .. epic squeeze .. shorts will cover for days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:53:05 </td>
   <td style="text-align:left;"> $TSLA no one can see it yet but a Tesla will probably become an automation company automating everything from travel to energy to household tasks with AI controlled machinery lol everyone laughing at the Tesla bot until ten years from now we have iRobot like humanoids washing our dishes lol😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:51:12 </td>
   <td style="text-align:left;"> $JOBY nice flying electric taxis the future Tesla should invest $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:50:43 </td>
   <td style="text-align:left;"> $WALLSTBULLS.NFT Only the OG #wsb will get it 
$GME $TSLA $ETH.X #NFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:50:18 </td>
   <td style="text-align:left;"> $TSLA https://youth-investment-group.com/2022/02/15/tesla-revenues-to-exceed-gm-and-ford-combined-by-2027-according-to-wallstreet/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:49:11 </td>
   <td style="text-align:left;"> $TSLA can anyone explain ?   This was 833 yesterday premarket 
Now 921 on really no news.... thats tens of billions of dollar worth more now than yesterday,,,,,, why is this ????? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:48:47 </td>
   <td style="text-align:left;"> $TSLA 

$MS Adam Jonas :👇

We are NOT recommending $GM $F stocks in lights of MUSKONOMY !! 

The level of innovation and profit Tesla has achieved is incredible!! 
Wrapping up EV production is Capital intense and we are not sure any of legacy auto is capable of - it is risky !! 

#MUSKONOMY  
Tesla —Boring Company—SpaceX — Neuralink. All connected we believe 
~ Jonas 

🙏🏻🐉🦅
Blue Sky is in sight! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:48:00 </td>
   <td style="text-align:left;"> $TSLA Adam Jonas putting it down on Tesla tied to the Boring Company and SpaceX as well in the future!!!! If you are not LONG in Tesla... you&amp;#39;re last in the game!!!! REAL TALK!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:47:40 </td>
   <td style="text-align:left;"> $TSLA 

Boombox 😒 🙄 … Really elon you want to hear fart sounds while driving….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:47:20 </td>
   <td style="text-align:left;"> I’m sorry I mean 5 trillion + over time according to CNBC speaker $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:46:59 </td>
   <td style="text-align:left;"> $TSLA when you call this stock a POS...it&amp;#39;s an automatic block...your ignorance is just incomprehensible.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:46:13 </td>
   <td style="text-align:left;"> $TSLA what the hell is the Mobil metaverse.  You all smoking crazy crack </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:45:59 </td>
   <td style="text-align:left;"> Having said that, there are times when you SHOULD hold certain stocks for several years.  $TSLA, $AAPL, $NVDA, $FTNT are multi-year holds for me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:45:56 </td>
   <td style="text-align:left;"> $TSLA https://www.youtube.com/watch?v=arcx5Cca0jA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:45:37 </td>
   <td style="text-align:left;"> $UPST congratulations who own the JACKPOT 🎰 on call or long !!! 
See you $199 tomorrow morning
🥬🥬🥬🥬🥬🥬🥬💥💥💥💥💥
Congratulations my self to getting all money back since I lost last few months . 

 $FB $TSLA $RBLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:44:48 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:44:48 </td>
   <td style="text-align:left;"> Still my top performing stock in my portfolio $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:44:38 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $TSLA is the #5 stock that institutions are trading over rolling 5 day window with 119.6K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:44:01 </td>
   <td style="text-align:left;"> $TSLA    Just a matter of gravity.  ♨️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:43:29 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL got pump out of air rsi weak </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:43:21 </td>
   <td style="text-align:left;"> $TSLA just another normal day at the office then </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:42:10 </td>
   <td style="text-align:left;"> $UPST lol shorts are too dumb to cover now… they will be force to cover at $160 and boom … $200 then $300.. absolutely monster earning. .. $RBLX $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:42:08 </td>
   <td style="text-align:left;"> $GGPI I want $RIVN and $LCID  and $TSLA to do well!!! The better the valuation is for those companies, the more it makes logical sense that polestar will follow. EVEN IF this only matches $NIO valuation from this point forward, ITS STILL GOING TO 20. But that’s not going to happen, somewhere between lcid and rivian valuation puts this around 30-35 dollars. Get ready to really make some money. Institutions are LOADED and anyone with a brain will be buying in long term all the way from now until 20. After 20 it may get risky in the short term but 5 years out you will be wishing you bought more at 20 so don’t worry. HUGE OPPORTUNITY here with this stock. A PURE EV WINNER GLOABALLY. SETTING UP. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:41:49 </td>
   <td style="text-align:left;"> $TSLA Pretty identical huge buys at open and close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:41:23 </td>
   <td style="text-align:left;"> The Musk economy will continue to blossom over the decade ahead $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:41:05 </td>
   <td style="text-align:left;"> $TSLA Adam Jonas on CNBC . Very bullish on tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:40:16 </td>
   <td style="text-align:left;"> $TSLA did I miss something !? I had a dentist appointment so was out for the past few hrs. 
did Brandon talk today or was that just bears trying to trick us? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:39:01 </td>
   <td style="text-align:left;"> Biggest long term EV investment is $TSLA CNBC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:38:39 </td>
   <td style="text-align:left;"> $TSLA why POS up? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:38:20 </td>
   <td style="text-align:left;"> $TSLA $QQQ $SPY Where do you trade and why?  What features keep you at your broker?  Is there anything you would want changed?  I am trying to figure out where I should move my money for trading purposes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:38:00 </td>
   <td style="text-align:left;"> $LCID $RIVN $TSLA 

LOL CNBC IS ABOUT TO HAVE ADAM JONAS ON THAT DISGRACE OF AN ANALYST

LETS NEVER FORGET HE SAID TO SELL LUCID AT $16 STOCK WENT TO $60 IN A STRAIGHT LINE

HE SAID BUY RIVN IT IS “THE ONE” TO CHALLENGE TSLA THAT WAS AT $130 STOCKS AT $60 

SERIOUSLY WHAT A DISGRACE WHAT DOES IT TAKE TO GET FIRED IN THIS BRACKET MAKES ME WANNA SHORT MORGAN STANLEY FOR HIRING THIS CLOWN 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:37:22 </td>
   <td style="text-align:left;"> $AMZN $TSLA  Tomorrow and next week: 
FED: No rate hikes. 
Market and Pumpers: to da moon 
Inflation next month:10%. 
Fed: Lets do 1% emergency increase..
Pumpers: 1% better than 0. To da moon 🤣🤣🤣
Biden: You are not our enemy. But we will screw your economy with intervention in region and control your exports with sanctions. 
Putin: Fuck. I am bombing for fuck sake.
MSM/Pumpers: war is good. Patriotic. Buy buy. To da moon.  😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:36:59 </td>
   <td style="text-align:left;"> $TSLA where are bears? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:36:47 </td>
   <td style="text-align:left;"> $TSLA $1000 EOW. mark it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:36:30 </td>
   <td style="text-align:left;"> $TSLA Einhorn started a short position - I don&amp;#39;t think he learned his lesson yet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:36:20 </td>
   <td style="text-align:left;"> $TSLA so not even Brandon was able to fuck up the stock today ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:36:12 </td>
   <td style="text-align:left;"> $TSLA My boy Adam Jonas is about to come on CNBC. He is about to pump this to latexee62f14bc5c8673150d8d215b3e2868bDWAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:32:30 </td>
   <td style="text-align:left;"> latexc02244115dc0a1a0bb752dfb4b4d3773AMD 806k (72% call/27% put)
$TSLA 791k (57% call/43% put)

Lynk in bayo for option trading ideas and alert </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:29:39 </td>
   <td style="text-align:left;"> $TSLA squeeze potential in this is mega </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:29:08 </td>
   <td style="text-align:left;"> $AAPL $TSLA $AMZN CLOSE YOUR TD AMERITRADE NOW IF YOU LOVE FREEDOM!!! https://www.google.com/amp/s/www.foxbusiness.com/politics/canadian-freedom-convoy-td-bank-freezes-accounts-with-1-1m-for-trucker-protest.amp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:27:57 </td>
   <td style="text-align:left;"> $TSLA bought 100 shares at open. Sold 100 shares at close. Pocketed a cool 3k. Let&amp;#39;s see what happens tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:27:09 </td>
   <td style="text-align:left;"> $TSLA low volume melt up today. Should u-turn tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:26:46 </td>
   <td style="text-align:left;"> $RBLX made as much money as $TSLA back in the day !!!! And more much more users !!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:26:29 </td>
   <td style="text-align:left;"> $TSLA Almost fiddy  
Bears are luck out today 
maybe we will get it tomorrow yo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:26:00 </td>
   <td style="text-align:left;"> $TSLA who voted for this psycho? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:25:43 </td>
   <td style="text-align:left;"> $TSLA 
Market is on

https://giphy.com/gifs/tyrone-biggums-dave-chapelle-the-chappelle-show-sUFNBs65WVF6M

🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:24:39 </td>
   <td style="text-align:left;"> $TSLA @InsaneManiaCrazyShit $950 plus. If you are not ready for a return to new highs get out of the way. Shorting our Tesla will be another losing quest or amateur quack. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:24:10 </td>
   <td style="text-align:left;"> $TSLA $NVDA $FB $WTRH not too shabby today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:23:00 </td>
   <td style="text-align:left;"> $TSLA holding a put and will collect tomorrow morning dip then move back into call. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:22:08 </td>
   <td style="text-align:left;"> $TSLA it&amp;#39;s highly concerning that Tesla and the whole Nasdaq react so much on every negative or positive news from Ukraine 
I undestand the reasoning of this, but it seems overdone for me in both directions. 
What happens if overnight where will be another bad news from Ukraine? The odds are high.  
In a healthy market TSLA shouldn&amp;#39;t react on such news at all. Cuz Tesla won&amp;#39;t sell even a single car less or more because of whatever is happining in Ukraine. 
This  volatility is a bad sign, IMO. Somthing is not OK with the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:21:57 </td>
   <td style="text-align:left;"> $TSLA shit market this stock crashed with huge earning. $ABNB weak earning stock exploded!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:21:15 </td>
   <td style="text-align:left;"> $TSLA if everyone is saying $1k, buy puts 👍🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:20:39 </td>
   <td style="text-align:left;"> $XELA &amp;quot;43M+ $XELA shares borrowed by shorts; cost to borrow up 15x YTD (source: ORTEX). IMO huge risk to bet against the house with 90k+ shareholders. Reminds me of early days when shorts loved $TSLA for its debt etc.&amp;quot; Par Chadha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:19:24 </td>
   <td style="text-align:left;"> $TSLA No compromising, No conquering Mars... Polestar GGPI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:18:56 </td>
   <td style="text-align:left;"> $UPST these are truly monster numbers and monster beating on earning .. $200 is conservative… $500 in future soon .. $SOFI $AFRM $CAR $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:18:52 </td>
   <td style="text-align:left;"> $TSLA Assholes that kept shorting the stock finally got a dose of their own medicine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:17:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN $TSLA $AAPL  
 
&amp;quot;If you&amp;#39;re worried about a few stocks holding up the market, then you clearly don&amp;#39;t own those few stocks that are holding up the market.&amp;quot; 
 
There are things you can control and things you can&amp;#39;t! The solutions are easier than we think! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:14:41 </td>
   <td style="text-align:left;"> $TSLA world hunger will be ended </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:14:01 </td>
   <td style="text-align:left;"> $TSLA 4hr view from 2/01/2022 update. Showing reaction higher taking place from the blue box area #elliottwave #tading #tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:12:29 </td>
   <td style="text-align:left;"> $TSLA just sell off 40% for me will you? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:11:01 </td>
   <td style="text-align:left;"> $TSLA Just finished ABC correction. Likely to start heading back down tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:10:31 </td>
   <td style="text-align:left;"> $TSLA  good day latexfba3c3f2cbc11abc5752e0b5d057230cFB 
$AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:09:07 </td>
   <td style="text-align:left;"> $SPY thanks for the money bears. I’ll be taking it all year long $TSLA $PLTR $NIO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:08:34 </td>
   <td style="text-align:left;"> $TSLA bend over a bear day is over. enjoy the bear tears yall </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:08:33 </td>
   <td style="text-align:left;"> $TSLA what I have been noticing these past few weeks is the MMs appear to be keeping NQ futs within a certain range.  We close to the upper part of the channel with the 2.26% gain today.  Tomorrow, NQ futs should be down and this stock as well. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:08:24 </td>
   <td style="text-align:left;"> $TSLA Tesla&amp;#39;s main problem is that they&amp;#39;re misleading.  Tesla also understands that one voice will not help drive that. Intrun they cast it onto there &amp;quot;fans&amp;quot; and run with it like wild fire.  Unfortunately, the marriage of &amp;quot;have you been cheating on me?!&amp;quot; Is coming if this bs keeps happening. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:06:30 </td>
   <td style="text-align:left;"> $TSLA 4hr view from 1/09 weekend update. Can see another blue box area where buyers should be waiting to appear again #elliottwave #tading #tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:06:22 </td>
   <td style="text-align:left;"> $TSLA this is going to durn a lot of puts this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:06:14 </td>
   <td style="text-align:left;"> $TSLA ...now futures are beginning to tank.  Congrats bagholders for chasing the most overvalued stock on the market! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:06:12 </td>
   <td style="text-align:left;"> $DWAC so many memes so little time $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:05:50 </td>
   <td style="text-align:left;"> $TSLA $AAPL $MSFT beautiful day 😊🤙💰💰💰💰💰💰💰💰💰💰💰💰💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:05:10 </td>
   <td style="text-align:left;"> $TSLA .....prepare bears....makes it easier </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:04:59 </td>
   <td style="text-align:left;"> $TSLA Withdrawing my a**!!!

https://www.axios.com/ukraine-defense-ministry-banks-cyber-20122b9b-c576-4865-8aa9-78d1df0e56ac.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:04:11 </td>
   <td style="text-align:left;"> $TSLA ....better stretch tonite shorty...... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:03:58 </td>
   <td style="text-align:left;"> $TSLA $SPY is the only reason this thing survived today. Tmrw… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:03:34 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-15 Technical Analysis Video: 
https://www.youtube.com/watch?v=dw-_95ODzdY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:03:33 </td>
   <td style="text-align:left;"> $TSLA ok, now dip please </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:03:13 </td>
   <td style="text-align:left;"> $TSLA [Feb-18 920.00 Calls] Option volume Up +466.55 % |  Volume: 39,398 vs 6,954 https://www.sleekoptions.com/sleekscan.aspx?sub1=dscan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:03:13 </td>
   <td style="text-align:left;"> $TSLA no remorse for bears anymore. The real war is bulls VS bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:03:08 </td>
   <td style="text-align:left;"> $TSLA call printing just the beginning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:03:02 </td>
   <td style="text-align:left;"> $TSLA for the first time I bought some protective puts here.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:02:59 </td>
   <td style="text-align:left;"> $TSLA well today sucked for all the rational traders and investors out there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:02:57 </td>
   <td style="text-align:left;"> $TSLA Everything will be wonderful now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:02:45 </td>
   <td style="text-align:left;"> $TSLA Bears got smoked. Got tears of joy. Eat dirt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:02:44 </td>
   <td style="text-align:left;"> $TSLA .....green candles all week long </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:02:40 </td>
   <td style="text-align:left;"> $TSLA 🤣 super </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:02:04 </td>
   <td style="text-align:left;"> $TSLA added more puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:01:49 </td>
   <td style="text-align:left;"> $TSLA what a close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:01:32 </td>
   <td style="text-align:left;"> $DKNG $TSLA $BAC..nice day.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:01:31 </td>
   <td style="text-align:left;"> $TSLA Great Close! 
             That Genius that is Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:01:08 </td>
   <td style="text-align:left;"> $TSLA Hope you new traders have access to after hours trading, shit about to get wild. 

@CBSDavidMartin reporting US can see Russia units moving out of assembly areas toward the Ukraine border; it looks like Russian military uncoiling in preparation for an invasion </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:00:52 </td>
   <td style="text-align:left;"> $TSLA this is a no-brainer.  Puts at this price! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:00:45 </td>
   <td style="text-align:left;"> $TSLA Tesla Blue Box Area Provided The Minimum Reaction Higher https://elliottwave-forecast.com/stock-market/tesla-blue-box-provided-minimum-reaction/  #elliottwave #tading #tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:00:36 </td>
   <td style="text-align:left;"> $TSLA I’ve got a huge boner 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 05:00:19 </td>
   <td style="text-align:left;"> $TSLA squeeze start </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:59:38 </td>
   <td style="text-align:left;"> $TSLA Took some puts here. Not sustainable. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:59:33 </td>
   <td style="text-align:left;"> $TSLA hahahahaha fuck the shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:59:26 </td>
   <td style="text-align:left;"> $TSLA I&amp;#39;m part of a server where top traders actually get paid based on results (over $25k last month). All based on merit. That&amp;#39;s how you know you&amp;#39;re getting the best alerts... 
https://linktr.ee/Trading214 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:59:22 </td>
   <td style="text-align:left;"> $TSLA HOD at close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:59:19 </td>
   <td style="text-align:left;"> $TSLA Who noticed all superbowl add, everything electric vehicles. It helps Tesla in adopting electric vehicles. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:59:18 </td>
   <td style="text-align:left;"> $TSLA .....bear fuck time inbound.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:59:16 </td>
   <td style="text-align:left;"> $TSLA 5%?.. we made 10% with AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:58:56 </td>
   <td style="text-align:left;"> $TSLA What an epic bear trap today for the loser Tesla bears. Hope all your puts are worthless </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:58:45 </td>
   <td style="text-align:left;"> $TSLA solid  close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:58:05 </td>
   <td style="text-align:left;"> $TSLA it doesn&amp;#39;t add up but don&amp;#39;t fight it now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:58:02 </td>
   <td style="text-align:left;"> $TSLA yes it will </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:57:54 </td>
   <td style="text-align:left;"> $TSLA $SPX on green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:57:25 </td>
   <td style="text-align:left;"> $TSLA ......hodl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:57:11 </td>
   <td style="text-align:left;"> $TSLA adding more on the break, this might regain that 1000+ range </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:56:34 </td>
   <td style="text-align:left;"> $TSLA 

Sad day for Thugs Short HFs and MSM ! No war - not much US10Y - VIX down, Market in vivid green !! 

Hmmmm ?! 👀

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:56:30 </td>
   <td style="text-align:left;"> $TSLA 🆙️🆙️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:56:23 </td>
   <td style="text-align:left;"> $TSLA sold my 925 call dont wanna hold over night </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:55:53 </td>
   <td style="text-align:left;"> $TSLA Put positions closing here, I’m adding more tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:55:31 </td>
   <td style="text-align:left;"> $TSLA 

Its overpriced what???😆😆😆
Smoked ya!!!
My love forever &amp;amp; ever TESLA❤️❤️❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:55:27 </td>
   <td style="text-align:left;"> $TSLA close at HOD? 

what say u shorty? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:55:27 </td>
   <td style="text-align:left;"> $TSLA Putin is lying 🤥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:55:16 </td>
   <td style="text-align:left;"> $TSLA $SPY pushing hard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:55:07 </td>
   <td style="text-align:left;"> $TSLA  
That Channel though.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:54:53 </td>
   <td style="text-align:left;"> $TSLA a game of patience 💯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:54:52 </td>
   <td style="text-align:left;"> $TSLA Anyone wishing for war just to make a quick buck is a pussy and a coward. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:54:35 </td>
   <td style="text-align:left;"> $TSLA 950 tmr sounds about right </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:54:31 </td>
   <td style="text-align:left;"> $TSLA boom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:54:30 </td>
   <td style="text-align:left;"> $TSLA don’t worry guys I just sold my shares it should go up now 🤦‍♀️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:54:00 </td>
   <td style="text-align:left;"> $TSLA going higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:53:43 </td>
   <td style="text-align:left;"> $SPY $ARKK $TSLA so war is canceled? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:53:35 </td>
   <td style="text-align:left;"> $AMZN $TSLA JB. Thanks we are ATH on pretty much everything we see, eat , drink and buy. GOod JOB. 😂😂😂

https://www.cnbc.com/2022/02/15/soaring-lumber-price-adds-nearly-19000-to-the-cost-of-a-new-home.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:53:21 </td>
   <td style="text-align:left;"> Tesla $TSLA FSD Beta users show CNBC how the system works — and doesn’t 
Tesla will need LiDAR sensor $INVZ eventually  
 
https://www.cnbc.com/2022/02/15/tesla-fsd-beta-users-show-cnbc-how-the-system-works-and-doesnt.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:52:45 </td>
   <td style="text-align:left;"> $TSLA 8 minutes of panic covering starts now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:52:18 </td>
   <td style="text-align:left;"> $TSLA another 5% tmr should shake out the shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:52:15 </td>
   <td style="text-align:left;"> $TSLA Elon DaGod speaking on CNBC this Evening on the future of the company…..bears R fucked. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:51:59 </td>
   <td style="text-align:left;"> $TSLA Biden Says Will Not Sacrifice Basic Principles, Will Give Diplomacy Every Chance to Succeed http://www.streetinsider.com/Politics/Biden+Says+Will+Not+Sacrifice+Basic+Principles%2C+Will+Give+Diplomacy+Every+Chance+to+Succeed/19626972.html via @Street_Insider  
 
Biden Says U.S. Ready to Engage in Diplomacy with Russia,  
 
Russia Attack Still Very Much a Possibility </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:51:55 </td>
   <td style="text-align:left;"> $TSLA beautiful </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:51:46 </td>
   <td style="text-align:left;"> $TSLA whos buying calls for EOW 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:51:21 </td>
   <td style="text-align:left;"> $TSLA Pump pump pump pump!!!!

Dump dump dump tomorrow 😂👍🏻😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:51:20 </td>
   <td style="text-align:left;"> $TSLA What&amp;#39;s all this consolidation about? We goin&amp;#39; up or down? What we doin?!!!! LET&amp;#39;S GO!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:50:57 </td>
   <td style="text-align:left;"> $TSLA breakig 920 in 30 min </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:50:45 </td>
   <td style="text-align:left;"> $TSLA Is Musk on after the closing bell? I saw a blurb for Musk Economy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:50:38 </td>
   <td style="text-align:left;"> $TSLA big news it will shoot up!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:50:20 </td>
   <td style="text-align:left;"> $TSLA take today as proof to this being way oversold. Leaders are working in great lengths to avoid war </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:49:35 </td>
   <td style="text-align:left;"> $TSLA interesting movement today… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:48:45 </td>
   <td style="text-align:left;"> $TSLA  Elon Musk thinks full self Driving will be &amp;quot;the most important source of profitability for Tesla&amp;quot; well........ 

1. You have lied about it, actually working, and promoting a false narrative and getting people to sign up for something that is not actually well off, its worst. For the last 5 years...hmm...Yeah that makes sense. Sounds like Bernie Madoff.

2. Elon thinks. FULL self Driving is going to be the most profitable for Tesla then why hasn&amp;#39;t it been done. 

3. Elon - &amp;quot;We can to to Mars and it&amp;#39;s just SO exciting! Get ready!!&amp;quot; 

Tesla owner Reality -
&amp;quot;Hi, i know your pretty crazy but, my 200$ a month Full self driving is running red lights and I&amp;#39;m worried if you can&amp;#39;t figure this pretty important issue,  out, here, now, you will definitely not figure out the ladder. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:48:37 </td>
   <td style="text-align:left;"> TSLA UNUSUAL OPTION TRADE: $TSLA latex980bc90a7473a9eee8dc20cfcf54f606AMZN 
$AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:47:27 </td>
   <td style="text-align:left;"> $TSLA Brandon is done talking, time to go up 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:47:16 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:47:03 </td>
   <td style="text-align:left;"> $TSLA Gas relief from the government. Tesla is fucked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:46:41 </td>
   <td style="text-align:left;"> $TSLA  We didn’t tank….opening at $930 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:46:28 </td>
   <td style="text-align:left;"> $BX $TSLA Blackstone Invests $100 Million in Media-Tech Firm Cloudinary 

https://newsfilter.io/a/314a392c8a11d6aa51870d0f8a27b58c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:46:26 </td>
   <td style="text-align:left;"> $TSLA Good algos play at $915. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:45:57 </td>
   <td style="text-align:left;"> $TSLA beautiful day today lads! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:45:23 </td>
   <td style="text-align:left;"> $TSLA Einhorn is a loser </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:45:16 </td>
   <td style="text-align:left;"> $TSLA Let’s see if we can close at the High of the day!$925?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:44:29 </td>
   <td style="text-align:left;"> $AAPL $AMZN $TSLA $QQQ $SPY Market should be down 3-4% today with 9.1% inflation report. Rally based on lower risk of Russian attack but the real threat has not diminished at all.  Putin will lie to your face saying the sky is red while you both are looking up at a blue sky </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:44:17 </td>
   <td style="text-align:left;"> Top Bearish Flow Today : 

$TSLA $RIOT $NVDA $AMD $AAPL

🤖📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:44:02 </td>
   <td style="text-align:left;"> $TSLA Biden Says Will Not Sacrifice Basic Principles, Will Give Diplomacy Every Chance to Succeed http://www.streetinsider.com/Politics/Biden+Says+Will+Not+Sacrifice+Basic+Principles%2C+Will+Give+Diplomacy+Every+Chance+to+Succeed/19626972.html via @Street_Insider </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:43:51 </td>
   <td style="text-align:left;"> Top Bullish Flow Today : 

$NVDA $VIX $AMD $TSLA $AAPL 

🤖📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:43:30 </td>
   <td style="text-align:left;"> $TSLA been consolidating all damn day! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:43:26 </td>
   <td style="text-align:left;"> $TSLA is 150k russian troops on ukraine border  is more than 130k yesterday ? more than 100k 3 days ago?or no? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:43:07 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ 

IT’S TIME TO LIMIT THE F DOWN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:42:47 </td>
   <td style="text-align:left;"> $TSLA All right then! We got that out-of-the-way let the climb continue! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:41:26 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-16 04:41:25 </td>
   <td style="text-align:left;"> $TSLA  
Shame on the Bears wishing for war …. 
disgusting ! 
Serves them   right ! </td>
  </tr>
</tbody>
</table></div>

---
