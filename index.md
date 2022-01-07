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

[View the latest Economic Forecasts](/pdf/Monthly-Market-Outlook--Jan-2022-.pdf)

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



Last Updated: 2022-01-07 08:57:45 UTC +8

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
   <td style="text-align:left;"> 2022-01-07 08:13:19 </td>
   <td style="text-align:left;"> US Futures Edge Up Ahead of Key Jobs Report </td>
   <td style="text-align:left;"> US stock futures edged higher on Friday as investors awaited a key jobs report at the end of a volatile week. Dow futures inched up 0.2%, while S&amp;P 500 and Nasdaq 100 futures gained 0.3% and 0.4%, respectively. All three major averages declined in regular trading on Thursday, led by the Dow’s 0.47% fall, while S&amp;P lost 0.1% and Nasdaq shed 0.13%. Stocks have come under pressure following the release of the Federal Reserve’s December meeting minutes, which indicated that the central bank is ready to scale back economic stimulus at a faster rate than previously anticipated. The move sent the 10-year US Treasury yield above 1.7%, further pressuring growth-oriented areas of the market. Meanwhile, investors now zero in on the December jobs report, as strong employment numbers could provide additional support to the Fed’s hawkish stance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-07 08:11:00 </td>
   <td style="text-align:left;"> Japan 10Y Bond Yield Hits 39-week High </td>
   <td style="text-align:left;"> Japan 10 Year Government Bond Yield increased to a 39-week high of 0.122%, tracking a general rise in global bond yields after the latest FOMC minutes showed the Fed will likely increase interest rates sooner rather than later. In contrast, the Bank of Japan will reduce corporate debt purchases in March but it is in no rush to normalise monetary policy, in a divergent path with many other central banks that would likely scale back monetary stimulus soon. Meanwhile, the Japanese government lifted its growth forecasts for the economy in fiscal 2022 to 3.2% from 2.2%, while approving a record budget of JPY 107.6 trillion, aiming to boost growth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-59750333?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-07 08:02:11 </td>
   <td style="text-align:left;"> The woman working to get unwanted food to the hungry </td>
   <td style="text-align:left;"> "It was one of the most brutal feelings I've ever had," says Maria Rose Belding.                                                                                                                                                                                                                     , Maria Rose is talking about the moment that changed her life and kick-started a food venture now helping to curb food waste across the United States, that's inspired other people around the world.                                                                                                 , She was just 14 and volunteering at a local charity which gave food to hungry families in her home city of Pella in Iowa.                                                                                                                                                                            , "I was the youngest person there," she explains.                                                                                                                                                                                                                                                     , "I would go outside and throw things [food items] away that had expired, while there were people sitting in the parking lot, waiting to come get food. And they could see me throwing away food in front of them."                                                                                   , This sparked an idea. Working with friends and colleagues, they came up with the Means Database - a website to connect food businesses, like restaurants and caterers, with charities and non-profit organisations that distributed food to hungry people.                                           , When a restaurant had food that might go to waste it could quickly log this on the Means Database and the nearest non-profit that could use it would step in and claim it.                                                                                                                           , The restaurant would not have to pay waste or dumpster charges, the food would not go to waste and someone was fed.                                                                                                                                                                                  , The idea took off almost immediately.                                                                                                                                                                                                                                                                , "We started in two states [but] by the end of 2015 we had them in 26 [states]. We ran it out of my dorm. By the end of our first year, I believe we moved 25-30,000lb (11-13,000kg) of food," says Maria Rose, who is now chair of the Means Database board.                                         , In 2021 alone, the database doubled the amount of food it rescued each month.                                                                                                                                                                                                                        , It works with big corporations such as Starbucks coffee shops, as well as sole traders. In the state of Florida it works with 160 businesses.                                                                                                                                                        , The database now operates across 48 states in the United States, as well as Canada and there has been interest in Europe.                                                                                                                                                                            , It is hoped that successfully tackling food waste could represent a big step forwards in ending food poverty and hunger - in 2018 the Boston Consulting Group estimated that one third of the food produced in the world gets thrown away.                                                           , Maria Rose is one in a long line of people working hard to eradicate world hunger. Back in 1961, US President Dwight Eisenhower initiated the World Food Programme - the founding idea was to bring food from countries with excess supplies and redistribute it to those in need.                   , Nearly 60 years later, the World Food Programme (WFP), part of the United Nations, was awarded the Nobel Peace Prize.                                                                                                                                                                                , "When we hear about a crisis, it's like that same drive that an individual feels, but on steroids," explains Valerie Guarnieri, the assistant executive director of the WFP.                                                                                                                         , The World Food Programme does more than distribute food in places affected by war and famine, it also works to improve access to food in areas where there is no conflict.                                                                                                                           , Ms Guarnieri says the WFP helps support more than 40 nations around the world with school meals, pointing to evidence that by providing a nutritious meal "you can bring children to school," she explains.                                                                                          , One of the students who has directly benefited from this scheme is Peter Mumo, who remembers the day the trucks arrived at his school in rural Kenya.                                                                                                                                                , "My performance was dropping, but after the school meals I became a top student in my class," he says. "I maintained that for the rest of my schooling life because I never missed school. I was attentive in class because I really wanted to get this education and go all the way to university." , Mr Mumo eventually studied engineering at university and afterwards went on to work for a pesticide company in Nairobi. He started putting some of his salary away each month for an idea he had had for helping the community where he grew up.                                                     , His idea for a cold water pumping system to help farmers irrigate their fields was so promising he was awarded a Mandela Washington Fellowship which gave him the opportunity to pitch to potential investors.                                                                                       , Today his irrigation system is used by more than 400 farmers in the area he grew up and he has started another project to help those farmers store their food in communal fridges.                                                                                                                   , Maria Rose, Valerie and Peter spoke to the BBC for a programme on the BBC World Service called Generation Change about young people tackling big global issues. and the Nobel Laureates whose footsteps they are following in.                                                                       , "We know what it takes to solve the problem of food insecurity," says Ms Guarnieri from WFP.                                                                                                                                                                                                         , "It takes ensuring that all people have access to food, and part of that is about growing more food and growing it in a sustainable way. And part of it is about addressing the other barriers in the supply chain that stop all people from having access to nutritious food at all times.          , "We don't need new inventions, or new techniques to do it. We need policy change, we need financing and we need commitment to action. I think young people can really help drive that through."                                                                                                      , Maria Rose Belding is also realistic about the possibility of solving hunger. "Solve is an interesting term," she says.                                                                                                                                                                              , "If you want to solve hunger, you have to solve poverty, you have to solve substance use disorders, you have to solve educational failure, you have to solve armed conflict, you have to solve domestic violence - just to name five.                                                                , "I don't know that we will ever truly solve hunger. But we can make it an aberration. Instead of a rule."                                                                                                                                                                                            , Generation Change is a co-production by the BBC and Nobel Prize Outreach                                                                                                                                                                                                                             , Listen to Generation Change on The Documentary, BBC World Service.                                                                                                                                                                                                                                   , David Tennant stars as an unlikely globetrotter...                                                                                                                                                                                                                                                   , The Highland hermit who must choose between happiness and health...                                                                                                                                                                                                                                  , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-59900249?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-07 08:01:53 </td>
   <td style="text-align:left;"> Ladbrokes claimed £102m furlough despite online boost </td>
   <td style="text-align:left;"> Bookmaker Ladbrokes claimed £102m from the furlough scheme, despite rapid growth in online betting making up for all losses from the closure of stores.                                                                                                     , Accounts published on Thursday show that Ladbrokes claimed £57.5m in 2020, and the BBC understands it claimed a further £44m this year.                                                                                                                     , Since the pandemic began parent company Entain has actually increased revenues, driven by strong online growth.                                                                                                                                             , Entain said the money protected 14,000 jobs, and is “under review.”                                                                                                                                                                                         , The biggest claimers from the furlough scheme were mostly those for whom Covid lockdowns meant steep falls in revenue – airlines, pub companies, leisure groups, shops, restaurants and caterers.                                                           , One company stands out in the list – Ladbrokes, the UK’s largest operator of betting shops, with 2,845 premises branded Ladbrokes or Coral.                                                                                                                 , For though it had to close them for large parts of 2020 and 2021, it had a lifeline - online.                                                                                                                                                               , Its parent company, FTSE 100-listed gaming giant Entain, has a big online gambling business, and customers who couldn’t bet in shops during the dark days of lockdown flocked to websites and apps instead.                                                 , Last April’s Grand National broke the record for the biggest online sports betting event in the UK.                                                                                                                                                         , This meant that despite lockdowns, Entain’s 2020 revenues were unchanged from the year before at £3.6bn, and it even managed to record a profit of £114m. In the first nine months of 2021 revenues grew 8%.                                                , Entain is also well placed to benefit from the explosive growth of online betting in the US through its BetMGM joint venture.                                                                                                                               , Despite a strong financial performance, Ladbrokes made a large furlough claim.                                                                                                                                                                              , Accounts for Ladbrokes Gaming and Betting Ltd, a subsidiary company of Entain, filed with Companies House and published on Thursday show that it claimed £57.5m of furlough in 2020.                                                                        , The BBC understands the company claimed around £44m in 2021, taking the total to £102m.                                                                                                                                                                     , According to BBC analysis of data published by HMRC, that would be one of the 20 biggest furlough claims for 2021.                                                                                                                                          , A spokesperson for Entain said: “The furlough scheme was a sensible and highly welcome policy intervention that helped us, as one of the country’s largest retailers, to maintain the livelihoods of more than 14,000 retail colleagues on full pay.        , “Whilst the virus is still with us and the outlook, although improving, is still far from certain, the Board will continue to keep the situation under review.”                                                                                             , Entain is legally entitled to claim the money, and there is no suggestion that it did anything wrong in making the claim or retaining the money.                                                                                                            , However rival bookmaker William Hill opted to return £24.5m of furlough money in August 2020, citing the “strength of the post-lockdown recovery.”                                                                                                          , A number of companies in other industries opted to return furlough funds when the impact of the pandemic proved less severe than initially feared - including housebuilders Redrow, Barratt and Taylor Wimpey, Games Workshop, and distribution giant Bunzl., Flutter, owner of the Paddy Power betting shops, did not tap the furlough scheme at all.                                                                                                                                                                    , Betfred, which operates 1500 betting shops, also made substantial furlough claims despite rising profits.                                                                                                                                                   , It claimed £28.1m in furlough the year ending 27 Sep 2020, according to company accounts.                                                                                                                                                                   , In addition, a Betfred subsidiary company, Done Brothers (Cash Betting) Ltd, claimed somewhere between £18.5m and £37.5m from Dec 2020 to May 2021, according to HMRC data (which only gives a range, not a specific figure).                               , The total for the group adds up to between £46.6m and £65.6m, though these figures don't include any claims it may have made in October and November 2020.                                                                                                  , Betfred Group saw turnover fall from £621m to £525m in the year ending 27 September 2020, the latest figures available, as lockdowns forced its shops to close.                                                                                             , However the group still made substantial profits, up from £171m to £205m, lifted by some one-off gains including £98m resulting from a successful court case against HMRC for VAT paid on fixed-odds betting terminals from 2005 to 2013.                   , A Betfred spokesman said: “Thanks to the Government’s Job Retention [furlough] Scheme we have not had to make a single redundancy due to the pandemic and we will continue to invest in our shops on the high street.”                                      , David Tennant stars as an unlikely globetrotter...                                                                                                                                                                                                          , The Highland hermit who must choose between happiness and health...                                                                                                                                                                                         , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/es/2022/01/06/espanol/servicio-cliente-pandemia.html </td>
   <td style="text-align:left;"> 2022-01-07 08:00:09 </td>
   <td style="text-align:left;"> Un país entero exige hablar con el gerente - The New York Times </td>
   <td style="text-align:left;"> , En tiempos de enojo y frustración, las personas se comportan como niños haciendo pataletas cada vez que enfrentan pequeñas decepciones al comprar o viajar.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Shira InbarCredit...                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Por Sarah Lyall                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Cuando el cliente llegó, los nervios en la tienda de víveres ya estaban crispados, como suelen estar las cosas en estos tiempos que la pandemia avanza hacia su tercer año. Quería comprar cambozola, un tipo de queso azul. Había estado encerrado durante mucho tiempo. Buscó con detenimiento en el área de lácteos: no lo encontró. Hizo señales a una empleada que tampoco lo halló. Le pidió que revisara en la trastienda y que lo buscara en la computadora del negocio. No tuvo suerte.                                                                                                                                                                                                                , Entonces se desquició, era otro miembro del gran coro de la indignación de los consumidores estadounidenses fuera de control, muy al estilo de 2021.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , “¿Has visto a un hombre de 60 y tantos años hacer un gran berrinche porque no tenemos el queso importado y caro que quiere?”, preguntó la empleada, Anna Luna, quien describió el ambiente de la tienda, en Minnesota, como “molesto, confundido y temeroso”.                                                                                                                                                                                                                                                                                                                                                                                                                                                   , “Ves a la persona y piensas: ‘No creo que esto sea por el queso’”.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Es un momento incierto y extraño; en especial, con la variante ómicron que azota a Estados Unidos. La situación es mala. La pandemia se siente como una serie interminable de malas noticias. Las compañías siguen posponiendo la fecha de regreso a la oficina. Los Centros para el Control y la Prevención de Enfermedades (CDC, por su sigla en inglés) de Estados Unidos continúan modificando sus lineamientos. Los desacuerdos políticos se han convertido en odio político. Además, cuando las personas se encuentran en entornos de transacciones —tiendas, aviones, en las llamadas telefónicas a centros de servicios a clientes—, están, en palabras de Luna, “comportándose como cuando eran niños”., Tal vez lo has sentido: tus emociones entran en conflicto con tus principios. Un aumento de enojo cuando ingresas a tu farmacia local sufriendo síntomas que podrían ser de COVID-19 y descubres que los termómetros están agotados y también las pruebas de antígenos. Una ráfaga de molestia a causa de las reglas complicadas acerca de las tarjetas de vacunación y las identificaciones en los restaurantes —¡reglas con las que tú mismo estás de acuerdo!—, porque tienes que esperar afuera, hace frío y dejaste tu cartera en el auto.                                                                                                                                                                 , Una sensación de una furia casi homicida contra el representante de la compañía de la tarjeta de crédito que te acaba de informar que, por no haber contestado de manera correcta las preguntas de seguridad, no puedes hacer uso de tu cuenta. (Un recordatorio para mí misma: adoptar un tono de sarcasmo altanero no es una buena forma de resolver este problema).                                                                                                                                                                                                                                                                                                                                          , “Las personas son —odio decirlo, porque existen muchas personas agradables de verdad— pero cuando son groseras, son muchísimo más groseras”, mencionó Sue Miller, quien trabaja en una asociación de comercio sin fines de lucro en Madison, Wisconsin. “Es que en vez de responder: ‘Esto realmente me causa una molestia’, dicen: ‘¿Qué demonios te pasa?’. Es una grosería a otra escala”.                                                                                                                                                                                                                                                                                                                   , La saña del público ha obligado a muchas industrias orientadas al público a repensar lo que solía ser un artículo de fe: que el cliente siempre tiene la razón. Si los empleados ahora tienen que asumir muchos puestos inesperados —terapeuta, policía, negociador de resolución de conflictos—, entonces, los gerentes en el espacio de trabajo están actuando como guardias de seguridad y como porteros para proteger a sus empleados.                                                                                                                                                                                                                                                                      , En una tienda de alimentación especializada de Traverse City, Michigan, un gerente llamado Shea O’Brien fue acusado recientemente de no saber leer por un cliente enfadado porque un tipo de pescado que estaba anunciado en rebaja se había agotado. En otro caso, dijo O’Brien, un hombre que no quería llevar mascarilla agredió verbalmente a otra empleada, intercalando insultos personales con un improvisado soliloquio sobre la libertad y la tiranía hasta que la empleada empezó a llorar.                                                                                                                                                                                                           , “No paraba de gritar: ‘La gobernadora ha dicho que ya no tenemos que llevar cubrebocas’”, dijo O’Brien. La respuesta de la mujer —que seguían siendo obligatorias en lugares con un determinado número de trabajadores— no hizo sino enfurecerlo más.                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Finalmente, el propietario llegó y “le dijo al cliente que no volviera nunca más”, dijo O’Brien.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , No es tu imaginación: el comportamiento de las personas realmente ha empeorado. En un estudio realizado a mil adultos estadounidenses durante la pandemia, el 48 por ciento de los adultos y el 55 de los trabajadores dijeron que en noviembre de 2020 esperaban que el civismo en Estados Unidos mejoraría después de la elección.                                                                                                                                                                                                                                                                                                                                                                            , Para agosto, la expectativa de mejoría había caído al 30 por ciento en general y al 37 por ciento entre trabajadores. En general, solo el 39 por ciento de los participantes opinaron que creían que el tono de Estados Unidos era civilizado. El estudio también halló que las personas que no tenían que trabajar con clientes eran más felices que aquellos que sí lo hacían.                                                                                                                                                                                                                                                                                                                                , “Hay una creciente bifuración entre los oficinistas y aquellos que interactúan con consumidores”, señaló Micho Spring, la presidenta de práctica corporativa global para la compañía de comunicación estratégica Weber Shandwick, que ayudó a llevar a cabo el estudio.                                                                                                                                                                                                                                                                                                                                                                                                                                         , Al mismo tiempo, muchos consumidores se sienten justamente agraviados por lo que ellos consideran como un servicio deficiente en compañías que efectúan gran parte de sus negocios en línea —minoristas, operadores de televisión por cable, compañías de renta de autos y similares— y porque parecen casi interesados en evitar que los clientes hablen con personas reales.                                                                                                                                                                                                                                                                                                                                  , “La pandemia ha dado permiso a muchas empresas para reducir su enfoque en la calidad de la experiencia que brindan al clliente”, expresó Jon Picoult, el fundador de Watermark Consulting, una firma de consultoría sobre servicio al cliente.                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , En parte, el problema es la desconexión entre la expectativa y la realidad, indicó Melissa Swift, lideresa de transformación en Estados Unidos en la firma de consultoría Mercer. Antes de la pandemia, agregó, los consumidores habían sido seducidos a la idea de la “economía sin fricción” (la noción de que podías conseguir lo que desearas, en el momento en el que lo quisieras).                                                                                                                                                                                                                                                                                                                       , Eso no está pasando.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , “Existe una falta de formas de desahogo de la ira de la gente”, señaló Swift. “Ese mesero, ese sobrecargo; se vuelven sustitutos para cualquier cosa que se interpone entre lo que experimentamos y lo que pensamos que merecemos”.                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , ¿Cómo mides la furia? Durante muchos años, Scott M. Broetzmann, ahora presidente y director ejecutivo de una firma de consultoría llamada Customer Care Measurement and Consulting, ha llevado a cabo estudios sobre la furia de los consumidores. La siguiente versión se dará a conocer la siguiente primavera. Casi no puede creer lo que ha visto durante la pandemia.                                                                                                                                                                                                                                                                                                                                      , “Cuando fundamos el estudio, nunca pensamos que el ambiente sería como es en la actualidad”, afirmó. “Nunca me habría imaginado que veríamos a personas peleando en aviones y golpeándose entre sí”. Aseguró que la primavera pasada, su vuelo a primera hora de Washington a Phoenix se retrasó por 45 minutos debido a un conflicto relacionado con un hombre y un cubrebocas que se desarrollaba en la parte posterior. Al final, el hombre fue expulsado de la aeronave para su vergüenza.                                                                                                                                                                                                                  , Esto parece un juego de niños, comparado con lo que ocurre en los cielos. En la era covid, los aviones se han convertido en paisajes fértiles para peleas en torno a normas que en realidad son metáforas de otras cosas. Aquí es donde los mandatos de los cubrebocas se encuentran con los que nunca se ponen las mascarillas y donde los consumidores cansados y combativos se encuentran con los empleados agotados y hartos (y cada vez más sobrecargados de trabajo, porque mucha gente está enferma).                                                                                                                                                                                                    , En 2021, se registraron 5779 denuncias de pasajeros indisciplinados en los aviones, más de 4000 de ellas relacionadas con los mandatos de mascarilla, según informó la Administración Federal de Aviación. Las historias se suceden: de pasajeros que rompen los dientes a auxiliares de vuelo; de auxiliares de vuelo que someten a los pasajeros con cinta aislante; de personas que se pelean por las mascarillas, los cinturones de seguridad, las políticas de no servir alcohol, la falta de servicio de comida normal… lo que sea.                                                                                                                                                                       , Recientemente, una mujer en un vuelo de Delta de Tampa a Atlanta golpeó y escupió a otro pasajero en un incidente que comenzó cuando se negó a acceder al pedido de la auxiliar de vuelo de sentarse mientras el carrito de bebidas estaba en el pasillo. Cuando se invitó a la mujer a buscar un asiento libre durante unos minutos, ella preguntó: “¿Qué soy yo, Rosa Parks?”, según la consiguiente denuncia penal.                                                                                                                                                                                                                                                                                          , Los sobrecargos reportan que hacer cumplir las reglas —no solo de mascarillas, sino también las de cinturones de seguridad y mantenerse sentados durante el despegue y el aterrizaje— es quizá la parte más desgastante de su trabajo.                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , “Es mentalmente agotador tener que vigilar a adultos sobre este asunto”, comentó Adam Mosley, un sobrecargo de 51 años, en respuesta a una solicitud de The New York Times para describir las condiciones en la industria de los servicios en esta extraña coyuntura.                                                                                                                                                                                                                                                                                                                                                                                                                                           , “En definitiva, hay un subconjunto de personas que no parecen pensar que algunas de las reglas aplican para ellas”, opinó. Hace poco, una mujer furiosa lo confrontó a él y a otro sobrecargo en la cocina del avión, los arrinconó mientras argumentaba que tenía el derecho de hablar con sus hijos sin portar una mascarilla.                                                                                                                                                                                                                                                                                                                                                                                , No todo es horrible, dijo. Algunos pasajeros hacen grandes esfuerzos para agradecerle, al igual que algunos clientes han decidido dejar enormes propinas en los restaurantes. Otros han llevado regalos (por ejemplo, chocolates) para él y sus colegas.                                                                                                                                                                                                                                                                                                                                                                                                                                                        , “Pienso que había tanta atención de los medios sobre los pasajeros con mala conducta que algunas personas se sintieron mal”, indicó Mosley.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Los aviones son los lugares donde ocurren los ejemplos más obvios de furia de los consumidores, junto a los restaurantes, donde los clientes con frecuencia expresan sus molestias ante la falta de personal, los precios más elevados, los mandatos de vacunación y otros problemas generados por la pandemia. Sin embargo, la mayor parte del mal comportamiento de los consumidores es de baja importancia, casos persistentes de falta de civismo en vez de una explosión de violencia.                                                                                                                                                                                                                     , “Los clientes han estado superagresivos e impacientes en las últimas fechas”, afirmó Annabelle Cardona, quien trabaja en una división en Lowell, Massachusetts, de una cadena nacional de tiendas de artículos para hacer reparaciones en el hogar. Hace poco, discutió a gritos con un cliente que la llamó floja e incompetente después de que ella le dijo que él necesitaba medir sus ventanas antes de que ella le pudiera proporcionar el tamaño adecuado de persianas.                                                                                                                                                                                                                                   , Dichas interacciones solían hacerla llorar. “Pero me he hecho menos sensible a esos comentarios. Ahora, en vez de llorar, solo soy realmente pesimista y juzgo a la gente que me rodea”, aseveró.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , En todo el país, los trabajadores respondieron con historias similares: de clientes que se enfurecen cuando los productos que querían no están disponibles; de clientes que culpan a la tienda, en lugar de a las interrupciones de la cadena de suministro, por los retrasos; de clientes que exigen reembolsos por artículos no reembolsables; de clientes tan preocupados y ansiosos que la cosa más pequeña los hace caer en una espiral de histeria.                                                                                                                                                                                                                                                       , En Chicago, un empleado de atención al cliente de la marca Patagonia relató cómo una joven se puso inconsolable cuando le dijeron que su paquete llegaría tarde. Otro cliente lo acusó de mentir y de participar en una estafa para defraudar a los clientes al enterarse de que el chaleco polar que había pedido se retrasaría aún más por problemas de la cadena de suministro.                                                                                                                                                                                                                                                                                                                              , En Colorado, Maribeth Ashburn, que trabaja en una joyería, dijo que estaba cansada de ser “la policía de las mascarillas”.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , “Los clientes te gritan, te tiran cosas y se van de la tienda”, dijo.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Lo peor, dijo, son los comentarios políticos. En una ocasión, una clienta lanzó una diatriba contra el doctor Anthony Fauci, diciendo que sabía de buena fuente que estaba a punto de ser encarcelado por sus “crímenes”. Otros han llamado a Ashburn “oveja” y “gata cobarde” por llevar cubrebocas.                                                                                                                                                                                                                                                                                                                                                                                                           , Su respuesta favorita —verse evasiva y murmurar “hmm”— parece empeorar las cosas. “Estoy muy desanimada por la polarización y por la forma poco amable en que se trata la gente”, dijo.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Miller, de la asociación de comercio de Wisconsin, dijo que las presiones de la pandemia y el deterioro de la conducta de los funcionarios electos —los gritos, las amenazas, el odio— les habían dado permiso a las personas comunes de también hacer berrinches. Con sus clientes, ella intenta mantener la calma, abordar sus problemas y consolarse con cualquier migaja de civismo que brinden.                                                                                                                                                                                                                                                                                                            , “No espero que la gente sea amable. No tienen que desearme un buen día. Pueden decir: ‘Hola, me gustaría comprar esto’ y después ‘Gracias’ y ‘Adiós’. Estaría muy feliz con eso”, concluyó.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Sarah Lyall es una periodista que trabaja para diversas secciones como Deportes, Cultura, Medios e Internacional. Antes fue corresponsal en la oficina de Londres y reportera de las secciones de Cultura y Metro. @sarahlyall                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/household-spending </td>
   <td style="text-align:left;"> 2022-01-07 07:46:00 </td>
   <td style="text-align:left;"> Japan Personal Spending Unexpectedly Falls </td>
   <td style="text-align:left;"> Household spending in Japan unexpectedly declined 1.3% in real terms in in November 2021, after a 0.6% fall a month earlier and missing market forecasts of a 1.6% rise. This was the fourth straight month of drop in personal consumption, amid rising cases of the Omicron strain, with spending falling for food (-3% vs -0.9% in October), housing (-15.8% vs -12.3%), fuel, light &amp; water charges (-7.1% vs -7.3%), furniture (-0.3% vs -16.7%), education (-3% vs 17.1%), and culture &amp; rcreation (-3.7% vs -5.4%). In contrast, consumption grew for clothing (8.9% vs -9.1%), medical care (0.9% vs -5.4%), and transport (5.8% vs 10.9%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/sonos-stock-rallies-after-trade/story.aspx?guid={20C05575-04D4-B545-7844-4E650F0B445A}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-07 07:39:00 </td>
   <td style="text-align:left;"> Sonos stock rallies after trade court rules Google violated patents - MarketWatch </td>
   <td style="text-align:left;"> Sonos Inc. 
        SONO,
        -0.10%
       shares rallied in the extended session Thursday after the International Trade Commission ruled that certain audio players, controllers, and components that Alphabet Inc.’s 
        GOOG,
        -0.07%
       
        GOOGL,
        -0.02%
       Google sold in the U.S. violated as many as five of its patents. Sonos shares surged 6% after hours, following a 0.1% decline to close the regular session at $28.87. “The commission has determined that the appropriate remedies are a limited exclusion order and a cease-and-desist order against Google,” the ITC said in a statement. “The commission has also determined to set a bond in the amount of 100 percent of the entered value of the infringing products imported during the period of presidential review.” For their part, Alphabet shares were up 0.3% after hours, following a less than 0.1% decline in the regular session., Microsoft, Alphabet, Amazon, and others will continue to have significant influence on indexes. But look elsewhere for outsize tech returns, UBS says.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Wallace Witkowski came to MarketWatch from the Associated Press in New York, where he was a business reporter specializing in pharmaceutical companies. He previously reported for trade publications in covering the drug and medical-device industries back to 1998. Based in San Francisco, his focus is on U.S. equities. Follow Wally on Twitter at: @wmwitkowski. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/peru/interest-rate </td>
   <td style="text-align:left;"> 2022-01-07 07:30:00 </td>
   <td style="text-align:left;"> Peru Hikes Interest Rate for a 6th Straight Month </td>
   <td style="text-align:left;"> Peru’s central bank decided to raise the policy rate for a sixth straight month by 50bps to 3% on January 6, 2022, in line with market expectations as the country seeks to tame persistent inflation. Peru’s annual inflation accelerated to a 13-year high of 6.43% in December 2021, driven by food and energy prices. “With the information available, we consider it appropriate to continue with the normalization of monetary policy over the coming months,” the bank said in its statement. A robust economic rebound from the pandemic, which outpaced regional peers also aided the central bank’s decision. Policymakers said they are closely monitoring inflation expectations and the evolution of economic activity to decide the appropriate monetary stance, as the bank pushed back its guidance on when it expects inflation to fall back into its target of between 1% and 3% to the last quarter of 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/06/world/british-warship-collides-with-russian-submarine/index.html </td>
   <td style="text-align:left;"> 2022-01-07 07:25:07 </td>
   <td style="text-align:left;"> British warship hit by Russian submarine in rare event - CNN </td>
   <td style="text-align:left;"> (CNN)A Russian submarine being tracked by a British naval warship on patrol in the North Atlantic more than a year ago hit a sonar the ship was towing, according to the UK Ministry of Defence. ,  "In late 2020 a Russian submarine being tracked by HMS Northumberland came into contact with her towed array sonar," a UK Ministry of Defence spokesperson said in a statement Thursday.         , "The Royal Navy regularly tracks foreign ships and submarines in order to ensure the defence of the United Kingdom," the statement said.                                                          , A towed array sonar is a sensor spooled out by a ship when it is deployed.                                                                                                                        , According to the British Royal Navy, the HMS Northumberland carried out a "vital mission to protect UK waters and the nation's nuclear deterrent" in 2020.                                        , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/06/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-01-07 07:03:04 </td>
   <td style="text-align:left;"> Stock futures inch higher ahead of key jobs report </td>
   <td style="text-align:left;"> , U.S. stock index futures were little changed during overnight trading on Thursday, ahead of Friday's key jobs report.                                                                                                                                                                                                                                                          , Futures contracts tied to the Dow Jones Industrial Average gained 65 points. S&amp;P 500 futures advanced 0.2%, while Nasdaq 100 futures added 0.3%.                                                                                                                                                                                                                               , During regular trading the Dow fell 170 points, or 0.47%, while the S&amp;P declined 0.1%. Both are on track for their first negative week in three. The Nasdaq Composite slid 0.13% for its seventh negative session in the last eight.                                                                                                                                           , All eyes are on Friday's nonfarm payrolls report. Economists are expecting the economy to have added 422,000 jobs in December, according to estimates compiled by Dow Jones. The unemployment rate is expected to come in at 4.1%.                                                                                                                                             , "Homebase data points to surging payrolls in December, but December figures will not yet capture the impact of the surging Omicron variant on employment," noted Lauren Goodwin, economist and portfolio strategist at New York Life Investments.                                                                                                                              , U.S. weekly jobless claims totaled 207,000 for the week ended Jan. 1, the Labor Department said Thursday. The reading was higher than the expected 195,000. But the private sector added 807,000 jobs in December, ADP said Wednesday, which was significantly higher than the expected 375,000.                                                                               , Stocks' declines over the last two days follow the release of the minutes from the Federal Reserve's December meeting. The central bank is ready to dial back its economic help at a faster rate than some had anticipated.                                                                                                                                                    , "A shift in Fed policy often injects volatility into markets," said Keith Lerner, chief market strategist at Truist. "Stocks have generally had positive performance during periods where the Fed is raising short-term rates because this is normally paired with a healthy economy."                                                                                         , "The dip in stocks seems a bit overdone," added UBS Global Wealth Management in a note to clients. "The normalization of Fed policy shouldn't dent the outlook for corporate profit growth, which remains on solid footing due to strong consumer spending, rising wages, and still-easy access to capital."                                                                   , The yield on the 10-year U.S. Treasury hit 1.75% on Thursday, sharply higher than last week's 1.51% level. The move higher has hit growth-oriented areas of the market, since promised future profits start to look less compelling. The tech-heavy Nasdaq Composite is on track for its worst week since February 2021 as investors rotate out of growth and into value names., Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                         , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                         , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                               , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                               , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                             , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/06/stocks-making-the-biggest-moves-after-hours-gamestop-more.html </td>
   <td style="text-align:left;"> 2022-01-07 06:21:40 </td>
   <td style="text-align:left;"> Stocks making the biggest moves after hours: GameStop, Quidel &amp; T-Mobile </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                           , Check out the companies making headlines in after-hours trading:                                                                                                                                                                                                                                          , GameStop — Shares of the retailer jumped more than 28% in extended trading after the Wall Street Journal reported that GameStop will create a marketplace for NFTs. The company is also exploring cryptocurrency partnerships for games and items for the marketplace, the report said.                   , Quidel Corporation — Quidel shares gained more than 2% after the diagnostic healthcare product manufacturer released preliminary fourth-quarter results. The company is targeting a revenue range between $633 million and $637 million. Analysts surveyed by StreetAccount were expecting $465.7 million., T-Mobile — Shares of the communications company declined more than 1% during after-hours trading on Thursday after the company announced preliminary full-year results. T-Mobile said it added 1.2 million postpaid accounts and 5.5 million postpaid customers.                                          , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                    , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                    , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                          , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                          , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                        , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/t-mobile-stock-slips-following-quarterly/story.aspx?guid={20C05575-04D4-B545-7843-43E8E2080771}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-07 05:56:00 </td>
   <td style="text-align:left;"> T-Mobile stock slips following quarterly customer results - MarketWatch </td>
   <td style="text-align:left;"> T-Mobile Inc. 
        TMUS,
        +0.18%
       shares slipped in the extended session Thursday after the telecom company reported it posted record-high customer results for the quarter. T-Mobile shares declined 1.4% after hours, following a 0.2% rise to close at $115.57. The company said it added 844,000 net postpaid phone customers in the fourth quarter, compared with 824,000 in the year-ago quarter. Postpaid net customer additions grew to 1.75 million — the highest in company history, it said — from 1.62 million in the previous quarter. For the year, T-Mobile said it added 2.92 million net postpaid customers, compared with 2.22 million in the previous year. Total customers rose to 108.7 million from 102.1 million in the year-ago period. , The Federal Reserve is signaling it will raise rates more dramatically because of inflation concerns, which is pressuring stocks.  Friday, the spotlight will fall on the December jobs report.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Wallace Witkowski came to MarketWatch from the Associated Press in New York, where he was a business reporter specializing in pharmaceutical companies. He previously reported for trade publications in covering the drug and medical-device industries back to 1998. Based in San Francisco, his focus is on U.S. equities. Follow Wally on Twitter at: @wmwitkowski. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-01-07 05:28:00 </td>
   <td style="text-align:left;"> Brazilian Equities Recoup Some Losses </td>
   <td style="text-align:left;"> The Ibovespa stock index added 0.3% to close at 101,350 on Thursday, snapping a three-day losing streak, boosted by heavyweight miner Vale and steel companies amid rising iron ore prices. Meanwhile, investors continued to digest the prospect of a more hawkish Federal Reserve and uncertainty around the Covid-19 pandemic. Minutes from the latest FOMC meeting indicate that policymakers are ready to accelerate the cutback of stimulus in the economy while noting it could be appropriate to reduce the size of the Fed’s balance sheet after raising the federal funds rate. On the data front, industrial production in Brazil unexpectedly fell for a sixth consecutive month in November, highlighting persistent weakness in the sector and raising concerns over the health of Latin America's largest economy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-01-07 05:17:52 </td>
   <td style="text-align:left;"> Canadian Shares Rebound Slightly </td>
   <td style="text-align:left;"> The S&amp;P/TSX rose 0.2% to close at 21,072 on Thursday, rebounding from a 0.9% loss in the last session, as gains in the oil-backed stocks more offset losses in miners and tech stocks, as investors trade cautiously amid outlooks of tighter monetary policy by the Federal Reserve. Minutes from the latest FOMC meeting indicate that policymakers are ready to accelerate the cutback of stimulus in the economy while noting it could be appropriate to reduce the size of the Fed’s balance sheet after raising the federal funds rate. On the corporate front, energy shares jumped 3%, tracking higher oil prices, while the keystone pipeline resumed operations after it was shut down due to harsh winter weather. Financial stocks (08%) also booked gains. On the other hand, mining shares loss 2.7% from lower bullion prices, while technology shares extended yesterday’s losses to drop 1.2%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-07 05:07:00 </td>
   <td style="text-align:left;"> Wall Street Extends Losses On Thursday </td>
   <td style="text-align:left;"> US stocks extended losses from the previous session on Thursday with the Dow Jones erasing more than 150 points, and the S&amp;P 500 and the Nasdaq Composite closing 0.1% lower. Big tech stocks continued to decline as investors rotated out of high valuation names, with Tesla and Netflix falling more than 2% and Apple erasing more than 1%. Still, rate-sensitive stocks gained after Fed minutes showed the central bank is ready to remove its economic support and hike rates sooner than expected. Meanwhile, the claims report continued to point to a tight labor market and all eyes now turn to the payrolls data due tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-stocks-end-lower-thursday/story.aspx?guid={9B49740F-E0E5-4C34-B3F1-76457F811EED}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-07 05:04:50 </td>
   <td style="text-align:left;"> U.S. stocks end lower Thursday, with tech rout putting Nasdaq Composite on pace for a 3.6% weekly drop - MarketWatch </td>
   <td style="text-align:left;"> Stocks closed lower Thursday, putting the technology-heavy Nasdaq Composite Index on pace for a 3.6% weekly decline, as Treasury yields climbed and expectations for a more aggressive pace of normalization of monetary policy from the Federal Reserve weighed on Wall Street. The Dow Jones Industrial Average 
        DJIA,
        -0.47%
       ended lower for a second straight day, shedding about 170 points, or 0.5%, to finish near 36,236. The S&amp;P 500 index 
        SPX,
        -0.10%
       shed about 0.1%, while tech-led selling continuing. The Nasdaq Composite 
        COMP,
        -0.13%
       ended 0.1% lower, a day after booking its worst one-day percentage drop since Feb. 25. St. Louis Fed President James Bullard on Thursday said the Fed could start to raise its benchmark interest rate as soon as March. The yield on the 10-year Treasury note was at 1.733%, its highest yield since March 31, according to Dow Jones Market Data. , A rising-rate environment spells risk for overvalued stocks. Companies with high cash flows can give investors some protection.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Joy Wiltermuth is a news editor and senior markets reporter based in San Francisco. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/laptops-cracked-screens-help-explain-supply-chain-crisis </td>
   <td style="text-align:left;"> 2022-01-07 04:55:34 </td>
   <td style="text-align:left;"> Laptops, cracked screens help explain supply chain crisis </td>
   <td style="text-align:left;"> Fox News investigates how the U.S. wound up with long lines of cargo ships at ports.                                                                                                                                                                                                                                                                           , The cracks on the screens of Americans' personal computer devices may be an indicator of a much larger problem in the ongoing supply chain crisis.                                                                                                                                                                                                             , And the world of consumer electronics, specifically laptops, has not only been hit particularly hard during the pandemic, it's a perfect metaphor for the problems with modern-day supply chains, according to experts.                                                                                                                                        , "Most of my repairs, about 20-30% of my repairs are screens, which is LCD panels," says Arthur Zilberman, the owner of LaptopMD in New York City.                                                                                                                                                                                                              , SEMICONDUCTORS 101: COMPUTER CHIPS SHORTAGES LEAD TO NATIONAL SECURITY CONCERNS                                                                                                                                                                                                                                                                                , A sign is seen on the shelf at a CVS store in Queens, New York.  (Lindsey Nicholson/Universal Images Group via Getty Images / Getty Images)                                                                                                                                                                                                                    , Zilberman has been in business several decades, and says he's never had a problem finding replacement parts like he is today, specifically replacement screens for things like cellphones and laptops.                                                                                                                                                         , "When I used to buy one or two screens, now I have to buy six or seven," Zilberman told Fox's Investigative Unit. "High inventory means lower cash flow, the money that could go for advertising, the money that can go for the [employee] salaries, the money that can go for development... it's not a good situation for me as a business."                 , CHICKEN PRICES SOAR PROMPTING BUSINESS OWNERS TO USE 'WHOLE-BIRD' STRATEGY AMID SUPPLY CHAIN CRISIS                                                                                                                                                                                                                                                            , Just this week, one company in the business of LCD-panel technology announced it would be opening a domestic repair facility for its U.S. customers "to avoid ongoing challenges in the volatile international supply chain."                                                                                                                                  , When it comes to a device like a personal computer, the screen may be a very important part, but it is one of many. And that is perhaps what helps make the modern-day laptop the perfect metaphor for our current supply chain woes.                                                                                                                          , "The COVID pandemic was a wakeup call that not only tested our supply chains, but showed us that it is just not responsible to be overly dependent on China for stuff that is critical to our economic and national security."                                                                                                                                 , "Something as complex as a laptop, that could be thousands of parts, hundreds of companies involved in just the making of those parts," says Michael Farlekas, whose company e2Open, helps facilitate supply chain logistics for multi-billion dollar companies.                                                                                               , "People have an idea that products are made in a factory... they're not," Farlekas told Fox. "They're made actually in dozens of factories, and factories that are spread around the world. So in between the factories, you have shipment cycles, which means trucks have to be loaded and delivered, and unloaded and unpacked," Farlekas continued.         , He says this complex network of deliveries between supply chain "nodes" is partially what led to the backlogs of shipping containers at U.S. ports that dominated the pre-holiday new cycle. "If any one of those items is constrained, the whole process is constrained, and that's what we've seen over the past, you know, really 18 months," he explained. , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                    , According to Rep. Tom Malinowski, D-N.J., co-sponsor of the bipartisan Building Resilient Supply Chains Act, there are serious national security implications with respect to the United States’ supply chain issues.                                                                                                                                          , "The COVID pandemic was a wakeup call that not only tested our supply chains, but showed us that it is just not responsible to be overly dependent on China for stuff that is critical to our economic and national security," Rep. Malinowski told Fox.                                                                                                       , The supply chain of a laptop computer captures the complexities that created many of our modern day supply chain issues, according to experts. (Courtesy: e2Open)                                                                                                                                                                                              , "I do not want the United States to be at the mercy of an adversary like China because we're overly dependent on them for everything from, you know, PPE in a health crisis to semiconductors to the critical components of solar panels, which almost all come from China today," Rep. Malinowski added. "That's not good for our future."                    , That dependency is already resulting in some dire straits for small business owners like Zilberman, who is pleading with lawmakers for help. "Please work overtime, do what you need to do, but get this situation solved," Zilberman said, "because small people like me cannot hang on any longer."                                                          , Farlekas says there could be a silver lining for people like Zilberman and others, if they can hang on long enough. And as long as we learn the right lessons from our current situation.                                                                                                                                                                      , "I think in the next four to six months, you'll see [these issues] smooth out quite a bit," Farlekas told Fox. "My focus would be on how you make the system stronger, more resilient, more agile overall. I think that will be the greatest thing that can come out of what we've seen in the last 18 months," he added.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/06/the-fed-is-scaring-markets-with-the-triple-threat-of-policy-tightening.html </td>
   <td style="text-align:left;"> 2022-01-07 04:38:49 </td>
   <td style="text-align:left;"> The Federal Reserve is scaring markets with the triple threat of policy tightening </td>
   <td style="text-align:left;"> , Investors have been preparing for the Federal Reserve to start hiking interest rates. They also know the central bank is cutting the amount of bonds it buys each month. On top of that, they figured, eventually, the tapering would lead to a reduction in the nearly $9 trillion in assets the Fed is holding.                                                                                                                                                                                                         , What they didn't expect were all three things happening at the same time.                                                                                                                                                                                                                                                                                                                                                                                                                                                 , But minutes from the Fed's December meeting, released Wednesday, indicated that may well be the case.                                                                                                                                                                                                                                                                                                                                                                                                                     , The meeting summary showed members ready to not only start raising interest rates and tapering bond buying, but also being prepared to engage in a high-level conversations about reducing holdings of Treasurys and mortgage-backed securities.                                                                                                                                                                                                                                                                          , While the moves are designed to fight inflation and as the jobs market heals, the jolt of a Fed triple threat of tightening sent the market into a tailspin Wednesday. The result saw stocks give back their Santa Claus rally gains and then some as the prospect of a hawkish central bank cast a haze of uncertainty over the investing landscape.                                                                                                                                                                     , Markets were mixed Thursday as investors tried to figure out the central bank's intentions.                                                                                                                                                                                                                                                                                                                                                                                                                               , "The reason the market had a knee-jerk reaction yesterday was it sounds like the Fed is going to come fast and furious and take liquidity out of the market," said Lindsey Bell, chief market strategist at Ally Financial. "If they do it in a steady and gradual manner, the market can perform well in that environment. If they come fast and furious, then it's going to be a different story."                                                                                                                      , Fed officials said during the meeting that they remain data-dependent and will be sure to communicate their intentions clearly to the public.                                                                                                                                                                                                                                                                                                                                                                             , Still, the prospect of a much more aggressive Fed was cause for worry after nearly two years of the most accommodative monetary policy in U.S. history.                                                                                                                                                                                                                                                                                                                                                                   , Bell said investors are likely worrying too much about policy from officials who have been clear that they don't want to do anything to slow the recovery or to tank financial markets.                                                                                                                                                                                                                                                                                                                                   , "The Fed sounds like they're going to be a lot quicker in action," she said. "But the reality is we don't honestly know how they're going to move and when they're going to move. That's going to be determined over the next several months."                                                                                                                                                                                                                                                                            , Indeed, the market won't have to wait long to hear where the Fed is headed.                                                                                                                                                                                                                                                                                                                                                                                                                                               , Multiple Fed speakers already have weighed in over the past couple days, with Governor Christopher Waller and Minneapolis Fed President Neel Kashkari taking a more aggressive tone. Meanwhile, San Francisco Fed President Mary Daly said Thursday she thinks the start of balance sheet reduction isn't necessarily imminent.                                                                                                                                                                                           , Chairman Jerome Powell will speak next week during his confirmation hearing, and a second time this month following the Fed meeting on Jan. 25-26, when he may strike a more dovish tone, said Michael Yoshikami, founder and chairman of Destination Wealth Management.                                                                                                                                                                                                                                                  , One big factor Yoshikami sees is that while the Fed is determined to fight inflation, it also will have to deal with the negative impact of the omicron variant.                                                                                                                                                                                                                                                                                                                                                          , "I expect the Fed to come out and say everything is based on the pandemic blowing over. But if omicron really does continue to be a problem for the next 30 or 45 days, it is going to impact the economy and might cause us to delay raising rates," he said. "I expect that commentary to come out in the next 30 days."                                                                                                                                                                                                , Beyond that, there are some certainties about policy: The market knows, for instance, that the Fed starting in January will be buying just $60 billion of bonds each month — half the level it had been purchasing just a few months ago.                                                                                                                                                                                                                                                                                 , Fed officials in December also had penciled in three quarter-percentage-point rate hikes this year after previously indicating just one, and markets are pricing in close to a 50-50 chance of a fourth hike. Also, Powell had indicated that there was discussion about balance sheet reduction at the meeting, though he seemed to play down how deeply his colleagues delved into the topic.                                                                                                                           , So what the market doesn't know right now is how aggressive the Fed will be reducing its balance sheet. It's an important issue for investors as central bank liquidity has helped underpin markets during the Covid tumult.                                                                                                                                                                                                                                                                                              , During the last balance sheet unwind, from 2017 until 2019, the Fed allowed a capped level of proceeds from its bond portfolio to run off. The cap started at $10 billion each month, then increased by $10 billion quarterly until they reached $50 billion. By the time the Fed had to retreat, it had run off just $600 billion from what had been a $4.5 trillion balance sheet.                                                                                                                                      , With the balance sheet now approaching $9 trillion — $8.3 trillion of which is comprised of the Treasurys and mortgage-backed securities the Fed has been buying — the initial view from Wall Street is that the Fed could be more aggressive this time.                                                                                                                                                                                                                                                                  , Estimates bandied about following Wednesday's news ranged from maximum caps of $100 billion from JPMorgan Chase to $60 billion at Nomura. Fed officials have not specified any numbers yet, with Kashkari earlier this week only saying that he sees the end of the runoff still leaving the Fed with a large balance sheet, probably bigger than before Covid.                                                                                                                                                           , One other possibility is that the Fed could sell assets outright, said Michael Pearce, senior U.S. economist at Capital Economics.                                                                                                                                                                                                                                                                                                                                                                                        , There would be multiple reasons for the central bank to do so, particularly with long-dated interest rates so low, the Fed's bond profile being relatively long in duration and the sheer size of the balance sheet — almost twice what it was last time around.                                                                                                                                                                                                                                                          , "While longer term yields have rebounded in recent days, if they were to remain stubbornly low and the Fed is faced with a rapidly flattening yield curve, we think there would be a good case that the Fed should supplement its balance sheet runoff with outright sales of longer-dated Treasury securities and MBS," Pearce said in a note to clients.                                                                                                                                                                , That leaves investors with a multitude of possibilities that could make navigating the 2022 landscape difficult.                                                                                                                                                                                                                                                                                                                                                                                                          , In that last tightening cycle, the Fed waited from the first hike before it started cutting the balance sheet. This time, policymakers seem determined to get things moving more quickly.                                                                                                                                                                                                                                                                                                                                 , "Markets are concerned that we've never seen the Federal Reserve both lift interest rates off zero and reduce the size of its balance sheet at the same time. There was a two-year gap between those two events in the last cycle, so it is a valid concern. Our advice is to invest/trade very carefully the next few days," DataTrek co-founder Nick Colas said in his daily note Wednesday evening. "We're not predicting a meltdown, but we get why the market swooned [Wednesday]: these are truly uncharted waters.", Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                                                                          , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                                                                        , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/06/us/politics/congress-corporate-donations-2020-election-overturn.html </td>
   <td style="text-align:left;"> 2022-01-07 04:32:07 </td>
   <td style="text-align:left;"> Companies Donated Millions to Those Who Voted to Overturn Biden's Win - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , One year after the Capitol riot, many businesses resumed corporate donations to lawmakers who voted against certifying the 2020 election.                                                                                                                                                                                                                                                                                                                                                                          , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                                                     , By Alan Rappeport, Madeleine Ngo and Kate Kelly                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , WASHINGTON — At its annual summit on the state of American business last January, officials from the U.S. Chamber of Commerce expressed disgust at the siege of the Capitol that had unfolded days earlier, and declared that lawmakers who discredited the 2020 election would no longer receive the organization’s financial backing.                                                                                                                                                                            , “There are some members who, by their actions, will have forfeited the support of the U.S. Chamber of Commerce. Period. Full stop,” Neil Bradley, the executive vice president and chief policy officer for the chamber, said at the time.                                                                                                                                                                                                                                                                         , Less than two months later, the nation’s biggest lobbying group reversed course. “We do not believe it is appropriate to judge members of Congress solely based on their votes on the electoral certification,” Ashlee Rich Stephenson, the chamber’s senior political strategist, wrote in a memo.                                                                                                                                                                                                                , In the year since the riot at the Capitol, many corporate giants and trade groups have moved from making stern statements about the sanctity of democracy to reopening the financial spigot for lawmakers who undermined the election. Millions of dollars in donations continue to flow to what watchdog groups deride as the “Sedition Caucus,” highlighting how quickly political realities shift in Washington.                                                                                                , A report published this week by Citizens for Responsibility and Ethics in Washington, a nonprofit watchdog group, showed how corporate money continued to support most of the 147 lawmakers who voted to overturn the election results.                                                                                                                                                                                                                                                                            , In the last year, 717 companies and industry groups gave more than $18 million to 143 of those lawmakers. Businesses that pledged to stop or pause their donations to those lawmakers have since given nearly $2.4 million directly to their campaigns or leadership political action committees, according to CREW.                                                                                                                                                                                               , Many of the corporations that have donated are household names, including Boeing, Pfizer, General Motors, Ford Motor, AT&amp;T and UPS. Trade groups such as the Chamber of Commerce have also continued to be big donors, with such associations, or their political actions committees, giving $7.67 million to political groups associated with lawmakers who voted to overturn the election or to PACs that support them.                                                                                          , To be sure, many companies have kept their word and maintained their pause on donations. Jeffrey Sonnenfeld, a professor of leadership at the Yale School of Management, said his own research showed that a majority of corporations that pledged to slow or cease their PAC donations to election certification objectors had followed through with those promises.                                                                                                                                              , According to the CREW report, more than half of the nearly 250 companies that said they would evaluate their political giving after the attack have not made a donation to the lawmakers who tried to stop the certification of the election. Microsoft has held firm on its pledge to cease donations to those lawmakers, and Hewlett-Packard decided to shut down its PAC entirely after Jan. 6.                                                                                                                 , But many companies have restarted campaign donations, with some saying they are doing so in the spirit of nonpartisanship.                                                                                                                                                                                                                                                                                                                                                                                         , “Our employee PAC program continues to observe longstanding principles of nonpartisan political engagement in support of our business interests,” said Trent Perrotto, a spokesman for the defense contractor Lockheed Martin, which contributed $145,000 to 72 lawmakers who voted against certifying the election.                                                                                                                                                                                               , Sharon J. Castillo, a Pfizer spokeswoman, said in a statement that “following the events of Jan. 6, 2021, the company adhered to its commitment to pause political giving to the 147 members of Congress who voted against certifying the election for six months.” She added that “monitoring elected officials’ conduct and statements is a part of our governance process, and we will continue to do so as we consider future Pfizer PAC disbursements.”                                                       , CREW noted that some lawmakers who had downplayed the riot or sought to sow doubts about what happened on Jan. 6 had continued to be magnets for corporate money. Representative Madison Cawthorn, a North Carolina Republican who has blamed Democrats for instigating the violence and has called those taken into custody in connection with the riot “political hostages,” received $2,000 in donations from the National Association of Insurance &amp; Financial Advisors and the Farmers’ Rice Cooperative Fund., Representative Louie Gohmert, a Texas Republican who has said there is no evidence that an “armed insurrection” took place, received $1,000 from the National Association of Insurance &amp; Financial Advisors.                                                                                                                                                                                                                                                                                                       , In the immediate aftermath of the riot, associating with lawmakers who appeared to abet it was viewed by many companies as a political liability. But in many cases, those concerns did not last.                                                                                                                                                                                                                                                                                                                  , Charles Spies, a Republican campaign finance lawyer who helped run Mitt Romney’s presidential super PAC, said that while the initial shock of the attack made corporate donors risk-averse, their thinking shifted with the politicization of the Jan. 6 congressional inquiry. Republicans have sought to downplay the attack and have accused Democrats of using the investigation to hurt the G.O.P.’s image.                                                                                                   , “It’s now a bit more politicized, which makes it harder for companies to just pick one side,” Mr. Spies said.                                                                                                                                                                                                                                                                                                                                                                                                      , Melissa Miller, a Ford spokeswoman, justified the carmaker’s donations by explaining that they were not driven by a single issue.                                                                                                                                                                                                                                                                                                                                                                                  , The House investigation. A select committee is scrutinizing the causes of the Jan. 6 riot at the U.S. Capitol, which occurred as Congress met to formalize Joe Biden’s election victory amid various efforts to overturn the results. Here are some people being examined by the panel:                                                                                                                                                                                                                            , Donald Trump. The former president’s movement and communications on Jan. 6 appear to be a focus of the inquiry. But Mr. Trump has attempted to shield his records, invoking executive privilege. The dispute is making its way through the courts.                                                                                                                                                                                                                                                                 , Mark Meadows. Mr. Trump’s chief of staff, who initially provided the panel with a trove of documents that showed the extent of his role in the efforts to overturn the election, is now refusing to cooperate. The House voted to recommend holding Mr. Meadows in criminal contempt of Congress.                                                                                                                                                                                                                  , Scott Perry and Jim Jordan. The Republican representatives of Pennsylvania and Ohio are among a group of G.O.P. congressmen who were deeply involved in efforts to overturn the election. Mr. Perry has refused to meet with the panel.                                                                                                                                                                                                                                                                            , Phil Waldron. The retired Army colonel has been under scrutiny since a 38-page PowerPoint document he circulated on Capitol Hill was turned over to the panel by Mr. Meadows. The document contained extreme plans to overturn the election.                                                                                                                                                                                                                                                                       , Fox News anchors. ​​Laura Ingraham, Sean Hannity and Brian Kilmeade texted Mr. Meadows during the Jan. 6 riot urging him to persuade Mr. Trump to make an effort to stop it. The texts were part of the material that Mr. Meadows had turned over to the panel.                                                                                                                                                                                                                                                      , Steve Bannon. The former Trump aide has been charged with contempt of Congress for refusing to comply with a subpoena, claiming protection under executive privilege even though he was an outside adviser. His trial is scheduled for next summer.                                                                                                                                                                                                                                                                , Michael Flynn. Mr. Trump’s former national security adviser attended an Oval Office meeting on Dec. 18 in which participants discussed seizing voting machines and invoking certain national security emergency powers. Mr. Flynn has filed a lawsuit to block the panel’s subpoenas.                                                                                                                                                                                                                              , Jeffrey Clark. The little-known official repeatedly pushed his colleagues at the Justice Department to help Mr. Trump undo his loss. The panel has recommended that Mr. Clark be held in criminal contempt of Congress for refusing to cooperate.                                                                                                                                                                                                                                                                  , John Eastman. The lawyer has been the subject of intense scrutiny since writing a memo that laid out how Mr. Trump could stay in power. Mr. Eastman was present at a meeting of Trump allies at the Willard Hotel that has become a prime focus of the panel.                                                                                                                                                                                                                                                      , “Our employee PAC makes bipartisan contributions based on a variety of considerations important to customers, our team and our company. They span things like manufacturing, mobility, innovation and trade,” Ms. Miller said. “We resumed contributions in April after refining our process based on input from PAC members.”                                                                                                                                                                                     , After the riot, JPMorgan Chase, the country’s largest bank by assets, vowed not to use funds from its corporate PAC to support lawmakers who had objected on Jan. 6 to certifying the election results at least until the end of the current donation cycle. Still, it has given money to groups that support Republicans for both the Senate and the House, contributions that are likely to find their way to individual objectors.                                                                              , “A PAC is an important tool for JPMorgan Chase employees to engage in the political process in the United States,” the bank’s political action committee wrote in a note that was distributed to workers in June, when a temporary ban on all PAC contributions from JPMorgan employees was first lifted.                                                                                                                                                                                                          , Citigroup, which had also paused its PAC giving in the immediate aftermath of the riot, reopened the doors to PAC contributions to lawmakers around the same time, saying it would evaluate candidates to which it donated on a case-by-case basis rather than committing to any blanket prohibitions.                                                                                                                                                                                                             , Crisis communications experts said the resumption of donations was not surprising, particularly given President Biden’s weak poll numbers and the prospect that Republicans might retake control of Congress in 2022.                                                                                                                                                                                                                                                                                              , “Companies will need to do business with Republicans, period, so they’ll give them money,” said Eric Dezenhall, a Washington expert in corporate damage control. “Heavily regulated companies need to defend themselves from multiple threats -— hostile legislation, boycotts, shareholder actions.”                                                                                                                                                                                                              , The donations also reflect the fact that, over time, lawmakers are a more influential constituency for companies than consumers.                                                                                                                                                                                                                                                                                                                                                                                   , “Consumers have short memories, but lawmakers have long memories,” said Gene Grabowski, who specializes in crisis communications for the public relations firm Kglobal. “Doing business with the ‘Sedition Caucus,’ as distasteful as it might be, is a political reality for many companies.”                                                                                                                                                                                                                     , Although companies that have continued to halt donations to some Republicans could be burning bridges with those lawmakers, there is also an economic logic behind not donating to those who have demonstrated a willingness to undermine elections.                                                                                                                                                                                                                                                               , Bruce F. Freed, the president of the Center for Political Accountability, argued that firms that resumed the donations were being shortsighted and suggested that there was a strong business case that the health of America’s democracy should take precedence over political access.                                                                                                                                                                                                                            , “Companies need a healthy democracy to compete and grow and thrive,” Mr. Freed said. “They still look at political spending too narrowly as a matter of access. They're not looking at what the broader interests and broader risks are.”                                                                                                                                                                                                                                                                          , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/mark-cuban-backed-money-app-dave-now-trading </td>
   <td style="text-align:left;"> 2022-01-07 04:03:02 </td>
   <td style="text-align:left;"> Mark Cuban-backed money app ‘Dave’ now trading </td>
   <td style="text-align:left;"> Mark Cuban, the billionaire owner of the Dallas Mavericks, blasts Sen. Elizabeth Warren, D-Mass., for demonizing the wealthy.                                                                                                                                                                                                                                                                                                                                                   , The banking app "Dave," backed by Dallas Mavericks owner Mark Cuban, began trading on the Nasdaq on Thursday, after completing its announced merger with special purpose acquisition company VPC Impact Acquisition Holdings III, Inc.                                                                                                                                                                                                                                          , After the business combination was approved by VPCC's stockholders earlier this week, VPCC changed its name to "Dave Inc," and now trades under the symbol, DAVE.                                                                                                                                                                                                                                                                                                               , "We are thrilled to partner with VPCC and our new board of directors as we continue our mission to build products that level the financial playing field," Dave co-founder and CEO Jason Wilk said in a statement announcing the news. "This new influx of capital will allow us to invest in our business and in turn, help more people living paycheck to paycheck who traditional banking system has failed to support. We’re looking forward to hitting the ground running.", The deal included a private investment in public equity of $210 million led by Tiger Global Management with participation from Wellington Management, Corbin Capital Partners, and Alameda Research, Dave said in a press release.                                                                                                                                                                                                                                              , SHARK TANK - Mark Cuban is a "Shark" on ABC's "Shark Tank."  (Andrew Eccles/ABC via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                                                                , Ahead of its debut, Dave held an estimated value of around $4 billion. It opened at $8.27 per share on Thursday, placing its value at around $3 billion.                                                                                                                                                                                                                                                                                                                        , Dave was founded in 2017, and provides a financial platform offering a cheaper alternative to traditional banks that charges a fee of $1 per month to its 10 million customers. It provides checking account access with up to $100 in overdraft protection, and helps users build their credit, budget, and even find side gigs.                                                                                                                                               , BANKS ARE STARTING TO RECONSIDER OVERDRAFT FEES                                                                                                                                                                                                                                                                                                                                                                                                                                 , "We believe the legacy financial system has failed to deliver and today, more than 150 million people need our help to build financial stability," Wilk said in a statement announcing the firm's public offering plans in June.                                                                                                                                                                                                                                                , "Dave is upending the banking industry with our suite of breakthrough financial products and making a meaningful impact on our customers’ lives," he continued. "This transaction and continued support from our longstanding investors signify confidence in our strategy, vision and the significant growth opportunities ahead."                                                                                                                                             , NEW YORK, NEW YORK - Mark Cuban appears on "Cavuto: Coast To Coast" hosted by Neil Cavuto at Fox Business Network Studios on September 30, 2019. (Photo by Steven Ferdman/Getty Images / Getty Images)                                                                                                                                                                                                                                                                          , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                     , In addition to Cuban, Dave is backed by Norwest, Section 32, Capital One, The Kraft Group, SV Angel, and The Chernin Group. The company’s board of directors includes Wilk, Cuban, Metromile CEO Dan Preston, Google Ventures Founders Bill Maris, and Norwest Venture Partners' Parker Barrile.                                                                                                                                                                                , FOX Business' Lucas Manfredi contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/canadian-cannabis-company-canntrust-developing/story.aspx?guid={BEDD8906-153A-40F2-A758-6D9D597F36D6}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-07 03:45:58 </td>
   <td style="text-align:left;"> Canadian cannabis company CannTrust developing 'orderly wind-down plan' after debt default - MarketWatch </td>
   <td style="text-align:left;"> CannTrust Holdings Inc. said Thursday it's developing an "orderly wind-down plan" to maximize the value of its assets, because the company does not have sufficient liquidity to operate beyond the near term. The wind-down plan would be used if a financing or strategic transaction option cannot be finalized by the Canadian cannabis producer. The company said it has contributed $50 million to a trust to facilitate class action settlements in "full satisfaction of the actions against it." It also set aside a $2.7 million trust for settlement of claims under its fourth amended and restated plan of compromise, arrangement and reorganization dated July 7. The company said it's currently in default of its minimum Ebitda covenant under its financing plan. The company's current stay period ends on Jan. 31. CannTrust has also accepted the resignation of four board members including chairman Robert Marcovitch. The company remains in talks with potential investors and strategic partners. , The Federal Reserve is signaling it will raise rates more dramatically because of inflation concerns, which is pressuring stocks.  Friday, the spotlight will fall on the December jobs report.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Steve Gelsi covers banking and cannabis as a Senior Reporter for MarketWatch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/glaxosmithkline-vir-increases-supply-covid-19/story.aspx?guid={F59BD589-50B7-4EE8-B6DF-41E1CD61A5CC}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-07 03:38:53 </td>
   <td style="text-align:left;"> GlaxoSmithKline, Vir increases supply of COVID-19 antibody therapy to Canada to 20,000 doses - MarketWatch </td>
   <td style="text-align:left;"> GlaxoSmithKline PLC 
        GSK,
        -0.53%
       announced Thursday an agreement to supply the Government of Canada with 20,000 doses of Sotrovimab, the COVID-19 monoclonal antibody therapy the company developed with Vir Biotechnology Inc. 
        VIR,
        .
       The agreement follows Canada's initial order of 10,000 doses of Sotrovimab announced in October, which included options for additional purchases. Sotrovimab was authorized for injection by Health Canada in July 2021 to treat mild to moderate COVID-19 in adults and adolescents 12 years old and older who are at high risk for hospitalization and death. Glaxo's stock slipped 0.1% in afternoon trading and Vir shares eased 0.1%, while the S&amp;P 500 
        SPX,
        -0.10%
       gained 0.1%., The Centers for Disease Control and Prevention is maintaining its position on its new COVID-19 isolation policy, with a slight update amid backlash.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/ford-stocks-price-target-upped/story.aspx?guid={A4A48598-0CAF-4FEE-9458-065DCB8493BF}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-07 03:38:44 </td>
   <td style="text-align:left;"> Ford stock's price target upped to $29 at Argus - MarketWatch </td>
   <td style="text-align:left;"> Argus Research analyst Bill Selesky on Thursday raised his price target on Ford Motor Co. 
        F,
        +3.38%
       shares to $29, from $20, citing the auto maker's "strengthening balance sheet" and "clearly defined" financial targets. "We believe that supply-chain problems and semiconductor chip shortages will soon dissipate and provide greater opportunities for higher revenues and earnings performance" for Ford, Selesky said. The analyst kept his buy rating on the stock. Ford shares have gained more than 174% in the past 12 months, compared with gains of around 25% for the S&amp;P 500 index 
        SPX,
        -0.10%
       in the same period. Ford shares surged earlier this week as the company said it plans to double production of its electric F-150 Lightning pickup truck to meet "soaring customer demand." , This is the latest scientific wrinkle to complicate the constantly changing flowchart of our pandemic lives.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-59902078?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-07 03:11:38 </td>
   <td style="text-align:left;"> Investors threaten drug maker bonuses over vaccine access </td>
   <td style="text-align:left;"> A large coalition of investment firms want the bosses of coronavirus vaccine makers to have their bonuses withheld if they fail to improve product distribution.                                                                                                                                                                                                                           , This could guarantee a "more equitable" global circulation of the vaccine, said Rogier Krens chief investment officer of Achmea Investment Management.                                                                                                                                                                                                                                     , Drug makers said they are making sure lower income countries have access.                                                                                                                                                                                                                                                                                                                  , Over nine billion doses have been administered worldwide.                                                                                                                                                                                                                                                                                                                                  , Mr Krens said that the group of 65 companies, which collectively control almost $3.5tn (£2.59tn) in assets, believes that vaccines are "not distributed fairly at the moment".                                                                                                                                                                                                             , Overall, China and India have administered the highest number of doses, with nearly three billion and 1.5 billion respectively.                                                                                                                                                                                                                                                            , The US is third, with more than 500 million. Many poorer countries are relying on deliveries from Covax, a scheme led by Gavi, the Vaccine Alliance, together with the WHO and the Coalition for Epidemic Preparedness Innovations (CEPI), which is trying to ensure everyone in the world has access to a Covid vaccine. So far the scheme has distributed more than 900 million vaccines., "What we're asking the companies to do is to tie their remuneration policy and strategy to a more equitable distribution of the vaccine," Mr Krens explained.                                                                                                                                                                                                                              , If they don't commit to a fairer distribution, he said the groups first step will be to vote against any remuneration proposals that don't take this into consideration.                                                                                                                                                                                                                   , Asked if that means trying to withhold bonuses if the concerns aren't addressed, Mr Krens, replied "effectively yes".                                                                                                                                                                                                                                                                      , Figures collated by Our World in Data - a collaboration between Oxford University and an educational charity, show that many of the countries with the lowest vaccination rates are lower income African nations such as Burundi, DR Congo and Chad. Meanwhile, those at the top of the list are wealthier countries such as the UAE, Portugal and Brunei.                                 , Last week the head of the World Health Organisation reiterated the importance of vaccines in ending the pandemic. Dr Tedros Adhanom Ghebreyesu warned against "narrow nationalism and vaccine hoarding", and added that if "we end inequity, we end the pandemic".                                                                                                                         , A fairer distribution of vaccines makes sense from both a humanitarian and financial perspective, according to Mr Krens.                                                                                                                                                                                                                                                                   , "We definitely feel it's our responsibility to invest in companies that act in a socially responsible way," he said.                                                                                                                                                                                                                                                                       , When it comes to the money that the group manages for pension funds and other clients Mr Krens explained that a continuation of the pandemic as it's going now, would be a "threat" to the economy and eventually, a threat to their investment returns.                                                                                                                                   , The massive gap in vaccination rates between advanced economies and poorer nations could cost the global economy $5.3tn over five years according to the International Monetary Fund.                                                                                                                                                                                                      , The group of investors have voiced their concerns in a letter to the boards of Pfizer, Moderna, AstraZeneca and Johnson &amp; Johnson.                                                                                                                                                                                                                                                         , In their statement, they highlight the World Health Organisation's roadmap which calls for 70% of the population of every country to be vaccinated by the middle of this year.                                                                                                                                                                                                             , This video can not be played                                                                                                                                                                                                                                                                                                                                                               , The roadmap calls on vaccine manufacturers to be more transparent about production schedules and to prioritise contracts with Covax and Avat which aim to improve the distribution of vaccines in poorer countries.                                                                                                                                                                        , Vaccines makers said they are doing what they can to ensure that doses are spread out fairly.                                                                                                                                                                                                                                                                                              , AstraZeneca, which has worked with Oxford University on its vaccine, said it is "producing its COVID-19 vaccine for no profit to low income countries and has distributed most of its supply to low and middle income countries."                                                                                                                                                          , Johnson &amp; Johnson said that approximately 60% its COVID-19 vaccines have been shipped to low and middle income countries and that fair access to them has been "at the forefront" of its response to the pandemic. It added that its executive pay strategy "is designed to promote long-term, sustainable value creation".                                                                , Moderna and Pfizer haven't responded to requests for comment. However last year, in an open letter Pfizer's chief executive Albert Bourla wrote that the biggest restriction on expanding manufacturing was "scarcity of highly specialised raw materials".                                                                                                                                , International political efforts to improve vaccine production and distribution through a wavier of intellectual property rights have stalled. Hopes for an agreement at the World Trade Organisation were dented when it's in person Ministerial Conference was abruptly cancelled in late November.                                                                                       , Achmea's Rogier Krens believes that such a sharing of the vaccine manufacturing know-how has an important role to play in improving vaccine distribution.                                                                                                                                                                                                                                  , Although they have largely resisted so far he said: "We're actually calling actively for the pharmaceutical companies to contribute in that area".                                                                                                                                                                                                                                         , He argued that increasing vaccine supply is crucial to getting more people protected from coronavirus.                                                                                                                                                                                                                                                                                     , Mr Krens said that the coalition of investors can bring about change from the drug makers, even if it doesn't happen overnight, because it's size equates to "quite a strong voice".                                                                                                                                                                                                       , David Tennant stars as an unlikely globetrotter...                                                                                                                                                                                                                                                                                                                                         , The Highland hermit who must choose between happiness and health...                                                                                                                                                                                                                                                                                                                        , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/argentina/industrial-production </td>
   <td style="text-align:left;"> 2022-01-07 03:06:29 </td>
   <td style="text-align:left;"> Argentina Industrial Output Growth Rebounds from 8-Month Low </td>
   <td style="text-align:left;"> Industrial production in Argentina jumped 10.1 percent year-on-year in November of 2021, accelerating from an upwardly revised 4.4 percent increase in the previous month. Industrial growth was driven by textiles, leather, &amp; footwear (48.8 percent); oil refining, chemicals, rubber &amp; plastic products (10.7 percent); vehicles &amp; parts (26.3 percent); food &amp; beverages (7.3 percent). On a seasonally adjusted monthly basis, industrial production rebounded 4.8 percent, after an upwardly 5 percent drop in the previous period. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/06/business/new-york-times-the-athletic.html </td>
   <td style="text-align:left;"> 2022-01-07 02:58:40 </td>
   <td style="text-align:left;"> New York Times Co. to Buy The Athletic for $550 Million in Cash - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , The deal could help the media company reach its goal of 10 million subscriptions ahead of schedule.                                                                                                                                                                                                                                                                                                                                                                                                                         , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                                                              , By Lauren Hirsch, Kevin Draper and Katherine Rosman                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , The New York Times Company has reached an agreement to buy The Athletic, the online sports news outlet with 1.2 million subscriptions, in an all-cash deal valued at $550 million, The Times said on Thursday.                                                                                                                                                                                                                                                                                                              , The deal brings The Times, which has more than eight million total subscriptions, quickly closer to its goal of having 10 million subscriptions by 2025, while also offering its audience more in-depth coverage of the more than 200 professional teams in North America, Britain and Europe that are closely followed by The Athletic’s journalists.                                                                                                                                                                      , Meredith Kopit Levien, the chief executive of the Times Company, called The Athletic “a great complement to The Times.”                                                                                                                                                                                                                                                                                                                                                                                                     , “We are now in pursuit of a goal meaningfully larger than 10 million subscriptions and believe The Athletic will enable us to expand our addressable market of potential subscribers,” she said. Ms. Levien told analysts Thursday evening there was “relatively modest” overlap in subscribers of the two companies.                                                                                                                                                                                                       , Under Times ownership, The Athletic will be operated separately from The Times’s newsroom and its sports section, the company said. The publisher will be David Perpich, a longtime senior executive at The Times who has been a leader of its Cooking and Games apps, as well as the product recommendation site Wirecutter.                                                                                                                                                                                               , Alex Mather and Adam Hansmann, who started The Athletic in 2016, will stay on after the acquisition. Mr. Mather, currently the site’s chief executive, will become general manager and co-president; Mr. Hansmann, now The Athletic’s president, will be its chief operating officer and co-president.                                                                                                                                                                                                                      , “We started The Athletic to bring fans closer to the teams, players and leagues they love through deep, immersive journalism and storytelling,” Mr. Mather and Mr. Hansmann said in a statement on Thursday. “Today marks a thrilling milestone for that dream, one realized because of the hard work of every single one of our employees. We are proud to have The Athletic become part of the Times Company’s family of subscription products.”                                                                          , Mr. Mather and Mr. Hansmann, formerly colleagues at the fitness tracking app Strava, started The Athletic in the belief that die-hard fans were not finding the coverage they craved at a time when newspapers were in decline, Sports Illustrated was undergoing an ownership change and ESPN began laying off journalists.                                                                                                                                                                                                , They hired prominent sports journalists from across the country and expanded quickly, bringing coverage of games and the latest sports developments to readers who had grown accustomed to getting news online. The Athletic had a reporter covering nearly every major professional sports team in North America, as well as several top European soccer clubs, while also serving up magazine-length feature articles and podcasts.                                                                                       , The site has about 600 employees — roughly 400 in its newsroom, making it the second-largest employer of sports journalists in the country, behind the Disney-owned ESPN. Like a number of digital media companies that have found success in recent years, The Athletic relies on subscribers, rather than advertisers, as its main source of revenue.                                                                                                                                                                     , Recently, as its rapid subscription growth began to slow, The Athletic explored various options, including selling a minority or majority stake in the company, with private equity firms and corporations as potential buyers.                                                                                                                                                                                                                                                                                             , The Athletic brought in about $65 million in revenue last year, with operating losses of roughly $55 million, Ms. Levien told analysts Thursday.                                                                                                                                                                                                                                                                                                                                                                            , In an interview, Ms. Levien and Mr. Perpich said they expected that the The Athletic would become profitable.                                                                                                                                                                                                                                                                                                                                                                                                               , “The future growth of The Athletic and of the combined New York Times and The Athletic — and the broader bundle and portfolio of products — depends on things that we have literally spent the last half decade, maybe longer, learning how to do,” Ms. Levien said, citing The Times’s experience with marketing and advertising, among other things.                                                                                                                                                                      , When asked about potential layoffs at The Athletic, she said, “at this point, that’s not our plan.”                                                                                                                                                                                                                                                                                                                                                                                                                         , Last summer, there was speculation that gambling platforms like FanDuel and DraftKings might acquire The Athletic. Ms Levien said gambling could be a business opportunity for the company.                                                                                                                                                                                                                                                                                                                                 , “We did not buy The Athletic to build a giant betting platform, but I don’t rule out that there will be ways that we work with gambling companies over time,” she said.                                                                                                                                                                                                                                                                                                                                                     , The Times’s acquisition of The Athletic is expected to close by April 1. For The Times, the addition will bring an infusion of paying readers. Ms. Levien has consistently emphasized the importance of adding digital subscribers since taking charge of the business in 2020. At the end of the third quarter of 2021, the Times Company had reached 8.4 million total subscriptions.                                                                                                                                     , The Times’s growth in recent years has included other big-ticket acquisitions. In 2016, the Times Company bought The Wirecutter and its sibling site, The Sweethome, for more than $30 million. In 2020, The Times bought Serial Productions, the company behind the “Serial” podcast, for more than $25 million. The same year, it acquired Audm, an app that offers listeners articles read aloud. The Times had about $1 billion in cash on its books as of the third quarter of last year, according to company filings., “If we were to have tried to build something, it would have been The Athletic,” Mr. Perpich said. “And so when we saw it, we just said, ‘We should acquire it as opposed to trying to replicate what they’re doing.’”                                                                                                                                                                                                                                                                                                       , When Mr. Mather and Mr. Hansmann started The Athletic, they said much of the nation’s sports coverage was “empty calories” produced by slowly dying newspapers, adding that a media company focused on journalism for sports fans would be better for readers.                                                                                                                                                                                                                                                              , Early on, Mr. Mather boasted in an interview with The Times that The Athletic’s goal was to let local newspapers “continuously bleed until we are the last ones standing.”                                                                                                                                                                                                                                                                                                                                                  , Katie Robertson contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/unitedhealths-stock-selloff-chopping-about/story.aspx?guid={2E461077-89D0-4FE1-B33E-2AE272C9C6E3}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-07 02:47:49 </td>
   <td style="text-align:left;"> UnitedHealth's stock selloff chopping about 120 points off the Dow's price - MarketWatch </td>
   <td style="text-align:left;"> Shares of UnitedHealth Group Inc. 
        UNH,
        -4.09%
       dropped 3.7% in afternoon trading Thursday, enough to pace the Dow Jones Industrial Average's 
        DJIA,
        -0.47%
       components in declines. The $18.22 price decline in the health insurance company's stock was shaving about 120 points off the price of the Dow, which was dropping 144 points, or 0.4%. In comparison, the S&amp;P 500 
        SPX,
        -0.10%
       was up 0.1%. The selloff in UnitedHealth's stock comes after peer Humana Inc. 
        HUM,
        -19.37%
      slashed its estimate of 2022 Medicare Advantage membership growth, amid higher-than-expected terminations during the annual election period. Humana's stock plunged 19.7%., Here's what job-seekers should know.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/retail/bed-bath-beyond-shutting-stores-febuary </td>
   <td style="text-align:left;"> 2022-01-07 02:36:44 </td>
   <td style="text-align:left;"> Bed Bath &amp; Beyond shutting 37 more stores in February </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                   , Bed Bath &amp; Beyond, which faced significant losses due to global supply chain woes, plans to shutter more than 30 stores nationwide next month.                                                                                                      , The company confirmed to FOX Business that it will close 37 stores across 19 states. The closures, however, are part of previously announced plans to optimize store footprint and close approximately 200 stores, according to Bed Bath &amp; Beyond.  , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                             , "While the decision to close a store is always a difficult one, Bed Bath &amp; Beyond looks forward to serving customers at other stores," a Bed Bath &amp; Beyond spokesperson said in a statement.                                                        , People walk past a Bed Bath &amp;amp; Beyond store on October 01, 2021 in the Tribeca neighborhood in New York City. (Michael M. Santiago/Getty Images / Getty Images)                                                                                  , The company currently serves customers at its 809 brick-and-mortar stores in addition to its online store and mobile app.                                                                                                                           , However, the news comes after the company struggled to get products on shelves in recent months due to ongoing issues tied to backups in the supply chain.                                                                                          , Those constraints resulted in an estimated $100 million impact on the quarter and an even higher impact in December, said CEO Mark Tritton in a prepared statement.                                                                                 , Bed Bath &amp; Beyond lost $276.4 million, or $2.78 per share, for the three months ended Nov. 27.                                                                                                                                                      , The company last year lost $75 million in the quarter, or 61 cents per share.                                                                                                                                                                       , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                         , Revenue was $1.88 billion, down sharply from $2.62 billion and also short of the $1.96 billion that Wall Street was looking for.                                                                                                                    , Here is the list of locations slated to close by the end of February.                                                                                                                                                                               , The Associated Press contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/humana-stock-tumbles-pace-sp/story.aspx?guid={B365363B-587D-4AF4-A9A3-375874876E91}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-07 02:16:55 </td>
   <td style="text-align:left;"> Humana stock tumbles to pace S&amp;P 500 losers after slashing Medicare Advantage membership growth view - MarketWatch </td>
   <td style="text-align:left;"> Shares of Humana Inc. 
        HUM,
        -19.37%
       tumbled 13.0% toward a three-month low in afternoon trading Thursday, to pace the S&amp;P 500's 
        SPX,
        -0.10%
       decliners, after the health insurance services company slashed its full-year membership estimate for its Medicare Advantage products. Humana's stock was headed for the biggest one-day selloff since it slid 13.9% on March 16, 2020. Humana disclosed earlier Thursday that it now expects 2022 net membership growth for its individual Medicare Advantage products of 150,000 to 200,000 members, down from a previous estimate of 325,000 to 375,000 due primarily to "higher than anticipated terminations" during the annual election period, combined with expectations of higher than originally expected terminations for the rest of 2022. The company expects 2022 adjusted earnings per share of approximately $20.50, compared with the FactSet consensus of $20.53. Meanwhile, for the Humana Premier Rx Plan (PDP), the company now estimates a net membership decline of 125,000 members in 2022, compared with previous estimates of a loss of "a few hundred thousand members," citing better-than-expected sales of the Walmart Value plan and lower-than-anticipated terminations. Among other health insurers, shares of UnitedHealth Group Inc. 
        UNH,
        -4.09%
       dropped 1.9% and Anthem Inc. 
        ANTM,
        -4.10%
       slumped 1.6%., The Centers for Disease Control and Prevention is maintaining its position on its new COVID-19 isolation policy, with a slight update amid backlash.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/lumber </td>
   <td style="text-align:left;"> 2022-01-07 02:14:44 </td>
   <td style="text-align:left;"> Lumber Hovers at 6-Month High </td>
   <td style="text-align:left;"> Chicago lumber futures traded near to $1,200 per thousand board feet, the highest since the beginning of June 2021, amid supply disruptions and a hot housing market. From the demand side, construction companies are hoarding material to avoid shortages. Also, unseasonably warm temperatures are allowing homebuilders to keep their activity fueling the demand for lumber. Meanwhile, supply disruptions remain amid record rainfall in Canada during November and labor shortages in the US. In Canada, floods have affected the transportation system, delaying or making it impossible to ship lumber to the US. In the United States, sawmills faced a labor shortage as workers are unwilling to work in such dangerous conditions at low wages. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/media/miami-mayor-citys-embrace-of-cryptocurrency-not-a-failure </td>
   <td style="text-align:left;"> 2022-01-07 02:07:43 </td>
   <td style="text-align:left;"> Miami mayor: City’s embrace of crypto ‘not a failure’ </td>
   <td style="text-align:left;"> Miami Mayor Francis Suarez responds to a Bloomberg report suggesting plans to invest city funds in Bitcoin failed in front of city commission.                                                                                                                                                            , Miami Mayor Francis Suarez shut down false claims on "Varney &amp; Co." Thursday that the city’s adoption of cryptocurrency has already failed.                                                                                                                                                               , According to a recent Bloomberg report, Suarez’s proposal to invest city funds in Bitcoin "faltered" in front of the city commission.                                                                                                                                                                     , In response, Suarez explained that none of the city’s efforts have failed, including MiamiCoin’s generation of $26 million that will contribute to a Bitcoin yield for resident distribution.                                                                                                             , CRYPTO'S 2022 OUTLOOK AFTER BREAKTHROUGH 2021                                                                                                                                                                                                                                                             , The mayor detailed how the city has also already paid employees in Bitcoin, he pointed out, and is considering accepting crypto payment for taxes and fees.                                                                                                                                               , Mayor Francis Suarez discusses Miami's push to become the next tech hub on 'FOX Business Tonight.'                                                                                                                                                                                                        , "That doesn’t seem to be very accurate to me," he said. "We knew that investing in Bitcoin as part of our Treasury was something that would require changes in the law. Those changes haven’t happened… and they’re not city changes that have to happen. Those are state and federal potential changes." , "So until those changes happen, that’s not even possible," he said. "So it’s certainly not a failure."                                                                                                                                                                                                    , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                               , Miami's residents should be expecting payment in Bitcoin in the first quarter of 2022. Suarez explained that the dividend yield being distributed will be based on the city’s return on investment from MiamiCoin.                                                                                        , "That will be distributed to every single Miamian that is verified that gets a digital wallet," he said. "It will be government innovation actually yielding a benefit to our residents. It’s going to be something incredible."                                                                          , CLICK HERE TO READ MORE ON FOX BUSINESS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/zambia/composite-pmi </td>
   <td style="text-align:left;"> 2022-01-07 02:04:29 </td>
   <td style="text-align:left;"> Zambia Private Sector Expands for 4th Month </td>
   <td style="text-align:left;"> The Stanbic Bank Zambia PMI was down slightly to 51.5 in December of 2021 from 51.8 in November but continued to signal improvements in the health of the private sector in December, helped by a further acceleration in the pace of new order growth. New business rose by expanding employment and purchasing activity, while output ticked down. Suppliers’ delivery times lengthened for the fifth successive month, and at the same pace as in November as a result of disruption related to the COVID-19 pandemic. On the price front, purchase prices and staff costs increased at a softer pace. Meanwhile, companies declined their own selling prices for the fourth consecutive month to attract customers. Looking forward, optimism improved, with around 40% of respondents predicting a rise in activity and demand in 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/nigeria/composite-pmi </td>
   <td style="text-align:left;"> 2022-01-07 02:02:45 </td>
   <td style="text-align:left;"> Nigeria Private Sector Growth at 2-Year High </td>
   <td style="text-align:left;"> The Stanbic IBTC Bank Nigeria PMI rose to an over two-year high of 56.4 in December of 2021, up from 55 in the previous month amid stronger output and new order growth. Firm mentioned fruitful marketing efforts and a general improvement in domestic and international demand. Also, record inventory building was central to the improvement. Meanwhile, employment rose but at the softest pace for 11 month. On the price front, purchase costs rose at a survey-record rate for the fourth month running due to higher raw material prices, fuel costs and unfavorable exchange rates movements. Looking forward, firms were optimistic for output growth in 2022 amid plans to broaden product offerings, increase advertisements and expand operations to new locations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/federal-reserve-james-bullard-march-interest-rate-hike-inflation </td>
   <td style="text-align:left;"> 2022-01-07 01:38:02 </td>
   <td style="text-align:left;"> Fed's Bullard backs March interest rate hike, citing 'unanticipated' inflation shock </td>
   <td style="text-align:left;"> Independent Advisor Alliance CIO Chris Zaccarelli discusses his 2022 market outlook and sector picks.                                                                                                                                                                                                                                                                                                                                                                                        , St. Louis Federal Reserve President James Bullard said Thursday that he sees an initial interest rate increase happening as soon as March as the U.S. central bank seeks to quell the hottest inflation in nearly four decades.                                                                                                                                                                                                                                                              , Speaking during a meeting of the CFA Society St. Louis, Bullard – who is serving as a voting member of the Federal Open Market Committee this year – suggested that policymakers may immediately pivot to raising rates once the Fed concludes its massive bond-buying program in March.                                                                                                                                                                                                     , "The FOMC could begin increasing the policy rate as early as the March meeting in order to be in a better position to control inflation," Bullard said. "Subsequent rate increases during 2022 could be pulled forward or pushed back depending on inflation developments."                                                                                                                                                                                                                  , The Fed president said that policy has shifted from keeping the economy afloat during the pandemic to combating inflation.                                                                                                                                                                                                                                                                                                                                                                   , "There was a significant unanticipated inflation shock in the U.S. during 2021," he said. "With the real economy strong but inflation well above target, U.S. monetary policy has shifted to more directly combat inflation pressure."                                                                                                                                                                                                                                                       , FED DOUBLES TAPER RATE, EYES THREE INTEREST RATE HIKES IN 2022                                                                                                                                                                                                                                                                                                                                                                                                                               , His comments come one day after the Fed released unexpectedly hawkish minutes from its Dec. 14-15 policy-setting meeting, revealing that most officials agreed that surging inflation and a rapidly recovering labor market could warrant a faster-than-expected interest rate hike.                                                                                                                                                                                                         , WASHINGTON, April 29, 2020.A man wearing a mask walks past the U.S. Federal Reserve building in Washington D.C., the United States, on April 29, 2020. (Getty)                                                                                                                                                                                                                                                                                                                               , "Participants generally noted that, given their individual outlooks for the economy, the labor market and inflation, it may become warranted to increase the federal funds rate sooner or at a faster pace than participants had earlier anticipated," the minutes, released Wednesday, said. "Some participants also noted that it could be appropriate to begin to reduce the size of the Federal Reserve’s balance sheet relatively soon after beginning to raise the federal funds rate.", At the conclusion of their two-day meeting last month, policymakers announced they would double the tapering of a massive bond-buying program, putting the Fed on pace to end the program by March. In making the decision, they cited improvements in the labor market and the hottest inflation in nearly 40 years.                                                                                                                                                                        , Although officials held rates near zero during the meeting, they were unanimous in forecasting at least one rate hike next year. That marked a considerable shift from September, when half of the central bankers believed interest rate increases were not warranted until at least 2023.                                                                                                                                                                                                  , Officials now project rates to stand at 0.9% at the end of 2022, 1.6% at the end of 2023 and 2.1% at the end of 2024.                                                                                                                                                                                                                                                                                                                                                                        , James Bullard, president and chief executive officer at the Federal Reserve Bank of St. Louis, speaks during the National Association of Business Economics' (NABE) Economic Policy Conference in Washington, D.C., U.S. on Monday, Feb. 26, 2018. (Joshua Roberts/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                , Traders expect the Fed to begin raising rates in March, according to the CME's FedWatch tool, which could mean the balance reduction begins in early summer. Policymakers said the appropriate timing of reducing the balance sheet would likely be "closer to that of policy rate liftoff in the committee’s previous experience," the minutes said.                                                                                                                                        , Meeting minutes suggested that once the process begins, the runoff of the $8.8 trillion balance sheet could be "faster than it was during the previous normalization episode" in 2017. Some participants also "judged that a significant amount of balance sheet shrinkage could be appropriate over the normalization process."                                                                                                                                                             , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                      , For months, the Fed has been wrestling with its dual mandate of stable prices and full employment: The nation's jobless rate plunged to 4.2% in November, but there are still about 6.9 million out-of-work Americans. At the same time, consumer prices in November soared 6.8% from a year ago, the fastest pace since June 1982. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/stitch-fix-shares-soar-12/story.aspx?guid={6F3602B8-733C-4C1A-AC53-0022746C173F}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-07 01:31:13 </td>
   <td style="text-align:left;"> Stitch Fix shares soar 12% after share buyback program announced - MarketWatch </td>
   <td style="text-align:left;"> Stitch Fix Inc. 
        SFIX,
        +10.27%
       stock soared 12% in Thursday trading after the online personal styling service announced a $150 million share buyback program. "This share repurchase program reflects the confidence we have in our strategy, unique value proposition and the growth potential ahead for Stitch Fix, which we believe is not reflected in the current market valuation," said Chief Executive Elizabeth Spaulding in a statement. Stitch Fix shares plunged last month after its fiscal first-quarter earnings announcement. The stock was downgraded and its price target slashed at multiple research groups. Stitch Fix stock has plunged more than 67% over the last year while the benchmark S&amp;P 500 index 
        SPX,
        -0.10%
       has gained 25.6%., A family in Florida says it got a surprise post-Christmas delivery in the form of two packages left at its doorstep by a U.S. Postal Service carrier.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Tonya Garcia is a MarketWatch reporter covering retail and consumer-oriented companies. You can follow her on Twitter @tgarcianyc. She is based in New York. Tonya joined MarketWatch from Moguldom Media, where she was business editor for MadameNoire, a website targeting African-American women with a range of content from personal finance to economics, politics, education and lifestyle and entertainment.  She also worked at Mediabistro, and previously handled media relations for MSLGroup’s consumer practice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/colombia/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-07 01:19:45 </td>
   <td style="text-align:left;"> Colombia 10Y Bond Yield Hits 21-month High </td>
   <td style="text-align:left;"> Colombia 10 Year Government Bond Yeld increased to a 21-month high of 8.6% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/tin </td>
   <td style="text-align:left;"> 2022-01-07 01:15:00 </td>
   <td style="text-align:left;"> Tin Prices Steady Around $39,200 </td>
   <td style="text-align:left;"> Tin futures were trading steady around $39,200 a tonne at the beginning of January, not far from an all-time high of $39,960 hit on November 24th, amid low inventories and supply disruptions. The inventories in the LME-warehouses were at 2,045 tonnes, recovering from the lowest of 887 hit on November 2021, but still below of 2020 average of 5,000 tonnes. Also, measures to curb Covid's spread in Myanmar have caused shipment disruptions, restricting refined tin output in China. Meantime, the third-biggest refined tin producer, Malaysia Smelting Group, declared force majeure on deliveries in June, while Chinese tin smelters reduced the output after curbs on power consumption. Meanwhile, investors remained optimistic as studies showed that the Omicron variant is less severe than previous strains, albeit more infectious, gearing up them to bet that the economic recovery will not derail limiting the impacts over the demand for the metal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/kuwait/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-07 01:13:00 </td>
   <td style="text-align:left;"> Kuwait Inflation Rate Slows to 3.8% in October </td>
   <td style="text-align:left;"> The inflation rate in Kuwait slowed down to 3.8 percent in October of 2021, from a more than 5-year high of 4.1 hit in September. Prices slowed down for food &amp; non-alcoholic beverages (7.7 percent vs 8.2 percent in September); clothing &amp; footwear (5.4 percent vs 6 percent); furnishings (2.5 percent vs 2.8 percent) and recreation &amp; culture (3.7 percent vs 4.3 percent). On a monthly basis, consumer prices edged up 0.25 percent, below a 1.3 percent increase in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-01-07 01:09:00 </td>
   <td style="text-align:left;"> South African Stocks End Lower </td>
   <td style="text-align:left;"> The FTSE/JSE All Share Index fell 1.2% to close at 74,165 on Thursday, tracking global peers, after minutes from the US Federal Reserve’s December meeting indicated policymakers were ready to cut economic support faster than expected. Domestically, investors are increasing bets that the central bank will hike interest rates early this year. On the political front, South Africa is still grappling with the fallout of the Zondo report, which determined that there was a "capture of the state" for corruption during the presidency of Jacob Zuma, with the ruling ANC heavily criticized for failing to take action. Now, President Ramaphosa has until the end of June to tell parliament what he plans to do to fight corruption. On the corporate front, mining and tech stocks were among the worst performers, while banks, real estate and consumer goods firms stayed in positive territory. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-01-07 01:08:34 </td>
   <td style="text-align:left;"> London Stocks Slip From Near 2-Year High </td>
   <td style="text-align:left;"> The FTSE 100 dropped 0.9% to 7,450 on Thursday, after touching a near two-year high in the previous session and following a global selloff in equity markets, amid interest rate hike expectations and concerns over the impact of Omicron coronavirus on the economy. The US Federal Reserve meeting minutes showed that a "very tight" job market and elevated inflation might require the central bank to raise interest rates sooner than expected. On the corporate front, clothing retailer Next beat guidance for sale and raised its profit outlook. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/sugar </td>
   <td style="text-align:left;"> 2022-01-07 00:55:00 </td>
   <td style="text-align:left;"> Sugar Hits 22-week Low </td>
   <td style="text-align:left;"> Raw sugar futures on ICE fell to $18.2 on the first week of January, the lowest in 5 months, amid expectations of higher supply and eased demand. Widespread rains in the center-south region of Brazil pointed to a higher sugar production in 2022, rebounding from the previous year’s low yield due to extended droughts. Further, Thai and Indian harvests were reported to be in the upper range of expected amounts. Fresh data indicates that Indian sugar mills produced 11.56 tonnes of sugar in the first three months of the 2021/2022 marketing year, a 4.3% increase from the same period in the previous year. Meanwhile, commodity dealers cited that there are growing beliefs that the sugar market could be balanced this year, rather than the deficit experienced last year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-01-07 00:48:00 </td>
   <td style="text-align:left;"> Italian Shares Fall from 13-Year Highs </td>
   <td style="text-align:left;"> The FTSE MIB Index closed 1.8% lower at 27,656 on Thursday, falling from the 13-year high of 28,212 touched reached yesterday and tracking a European equity sell-off, as investors weighed on the minutes from yesterday’s FOMC meeting and new coronavirus related restrictions. Fed policymakers are ready to accelerate the cutback of stimulus in the economy, while noting it could be appropriate to reduce the size of the Fed’s balance sheet after raising the federal funds rate. On the pandemic front, the Italian government made the Covid vaccine mandatory for all individuals over 50 years old, in an attempt to alleviate pressure on hospitals after a record setting 219,441 coronavirus cases were diagnosed in the last 24 hours. On the corporate front, luxury goods shares took the biggest losses, led by Moncler (-4.1%) and Azimut (-3.1%). Meanwhile, highly volatile Iveco Group fell 6.8%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-01-07 00:47:48 </td>
   <td style="text-align:left;"> European Stocks Close in the Red </td>
   <td style="text-align:left;"> European stocks fell from records on Thursday, with Frankfurt's DAX 30 ending 1.4% lower at 16,045 and other major European bourses dropping between 0.1% and 1.8%, amid a global selloff in technology shares and bonds. Investors digested the minutes of the US Federal Reserve policy meeting, while remained concerned about a spike in coronavirus infections and rising inflation. Fed officials agreed that it might be needed to raise interest rates sooner than expected, as well as to reduce the central bank’s overall asset holdings, voicing concerns over persistent high inflation against a backdrop of an improving labor market outlook. Among single stocks, catering group Sodexo beat first-quarter revenue forecast as schools reopened. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-01-07 00:47:05 </td>
   <td style="text-align:left;"> The DAX Index fell 1.24% </td>
   <td style="text-align:left;"> Germany Stock Market dropped 202 points. Losses were led by Puma (-4.55%), Zalando (-4.28%) and Symrise (-3.85%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-01-07 00:46:00 </td>
   <td style="text-align:left;"> French Stocks Fall from Record </td>
   <td style="text-align:left;"> The CAC 40 Index fell 1.7% to close at 7,250 on Thursday, after reaching the record high of 7,385 on the previous session, amid the outlook of higher interest rates and a surge in coronavirus infections. Following yesterday’s session, the release of the FOMC meeting minutes indicated policymakers are ready to aggressively dial back stimulus and normalize monetary policy, maintaining the outlook for three rate hikes in 2022. On the pandemic front, French lawmakers approved a bill to transform the country’s health pass into a stricter “vaccine pass”, which now awaits for senate approval. On the corporate front, tech shares fell 3.1%, led by Capgemini (4.5%), and Dassault Systemes (-3.8%). Less optimistic expectations on the economy also hit luxury goods stocks, as seen in Hermes (-4.9%) and LVMH (-3.9%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-01-07 00:45:08 </td>
   <td style="text-align:left;"> The FTSE 100 Index dropped 0.90% </td>
   <td style="text-align:left;"> United Kingdom Stock Market fell 68 points. Leading the losses are Aveva Group (-5.41%), Experian (-4.82%) and Relx (-4.77%). Top gainers were Standard Chartered (3.56%), Natwest Group PLC (2.38%) and Royal Bank (2.36%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/trade-deficit-economy-china </td>
   <td style="text-align:left;"> 2022-01-07 00:36:28 </td>
   <td style="text-align:left;"> November trade deficit hits near record-high $80.2 billion </td>
   <td style="text-align:left;"> B. Riley Securities chief global strategist and managing director Mark Grant explains why investors should stay away from investing in Chinese stocks.                                                                                                                                                  , The U.S. trade deficit surged to a near-record high of $80.2 billion in November as exports slowed at the same time that imports jumped sharply.                                                                                                                                                        , The November deficit was 19.3% higher than the October deficit of $67.2 billion and was just below the all-time monthly record of $81.4 billion set in September, the Commerce Department reported Thursday.                                                                                            , FED EYES FASTER RATE CUTS DUE TO INFLATION                                                                                                                                                                                                                                                              , November imports, goods Americans bought from other countries, jumped 4.% to $304.4 billion in November while exports, those the U.S. sends overseas, edged up a scant 0.2% to $224.2 billion.                                                                                                          , Through the first 11 months of 2021, the U.S. trade deficit is 28.6% higher than during the same period last year with the economic recovery in the United States outpacing other nations, as is the readiness of Americans to spend.                                                                   , JOBLESS CLAIMS TICK HIGHER                                                                                                                                                                                                                                                                              , For all of 2020, the U.S. trade deficit stood at $676.7 billion, a slight 0.1% above the 2019 figure.                                                                                                                                                                                                   , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                 , The politically sensitive deficit with China in goods rose 2.9% to $32.3 billion in November and is up 12.8% for the first 11 months of this year compared to the same period in 2020                                                                                                                   , The United States and China, the world's two largest economies, engaged in a contentious trade battle under former President Donald Trump, who accused China of unfair trade practices that had cost millions of American jobs. Each country imposed tit-for-tat punitive tariffs on its economic rival., So far, the Biden administration has taken a more cautious approach in its economic dealings with China.                                                                                                                                                                                                , Michael Pierce, senior U.S. economist at Capital Economics, said that the sharp jump in November's trade deficit means that trade will be a small drag on the overall U.S. economy in the October-December quarter.                                                                                     , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                             , Pierce forecast growth, as measured by the gross domestic product, would be around 4.5% in the fourth quarter, an improvement from the modest 2.3% in the third quarter but below expectations for much stronger growth before the omicron variant hit.                                                 , Other economists are more optimistic, predicting growth will come in between 6% and 7% in the October-December period. The government will release its first look at fourth quarter GDP on Jan. 27. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/tunisia/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-07 00:34:16 </td>
   <td style="text-align:left;"> Tunisia November Inflation Rate at Over 2-Year High </td>
   <td style="text-align:left;"> The annual inflation rate in Tunisia rose to 6.6 percent in December of 2021 from 6.4 percent in the previous month. It was the highest inflation rate since September of 2019. Main upward pressure came from prices of food &amp; non-alcoholic beverages (7.6 percent vs 6.9 percent in November), alcoholic beverages &amp; tobacco (18.4 percent vs 18.1 percent), housing &amp; utilities (5.1 percent vs 5 percent), furnishings (5.2 percent vs 4.8 percent), education (9.1 percent, the same as November), and clothing &amp; footwear (8.7 percent vs 8.8 percent). On a monthly basis, consumer prices were up 0.5 percent, after a 0.1 percent uptick in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/media/republicans-challenge-scranton-joe-poor-economic-record-2022-midterms </td>
   <td style="text-align:left;"> 2022-01-07 00:16:41 </td>
   <td style="text-align:left;"> Republicans look to challenge ‘Scranton Joe’ Biden on poor economic record in 2022 midterms </td>
   <td style="text-align:left;"> FOX Business’ Connell McShane visits President Biden’s hometown of Scranton, Pennsylvania, where inflation concerns could have an impact on midterm election results.                                                                              , One year into his presidency, Joe Biden's hometown struggles to alleviate rising consumer prices and an ongoing labor shortage.                                                                                                                    , FOX Business’ Connell McShane visited Scranton, Pennsylvania, where Republicans are looking to take advantage of the president’s poor economic record.                                                                                             , Former Rep. Lou Barletta, R-Pa., is one of more than a dozen GOP candidates running for governor in the 2022 midterms, with the Senate race just as crowded.                                                                                       , "I think people are seeing the direction that Pennsylvania is going between Joe Biden and Washington," Barletta told McShane. "Many feel this is the right time to get in, to change the direction of Pennsylvania."                               , INFLATION SURGE IS TOP WEAPON FOR REPUBLICANS IN THEIR 2022 ARSENAL                                                                                                                                                                                , Gerrity’s Supermarkets owner Joe Fasula said a shortage at each link in the supply chain has gotten "out of control," forcing the business to pass on rising prices to consumers.                                                                  , President Joe Biden speaks at an event at the Electric City Trolley Museum in Scranton on October 20, 2021. (Photo by Spencer Platt/Getty Images / Getty Images)                                                                                   , "The best way to answer the question, 'When is inflation going to end?' is with another question of, 'When is the labor shortage going to end?' Because until a labor shortage ends, you're going to continue to see prices increase," Fasula said., With Republicans needing a net gain of just one seat in the 2022 midterm elections to regain Senate majority, inflation could be the key economic issue that tips the scale.                                                                       , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                        , Gerrity’s Supermarkets owner Joe Fasula speaks with FOX Business’ Connell McShane about passing along rising production prices to consumers.                                                                                                       , "It doesn’t matter what part of Pennsylvania I go to, businesses tell me the same thing: ‘We can’t find workers.’ It’s caused inflation," Barletta said.                                                                                           , "Usually there’s backlash to the people who are in office as the cause of that," he pointed out.  "That’s what I think is happening right now."                                                                                                    , READ MORE FROM FOX BUSINESS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/cobalt </td>
   <td style="text-align:left;"> 2022-01-07 00:14:13 </td>
   <td style="text-align:left;"> Cobalt at Near 3-1/2-Year High </td>
   <td style="text-align:left;"> Cobalt futures traded above $70,000 a tonne, hoovering around a 3-1/2-year high of $71,750 touched at the beginning of July 2018 amid prospects that the metal will benefit from the green transition. Cobalt is used in the production of lithium-ion batteries, which is used to produce electric vehicles, so as it is expected that the demand for electric vehicles will grow - amid the green transition - the prices of Cobalt are trying to anticipate this scenario. Also, the metal has successfully outperformed its peers after the shock of the Omicron variant, while it is expected to continue gained momentum throughout a green transition, as the metal has low exposure to China’s property and construction sector, which would not be affected by any crashes in these sectors. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/06/business/covid-paxlovid-antibodies-omicron.html </td>
   <td style="text-align:left;"> 2022-01-07 00:13:30 </td>
   <td style="text-align:left;"> Covid Treatments Including Paxlovid Are Rationed as Cases Spike - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Scarce supplies and surging Covid cases have caused health officials, hospitals, doctors and patients to scramble for pills and infusions.                                                                                                                                                                                                                                                                                                                          , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                             , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                      , By Rebecca Robbins, Noah Weiland and Christina Jewett                                                                                                                                                                                                                                                                                                                                                                                                               , At the onset of the coronavirus pandemic in 2020, scarce ventilators and protective equipment faced strict rationing. Today, as the pandemic rages into its third year, another precious category of products is coming under tight controls: treatments to stave off severe Covid-19.                                                                                                                                                                              , There is a greater menu of Covid pills and infusions now than at any point in the pandemic. The problem is that the supplies of those that work against the Omicron variant are extremely limited.                                                                                                                                                                                                                                                                  , That has forced state health officials and doctors nationwide into the fraught position of deciding which patients get potentially lifesaving treatments and which don’t. Some people at high risk of severe Covid are being turned away because they are vaccinated.                                                                                                                                                                                               , Some hospitals have run out of certain drugs; others report having only a few dozen treatment courses on hand. Staffs are dispensing vitamins in lieu of authorized drugs. Others are scrambling to develop algorithms to decide who gets treatments.                                                                                                                                                                                                               , “There is simply not enough to meet the needs of everyone who is going to have Covid in the upcoming weeks and be at risk of severe complications,” said Dr. Natasha Bagdasarian, Michigan’s chief medical executive. “I don’t think there is a way to make sure it gets to all the right people right now.”                                                                                                                                                        , At Family Health Centers of San Diego, a network of clinics for low-income patients, the staff has had to turn away about 90 percent of the hundreds of people who are calling daily and are eligible for Covid treatments.                                                                                                                                                                                                                                         , “It makes me nauseous going home at night because it makes me feel like I’m deciding, with this limited resource, who should get it,” said Dr. Christian Ramers, an infectious disease specialist there.                                                                                                                                                                                                                                                            , A plentiful supply of effective treatments would be a powerful weapon as the virus again surges across the United States. Fueled by the highly contagious Omicron variant, Covid cases have soared to record highs, and the number of hospitalized patients also has increased sharply, though Omicron tends to cause milder illness than other variants.                                                                                                           , For most of the pandemic, monoclonal antibodies — a treatment generally administered intravenously at hospitals or clinics — have been the primary option for recently infected patients. But the two most common types of the antibodies don’t appear to work against the Omicron variant, which is quickly becoming the world’s dominant version of the coronavirus.                                                                                              , There is a third antibody treatment, made by GlaxoSmithKline and Vir Biotechnology, that is potent against Omicron. But the federal government has ordered only about 450,000 treatment courses, many of which have already been used or have not yet been delivered to states.                                                                                                                                                                                     , The Food and Drug Administration two weeks ago authorized the use of a new antiviral pill, developed by Pfizer, that shows great promise at fighting Covid in general and Omicron cases in particular.                                                                                                                                                                                                                                                              , The federal government is providing the pill, known as Paxlovid, to states, whose health officials decide where to send the pills and how to advise doctors to use them.                                                                                                                                                                                                                                                                                            , Supplies are already being depleted. New York City, for example, received about 1,300 treatment courses of Paxlovid in late December, which it used up within a week, according to a spokesman for Alto Pharmacy, which is distributing the city’s supply. New York City currently does not have any Paxlovid in stock.                                                                                                                                             , On Tuesday, the U.S. government doubled its order for Paxlovid, though supplies won’t be plentiful until April.                                                                                                                                                                                                                                                                                                                                                     , State and local officials say the goal is to get Paxlovid to as many of the most vulnerable people as possible, with a particular focus on those with weakened immune systems or who are unvaccinated.                                                                                                                                                                                                                                                              , Unvaccinated people are at far greater risk of hospitalization or death from Covid. But giving them priority access to treatments leaves people feeling “like you are rewarding intransigence,” said Dr. Matthew K. Wynia, the director of the Center for Bioethics and Humanities at the University of Colorado, who has advised the state on how to ration Covid treatments.                                                                                      , Only some states, like Ohio and Nevada, have sent Paxlovid to pharmacies that serve nursing homes, whose residents are especially vulnerable to Covid. Many states, including Virginia, Pennsylvania and Arizona, have sent most or all of their initial Paxlovid supplies to pharmacy chains like Walgreens and Rite Aid.                                                                                                                                          , That was meant to make the pills as widely accessible as possible. But the system rewards patients who have the time, energy and savvy to chase down treatments.                                                                                                                                                                                                                                                                                                    , Patrick Creighton, 48, a sports radio host in Katy, Texas, woke up on New Year’s Eve with his throat burning. He was vaccinated but tested positive later that day. Concerned that his diabetes elevated his risk of becoming seriously ill, he decided to seek out Paxlovid, which he had been reading up on.                                                                                                                                                      , A telemedicine doctor wrote him a prescription the next day. Now he needed to find a pharmacy with Paxlovid in stock. He said he called 18 pharmacies within driving distance: one Brookshire Brothers, four Krogers, four H-E-Bs, three Walgreens, three CVS stores and three Walmarts. None had the pills.                                                                                                                                                        , His 19th call was a winner: A nearby Walmart had Paxlovid in stock. The ordeal still wasn’t over. He was incorrectly told that he might have to pay $500 for the free treatment. Then he had to see a second telemedicine doctor because of a problem with the way his prescription was sent. Then his wife had to make a second trip to Walmart to pick up the pills. But on the evening of Jan. 2, he finally took the first three tablets of the 30-pill regimen., Mr. Creighton said he worried about patients who weren’t able to navigate the obstacles like he could. “It should be easily obtainable for everybody.”                                                                                                                                                                                                                                                                                                              , The GlaxoSmithKline antibody treatment is similarly hard to come by.                                                                                                                                                                                                                                                                                                                                                                                                , At the University of Pittsburgh Medical Center, the staff is now giving out 400 to 800 antibody treatments each week, down from 2,000 to 3,000 before Omicron rendered two of the products useless. Demand has rocketed higher, but the hospital no longer has enough supply.                                                                                                                                                                                       , “It is devastating to tell these patients, ‘Sorry, we can’t do anything for you, we have to save this drug only for our most severely immunocompromised,’” said Erin McCreary, an infectious diseases pharmacist at the hospital.                                                                                                                                                                                                                                   , Louis Shantzek, a Miami retiree, tried unsuccessfully to get an antibody infusion last week after he tested positive for the virus. He is 72 and has diabetes and a heart condition — all factors that would normally make him eligible to get an antibody treatment.                                                                                                                                                                                               , The global surge. The coronavirus is spreading faster than ever, but it appears that Omicron is milder than previous variants. Still, the latest surge in cases is causing hospitalizations in the U.S. to rise and lifesaving treatments to be rationed.                                                                                                                                                                                                           , Boosters. The C.D.C. endorsed booster shots of the Pfizer vaccine for children ages 12 to 17, citing rising infections in teens and young adults. The agency also said being “up to date” on the vaccine now includes having a booster, though it was not yet changing its definition of “full vaccination.”                                                                                                                                                        , Testing. A new study suggests that two widely used at-home antigen tests may fail to detect some Omicron cases in the first days of infection. The study comes as a White House official said that the cost of rapid at-home tests will be reimbursed by insurers starting next week.                                                                                                                                                                               , U.S. strategy. Six advisers to President Biden’s transition team urged him to adopt a new pandemic strategy — one that is geared to the “new normal” of living with the virus indefinitely. Meanwhile, the C.D.C. is facing criticism for repeatedly failing to explain its policy decisions to the public.                                                                                                                                                         , Around the world. In China, a city of 13 million is locked down over a handful of cases, leading to questions over how long the country’s zero-Covid strategy can last. In France, President Emmanuel Macron drew criticism for saying the government should make life miserable for the unvaccinated.                                                                                                                                                              , Staying safe. Worried about spreading Covid? Keep yourself and others safe by following some basic guidance on when to test and how to use at-home virus tests (if you can find them). Here is what to do if you test positive for the coronavirus.                                                                                                                                                                                                                 , Mr. Shantzek’s symptoms included aches, fatigue and a bad cough. When his adult daughter called two nearby hospitals, she was told he couldn’t get an antibody infusion because he had received three doses of a vaccine and was therefore considered at relatively low risk.                                                                                                                                                                                       , “It’s like being told, ‘You’re doing everything you’re supposed to do, but yet we’re not going to help you,’” said Mr. Shantzek, whose symptoms have since eased.                                                                                                                                                                                                                                                                                                   , This is not the first time in the pandemic that scarce supplies have forced hospitals and doctors into painful treatment decisions. Early on, an intravenous treatment, remdesivir, became so popular that hospitals had to restrict its use. Supplies of remdesivir have since become more plentiful, but the treatment is primarily used for patients who are already hospitalized with severe Covid.                                                             , Drug makers say they are working as fast as possible to produce more treatments.                                                                                                                                                                                                                                                                                                                                                                                    , The federal government did not immediately order supplies of the GlaxoSmithKline antibody when the F.D.A. authorized the treatment’s use last May. At the time, the country had an ample supply of other antibody treatments.                                                                                                                                                                                                                                       , In the fall, the Biden administration ordered about 450,000 doses — the maximum amount that Glaxo could provide since the British company had already committed to fulfill orders from other buyers. (The U.S. government has said it plans to buy a further 600,000 treatment courses.)                                                                                                                                                                            , Pfizer, meanwhile, developed Paxlovid in less than two years. But it takes up to eight months to produce the pills. Though Pfizer started manufacturing them before it began a major clinical trial of the drug last summer, large quantities are only now starting to become available.                                                                                                                                                                            , An increasing number of hospitals are imposing restrictions on treatments.                                                                                                                                                                                                                                                                                                                                                                                          , In western Indiana, officials at Sullivan County Community Hospital determined last month that they had to restrict eligibility for antibody infusions, after weeks of receiving far fewer doses than they had ordered. They opted to almost entirely exclude vaccinated people.                                                                                                                                                                                    , “It does make it difficult to have some of those restrictions in place, when maybe it’s your family member that doesn’t meet the requirement, or it’s your neighbor, or your child’s teacher at school,” said Lori Resler, the hospital’s chief nursing officer.                                                                                                                                                                                                    , In Texas, doctors and their staff have been calling a long list of pharmacies to see who has Paxlovid in stock before prescribing the treatment, said Dr. Luis Ostrosky, chief of infectious diseases at the University of Texas health system. The idea is to avoid sending patients on a wild-goose chase, since many pharmacies received only 20 Paxlovid treatment courses.                                                                                     , On Monday, Brooks Rizzo, a family nurse practitioner and director of the Sunflower Rural Health Clinic in Ruleville, Miss., arrived to find a line of patients waiting in the icy cold as they sought Covid tests and treatments.                                                                                                                                                                                                                                   , Ms. Rizzo said her clinic had not received any antibody treatments since Dec. 24, and it isn’t among the hospitals that were initially picked to receive supplies of Paxlovid. She said clinic employees resorted to providing vitamins and over-the-counter medicines.                                                                                                                                                                                             , Dr. Shireesha Dhanireddy, an infectious disease specialist at the University of Washington, said she spent last weekend poring over the charts of Covid patients to figure out who should get scarce treatments. The three-hospital system has tens of thousands of patients but only 60 courses of Paxlovid. Those getting the pills include patients on certain types of chemotherapy and those who recently received organ transplants.                          , At Johns Hopkins University, employees are rushing to develop algorithms to help allocate scarce treatments, said Dr. Kelly Gebo, an infectious diseases and epidemiology specialist. Compounding the scarcity problem, workers are falling ill, making it harder to deliver resource-intensive treatments like monoclonal antibodies.                                                                                                                              , “It’s demoralizing as health care workers when we can’t deliver optimal care when we have limited resources,” she said.                                                                                                                                                                                                                                                                                                                                             , Sharon LaFraniere contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                                            , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/currency </td>
   <td style="text-align:left;"> 2022-01-07 00:05:19 </td>
   <td style="text-align:left;"> Brazilian Real not Far from 8-Month Low </td>
   <td style="text-align:left;"> The Brazilian Real traded around 5.70 at the beginning of January, not far from an 8-month low of 5.745 hit on December 21st, after the FOMC minutes showed the Fed will likely raise rates sooner than expected and braced for the possibility of cutting its bond holdings. Also, the currency remains subdued amid successively negative revisions for the economic growth in 2022. In 2021, analysts even projected a GDP growth of 2.5% for this year, although, after shocks, expectations have receded to 0.36%. In addition, an increasing political uncertainty has driven investors away from the real as the general elections of 2022 approach, polls are showing that the left-wing PT is increasingly likely to win, while fiscal concerns increased after populist policies from Bolsonaro. Meanwhile, news that president Jair Bolsonaro was hospitalized during the weekend for an intestinal blockage brought additional volatility to the market. The far-right president plans to run for re-election in October. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/cocoa </td>
   <td style="text-align:left;"> 2022-01-07 00:03:42 </td>
   <td style="text-align:left;"> Cocoa Hits 5-week Low </td>
   <td style="text-align:left;"> Cocoa decreased to a 5-week low of 2414 USD/T </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-01-06 23:56:37 </td>
   <td style="text-align:left;"> Natural Gas Hovers Below $3.9 after Storage Report </td>
   <td style="text-align:left;"> US natural gas futures traded below $3.9 per million British thermal units, amid forecasts for less cold weather and lower heating demand next week than previously expected. Also, EIA data showed a smaller-than-expected storage draw last week due to milder than normal weather. US utilities pulled just 31 billion cubic feet of gas from storage during the week ended December 31st, compared with a decline of 127 bcf in the same week last year. Meanwhile, lingering cold since New Year's Day has continued to cause well freeze-offs in Texas, New Mexico, North Dakota, Pennsylvania, West Virginia and Ohio. Demand from Europe and Asia remains historically high and US producers have been boosting LNG exports to Europe. The United States will be the biggest exporter of LNG in the world through 2022 as a whole, according to forecasts from ICIS and the US Energy Information Agency, as the country's production and storage remain elevated. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/currency </td>
   <td style="text-align:left;"> 2022-01-06 23:55:41 </td>
   <td style="text-align:left;"> Mexican Peso at Near 2-Month High </td>
   <td style="text-align:left;"> The Mexican peso traded around 20.45 per USD in the first week of January, the strongest since early November after the central bank minutes showed that the policymakers remain concerned over inflation and triggering expectations of a continuation in the tightening cycle. In its last meeting, Banxico surprised the markets and hiked the rates by 50 bps to 5.5%, above expectations of 25 bps saying inflation risk balance has deteriorated, with both the headline inflation and the core inflation expectations for the next year increasing again, and the ones for the medium-term remaining above the target. The inflation hit a 20-year high of 7.37% in November, well above the Banxico target of 3% plus or minus one percentage point. Also, rising oil prices and a recovery in risk appetite as traders hope omicron disruptions will not derail growth helped to boost further gains in the currency. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-01-06 23:51:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index at Over 2-Week High </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index went up 0.3% to 2,296 on Thursday, its highest since December 20th and extending gains for a third straight session, amid an uptick in demand across its larger vessel segments. "This week started with uncertainty for the Indonesian coal export after the government put a ban during the weekend," said shipbroker Fearnleys. The capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, rose 2.4% to 2,356; and the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, incresed 10 points to 3,013. Meanwhile, the supramax index slipped 41 points to its lowest level since April 2021 at 2,124. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/currency </td>
   <td style="text-align:left;"> 2022-01-06 23:42:09 </td>
   <td style="text-align:left;"> Chinese Yuan Hits 5-week Low </td>
   <td style="text-align:left;"> USDCNY increased to a 5-week high of 6.3936 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-06 23:41:00 </td>
   <td style="text-align:left;"> China Government Bond 10Y Around 2.8% </td>
   <td style="text-align:left;"> The yield on the benchmark China 10-year government bond edged slightly up to 2.8% at the beginning of January after it become clear that China will keep loose monetary policy while the Fed is likely to tight monetary policy faster. The People's Bank of China at the December 20th fixing slashed its one-year loan prime rate by 5 bps to 3.8 percent, the first-rate cut in 20 months, in a bid to support growth amid property debt woes and persistent COVID-19 outbreaks. Meanwhile, China plans to sell a record amount of treasury bonds in 2022, while keeping overall interest rates of the issuance lower, as Beijing adopts a proactive policy to stabilize economic growth, a senior official at the finance ministry said in late December. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/currency </td>
   <td style="text-align:left;"> 2022-01-06 23:40:22 </td>
   <td style="text-align:left;"> Canadian Dollar Hovers at One-Week Low </td>
   <td style="text-align:left;"> The Canadian dollar weakened to above 1.275, not far from a one-week low of 1.27883 hit on December 29th, after the FOMC minutes showed the Fed will likely raise rates sooner than expected and braced for the possibility of cutting its bond holdings. Still, further losses in the loonie were cushioned by higher oil prices, which rose to near $80 a barrel. Also, investors remained optimistic as studies showed that the Omicron variant is less severe than previous strains, albeit more infectious, gearing up traders to bet that the economic recovery will not derail. A more robust economic recovery strengthens the appeal for higher rates from the BoC, which dashed investors’ expectations in its last meeting arguing that the new variant Omicron had raised uncertainty around the economic recovery. Canada's jobs report for December, , due on Friday, could provide further clues on the strength of the domestic economy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-06 23:38:00 </td>
   <td style="text-align:left;"> Japan 10Y Government Bond Yield at 10-Month High </td>
   <td style="text-align:left;"> The yield on the benchmark Japan 10-year JGB extended a rally to a 10-month high of 0.1% in the first week of January, tracking a general rise in global bond yields after the latest FOMC minutes showed the Fed will likely increase interest rates sooner rather than later. In contrast, the Bank of Japan will reduce corporate debt purchases in March but it is in no rush to normalise monetary policy, in a divergent path with many other central banks that would likely scale back monetary stimulus soon. Meanwhile, the Japanese government lifted its growth forecasts for the economy in fiscal 2022 to 3.2% from 2.2%, while approving a record budget of JPY 107.6 trillion, aiming to boost growth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-06 23:31:41 </td>
   <td style="text-align:left;"> Australia 10-Year Bond Yield at Over 1-Month High </td>
   <td style="text-align:left;"> The yield on the Australian 10-year government bond extended gains to climb above 1.8% in early January, touching its highest level since late November and tracking a general rise in US Treasury yields, amid expectations of quicker interest rate hikes. The latest FOMC meeting minutes suggested the US Federal Reserve could raise interest rates as early as March to curb inflation, amid improving outlooks for the economy and labor market. At the same time, markets have priced in up to three interest rate hikes by the Reserve Bank of Australia this year, as inflation pressure and expectations remain elevated and as unemployment levels continue to fall. In addition, investors continue to hope the omicron coronavirus variant will not disrupt the economic activity as initially expected although infections continue to rise globally. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/bed-bath-beyond-earnings-supply-chain-disruptions </td>
   <td style="text-align:left;"> 2022-01-06 23:13:32 </td>
   <td style="text-align:left;"> Bed Bath &amp; Beyond shares surge despite earnings miss </td>
   <td style="text-align:left;"> Strategic Resource Group managing director Burt Flickinger on which businesses are struggling with pandemic exit strategies.                                                                                                                                                                                                                                                                                                                                                                                                          , Shares of Bed Bath &amp; Beyond surged Thursday despite the company's third quarter earnings taking an estimated $100 million hit due to supply chain disruptions.                                                                                                                                                                                                                                                                                                                                                                        , The retailer posted a third quarter net loss $276 million, or $2.78 per share, down from a loss of $75 million, or 61 cents, a year ago. Adjusted for one-time items, the loss was 25 cents a share. Net sales slid for the second consecutive quarter to $1.88 billion, down 28% compared to $2.62 billion a year ago, while overall comparable sales declined 7% year-over-year.                                                                                                                                                    , COVID-19 VACCINES GIVE WALGREENS AN EDGE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Bed Bath &amp; Beyond banner comparable sales fell 10% year-over-year, with destination categories such as bedding, bath, kitchen food prep, indoor decor and home organization, which represent approximately two-thirds of the banner's total sales, declining 13% year-over-year.                                                                                                                                                                                                                                                      , Meanwhile, the buybuy BABY banner delivered its fourth consecutive quarter of comparable sales growth, increasing in the midteens compared to a year ago and driven by double-digit store growth and high-single digit digital growth.                                                                                                                                                                                                                                                                                                , A Bed Bath and Beyond store in the Tribeca neighborhood in New York City, Oct. 1, 2021.  (Michael M. Santiago/Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                                                                                            , Though Bed Bath &amp; Beyond CEO Mark Tritton admitted the company's quarterly sales momentum was "not where we wanted it to be," he emphasized that the company is on track to achieve approximately $1.3 billion in sales in the first year of its transformation, ahead of its investor day goals, and that it continues to improve profitability and market share.                                                                                                                                                                    , The company noted its Beyond+ loyalty program grew by nearly half a million members in the third quarter and that its adjusted gross margin rate has significantly exceeded its plans and is above 2020 and 2019 due to market driven pricing, promo optimization and product mix actions to fight a sharp increase in inflation and pervasive freight and supply chain headwinds.                                                                                                                                                    , So far, Bed Bath &amp; Beyond has closed 170 locations as part of its three-year transformation and it expects to close 200 stores by the end of the year.                                                                                                                                                                                                                                                                                                                                                                                , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , In addition to announcing its own digital marketplace and a collaboration with Kroger, Bed Bath &amp; Beyond is looking to expand its portfolio of Owned Brands to buybuy BABY in 2022 given the business' stabilized sales results. The company also expects to complete its $1 billion three-year share repurchase plan by the end of fiscal year 2021, two years ahead of schedule.                                                                                                                                                    , Looking ahead, the company anticipates approximately $2.1 billion in sales from its core businesses in the fourth quarter. On a comparable sales basis, Bed Bath &amp; Beyond expects a high-single digit decline compared to the same period a year ago and adjusted earnings per share of up to 15 cents. Bed Bath &amp; Beyond is also revising its full-year outlook to a net sales forecast of approximately $7.9 billion, comparable sales growth in the high-single digits, and an adjusted earnings per share loss of up to 15 cents.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/7-year-note-yield </td>
   <td style="text-align:left;"> 2022-01-06 23:09:16 </td>
   <td style="text-align:left;"> Australia 7Y Bond Yield Hits 6-week High </td>
   <td style="text-align:left;"> Australia 7 Year Government Bond Yeld increased to a 6-week high of 1.699% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/20-year-bond-yield </td>
   <td style="text-align:left;"> 2022-01-06 23:08:28 </td>
   <td style="text-align:left;"> Australia 20Y Bond Yield Hits 6-week High </td>
   <td style="text-align:left;"> Australia 20 Year Government Bond Yeld increased to a 6-week high of 2.453% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/3-year-note-yield </td>
   <td style="text-align:left;"> 2022-01-06 23:07:50 </td>
   <td style="text-align:left;"> Australia 3Y Bond Yield Hits 4-week High </td>
   <td style="text-align:left;"> Australia 3 Year Government Bond Yeld increased to a 4-week high of 1.034% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/5-year-note-yield </td>
   <td style="text-align:left;"> 2022-01-06 23:07:47 </td>
   <td style="text-align:left;"> Australia 5Y Bond Yield Hits 5-week High </td>
   <td style="text-align:left;"> Australia 5 Year Government Bond Yeld increased to a 5-week high of 1.484% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/factory-orders </td>
   <td style="text-align:left;"> 2022-01-06 23:05:00 </td>
   <td style="text-align:left;"> US Factory Orders Rise Most in 6 Months </td>
   <td style="text-align:left;"> New orders for US manufactured goods rose by 1.6 percent from a month earlier in November 2021, the largest increase since May and slightly above market expectations of 1.5 percent. Demand for transport equipment was up 6.5 percent (vs -0.3 percent in October), boosted by civilian aircraft (34.0 percent vs -4.1 percent), defense aircraft (3.0 percent vs -18.6 percent), and vehicles (0.4 percent vs 3.2 percent). Orders also advanced for computers and electronic products (4.0 percent vs 0.9 percent), fabricated metal products (0.7 percent vs -0.6 percent), and primary metals (0.2 percent vs 1.0 percent), while a decline was seen in demand for machinery (-0.9 percent vs -0.5 percent), and electrical equipment, appliances, and components (-1.1 percent vs 1.6 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/non-manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-01-06 23:05:00 </td>
   <td style="text-align:left;"> US Services Growth Slows More than Expected: ISM </td>
   <td style="text-align:left;"> The ISM Services PMI fell to 62 in December from a record high of 69.1 in November, well below market forecasts of 66.9. but still pointing to the 19th consecutive month of growth in the sector. The demand for services remains strong and sustained but companies continue to struggle with inflation, supply chain disruptions, capacity constraints, logistical challenges and shortages of labor and materials.  A slowdown was seen in production (67.6 vs 74.6), new orders (61.5 vs 69.7) and employment (54.9 vs 56.5) while price pressures intensified slightly (82.5 vs 82.3) and inventories contracted at a faster pace (46.7 vs 48.2). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/06/hedge-funds-are-selling-tech-shares-at-their-fastest-pace-in-a-decade-as-rates-spike.html </td>
   <td style="text-align:left;"> 2022-01-06 23:01:17 </td>
   <td style="text-align:left;"> Hedge funds are selling tech shares at their fastest pace in a decade as rates spike </td>
   <td style="text-align:left;"> , Surging bond yields have triggered hedge funds to sell growth-focused technology shares at a speed not seen in the past decade.                                                                                                                                                                             , The hedge fund community dumped tech stocks in the four sessions between Dec. 30 and Tuesday as interest rates spiked. The four-session tech unloading marked the biggest sale in dollar terms in more than 10 years, reaching a record since Goldman Sachs' prime brokerage started tracking the data.     , Tech stocks are seen as sensitive to rising yields because increased debt costs can hinder their growth and can make their future cash flows appear less valuable. The tech-heavy Nasdaq Composite has sold off more than 3% this week, underperforming the S&amp;P 500, which dipped 1% during the same period., The rate spike in the new year resumed Thursday, with investors assessing the Federal Reserve's faster-than-expected policy tightening. The yield on the benchmark 10-year Treasury note hit a high of 1.75% during the session, rising for a fourth straight day. The benchmark rate ended 2021 at 1.51%.  , Yields jumped after the Fed issued on Wednesday minutes from its last meeting, which showed the central bank could become even more aggressive than expected about raising interest rates and tightening policy.                                                                                            , Goldman noted that hedge funds' selling of tech stocks is driven almost entirely by long sales, in contrast to mainly short sales seen in the last two months of 2021. The selling was driven by software and semiconductor stocks, the Wall Street firm said.                                              , Many Big Tech names have been under pressure. Shares of Netflix have fallen more than 8% this week. Microsoft has dropped 6% in the new year, while Alphabet fell 4%.                                                                                                                                       , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                      , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                      , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                            , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                            , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                          , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-06 23:01:00 </td>
   <td style="text-align:left;"> Canada 10Y Bond Yield at Near 6-Week High </td>
   <td style="text-align:left;"> The yield on the Canadian 10-year government bond traded near 1.7% in the first week of January, close to levels not seen since November 25th, tracking an increase in US Treasury yields after the FOMC minutes showed the Fed will likely raise rates sooner than expected and braced for the possibility of cutting its bond holdings. Interest rate futures now roughly see an 80% chance of a rate hike in the fed funds rate at the March meeting. Also, investors remained optimistic as studies showed that the Omicron variant is less severe than previous strains, albeit more infectious, gearing up traders to bet that the economic recovery will not derail. A more robust economic recovery strengthens the appeal for higher rates from the BoC, which dashed investors’ expectations in its last meeting arguing that the new variant Omicron had raised uncertainty around the economic recovery. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/politics/2022/01/06/president-joe-biden-january-6th-anniversary-trump-defeated-remarks-vpx.cnn </td>
   <td style="text-align:left;"> 2022-01-06 23:00:45 </td>
   <td style="text-align:left;"> Video: Biden tears into Trump during January 6th speech - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/bulgaria/stock-market </td>
   <td style="text-align:left;"> 2022-01-06 22:59:01 </td>
   <td style="text-align:left;"> Stocks in Bulgaria Hit 3-year High </td>
   <td style="text-align:left;"> SOFIX increased to a 3-year high of 646.86 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/solar </td>
   <td style="text-align:left;"> 2022-01-06 22:58:58 </td>
   <td style="text-align:left;"> Solar Energy Index Hits 33-week Low </td>
   <td style="text-align:left;"> Solar Energy Index decreased to a 33-week low of 361.36 USD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-01-06 22:58:16 </td>
   <td style="text-align:left;"> Crude Oil is up by 2.52% </td>
   <td style="text-align:left;"> Crude Oil WTI increased 2.52% to 79.81 USD/Bbl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/wheat </td>
   <td style="text-align:left;"> 2022-01-06 22:58:00 </td>
   <td style="text-align:left;"> Wheat Falls to 11-Week Low </td>
   <td style="text-align:left;"> Chicago wheat futures declined to $7.4 a bushel in the first week of January, the lowest in over two months, amid lower export demand. Fresh data from the USDA showed that the United States exported 48.6 thousand tonnes of wheat in the week that ended December 30th, the lowest since the start of the marketing year in June, far below market estimates between 150 and 400 thousand tonnes. The US sold 273.5 tonnes of wheat in the same period in the previous year. China purchased 200 tonnes (vs 55.4 thousand tonnes in the same period last year) while 9.6 tonnes were purchased by Mexico (vs 33.7 thousand). Meanwhile, commodity traders await the World Agricultural Supply and Demand Estimates report by the USDA to be published January 12th for better insights. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-01-06 22:54:51 </td>
   <td style="text-align:left;"> Canadian Shares Trade Slightly Higher </td>
   <td style="text-align:left;"> The S&amp;P/TSX was slightly higher to hover around 21,060 on Thursday, rebounding from a 0.9% loss in the last session, as gains in the oil-backed stocks more offset losses in miners, as investors trade cautiously amid outlooks of tighter monetary policy by the Federal Reserve. Minutes from the latest FOMC meeting indicate that policymakers are ready to accelerate the cutback of stimulus in the economy while noting it could be appropriate to reduce the size of the Fed’s balance sheet after raising the federal funds rate. On the corporate front, energy shares jumped 4%, tracking higher oil prices, while the keystone pipeline resumed operations after it was shut down due to harsh winter weather. Financial stocks (0.6%) also booked gains. On the other hand, mining shares loss 1.6% from lower bullion prices, while technology shares extended yesterday’s losses to drop 1%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-01-06 22:51:00 </td>
   <td style="text-align:left;"> Brazilian Equities Try to Recover </td>
   <td style="text-align:left;"> The Ibovespa stock index was up 1% to around 101,990 on Thursday, snapping a three-day losing streak, boosted by heavyweight miner Vale and steel companies amid rising iron ore prices. Meanwhile, investors continued to digest the prospect of a more hawkish Federal Reserve and uncertainty around the Covid-19 pandemic. On the data front, industrial production in Brazil unexpectedly fell for a sixth consecutive month in November, highlighting persistent weakness in the sector and raising concerns over Latin America's largest economy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/6-month-bill-yield </td>
   <td style="text-align:left;"> 2022-01-06 22:41:20 </td>
   <td style="text-align:left;"> Canada 6M Bond Yield Hits 21-month High </td>
   <td style="text-align:left;"> Canada 6 Month Government Bond Yeld increased to a 21-month high of 0.525% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-06 22:38:00 </td>
   <td style="text-align:left;"> US Stocks Attempt to Recover </td>
   <td style="text-align:left;"> The 3 main US stock indexes fluctuated on Thursday with the Dow declining as much as 30 points and S&amp;P and Nasdaq attempting to rebound from a big Fed fallout in the previous session. Still, the tech sector sensitive to a rise in borrowing cost remained under pressure with Tesla, Netflix, Apple, Amazon and Fintech stocks staying in the negative territory. On the other side, banks including Bank of America and JPMorgan Chase gained slightly on higher treasury yields. Meanwhile, the claims report continued to point to a tight labour market and all eyes now turn to the payrolls data due tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/rubber </td>
   <td style="text-align:left;"> 2022-01-06 22:30:00 </td>
   <td style="text-align:left;"> Rubber Falls from Over 1-Month High </td>
   <td style="text-align:left;"> Osaka rubber futures fell to 224 yen per kg level at the start of 2022, after hitting an over one-month high of 229 on January 5th and despite a weaker yen, amid sluggish domestic automobile sales and fears over rising COVID-19 cases worldwide. Japan's domestic new car sales fell 11.4% in December from a year earlier, a sign that supply bottlenecks continued to delay deliveries and weigh on the country's fragile consumption. Rubber lost nearly 18% in 2021 as demand from the auto sector declined due to chip shortages and COVID-19 restrictions imposed especially across Europe and top buyer China. Still, the imports from China are set to pick ahead of the week-long holiday for the Lunar New Year as factories are building up inventories to address seasonal supply shortage coinciding with the annual wintering of rubber trees in major producing countries. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/currency </td>
   <td style="text-align:left;"> 2022-01-06 22:27:00 </td>
   <td style="text-align:left;"> South African Rand Strengthens </td>
   <td style="text-align:left;"> The South African rand was trading around 15.7 against USD in early January, after touching a three-week low of 16, amid increasing bets that the South African Reserve Bank will hike interest rates early this year. The currency was also supported by the lifting of travel restrictions by France, joining similar decisions by other countries, and prospects that South Africa’s national state of disaster could end soon after authorities confirmed the Western Cape, the recent epicenter of the Omicron variant, has now passed the peak of its fourth wave of Covid-19 infections, with a consistent decline in cases expected in the coming weeks. However, expectations of a faster-than-expected rise in US interest rates and concerns over South Africa's economic outlook limited further gains. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/uk-politics-59893027?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-06 22:23:17 </td>
   <td style="text-align:left;"> I understand anxiety over rising prices, says Chancellor Rishi Sunak </td>
   <td style="text-align:left;"> This video can not be played                                                                                                                                                                                                                                                                                             , Chancellor Rishi Sunak has said he "understands people's anxiety... about rising prices" and insisted he will "always be listening" to concerns.                                                                                                                                                                         , He pointed to a living wage rise and the winter fuel payment as ways the government is helping people.                                                                                                                                                                                                                   , But the chancellor is coming under pressure from Labour and some of his own MPs to cut the VAT on energy bills.                                                                                                                                                                                                          , And minister Jacob Rees-Mogg is reported to have raised concern about a tax rise coming into force in April.                                                                                                                                                                                                             , On Wednesday, the Financial Times said the leader of the House, Mr Rees-Mogg, had argued against a hike in National Insurance in a Cabinet meeting, calling instead for savings to be made in government spending.                                                                                                       , The government says the rise will initially help tackle the backlog in the NHS, and later be invested in social care.                                                                                                                                                                                                    , Asked if there were splits in the Cabinet over the tax, Mr Sunak said he had respect for his colleagues but added that it was "not a responsible thing to do" to "duck difficult decisions" and that people wanted the government to invest in the NHS and social care.                                                  , The tax rise is due to kick in during April, around the same time households could see a big rise in their energy bills.                                                                                                                                                                                                 , Soaring global gas prices on the wholesale market have put pressure on suppliers, and 27 energy companies have gone bust.                                                                                                                                                                                                , Speaking in the Commons on Thursday, Conservative MP Peter Bone urged the government to cut VAT on energy bills to help consumers.                                                                                                                                                                                       , "Energy costs are not a luxury, they are a necessity, something that you can't avoid. You need to heat your home," he said.                                                                                                                                                                                              , Labour are also urging the government to scrap VAT on energy bills with the party's deputy leader Angela Rayner accusing the prime minister of failing "to invest in long term energy security" and that "yet again working families are picking up tab for his incompetence" at Prime Minister's Questions on Wednesday., Liberal Democrat leader Sir Ed Davey says the warm homes discount should be increased from £140 per year to £300 and offered to more people.                                                                                                                                                                             , Speaking to the Today programme, he said: "We've got to pay for it. But one of the other effects of the big rising global gas prices, as well as hitting people with their heating bills, is it's resulted in record profits for the oil and gas sector.                                                                 , "I think at this stage, when people are going to face an average increase in energy bill of nearly £700, and these oil and gas sectors are making super-profits, it's not unreasonable to ask them to make a contribution."                                                                                              , Speaking from a vaccination centre in West Sussex, the chancellor said the government had put in place a series of measures to help people with energy costs.                                                                                                                                                            , "We announced half a billion pounds towards the end of last year to help millions of families - £100-£150 to help them get through the winter," he said.                                                                                                                                                                 , The chancellor also cited the warm homes discount which reduces energy bills by £140, cold weather payments and winter fuel discounts.                                                                                                                                                                                   , "There is support there for people," he said, but added that he was "always listening making sure the policy we've got will support people in the way we want it to, and that's what our track record over the last year or two shows".                                                                                  , Abolishing VAT of 5% on energy bills would be quick and easy, but is considered a blunt instrument, as it would provide support to well-off customers who don't need it.                                                                                                                                                 , And for those that do need it, 5% of a possible £700 price rise is pretty small.                                                                                                                                                                                                                                         , The government could temporarily suspend the additional levies on bills that fund green policies.                                                                                                                                                                                                                        , But that would be a tricky sell in some quarters, after the UK hosted a major global climate summit, and these levies are designed to reduce dependence on volatile fossil fuels.                                                                                                                                        , One other option is to extend and expand the Warm Homes Discount. Currently, customers in receipt of certain benefits can apply for a one-off payment of £140.                                                                                                                                                           , And another option - suggested by the industry - would be to subsidise the energy companies themselves, by establishing a fund or facility which would allow them to draw down government cash when wholesale prices were very high and then pay it back when prices dipped again.                                       , Read more from Simon Jack here.                                                                                                                                                                                                                                                                                          , David Tennant stars as an unlikely globetrotter...                                                                                                                                                                                                                                                                       , The Highland hermit who must choose between happiness and health...                                                                                                                                                                                                                                                      , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/20-year-bond-yield </td>
   <td style="text-align:left;"> 2022-01-06 22:16:28 </td>
   <td style="text-align:left;"> UK 20Y Bond Yield Hits 10-week High </td>
   <td style="text-align:left;"> UK 20 Year Government Bond Yeld increased to a 10-week high of 1.376% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/technology-59880739?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-06 21:50:46 </td>
   <td style="text-align:left;"> NFT marketplace OpenSea valued at more than $13bn </td>
   <td style="text-align:left;"> An online marketplace OpenSea says it is now worth $13.3bn (£9.8bn) following a new investment of $300m.                                                                                  , The platform enables trade in NFTs (non-fungible tokens), unique pieces of digital code that can be associated with a digital asset such as a work of digital art.                        , Some NFTs have sold for millions of dollars.                                                                                                                                              , OpenSea says trades on the platform rose 600-fold last year, but some critics say the valuation is too high.                                                                              , "In 2021, we saw the world awaken to the idea that NFTs represent the basic building blocks for brand new peer-to-peer economies," wrote Devin Finzer, who co-founded the company in 2017,, But others argue the spiralling valuations of some crypto-businesses reflects a shortage of places for investors to put their money.                                                      , "There's far too much money sloshing around and far too few places to put it," said author David Gerard. "Even the rich are buying lottery tickets."                                      , The valuation for OpenSea comes at a time when an increasing number of businesses, sports clubs and celebrities are producing or purchasing NFTs.                                         , Recently the rapper Eminem spent about $450,000 on an image of a "Bored Ape" resembling him.                                                                                              , The Bored Ape Yacht Club (BAYC) is a collection of thousands of NFTs of digital illustrations of anthropomorphic apes.                                                                    , Bored Apes are among the most popular NFTs  - the total value of trades just passed $1bn according to data from Cryptoslam - an NFT industry data aggregator.                             , Not everyone shares the rapper's appreciation of the digital artworks. The Guardian's art critic Jonathan Jones called them a "very ordinary and derivative bit of comic book design".    , But BAYC says each ape image is "unique and programmatically generated from over 170 possible traits, including expression, headwear, clothing, and more".                                , The market in digital art and collectables is now approaching that of the global art trade, according to the Financial Times.                                                             , The total value of trade for NFTs was estimated to be worth $40.9bn last year according to calculations by blockchain data firm Chainalysis, the paper reported.                          , The figure is probably an underestimate, because only NFTs using the Ethereum blockchain were considered.                                                                                 , Last year the global art market was worth $50.1bn, it said.                                                                                                                               , Announcing new funding, OpenSea said it would "look to bring NFTs to a broad consumer audience this year" and reduce their "barriers to entry".                                           , But regulators and critics worry that consumers may not appreciate the risks involved in largely unregulated crypto-asset investments like NFTs.                                          , Research by Chainalysis suggested that while many people may collect them, data shows that expert investors make most of the money.                                                       , Other analysts worry NFT marketplaces are prone to so-called wash-trading where investors sell and then buy back an NFT they own with the aim of boosting demand.                         , The environmental impact of the technology behind NFTs also concerns critics.                                                                                                             , As with crypto-currency, the record of who owns what NFT is stored on a shared ledger known as the blockchain, a process maintained by thousands of computers worldwide.                  , Keeping those computers running creates a considerable demand for electricity and consequently pollution.                                                                                 , David Tennant stars as an unlikely globetrotter...                                                                                                                                        , The Highland hermit who must choose between happiness and health...                                                                                                                       , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/imports </td>
   <td style="text-align:left;"> 2022-01-06 21:49:00 </td>
   <td style="text-align:left;"> Canada November Imports at Record High </td>
   <td style="text-align:left;"> Imports to Canada rose by 2.4  % over a month to a record high of CAD 55.4  billion in November of 2021, driven by atypical shipments of pharmaceutical products. Gains were observed in 6 of 11 product sections. Imports of consumer goods rose for the fourth consecutive month (+5.2%) as Canada saw large imports of vaccines and medication for packaging and labelling. Higher purchases were also seen for metal and non-metallic mineral products (+7.3%), particularly iron and steel products (+24.9%) because of higher imports from South Korea; and basic and industrial chemical, plastic and rubber products (+7.3%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/imports </td>
   <td style="text-align:left;"> 2022-01-06 21:44:00 </td>
   <td style="text-align:left;"> US Imports Surge 4.6% to New Record </td>
   <td style="text-align:left;"> Imports to the United States increased further by USD 13.4 billion to a new record high of USD 304.4 billion in November 2021, amid a continued strong domestic recovery and ahead of the holiday shopping season. Purchases of goods were up USD 12.3 billion due to imports of industrial supplies and materials (up USD 5.9 billion), namely finished metal shapes and crude oil; consumer goods (up USD 3 billion), mainly driven by pharmaceutical preparations; and automotive vehicles, parts, and engines (up USD 1.2 billion). Imports of services increased $1.1 billion, driven by transport and travel. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/exports </td>
   <td style="text-align:left;"> 2022-01-06 21:41:00 </td>
   <td style="text-align:left;"> Canada November Exports at Record High </td>
   <td style="text-align:left;"> Exports from Canada increased by 3.8 % over a month to a record high of CAD 58.6 billion in November of 2021, despite transportation disruptions caused by flooding and landslides in British Columbia. It was also the fifth increase in six months. Exports were up in 8 of 11 product sections, mainly driven by sales of consumer goods (+9%), particularly pharmaceutical products. Also, shipments rose for basic and industrial chemical, plastic and rubber products (+14.7%); lubricants and other petroleum refinery products (+58.1%) due to higher exports of motor gasoline blending stock (a refinery output) to the United States; energy products (+2.8%), particularly crude oil (+5.6%)and petroleum energy products (+61.2%); and forestry products and building and packaging materials (+6.7%). However, gains were offset by lower exports of coal (-29%) and natural gas (-17%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/balance-of-trade </td>
   <td style="text-align:left;"> 2022-01-06 21:39:00 </td>
   <td style="text-align:left;"> US Trade Gap Close to Record High </td>
   <td style="text-align:left;"> The US trade deficit increased to $80.2 billion in November of 2021 from an upwardly revised $67.2 billion gap in October and close to a record high of $81.4 billion in September. Figures compare with market forecasts of $77.1 billion. Imports jumped 4.6% to a fresh record of $304.4 billion, prompted by a broad-based increase in purchases, namely finished metal shapes, crude oil, and passenger cars. Exports also reached a new all-time high of $224.2 billion, edging up 0.2%, driven by services mainly travel and transport, and higher shipments of crude oil while sales fell for nonmonetary gold and capital goods. Considering the first 11 months of 2021, the US recorded a trade gap of $785.5 billion and is on track to reach a record high for the full year as the economy continues to recover from the pandemic, boosting demand. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/balance-of-trade </td>
   <td style="text-align:left;"> 2022-01-06 21:37:00 </td>
   <td style="text-align:left;"> Canada Posts Largest Trade Surplus in 13-Years </td>
   <td style="text-align:left;"> Canada’s trade surplus surged to CAD 3.13 billion in November of 2021, the largest since 2008, from an upwardly revised CAD 2.26 billion surplus and surpassing market estimates of a CAD 2.03 billion. Exports jumped 3.8 percent to a new record of CAD 58.6 billion, boosted by pharmaceutical products as the country received large shipments of Covid-19 medication and vaccines for packaging and labeling, only to be subsequently exported in the same month. Notable increases in sales also were reported for industrial chemical, plastic, and rubber products and energy products. Meanwhile, imports rose at a softer 2.4% to a record CAD 55.4 billion, also due to the high influx of pharmaceutical products, while purchases of metal and non-metallic minerals rebounded significantly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/exports </td>
   <td style="text-align:left;"> 2022-01-06 21:37:00 </td>
   <td style="text-align:left;"> US Exports Rise 0.2% to New Record High </td>
   <td style="text-align:left;"> Exports from the United States increased by USD 0.4 billion from a month earlier to USD 224.2 billion in November of 2021, the highest level since the series began in 1950, reflecting strong foreign demand, a general rise in prices and increased travel volume. Exports of services increased USD 3.2 billion, boosted by travel and transport. However, sales of goods fell USD 2.9 billion, amid lower shipments of capital goods (down USD 1.2 billion), namely other industrial machines; telecommunications equipment and civilian aircraft engines; and industrial supplies and materials (down USD 0.9 billion), due to nonmonetary gold. By contrast, exports of oil increased USD 0.4 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/jobless-claims </td>
   <td style="text-align:left;"> 2022-01-06 21:36:00 </td>
   <td style="text-align:left;"> US Weekly Jobless Claims Rise Last Week </td>
   <td style="text-align:left;"> The number of Americans filing new claims for unemployment benefits increased by 7 thousand to 207 thousand in the week ending January 1st from an upwardly revised 200 thousand in the previous period and compared to market expectations of 197 thousand. Still, claims remained below the levels seen before the Covid-19 pandemic, when claims were averaging around 215,000. The 4-week moving average of claims, which removes week-to-week volatility, rose to 204.5 thousand, an increase of 4.75 thousand from the previous week's revised average of 199.75 thousand. On a non-seasonally adjusted basis, initial claims rose by 57.6 thousand to 315.47 thousand with notable increases being recorded in New York (+8,922), Pennsylvania (+6,806), Connecticut (+5,992), Washington (+4,578) and Michigan (+4,559). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/cocoa </td>
   <td style="text-align:left;"> 2022-01-06 21:27:00 </td>
   <td style="text-align:left;"> Cocoa Falls to $2400 on Production Surplus Expectations </td>
   <td style="text-align:left;"> Cocoa futures continued to fall to trade close to $2400 a tonne at the beginning of January, much below its one-year peak of $2755 hit in October and extending a 2.6% loss from last year amid expectations of a global production surplus and a temporary drop in demand. Light rains and mild seasonal winds in most of Ivory Coast's cocoa-growing regions should boost the quality and size of the October-to-March main crop and increase the April-to-September crop. Also, subdued chocolate consumption amid renewed Omicron-induced movement restrictions pressured the cocoa market. Still, the International Cocoa Organization (ICCO) in its recent report projected that demand for cocoa would go up by 4.9 million tonnes in 2021/2022 cropping season due to increased use of beans whereas production would rise at a faster 5.2 million tonnes due to better weather conditions in major producing countries. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/uk-59892136?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-06 21:13:21 </td>
   <td style="text-align:left;"> Covid: Pre-departure travel tests have outlived their usefulness - Shapps </td>
   <td style="text-align:left;"> This video can not be played                                                                                                                                                                                                                                                                                                          , The current Covid testing system for people travelling to England has "outlived its usefulness", Transport Secretary Grant Shapps says, as Omicron is now "widespread and worldwide".                                                                                                                                                 , Ahead of a rule change later this week, he said the system - introduced to slow Omicron's spread - had "done its part".                                                                                                                                                                                                               , Pre-departure tests will end for fully vaccinated travellers and day two PCRs will be replaced by lateral flow tests.                                                                                                                                                                                                                 , Mr Shapps said ministers would "ensure a stable system is in place for 2022".                                                                                                                                                                                                                                                         , The shake-up, announced on Wednesday, came after travel firms said the measures were not effective now Omicron was spreading widely.                                                                                                                                                                                                  , Under the current rules in force until Friday, all fully vaccinated travellers over the age of 12 must show proof of a negative lateral flow or PCR test taken in the two days before coming to the UK. Fully vaccinated people must also pay for a PCR test within two days of arrival and self-isolate while waiting for the result., People who aren't fully vaccinated must currently take PCR tests on both day two and day eight after arriving, and self-isolate for 10 days.                                                                                                                                                                                          , But under the new rules:                                                                                                                                                                                                                                                                                                              , People going abroad should continue to check the travel rules for their destination country.                                                                                                                                                                                                                                          , Scotland's health minister Humza Yousaf spoke of his "frustration" that the changes were announced for England only, despite UK-wide talks on what the rules should be. He said he would give an update on Thursday afternoon, while Welsh health minister Eluned Morgan said Wales would "reluctantly" align with England.           , Northern Ireland has confirmed it will also follow suit.                                                                                                                                                                                                                                                                              , Meanwhile, Downing Street said it would continue to look at what it means to be "fully vaccinated" given what is known about waning immunity. At the moment, "fully vaccinated" refers to people who have had two jabs, but in Scotland the term is now being used to mean those who have had their booster.                          , Two doses of some vaccines offer almost no protection from an Omicron infection, although they should still greatly reduce the risk of needing hospital care. But a third booster prevents around 75% of people getting any Covid symptoms.                                                                                           , Dr Sarah Pitt, virologist at the University of Brighton, said it was "sensible" to test people before they got on a plane, as about one in three people who have Covid do not have symptoms but can be infectious to others.                                                                                                          , "It's not that you're a special risk from having been travelling, but people should be testing themselves regularly anyway," she said.                                                                                                                                                                                                , PCR tests have been used for travellers as they are able to distinguish between different variants, unlike lateral flow tests.                                                                                                                                                                                                        , Asked whether the rule change could mean new variants are missed among people arriving from abroad, he said anyone who had a positive lateral flow test must get a PCR test via the NHS so it can be checked for new variants using sequencing techniques.                                                                            , Mr Shapps said the UK had a much higher level of sequencing than any other country in the world, so it was tracking new variants very carefully "regardless of whether it starts here or somewhere else".                                                                                                                             , He warned that stricter travel measures could be reintroduced if another variant of concern emerged, and earlier tweeted that the rules would be reviewed by the end of the month.                                                                                                                                                    , The travel industry welcomed the relaxation of the rules.                                                                                                                                                                                                                                                                             , EasyJet chief executive Johan Lundgren said the changes would make travel "much simpler and easier", as customers could now book and travel with "confidence".                                                                                                                                                                        , Chief executive of travel association Abta, Mark Tanzer, said it was "potentially very positive", but that damage had "already been done".                                                                                                                                                                                            , "We now hope to see confidence return as we enter what is usually the peak booking season for summer holidays," he added.                                                                                                                                                                                                             , Steve Heapy, boss of the airline Jet2, also said the timing of the announcement would make a "huge difference".                                                                                                                                                                                                                       ,  Will the changes affect your travel plans? Share your experiences by emailing haveyoursay@bbc.co.uk.                                                                                                                                                                                                                                 , Please include a contact number if you are willing to speak to a BBC journalist. You can also get in touch in the following ways:                                                                                                                                                                                                     , If you are reading this page and can't see the form you will need to visit the mobile version of the BBC website to submit your question or comment or you can email us at HaveYourSay@bbc.co.uk. Please include your name, age and location with any submission.                                                                     , David Tennant stars as an unlikely globetrotter...                                                                                                                                                                                                                                                                                    , The Highland hermit who must choose between happiness and health...                                                                                                                                                                                                                                                                   , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/uruguay/interest-rate </td>
   <td style="text-align:left;"> 2022-01-06 21:12:00 </td>
   <td style="text-align:left;"> Uruguay Hikes Main Rate to 6.5% </td>
   <td style="text-align:left;"> The Central Bank of Uruguay raised its benchmark policy rate by 75bps to 6.5% on its January 5th meeting, the highest since the return of the monetary policy rate in 2020, and anticipated further gradual rate hikes through 2022. It was the fourth consecutive hike, as the central bank aims to lower the country's inflation to the target of 3%-7%. While consumer inflation in Uruguay hit an eight-month high of 7.96% in December, the central bank has lowered the 24-month inflation projections to 6.55% from 6.97% expecting the higher borrowing costs will calm down the prices. At the same time, the monetary policy committee noted that the economic growth accelerated in the third quarter of 2021 and should continue to grow in the coming months, while unemployment has already recovered to pre-pandemic levels. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/06/stocks-making-the-biggest-moves-premarket-walgreens-bed-bath-beyond-conagra-and-others.html </td>
   <td style="text-align:left;"> 2022-01-06 21:05:12 </td>
   <td style="text-align:left;"> Stocks making the biggest moves premarket: Walgreens, Bed Bath &amp; Beyond, Conagra and others </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                          , Check out the companies making headlines before the bell:                                                                                                                                                                                                                                                                                                                                                , Walgreens (WBA) – The drug store operator's shares gained 2.9% in the premarket, after beating estimates on both the top and bottom lines for its latest quarter. Walgreens earned an adjusted $1.68 per share, compared with the $1.33 consensus estimate, boosted by demand for Covid-19 vaccinations and testing.                                                                                     , Bed Bath &amp; Beyond (BBBY) – The housewares retailer tumbled 9.3% in premarket trading, after reporting an adjusted quarterly loss of 25 cents per share compared with a consensus estimate of breakeven. Overall and comparable-store sales also fell below Wall Street forecasts.                                                                                                                        , Constellation Brands (STZ) – The spirits producer's stock initially fell 2% in the premarket after reporting earnings, before recovering that loss. Constellation earned an adjusted $3.12 per share, compared with a $2.76 consensus estimate, with sales also beating forecasts.                                                                                                                       , Conagra (CAG) – Conagra fell 1% in the premarket after missing estimates by 4 cents with an adjusted quarterly profit of 64 cents per share, although revenue was slightly above forecasts. Conagra did raise its full-year sales forecast on higher prices and strong demand for its frozen foods.                                                                                                      , Helen of Troy (HELE) – Helen of Troy shares added 2.2% in premarket trading after the household products company beat consensus estimates in its latest quarter and raised its earnings outlook. Helen of Troy reported an adjusted quarterly profit of $3.72 per share, well above the $3.11 that analysts were expecting. Results were driven by double-digit growth in housewares and beauty products., Pfizer (PFE), BioNTech (BNTX) – The CDC has recommended the use of the Pfizer/BioNTech Covid-19 vaccine as a booster shot for the 12 to 15 years old age group. The agency estimates that about half the group is fully vaccinated and that about a third of those will return for the booster shot. BioNTech rose 2.5% in premarket trading, while Pfizer was little changed.                           , Hasbro (HAS) – The toymaker named digital gaming business head Chris Cocks as its next CEO, effective February 25. He'll replace interim CEO Rich Stoddart, who has been filling that role since the death of Brian Goldner last October.                                                                                                                                                                , Coinbase (COIN) – Coinbase reversed an earlier premarket slide and rose 1%, following an upgrade to "buy" from "neutral" at BofA Securities. Coinbase initially extended yesterday's 6.4% loss after the cryptocurrency exchange operator's shares fell for four straight days as crypto prices tumbled, with losses accelerating following yesterday's release of Fed meeting minutes.                  , Datadog (DDOG) – Datadog shares added 2.2% in the premarket after the monitoring and security platform provider announced a new partnership with Amazon Web Services, which will focus on developing and tightening product alignment.                                                                                                                                                                   , ADT (ADT) – ADT lost 2.1% in premarket trading after RBC Capital downgraded the home security products provider to "sector perform" from "outperform," and cut its price target to $10 from $12 per share. RBC cites component and wage inflation, among other factors.                                                                                                                                  , Allbirds (BIRD) – The footwear maker's stock rallied 5.7% in the premarket after Morgan Stanley upgraded it to "overweight" from "equal-weight". The firm said the company's valuation is attractive relative to its peers because of a recent pullback in the stock as well as growth prospects.                                                                                                        , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                   , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                   , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                         , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                         , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                       , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-06 21:03:00 </td>
   <td style="text-align:left;"> German Inflation Rate Hits Fresh High since 1992 </td>
   <td style="text-align:left;"> Germany's consumer price inflation rate is expected to climb to 5.3 percent in December of 2021, the most since June 1992 and above market expectations of 5.1 percent, a preliminary estimate showed. The inflation rate remains well above the ECB's target of 2 percent since July 2021, due to ongoing supply issues and base effects, especially the temporary VAT reduction and the sharp decline in mineral oil product prices last year. The main upward pressure should come from energy products (18.3 percent vs 22.1 percent in November), food (6 percent vs 4.5 percent), and services (3.1 percent vs 2.9 percent). On a monthly basis, consumer prices are expected to rise 0.5 percent in December. Meanwhile, the harmonized CPI which compares with other European countries was up 5.7 percent on the year, down from the previous month’s 6 percent advance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-06 20:58:00 </td>
   <td style="text-align:left;"> German Bund Yield Surges to Highest since 2019 </td>
   <td style="text-align:left;"> Germany's benchmark Bund yield surged to -0.04%, the highest since May 2019 as investors ramped up bets for an ECB rate hike following hawkish Fed minutes on Wednesday. The latest Federal Reserve meeting minutes signaled US policymakers might raise rates as early as March, surprising markets that had thought May or June were more likely. On the data front, the national consumer price index in Germany rose by 5.3% from a year earlier in December, a new high since 1992. Still, consumer prices harmonized to make them comparable with inflation data from other European Union countries, rose 5.7% year-on-year following a record increase of 6.0% in November, the first slowdown since June. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/cotton </td>
   <td style="text-align:left;"> 2022-01-06 20:49:00 </td>
   <td style="text-align:left;"> Cotton Prices Remain Elevated Amid Supply Concerns </td>
   <td style="text-align:left;"> Cotton futures on ICE traded close to 116 USd/Lbs at the start of 2022, not far from its 9-½-year peak of 119.2 USd/Lbs hit on November 15th, and extending a 45% gain from last year amid expectations of firm demand, particularly from China and tight supplies. An urgency in obtaining the supplies and a buyout of cotton futures by hedge funds also supported the cotton market. Meanwhile, farmers in top producer India held on to production as heavy rains hit the quality of crop. Elsewhere, USDA in its latest December report estimated 2021/22 global production to drop by 200,000 bales as a 1.0 million bale drop in Pakistan more than offset gains in Benin, Turkey, Uzbekistan, and Cameroon. Moreover, world cotton ending stocks were projected 1.2 million bales lower due to lower beginning stocks, smaller production and slightly higher consumption. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/52-week-bill-yield </td>
   <td style="text-align:left;"> 2022-01-06 20:39:33 </td>
   <td style="text-align:left;"> Canada 52W Bond Yield Hits 4-week High </td>
   <td style="text-align:left;"> Canada 52 Week Government Bond Yeld increased to a 4-week high of 0.858% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/challenger-job-cuts </td>
   <td style="text-align:left;"> 2022-01-06 20:37:00 </td>
   <td style="text-align:left;"> US Job Cuts in 2021 Lowest on Record </td>
   <td style="text-align:left;"> US-based companies announced plans to cut 321,970 jobs from their payrolls in 2021, the least on record and down 86% from 2020 as employees try to retain workers faced with a record number of job quits. Company closings caused the most cuts (69,648), followed by restructuring (58,712), and market conditions (54,160). In December alone, 19,052 job cuts were announced, 28.1% above an 18-year low of 14,875 hit in November but still 75.3% less than 77,030 in December 2020. "The number of COVID cases will impact the labor market, regardless of how severe illnesses are. The main difference between COVID waves is that now much of the financial support from the government is gone, which may push workers who were leaving the workforce for child care, COVID concerns, or burnout back into the labor market. January may see more cuts due to workers’ refusal to get vaccinated, since many companies imposed deadlines for this month,” said Andrew Challenger, senior VP of Challenger, Gray &amp; Christmas. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-01-07 08:57:58 UTC +8

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
   <td style="text-align:left;"> 2022-01-07 08:57:32 </td>
   <td style="text-align:left;"> $SPY I imagine the stock market has its own +/- of money the are up. There is a software that moves money around all the time scalping traders and shit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:57:24 </td>
   <td style="text-align:left;"> $SPY Cramer is bearish now lol you bulls may get lucky lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:57:15 </td>
   <td style="text-align:left;"> $SPY it’s not a bubble it’s a faraday box </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:55:56 </td>
   <td style="text-align:left;"> $SPY Hear me out bears, what are you going to do when the Fed hikes rates and the market actually begins RALLYING…now that will be a true pivotal moment in this monster bubble </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:55:28 </td>
   <td style="text-align:left;"> $SPY Please don&amp;#39;t embarrass yourself into tomorrow.

Jobs report is a good news is bad news and bad news is bad news dealio for you now. Sell off, so.

Good jobs = abrupt end QE &amp;amp; double rate hike.

Bad jobs = Just no growth, silly 

Mediocre jobs = Well, that IS your best hope, but FED slant now Hawkish you MUST keep in mind👌

Add to your day redness and mope a bit but just don&amp;#39;t even return til the 17th Mon., let these next 2 weeks of data pass you buy, not bullish in the least bit.... 

Sooooo many silver bullets you have to dodge right now👍

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:54:49 </td>
   <td style="text-align:left;"> $SPY After Christmas and all time highs, $470 said… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:54:22 </td>
   <td style="text-align:left;"> $SPY Its not gonna stop going up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:54:17 </td>
   <td style="text-align:left;"> $SPY 

Yay bear cub </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:54:12 </td>
   <td style="text-align:left;"> $SPY $QQQ why futures is green???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:54:10 </td>
   <td style="text-align:left;"> $SPY if you’re struggling with options and need some help the premium signals tab gets plays like this all the time 🤑🤑 — link in bio of interested </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:54:07 </td>
   <td style="text-align:left;"> $SPY Runaway inflation this year. JPow does not have the nutsack to disappoint market participants. Choose the stocks that fit this thesis (I do think we reach EFFR of .75%-1% but no taper. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:54:07 </td>
   <td style="text-align:left;"> $SPY Simpcoiners causing contagion. Epic. 
 https://www.reddit.com/r/Epic_Economics/comments/rxu2nk/simpcoiners_want_more_dollars_we_all_do_they_just/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:53:27 </td>
   <td style="text-align:left;"> $SPY All bears screaming saying today was a bull trap and hope to save them puts🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:53:19 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA If tomorrow we gap up, I would take that first profit….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:53:17 </td>
   <td style="text-align:left;"> $SPY futures erased all todays negativity. Fake ass shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:53:13 </td>
   <td style="text-align:left;"> $SPY btw nfl fans i got you. Ab to arians txt pt1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:53:05 </td>
   <td style="text-align:left;"> $SPY 180/4hr wants up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:52:29 </td>
   <td style="text-align:left;"> $QQQ  Bear : waiting till morning 

$Spy  $Tesla

 Tomorrow bear turn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:52:21 </td>
   <td style="text-align:left;"> $SPY Today was bull trap day. Tomorrow we short this like Ken shorts AMC 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:51:56 </td>
   <td style="text-align:left;"> $SPY the overwhelming narrative being blasted by the media is inflation, rates, and taper. This narrative is fundamentally wrong, and ppl think rates will decrease inflation. There is a step in between, its called a recession. 

Taper will slowly raise bond yield rates, but will not reduce inflation. This will just drive the economy to another stimulus. 

They cant reduce the money supply to increase the money supply value, that will crash asset prices. 

Really the only thing they can do is decrease the debt ceiling bu fiscally paying off debts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:51:35 </td>
   <td style="text-align:left;"> $SPY futes limping! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:51:22 </td>
   <td style="text-align:left;"> $SPY Make Bears poor again… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:51:22 </td>
   <td style="text-align:left;"> $SPY $TSLA $GME $AMC Just sharing some stock porn 💋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:51:20 </td>
   <td style="text-align:left;"> $SPY Futes rippin and 10 year now droppin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:51:06 </td>
   <td style="text-align:left;"> $SPY how is that 10 year old yield looking? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:50:59 </td>
   <td style="text-align:left;"> $SPY just dont stop. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:50:52 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:50:42 </td>
   <td style="text-align:left;"> $SPY melt down started </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:50:11 </td>
   <td style="text-align:left;"> $SPY this will never recover </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:50:06 </td>
   <td style="text-align:left;"> $SPY $QQQ jobs report hits tomorrow sleep tight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:48:55 </td>
   <td style="text-align:left;"> $SPY over 12hrs before any futures matter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:48:52 </td>
   <td style="text-align:left;"> $SPY bulls need a vet tmrw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:48:35 </td>
   <td style="text-align:left;"> $SPY Not a meme </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:48:33 </td>
   <td style="text-align:left;"> $SPY bears r screwed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:48:33 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ in nikola tesla&amp;#39;s last letter to his mom, he said &amp;quot;All these years that I had spent in the service of mankind brought me nothing but insults and humiliation&amp;quot;  
rest in peace nikola </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:48:12 </td>
   <td style="text-align:left;"> $SPY these bears gonna look great on my walls tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:47:57 </td>
   <td style="text-align:left;"> $SPY this place is filled with counterfeit dildos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:47:50 </td>
   <td style="text-align:left;"> $SPY carnage tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:47:47 </td>
   <td style="text-align:left;"> $SPY can you try to be professional. Take the shades off wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:47:46 </td>
   <td style="text-align:left;"> $SPY I could not think of less bullish scenario then spy dipping nearly 2%, recovering zero and AMC, GME, DKNG, HOOD, BTC all trending with Econ data tomorrow and hawkish Fed.  If it rips I’ll go bullish but just a shitty setup </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:47:31 </td>
   <td style="text-align:left;"> $SPY hold on to those puts bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:47:17 </td>
   <td style="text-align:left;"> $SPY we will open red tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:47:11 </td>
   <td style="text-align:left;"> $SPY Xi fucking rocked Trump big time.  So much for the Trade War... Is Trump or Trade War around anymore?

The greatest victory is that which requires no battle.
Sun Tzu, The Art of War

Wuhan strain to set it off and Omicron to end it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:47:09 </td>
   <td style="text-align:left;"> $SPY and $UVXY https://www.google.com/amp/s/www.cnbc.com/amp/2022/01/06/cramer-says-its-too-early-to-buy-aggressively-after-rough-2022-start.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:47:03 </td>
   <td style="text-align:left;"> $SPY spy going straight to 474 tomorrow. Unreal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:46:52 </td>
   <td style="text-align:left;"> $SPY autobid futes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:46:51 </td>
   <td style="text-align:left;"> Ticker: $SPY 
Buy: January 10, 2022 $468.00 Calls 
Entry Price: $2.75 - $2.75 
Exit Price: $3.60 
Stop Loss: $2.42 
Potential ROI: 31% 
Estimated Hold Time: 52 Minutes 
Alert Courtesy Of: https://www.fastscalp.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:46:30 </td>
   <td style="text-align:left;"> $SPY I kind of wish that God would put a couple of point&amp;#39;s into lethality for the next covid variant. That way we can get rid of some of these arrogant anti-vaxxers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:46:25 </td>
   <td style="text-align:left;"> $SPY couple in really strong data and degenerates chasing AMC/GME, futes have to be manipulated to cushion the sell off tomorrow… daytraders will not be holding this over the weekend.. some green tomorrow I guess but much more red imo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:46:02 </td>
   <td style="text-align:left;"> $SPY who’s all excited now but Futs don’t matter 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:45:53 </td>
   <td style="text-align:left;"> $BXRX this just doesn’t make sense to me. I mean I was saying a similar thing about $KPRX , ran soon after 150% . 
BXRX trading at 21 cents had news of a 6 month extension December 16th. It just completed a small direct offering at 33 cents a share. News conference next week. 17.7 mil market cap. Such a low market cap and such a low market price. Seems to go to be true to me. Watching closely. Just my opinions
Will watch indices $SPY $IWM $QQQ as well, however this is undervalued regardless I believe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:44:57 </td>
   <td style="text-align:left;"> $SPY haha didnt even realize if you shake trading view on your phone then it snows

Loll its the little things </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:44:54 </td>
   <td style="text-align:left;"> $SPY and $UVXY 👀https://www.google.com/amp/s/www.barrons.com/amp/articles/fed-minutes-stock-market-turmoil-ahead-51641426580 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:44:52 </td>
   <td style="text-align:left;"> $SPY I’m outside Powell window, he will know the reference lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:44:45 </td>
   <td style="text-align:left;"> For those keeping track it&amp;#39;s still a doji $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:44:38 </td>
   <td style="text-align:left;"> $SPY 

Huh? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:44:15 </td>
   <td style="text-align:left;"> $SPY FUTURES UPDATE FOR THE SHORTS

👇👇👇👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:44:11 </td>
   <td style="text-align:left;"> $SPY I jumped too </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:44:07 </td>
   <td style="text-align:left;"> $SPY Just stop , bulls, you&amp;#39;re climbing a bridge.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:43:55 </td>
   <td style="text-align:left;"> $SPY 60% of 2021 gdp was SPY calls printing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:43:52 </td>
   <td style="text-align:left;"> $SPY the data tomorrow is so bullish for bears your gonna have an insta sell event because tapering and interest rates are gonna move just that much faster.. under Biden, he’s created the strongest recovery ever.. Ridiculous I know but thats how they’re rigging the numbers to justify no more QE … don’t worry bulls, the pain will be transitory 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:43:51 </td>
   <td style="text-align:left;"> $SPY lol those bulls. Last night this board was full of bear shet but as expected it went in a bit different way 😂 You should be concerned about such pump into unemployment and jobs reports.
(No position, no bias) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:43:45 </td>
   <td style="text-align:left;"> $SPY $SPX 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:43:28 </td>
   <td style="text-align:left;"> $SPY Hopefully Futes give a boost to AMC and GME for a better short entry. They no longer have negative betas so it makes sense. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:43:25 </td>
   <td style="text-align:left;"> $SPY More Fear Please 🍺🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:43:15 </td>
   <td style="text-align:left;"> $SPY $UVXY https://www.google.com/amp/s/www.cnbc.com/amp/2022/01/06/the-fed-is-scaring-markets-with-the-triple-threat-of-policy-tightening.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:42:57 </td>
   <td style="text-align:left;"> $SPY #NFLX $AAPL #GOOGL   #FB #AMZN   
 
caution under the ichimoku cloud for Cheese Omelettes. 
 (trend is bearish under cloud, bullish above, per ichimoku rules) 
It&amp;#39;s been years since these names been under cloud for more than a coffee. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:42:47 </td>
   <td style="text-align:left;"> $SPY getting paid tomorrow 🤑🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:42:35 </td>
   <td style="text-align:left;"> $SPY  Man o Man.... 480 ny EOD would be a dream come true. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:42:33 </td>
   <td style="text-align:left;"> $SPY is this the strongest futes of the year? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:42:31 </td>
   <td style="text-align:left;"> $SPY Futes are rippin! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:42:29 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:42:27 </td>
   <td style="text-align:left;"> $SPY Unless your buying long dated Puts, close those dailys out so you avoid the fuckery (like tonight) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:42:18 </td>
   <td style="text-align:left;"> $SPY looking like a bearflag on the 4hr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:42:08 </td>
   <td style="text-align:left;"> $SPY payday tomorrow bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:41:54 </td>
   <td style="text-align:left;"> $SPY at the rate AH’s is going… we should open tomorrow above $490 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:41:40 </td>
   <td style="text-align:left;"> $SPY Oil telling you all you need to know, $4 gas sooner than you think.
.*national average 

&amp;#39;Course the 2 yr and TIPS not a bad 2bd either. 

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:41:36 </td>
   <td style="text-align:left;"> $SPY pretty clear algo on futes right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:41:20 </td>
   <td style="text-align:left;"> $SPY 

Yep....

&amp;quot;Jackson Health System in Miami on Wednesday announced that the hospital had 468 covid patients, although about 50 percent were admitted primarily for reasons not related to covid&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:41:14 </td>
   <td style="text-align:left;"> $SPY non farm payroll and other economic data being released in the morning. Let&amp;#39;s see what that brings. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:40:59 </td>
   <td style="text-align:left;"> $SPY the best part of the bear cycles are the elevator rides down out of nowhere </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:40:52 </td>
   <td style="text-align:left;"> $SPY inflation adjusted GDP negative </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:40:51 </td>
   <td style="text-align:left;"> $SPY  your mom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:40:48 </td>
   <td style="text-align:left;"> $SPY wow retail job is fun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:40:42 </td>
   <td style="text-align:left;"> $SPY, $QQQ big movement AH…price moving higher AH than regular session. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:40:41 </td>
   <td style="text-align:left;"> $SPY 

Wow does this about say it all.  The scare tactics are hilarious.  But smart folks know the truth.  

&amp;quot;Officials at CarePoint, which operates three hospitals in northern New Jersey, say their surge of covid patients has included a significant increase in those with secondary diagnoses. Such patients make up slightly less than half of patients on the hospitals’ wards. Some are completely unrelated, such as a girl who fell on a playground and broke her arm but tested positive with mild symptoms of covid.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:40:25 </td>
   <td style="text-align:left;"> $SPY @DrabooD always taught me to stack your calls on the red days, take your vitamins, and pray like hell before you go to sleep for ATH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:40:14 </td>
   <td style="text-align:left;"> $SPY go to sleep bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:40:07 </td>
   <td style="text-align:left;"> $SPY 3% correction? Not buying it.  I have trust issues when it’s less than 5%

Short covering into jobs report more likely 

$460 woulda been a great buy based on trend 

Jobs report will be solid.  But that just gives green light to Fed rate hikes.  

I said last week 479-480 was top.  We bounced nicely right above 50 SMA.  But never trust the first bounce. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:39:43 </td>
   <td style="text-align:left;"> Don&amp;#39;t let your guard down and keep scanning for RS stocks on a daily basis... 
 
$SPY  $DJIA $IWM $IWO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:39:39 </td>
   <td style="text-align:left;"> $QQQ $SPY glad I sold my puts! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:39:34 </td>
   <td style="text-align:left;"> $GME =====&amp;gt; MY FELLOW APES... I&amp;#39;M BACK WITH MY BABY RIGHT HERE.... BACK TO  $400s  WE GO ... ALL THE WAY IN!!! 😳🤑😎🔥💥🚀🚀 
. 
$SPY  $AMC  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:39:25 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:39:22 </td>
   <td style="text-align:left;"> $SPY you didnt like it during cash session but cant get enough after hour when there&amp;#39;s no volume? Who&amp;#39;s actually falling for this shit? Lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:39:20 </td>
   <td style="text-align:left;"> $SPY bear fag on the charts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:39:00 </td>
   <td style="text-align:left;"> $SPY: The long term trend is positive and the short term trend is neutral. Lets see where this goes. https://www.chartmill.com/stock/analyzer/stock/SPY?key=84303b30-e7bc-44d7-b0b1-1493858db9a2&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=SPY&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:37:56 </td>
   <td style="text-align:left;"> $SPY 

Anyone here use TradeZero for shorts? 

How do you like it? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:37:56 </td>
   <td style="text-align:left;"> Just released via Cathie Wood Twitter “Jim Cramer is a meme. You think Brandon is bad, he’s worse. Leading many into terrible positions only to flip flop weeks later. Con artist using a big platform to prey on the uninformed. No one should take him seriously.” 
Disclaimer, not an actual quote. Don’t sue me. $DKNG $SOFI $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:37:43 </td>
   <td style="text-align:left;"> $SPY We are off 2% from a record ATH and you’re all talking about a crash…retail is hilarious 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:37:38 </td>
   <td style="text-align:left;"> $SPY $TWTR $REDDIT.P lez be honest tho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:37:30 </td>
   <td style="text-align:left;"> $SPY idk. I still say chart is bearish. 🤷‍♂️daily MACD red rsi under/testing 50 sitting on the 20ema 🤷‍♂️ we will see. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:37:29 </td>
   <td style="text-align:left;"> $SPY 5 hr to gunna </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:37:10 </td>
   <td style="text-align:left;"> $SPY this is what all this hoorah is about. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:36:50 </td>
   <td style="text-align:left;"> The distribution of VIX over the past decade. 

After the 2009 market crash, it took 4-5 years for the VIX to settle down. The COVID crash was an investment opportunity, it takes a while until VIX settles down. On its way down, we keep making new ATH. 
 
$VIX  $SPY $SPX $QQQ $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:36:42 </td>
   <td style="text-align:left;"> $SPY all naturales </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:36:31 </td>
   <td style="text-align:left;"> $SPY $GME Apes are master businessmen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:36:29 </td>
   <td style="text-align:left;"> $SPY CRAMER is a Troll </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:36:28 </td>
   <td style="text-align:left;"> $SPY bears win tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:36:27 </td>
   <td style="text-align:left;"> $SPY 480 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:36:27 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:36:25 </td>
   <td style="text-align:left;"> $SPY without the fake set back of oil with the phony release of crap sour oil, oil would be approaching 95-100 barrel. Inflation is still rampant. Low value money supply continues to circulate, fueling an inflation cycle where products go up, wages go up, business goes out, cost to mfg goes up, products prices go up. This will continue until money supply value rises. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:36:04 </td>
   <td style="text-align:left;"> $SPY bears will absolutely lose tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:35:39 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:35:32 </td>
   <td style="text-align:left;"> $SPY I’ve played both sides this week … bulls taking the W tomorrow.. maybe end of day bears get a sell off but they gonna pressure cook retail bears tonight and watch it explode a fat nut in their faces tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:35:14 </td>
   <td style="text-align:left;"> $SPY everyone done freaking out for the 10000th time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:34:59 </td>
   <td style="text-align:left;"> $SPY whether you’re a bear or bull…I think we can all agree that Cramer needs to just shut. the. fuck. up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:34:58 </td>
   <td style="text-align:left;"> $SPY clear skies ahead 😍😍😍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:34:55 </td>
   <td style="text-align:left;"> $SPY sucks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:34:47 </td>
   <td style="text-align:left;"> $SPY Gme done siphoning tomorrow all Stonks green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:34:36 </td>
   <td style="text-align:left;"> $SPY waiting and watching if they somehow turn this short term bear flag into a btd just like a gazillion times in the past </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:34:33 </td>
   <td style="text-align:left;"> $SPY EZPZ up tomorrow and next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:34:32 </td>
   <td style="text-align:left;"> $SPY let’s break $470 before after hours closes bitches </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:34:13 </td>
   <td style="text-align:left;"> $SPY ready for the zap candle and the spy board to be a sea of red laughter. Will start with a few. What was that posts. Followed by maybe it will bounce back. Then hopelessness. Tomorrow a few porn pics from some booger eater trying to get his stocktwits account t deleted cuz he was all in calls. Happy Friday! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:34:04 </td>
   <td style="text-align:left;"> $SPY FRIDAY, JAN. 7     
8:30 am Nonfarm payrolls Dec.  422,000 210,000
8:30 am Unemployment rate Dec.  4.1% 4.2%
8:30 am Average hourly earnings Dec.  0.4% 0.3%
10 am San Francisco Fed President Mary Daly speaks on a panel at AEA meetings    
12:15 pm Atlanta Fed President Raphael Bostic speaks about the economy at AEA meetings    
3 pm Consumer credit Nov.  $20 billion </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:33:55 </td>
   <td style="text-align:left;"> $SPY $QQQ Skip to minute 13. You need to own assets that inflate not to get rich but just to not lose as the currency is devalued. That is the primary driver of the up only market the money illusion.

With the US government needing 30% of its debt monetized to keep its funding costs down we have a Fed balance sheet at $8-9 trillion of the $30 trillion debt. With projections of $140 trillion in debt by 2050 needing 30% or $40 trillion in monetization to keep funding costs down expect the Fed balance sheet to continue to explode as they jawbone the public into thinking they will pull back as prices hit non-stop record highs over the coming decades.

https://youtu.be/MFO6OtnmEDo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:33:47 </td>
   <td style="text-align:left;"> $SPY diamond top reversal 🧸🐻‍❄️🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:33:28 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $IWM About this pullback...Is it...
1) a kneejerk reaction to the hawkish FOMC-minutes or
2) a market correction in the making
IMHO, if it&amp;#39;s (2) then there is not enough blood/panic yet to get to the bottom...meaning there&amp;#39;s more room to go down...sigh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:33:28 </td>
   <td style="text-align:left;"> $SPY Christ you bears are hell. You base your moves off fundamentals ONLY when it’s convenient for you. Otherwise, all you say is “Bulls suck” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:33:15 </td>
   <td style="text-align:left;"> $SPY the news stopped reporting on covid deaths? Do they no longer care about dead people?

😃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:33:14 </td>
   <td style="text-align:left;"> $RBLX $SE $WKEY $CEMI $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:33:10 </td>
   <td style="text-align:left;"> $SPY RIP 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:32:46 </td>
   <td style="text-align:left;"> $SPY send this fuck!!!!! 477 one more time I want cheap puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:32:34 </td>
   <td style="text-align:left;"> $SPY we going to the moon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:31:43 </td>
   <td style="text-align:left;"> $SPY would not be surprised to gap up to 477+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:31:23 </td>
   <td style="text-align:left;"> $SPY time to start talking about reduced productivity, reduced GDP, terrible Q1s across the board for many of USA&amp;#39;s largest companies.  

https://www.msn.com/en-us/news/us/in-the-nation-s-hospitals-this-covid-wave-is-different/ar-AASvF91?ocid=uxbndlbing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:31:18 </td>
   <td style="text-align:left;"> $BFRI everyone saying the lowest it could go! What about the highest! It’s FK’n $22!
Where bulls and act like one!
Low floater with ZERO shares available at 155% short fee! Buy them up and lower your average!
The name of the game is buy low and sell high😉 want to make money, change your attitude! $GME $AMC $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:31:17 </td>
   <td style="text-align:left;"> $SPY me not giving a shit about futures. I watched game pump and know what happens next. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:31:16 </td>
   <td style="text-align:left;"> $SPY 

Bears who thought market crash coming tomorrow: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:31:15 </td>
   <td style="text-align:left;"> $SPY same game, now for bulls - do not get too excited </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:31:13 </td>
   <td style="text-align:left;"> $SPY these futures are wildin 😅🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:31:13 </td>
   <td style="text-align:left;"> $SPY The fact that the Fed hasn’t even set a definite date regarding quantitative tightening should tell you that they’re full of shit. They also have no idea what they’re doing. If you have taken intro to macro then I consider you as an equal to the average Fed governor. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:31:10 </td>
   <td style="text-align:left;"> $SPY $DWAC So Jerome Powell already admitted inflation is not transitory.  Can someone please explain why we still have interest rates at 0% at least until March?  Why not raise right now?  Two more months to let inflation rip and when March comes they are only doing a 0.25% increase.  0.25% won’t do anything to stop inflation and it takes a while for the rate increases to filter into the economy.  So Jerome Powell is basically letting inflation run wild on purpose.  This is the worlds biggest tax, Joe Biden doesn’t have to raise our taxes to raise our taxes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:30:55 </td>
   <td style="text-align:left;"> $SPY bulltrap in the morning. Sleeping well tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:30:46 </td>
   <td style="text-align:left;"> $SPY So the &amp;quot;Polar Vortex&amp;quot; spent most of 2021 in the Antarctic. Coldest Winter on record - Even the Climate Change fanatics admit it (cause of Science and the Data).

Now its North America&amp;#39;s turn for the &amp;quot;Polar Vortex&amp;quot; express. the three month forecasts are for higher than average precipitation (just ask California) and below average temperatures.

Looks like a Reversion to the Mean - just like trading stocks. To all my peeps in New England - grab the snow shovels and plows, Winters coming (starting tonight).

https://www.cnn.com/2021/10/09/weather/weather-record-cold-antarctica-climate-change/index.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:30:43 </td>
   <td style="text-align:left;"> $SPY you bulls are a bunch of cock suckers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:30:38 </td>
   <td style="text-align:left;"> $SPY

Futures are moving recklessly high!!!

💵👍🙂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:30:09 </td>
   <td style="text-align:left;"> $SPY today opened at 469.91 then 30 minutes later was 466.09. Tomorrow will be the same except in 30 minutes it’ll be 463 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:29:44 </td>
   <td style="text-align:left;"> $SPY poor bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:29:42 </td>
   <td style="text-align:left;"> $SPY The end of active trading today is really winding up for a ________ tomorrow to you, bulls; you just not heeding the FED warning Wed.

Tutes gon have to reign you in, they will do it SOMETIME in the next week. 

Mark. This. Post. 

LOL, too, $BAC downgraded fellow investment bank, $GS , and... that&amp;#39;s 100% right, we&amp;#39;ll find out at GS&amp;#39; ER they bet WRONGLY on the market going up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:29:38 </td>
   <td style="text-align:left;"> $SPY tomorrow is going to be too good. Huge gapper up ⬆️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:29:37 </td>
   <td style="text-align:left;"> $SPY oil is going to break the previous high </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:29:32 </td>
   <td style="text-align:left;"> $SPY 470 gonna slap you bulls back down so hard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:29:20 </td>
   <td style="text-align:left;"> $SPY I don’t trust fridays </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:28:48 </td>
   <td style="text-align:left;"> $SPY bear stew </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:28:45 </td>
   <td style="text-align:left;"> $SPY $ES_F  FUTURES RIPPING! LIMIT UP! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:28:30 </td>
   <td style="text-align:left;"> $SPY AH hopium for trapped bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:28:26 </td>
   <td style="text-align:left;"> $DJIA $SPY $SPX 
I know futures don&amp;#39;t usually matter at this time of day but, Sunday/Monday and Friday are a little different. Futures are on the move and it&amp;#39;s free money Friday tomorrow. If you are all in short don&amp;#39;t worry just say your prayers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:28:20 </td>
   <td style="text-align:left;"> $SPY held long overnight. Guess that was the right move. Won’t go against it until things really shift </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:27:59 </td>
   <td style="text-align:left;"> $SPY still going up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:27:20 </td>
   <td style="text-align:left;"> $SPY, $QQQ, $AMZN, $NVDA let’s go!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:27:08 </td>
   <td style="text-align:left;"> $SPY ES got stuck at this level last night too </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:27:02 </td>
   <td style="text-align:left;"> $SPY damn that’s a lot up AH. She’s about to rip back to 474 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:27:01 </td>
   <td style="text-align:left;"> $SPY tomorrows green, in calls. Going to try to catch the top and go for some outs a month out. Play what’s in front of you. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:26:47 </td>
   <td style="text-align:left;"> $SPY 👍🏻📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:26:42 </td>
   <td style="text-align:left;"> $SPY 
I personally want the volatility tomorrow. Seems like a set up where I can make money off both puts and calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:26:41 </td>
   <td style="text-align:left;"> $SPY It will kiss $470 Al, 

Then BOOM 🧨  puts will, print 

RIP John Madden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:26:34 </td>
   <td style="text-align:left;"> ”Hey babe, what you doing?” Replied “Watching the fight!” $SPY $UVXY $SPXS $NDX $SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:26:30 </td>
   <td style="text-align:left;"> $SPY uffff </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:26:21 </td>
   <td style="text-align:left;"> $SPY Come on you fat mother fucka Let it RIP!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:26:09 </td>
   <td style="text-align:left;"> $SPY a gap up tomorrow and 473 would be real nice </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:26:03 </td>
   <td style="text-align:left;"> $SPY Puts for Mon or Wed 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:25:51 </td>
   <td style="text-align:left;"> $SPY lol everyone already know tmrws close when a potential continuation down doesn’t even get decided until we retrace into that first drop completely — someone pass me that 🔮 nah, I’ll trade what I see when in the morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:25:50 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:25:50 </td>
   <td style="text-align:left;"> $CFVI $SPY Added note as well, I would not be over playing your cards now. The fed mentioned interest rates will rise this year so keep that all in mind and do not overextend. Stick to quality over quantity for now until the market correction occurs. I believe it will correct at least 80-120 points. If lockdowns were to happen again which does not seem likely for now 150-200 point correction would happen in my view. Be cautious but there is still plays here just stick to quality for now 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:25:40 </td>
   <td style="text-align:left;"> T bills $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:25:37 </td>
   <td style="text-align:left;"> $SPY Futes be popping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:25:27 </td>
   <td style="text-align:left;"> $SPY Cocaine futes bulls engaged. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:25:19 </td>
   <td style="text-align:left;"> $SPY futures already at the 50MA. Boolish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:25:19 </td>
   <td style="text-align:left;"> latexa8395b0e88e064eb0c1854f5b3915a2cQQQ
$DIA
Date Courtesy : Stock Trader&amp;#39;s Almanac 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:25:04 </td>
   <td style="text-align:left;"> $SPY The market knows exactly how to get the Fed to make decisions that benefit it. If you don’t think JPow is looking at this ~2% pullback from ATH and thinking “Oh no what have I done I mustn’t upset the glorious market”, then you are mistaken. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:25:00 </td>
   <td style="text-align:left;"> $SPY some genius posted about dark money earlier. Doesn&amp;#39;t seem to be bullish yet? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:24:46 </td>
   <td style="text-align:left;"> $SPY puts be gone bro </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:24:42 </td>
   <td style="text-align:left;"> $SPY back to 480 in a jiffy, 500 on deck. Give it a few weeks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:24:13 </td>
   <td style="text-align:left;"> $SPY $ADBE $NFLX $U $FB 

Reminder </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:24:11 </td>
   <td style="text-align:left;"> $SPY 470 support reclaimed fuck ya puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:23:34 </td>
   <td style="text-align:left;"> $SPY all I know CHWY is falling off a Cliff soon ! ⬇️ 💰💰💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:23:31 </td>
   <td style="text-align:left;"> $SPY  people take politics so seriously here  Deep down, I do believe that ST Citizens are very polite and smart in real life. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:23:00 </td>
   <td style="text-align:left;"> $SPY isn’t it time they get rid of day trade rules? I can’t think of a time it ever helped me but whenever I get fked it’s always in the equation. It’s made to rape people with only couple grand </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:22:57 </td>
   <td style="text-align:left;"> $SPY ripping hard omg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:22:53 </td>
   <td style="text-align:left;"> $SPY stock analysis before market opens tomorrow 

https://youtu.be/dEtYsWDFGEU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:22:44 </td>
   <td style="text-align:left;"> $SPY $SPX Let’s see who runs this shit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:22:19 </td>
   <td style="text-align:left;"> $SPY bear market go away buy your puts another day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:22:13 </td>
   <td style="text-align:left;"> $SPY everything made in China and backed by Simpcoin debts. Contagion. take the loss. Get out and get some sleep. You’ll feel better. Avoid the FALLOUT contagion.  Here to help. 
 https://www.tradingview.com/chart/BTCUSDT/zJjExszC-Bitcoin-Double-Topped-Blowoff-Defi-Ponzied-Squid-Game/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:22:11 </td>
   <td style="text-align:left;"> $SPY What would it take for @Stocktwits to host a convention? 🤔 Guest speakers, vendor booths, merch, and all the cool Stocktwits users could link up and party. I know personally I would make a trip for that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:22:09 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:22:04 </td>
   <td style="text-align:left;"> $SPY I’ll give my opinion once. The whole capital riots were dumb. Just as dumb as all the other riots that happened all year. The only reason the capital riots are prosecuted is because and only because, it affected those in power. This is not a race war. Or even a wealth war. It’s a struggle for control. That’s why “they” tell you it was an assault on democracy. That’s all. It’s sickening that race and other hot ticket items are used by the political corporatocracy to further thier control. It’s a slap in the face really.  Politicians are trash. Never forget that. No one has any right to tell you what to do or how to live your life. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:21:21 </td>
   <td style="text-align:left;"> $SPY …I’d love to think we can end tomorrow slightly higher.  Maybe 470.

These folks don’t agree, but they’re often way wrong.

GLTATraders, LT &amp;amp; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:21:14 </td>
   <td style="text-align:left;"> $SPY what should I eat for dinner? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:21:13 </td>
   <td style="text-align:left;"> $SPY no one should trust futures at this point so bipolar to what it does at market open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:21:02 </td>
   <td style="text-align:left;"> $SPY if only spy could jump 30 bucks like $GME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:20:48 </td>
   <td style="text-align:left;"> $SPY Heads up, this indicator doesn&amp;#39;t turn red that often, but when it does, it has my full attention. This is on weekly it computes volume, currently price is below my weekly pivot of 470.60, I expect price action to retest that area, maybe it will hang on maybe it won&amp;#39;t if it doesn&amp;#39;t, I&amp;#39;ve put my weekly pivots below...

467.27
459.25
453.08
443.91
431.28 ~10%
.
.
.
383.63 ~20%
there aren&amp;#39;t any weekly pivots in the 15% around 407.xx

$IWM has been red for a minute, but $DJIA and $QQQ  just turned red this week too </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:20:23 </td>
   <td style="text-align:left;"> $SPY when Asian and China open these will retrace fast 
471 max pain tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:20:11 </td>
   <td style="text-align:left;"> $SPY told y’all BTMFD everytime off the 50dma after most recent ath’s !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:19:56 </td>
   <td style="text-align:left;"> $SPY the current market is like a hot wing hoagie without ranch or blue cheese </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:19:42 </td>
   <td style="text-align:left;"> $SPY who’s the biggest GOAT here??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:19:21 </td>
   <td style="text-align:left;"> $SPY 3x rate hike all known fact, tapering known fact, shrinking balance sheet not until after 1st rate hike check. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:19:19 </td>
   <td style="text-align:left;"> $SPY im swinging 5 467p exp 1/7 wish me luck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:19:10 </td>
   <td style="text-align:left;"> $SPY one shot closer to that free pizza

https://www.cnbc.com/2022/01/06/moderna-ceo-says-people-may-need-fourth-covid-shot-as-efficacy-of-boosters-likely-to-decline-over-time.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:19:02 </td>
   <td style="text-align:left;"> $SPY bet your bottom dollar that tommmooorrrroooow there will be sunshiiinnnnee </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:18:55 </td>
   <td style="text-align:left;"> $SPY text book </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:18:54 </td>
   <td style="text-align:left;"> $SPY Inflation ripping! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:17:58 </td>
   <td style="text-align:left;"> $SPY 20% interest rates would be cool. 
 
Or 30% inflation would be cool too. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:17:54 </td>
   <td style="text-align:left;"> $SPY 450 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:17:34 </td>
   <td style="text-align:left;"> $SPY  Oh My Puts.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:17:32 </td>
   <td style="text-align:left;"> $SPY we ain&amp;#39;t out the water yet, trade accordingly.  Good luck to all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:17:07 </td>
   <td style="text-align:left;"> $SPY here comes the futures smack down soon 🔜 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:17:03 </td>
   <td style="text-align:left;"> Making the dollar stronger in the short term wouldn’t be the worst thing consumer cost go down stocks go on sale and if you have extra cash on the side you can bulk up your long term position for the next bull cycle it’s all about how you strategize it and prepare $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:17:01 </td>
   <td style="text-align:left;"> $SPY if you have a ton of puts might want to hedge overnight, try those mini futes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:16:57 </td>
   <td style="text-align:left;"> $SPY $SPX The Goat speaks 
The Zoltan
https://plus2.credit-suisse.com/6f8d2b00-2bef-43de-a288-b5038ac1cd58 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:16:56 </td>
   <td style="text-align:left;"> $PTON Peloton Interactive Stock Isn’t a Stay-at-Home Play, Irrespective of the Omicron Variant 
Hedge Funds Are Selling Peloton 
Market $SPY $QQQ selling losers $PTON </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:16:54 </td>
   <td style="text-align:left;"> $SPY at least 20% correction this year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:16:47 </td>
   <td style="text-align:left;"> $SPY lmao tooooo many bears are pleading their case here , which only means one thing…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:16:43 </td>
   <td style="text-align:left;"> $TSLA https://twitter.com/divestech/status/1479170138909954055?s=21 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:16:38 </td>
   <td style="text-align:left;"> $SPY These futures are crazy... they need to maintain upward momentum at all costs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:16:22 </td>
   <td style="text-align:left;"> $SPY 480 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:16:16 </td>
   <td style="text-align:left;"> $SPY promising but not convinced </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:16:14 </td>
   <td style="text-align:left;"> $AAPL  hike rates and fed news subside soon, possibly Tomrrow? . These fool that sell, feel the regret soon.  Bears don’t understand, when it drop is a gift for bulls to load up! After 2 days it drop 10$ expect 175-180 soon. Bears lock your gains before to late ! The curve of macd and stochasticSlow is bullish $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:16:05 </td>
   <td style="text-align:left;"> $SPY man I’m gonna laugh if they take us back to ATH tomorrow lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:15:57 </td>
   <td style="text-align:left;"> $SPY not getting excited yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:15:50 </td>
   <td style="text-align:left;"> $SPY 474 tomorrow. Monday back to 468 for double bottom then test all time high after </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:15:48 </td>
   <td style="text-align:left;"> $SPY my bear patience is running out … last short here before I watch this rally 2% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:15:40 </td>
   <td style="text-align:left;"> $SPY bear flag </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:15:32 </td>
   <td style="text-align:left;"> $SPY JUST IN:

The number of Nasdaq stocks down 50% or more is almost at a record for the stock market. 

The bubble has deflated </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:15:11 </td>
   <td style="text-align:left;"> $SPY holy shit balls are we looking at 2% day tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:15:08 </td>
   <td style="text-align:left;"> $SPY where is @realness365 

🧐👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:14:49 </td>
   <td style="text-align:left;"> $SPY 

Nature </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:14:20 </td>
   <td style="text-align:left;"> $SPY dump it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:14:16 </td>
   <td style="text-align:left;"> $SPY $TSLA everybody wants the market to just fly like a rocket ship. But in reality its less rocket and more like a surfer. Just ride the waves </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:14:09 </td>
   <td style="text-align:left;"> $SPY My grandfather is extremely upset over what Kamala Harris said comparing Jan 6th to Pearl Harbor. He was there and today is 100 years old. He’s sad that a VP said that and he lives today with the memory of his friends who died that day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:14:03 </td>
   <td style="text-align:left;"> $SPY 50% retracement up Fibonacci says so! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:14:00 </td>
   <td style="text-align:left;"> $SPY carnage tmrw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:13:53 </td>
   <td style="text-align:left;"> $SPY 
TLT bounce ... from Fed printing ! 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:13:44 </td>
   <td style="text-align:left;"> $SPY The option chain looks very freaking. Are they going to kill option trading this way? That sucks/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:13:42 </td>
   <td style="text-align:left;"> $SPY where are we now.  I am liquidating reluctantly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:13:41 </td>
   <td style="text-align:left;"> $SPY classic bear flag </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:13:37 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:13:28 </td>
   <td style="text-align:left;"> $SPY … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:13:24 </td>
   <td style="text-align:left;"> $SPY This is bullish.

https://babylonbee.com/news/businesses-requiring-positive-covid-test-as-proof-of-vaccination </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:13:18 </td>
   <td style="text-align:left;"> $SPY Bulls are hammering the futures because 2% from ATH is an incredible entry point amid Fed tapering and upcoming rate hikes.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:12:31 </td>
   <td style="text-align:left;"> $SPY what futures gonna do? Bounce off ceiling all night and crash in morning 💥 goodnight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:12:24 </td>
   <td style="text-align:left;"> $SPY Dangerous game for shorts around earnings , learned my lessons 😆 🤣 .

Need to keep an eye on pop n drop earnings,  if that happens , we may not be having a very bullish spring </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:12:16 </td>
   <td style="text-align:left;"> $SPY Lol at anyone who thought  student loans would be forgiven. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:10:40 </td>
   <td style="text-align:left;"> $SPY Remember when it was the evil, rushed Trump vaccine? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:10:35 </td>
   <td style="text-align:left;"> $SPY think of next week ! This bullishness will wear off real quick ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:10:21 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Nothing here, until 8:30 AM EST tomorrow, where you will have the single most &amp;quot;moving&amp;quot; NFP jobs report you seen in quite some time, peeps.

Position yourselves well, peeps. 

Hot means FED will tighten very soon.

Cold means FED will have more luxury time they feel to be cautious with rates but that&amp;#39;ll all last all of the weekend as CPI hammers home s&amp;#39;more sweet inflationary reality early next week w/ PPI &amp;amp; retail sales to follow.

And then, you&amp;#39;re in luck!  PCE Deflator CORE gov&amp;#39;t inflation #s grace us  the following week. 

So, bulls, this is all to say, pick your </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:10:16 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $MSFT $TSLA 

If hedged funds and CEO&amp;#39;S are selling..

 fck this 💩

I&amp;#39;m loading PUTS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:10:04 </td>
   <td style="text-align:left;"> $SPY what is a bear flag? What’s that pattern? 🤷‍♂️👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:09:52 </td>
   <td style="text-align:left;"> $SPY new ATHs coming 🚀🚀🚀😍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:09:50 </td>
   <td style="text-align:left;"> $SPY haaaa who’s holding puts overnight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:09:27 </td>
   <td style="text-align:left;"> $SPY Don&amp;#39;t tell me you shorted in the hole , did you? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:08:57 </td>
   <td style="text-align:left;"> $SPY Watch this run all day tomorrow and then rug pool last 15 minutes before market close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:08:57 </td>
   <td style="text-align:left;"> $SPY Fake out or Bottom? https://youtu.be/0tdXXVBBYwk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:08:34 </td>
   <td style="text-align:left;"> $SPY futures simpin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:08:08 </td>
   <td style="text-align:left;"> $SPY truly believe tomorrow will be bearish, wouldn’t be surprised to see a pop upwards at opening followed by a rug pull…let’s see how this plays out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:08:00 </td>
   <td style="text-align:left;"> $SPY die spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:07:51 </td>
   <td style="text-align:left;"> $DJIA $SPY $SPX 
Never forget that 90% of people trade US indices do so because they are the most Bullish equities in the world and so Bears are out numbered 10 to 1. That&amp;#39;s not to say they won&amp;#39;t correct but there will always be bounces that Fuck the Bears one way or another. My number one rule is never swing trade a short. Just saying. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:07:47 </td>
   <td style="text-align:left;"> $SPY 👍🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:07:43 </td>
   <td style="text-align:left;"> $SPY notice that consolidating on solid volume today? Dangerous for shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:07:43 </td>
   <td style="text-align:left;"> $SPY still ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:07:11 </td>
   <td style="text-align:left;"> $SPY That was a lot of heavy lifting to end up red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:07:03 </td>
   <td style="text-align:left;"> $SPY Been buying a lot of stonks at 52 week lows. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:06:52 </td>
   <td style="text-align:left;"> $SPY How market will spin tomorrow&amp;#39;s job report. If job report is weak than taper and hike on hold. If job report strong than taper and hike priced in. Head I win Tail I win. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:06:37 </td>
   <td style="text-align:left;"> $SPY “significant” balance sheet runoff. 🙌✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:06:33 </td>
   <td style="text-align:left;"> $SPY spot etf announced next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:05:50 </td>
   <td style="text-align:left;"> $SPY . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:05:23 </td>
   <td style="text-align:left;"> $SPY y’all hedged? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:05:18 </td>
   <td style="text-align:left;"> $SPY SPY to 460 and it&amp;#39;s head and shoulders. Then the fun begins. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:05:13 </td>
   <td style="text-align:left;"> $SPY unless they&amp;#39;re based off of a specific event happening, futes usually don&amp;#39;t mean shit. Leading up to market open, they&amp;#39;ll try to set the stage but that only lasts a little while usually.  Odd things those futures are. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:05:12 </td>
   <td style="text-align:left;"> $SPY the carnage in growth has been historic in its severity. worse than the pandemic rout. I suspect we are nearing an exhaustion of willing sellers, and when we do, the reversal is going to ignite many stocks to the upside a lot faster than most expect. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:05:05 </td>
   <td style="text-align:left;"> $SPY HELLO EVERYONE IM LOOKING TO DIVERSIY MY PORTFOLIO. HOW DO I PURCHASE A 2000-YEAR TREASURY BOND? THANKS IN ADVANCE $QQQ $IWM $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:04:59 </td>
   <td style="text-align:left;"> $SPY skybox </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:04:55 </td>
   <td style="text-align:left;"> $SPY time to break it down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:04:48 </td>
   <td style="text-align:left;"> $SPY dump started already </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:04:45 </td>
   <td style="text-align:left;"> $SPY where was the outrage and the &amp;quot;speeches&amp;quot; on the Billions in damage during the Marxist riots of 2020 by the liberals? Silence. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:04:44 </td>
   <td style="text-align:left;"> $SPY  99% drama queens. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:04:41 </td>
   <td style="text-align:left;"> $SPY by puts before the close tomorrow 

In calls right now

Gotta trade both sides of this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:04:39 </td>
   <td style="text-align:left;"> $SPY hmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:04:33 </td>
   <td style="text-align:left;"> $SPY has the market turned or is this a Bull trap. The later I fear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:04:31 </td>
   <td style="text-align:left;"> $SPY dark pools buying 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:04:24 </td>
   <td style="text-align:left;"> $SPY This still needs to bust through today&amp;#39;s high tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:04:22 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:04:22 </td>
   <td style="text-align:left;"> $SPY bang!!!!!! green right out the gate. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:04:15 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:03:52 </td>
   <td style="text-align:left;"> $SPY 

Good for the memes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:03:45 </td>
   <td style="text-align:left;"> $SPY futes are RIPPING , MASSIVE Green Day tomorrow 🚛🚛🚛🚛 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:03:28 </td>
   <td style="text-align:left;"> $SPY bulls : we are going back up! 

Literal double top - this thing is about to tank and take a real serious poopie oopie </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:03:22 </td>
   <td style="text-align:left;"> $SPY ah there we go finally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-07 08:03:20 </td>
   <td style="text-align:left;"> $SPY break above today high or Friday dump? Usually lately Friday&amp;#39;s have been ok but sediment seems to have shifted. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:57:46 </td>
   <td style="text-align:left;"> $QQQ should I sell? Man </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:55:28 </td>
   <td style="text-align:left;"> $SPY Please don&amp;#39;t embarrass yourself into tomorrow.

Jobs report is a good news is bad news and bad news is bad news dealio for you now. Sell off, so.

Good jobs = abrupt end QE &amp;amp; double rate hike.

Bad jobs = Just no growth, silly 

Mediocre jobs = Well, that IS your best hope, but FED slant now Hawkish you MUST keep in mind👌

Add to your day redness and mope a bit but just don&amp;#39;t even return til the 17th Mon., let these next 2 weeks of data pass you buy, not bullish in the least bit.... 

Sooooo many silver bullets you have to dodge right now👍

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:54:58 </td>
   <td style="text-align:left;"> Not bad... $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:54:12 </td>
   <td style="text-align:left;"> $SPY $QQQ why futures is green???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:53:19 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA If tomorrow we gap up, I would take that first profit….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:52:29 </td>
   <td style="text-align:left;"> $QQQ  Bear : waiting till morning 

$Spy  $Tesla

 Tomorrow bear turn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:50:06 </td>
   <td style="text-align:left;"> $SPY $QQQ jobs report hits tomorrow sleep tight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:48:52 </td>
   <td style="text-align:left;"> $QQQ fake after hours volume 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:48:33 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ in nikola tesla&amp;#39;s last letter to his mom, he said &amp;quot;All these years that I had spent in the service of mankind brought me nothing but insults and humiliation&amp;quot;  
rest in peace nikola </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:48:04 </td>
   <td style="text-align:left;"> $QQQ Nice bounce from the 100 SMA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:47:42 </td>
   <td style="text-align:left;"> $QQQ Watching to see if $377 holds... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:47:18 </td>
   <td style="text-align:left;"> $QQQ AH volume is fractional to intraday dont be fooled into thinking we rocket tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:47:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 50439500. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:45:53 </td>
   <td style="text-align:left;"> $BXRX this just doesn’t make sense to me. I mean I was saying a similar thing about $KPRX , ran soon after 150% . 
BXRX trading at 21 cents had news of a 6 month extension December 16th. It just completed a small direct offering at 33 cents a share. News conference next week. 17.7 mil market cap. Such a low market cap and such a low market price. Seems to go to be true to me. Watching closely. Just my opinions
Will watch indices $SPY $IWM $QQQ as well, however this is undervalued regardless I believe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:45:39 </td>
   <td style="text-align:left;"> $QQQ Why do I feel like this will drop it’s balls tm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:45:13 </td>
   <td style="text-align:left;"> $NIO $TSLA $QQQ Risk on, fuck it risk off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:41:57 </td>
   <td style="text-align:left;"> $QQQ Escape Velocity 😂😀🤑😆🤣😅💲💰💲💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:41:40 </td>
   <td style="text-align:left;"> $SPY Oil telling you all you need to know, $4 gas sooner than you think.
.*national average 

&amp;#39;Course the 2 yr and TIPS not a bad 2bd either. 

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:41:39 </td>
   <td style="text-align:left;"> $QQQ Week top stocks fall MMs mufucs put money in meme stonks! Gotta keep APES happy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:40:42 </td>
   <td style="text-align:left;"> $SPY, $QQQ big movement AH…price moving higher AH than regular session. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:39:39 </td>
   <td style="text-align:left;"> $QQQ $SPY glad I sold my puts! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:38:41 </td>
   <td style="text-align:left;"> $QQQ Is this going to $391 tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:37:57 </td>
   <td style="text-align:left;"> $QQQ

Is there enough fear by this it seems not ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:37:55 </td>
   <td style="text-align:left;"> $TSLA $QQQ 1.3% Nasdaq day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:36:50 </td>
   <td style="text-align:left;"> The distribution of VIX over the past decade. 

After the 2009 market crash, it took 4-5 years for the VIX to settle down. The COVID crash was an investment opportunity, it takes a while until VIX settles down. On its way down, we keep making new ATH. 
 
$VIX  $SPY $SPX $QQQ $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:36:30 </td>
   <td style="text-align:left;"> $QQQ probably going to rally to 400 and nuke again ugh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:35:55 </td>
   <td style="text-align:left;"> $QQQ AH looking good! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:33:55 </td>
   <td style="text-align:left;"> $SPY $QQQ Skip to minute 13. You need to own assets that inflate not to get rich but just to not lose as the currency is devalued. That is the primary driver of the up only market the money illusion.

With the US government needing 30% of its debt monetized to keep its funding costs down we have a Fed balance sheet at $8-9 trillion of the $30 trillion debt. With projections of $140 trillion in debt by 2050 needing 30% or $40 trillion in monetization to keep funding costs down expect the Fed balance sheet to continue to explode as they jawbone the public into thinking they will pull back as prices hit non-stop record highs over the coming decades.

https://youtu.be/MFO6OtnmEDo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:33:28 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $IWM About this pullback...Is it...
1) a kneejerk reaction to the hawkish FOMC-minutes or
2) a market correction in the making
IMHO, if it&amp;#39;s (2) then there is not enough blood/panic yet to get to the bottom...meaning there&amp;#39;s more room to go down...sigh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:33:27 </td>
   <td style="text-align:left;"> $QQQ lets go. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:30:09 </td>
   <td style="text-align:left;"> $QQQ Futes jumping.

Nasdaq trade would be at 2R if I&amp;#39;d taken it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:27:20 </td>
   <td style="text-align:left;"> $SPY, $QQQ, latex7856e50045d4a9a47c8b8b2172b991b6QQQ
$DIA
Date Courtesy : Stock Trader&amp;#39;s Almanac 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:22:35 </td>
   <td style="text-align:left;"> $QQQ they purposely left a gap in this so they can fill it to the downside tomorrow lol load the puts asap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:20:48 </td>
   <td style="text-align:left;"> $SPY Heads up, this indicator doesn&amp;#39;t turn red that often, but when it does, it has my full attention. This is on weekly it computes volume, currently price is below my weekly pivot of 470.60, I expect price action to retest that area, maybe it will hang on maybe it won&amp;#39;t if it doesn&amp;#39;t, I&amp;#39;ve put my weekly pivots below...

467.27
459.25
453.08
443.91
431.28 ~10%
.
.
.
383.63 ~20%
there aren&amp;#39;t any weekly pivots in the 15% around 407.xx

$IWM has been red for a minute, but $DJIA and $QQQ  just turned red this week too </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:16:56 </td>
   <td style="text-align:left;"> $PTON Peloton Interactive Stock Isn’t a Stay-at-Home Play, Irrespective of the Omicron Variant 
Hedge Funds Are Selling Peloton 
Market $SPY $QQQ selling losers $PTON </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:15:06 </td>
   <td style="text-align:left;"> $QQQ NEW ARTICLE : Is It a Good Time to Reconsider the Nasdaq-100 ETF? https://www.stck.pro/news/QQQ/21004599 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:15:02 </td>
   <td style="text-align:left;"> $QQQ way oversold. this thing is going to rocket all the FOMO tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:12:48 </td>
   <td style="text-align:left;"> $QQQ 🦍🦍🦍🦍🦍🦍🦍🦍🦍🦍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:10:43 </td>
   <td style="text-align:left;"> $QQQ danger danger. 
 https://www.reddit.com/r/Epic_Economics/comments/rxt38s/extreme_risk_in_markets_balance_sheet_runoff/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:10:24 </td>
   <td style="text-align:left;"> $QQQ what bad news will hit tonight or tomorrow morning? We need for downside pronto </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:10:21 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Nothing here, until 8:30 AM EST tomorrow, where you will have the single most &amp;quot;moving&amp;quot; NFP jobs report you seen in quite some time, peeps.

Position yourselves well, peeps. 

Hot means FED will tighten very soon.

Cold means FED will have more luxury time they feel to be cautious with rates but that&amp;#39;ll all last all of the weekend as CPI hammers home s&amp;#39;more sweet inflationary reality early next week w/ PPI &amp;amp; retail sales to follow.

And then, you&amp;#39;re in luck!  PCE Deflator CORE gov&amp;#39;t inflation #s grace us  the following week. 

So, bulls, this is all to say, pick your </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:10:16 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $MSFT $TSLA 

If hedged funds and CEO&amp;#39;S are selling..

 fck this 💩

I&amp;#39;m loading PUTS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:09:22 </td>
   <td style="text-align:left;"> $QQQ Is that the Bottom, or a Dead Kitty https://youtu.be/0tdXXVBBYwk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:05:37 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:05:09 </td>
   <td style="text-align:left;"> $QQQ Short Term oversold.  Mid term neutral.  💲💰💲💰🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:05:05 </td>
   <td style="text-align:left;"> $SPY HELLO EVERYONE IM LOOKING TO DIVERSIY MY PORTFOLIO. HOW DO I PURCHASE A 2000-YEAR TREASURY BOND? THANKS IN ADVANCE $QQQ $IWM $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:02:30 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-01-06 Trade Analysis Video: 
https://www.youtube.com/watch?v=0XQD3qbO2Yk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 08:01:59 </td>
   <td style="text-align:left;"> $SPY $QQQ Silly bears are like it’s collapsed. We are still at an all time high vs even 6 months ago. Let’s buy every dip bull gang and take bear gangs money like always. 🤑📈📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:58:09 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:55:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA I DONT ALWAYS MOCK BULLS BUT WHEN I DO I SAY LOL AT DUMB BULLS 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:55:09 </td>
   <td style="text-align:left;"> $QQQ love the straddle play with volatility </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:55:09 </td>
   <td style="text-align:left;"> Dear followers, my original account @beatthemarketpro just got suspended for some reason.  I don&amp;#39;t really care about the reason why because I don&amp;#39;t care whether I have an account or not.  All I cared about was doing my little part to help some of you do what we love to do, trading and profiting in the stock market.  Therefore, I won&amp;#39;t be reactivating my own account and this will be my final post.  Thank you so much for following me and for your readership.  It&amp;#39;s been fun.  I wish you all the best in your future endeavors and God bless.  -A $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:54:44 </td>
   <td style="text-align:left;"> $BBIG I accumulated close to 100,000 shares and will add on any dips $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:54:10 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures surging, looks like the bears are in trouble tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:52:55 </td>
   <td style="text-align:left;"> $QQQ no shorts not covering AH ... yall who have calls wish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:51:31 </td>
   <td style="text-align:left;"> $QQQ Shorts covering AH? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:50:41 </td>
   <td style="text-align:left;"> $WISH

this has 1.25 bil in cash, is not expected to make a profit until 2025. And spent 745 million in 2020, more in 2021 and more in the future, that means that cash they have is enough to lost 1 or 2 more years. Then it’s either bankruptcy or share dilution to raise cash to survive. 

They are selling shares to you and running. Is common sense gone? Try to warn people and they call you a hedgeminion. I’m your neighbor trying to help you.

To prove my point let’s look at what the execs at the company have been doing since ipo

 $QQQ $SPY $DYD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:50:22 </td>
   <td style="text-align:left;"> $QQQ preview for tomorrow 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:50:20 </td>
   <td style="text-align:left;"> $BBIG This beauty will run hard.
Price Target $39 $$$$
$spy $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:50:19 </td>
   <td style="text-align:left;"> $SPY $DJIA $DIA $QQQ A new season of &amp;quot;Republican Squid Games&amp;quot; to air on Fox News tonight at 9pm. 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:50:19 </td>
   <td style="text-align:left;"> $QQQ good try bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:49:49 </td>
   <td style="text-align:left;"> $SPY $QQQ for  those that loaded up and bought  puts before the close  tonight,  we know you guys are going to be on the streets tomorrow n  bankrupt , so tell us what account to send the money to so you guys can have some breakfast tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:48:56 </td>
   <td style="text-align:left;"> $SPY $QQQ looks like the last time I can lighten up some of my bags to deleverage risk. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:47:27 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA I JUST ATE A RICE BOWL AND NOW I FEEL LIKE A BEACHED WHALE SOMEONE ROLL ME BACK IN 🐋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:47:24 </td>
   <td style="text-align:left;"> S&amp;amp;P 500 Subdued On Fast And Furious Fed Tightening Roadmap, NFP Eyed For Direction $QQQ $SPX $DJI https://talkmarkets.com/content/stocks--equities/sp-500-subdued-on-fast-and-furious-fed-tightening-roadmap-nfp-eyed-for-direction?post=340384 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:45:55 </td>
   <td style="text-align:left;"> $QQQ fallout 🩸🩸🩸☠️
 https://www.reddit.com/r/Epic_Economics/comments/rxsjza/nas100_fallout_buyer_beware_growth_at_all_costs/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:44:20 </td>
   <td style="text-align:left;"> $QQQ bottomed again near $380-$381.... https://share.trendspider.com/chart/QQQ/81303m8fzr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:42:57 </td>
   <td style="text-align:left;"> $DKNG what a beast! Only the beginning. So much room $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:42:29 </td>
   <td style="text-align:left;"> $SPY $QQQ Even though I have thoughts that this bubble will burst, especially with such a hideous and dangerous administration, I just cannot pull the trigger to sell my long term. In fact, I bought more 😬😜 even when I&amp;#39;m bearish, I still buy lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:40:03 </td>
   <td style="text-align:left;"> $QQQ apes coming for you shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:36:17 </td>
   <td style="text-align:left;"> Sellers Pay A Visit, Pushing Markets Back Into Prior Ranges $QQQ $IWM $SPX https://talkmarkets.com/content/etfs/sellers-pay-a-visit-pushing-markets-back-into-prior-ranges?post=340383 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:34:34 </td>
   <td style="text-align:left;"> $SPY $QQQ You have to know when to sell the rip. Just saying for a friend… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:32:28 </td>
   <td style="text-align:left;"> $PTON Peloton Stock Falls to Fresh Low. Weakening Demand Has Analysts Concerned.

$QQQ $SPY Market has a lot of selling to still do due being ahead of itself </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:30:51 </td>
   <td style="text-align:left;"> $QQQ this is getting wrecked tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:30:42 </td>
   <td style="text-align:left;"> $QQQ pure vomit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:27:55 </td>
   <td style="text-align:left;"> Instead of doubling down on tech stocks, why not go in a different direction in 2022? My classic value screen returned 12 dirt-cheap stocks with high Zacks Rank and Style Scores. Check them all out on the podcast. $KSS $TOL $ARW $TTE $QQQ  https://shar.es/aWKMuB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:25:51 </td>
   <td style="text-align:left;"> $SPY We&amp;#39;ll wake up to .90% 2 yr and by 10AM it will be higher. Much. 

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:25:20 </td>
   <td style="text-align:left;"> $QQQ Opportunity Chart = When the Casino takes partners 😉..still think 2023. Gut feeling Old Bank just drooling on taking newbs property and  working on paperwork this month. BBB campaign vs Short campaign trail. Sprinkle in promo with lunch money gambling to bank on call selling and ALL GOOD. DTs when bored for play money = fun either way 🍀✌️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:25:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL

Tomorrow could decide a lot for which way the market moves in 2022 in my opinion. Question is does the market move up or descend down...😈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:23:48 </td>
   <td style="text-align:left;"> $NQ_F $QQQ $NASDAQ 
Oscar Carboni Says Stop Short Selling Nasdaq For Today ! See Video For Details 01/07/2022 Video 2346 https://youtu.be/eyFBePpv1MA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:22:48 </td>
   <td style="text-align:left;"> $QQQ Ramp tomorrow🤞 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:21:27 </td>
   <td style="text-align:left;"> $QQQ open at 387 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:21:10 </td>
   <td style="text-align:left;"> $QQQ I think $GME could remind everyone tomorrow what is in store for tech ER. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:20:41 </td>
   <td style="text-align:left;"> $MULN let&amp;#39;s see what the market $djia $spy $qqq $nasdaq does tommorow https://finance.yahoo.com/news/mullen-automotive-named-top-ev-133000686.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:20:33 </td>
   <td style="text-align:left;"> $BTC.X $SPY $QQQ 👋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:19:40 </td>
   <td style="text-align:left;"> Job Market Remains Tight Despite Omicron Concerns

https://www.google.com/amp/s/www.wsj.com/amp/articles/weekly-jobless-claims-01-06-2022-11641415216

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:18:35 </td>
   <td style="text-align:left;"> $QQQ made in China frauds. Profits over people 
 https://www.reddit.com/r/Epic_Economics/comments/rxrwvv/defaulting_on_debt_market_contagion/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:17:34 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $TSLA 

Futures update for the shorts 

👇👇👇👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:16:45 </td>
   <td style="text-align:left;"> $spy $qqq BREAKING: market will go parabolic starting tomorrow as Donny is coming back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:14:06 </td>
   <td style="text-align:left;"> $SPY I started my week shorting the $QQQ. Sold on Tuesday and shorted $AAPL at the bell. Sold those puts at yesterday’s bell and switched to $DIA puts. I sold the DIA at today’s bell and went cash. Man I’ve had a hell of a week. I think we go up gradually all day tomorrow until 2:00. That’s when I buy puts and hold over the weekend. Bearish for now. I believe tomorrow’s bell will be bloody </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:13:14 </td>
   <td style="text-align:left;"> $QQQ $SPY Fed gave these gains, Fed will tank them. 20%-30% annual gains were never sustainable. Expect messy and volatility until Fed is done tightening. Short term —&amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:12:04 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA In this video Jim Cramer talks about how to invest right now!

https://www.youtube.com/watch?v=mHicdnezVJE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:11:52 </td>
   <td style="text-align:left;"> $QQQ $SPY $SPX $IWM 

Tea party has to end sooner rather than later. $VIX begging for it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:09:36 </td>
   <td style="text-align:left;"> $QQQ 378 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:08:45 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $TQQQ $SOXL 

Enough selling bitches. Time for a face ripper rally! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:07:27 </td>
   <td style="text-align:left;"> $QQQ lol man they are trying so hard to keep this up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:07:12 </td>
   <td style="text-align:left;"> $SPY $QQQ not nearly enough negativity. Not oversold. Inflation is going higher just watch oil </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:05:40 </td>
   <td style="text-align:left;"> $SPY $QQQ how many times have we seen this movie? They beat up big tech then in 1 session they kill all bears by pumping it 5% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:05:34 </td>
   <td style="text-align:left;"> $QQQ stocks only go up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:03:39 </td>
   <td style="text-align:left;"> $QQQ $AAPL $TSLA $MSFT $GOOGL 

BUT BUT BUT THE FED 😆

PRICED IN. 

Shorts are about to get taken to the woodshed!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:02:48 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA 

Hard to sustain a FED-sponsored bull market without the FED! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:02:01 </td>
   <td style="text-align:left;"> Is It a Good Time to Reconsider the Nasdaq-100 ETF? | ETF Trends $QQQ https://www.etftrends.com/nasdaq-portfolio-solutions-channel/is-it-a-good-time-to-reconsider-the-nasdaq-100-etf/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:01:38 </td>
   <td style="text-align:left;"> $SPY toots peepin $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 07:01:35 </td>
   <td style="text-align:left;"> $SPY $QQQ btfd in googl Amzn nflx shop and Msft going up before er </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:59:52 </td>
   <td style="text-align:left;"> $SPY $QQQ $WEN plz meme rally tomorrow me no want work dumpster again :( </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:55:46 </td>
   <td style="text-align:left;"> $QQQ Yeah, going higher. Scoop up whatever you want in the sector I guess. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:54:56 </td>
   <td style="text-align:left;"> $QQQ tech earnings in 3 weeks. Let the run up begin. Maybe starting Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:53:48 </td>
   <td style="text-align:left;"> $SPY $QQQ I have a lot of respect for the host holding him accountable for previous predictions. I&amp;#39;m bearish. I the market, but generally seems the types of moves Harry is talking about seem to happen towards the end of a bear market, but we are in unprecedented times in terms of money printing. Only Gd knows.

 https://youtu.be/LtXIz8Xeg-Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:53:19 </td>
   <td style="text-align:left;"> $QQQ smells like a limit down coming real soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:51:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMC $GME 

You think MM bringing back the ape mentality for the short term before they tank the widespread market and this ideology kills baggers in a transition to bear market. Few weeks-months out but a theory? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:46:00 </td>
   <td style="text-align:left;"> $QQQ: The short term is neutral, but the long term trend is still positive. Not much to worry about for now. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:44:39 </td>
   <td style="text-align:left;"> $SPY $QQQ everyone is bearish now.. all buying puts even CNBC bearish.. time to begin to go long in to upcoming er in big tech </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:44:23 </td>
   <td style="text-align:left;"> $QQQ Red Hollow Candlestick today. Often see this just before a push higher. 

Could get a bounce here
https://share.trendspider.com/chart/QQQ/66823k1kfh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:43:07 </td>
   <td style="text-align:left;"> $QQQ I want to be bullish but the dark side is so tempting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:42:39 </td>
   <td style="text-align:left;"> $QQQ no shit! CRamer is samrt

https://www.cnbc.com/2022/01/06/cramer-says-tech-stocks-could-bottom-one-day-after-nasdaqs-nosedive.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:41:52 </td>
   <td style="text-align:left;"> $SPY, u ain&amp;#39;t seen nothing yet #STEALTH $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:39:34 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $DWAC

YIKES!!😱 LOOKS LIKE TOMORROW 

PEARS BEGGIN GETTING CLAPPED BY 

NEWBY GEN Z TRADERS...🤣🤣📈

https://apple.news/AlTa4NPOKRt6lphh2JxBgBw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:38:57 </td>
   <td style="text-align:left;"> $QQQ wild that none of this matters when  your FAANMG group plus $TSLA holds indicies up due to an ever increasing weighting. Stock buybacks and endless amounts of cheap speculative money flowing into the liquidity leaders. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:37:15 </td>
   <td style="text-align:left;"> $qqq $ndx $spx https://www.youtube.com/watch?v=4TqM0peojuk&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:36:28 </td>
   <td style="text-align:left;"> $QQQ I’m shooting for a shitty Jobs Report since all I keep reading is no one wants to work and record people quitting jobs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:34:35 </td>
   <td style="text-align:left;"> $QQQ panic buying tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:34:05 </td>
   <td style="text-align:left;"> $spy $BRK.B $qqq $cost https://www.youtube.com/watch?v=5sX81VcUmY4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:33:21 </td>
   <td style="text-align:left;"> $QQQ $AAPL $TSLA $MSFT $GOOGL  Anyone know what a triple bottom and inverse head and shoulders equals tomorrow? 😆🚀🐂

ADD IN THE SHORT COVERING AS WELL 😱👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:32:01 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ 🚨 
Feb 21 

Donald trump is coming out with his own social media app called “Truth Social”

$TWTR better look out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:31:33 </td>
   <td style="text-align:left;"> $SPY $QQQ So it will be all up to the jobs report tomorrow, if the report is strong then we go up and if the report is weak then we go down. I am pretty confident that we will see a very strong report tomorrow that the market will like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:31:17 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM So this is new from us - https://cestrianetfselect.substack.com/p/a-dead-inside-take-on-etfs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:31:01 </td>
   <td style="text-align:left;"> $QQQ boomer bears taking their frustrations with technology out on the nasdaq lmao. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:30:13 </td>
   <td style="text-align:left;"> $SPY You just know already that by 8:35 am EST tom. rates will be heading toward 2%, and, 2.25% after inflation data next week--the consumer is not about to stop spending, TRILLIONS household wealth out there all giddy--, and , the horse&amp;#39;s mouth speaks 26th to confirm everything, bumping rates even more, like 2.5% . $ZT_F 

So why you resisting? 

Do we have to &amp;quot;crack the whip or can you fall over yourself (and we promise not to laugh) ?&amp;quot; $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:28:25 </td>
   <td style="text-align:left;"> $QQQ max pain is 392 tomorrow 👍🏾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:27:04 </td>
   <td style="text-align:left;"> $QQQ $SPY remember friday is sell off day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:26:34 </td>
   <td style="text-align:left;"> $QQQ calls&amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:26:25 </td>
   <td style="text-align:left;"> $SPY $QQQ 

let’s see some gamma squeezes tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:26:13 </td>
   <td style="text-align:left;"> $SPY $QQQ Today&amp;#39;s action IMO, calls for a double bottom. We may go up a little tomorrow then come down Monday to double bottom. 
The bottom is definitely around here. 
$XBI As long as 100 holds no fire in da house.  But if it is broken.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:25:46 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ whens these fed news and rate hike news subside in 2-4 days , watch we make a run again.  Take this opportunity to load calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:24:39 </td>
   <td style="text-align:left;"> $QQQ amc n gme LFG. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:23:37 </td>
   <td style="text-align:left;"> $FNGS the $QQQ mega cap ETF, long or short? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:23:32 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA MAKE CARBS GREAT AGAIN 🥯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:21:33 </td>
   <td style="text-align:left;"> $SPY $QQQ at this point, futures mean nothing I’ve found ha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:19:43 </td>
   <td style="text-align:left;"> $QQQ The earlier dump netted a good return followed by the pump.  $DWAC $SNAP both champions for option gains </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:19:41 </td>
   <td style="text-align:left;"> $SPY $QQQ sorry  Bears, tommorow your puts will open worthless 

Hopefully u sold before the close today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:19:30 </td>
   <td style="text-align:left;"> $1 Trillion Wipeout On Nasdaq Begins To Moderate - TheStreet $QQQ $QQQJ $TQQQ $TSLA $AAPL  https://apple.news/AoAVa0lEKS5uXRJwzjNb6fA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:18:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA DIET PEPSI IS BETTER THAN DIET COKE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:18:00 </td>
   <td style="text-align:left;"> Stock market outlook: Fed sell-off is a big buying opportunity - Business Insider $QQQ $TQQQ $QQQJ $AAPL $NVDA  https://apple.news/AJtuIi13RQxmlJ6ZQPSTeOQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:16:33 </td>
   <td style="text-align:left;"> $QQQ Does J Powell speak next week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:16:31 </td>
   <td style="text-align:left;"> $SPY $QQQ , whatever, YEARS, not months, not &amp;quot;year,&amp;quot; it will be YEARS b4 any semblance of &amp;quot;Worldblox&amp;quot; open works in place so ecosystem participatable for the many to see themselves running around with their virtual gucci handbags. 

And, I kn ow, I kn ow, a silly concept in the first place but, it&amp;#39;s how growth will ONLY happen, next leg up texh, but even CEO Jensen NVIDIA admitted indirectly METAVERSE is years away--software, ecosystem far removed from actual development for monetery scale.$NVDA ER he&amp;#39;ll walk back what he said Nov. , I 10p% guarantee it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:16:06 </td>
   <td style="text-align:left;"> $STNE  Stone repurchased a total of 3,595,713 shares on an average price of $55.40 per share back in 2019. Can you say you are getting a huge discount $SPY $QQQ $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:14:22 </td>
   <td style="text-align:left;"> $QQQ $AAPL $TSLA $MSFT $GOOGL  the QQQ opens above this, everything is going to TAKE OFF LIKE A ROCKET 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:13:58 </td>
   <td style="text-align:left;"> Top Portfolio Strategist Sets Bullish S&amp;amp;P 500 Target for 2022 - TheStreet $SPY $BX $QQQ $TQQQ $FNGU  https://apple.news/A1-FVuaD5QkqmKiTuDjn0tw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:11:59 </td>
   <td style="text-align:left;"> $SPY $QQQ 

But the bears were up all night calling for a crash, what’s going on...🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:07:56 </td>
   <td style="text-align:left;"> $spy $qqq we are in the end times </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:07:45 </td>
   <td style="text-align:left;"> $QQQ looks like the selling has dried up! You know what that means📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:07:23 </td>
   <td style="text-align:left;"> $QQQ $SPY Not a bad day today. But even just in case all tech companies fall 50%-60% or more due to a bear market or rate hike by the FED, I will be continuosly buying shares of growth/tech companies at discounted prices. Shares do not always go up, but they do not always go down forever either. At some point, higher interest rates will be priced in and stocks will go up again. I&amp;#39;m not worried in long term. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:03:41 </td>
   <td style="text-align:left;"> $QQQ why didn’t I buy that $GME call today… had the finger on the trigger too FML </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:02:42 </td>
   <td style="text-align:left;"> $DWAC $QQQ $CFVI 
🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:02:15 </td>
   <td style="text-align:left;"> $SPY $GME $QQQ $NVDA Plenty of liquidity in GME and AMC let it rip one more time for old time&amp;#39;s sake!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:01:20 </td>
   <td style="text-align:left;"> $QQQ sooner or later someone s gonna ask how much u made last year. 

(as a company) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:00:38 </td>
   <td style="text-align:left;"> $QQQ Hospital or death camp? You&amp;#39;ll connect that ventilator over my dead body! Fuck Bill Gates! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 06:00:36 </td>
   <td style="text-align:left;"> $QQQ Up almost 1 dollar in AH, fire </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:58:40 </td>
   <td style="text-align:left;"> $QQQ 375-370 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:57:31 </td>
   <td style="text-align:left;"> $QQQ hulk candle! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:57:25 </td>
   <td style="text-align:left;"> $QQQ futes gunna tear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:56:13 </td>
   <td style="text-align:left;"> $QQQ the narrative is shifting. https://www.youtube.com/watch?v=RO59kE5NEws </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:56:04 </td>
   <td style="text-align:left;"> $SPY $qqq 
My target met earlier than Friday, while every one was bullish I was bearish
Now we rally $$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:55:38 </td>
   <td style="text-align:left;"> $QQQ Widespread reports of Democrat doctors murdering `covid` patients. Stay away from the hospitals even if you feel sick! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:52:18 </td>
   <td style="text-align:left;"> $SPY The DOR will be opened soon, probably ly tomorrow but 100% certain, next week, the FED&amp;#39;s warning hits ya in the liver, bulls, if you don&amp;#39;t step out....

$QQQ Tech will not continue this 35 year ride, it&amp;#39;s never had to deal with the likes of such a bearish term of confluencing influences as now👍

#DayOfReckoning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:51:31 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/2NMJAkM1YlU Go! $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:50:56 </td>
   <td style="text-align:left;"> 5-Day ETF Sentiment Recap: $QQQ is the #2 ETF that institutions are trading over rolling 5 day window with 622.1K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:49:44 </td>
   <td style="text-align:left;"> $QQQ $GOOGL $SPX $SPY 

Google should unveil an electric car and see the stock hit $3 trillion. Come on, Sundar! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:49:32 </td>
   <td style="text-align:left;"> Nasdaq falls for a third day as tech stocks struggle, Dow loses 170 points

$QQQ $DJIA

https://www.cnbc.com/2022/01/05/stock-market-futures-open-to-close-news.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:49:01 </td>
   <td style="text-align:left;"> $spy $qqq I  see $spy over $475 and qqq over $396 tomorrow $$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:48:34 </td>
   <td style="text-align:left;"> $QQQ 

Roughly 40% of Nasdaq stocks are down 50% or more from their 52 week highs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:48:10 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 1/6/2022 $SPY $XLF $QQQ $VIX $AAPL https://www.chartguys.com/daily-market-videos/4099/bulls-stop-the-bleed-for-now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:47:09 </td>
   <td style="text-align:left;"> $SPY $QQQ $GME you guys think $KODK will announce an electric car or go with the NFT/Crypto? They&amp;#39;re overdue for some hype. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:46:23 </td>
   <td style="text-align:left;"> $QQQ Not sure who was letting those $384.02 AH trades go through at volumes of 1 and 2 where the minimum bid was over $384.6X, but looks like MM are fed up with you lol. Bullish short term until interest rate hikes near, bearish back half of 2022. Overreaction to fed minutes. Sell off should have occurred last month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:46:18 </td>
   <td style="text-align:left;"> $SPY $QQQ Roughly 40% of Nasdaq stocks are down &amp;gt; 50% from their highs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:44:38 </td>
   <td style="text-align:left;"> $AMC $GME $QQQ $SPY https://youtu.be/hNwFIacJpBQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:42:53 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $SMH … my company will be buying and selling jpg’s …… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:42:20 </td>
   <td style="text-align:left;"> $SPY $IWM $QQQ $UVXY Chip chop ham - welcome to 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:42:00 </td>
   <td style="text-align:left;"> $QQQ this wrecked my calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:41:40 </td>
   <td style="text-align:left;"> $spy $qqq $LABU 
Big rally tomorrow and Monday.
Stay long and strong 💪 $$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:41:36 </td>
   <td style="text-align:left;"> $QQQ my technical says QQQ will drop tomorrow, too. Next week is bull week for me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:40:51 </td>
   <td style="text-align:left;"> $QQQ $SPY it&amp;#39;s really going to suck if the Q&amp;#39;s breaks out of this channel to the downside.  It&amp;#39;s given such nice pivots to trade against the past 18-20 months.   I have hope it continues up... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:40:47 </td>
   <td style="text-align:left;"> $QQQ the 10 year is at resistance....suspense here... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:39:41 </td>
   <td style="text-align:left;"> $QQQ $AAPL $TSLA $MSFT $GOOGL  another look for the rookies still holding PUTS screaming FED 😱😆🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:39:23 </td>
   <td style="text-align:left;"> $QQQ 380 seems to be the spot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:35:42 </td>
   <td style="text-align:left;"> $QQQ DWAC Exploding ... 
https://www.reuters.com/world/us/trump-launch-his-social-media-app-february-listing-shows-2022-01-06/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:34:29 </td>
   <td style="text-align:left;"> $SPY $QQQ looks like they might try to punish retail call buyers one last time to end the week with these memes pushing. A lot of people must need “call printing” cash. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:34:19 </td>
   <td style="text-align:left;"> $QQQ Congrats 👍 No panic all normal. Just the min wage swing cashing some out + some Bears anticipating gap down off Bearish data. The +- swing for possible $363- discounts timing I talked about did great IMO. May have got some recruits! Slap MA, make a few bucks, boost moral, give promo content 👌 Daytraders..the real MVPs 😁👍

ALL GOOD 🍀✌️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:32:32 </td>
   <td style="text-align:left;"> $DWAC  $SPY $QQQ TRUTH -their tag line should be &amp;quot;Nothing Truth Here&amp;quot; lol, another ponzi pump and dump stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:32:22 </td>
   <td style="text-align:left;"> $GUSH holla holla get a dolla. Room to 120s minimum $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:31:49 </td>
   <td style="text-align:left;"> $SPY $AAPL $QQQ $WFC $TSLA 
LIMIT  UP , circuit breakers! futures are going to rip all night🔥🔥 folks  welcome the Revolution,  welcome the good life! I hope everyone loaded up huge on calls  cuz   tomorrow’s gonna be a Friday you’re gonna remember </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:31:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Preliminary option volume of 42.3M today is 18% above recent average. Calls led puts 24.90M to 17.39M </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:29:57 </td>
   <td style="text-align:left;"> $SPY $QQQ the current gameplan with the Fed is that they are using their most effective tool in the kit (their mouthpiece, examples: fed minutes, airtime, etc), to give a hawkish view, and their actions are slightly dovish to their words.  This keeps the markets in check so that no one industry bubbles or pops. I think growth (specifically GARP)  has been thrown out with the bathwater and should be bought </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:29:51 </td>
   <td style="text-align:left;"> $QQQ $AAPL $TSLA $MSFT $GOOGL 

Anyone see a pattern here?

The Fed lol, oh my LORD this shit has been priced in for a YEAR!!!

Tech just needed to cool off, and it has. Guess what’s next??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:29:29 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:29:06 </td>
   <td style="text-align:left;"> $TSLA is it possible, that Nasdaq is simply range bound since November and the whole everyday drama is nothing but noise? $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:27:57 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ those 10 year notes are popping lately... but they were also at their current level in March and April of 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:26:35 </td>
   <td style="text-align:left;"> $QQQ shook out some paper hands </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:25:07 </td>
   <td style="text-align:left;"> $QQQ look at the yearly chart and tell me you&amp;#39;re honestly bullish with inflation out of control and a rising rate environment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:24:33 </td>
   <td style="text-align:left;"> $QQQ tough time weak </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:24:07 </td>
   <td style="text-align:left;"> $SPY $QQQ SPY bounced off of 50 DMA and QQQ bounced off of 100 DMA today. SPY formed a bullish doji pattern. I think we see a short term bounce to 472-475 on SPY and 388-390 on QQQ. If that doesnt hold then we see the next leg down. GLTA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:24:00 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA major mkt movers are at thier support level&amp;#39;s overnight tomorrow will decide if we head even lower or found a bottom, postioned for both sides just need a big decisive move not like todays flat line close, I am bullish and bearish i suppose </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:22:23 </td>
   <td style="text-align:left;"> $QQQ $AAPL $SPY $UVXY  6 total $TQQQ buy the dip and sell the rip scalps. Last dip buy before the close and sale after hours. You can trade with me and Finom Group folks! (1/2) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:22:05 </td>
   <td style="text-align:left;"> $QQQ 

Bulls. 

How can you possibly be bullish on this chart heading into Friday? Lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:21:52 </td>
   <td style="text-align:left;"> $SPY $QQQ you love seeing the bulls coming out swinging on ah futes pumped on 10k shares. Mmmmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:19:32 </td>
   <td style="text-align:left;"> $SPY Welp, don&amp;#39;t they say , the 2l1st week like 70% of the time shows stock market direction for the entire year? 

_________.

Am I? $QQQ $SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:19:27 </td>
   <td style="text-align:left;"> $QQQ  tomorrow when watching this.   Its going to be amazing! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:18:10 </td>
   <td style="text-align:left;"> $PTON The Market about to correct -15% $SPY $QQQ then 
Peloton 🚴 Trades at 10.00 a(Ten Bucks) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:17:13 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Closing imbalance = ~$156M to the BUY side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:16:47 </td>
   <td style="text-align:left;"> latex4f484fb7b41110e756411ed377a01581QQQ , I sure like U </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:16:40 </td>
   <td style="text-align:left;"> ✅4-0 so far this week on offfical closed signals❌

-RECAP-
$SPY Well what a week so far. Proud to say I’m still undefeated from last week on signals even with covid 😤. Anyways yesterday I gave out many callouts in the watchlist channel ex. $AMD and In general cause of the FOMC. Hopefully most people could have banked on those callouts even tho they weren’t official signals. As for today more stagnation in the market but still got some nice gains. Also connected recaps to new Twitter so if anyone from Twitter wants to see past recaps go to discord or my stocktwits. (Link in desc) also 30% sale still going on use code: HOLIDAY
-CLOSED-
🟢 $QQQ PUTS 35% PROFIT - (day trade signals) 
-OPEN- 
🟡 Still staying easy on swings as of now with this current market action. 

Join with the link in the description! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:15:00 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Market momo &amp;amp; activity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:14:33 </td>
   <td style="text-align:left;"> $QQQ Buy DWAC on principle 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:14:22 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Fear &amp;amp; Greed Index </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:14:06 </td>
   <td style="text-align:left;"> $QQQ pumping after hours easy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:12:13 </td>
   <td style="text-align:left;"> $SPY Live look at bulls&amp;#39; digestion of FED threats and compulsories $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:11:07 </td>
   <td style="text-align:left;"> $QQQ Gap up tomorrow morning watch for strong Futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:11:04 </td>
   <td style="text-align:left;"> $QQQ LoL.  Some serious short covering going on in AH.  😀😂😅🤣😆🤑💰💲💰💲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:09:51 </td>
   <td style="text-align:left;"> $QQQ that’s right! You bears are so done for tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:09:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $ETH.X $BTC.X Searches For ‘Sell Ethereum’ Explode 972% In One Day As Ethereum Tanks

BY VALUEWALK

Online searches for &amp;quot;Sell Ethereum&amp;quot; exploded 972% in the United Kingdom on 6th January 2022

hmmmm wonder why? 
Wondering what the Bitcoin % search total is?

Google searches for “Why has Ethereum gone down?” also increased 2,028% on the same day as well as “Sell Bitcoin” rising 400%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:09:29 </td>
   <td style="text-align:left;"> $QQQ need Bostic to come to our rescue </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:09:07 </td>
   <td style="text-align:left;"> $NQ_F going to take out the high of the day in the next few minutes... watch!  $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:09:03 </td>
   <td style="text-align:left;"> $SPY $QQQ At least the market has stabilized today and we might have found the bottom. The jobs report could come in as a rescue tomorrow, as long as the report is strong to reassure investors that the US economy is in a wonderful shape, the market should bounce back hard. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:08:39 </td>
   <td style="text-align:left;"> $QQQ Already moving up AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:08:34 </td>
   <td style="text-align:left;"> $QQQ I will take it anyday we are not down 3% is good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:07:35 </td>
   <td style="text-align:left;"> $QQQ $spy $dia 

I deposited a little bit into my TD Ameritrade just so I could see that EOD number as Green …. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:06:57 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX hard to imagine MM let put buyers get away with this. (PCQQ put call ratio on QQQ) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:06:27 </td>
   <td style="text-align:left;"> $QQQ good luck tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:06:25 </td>
   <td style="text-align:left;"> $QQQ Nice hold without the support of the big boys.  MSFT aapl amzn tsla all down.  Amazing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:06:08 </td>
   <td style="text-align:left;"> $QQQ NEW ARTICLE : William Blair: Shades of Sustainability https://www.stck.pro/news/QQQ/20996524 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:05:39 </td>
   <td style="text-align:left;"> $QQQ inverse head and shoulders begins play out tm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:05:15 </td>
   <td style="text-align:left;"> $QQQ holding on by a thread just let it go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:04:36 </td>
   <td style="text-align:left;"> $QQQ ppt can bring any index to whatever level </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:04:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Economic calendar for 1/7 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:04:12 </td>
   <td style="text-align:left;"> $QQQ similar to Dec. 16, 17th candles....a lower lower tomorrow and then a lower high, melt-up...? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:02:39 </td>
   <td style="text-align:left;"> $QQQ  No where to go but up now… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:01:49 </td>
   <td style="text-align:left;"> $QQQ held the 100mda </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:01:35 </td>
   <td style="text-align:left;"> $QQQ be very surprised if it doesn&amp;#39;t flush more tomorrow. Guess I can be wrong though </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:01:32 </td>
   <td style="text-align:left;"> $ETSY Great close as everything sold off but this kept stable and was good buying volume. This will see $300 soon. $spy $qqq $ebay $wish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:01:25 </td>
   <td style="text-align:left;"> $QQQ what a truely useless day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:01:16 </td>
   <td style="text-align:left;"> $BTC.X if you’re watching, this is a pending dumpster fire in the short term. Along with $AAPL and $QQQ  and most of the rest of the temporarily overvalued and sheep infested market. 

I smell a markets in turmoil episode coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:01:07 </td>
   <td style="text-align:left;"> $QQQ Caught a bid into close after flush! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:00:58 </td>
   <td style="text-align:left;"> $QQQ whole new meaning to managed mkts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:00:54 </td>
   <td style="text-align:left;"> $QQQ portfolio has gone up last three days. bought the dip at close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:00:39 </td>
   <td style="text-align:left;"> $SPX $QQQ    you don&amp;#39;t want to be a bear rt $NQ_F afterburners are on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:00:23 </td>
   <td style="text-align:left;"> $QQQ fully flushed tomorrow we rise </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:00:19 </td>
   <td style="text-align:left;"> Btw, I think it would be positive to see a 5-7% market pullback ahead of the new earnings season that starts in 2-3 weeks. This would allow for earnings surprises to have a bigger impact. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:00:12 </td>
   <td style="text-align:left;"> $QQQ Beautiful flush into close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 05:00:03 </td>
   <td style="text-align:left;"> Great day traders! See you in the morning Jobs on deck $SPY $QQQ yields in play as well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:59:41 </td>
   <td style="text-align:left;"> $QQQ bull flag </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:59:02 </td>
   <td style="text-align:left;"> $QQQ Masterful job killing options. Calls and puts alike. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:58:56 </td>
   <td style="text-align:left;"> $QQQ swinging calls once again like yesterday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:58:45 </td>
   <td style="text-align:left;"> $SPY &amp;quot;The pot&amp;quot; is getting colder and colder, soon you will feel the effects as temps turn below your maximum safe cold degrees 

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:58:26 </td>
   <td style="text-align:left;"> $QQQ hasn&amp;#39;t been this sideways in a while. I&amp;#39;ll be there to realize the gains coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:58:15 </td>
   <td style="text-align:left;"> $QQQ Wow.  Some big whale just bought the dip.  Damn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:58:03 </td>
   <td style="text-align:left;"> $QQQ EOD Flush </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:58:01 </td>
   <td style="text-align:left;"> $QQQ anyone else sick of hearing about the 10 year yield? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:57:37 </td>
   <td style="text-align:left;"> $QQQ last red day for a long time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:57:37 </td>
   <td style="text-align:left;"> $SPY $QQQ controlled selloff hmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:57:02 </td>
   <td style="text-align:left;"> $QQQ Now that&amp;#39;s what I&amp;#39;m talking about. She&amp;#39;s showing her true colors. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:56:43 </td>
   <td style="text-align:left;"> $SPY $QQQ Thinking that tomorrow&amp;#39;s worry-wort NFP report that&amp;#39;s goosing VIX post-FOMC minutes will be VIX-deflationary.  Get your premium sales orders in now!   
 
If I&amp;#39;m wrong, &amp;quot;Praise be to hedges!!!&amp;quot;  lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:56:40 </td>
   <td style="text-align:left;"> $spy $qqq they bought the dip .. it wasn’t one though </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:56:15 </td>
   <td style="text-align:left;"> $QQQ looks like Dec 20 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:56:08 </td>
   <td style="text-align:left;"> $QQQ STAY SHORT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:55:55 </td>
   <td style="text-align:left;"> Problem with staying long overnight is if the Nasdaq breaks ~15,600, you&amp;#39;re going to get a quick swoosh lower and this&amp;#39;ll lead to broad tech selling, regardless if your (tech) stock has held up on this decline. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:55:52 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $SMH … Jim Cramer just now : 👇🏻

If u hate I block .. But conversations I will allow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:55:39 </td>
   <td style="text-align:left;"> $SPY if you guys don&amp;#39;t understand macro now is the time to open your textbooks. The Fed is your enemy and is removing liquidity. This means markets will remain volatile and have a downward bias. It doesn&amp;#39;t matter if the company you own is changing the world, the valuation will come down to a reasonable multiple. Nothing is safe when the Fed tilts this hawkish $AAPL $TSLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:54:45 </td>
   <td style="text-align:left;"> $QQQ respecting the intraday channel. AH it&amp;#39;ll probably break down imo. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:53:51 </td>
   <td style="text-align:left;"> $SPY $QQQ guess we have to wait until 4:01pm to see the true move </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:53:20 </td>
   <td style="text-align:left;"> $QQQ get dumped on bulls. You&amp;#39;re more pitiful than the senior citizens I scammed with $Webistics </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:53:19 </td>
   <td style="text-align:left;"> $SPY $QQQ CHECK OUT THAT BIG BOUNCE IN JPOW aka The Market

Looks like the Bears are large and in charge for now

They need to swell the coffers to keep the BullTards in check </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:52:36 </td>
   <td style="text-align:left;"> INCREDIBLE first week of the year still another day left WOW $spy $qqq $amzn $tsla another 6k in futures!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:51:16 </td>
   <td style="text-align:left;"> $SPY $QQQ Weak bounce failed already ... false breakouts ... look out below tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:51:15 </td>
   <td style="text-align:left;"> $QQQ I see a big red Friday, zero support </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:51:00 </td>
   <td style="text-align:left;"> You can vote with your wallet &amp;amp; attention against censorship/corruption every day by boycotting Facebook,Twitter,Apple, Amazon ,Microsoft , Google,CNN  MSNBC &amp;amp; others. 
Money talks in language censoring goons understand.
Here are some suggestions:
-Cancel Cable ,Satellite, or Streaming TV bundles that have CNN/MSNBC
 
-Use web browsers like Brave  

-Use search engines like Brave 

-Use email service like ProtonMail 

-Use social media sites like MINDS,Parler &amp;amp; Gab 

-Post videos to Rumble,Odysee &amp;amp; Bitchute rather than youtube

-Shop online at Overstock &amp;amp; smaller retailers rather than Amazon

-Use Linux OS like Linux Mint or others on your PC rather than Windows, Mac or Chrome OS (Almost any PC can be switched to Linux)

-Use a degoogled Android OS smartphone rather than an  iPhone or Google Android

-Use Linux mini PC on your TV for web browsing/gaming/video streaming rather than fire tv/roku/chromecast/apple tv

Please share this action plan if you agree
$CFVI $DWAC $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:50:04 </td>
   <td style="text-align:left;"> $QQQ volume picking up. Bounce in route </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:49:36 </td>
   <td style="text-align:left;"> $QQQ $SPY Apple looks like shxt....how is this going to work. 😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:49:21 </td>
   <td style="text-align:left;"> $AABB 
Guaranteed 400% gainer with no brainer? Thats what Peter shared on the podcast today...hope you are not missing out on the lifetime opportunity. Wee Green, Tho everything else is Ruin. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:49:14 </td>
   <td style="text-align:left;"> $QQQ 
You’ve been working all day. Take a break and a day off tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:48:36 </td>
   <td style="text-align:left;"> $QQQ where’s your money printer idiots?  Oh yeah it doesn’t exist anymore. Whoops! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:48:04 </td>
   <td style="text-align:left;"> $CNTB might get interesting - no one paying attention to it yet  $SPY  $QQQ have a look at $CNTB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:47:49 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $CHPT i love chipotle so much man </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:46:24 </td>
   <td style="text-align:left;"> $SPY $QQQ algos starting to lose their grip as volume picks up. hold on boys :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:46:17 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ Same narrative over the last few years, “Don’t fight the Fed” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:45:54 </td>
   <td style="text-align:left;"> $QQQ puts are cold product </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:45:15 </td>
   <td style="text-align:left;"> $qqq benchmark stks continue to punish the little guy 😠 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:45:10 </td>
   <td style="text-align:left;"> $QQQ dump it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:45:03 </td>
   <td style="text-align:left;"> $SPY $SPX $DJIA $NASDAQ $QQQ a radical change from QE to QT. 10%-30% Drop for sure the next two months.

The Federal Reserve is scaring markets with the triple threat of policy tightening

https://www.cnbc.com/2022/01/06/the-fed-is-scaring-markets-with-the-triple-threat-of-policy-tightening.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:45:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 49988700. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:44:54 </td>
   <td style="text-align:left;"> $QQQ pushhh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:44:48 </td>
   <td style="text-align:left;"> $QQQ green! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:44:48 </td>
   <td style="text-align:left;"> $QQQ sell off friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:44:47 </td>
   <td style="text-align:left;"> $QQQ Keep selling Fed. You&amp;#39;ve still got a fewer dollars lower to go for that game you played all day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:43:58 </td>
   <td style="text-align:left;"> $QQQ $AAPL apple breaks support of 172 more downside for market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:43:57 </td>
   <td style="text-align:left;"> $QQQ what a fucking rug pull towards the close.  Everything has been so shit since the powell pivot.  :( </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:43:57 </td>
   <td style="text-align:left;"> $SPY $QQQ it’s time for small caps soon, F the big tech </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:43:44 </td>
   <td style="text-align:left;"> $QQQ sitting on 100ma... usually finds support there. See if it holds true again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:43:37 </td>
   <td style="text-align:left;"> $QQQ $270 is the bottom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-07 04:43:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $VXX betting on volatility in January is practically free money. Plays out every time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:56:20 </td>
   <td style="text-align:left;"> $AAPL   Ouch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:55:42 </td>
   <td style="text-align:left;"> $TSLA  I need to recover some losses from stupid $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:55:23 </td>
   <td style="text-align:left;"> $AAPL Yep! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:55:16 </td>
   <td style="text-align:left;"> $AAPL who is saying “wow Apple is a great deal” they haven’t made any more profit than the last 3 years yet they are trading 5x from 3 years ago like a growth stock. Puts will print. Apple back to 150 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:53:00 </td>
   <td style="text-align:left;"> $AAPL&amp;#39;s ROE of 150.07% is amongst the best returns of the industry https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:52:40 </td>
   <td style="text-align:left;"> $AAPL wonder why 1/21 calls are so cheap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:51:31 </td>
   <td style="text-align:left;"> $AAPL Four years of buying and haven’t sold 1 share. Bigger the dip more I buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:46:01 </td>
   <td style="text-align:left;"> $AAPL Could at least see a short-term bounce near here:  see 30min A-D_stoch, into OB area but does have a little room lower if it wants.  
Both TSI indicators (bottom 2 panes) still heading lower.  Short-term momentum almost has a similar look (a step behind) NFLX chart shared.  

Primary expectation:  Another day or so lower or sideways (inside range) then stabilize.  
Assess there if momentum improving  261.8 fib is ~188 (longer TF).  

Hypo 2:  short-term bounce met by further selling.  Levels below are 161.8 fib (~169) then dynamic S/R + 141.4 fib (~165, also see volume profile to the left). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:42:57 </td>
   <td style="text-align:left;"> $SPY #NFLX $AAPL #GOOGL   #FB #AMZN   
 
caution under the ichimoku cloud for Cheese Omelettes. 
 (trend is bearish under cloud, bullish above, per ichimoku rules) 
It&amp;#39;s been years since these names been under cloud for more than a coffee. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:40:30 </td>
   <td style="text-align:left;"> $AAPL tomorrow gonna be hilarious for the bulls. Might even have a tiny gap up into a rip roaring sell off after all the rookies got their calls 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:39:37 </td>
   <td style="text-align:left;"> $AAPL wtf was that ? 172.12 from 172.72 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:38:02 </td>
   <td style="text-align:left;"> $AAPL Fully expect substantial upside movement tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:31:39 </td>
   <td style="text-align:left;"> $AMD $AAPL $TSLA what would you do? https://reddit.com/r/hmm/comments/rxkbeo/hmmm/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:28:04 </td>
   <td style="text-align:left;"> $AAPL features ripping but watch in ur morning freaking go red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:27:28 </td>
   <td style="text-align:left;"> $AAPL I feel it time to go up nice bottom rebound coming up long hold so I don’t care but looks like a nice bounce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:24:24 </td>
   <td style="text-align:left;"> $AAPL she’s about to rip at the bottom! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:24:23 </td>
   <td style="text-align:left;"> $AAPL the support at 171.90 was strong today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:23:37 </td>
   <td style="text-align:left;"> $AAPL So is the nonsense of these past two days now behind us? Who knows with this crazy market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:21:23 </td>
   <td style="text-align:left;"> $DOCU and $AAPL Puts tomorrow 
For Lottos 
Along with $avct &amp;amp; $reli </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:19:34 </td>
   <td style="text-align:left;"> $AAPL loaded up and ready for moon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:16:18 </td>
   <td style="text-align:left;"> $AAPL still holding well despite many others are tanking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:16:14 </td>
   <td style="text-align:left;"> $AAPL  hike rates and fed news subside soon, possibly Tomrrow? . These fool that sell, feel the regret soon.  Bears don’t understand, when it drop is a gift for bulls to load up! After 2 days it drop 10$ expect 175-180 soon. Bears lock your gains before to late ! The curve of macd and stochasticSlow is bullish $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:12:41 </td>
   <td style="text-align:left;"> $AAPL well done👍 .. good night from germany🍏🍏🍏🍻🍻🍻🍻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:12:14 </td>
   <td style="text-align:left;"> $AAPL to those morons that continue to say Apple doesn’t innovate. FYI - Apple has to date been awarded over 72,000 patents. Right, they do not innovate. Now you can all just go away for good please. I’ll block you anyways. 🤡’s. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:10:16 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $MSFT $TSLA 

If hedged funds and CEO&amp;#39;S are selling..

 fck this 💩

I&amp;#39;m loading PUTS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:10:06 </td>
   <td style="text-align:left;"> $AAPL Sold of EOD, people tapping into cash? https://youtu.be/0tdXXVBBYwk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:08:16 </td>
   <td style="text-align:left;"> SweepCast alerted: $AAPL with Unusual Options Activity Alerted on $175 PUT Expiring: 01-21-2022 worth 948K🐻 |🥇  Highly Aggressive Buyers Above Asking Price | SweepCast.com or Premium Room ➡️  #investingtips </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:07:41 </td>
   <td style="text-align:left;"> $AAPL LETS GO!!!!!!! $180 tomorrow!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:05:05 </td>
   <td style="text-align:left;"> $SPY HELLO EVERYONE IM LOOKING TO DIVERSIY MY PORTFOLIO. HOW DO I PURCHASE A 2000-YEAR TREASURY BOND? THANKS IN ADVANCE $QQQ $IWM $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:01:32 </td>
   <td style="text-align:left;"> $AAPL support is 150 but doubt it gets anywhere near that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 08:01:06 </td>
   <td style="text-align:left;"> latex40880684bb63ac79eddb7678284cb2ee$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:53:45 </td>
   <td style="text-align:left;"> $SPY  faang getting hit. 
 
*Updated DEC 30th $FB  Rudolph chart..   
 
$AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:53:07 </td>
   <td style="text-align:left;"> $AAPL back to game. Institutions loaded today. $176.00 tomorrow on the road to $200.00. Expect an upgrade in the morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:50:54 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #1 ticker with sweep activity where institutions are trading options urgently with 86.1K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:49:36 </td>
   <td style="text-align:left;"> $AAPL looks like $GME will bring down the rest of the market 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:49:21 </td>
   <td style="text-align:left;"> $ENPH Just read this fucking slide carefully and think it through....Bardi is setting up to be the $AAPL of Household Distributed Energy, and IQ8s are the iPhone that will carry Enphase kit into every home. Then GaN IQ9s are coming.

I&amp;#39;m half expecting an aquisition on Blockchan Transactive Energy...I&amp;#39;ll will shoot my wad if he does that. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:46:48 </td>
   <td style="text-align:left;"> $AAPL contagion. 
 https://www.reddit.com/r/Epic_Economics/comments/rxsjza/nas100_fallout_buyer_beware_growth_at_all_costs/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:43:43 </td>
   <td style="text-align:left;"> $AAPL $AMZN $TSLA Todays OP Highlights

Ready for tomorrow’s plays?

https://www.instagram.com/reel/CYaEjSILuiB/?utm_medium=copy_link </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:30:53 </td>
   <td style="text-align:left;"> $AAPL anyone else having issues w iCloud email server? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:29:49 </td>
   <td style="text-align:left;"> $AAPL Long. No worries. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:29:18 </td>
   <td style="text-align:left;"> $AAPL Inverted hammer here on daily after 3 red days, inverted hammer can be sign of bottom after a dip. One to keep on watch here. https://share.trendspider.com/chart/AAPL/81303loyua </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:29:12 </td>
   <td style="text-align:left;"> $AAPL Apple CEO Tim Cook’s compensation rises to nearly $100 million thanks to new stock award </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:27:11 </td>
   <td style="text-align:left;"> $AAPL technical analysis for tomorrow.

https://youtu.be/11NVhXo8NG8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:25:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL

Tomorrow could decide a lot for which way the market moves in 2022 in my opinion. Question is does the market move up or descend down...😈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:24:47 </td>
   <td style="text-align:left;"> $AAPL boughf more today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:22:45 </td>
   <td style="text-align:left;"> $AAPL ripping AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:20:24 </td>
   <td style="text-align:left;"> $AAPL Simulated 175.0 dollar CALLS for Friday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:19:39 </td>
   <td style="text-align:left;"> $AAPL is apple still buying back stock? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:17:35 </td>
   <td style="text-align:left;"> $AAPL made in China Stonks. Profits over people. ☠️
 https://www.reddit.com/r/Epic_Economics/comments/rxrwvv/defaulting_on_debt_market_contagion/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:17:34 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $TSLA 

Futures update for the shorts 

👇👇👇👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:14:06 </td>
   <td style="text-align:left;"> $SPY I started my week shorting the $QQQ. Sold on Tuesday and shorted $AAPL at the bell. Sold those puts at yesterday’s bell and switched to $DIA puts. I sold the DIA at today’s bell and went cash. Man I’ve had a hell of a week. I think we go up gradually all day tomorrow until 2:00. That’s when I buy puts and hold over the weekend. Bearish for now. I believe tomorrow’s bell will be bloody </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:07:45 </td>
   <td style="text-align:left;"> $AAPL Warren dumped on your dumb faces </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:07:38 </td>
   <td style="text-align:left;"> $AAPL Where world Apple be in the top 10. https://youtu.be/nbtyZxVZpkE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:06:07 </td>
   <td style="text-align:left;"> $AAPL Time for the AAPL haters and doom sayers to yell “sell” like they do year after year, month after month.  You’d think after being continually wrong for 10 years they’d learn it is time to quit being wrong. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:03:39 </td>
   <td style="text-align:left;"> $QQQ $AAPL $TSLA $MSFT $GOOGL 

BUT BUT BUT THE FED 😆

PRICED IN. 

Shorts are about to get taken to the woodshed!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:02:48 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA 

Hard to sustain a FED-sponsored bull market without the FED! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:01:25 </td>
   <td style="text-align:left;"> $EMAN $AAPL https://www.emagin.com/investors/press-releases/news-2021/551-eaginorporationntroducesorldsrightestullcolor20211101042003 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 07:01:19 </td>
   <td style="text-align:left;"> $AAPL Earnings coming up my time to buy😍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:57:51 </td>
   <td style="text-align:left;"> $AAPL will hold their 2022 shareholder meeting on March 4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:57:43 </td>
   <td style="text-align:left;"> $SPY BREAKING NEWS: No more pole dancing first ladies who hate America and cannot speak English. $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:53:49 </td>
   <td style="text-align:left;"> $AAPL can we please have a green day for once tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:52:46 </td>
   <td style="text-align:left;"> $AAPL 

I could really use a face ripping short squeeze right about now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:52:34 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:52:04 </td>
   <td style="text-align:left;"> $AAPL CNBC not talking about Apple too much, they dont want your eyes on it heading into earnings. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:52:00 </td>
   <td style="text-align:left;"> The industry average ROA is 5.50%. $AAPL outperforms 97% of its industry peers. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:51:19 </td>
   <td style="text-align:left;"> $SPY Deadly insurrection at the U.S. Capitol a year ago is part of a broader war on democracy by Donald Trump. Trump lost the election by a mile, and now he&amp;#39;s saaad. $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:50:53 </td>
   <td style="text-align:left;"> $AAPL YES UNCLE JOE...IT WAS SO SCARY. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:49:39 </td>
   <td style="text-align:left;"> $SPY $AAPL $UVXY   received first order from misfits.com  28.00 - organic produce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:45:29 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple CEO Tim Cook&amp;#39;s compensation rises to nearly $100 million thanks to new stock award https://www.stck.pro/news/AAPL/21000722 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:45:05 </td>
   <td style="text-align:left;"> $AAPL 

https://www.bloomberg.com/news/articles/2022-01-06/nasdaq-s-1-trillion-rout-fuels-concern-of-a-bumpy-ride-in-2022

1 trillion dollars off ..

That’s what you use Fed decision to spark dirty sell off ..

Time to back the fuck UP .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:44:47 </td>
   <td style="text-align:left;"> $AAPL $MSFT mms taking those January options then we fly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:41:54 </td>
   <td style="text-align:left;"> $AAPL my 50 shares already making some money :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:41:17 </td>
   <td style="text-align:left;"> $SPY you don’t sell $MSFT and you don’t sell $AAPL. So the narrative to sell was Covid, and now that that’s over it’s the yield. The yield was at 3% and these companies roared. They will to continue. Have a 2,5,7,10 year horizon and ride this out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:41:17 </td>
   <td style="text-align:left;"> $AAPL Bullish Doji Star setup: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:40:25 </td>
   <td style="text-align:left;"> $AAPL Cook made $100 Million last year. He mad 700% more then the year prior. Y&amp;#39;all think Apple employ got a raise?? Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:40:07 </td>
   <td style="text-align:left;"> $AAPL $PLTR i think my trading “career” is coming to an end. I had an account balance of about 80k. I’m down to these last plays. I can barely sleep at night. If these two positions could just bring me back to 40k overall I think I would just close shop. Any chance these can get me there? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:39:34 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $DWAC

YIKES!!😱 LOOKS LIKE TOMORROW 

PEARS BEGGIN GETTING CLAPPED BY 

NEWBY GEN Z TRADERS...🤣🤣📈

https://apple.news/AlTa4NPOKRt6lphh2JxBgBw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:37:32 </td>
   <td style="text-align:left;"> $msft $aapl $nvda $amzn https://www.youtube.com/watch?v=tDybEAtDbuc&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:33:21 </td>
   <td style="text-align:left;"> $QQQ $AAPL $TSLA $MSFT $GOOGL  Anyone know what a triple bottom and inverse head and shoulders equals tomorrow? 😆🚀🐂

ADD IN THE SHORT COVERING AS WELL 😱👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:27:32 </td>
   <td style="text-align:left;"> $AAPL get ready for super red tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:25:46 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ whens these fed news and rate hike news subside in 2-4 days , watch we make a run again.  Take this opportunity to load calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:22:24 </td>
   <td style="text-align:left;"> $AAPL who doesn’t have Webull here and wants to help a brother out? You open an account and deposit any money, you get free stocks and so do I. 

Let me know if you’re interested! Free money. Just gotta use my link </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:22:14 </td>
   <td style="text-align:left;"> $GME $AMC dont miss out buy low sell high $AAPL $TSLA gla. 💵💵💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:20:12 </td>
   <td style="text-align:left;"> $AAPL Guys, no sweat it. We are moving on EV’s. You should see PR’s coming in the days ahead. $5T is a real number when that product line opens. Hold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:19:30 </td>
   <td style="text-align:left;"> $1 Trillion Wipeout On Nasdaq Begins To Moderate - TheStreet $QQQ $QQQJ $TQQQ $TSLA $AAPL  https://apple.news/AoAVa0lEKS5uXRJwzjNb6fA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:18:30 </td>
   <td style="text-align:left;"> $AAPL Why hold $AAPL  When you can gain more with $AMC MOASS! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:18:22 </td>
   <td style="text-align:left;"> $AAPL apple store nft’s please </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:18:10 </td>
   <td style="text-align:left;"> $AAPL baba going up now and we crashing here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:18:00 </td>
   <td style="text-align:left;"> Stock market outlook: Fed sell-off is a big buying opportunity - Business Insider $QQQ $TQQQ $QQQJ $AAPL $NVDA  https://apple.news/AJtuIi13RQxmlJ6ZQPSTeOQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:17:29 </td>
   <td style="text-align:left;"> latexdd0ad37f7854fa46c2126a1c886c57c5 tomorrow and 180$ eow ...smoke that in ur bear pipe 🤒 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:17:28 </td>
   <td style="text-align:left;"> $AAPL   Risk on trade tomorrow cause of GameStop &amp;amp; AMC.

I&amp;#39;m playing it safe with Apple. It&amp;#39;s already moving after hours + T-Mobile released new subscriptions which we know are mostly iphones.

Job report in the AM. 

Apple been down the last few days.

Many reasons to be long here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:14:28 </td>
   <td style="text-align:left;"> $AAPL omg how much lower this wull go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:14:22 </td>
   <td style="text-align:left;"> $QQQ $AAPL $TSLA $MSFT $GOOGL  the QQQ opens above this, everything is going to TAKE OFF LIKE A ROCKET 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:13:49 </td>
   <td style="text-align:left;"> $ATOM ATOMERA.  Rumors connect it to $TSLA, $AAPL, and now US Air Force and by extension the US DoD.   Waiting patiently and adding at these pps. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:13:27 </td>
   <td style="text-align:left;"> $AAPL lol. Remember MAGA? lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:09:28 </td>
   <td style="text-align:left;"> $DWAC $AAPL $MSFT $TSLA  Money news for all investors https://seekingalpha.com/news/3785983-trump-spac-digital-world-acquisition-jumps-on-plans-to-start-truth-social-feb-21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:05:26 </td>
   <td style="text-align:left;"> $AAPL careful bears, the fed news will fade and the drop will push back up. I made 610$ under an hour . Then I have freedom and not watch the market all day ! Don’t care what market do, I repeat next day! I been doing this awhile , regardless if I miss more gains or not, to me the freedom and repetition in long run will make it . I do see Appl bounce back up before 1/27 earnings. This just a scare sell off to lock gains for a run too  earnings.  So watch out bears , the oversold in 1hr and 4hour has a big potential to bounce and see 175-180s .  I see a curve :) and that to me is bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:05:19 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple to hold annual shareholder meeting virtually, SEC filing says https://www.stck.pro/news/AAPL/20999435 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:02:59 </td>
   <td style="text-align:left;"> $AAPL GME up 40% AH on NFT news. Bears better hope Apple pay dont get involved with NFT&amp;#39;s =4 trillion dollar market cap...LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 06:00:09 </td>
   <td style="text-align:left;"> $AAPL 177.5C Exp:07-Jan-22 --  🚀 &amp;lt;R&amp;gt; Total(Day): $125,623 
$AAPL 185C Exp:16-Sep-22 ↑  🚀 Total(Day): $36,000 
$AAPL 185C Exp:28-Jan-22 --  🚀 Total(Day): $39,780 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:58:46 </td>
   <td style="text-align:left;"> $AAPL 📜 SEC Form DEFA14A filed by Apple Inc.

https://quantisnow.com/insight/2225464?s=s

45 seconds delayed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:58:05 </td>
   <td style="text-align:left;"> $AAPL chart looks like an inverted slice of meatloaf, with a possible power drill on the 30 second chart. Tomorrow should setup nicely for a triple ski slope top. Man some of ya’ll and your non sense </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:55:53 </td>
   <td style="text-align:left;"> $AAPL already down 6% from its recent ATH. That’s enough. Time to get to $3 trillion and never look back. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:55:15 </td>
   <td style="text-align:left;"> $SPY JANUARY 6 - Never again will we allow traitors and criminals try to take down the United States of America.  NEXT TIME, SHOOT ON SIGHT. $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:50:22 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:48:40 </td>
   <td style="text-align:left;"> $AAPL small fish here but added 2 more shares today. Holding 42 total now with average at 125 per. Slow and steady right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:48:35 </td>
   <td style="text-align:left;"> $AAPL 👍🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:48:10 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 1/6/2022 $SPY $XLF $QQQ $VIX $AAPL https://www.chartguys.com/daily-market-videos/4099/bulls-stop-the-bleed-for-now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:47:57 </td>
   <td style="text-align:left;"> $AAPL buying 50 shares tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:45:49 </td>
   <td style="text-align:left;"> $AAPL right side is bullish on multiple timeframes.  We only like to buy it in 3, 7 or 11 swing at the blue boxes.   Like to watch the $NQ_F at equal leg which can give some sense of timing for larger cap tech for buy areas. We don’t like to trade it in the middle area right now.   #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:45:28 </td>
   <td style="text-align:left;"> $PLTR $AAPL $TSLA $TQQQ  Look I’ll say it louder. BUY SHARES LIKE A MAN AND YOU DONT HAVE TO WORRY ABOUT ALL THIS TALK OF CRASHING AND CORRECTION. Bought shares years ago and just sit back with a stop loss. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:45:06 </td>
   <td style="text-align:left;"> $AAPL time to go downnn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:44:43 </td>
   <td style="text-align:left;"> $AAPL inverted hammer maybe a start of HL and reversal. Looking for confirmation candle tom. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:44:35 </td>
   <td style="text-align:left;"> $CGC $WEED.CA  still believe this is  $AAPL of marijuana sector. And $TLRY will be pay off my looses. Just government is dragging there feet to legalized.  And we are paying the price. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:39:56 </td>
   <td style="text-align:left;"> Apple: (1) Amount Previously Paid  https://www.conferencecalltranscripts.com/summary/?id=10297897 $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:39:41 </td>
   <td style="text-align:left;"> $QQQ $AAPL $TSLA $MSFT $GOOGL  another look for the rookies still holding PUTS screaming FED 😱😆🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:37:52 </td>
   <td style="text-align:left;"> $AAPL [15s. delayed] filed form DEFA14A on January 06, 16:33:53 https://s.flashalert.me/5UDpz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:36:41 </td>
   <td style="text-align:left;"> Apple Inc. releases salary data. CEO sees compensation rise 568% https://www.conferencecalltranscripts.com/summary/?id=10297856 $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:36:16 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 465.3K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:35:55 </td>
   <td style="text-align:left;"> $AAPL Form DEFA14A (additional definitive proxy soliciting materials and rule 14(a)(12) material) filed with the SEC 

https://newsfilter.io/a/faf50a88d427a5a840aeb67b1431e3d1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:35:20 </td>
   <td style="text-align:left;"> $DWAC $AAPL and $GOOGL will try and suppress it by removing truth social from the App Store on launch day. Good thing they have $1 billion in cash to sue when they do. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:32:33 </td>
   <td style="text-align:left;"> $AAPL 📜 SEC Form DEF 14A filed by Apple Inc.

https://quantisnow.com/insight/2225404?s=s

45 seconds delayed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:32:20 </td>
   <td style="text-align:left;"> $AAPL / Apple files form DEF 14A https://fintel.io/sf/us/aapl?utm_source=stocktwits.com&amp;amp;utm_medium=Referral&amp;amp;utm_campaign=filing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:32:18 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-06 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=c8zSDug38yk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:32:15 </td>
   <td style="text-align:left;"> $AAPL [15s. delayed] filed form DEF 14A on January 06, 16:30:34 https://s.flashalert.me/4Eohe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:31:49 </td>
   <td style="text-align:left;"> $SPY $AAPL $QQQ $WFC $TSLA 
LIMIT  UP , circuit breakers! futures are going to rip all night🔥🔥 folks  welcome the Revolution,  welcome the good life! I hope everyone loaded up huge on calls  cuz   tomorrow’s gonna be a Friday you’re gonna remember </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:31:45 </td>
   <td style="text-align:left;"> $AAPL Simulated 175.0 dollar CALLS for Friday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:31:43 </td>
   <td style="text-align:left;"> $AAPL Form DEF 14A (other definitive proxy statements) filed with the SEC 

https://newsfilter.io/a/f38cc33e8c209becb31060d730c1e0c5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:30:37 </td>
   <td style="text-align:left;"> Would like to take a poll....you think $AAPL $HUM will slide lower at the open tomorrow before reversal? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:29:51 </td>
   <td style="text-align:left;"> $QQQ $AAPL $TSLA $MSFT $GOOGL 

Anyone see a pattern here?

The Fed lol, oh my LORD this shit has been priced in for a YEAR!!!

Tech just needed to cool off, and it has. Guess what’s next??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:28:28 </td>
   <td style="text-align:left;"> $AAPL This is how I have been feeling every day this week. Still holding strong and long. Dont have weak hands. 

https://www.youtube.com/watch?v=bbNsr8zuzI8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:28:25 </td>
   <td style="text-align:left;"> $AAPL 200 open tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:28:13 </td>
   <td style="text-align:left;"> Waiting on a dip towards 165 to load 190c $AAPL 
January will be a weird trading month very weird in the stock market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:28:00 </td>
   <td style="text-align:left;"> $AAPL 

Now going to block all the bears !! They don’t give reason for it to drop .. they just tell me to read books or etc 

That’s bullshit.

I said this is no way this should go down just 5% like that for no reason.. besides Fed small changes to monetary policies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:27:50 </td>
   <td style="text-align:left;"> Most Traded Contracts

$T January $23 Call
$AAPL 07 January $175 Call
$AAPL 07 January $177.50 Call
$T January 2023 $20 Call
$T January $22 Call
$T June $23 Call
$AAPL 07 January $170 Put
$T June $21 Call
$AAPL 07 January $172.50 Put
$F 07 January $24 Call </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:27:11 </td>
   <td style="text-align:left;"> latexa83cdf5e97de5c5630a11fbbdf8a4a17AAPL 175 C @ 1.3 -&amp;gt; 1.8 PT1 HIT (+38%) 🔥
$LMND 35 P @ .4 -&amp;gt; .95 PT3 HIT (+138%) 🎯 
[Low vol/liquidity here, but trade ran perfectly]

All Alerts &amp;amp; Watchlists posted on Discord Daily (Patrons) 
Link in Bio 🧀
Free Lotto Friday Watchlist posted tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:23:40 </td>
   <td style="text-align:left;"> $AAPL A drag on the entire market, SPY, QQQ, everything…… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:23:00 </td>
   <td style="text-align:left;"> $AMZN  Here is my end of the day analysis:
First congrats 🎉🎊 to all of those who bought the Dip this morning. Like Warren Buffet said buy when others are fearful and sell when they are greedy. I see we printed that Long leg Doji. Following AMZN pattern it is usually followed by few bullish days. Check it out. I still believe in my PT $3600 in 2 weeks. Time will tell.. $AAPL $FB $BABA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:22:23 </td>
   <td style="text-align:left;"> $QQQ $AAPL $SPY $UVXY  6 total $TQQQ buy the dip and sell the rip scalps. Last dip buy before the close and sale after hours. You can trade with me and Finom Group folks! (1/2) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:21:42 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:21:42 </td>
   <td style="text-align:left;"> $AAPL tomorrow $178 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:21:20 </td>
   <td style="text-align:left;"> $AAPL haha delusional bulls crying help when this POS is only down 5 points from close Friday / open Monday.  Shove 3 tril up your ass </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:20:45 </td>
   <td style="text-align:left;"> $AAPL if you bought that dip before bell close. You will make money tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:20:17 </td>
   <td style="text-align:left;"> $AAPL wouldn’t be surprised if we test $168.50 tomorrow. Many stoplosses will be fucked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:19:49 </td>
   <td style="text-align:left;"> $AAPL I DONT GIVE A F WHAT A BEAR HAS TO SAY...THIS WILL BE OVER $180 BEFORE AND AFTER ER. SELL IT IF YOU WANT BEARS. SHORT IT IF YOU WANT BEARS. IT GOES TO $160...I WILL JUST BUY MORE CALLS AND AVG DOWN. BEARS TALKING ABOUT TRADING 46 TIMES CASH...YEAH AND LOOK AT TELSA...LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:19:26 </td>
   <td style="text-align:left;"> $AAPL That Trillion dollars sure went fast !!!  What the hell ?!?!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:19:15 </td>
   <td style="text-align:left;"> $AAPL loaded aapl puts again at the close. Jan 21 $170 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:18:13 </td>
   <td style="text-align:left;"> $AAPL DWAC!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:17:47 </td>
   <td style="text-align:left;"> $AAPL can someone wake me up after it hit $185 in 1 week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:17:05 </td>
   <td style="text-align:left;"> $AAPL low volume day. tube in to cnbc to hear people talk non stop about “what’s going on” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:15:48 </td>
   <td style="text-align:left;"> $AAPL So overvalued! But you&amp;#39;ll see people blindly throwing there cash in here because it is apple and it has always gone up and probably will keep going up or the market will crash.  But compare this stock to the 100&amp;#39;s of growth stocks trading at cash value basically.  This trades at what 46 times it&amp;#39;s cash value and 8-9 revenue. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:15:06 </td>
   <td style="text-align:left;"> $AAPL really hoping for a strong bounce from here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:09:13 </td>
   <td style="text-align:left;"> This is why Hedge Funds use A.I. $AAPL in Downtrend: RSI indicator exits overbought zone. View odds for this and other indicators: https://srnk.us/go/3303680 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:08:14 </td>
   <td style="text-align:left;"> $AAPL we need news of tarrifs or Monopoly to significantly drop Apple. Other than that it&amp;#39;s green as usual. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:08:12 </td>
   <td style="text-align:left;"> $AAPL BULLSHIT BULLSHIT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:07:22 </td>
   <td style="text-align:left;"> $MSFT $AAPL $FB $AMZN Added more msft and fb. Invested in aapl and amzn today. Thanks for the dips. I don&amp;#39;t care what your charts tell you. I also don&amp;#39;t give a crap about fed. All I know is  that when these te h giants drop so big, you add....especially few weeks before earnings. Bring it on shorts! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:06:53 </td>
   <td style="text-align:left;"> $AAPL nice bounce incoming for tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:06:44 </td>
   <td style="text-align:left;"> $AAPL ER report will increase volitility IV will rise. You dont want to be a buyer then. You want to be a seller. Stay ahead of the game </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:06:22 </td>
   <td style="text-align:left;"> $FUTU Alerted earlier today. Timed the top neatly. 

We banking tomorrow.

Congrats gentlemen. 🤞🧸💰

$AAPL $FB $MARA $BTC.X 

Doubters to believers. 🧸🤞

I don&amp;#39;t respond to dms. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:05:54 </td>
   <td style="text-align:left;"> $AAPL earning will be terrible, sell everything </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:05:48 </td>
   <td style="text-align:left;"> $AAPL down 5% in two days because interest rates? wtf? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:05:41 </td>
   <td style="text-align:left;"> $AAPL Fair Value remains at 30$. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:05:41 </td>
   <td style="text-align:left;"> $AAPL Closed short. Hesitant on the cover, but there could be a nice relief bounce tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:05:29 </td>
   <td style="text-align:left;"> $AAPL THIS BULLSHIT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:04:31 </td>
   <td style="text-align:left;"> $AAPL A lot of key supports level lost today . It might be a wrap for Apple until the Q2 Earnings run up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:04:12 </td>
   <td style="text-align:left;"> $AAPL Bloodbath coming tomorrow. Anyone with a brain is selling. Powell is taking money out the economy started in a few months which means unless you’re short the market your portfolio will get drained as the money supply is drained. Really common sense! 
 
Enjoy!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:03:49 </td>
   <td style="text-align:left;"> $AAPL https://stocktwits.com/Venuspre/message/424274488 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:02:49 </td>
   <td style="text-align:left;"> $AAPL 
 
Wow just fucking $10.00 off from Monday Close of Day.

182.01 on Monday Close of Day to 172.01 today Close of Day.

That was so steep drop - about 5.5% drop in three days.

While all the indications 1st month and 3rd month is alerting oversold .. the seller never stop attacking it .. 

Tmw .. back the fuck this stock up! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:02:09 </td>
   <td style="text-align:left;"> $AAPL 3 red days for Apple is unheard of..Tomorrow big bounce IMO. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:01:28 </td>
   <td style="text-align:left;"> $AAPL TSLA and AAPL earnings on the sam week. This month will be exciting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:01:16 </td>
   <td style="text-align:left;"> $BTC.X if you’re watching, this is a pending dumpster fire in the short term. Along with $AAPL and $QQQ  and most of the rest of the temporarily overvalued and sheep infested market. 

I smell a markets in turmoil episode coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:00:38 </td>
   <td style="text-align:left;"> $AAPL 

How is this down more than Ark today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:00:37 </td>
   <td style="text-align:left;"> $FB been alerted earlier today. Timed the top perfectly. 🤞💰

Congrats gentlemen. 

Tomorrow we feast.

$AAPL $FUTU $MARA $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:00:29 </td>
   <td style="text-align:left;"> $AAPL That&amp;#39;s it. If ya didnt sell. Well.......... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 05:00:01 </td>
   <td style="text-align:left;"> $AAPL sickening </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:59:12 </td>
   <td style="text-align:left;"> $AMD $NVDA $AAPL $AMZN $TSLA 
They did 3 Red days on Nasdaq and lets pump Tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:58:31 </td>
   <td style="text-align:left;"> $AAPL Tomorrow will be green...This is a baby pullback. ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:58:22 </td>
   <td style="text-align:left;"> $AAPL yesterday I swung calls overnight. Today it’s puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:58:20 </td>
   <td style="text-align:left;"> $AAPL lovely, as expected.

Congrats gentlemen. 💰🤞

Closed my position. 

$FB $FUTU $MARA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:58:07 </td>
   <td style="text-align:left;"> $aapl euphoria at 181 and doom at 172. Smh when i bought puts, i shorted a bunnch after the drop thinking it wont Bend over like Pakistan in 1 day but costly mistake. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:58:04 </td>
   <td style="text-align:left;"> $AAPL wow 12 haircut in 3 days unreal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:57:47 </td>
   <td style="text-align:left;"> $BB $AAPL 

404 Not Found😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:57:34 </td>
   <td style="text-align:left;"> $AAPL so, how many million shares trade in the last second today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:56:47 </td>
   <td style="text-align:left;"> $TSLA $AAPL $SPY distribution? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:56:44 </td>
   <td style="text-align:left;"> $AAPL $BA  HOLD BITCHES </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:55:39 </td>
   <td style="text-align:left;"> $SPY if you guys don&amp;#39;t understand macro now is the time to open your textbooks. The Fed is your enemy and is removing liquidity. This means markets will remain volatile and have a downward bias. It doesn&amp;#39;t matter if the company you own is changing the world, the valuation will come down to a reasonable multiple. Nothing is safe when the Fed tilts this hawkish $AAPL $TSLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:55:17 </td>
   <td style="text-align:left;"> $AAPL puts to hedge your longs look good. $DWAC latexe8f93293807ee8c3fbe1300fba219c10TSLA 
$AAPL 
 
leaving a daily reversal candle on the Nasdaq. .
in any case, take advantage of the rebounds, because this continues. .
..... ** // </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:55:00 </td>
   <td style="text-align:left;"> $AAPL PE ratio 32.39 --- &amp;gt; 30.61 , not too outrageous for the car and AR And with continued iphone dominance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:54:28 </td>
   <td style="text-align:left;"> $AAPL Ready to gap fill... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:54:10 </td>
   <td style="text-align:left;"> $AAPL I sold my Walgreens calls to jump into Apple this week on Tuesday 😂 This market is something else </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:53:30 </td>
   <td style="text-align:left;"> Damn looks like they are going to try to keep it pinned without any volatility. $FB $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:52:31 </td>
   <td style="text-align:left;"> $AAPL I like when it moves a dollar or two in the last five minutes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:52:28 </td>
   <td style="text-align:left;"> So.... It&amp;#39;s going to join the billion apps in the $AAPL store and $DWAC runs w/ $PHUN. #FOMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:52:15 </td>
   <td style="text-align:left;"> $AAPL I sold a bunch of MCD to buy AAPL and I really screwed up this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:52:07 </td>
   <td style="text-align:left;"> $AAPL 172 serving strong support but I feel a leg down is going to happen. Could be wrong who knows </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:51:22 </td>
   <td style="text-align:left;"> $AAPL Not Worried!! This is by far my largest position of all times !!! Holding for 3 years ...APPLE will weather the Storm !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:51:08 </td>
   <td style="text-align:left;"> $aapl fucking hell dude are the sellers not tired? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:51:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 48 analysts. The buy consensus is at 83%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=analyst-ratings&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:50:33 </td>
   <td style="text-align:left;"> $AAPL so it only went up to $182 so big guys can show off $3T valuations? Now it is sucking balls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:50:18 </td>
   <td style="text-align:left;"> $AAPL $F $NOK $TSLA Hey, it&amp;#39;s me, the guy who called the SOLY buyout a year ago. I&amp;#39;m back to tell you to buy OTLK this tiny biotech will get bought out before EOY mark this post 🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:50:03 </td>
   <td style="text-align:left;"> $AAPL might drop to $165 or $170 but I think I’ll pick up a few shares for my core position at this price tomorrow could go either way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:49:07 </td>
   <td style="text-align:left;"> $AAPL my kids penny stocks are outperforming my blue chips </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:48:54 </td>
   <td style="text-align:left;"> $TSLA $AABB $AAPL $SBES </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:48:46 </td>
   <td style="text-align:left;"> $AAPL Remember this was $182 a few days and yall wish you could of had it at $171-172? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:48:09 </td>
   <td style="text-align:left;"> $AAPL Will do buybacks and dividends in fiscal 22 of at least $ 100 Billion combined, dont you love that stuff ? Imagine they do it every year. Easy hold forever stock. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:48:04 </td>
   <td style="text-align:left;"> $AAPL two red day and you start talking about Armageddon. This is the market… and yours is just noise. 🥱 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:48:02 </td>
   <td style="text-align:left;"> $AAPL Only adding 10k more in Feb calls tomrrow if need be. Other than that. Just chillin til ER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:48:01 </td>
   <td style="text-align:left;"> $AAPL looks like those calls I sold will expire WORTHLESS 😼 Like taking candy from a baby 😷 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:47:52 </td>
   <td style="text-align:left;"> $AAPL All I ask is for $174 tommorow to sell my calls . Please </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:47:48 </td>
   <td style="text-align:left;"> $AAPL breaking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:47:21 </td>
   <td style="text-align:left;"> Or do we get an uneventful close to today&amp;#39;s trading?  We&amp;#39;ll know in a few minutes.

$FB $MSFT $AAPL $CRM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:47:21 </td>
   <td style="text-align:left;"> $AAPL sh** </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:47:02 </td>
   <td style="text-align:left;"> $AAPL Apple is gonna drop 4 days in a row that’s lovely 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:46:56 </td>
   <td style="text-align:left;"> $AAPL 

These shorts are being ridiculous they are pushing all the way to oversold territory and over bottom 

This looks not natural.

These chart is based one month 

Oversold - tmw back the fuck up! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:46:17 </td>
   <td style="text-align:left;"> $AAPL $169s tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:46:04 </td>
   <td style="text-align:left;"> $AAPL distribution </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:45:50 </td>
   <td style="text-align:left;"> $AAPL what a joke </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:45:20 </td>
   <td style="text-align:left;"> It&amp;#39;s almost time for the volatility to start. 3:53 usually. 

$MSFT $AAPL $CRM $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:45:06 </td>
   <td style="text-align:left;"> $AAPL   🍏 Max Pain, is currently showing:  $175.00. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:44:28 </td>
   <td style="text-align:left;"> $AAPL 🦁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:44:22 </td>
   <td style="text-align:left;"> $AAPL $MSFT so simple to turn the markets red, just sell off microsoft and apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:44:11 </td>
   <td style="text-align:left;"> $AAPL only a clown will short the best company in the dam world!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:43:58 </td>
   <td style="text-align:left;"> $QQQ $AAPL apple breaks support of 172 more downside for market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:43:28 </td>
   <td style="text-align:left;"> $AAPL struggling all day to hold 173 that was key to grab $spy puts $spx </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:42:28 </td>
   <td style="text-align:left;"> $aapl so apple is not buying back ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:42:17 </td>
   <td style="text-align:left;"> $AAPL Gonna buy more calls. Just for earnings run up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:42:14 </td>
   <td style="text-align:left;"> $AAPL load uppp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:42:01 </td>
   <td style="text-align:left;"> $AAPL terrible week so far. 3 great weeks, 1 bad. Bummer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:41:53 </td>
   <td style="text-align:left;"> $AAPL Man , if bears played their cards right , they profited SERIOUS gains this week . Wish I was on the right side of the trade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:40:59 </td>
   <td style="text-align:left;"> $TSLA $QQQ $SPY $AAPL

SOMEONE FIND ME SOME INK FOR THE 

PRINTERS!!! 🖨 💵 💵 💵 💵 💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:40:37 </td>
   <td style="text-align:left;"> $AAPL back to $180 tmrw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:40:07 </td>
   <td style="text-align:left;"> $AAPL almost ready to load up again. Almost. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:39:57 </td>
   <td style="text-align:left;"> $AAPL tbh, this was the pivot point last few weeks.. Not gonna short here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:39:56 </td>
   <td style="text-align:left;"> $AAPL going to back to $140s in the next month! Powell killed $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:39:16 </td>
   <td style="text-align:left;"> $AAPL 🤯🤯🤯🤯🤯🤯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:39:14 </td>
   <td style="text-align:left;"> $AAPL banks selling the close 🥲171-170.8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:39:12 </td>
   <td style="text-align:left;"> $AAPL 

Beware a lot of short attack here .. we need to be viligant and play smart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:38:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL

THIS DIP IS TRANSITORY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:38:31 </td>
   <td style="text-align:left;"> I know those weekly calls look tempting. Be careful. 

$AAPL $MSFT $CRM $FB $NIO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:38:26 </td>
   <td style="text-align:left;"> $AAPL So what’s the pt for tommorow $168 ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:38:15 </td>
   <td style="text-align:left;"> $AAPL 165 incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:37:57 </td>
   <td style="text-align:left;"> $AAPL I lost too much money this week betting on Apple smh , I’m annoyed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:37:44 </td>
   <td style="text-align:left;"> $AAPL always tanks at the end of the day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:37:39 </td>
   <td style="text-align:left;"> $AAPL 

Oh yeah baby. No we free fall. Nothing to support us underneath.

Best of luck folks. 

Congratulations shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:37:31 </td>
   <td style="text-align:left;"> $AAPL $AMZN $DIS Yall ready to Stack MORE tomorrow?
Let’s get it!!!!

https://www.instagram.com/reel/CYZu8H6M03m/?utm_medium=copy_link </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:36:53 </td>
   <td style="text-align:left;"> NEW POST:  Sneaky, in Camouflage  https://marketchess.com/2022/01/06/sneaky-in-camouflage  $AAPL $MSFT $QQQ $TBT $TLT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:35:48 </td>
   <td style="text-align:left;"> $AAPL damn killing all calls for tomorrow fml </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:35:21 </td>
   <td style="text-align:left;"> $AAPL 170 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:35:18 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA here&amp;#39;s more

The worse thing that could happen to this current bull market is for the economy to markedly pick up. That growth would spur inflation, which along with improved sentiment, would make the Fed a lot more comfortable tightening at a faster pace. Liquidity would then be pulled from the system and drive the stock market lower.

Don’t confuse the stock market with the economy. Understand that the market is forward looking and the biggest lever on future demand is liquidity. That’s why you need to understand the reaction function of the Federal Reserve. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:35:11 </td>
   <td style="text-align:left;"> $AAPL 

Late dump. 

Ugh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:35:07 </td>
   <td style="text-align:left;"> $AAPL What a poor show.down $11 in 3 days. Unbelievable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:34:40 </td>
   <td style="text-align:left;"> $AAPL

Oh yeah. 

Anyone that&amp;#39;s watch a Tim Sykes infomercial is Shorting now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:34:25 </td>
   <td style="text-align:left;"> $AAPL Might have to use my free cash tomorrow. I will let it ride today. Holding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:34:15 </td>
   <td style="text-align:left;"> $AAPL $TSLA rekt. Don’t fight the Fed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:33:23 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL more Druckenmiller- &amp;quot;looking at the great bull markets of this century, the best environment for stocks is a very dull, slow economy that the Federal Reserve is trying to get going… Once an economy reaches a certain level of acceleration… the Fed is no longer with you… The Fed, instead of trying to get the economy moving, reverts to acting like the central bankers they are and starts worrying about inflation and things getting too hot. So it tries to cool things off… shrinking liquidity… [While at the same time] The corporations start having to build inventory, which again takes money out of the financial assets… finally, if things get really heated, companies start engaging in capital spending… All three of these things, tend to shrink the overall money available for investing in stocks and stock prices go down…&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:32:50 </td>
   <td style="text-align:left;"> $AAPL cmon give me 171 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:32:13 </td>
   <td style="text-align:left;"> $AAPL 

Call all Shorts with deep pockets. Lets go. Get this down to -$172. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:31:21 </td>
   <td style="text-align:left;"> $AAPL At this point bro i don’t care what happens just go back up to $174 tommorow so i can get out of these calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:30:55 </td>
   <td style="text-align:left;"> $AAPL Exactly. Algos WANT YOUR SHIT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:30:44 </td>
   <td style="text-align:left;"> $CLOV $TSLA $AAPL $BHG $HIMS 

Biden will talk about lowering Medicare by the end of this month.  His whole speech is about bringing millions of customers to Clover health using our AI software.  Oh yea Chelsea Clinton is a huge owner of this company 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:30:42 </td>
   <td style="text-align:left;"> $AAPL with an 8 year long, what’s a good price to dump? Think full crash not till spring? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:30:06 </td>
   <td style="text-align:left;"> Updated correlation matrix for Apple( $AAPL ), Cummins(… https://www.macroaxis.com/invest/marketCorrelation?s=AAPL,CMI,NEE,TEL,FDX,SWN,NEM,IRLTF,FAF,SRE,TSN,ACGL #correlations #stocks #stockratings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:29:58 </td>
   <td style="text-align:left;"> $AAPL I want to work for wallstreet and make u all rich. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:29:54 </td>
   <td style="text-align:left;"> $AAPL lose 172.26 and next week could be scary </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:29:54 </td>
   <td style="text-align:left;"> $AAPL Mutual Funds and other large brokers either sell the close or run it up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:29:45 </td>
   <td style="text-align:left;"> $AAPL pros want your cheap shares. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:29:28 </td>
   <td style="text-align:left;"> $AAPL hahaha donks of the administration </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:28:51 </td>
   <td style="text-align:left;"> $AAPL Should run up at close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:28:41 </td>
   <td style="text-align:left;"> $AAPL 150 price target March 18.

Big tech is about to get wrecked. Shorting the $NASDAQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:28:40 </td>
   <td style="text-align:left;"> $DWAC

&amp;quot;Trump&amp;#39;s new media venture plans to launch its social media app Truth Social on Feb. 21, according to an Apple Inc App Store listing&amp;quot; $AAPL $TWTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:28:35 </td>
   <td style="text-align:left;"> $AAPL Literally every other stock , every singe one is green on my watchlist except for this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:28:21 </td>
   <td style="text-align:left;"> $AAPL 

We need more Shorts. Put me out of my misery </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:28:08 </td>
   <td style="text-align:left;"> $SPY come one drop $AAPL just shit the bed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:28:03 </td>
   <td style="text-align:left;"> $AAPL Fkit. Added final position at 3.95. 60 Feb 18 $180 calls at 3.98 avg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:28:03 </td>
   <td style="text-align:left;"> $AAPL REPEAT GRENADES 💣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:28:00 </td>
   <td style="text-align:left;"> $AAPL 
Selling some apple to buy semiconductor stocks on the dip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:27:46 </td>
   <td style="text-align:left;"> $AAPL Added today. I add Apple Twice a Month, going on two years now. It pays off. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:27:28 </td>
   <td style="text-align:left;"> $AAPL 

We break this little support at around $172.15 and it&amp;#39;s a wrap for my calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:27:21 </td>
   <td style="text-align:left;"> $AAPL all I see is buying opportunity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:26:01 </td>
   <td style="text-align:left;"> $AAPL 

Yikes not surprising short are attacking !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:25:40 </td>
   <td style="text-align:left;"> $AAPL auvi will moon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:25:27 </td>
   <td style="text-align:left;"> $AAPL hurry get out. Apple is going out of business tomorrow. 🤣🤣. Everybody knows this will be $200 by 7/1/22 at the latest. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:25:26 </td>
   <td style="text-align:left;"> $AAPL the ONE week I buy calls instead of puts and Apple drops $10 😂 Wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:25:08 </td>
   <td style="text-align:left;"> Digital Health: Firms Advance Wearable Tech at CES 2022 | Investor&amp;#39;s Business Daily

$AAPL | $PTON |$GOOGL ( $FIT ) |  $PLNT  https://www.investors.com/news/technology/digital-health-firms-advance-wearable-tech-at-ces-2022/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:25:01 </td>
   <td style="text-align:left;"> $AAPL this pos never cease to amaze you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:24:57 </td>
   <td style="text-align:left;"> $AAPL 

Jeez. The free fall is just starting. Sat here all day and watched my Calls burn. 

Oh well. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:24:52 </td>
   <td style="text-align:left;"> $AAPL this is exactly what happened yesterday…drop before it close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:23:36 </td>
   <td style="text-align:left;"> $AAPL Half my original call position is back on at $4.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:22:57 </td>
   <td style="text-align:left;"> $AAPL the gains were good. Bye bye apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:22:45 </td>
   <td style="text-align:left;"> $AAPL SAVE US JOEY... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:22:13 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA here&amp;#39;s a gem from Druckenmiller.

&amp;quot;Earnings don’t move the overall market; it’s the Federal Reserve Board… focus on the central banks and focus on the movement of liquidity… most people in the market are looking for earnings and conventional measures. It’s liquidity that moves markets.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:21:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL

OOF.. DOWN GOES ANOTHER PRINTER... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:21:34 </td>
   <td style="text-align:left;"> $AAPL 

My own thinking is that they want you to forget about AAPL and make you look else where.

Imagine this stock has been stagnant for one month still stuck between 182 to 170 due to heavy short attacks and lots of pushing going on.

I was there for the most of Dec.

My thinking is that they do that to make people walk away and look outside investing. Then they took opportunity to reap gain when no body is on board.

That’s dirty game ..

Saw that 140, 150, 160, 170, and 180

I think they want to consolidate earlier before the take off before the ER and rise even higher before the tax seasons.

The chart looks odd .. they won’t do the same thing as past few years. They are changing the course by picking now, not Feb or March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:21:09 </td>
   <td style="text-align:left;"> $AAPL so will this be red for 10 days straight now. Wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-07 04:20:35 </td>
   <td style="text-align:left;"> $BHG $FCEL About to launch 🚀 get out of $AAPL $NVAX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:57:38 </td>
   <td style="text-align:left;"> $TSLA over $1100 easy tomorrow if we get good 8:30am unemployment and nonfarm payroll numbers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:56:54 </td>
   <td style="text-align:left;"> $TSLA  all that fud and fuss and Bears got                      -1 percent  
 
Bears your working for peanuts  
broke Bears scared as shit tonight  
lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:56:52 </td>
   <td style="text-align:left;"> $TSLA Elon can’t tweet anything that’ll save this leveraged bubble. Trapped. Stay away. Simpcoiners causing contagion. Epic fail army. Shame on Elon for pumping for personal gain. ☠️
 https://www.reddit.com/r/Epic_Economics/comments/rxu2nk/simpcoiners_want_more_dollars_we_all_do_they_just/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:56:23 </td>
   <td style="text-align:left;"> latex472a333021fdd9930e7a8c31d010ef3bGM
$F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:54:57 </td>
   <td style="text-align:left;"> $TSLA Let this be legit, bulls deserve a break </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:54:48 </td>
   <td style="text-align:left;"> $TSLA 

So yes I have a big Tesla position 97% - long , 3% swing !! 

How do I manage expenses ?! my 3% is always my “go for” but most well off ppl with large funds live off margins taken on their positions - in my case 1.7% margin interest this is nothing and it’s “Tax deductible” ! 

You can literally draw money to buy rentals and depreciate the entire value without having to sell any of your long position yet generate passive income without paying taxes or at least paying very minimum  (just an example)- 

I believe government is the worst when it comes to money allocation , they don’t deserve it! 

Many tricks and tweaks I have in my toolbox  I’ll be sharing if I feel we are seriously going through rough times … 

RELAX - follow me !

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:54:44 </td>
   <td style="text-align:left;"> $TSLA last time tesla had 2 down days followed by a hammer on 3rd day in November it went up the next 2 days. I wonder if history will repeat? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:54:16 </td>
   <td style="text-align:left;"> $TSLA    Give us just a little hint Elon …. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:54:08 </td>
   <td style="text-align:left;"> $TSLA would be nice if we hit $1150 tomorrow! We shall see… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:53:43 </td>
   <td style="text-align:left;"> $TSLA retail for breakfast tomorrow lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:52:35 </td>
   <td style="text-align:left;"> $TSLA LFG FJB. START THE FOMO PUMP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:51:26 </td>
   <td style="text-align:left;"> $TSLA +10 bucks AH and above 50sma again...
Could it be, that patterns work? Probably just a coincidence.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:51:22 </td>
   <td style="text-align:left;"> $SPY $TSLA $GME $AMC Just sharing some stock porn 💋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:51:14 </td>
   <td style="text-align:left;"> $F my thesis, if $TSLA goes to $1,500, $F can easily get to $60 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:50:56 </td>
   <td style="text-align:left;"> $TSLA stagnate at least one more day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:49:40 </td>
   <td style="text-align:left;"> $TSLA  just a tweet away from another 150 point run! 
 
 
love this stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:49:15 </td>
   <td style="text-align:left;"> $TSLA Earning on Jan 26.  Expect it to amazing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:48:55 </td>
   <td style="text-align:left;"> $TSLA 1075 ah wtf is that right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:48:33 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ in nikola tesla&amp;#39;s last letter to his mom, he said &amp;quot;All these years that I had spent in the service of mankind brought me nothing but insults and humiliation&amp;quot;  
rest in peace nikola </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:47:53 </td>
   <td style="text-align:left;"> $TSLA How funny would it be if Monday repeated itself tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:47:44 </td>
   <td style="text-align:left;"> $F analysts price targets on Ford too low, trading at 1/10 of $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:47:43 </td>
   <td style="text-align:left;"> $TSLA    
A dip before record earnings is a gift from the market  
 
thank you fed  
 
now back to moooning  
 
PT Q4 $1500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:47:28 </td>
   <td style="text-align:left;"> $TSLA Still can’t understand how Tesla is red and can’t follow nasdaq into green… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:46:57 </td>
   <td style="text-align:left;"> $TSLA $1243 high on Nov 1st. Volume dropping since. Plebs chased. Back to triple digits. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:45:41 </td>
   <td style="text-align:left;"> $TSLA Algo’s playing tricks on you! Mind games baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:45:15 </td>
   <td style="text-align:left;"> $TSLA   
The  competition has been coming since        2009 lol 
PT $1500 Q4  
covers calls to the moon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:45:13 </td>
   <td style="text-align:left;"> $NIO $TSLA $QQQ Risk on, fuck it risk off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:44:48 </td>
   <td style="text-align:left;"> $TSLA Run it up. I&amp;#39;m hungry for retail fomo. 1000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:43:49 </td>
   <td style="text-align:left;"> $TSLA $GM 

FJB:- electrified America, Mary!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:43:43 </td>
   <td style="text-align:left;"> $TSLA Fck the noise, HODL! 🙌🏼 💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:42:50 </td>
   <td style="text-align:left;"> $GM $TSLA siunds about right!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:42:49 </td>
   <td style="text-align:left;"> $TSLA if tesla new batteries indeed able to get 750 miles to charge that is indeed as @BigNews said be a massive game changer. You will open up a whole new set of buyers like myself that have held back due to annoyance of too many recharges and the concept of battery decay over time is resolved when start at 750 than 300. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:41:04 </td>
   <td style="text-align:left;"> $TSLA is expected to show a strong growth in EPS. In the coming 5 years, the EPS will grow by 52.30% yearly. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:40:40 </td>
   <td style="text-align:left;"> $TSLA Elon is still holding BTC on Tesla’s books? Going to crash with it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:39:34 </td>
   <td style="text-align:left;"> $GME =====&amp;gt; MY FELLOW APES... I&amp;#39;M BACK WITH MY BABY RIGHT HERE.... BACK TO  $400s  WE GO ... ALL THE WAY IN!!! 😳🤑😎🔥💥🚀🚀 
. 
$SPY  $AMC  $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:38:28 </td>
   <td style="text-align:left;"> $TSLA  believe it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:38:16 </td>
   <td style="text-align:left;"> $TSLA tomorrow is 79th anniversary of Nikola Tesla death </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:38:08 </td>
   <td style="text-align:left;"> $TSLA this will be $1,120 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:37:55 </td>
   <td style="text-align:left;"> $TSLA $QQQ 1.3% Nasdaq day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:37:50 </td>
   <td style="text-align:left;"> $TSLA 😇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:36:56 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:36:26 </td>
   <td style="text-align:left;"> $TSLA lotta AH movement right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:35:21 </td>
   <td style="text-align:left;"> So the numbers are out and $F sold 508,000 vehicles last quarter. Yep, that’s right, that’s more than 200,000 better than wannabe loser $TSLA. And whatever argument you are going to bring about margins or blah blah blah, I have two words: PRICE ACTION. Wall St. Knows better than you how to judge which metrics matter. That is why $F is powering higher and $TSLA, is well, being $TSLA. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:33:32 </td>
   <td style="text-align:left;"> $LCID unlike $TSLA the CEO of $LCID is actually an Engineer who understands the car he sells in its entirety. Not that Elon isn’t brilliant, he is but having the ceo of a tech company who actually is an engineer is pretty rare for the major tech companies out there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:32:34 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-06 Technical Analysis Video: 
https://www.youtube.com/watch?v=ti3BsrUax68 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:32:18 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:31:53 </td>
   <td style="text-align:left;"> $F deserves $TSLA like multiple, Ford real EPS + paying out a dividend, perhaps we&amp;#39;ll see even higher dividend payouts, will imho be the largest EV manufacturer in the world </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:31:39 </td>
   <td style="text-align:left;"> $AMD $AAPL $TSLA what would you do? https://reddit.com/r/hmm/comments/rxkbeo/hmmm/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:30:34 </td>
   <td style="text-align:left;"> $AMC $GME  $TSLA  $DWAC  
 
Damn son. 
 
https://www.interactivebrokers.com/mkt/?src=xiaowangY1&amp;amp;url=%2Fcn%2Findex.php%3Ff%3D2359 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:29:55 </td>
   <td style="text-align:left;"> $TSLA unlimited demand. Tesla threatening to cancel orders if they don&amp;#39;t take delivery. These people are waiting for BBB EV credits. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:29:51 </td>
   <td style="text-align:left;"> $TSLA bears are ballsy… historically speaking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:29:03 </td>
   <td style="text-align:left;"> $TSLA 50.00+ up day tomorrow for sure. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:27:56 </td>
   <td style="text-align:left;"> $TSLA Cut a loss here after entering on Monday. Back on watch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:27:22 </td>
   <td style="text-align:left;"> $TSLA I won’t be surprised if this gets to $900 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:25:19 </td>
   <td style="text-align:left;"> $TSLA “I know it hurts sometimes but you&amp;#39;ll get over it
You&amp;#39;ll find another life to live” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:24:09 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:18:37 </td>
   <td style="text-align:left;"> $TSLA I did some comparison shopping in After Hours action.  I compared this to FB.  What did I find?  Not one green After Hours fill for Tesla.  Every fill was coming up shorted down to $1045.  In comparison, every fill on FB was green up and down the board </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:18:14 </td>
   <td style="text-align:left;"> $TSLA This idiot is done but barely able to stop liquidation of her fund and needs to sell Tesla stock.  Sell-off in Cathie Wood&amp;#39;s ARK Innovation fund reached 48% at low point Thursday

https://www.cnbc.com/2022/01/06/sell-off-in-cathie-woods-ark-innovation-fund-reached-48percent-at-low-point-thursday.html?__source=androidappshare </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:18:10 </td>
   <td style="text-align:left;"> $TSLA pretty big OI at $1100 . No way MMs let us get there tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:16:43 </td>
   <td style="text-align:left;"> $TSLA https://twitter.com/divestech/status/1479170138909954055?s=21 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:15:52 </td>
   <td style="text-align:left;"> $TSLA pedo guys shorting this? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:14:31 </td>
   <td style="text-align:left;"> $TSLA $VOO $BTC.X $ETH.X $META 

https://youtu.be/H9lkwE7wDpw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:14:16 </td>
   <td style="text-align:left;"> $SPY $TSLA everybody wants the market to just fly like a rocket ship. But in reality its less rocket and more like a surfer. Just ride the waves </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:13:27 </td>
   <td style="text-align:left;"> $TSLA was short since two weeks ago. Glad I doubled down at the gap up. Balls of steel </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:13:15 </td>
   <td style="text-align:left;"> $TSLA the crappy thing about this stock is that it would have already dropped to the $800s had not Musk lied about selling enough of his shares to meet his 10% goal on December 21st. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:12:55 </td>
   <td style="text-align:left;"> $TSLA today bought 2024 call and 2/18/2022 $1200 calls 🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:12:49 </td>
   <td style="text-align:left;"> $F $TSLA $LCID Why is Ford going to keep going up? The industry had prayed so long for a legacy automobile to switch to electric! Ford’s move is a miracle, going from stubborn to innovative. If this is not an inflection point worthy of attention and excitement, tell me about another monolithic company turning fast and nimble? Not in recent history on such a scale </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:12:09 </td>
   <td style="text-align:left;"> $TSLA back to 1200 tomorrow- full circle back to Monday! Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:11:14 </td>
   <td style="text-align:left;"> $TSLA Bulls promised me an opportunity to short from 1500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:10:59 </td>
   <td style="text-align:left;"> $F at 250$ same marketcap like $TSLA big upside </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:10:16 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $MSFT $TSLA 

If hedged funds and CEO&amp;#39;S are selling..

 fck this 💩

I&amp;#39;m loading PUTS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:09:49 </td>
   <td style="text-align:left;"> $TSLA 1150 let’s go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:06:52 </td>
   <td style="text-align:left;"> $TSLA being sued by $NKLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:06:44 </td>
   <td style="text-align:left;"> $tsla $chwy @SAL61  Here&amp;#39;s one i like to short periodically </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:05:51 </td>
   <td style="text-align:left;"> $TSLA Tesla leads 10 most-traded retail stocks on the Nasdaq in 2021 | Markets Insider https://markets.businessinsider.com/news/stocks/tesla-stock-leads-10-most-traded-retail-stocks-2021-nasdaq-2022-1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:03:00 </td>
   <td style="text-align:left;"> $TSLA I see the entire market is showing green after hours. Nasdaq may soar tomorrow and taking everything to the Moon and beyond! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:02:14 </td>
   <td style="text-align:left;"> SweepCast alerted: $TSLA with Unusual Options Activity Alerted on $1050 CALL Expiring: 01-21-2022 worth 4366K🐂 |🥇  Highly Aggressive Buyers Above Asking Price | SweepCast.com or Premium Room ➡️  #stockstowatch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:01:53 </td>
   <td style="text-align:left;"> $BKKT gonna be releasing $GME new nft??? Looks like gonna skyrocket $AMC $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:00:38 </td>
   <td style="text-align:left;"> $MULN https://finance.yahoo.com/news/mullen-automotive-named-top-ev-133000686.html
Love electric vehicles and this is a new article.  
$wkhs $ride $tsla $nio </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:00:33 </td>
   <td style="text-align:left;"> $TSLA ark selling Tesla and buying hood
😂😂😂 ARK hit 52 week lowest! People like bitch where is my money lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:00:24 </td>
   <td style="text-align:left;"> $TSLA Huge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 08:00:17 </td>
   <td style="text-align:left;"> $TSLA bvps -47% debt = $15 sp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:58:19 </td>
   <td style="text-align:left;"> $TSLA don&amp;#39;t gamble, don&amp;#39;t try to time it. Just hodl ladies and gentlemen. Your future self will thank the current you! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:58:17 </td>
   <td style="text-align:left;"> $RIDE Still holding this one ..I love this truck and I believe this company will eventually take off .. screw rivian  China human rights violators ..&amp;amp; Elon $TSLA  Musk should forget his weird looking truck and get together with Lordstown they have the plants to build let&amp;#39;s go love it 😃👍🇺🇸❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:57:51 </td>
   <td style="text-align:left;"> $TSLA Green after hours and red in the morning! Wash and repeat bitches </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:57:14 </td>
   <td style="text-align:left;"> $TSLA $1000 retest coming soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:56:07 </td>
   <td style="text-align:left;"> $TSLA shorting this to 600 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:55:46 </td>
   <td style="text-align:left;"> $TSLA What did I miss? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:55:41 </td>
   <td style="text-align:left;"> $TSLA Not everyone is brainwashed…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:55:24 </td>
   <td style="text-align:left;"> $TSLA So we get corn holed by GME &amp;amp; Meme stocks tomorrow right? Kills the whole market when that shit happens look at Gme ah FUCK ME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:54:57 </td>
   <td style="text-align:left;"> $TSLA all he does is Twitter pump. Like donnie used to. ☠️
 https://www.tradingview.com/chart/NAS100/p0QW0Xkm-NAS100-Fallout-Buyer-BEWARE-Growth-at-all-Costs-is-No-More/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:54:37 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #2 ticker with sweep activity where institutions are trading options urgently with 72.6K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:52:16 </td>
   <td style="text-align:left;"> $TSLA  If TSLA does not close the week above $1200, I will stop having sex. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:51:22 </td>
   <td style="text-align:left;"> $TSLA 2000$ EOY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:50:40 </td>
   <td style="text-align:left;"> $TSLA 📈📈📈📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:49:54 </td>
   <td style="text-align:left;"> $TSLA remember what’s being made on the daily… inverted head n shoulders. Very bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:47:53 </td>
   <td style="text-align:left;"> $F $GM  $TSLA  Cybertruck will never see the light of day.  The body is so stiff it will kill or seriously injure occupants due to lack of crumple zones, and present an unacceptable hazard to other road users due to sharp edges and excessive rigidity.  Therefore it&amp;#39;s uninsurable.  This is why Tesla started an insurance company several months after the Cybertruck debut - because underwriters looked into it and said &amp;quot;no fucking way are we insuring that.&amp;quot;  And I suspect the reason there&amp;#39;s still no date on cybertruck is because in order to become legal and insurable, nearly everything about the design would have to change.  This isn&amp;#39;t even getting into the other design failures.  The game still belongs to the companies that know trucks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:47:29 </td>
   <td style="text-align:left;"> $TSLA made it on to the Best Stocks short list with an Earning Momentum of 22 and a perfect timing. https://epsmomentum.com/boxes/list2?ticker=TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:45:18 </td>
   <td style="text-align:left;"> $TSLA absolutely zero support PT $0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:44:32 </td>
   <td style="text-align:left;"> $TSLA NEWS - TSLA Beats Delivery Numbers: 
https://www.youtube.com/watch?v=5Cg5QiZoWHY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:44:12 </td>
   <td style="text-align:left;"> $TSLA when is the announcement by Elon? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:43:43 </td>
   <td style="text-align:left;"> $AAPL $AMZN $TSLA Todays OP Highlights

Ready for tomorrow’s plays?

https://www.instagram.com/reel/CYaEjSILuiB/?utm_medium=copy_link </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:43:37 </td>
   <td style="text-align:left;"> $TSLA I think a key I’m finding is to some days just not fuckin trade lol I’m so happy I made 3200 back today after losing 4K yesterday but WOW I’m just not going to rush in to SHIT anymore </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:42:39 </td>
   <td style="text-align:left;"> $TSLA  Keep climbing someday I can stop working like a dog! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:42:33 </td>
   <td style="text-align:left;"> $TSLA https://www.almanacnews.com/news/2022/01/05/structure-fire-related-to-tesla-charger-displaces-menlo-park-family </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:41:26 </td>
   <td style="text-align:left;"> $TSLA hmmm maybe I should of picked up some 1100 weekly lottos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:39:47 </td>
   <td style="text-align:left;"> $TSLA i’ll be playing meme stocks tomorrow, tesla i’ll see you next week pls stay volatile 🙏🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:39:31 </td>
   <td style="text-align:left;"> $TSLA 1200 anytime next week and I’ll make everything I lost back 💀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:37:25 </td>
   <td style="text-align:left;"> $TSLA tomorrow about to be a rip show buy Jan 7 $1120 calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:36:39 </td>
   <td style="text-align:left;"> $TSLA 

Can we get 3 green consecutive green candles  starting tomorrow?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:35:28 </td>
   <td style="text-align:left;"> $TSLA over 1088 can see 1119. Will depend on $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:34:20 </td>
   <td style="text-align:left;"> $TSLA Remember yesterday when the price was 1088 yeah penny stock Castor held 3X better than this scam today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:32:20 </td>
   <td style="text-align:left;"> $TSLA 1160 close tmrw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:31:38 </td>
   <td style="text-align:left;"> $TSLA save me from my stupidity and be over $1100 tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:31:22 </td>
   <td style="text-align:left;"> $GME good luck guys, I&amp;#39;m all in $TSLA 

done with meme stocks and going with the biggest company that the world has ever seen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:31:06 </td>
   <td style="text-align:left;"> $TSLA hey $1,071 after hours not bad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:30:17 </td>
   <td style="text-align:left;"> $TSLA 3 red days and held the key $1025-$1030 and pushed up nicely into end of day. Strong $200+ pullback here... https://share.trendspider.com/chart/TSLA/81303lq0h8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:29:26 </td>
   <td style="text-align:left;"> $TSLA I’m in this turd meanwhile meme $GME flying AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:29:19 </td>
   <td style="text-align:left;"> $TSLA open 1100 hundo or more tomorrow Would b bitchen azz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:29:09 </td>
   <td style="text-align:left;"> $TSLA this is one of the last hold outs of the pandemic bubble. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:28:14 </td>
   <td style="text-align:left;"> $TSLA $1,069.69 Nice 😩😩😩😩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:28:10 </td>
   <td style="text-align:left;"> $TSLA Open $1110 tomorrow.. 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:27:51 </td>
   <td style="text-align:left;"> $TSLA nice moves! the whales made bets earlier for some good reasons, I guess 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:27:15 </td>
   <td style="text-align:left;"> $TSLA looks like a bearflag on the 2 and 4 hr timeframe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:26:58 </td>
   <td style="text-align:left;"> $F 30-40$ this year is the realistic target. Ford is becoming a big EV/tech company. This could easily go parabolic. I’m not saying we are going to do what $TSLA did, but we could be on par to do something similar. So many catalysts, so many evs being produced and sold already, so many big partnerships. Farley is doing everything right. 100$ + target long term. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:26:54 </td>
   <td style="text-align:left;"> $TSLA 1070 ah lets go Elon /Brandon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:26:14 </td>
   <td style="text-align:left;"> $TSLA did I miss something why is it up? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:25:56 </td>
   <td style="text-align:left;"> $TSLA  1200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:25:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL

Tomorrow could decide a lot for which way the market moves in 2022 in my opinion. Question is does the market move up or descend down...😈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:24:03 </td>
   <td style="text-align:left;"> $TSLA 18% up day tomorrow new ath </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:22:12 </td>
   <td style="text-align:left;"> $TSLA Just </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:21:59 </td>
   <td style="text-align:left;"> $TSLA $420 soon….. waiting since 4/2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:21:19 </td>
   <td style="text-align:left;"> $ARVL I wouldn’t be surprised, if Amazon order vans from Arrival. They aren’t limited to Rivian so they will be needed many vans for delivery. 

$RIVN $LCID $TSLA $F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:20:47 </td>
   <td style="text-align:left;"> $TSLA WTFH?!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:19:58 </td>
   <td style="text-align:left;"> $TSLA 70% year incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:19:08 </td>
   <td style="text-align:left;"> Tesla Inc ( $TSLA ) current probability of bankruptcy is under… https://www.macroaxis.com/stock/TSLA/Tesla-Inc #stocks #news #wallstreet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:17:54 </td>
   <td style="text-align:left;"> $TSLA made in China Stonk. Elon pumps for personal gain. Shame. 
 https://www.reddit.com/r/Epic_Economics/comments/rxrwvv/defaulting_on_debt_market_contagion/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:17:34 </td>
   <td style="text-align:left;"> $TSLA “So far, the Brandenburg agencies have not released details on how long it may take to evaluate objections raised by local residents and issue final approval (or rejection, which is largely considered to be highly unlikely). Experts believe, however, that the plant could start operating as soon as December, or early January at the latest.”
Article back in Late November 

https://amp.dw.com/en/teslas-german-gigafactory-on-track-for-december-opening/a-59899402 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:17:34 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $TSLA 

Futures update for the shorts 

👇👇👇👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:17:33 </td>
   <td style="text-align:left;"> $LAC ceo was on CNBC and mentioned ongoing talks with $TSLA and other EV  producers. Lithium production will be late this year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:17:14 </td>
   <td style="text-align:left;"> $TSLA discount season is over folks Q4 deliveries completely ignored in share price. When earnings are announced we move up to $1300 before cruising to higher ATHs further down the year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:16:59 </td>
   <td style="text-align:left;"> $TSLA tesla likes to get it on after dark. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:16:04 </td>
   <td style="text-align:left;"> $TSLA ok hope I get a 4x out of this tomorrow today I got rekted by my own stupidity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:14:52 </td>
   <td style="text-align:left;"> $PL Steve Jurvetson bought a ton of $PL shares today. $TSLA https://www.forbes.com/profile/stephen-jurvetson/?sh=7879d6e74fe3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:14:35 </td>
   <td style="text-align:left;"> $TSLA I get allot of questions about why 8 rate hikes (2022,2023, 2024)? FOMC is serious about trying to cap inflation (6-9% per annum)

Fed is Main Street,not a WallStreet Insitution,so Fed will now focus on &amp;quot;C&amp;quot; &amp;amp; &amp;quot;Xn&amp;quot; GDP variables,rather than &amp;quot;I&amp;quot; (Wall Street) variable(Ref C+I+G+Xn) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:14:21 </td>
   <td style="text-align:left;"> $TSLA German factory news? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:12:40 </td>
   <td style="text-align:left;"> $NIO $TSLA $XPEV $NAKD $DOGE.X 

I&amp;#39;m all in when somebody does meta EVs that roll on crypto coins :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:12:33 </td>
   <td style="text-align:left;"> $TSLA In an ordinary week I’d call sideways action to end the week, but this hasn’t been an ordinary week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:12:26 </td>
   <td style="text-align:left;"> $TSLA 

Deployment of 49 Starlink satellites confirmed-

@elonmusk 

🙏🏻🐉🦅👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:10:37 </td>
   <td style="text-align:left;"> $TSLA $2.50 up!!! I’M RICH!!!! 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:09:37 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-06 Daily Forecast Video: 
https://www.youtube.com/watch?v=qdH-W4wnxpU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:08:45 </td>
   <td style="text-align:left;"> $F $AMC $GME 
Lets moon $F to $TSLA levels </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:08:41 </td>
   <td style="text-align:left;"> $TSLA The foreign bulls will take this to 1120 by 4am EST. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:08:33 </td>
   <td style="text-align:left;"> $TSLA can it go back 1180 by Jan 14? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:07:54 </td>
   <td style="text-align:left;"> $TSLA artificial pop to start the week, soon the pain continues. Time to get smart. We had the yin. Here comes the yang. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:07:30 </td>
   <td style="text-align:left;"> $TSLA the drop will be epic. Loading the boat in 200 points </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:07:28 </td>
   <td style="text-align:left;"> $TSLA recovering AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:06:56 </td>
   <td style="text-align:left;"> $TSLA what number is tesla in the top 10. https://youtu.be/nbtyZxVZpkE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:06:33 </td>
   <td style="text-align:left;"> $TSLA is it okay for me to denounce the January 6 insurrection and equate it to the Beer Hall Putsch, but also call the current admin a group on phony, corrupt politicians? Some right wingers on here somehow think I support Antifa because I don’t believe our elections are rigged. What’s it got to do with Tesla? Our current admin is denying reality by saying GM is leasing the EV revolution. Both Trump and Biden have at least one thing in common (as well as the whacko right wingers on here) and that is an allergy to truth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:06:10 </td>
   <td style="text-align:left;"> Unusual Options Activity: $TSLA is the #18 ticker with unusual activity from institutional traders with an average of 17% out of the money, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:05:44 </td>
   <td style="text-align:left;"> $TSLA Starlink is the best! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:03:49 </td>
   <td style="text-align:left;"> $TSLA https://www.autospies.com/news/index.aspx?submissionid=108141 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:03:39 </td>
   <td style="text-align:left;"> $QQQ $AAPL $TSLA $MSFT $GOOGL 

BUT BUT BUT THE FED 😆

PRICED IN. 

Shorts are about to get taken to the woodshed!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:02:48 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA 

Hard to sustain a FED-sponsored bull market without the FED! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:02:05 </td>
   <td style="text-align:left;"> $tsla Excellent, welcome to crash Friday https://www.investing.com/indices/indices-futures 🐻☠😈💀❤  ... indices-futures are selling off their fake highs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:01:18 </td>
   <td style="text-align:left;"> $TSLA spike incoming ⚡️🧨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:01:09 </td>
   <td style="text-align:left;"> $TSLA https://www.autoevolution.com/news/angleton-gets-tesla-megapack-installation-has-200-mwh-of-energy-on-tap-178518.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 07:00:58 </td>
   <td style="text-align:left;"> $F $TSLA $LCID $NIO I called it last month. $50-$60 by EOY. Ford is still in what Michael Burry would call “ick” territory. I always like to get in early, just as NIO was in “ick” territory in early 2020, at $6/share. Doug Fielf is transforming Ford, thanks to his experience in Tesla and Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:59:53 </td>
   <td style="text-align:left;"> $TSLA when will Tesla be transparent as to which vehicles are included in their so-called qtrly deliveries? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:59:47 </td>
   <td style="text-align:left;"> $TSLA Hey Elan, do a 1000:1 stock split and the retail bozos will buy this back up to $1000 soon!!  TSLA will be the Gazillion dollar market cap!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:58:20 </td>
   <td style="text-align:left;"> $TSLA when will the Tesla roadster be fitted with rockets? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:57:43 </td>
   <td style="text-align:left;"> $SPY BREAKING NEWS: No more pole dancing first ladies who hate America and cannot speak English. $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:57:20 </td>
   <td style="text-align:left;"> $TSLA BTFD time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:56:59 </td>
   <td style="text-align:left;"> $TSLA when gamma squeeze?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:56:38 </td>
   <td style="text-align:left;"> $TSLA need to drive 100 miles by tomorrow before I drop off my car to get a full PPF protection for only $7k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:55:38 </td>
   <td style="text-align:left;"> $TSLA Gap up next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:55:34 </td>
   <td style="text-align:left;"> $TSLA the gap hasnt been filled ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:54:36 </td>
   <td style="text-align:left;"> $TSLA  $tsla Incoming, TESLA 900&amp;#39;s Crash Friday, let me count the ways:

1. https://www.google.com/url?sa=t&amp;amp;rct=j&amp;amp;q=&amp;amp;esrc=s&amp;amp;source=newssearch&amp;amp;cd=&amp;amp;ved=2ahUKEwjRpM_TmZ71AhVBjYkEHcZdDHUQxfQBKAB6BAgDEAI&amp;amp;url=https%3A%2F%2Fwww.barrons.com%2Farticles%2Ftesla-stock-price-beta-delivery-numbers-51641473575&amp;amp;usg=AOvVaw0N0TQYgpf0oZYkQfkqHdpf

2. https://www.google.com/url?sa=t&amp;amp;rct=j&amp;amp;q=&amp;amp;esrc=s&amp;amp;source=newssearch&amp;amp;cd=&amp;amp;ved=2ahUKEwjRpM_TmZ71AhVBjYkEHcZdDHUQxfQBKAB6BAgHEAI&amp;amp;url=https%3A%2F%2Fwww.fool.com%2Finvesting%2F2022%2F01%2F06%2Fwhy-tesla-stock-just-keeps-falling%2F&amp;amp;usg=AOvVaw3ZQJi6iSAbTOcJbO9mmDUa

3. https://www.google.com/url?sa=t&amp;amp;rct=j&amp;amp;q=&amp;amp;esrc=s&amp;amp;source=newssearch&amp;amp;cd=&amp;amp;ved=2ahUKEwjRpM_TmZ71AhVBjYkEHcZdDHUQxfQBKAB6BAgFEAI&amp;amp;url=https%3A%2F%2Fwww.barrons.com%2Farticles%2Fford-tesla-stock-price-performance-51641335589&amp;amp;usg=AOvVaw2NpzvN7h8NnaDOWawuWP1H

4. https://www.google.com/url?sa=t&amp;amp;rct=j&amp;amp;q=&amp;amp;esrc=s&amp;amp;source=newssearch&amp;amp;cd=&amp;amp;ved=2ahUKEwitvOunmp71AhXSjokEHeNKD0wQxfQBKAB6BAgGEAI&amp;amp;url=https%3A%2F%2Fwww.marketwatch.com%2Fstory%2Fford-motor-co-stock-outperforms-market-on-strong-trading-day-01641505999-7ea4e43de483&amp;amp;usg=AOvVaw0rb-RCoFnhdHuhEr0b5aro

5. https://www.google.com/url?sa=t&amp;amp;rct=j&amp;amp;q=&amp;amp;esrc=s&amp;amp;source=newssearch&amp;amp;cd=&amp;amp;ved=2ahUKEwjP_52-mp71AhU9jIkEHZnSBWgQxfQBKAB6BAgFEAI&amp;amp;url=https%3A%2F%2Fwww.barrons.com%2Farticles%2Ftesla-tsla-stock-trading-51641473575&amp;amp;usg=AOvVaw0wVGHhTUxZLUXtqn2uA7ZB

6. https://www.google.com/url?sa=t&amp;amp;rct=j&amp;amp;q=&amp;amp;esrc=s&amp;amp;source=newssearch&amp;amp;cd=&amp;amp;ved=2ahUKEwjP_52-mp71AhU9jIkEHZnSBWgQxfQBKAB6BAgQEAI&amp;amp;url=https%3A%2F%2Fwww.barrons.com%2Farticles%2Ftesla-ev-cold-51641484242&amp;amp;usg=AOvVaw0raEttxfZyydUh7vt9_HSo

7. https://www.google.com/url?sa=t&amp;amp;rct=j&amp;amp;q=&amp;amp;esrc=s&amp;amp;source=newssearch&amp;amp;cd=&amp;amp;ved=2ahUKEwjP_52-mp71AhU9jIkEHZnSBWgQxfQBKAB6BAgCEAI&amp;amp;url=https%3A%2F%2Fwww.investors.com%2Fmarket-trend%2Fstock-market-today%2Fdow-jones-slips-as-yields-rise-alibaba-stock-leads-china-stocks-higher-tesla-stock-lags%2F&amp;amp;usg=AOvVaw1dHRPcK_Znh5GblYb92aqi

8. https://www.google.com/url?sa=t&amp;amp;rct=j&amp;amp;q=&amp;amp;esrc=s&amp;amp;source=newssearch&amp;amp;cd=&amp;amp;ved=2ahUKEwjyofnkmp71AhWulYkEHSAqA704ChDF9AEoAHoECAQQAg&amp;amp;url=https%3A%2F%2Fwww.investors.com%2Fmarket-trend%2Fstock-market-today%2Fdow-jones-futures-rise-after-stock-market-sell-off-tesla-tests-key-support%2F&amp;amp;usg=AOvVaw2eF_FzVGwT6puRjUy5CmyM

9. https://www.google.com/url?sa=t&amp;amp;rct=j&amp;amp;q=&amp;amp;esrc=s&amp;amp;source=newssearch&amp;amp;cd=&amp;amp;ved=2ahUKEwjyofnkmp71AhWulYkEHSAqA704ChDF9AEoAHoECAMQAg&amp;amp;url=https%3A%2F%2Fwww.nasdaq.com%2Farticles%2Fford-lightning-f-150-proves-a-huge-draw&amp;amp;usg=AOvVaw1Q4Oqj1PXCEbzFLpKN2lS2

Thank dog that I am here to help. Carry on sticking forks in TESLA for profits. Rest assured we ain&amp;#39;t seen nothing yet. @PROFIT_MAKER HTTPS://STOCKTWITS.COM/PROFIT_MAKER your 24/7 care bear specialist. Thanks bulls for lending bears you shares to short for profits at your expense 🐻❤💀☠😈😁✔ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:54:34 </td>
   <td style="text-align:left;"> $TSLA Nasdaq was up over 100 pts today for awhile , we didn’t do shit, need a better entry lower </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:54:21 </td>
   <td style="text-align:left;"> $TSLA when moon? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:51:19 </td>
   <td style="text-align:left;"> $TSLA as mentioned before nothing but pandemic luck, a short squeeze and a meme stock. Where would you guys be without the irrational investor. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:51:19 </td>
   <td style="text-align:left;"> $SPY Deadly insurrection at the U.S. Capitol a year ago is part of a broader war on democracy by Donald Trump. Trump lost the election by a mile, and now he&amp;#39;s saaad. $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:51:02 </td>
   <td style="text-align:left;"> $TSLA gapped filled wonder what other techs filled gap today. $MSFT did too. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:50:44 </td>
   <td style="text-align:left;"> $TSLA I know guys this I my third day said tmr gonna be green and good day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:50:35 </td>
   <td style="text-align:left;"> $TSLA I thought the 19k being hired was strong news but here we are flat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:47:52 </td>
   <td style="text-align:left;"> $TSLA when stock split? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:46:37 </td>
   <td style="text-align:left;"> $NIO Does anyone remember saying wish I bought $TSLA when it was $25…😥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:45:06 </td>
   <td style="text-align:left;"> $TSLA  🔥🔥🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:45:03 </td>
   <td style="text-align:left;"> $TSLA hmm ill wait till next week. Not to sure about tomorrow🧐. Looks like meme stock day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:44:56 </td>
   <td style="text-align:left;"> $TSLA I’m flat but I think serious red tomorrow 1000-1020, might come back later …. Lots of economic news at 8:30 am also, if good we could raise rates sooner and say goodbye to fed money too. + way to many calls , market will not let you have that, because it’s what they do. If we can find support around 1000-1020 I’m a player </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:44:42 </td>
   <td style="text-align:left;"> $TSLA surprise surprise another GD fucking red day and now down 13% after BEATING EXPECTATIONS BY 30 FUCKING PERCENT. Probably be under $700 after earnings on this fucking logic. Bears continue to get bailed out of their retarded as fuck and off basis short positions while bulls get fucked for investing in a company performing like never seen before and making the world a better place. Incredibly outrageous and fucked up. Sick of this fucking GD bullshit. How long will these dumbfucks make money for doing shit that should make them bankrupt. Fucking insane. Fuck everyone that’s short. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:44:09 </td>
   <td style="text-align:left;"> $TSLA this will rocket once the bottom is in place. This will rocket faster than Starlink 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:43:05 </td>
   <td style="text-align:left;"> $TSLA technical analysis for tomorrow.

https://youtu.be/hYlXY45mfJY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:42:58 </td>
   <td style="text-align:left;"> $TSLA price target increased to $1,600 by Gary Black. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:40:00 </td>
   <td style="text-align:left;"> Looking at the last year, $TSLA shows a very strong growth in Revenue. The Revenue has grown by 66.27%. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:39:13 </td>
   <td style="text-align:left;"> $TSLA https://www.etsy.com/listing/1154186083/dogecoin-vinyl-decals-clear-background?ref=shop_home_active_3&amp;amp;frs=1 ⚡🏎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:39:00 </td>
   <td style="text-align:left;"> $TSLA starting today we&amp;#39;ll see massive upgrades and recommendations in some of the severely beaten down growth stock names, then some articles about how well the better growth stocks deal with rising rates, and how it even helps some of them, then we&amp;#39;ll see growth rally in the next month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:38:57 </td>
   <td style="text-align:left;"> $QQQ wild that none of this matters when  your FAANMG group plus $TSLA holds indicies up due to an ever increasing weighting. Stock buybacks and endless amounts of cheap speculative money flowing into the liquidity leaders. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:37:22 </td>
   <td style="text-align:left;"> $TSLA Bulls post your position! Who is really bouty bouty! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:34:50 </td>
   <td style="text-align:left;"> $TSLA If Cathie is selling for profits. I&amp;#39;m definitely not getting in soon. Thank you CATHIE WOODS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:34:26 </td>
   <td style="text-align:left;"> $TSLA 18% day tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:33:40 </td>
   <td style="text-align:left;"> $NAKD  we have more chance to reach easy 💯 on short squeeze as we are under $5 and no other MEME EV except us $TSLA $NIO $F $DWAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:33:38 </td>
   <td style="text-align:left;"> $TSLA the pro is that it closed on the same downtrend-line right before the gap up Monday. All we need is a catalyst and we could potentially replicate Monday. And Ofcourse this weak ass Nasdaq needs some  milk… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:33:25 </td>
   <td style="text-align:left;"> $TSLA Can’t think of a reason not to buy more TSLA. Loaded up on $1100 strike March calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:33:21 </td>
   <td style="text-align:left;"> $QQQ $AAPL $TSLA $MSFT $GOOGL  Anyone know what a triple bottom and inverse head and shoulders equals tomorrow? 😆🚀🐂

ADD IN THE SHORT COVERING AS WELL 😱👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:33:03 </td>
   <td style="text-align:left;"> $TSLA Tesla is doing great considering everything going on so is apple and Intel </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:32:53 </td>
   <td style="text-align:left;"> $TSLA 1st part of &amp;quot;Master Plan Tre&amp;quot; has been started =Redwood(JB Straubel) supplying recycling material to panasonic GigaNevada.  2nd part = ABML(Ryan Melsert), will be extraction mining sourced lithium(and recyled black mass) to panasonic, ie... Tesla!!  Elon, JB and Ryan, Triangle forming watch this play out, will be awesome! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:32:29 </td>
   <td style="text-align:left;"> $TSLA people hate on this stock so much like if y’all haters/ bashers got into it when it was 200 or what ever y’all wouldn’t be so bitter towards it. Its funny how much success Tesla has had and has proven to grow but yet y’all still bashing it. Either way y’all bears can beat it ✌🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:31:48 </td>
   <td style="text-align:left;"> $TSLA turns out if I had listened to the vomit I was spewing from my ass, I would have actually made a shit ton of fucking money shorting. What the fuck. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:31:45 </td>
   <td style="text-align:left;"> $TSLA up 200 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:31:09 </td>
   <td style="text-align:left;"> $TSLA Is this about the FOMC or Elon is still selling his damn shares? 😂😂 Pheww </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:30:43 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-06 Largest Trades Data: 
https://www.youtube.com/watch?v=za4u4dNdX4Y </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:29:35 </td>
   <td style="text-align:left;"> $TSLA Why the fuck nobody else takes drone shots of $F $GM or $TM parking lots. I see drone shots of Tesla parking lot..
SEMI IS COMINH
CYBER TRUCK KA COMING
DRRR Model 25K coming.. It will eventually but wtf… 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:28:54 </td>
   <td style="text-align:left;"> $TSLA the $25,000 car Elon will announce at earnings plus the stock split. Will send this soaring </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:28:53 </td>
   <td style="text-align:left;"> $TSLA 

BREAKING!

Audi 🇺🇸 USA sales in Q4 -47% ⬇️

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:28:47 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:27:56 </td>
   <td style="text-align:left;"> $TSLA https://apple.news/ACkZZ6XSvTteqvy2xKifJVA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:27:33 </td>
   <td style="text-align:left;"> $TSLA WHAT OUR PT FOR NEW ATH TOMORROW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:27:01 </td>
   <td style="text-align:left;"> $TSLA First they came for Cathie. Now they will come for Elon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:24:05 </td>
   <td style="text-align:left;"> $CLOV Big day tomorrow for all memes $GME $AMC $DWAC $TSLA LFG $CLOV Clover Health on the move!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:24:00 </td>
   <td style="text-align:left;"> $TSLA https://www.benzinga.com/news/22/01/24937051/tesla-to-increase-workforce-to-19-000-in-china-for-new-model-line </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:23:48 </td>
   <td style="text-align:left;"> $TSLA has officially given up ALL of the gains after the blowout delivery announcement.  Wow, that 10-year sure is damaging </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:23:48 </td>
   <td style="text-align:left;"> $TSLA I am seeing RED tomorrow, to many bad news.  Hope I am wrong. GL to all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:23:14 </td>
   <td style="text-align:left;"> $TSLA Jesus so they’re just gonna let us buy 1200cs for earnings at this price eh? Okay 🤌🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:22:30 </td>
   <td style="text-align:left;"> $TSLA https://www.etsy.com/listing/1138257430/doge-crypto-t-shirt?ref=shop_home_feat_3&amp;amp;frs=1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:22:24 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/BORPr2JvKf8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:22:14 </td>
   <td style="text-align:left;"> $GME $AMC dont miss out buy low sell high $AAPL $TSLA gla. 💵💵💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:21:53 </td>
   <td style="text-align:left;"> $TSLA https://apple.news/AeZsq44UWQ5a1MWK9ae_8NQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:21:09 </td>
   <td style="text-align:left;"> $TSLA looks like everything getting pumped to new ath tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:20:47 </td>
   <td style="text-align:left;"> $TSLA 1100+ 💸BULLISH BALL FORMING 10MIN CHART 💂🏿‍♂️💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:20:03 </td>
   <td style="text-align:left;"> $TSLA $1400 easily after ER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:19:30 </td>
   <td style="text-align:left;"> $1 Trillion Wipeout On Nasdaq Begins To Moderate - TheStreet $QQQ $QQQJ $TQQQ $TSLA $AAPL  https://apple.news/AoAVa0lEKS5uXRJwzjNb6fA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:18:59 </td>
   <td style="text-align:left;"> $CLOV Taking market share from the big players...Were going to $100. $GME $AMC $DWAC $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:17:23 </td>
   <td style="text-align:left;"> $TSLA Why hold $TSLA when you can gain more with $AMC MOASS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:17:09 </td>
   <td style="text-align:left;"> $TSLA Some people on here trying to blame this on the NASDAQ today.  If TSLA was truly following the NASDAQ it would of been down only $2 or $3 Dollars.  Not $23.  Plain and simple, Major Money knows the Fed is going to raise the interest rate.  This isn&amp;#39;t only relegated to Tesla but market wide.  Some stocks are going to be hit worse than others and Tesla is one of them though. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:16:51 </td>
   <td style="text-align:left;"> $TSLA cooling off.   Adding $POWW and $FLXS for a nice pop soon.  $JOBY might need to wait a bit until a nice run </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:14:50 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:14:22 </td>
   <td style="text-align:left;"> $QQQ $AAPL $TSLA $MSFT $GOOGL  the QQQ opens above this, everything is going to TAKE OFF LIKE A ROCKET 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:13:49 </td>
   <td style="text-align:left;"> $ATOM ATOMERA.  Rumors connect it to $TSLA, $AAPL, and now US Air Force and by extension the US DoD.   Waiting patiently and adding at these pps. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:13:05 </td>
   <td style="text-align:left;"> $TSLA awww poor Cathie </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:13:00 </td>
   <td style="text-align:left;"> A Couple Of Risk-Off Days Do Not Make A Crisis - Yet $TSLA $NDX $SPX $VXN https://talkmarkets.com/content/etfs/a-couple-of-risk-off-days-do-not-make-a-crisis--yet?post=340374 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:10:30 </td>
   <td style="text-align:left;"> $TSLA when-if we market crashes... everyone will rush to put $ in a business with great margins, growth, profits and demand...

Tick tock tesla millionaires...

Hold pay your home off, hold buy your car cash, hold be rich </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:09:52 </td>
   <td style="text-align:left;"> $TSLA what a horrendous three days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:09:43 </td>
   <td style="text-align:left;"> $TSLA I’m ok with everything happening at this moment 🥲🥲🥲🥲🙏🏻🙏🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:09:28 </td>
   <td style="text-align:left;"> $DWAC $AAPL $MSFT $TSLA  Money news for all investors https://seekingalpha.com/news/3785983-trump-spac-digital-world-acquisition-jumps-on-plans-to-start-truth-social-feb-21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:08:33 </td>
   <td style="text-align:left;"> $AEHR lol all the current &amp;quot;hot&amp;quot; going vehicles from $TSLA and $F will indirectly benefit $AEHR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:06:19 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Tesla leads 10 most-traded retail stocks on the Nasdaq in 2021 https://www.stck.pro/news/TSLA/20997096 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:05:50 </td>
   <td style="text-align:left;"> Tesla&amp;#39;s record sales in UK help reach new electric market share milestone - Electrek $TSLA https://apple.news/ABc91BUzRTrCwuKpPxsJdRg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:05:46 </td>
   <td style="text-align:left;"> $TSLA  Tesla&amp;#39;s mission is to accelerate the world&amp;#39;s transition to sustainable energy 
 
How much does a 25k Tesla hatchback fit their mission ? 
like a glove 
 
 
PT $1500 Q4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:05:01 </td>
   <td style="text-align:left;"> $TSLA  https://twitter.com/alphatrades7/status/1479212141945274374?s=20 #tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:04:24 </td>
   <td style="text-align:left;"> $TSLA Does anyone know any of the market markers&amp;#39;s Facebook page so I can ask them if they&amp;#39;re done processing the dumped shares yet? It seems like they are using the same playbook. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:02:32 </td>
   <td style="text-align:left;"> $TSLA 700P Exp:15-Jul-22 --  🔥 Total(Day): $34,555 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:02:04 </td>
   <td style="text-align:left;"> $TSLA why can’t this stock move like that rocket did </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:01:09 </td>
   <td style="text-align:left;"> $TSLA Support is currently at $954.  Look what happens when that breaks and the drop down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 06:00:41 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-06 Options Analysis Video: 
https://www.youtube.com/watch?v=M6467g5Fae0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:59:35 </td>
   <td style="text-align:left;"> $TSLA its meme day again tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:59:10 </td>
   <td style="text-align:left;"> $TSLA can we do $GME tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:59:07 </td>
   <td style="text-align:left;"> $TSLA W Land </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:59:00 </td>
   <td style="text-align:left;"> $TSLA  how much will this blow up if it’s Elons announcement  about a production line change  is the infamous 25k Tesla Hatch back being announced at Q4 ? 
 
https://www.torquenews.com/13417/tesla-s-planned-25k-car-could-end-being-half-price-when-incentives-kick/amp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:56:16 </td>
   <td style="text-align:left;"> $TSLA China with $BIDU and $BABA kept this train running today.  Tesla to 700 fanbois </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:56:02 </td>
   <td style="text-align:left;"> $TSLA - Earnings call in two weeks. Technical Analysis Alert: Tesla Relative Strength Index… https://www.macroaxis.com/stocks/Momentum-Indicators/Relative-Strength-Index/TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:55:27 </td>
   <td style="text-align:left;"> $TSLA looking to buy that 1120 area in the morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:55:15 </td>
   <td style="text-align:left;"> $SPY JANUARY 6 - Never again will we allow traitors and criminals try to take down the United States of America.  NEXT TIME, SHOOT ON SIGHT. $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:54:26 </td>
   <td style="text-align:left;"> $AMC is  going to moon!!!!! Look at amc! After hour it’s  flying $BTC.X  $TSLA $ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:54:10 </td>
   <td style="text-align:left;"> $TSLA Imagine Elon announced a stock split all of a sudden. 🤭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:53:06 </td>
   <td style="text-align:left;"> Wouldn&amp;#39;t it be a dream if this  $TSLA tweet had something to do with $AEI? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:53:00 </td>
   <td style="text-align:left;"> $TSLA fill to 1150 tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:52:02 </td>
   <td style="text-align:left;"> $TSLA who watching this rocket right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:51:53 </td>
   <td style="text-align:left;"> $TSLA many stock holders today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:51:51 </td>
   <td style="text-align:left;"> $TSLA oooo $2 up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:51:39 </td>
   <td style="text-align:left;"> $TSLA anyone watching space x </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:51:31 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/2NMJAkM1YlU Go! $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:51:20 </td>
   <td style="text-align:left;"> $F $TSLA $DWAC $AMC Bought high and will hold for higher. Keeping my golden shares of Ford for the entirety of 2022. Best hedge against risks in a volatile market according to my algorithm and the fundamentals </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:48:40 </td>
   <td style="text-align:left;"> $TSLA 🚀🚀🚀  $DWAC exploding... 
https://www.reuters.com/world/us/trump-launch-his-social-media-app-february-listing-shows-2022-01-06/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:48:13 </td>
   <td style="text-align:left;"> $TSLA I’ve been here long enough to know they will *not* let tomorrow do anything but chop… not hitting 1200 in my opinion </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:48:05 </td>
   <td style="text-align:left;"> $TSLA all 22 ev companies against tesla have had less then $30k range this year 2022 in USA ev race as well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:47:57 </td>
   <td style="text-align:left;"> $TSLA 

There’s massive conspiracy to save $F $GM from going under — you can run but you can’t hide !! 

You the retail investors when truth reveals some serious facts about battery issues , gross margin and losses just be prepared to lose all your investments in these lousy 
 Dead horses 🐎!!  

YOU’RE BEING MISLED!! 

🙏🏻🐉🦅IMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:47:56 </td>
   <td style="text-align:left;"> $AMZN caught this beautiful selloff today with +130% profit, and some $SPY 10-15% in and out scalping, been busy working on discord I’ll give u guys an update when it’s ready, first 100 people that joins will get an free access for the whole year of 2022! Hope everyone doing well, stay tuned! $TSLA $GME $BABA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:47:54 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:47:13 </td>
   <td style="text-align:left;"> $TSLA could we get 16% up pre market u never know unless u do </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:46:56 </td>
   <td style="text-align:left;"> $TSLA  you think we open green tomorrow ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:46:54 </td>
   <td style="text-align:left;"> $TSLA How many of you saw the AH mega print of over 331k shares bought at $1067.70?  Last time I saw this a few days ago, the gap up next morning was big. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:46:50 </td>
   <td style="text-align:left;"> $TSLA down to 700 in less than 3 months.  It’s cool there’s property next to snoop dog for sale.  So don’t get worried. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:46:14 </td>
   <td style="text-align:left;"> $TSLA   we have ignition </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:45:56 </td>
   <td style="text-align:left;"> $TSLA 

$25k car should be starting production in 2023 if 4680 production will ramp up this year.

Source: Elon Musk on Battery Day 2020 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:45:46 </td>
   <td style="text-align:left;"> $TSLA has WS forgot about the deliveries already with earnings around the corner ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:45:28 </td>
   <td style="text-align:left;"> $PLTR $AAPL $TSLA $TQQQ  Look I’ll say it louder. BUY SHARES LIKE A MAN AND YOU DONT HAVE TO WORRY ABOUT ALL THIS TALK OF CRASHING AND CORRECTION. Bought shares years ago and just sit back with a stop loss. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:45:24 </td>
   <td style="text-align:left;"> $TSLA dip to 1020 then rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:44:58 </td>
   <td style="text-align:left;"> $TSLA I need quick money. My car need a transmission. What should I do </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:44:46 </td>
   <td style="text-align:left;"> $TSLA I would just like $1125 for tmrw, $1200 by Tuesday next week please </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:44:36 </td>
   <td style="text-align:left;"> $TSLA https://electrek.co/2022/01/06/tesla-unveils-giant-megapack-battery-project-texas/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:43:39 </td>
   <td style="text-align:left;"> $TSLA  
The Rise of Tesla Year 2020: Documentary Series (Part 2 of 3) 
https://www.youtube.com/watch?v=-Lt6SdtXJ5c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:42:20 </td>
   <td style="text-align:left;"> $TSLA  Hope your  not holding outs over night  …. News is starting to leak  
 
&amp;quot;As for now, this is assumed to be the Model Y, because it is the newest vehicle at the plant. But, it could also be hinting at Tesla&amp;#39;s upcoming $25,000 model, which was rumored to first start production in China.&amp;quot; 
 
https://www.benzinga.com/amp/content/24937051 
 
PT $1500 Q4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:42:01 </td>
   <td style="text-align:left;"> $TSLA where the news at I fucking want 1250 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:41:25 </td>
   <td style="text-align:left;"> $TSLA Post Market action from Tuesday and today.  Very similar in nature and we all know what happened yesterday.  They buy up shares in the After Hours and then pump it first thing upon opening bell.  They then use those same shares as ammunition to short and walk it down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:40:35 </td>
   <td style="text-align:left;"> $NKLA There is a new chef in town who produces a carbon zero Truck. Gains are gonna made here dear $TSLA collegues 😬📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-07 05:40:27 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $TSLA is the #3 stock that institutions are trading over rolling 5 day window with 299.4K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
</tbody>
</table></div>

---
