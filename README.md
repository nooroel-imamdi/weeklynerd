# Weekly Nerds
Deze repository bevat een verzameling aan sketchnotes die zijn gemaakt gedurende de twaalf colleges die zijn gegeven op de Weeky Nerd-dagen. Op vijf van de twaalf weekly nerds is dieper ingegaan middels een artikel. Ook deze artikelen zijn in deze repository terug te vinden.

## Inhoud
1. [Artikelen]()
⋅⋅* [Een eigen bedrijf ná het CMD]()
⋅⋅* [Theme Parks for the Web]()
⋅⋅* [Sketchnotes]()
⋅⋅* [Accessibility]()
2. [Sketchnotes Weekly Nerds]()

## Artikelen

### Een eigen bedrijf ná het CMD
Nick de Bruijn is samen met Pim Verlaan oprichters van Lifely, een bedrijf dat bedrijfssoftware ontwikkelt. Zij digitaliseren processen en ontwikkelen doordachte webapplicatie op basis van business intelligence.

Zowel De Bruijn als Verlaan zijn voormalig studenten Communication and Multimedia Design (CMD) aan de Hogeschool van Amsterdam. Volgens de eerst genoemde werd de basis van hun partnerschap gelegd op de allereerste dag bij het CMD, waarbij deze twee individuen door hun toenmalige docent als het laatkomers-groepje aan elkaar werden gekoppeld, wat uiteindelijk zal resulteren in het inmiddels vijfjarig bestaan van Lifely. Het duo De Bruijn en Verlaan hebben de opleiding echter nooit afgemaakt.

#### Mensen moeten snel hun werk kunnen doen
‘Software is noodzakelijk in de business’. Vanuit dit idee is Lifely gaan inzetten op het ontwikkelen van software en systemen op basis van web-technieken. Uit hun eindproductie bestaat 80% uit systemen en slechts 20% uit web.

#### Gebruik van Frameworks in de échte wereld
In de minor ‘Webdevelopment’ krijgen we de basis mee dat we focus dienen te leggen op Vanilla JavaScript en het liefst frameworks uit de weg dienen te gaan. Bij Lifely maakt men echter wel gebruik van frameworks, met name React en Meteor. Verklaring van De Bruijn: Frameworks zijn veel sneller, gestructureerd en bovendien is het allemaal sneller te ‘shippen’. Belangrijkste hierbij blijft dat je begrijpt wat er onder de motorkap van een dergelijke framework gebeurd. Er is dus helemaal niets mis met het gebruik frameworks. Gebruik ze echter effectief en niet kwantitatief.


#### CMD-ers versus Uni-ers
De Bruijn ging kort in op de verschillen tussen CMD-ers en Uni-ers die hij op de werkvloer bij Lifely heeft mogen ervaren. CMD-ers lossen problemen gelijk op, terwijl Uni-ers eerst een meesterplan bedenken en dan pas overgaan tot het oplossen van het werkelijke probleem. Daarnaast merkte De Bruijn op dat CMD-ers het totaalplaatje zien, iets wat je niet altijd van de Uni-ers kunt verwachten.

De Bruijn kwam tot slot met de nodige tips voor de CMD-ers:

- Zet in op je krachten, niet alles is een acht binnen het vakgebied.
- Los één probleem op.
- Pak het niet te groot aan.
- Voel je geen superman.

#### Wat is mijn kijk op een eigen bedrijf ná CMD?
Het verhaal van Nick de Bruijn over het bedrijfsleven kwam op een goed moment. De Bruijn gaf zijn lezing aan het eind van de reguliere vakken in de minor. Hierdoor kon ik een balans tussen hetgeen wat ik die afgelopen maanden in de schoolbanken heb mogen leren en datgeen wat in het bedrijfsleven wordt ervaren. Waar in minor grote nadruk op werd gelegd was het vermijden van het gebruik van libraries/frameworks. Dat is uiteraard het ideaalbeeld waarmee webdevelopers worden gekweekt. Je ziet echter dat er in het échte leven compromissen moeten worden gesloten, in het belang van het bedrijf. In het geval van De Bruijn gaat het om het versnellen van een bepaald proces van de totale productie. Bij deze lezing en gedachtengang leg ik dan ook de link met het lezing van Peter Paul Koch. Die stelt namelijk ook dat je het gebruik van libraries moet vermijden en het streven maximaal één library is. Ik denk dat je als bedrijf wel degelijk, verantwoord libraries kunt gebruiken om processen in te korten. Het allerbelangrijkste blijft dat je als bedrijf baas bent over welk invloed deze frameworks hebben het eindproduct en dat niet de frameworks gaan bepalen welk proces jouw eindproduct bepaald. Iedereen binnen het bedrijf die gebruikt maakt van frameworks moet op de hoogte zijn van de werking hiervan tot relatie met de webbrowsers. Indien deze gevallen van toepassing zijn is er wat mij betreft sprake van een juiste balans met de gewilde controle.


### Theme Parks for the Web

Jasper Moelker sprak in zijn college bij de Voorhoede onder andere over progressive enhancement en graceful degradation. Wat houden deze termen in?

Graceful degradation: Providing an alternative version of your functionality or making the user aware of shortcomings of a product as a safety measure to ensure that the product is usable. ~ WC3 Wiki

Progressive enhancement: Starting with a baseline of usable functionality, then increasing the richness of the user experience step by step by testing for support for enhancements before applying them. ~ WC3 Wiki

We leven in een wereld waarin iedereen gebruikt maakt van moderne operation systems en webbrowsers. Web developers hebben hierdoor alle vrijheid om volledig los te gaan met nieuwe tricks en hoeven geen rekening meer te houden met bejaarde webbrowsers die nieuwe technieken niet ondersteunen. Voor developers klinkt dit als muziek in de oren. De werkelijkheid ligt echter verre van deze ideale situatieschets. Hoe komt dat?

#### Factoren
Verschillende factoren leiden tot deze situatie. We hebben te maken met individuen die het web in gebruik nemen om slechts te consumeren. Deze groep ziet hierdoor vaak de technieken achter het web over het hoofd. Zij verwachten slechts de content die wij als ‘bouwers’ aan hen beloven. Het is dan ook aan de gebruikers zelf om hun systeem en webbrowsers up-to-date te houden, maar zoals je wellicht al kunt vermoeden toont een grote groep hiervan zich vergeetachtig ten opzichte onderhoud aan hun systemen en software. Al developers kunnen we naast het sturen van herinneringen slechts in spanning afwachten of gebruikers onze adviezen opvolgen.

Een andere factor zijn kantoren die slechts een decennia oude webbrowser toestaan die nog eens bepaalde scripts en plugins uitschakelen met het oog op beveiliging. Bovendien hebben we in bepaalde situaties te maken met lage resolutie schermen op de werkvloer en komt het vaak genoeg voor dat computers net aan de uitvoering van de algemene kantoorsoftware kunnen bijbenen.

Een factor die ook veelal over het hoofd wordt gezien is accessibility. Denk aan dyslectische eindgebruikers die onze ingewikkelde instructies amper kunnen volgen en blinde gebruikers die onze o zo belangrijke knoppen niet kunnen bedienen.

Als we deze factoren op een rijtje zetten, dan kunnen we alleen maar concluderen dat we leven in het onbekenden en opzoek moeten naar een manier om het web ook voor deze gevallen bruikbaar te maken. Daarmee vallen we terug op de principes ‘progressive enhancement’ en ‘graceful degradation’.

#### Wat heeft mijn voorkeur?
Als ik de principes ‘graceful degradation’ en ‘progressive enhancement’ tegenover elkaar zetten, ben ik van mening dat een webproduct gebouwd dient te worden op basis van de laatstgenoemde principe. Als developer weet jij als geen ander hoe divers het web de afgelopen jaren is geworden met verschillende operaton systems, webbrowers, apparaten, formaten en resoluties. Als developer ben je een expert en ben je in staat het web juist toegankelijker maken, in plaats van de gebruiker te kakken te zetten met ‘helaas, uw verouderde webbrowsers ondersteunt onze website niet’ (graceful degradation). Naar mijn mening bestraf je de gebruikers om iets waar hij in feiten totaal geen verstand van heeft, terwijl jij als developer deze ellende kunt voorkomen door hierop in te spelen met ‘progressive enhancement’. Het web is voor iedereen en dat bouw je met ‘progressive enhancement’.

##### Referentie
- [The World Wide Web Consortium (W3C)](https://www.w3.org/wiki/Graceful_degradation_versus_progressive_enhancement)


### Sketchnotes
Sketchnoting kent sinds de laatste vijf jaar een ware opmars. Het web staat er vol mee en binnen het CMD aan de Hogeschool van Amsterdam wordt vanaf de propedeuse sterk geadviseerd om te ‘sketchnoten’ tijdens de colleges. Maar wat zijn sketchnotes?

“Sketchnotes zijn rijke visuele notities gemaakt uit een mix van handschrift, tekeningen, handgetekende typografie, vormen en visuele elementen zoals pijlen, vierkanten en lijnen.”
*~  Mike Rohde, een guru op het gebied van sketchnote.*

Bij sketch is er sprake van het activeren van de linker en rechter hersenhelften. De linker hersenhelft verwerkt woorden, terwijl de rechter hersenhelft visueel is ingesteld.

De vraag die vrijwel altijd wordt gesteld voor aanvang van een college op school is: mogen we ook onze laptop gebruiken om aantekeningen te maken? Het meest voor komende antwoord is ‘nee’. De meeste docenten voegen daarbij de onderbouwing aan toe dat bij het gebruik van laptops afleidende factoren kunnen optreden, zoals Facebook en andere soortgelijk social media-kanalen. Dit is echter niet enige onderbouwende reden om het gebruik van laptops tijdens colleges te vermijden.

Derek Bruff heeft onderzoek gedaan naar het gebruik van sketchnotes op scholen en verwerkte zijn resultaten in het artikel ‘Why Use Sketchnotes in the Classroom?’.
Op basis van logica vertelt Bruff dat wanneer je aantekeningen maakt in de vorm van sketchnoting, dat je dan intensiever bezig bent doordat je zaken gaat visualiseren. Dit zou logischerwijs er toe leiden dat je zaken, ten opzichte van laptop-aantekeningen, langer in het geheugen kunt bewaren.

Dan gaat Bruff in op de bewijsvoering. Hiervoor haalt hij de neurologische theorie dual coding aan. Het idee achter deze theorie is dat wij inkomende informatie verwerken door middel van twee kanalen: het verbale en het visuele. Wanneer we deze kanalen laten doen samenwerken, dan zij we beter in staan om ideeën te begrijpen en te herinneren. Indien een sketchnoter een nieuw idee presenteert middels sketching en diagrammen, dan is er sprake van dual coding.

De onderbouwing van Bruff tot slot: sketchnoting bevordert actieve verwerking van informatie en deze bevorderen een bruikbaar evenwicht tussen hoofdideeën en details.

#### Wat is mijn kijk op sketchnoting?
Als ik vanuit persoonlijk vlak kijk, ben ik pas echt gaan sketchnoten bij aanvang van de minor Webdevelopment. In eerste instantie meer omdat het ‘verplicht’ werd gesteld binnen de minor. Naarmate ik ben gaan sketchnoten is er ook een bepaalde plezier bij komen kijken. Ik had namelijk altijd het idee dat sketchnoten ‘een soort van tekenen’ inhield en dat is nou net iets waar ik mezelf absoluut de competenties voor zie hebben. Al snel werd duidelijk dat het niet om de tekenkunst gaat, maar puur gaat om informatie op een bepaalde manier te verwerken. Bovendien, als je na enkele maanden je sketchnote terugziet, blijf je toch langer staren naar je aantekeningen dan dat je voorheen deed bij de ‘steekwoorden-aantekeningen’. Ik ben nog slechts een beginner in sketchnote, want ook dit is een kunst: maar dan een kunst van de juiste informatie verwerken.

##### Referentie
- [Why Use Sketchnotes in the Classroom?](http://derekbruff.org/?p=2902)
- [Functies van linker en rechter hersenhelft](http://www.brainquest.nl/functies-van-linker-en-rechter-hersenhelft/)

### Wat is er mis met webdevelopment
Peter Paul Koch is een front-end programmeur die onderzoek doet naar browserverschillen. Hij is de oprichter van quirksmode.org, dat hoog aangeschreven staat bij front-end programmeurs en browsermakers. Hiermee brengt Koch adviezen uit aan onder andere Google, Microsoft, Mozilla, Samsung en BlackBerry.

Op de Hogeschool van Amsterdam sprak Koch over de hoedanigheid van webdevelopment, hedendaags. De volgende drie punten ervaart Koch als problemen binnen webdevelopment:

1. Het nabootsen van Native Apps;
2. Hoeveelheid features in de browser;
3. Libraries/tools;

#### Het nabootsen van Native Apps
Webdevelopers liepen de afgelopen jaren met de gedachten native apps in de webbrowsers te kunnen maken. Men dacht dat hetgeen Native Apps op de Windows en iOS kunnen, dat een deel daarvan ook op het web gedaan zou kunnen worden met behulp van JavaScript. De meeste bekende voorbeeld is Google Docs, die moest Microsoft Office vervangen in de browsers. Op het moment dat men doorkreeg dat deze tot zekere hoogte van waarde waren en ook degelijk werkten. Google Docs was geen betere nieuwkomer maar goed genoeg. Webontwikelaar waren enthousiast over deze ontwikkeling en dachten dat de Native-wereld ook ‘gewoon’ op het Web tot leven kan worden gewerkt. Met deze mindset deed Webdevelopment zijn intreden in de mobiele wereld.

Op het moment dat de komst van iPhone en Android wereldkundig werd gemaakt en bekend werd dat het een revolutie zou worden over hoe computers gebruikt gingen worden, dachten developers: ‘dat kunnen wij ook op het web met de kennis die wij hebben van JavaScript’. De werkelijkheid bleek anders. Deze mindset is echter nog niet uit de gedachtes verdwenen en zorgen er volgens Koch momenteel voor dat we veel te ingewikkeld denken over webdevelopment.

Het verschil tussen Native Apps en Web Apps in een notendop:
Native Apps ‘praten’ direct met de Operating System
Web Apps ‘praten’ praten met de Webbrowser en de Webbrowser praat met de Operating System.

#### Hoeveelheid features in de browser
De browsers maken te veel features aan per jaar. Als je aan de gemiddelde developer vraagt welke features er in de afgelopen jaar zijn gemaakt, dan zijn die niet meer te benoemen door de hoeveelheid. Koch heeft niet zo zeer moeite met features in de browser, maar met de hoeveelheid. Elk individu kan iets nuttigs zien in een feature. Alleen de hoeveelheid die men voor de kiezen krijgt, daar is Koch op tegen. Koch stelt hardop de vraag: ‘Is dit de weg die wij willen bewandelen binnen webdevelopment en browsers.

#### Libraries/tools
Koch ergert zich aan het hoeveelheid gebruik van tools. Net zoals bij het val van de features heeft hij geen bezwaar tegen individuele tools, maar gaat hem om de hoeveelheid gebruik in een website. Het fundamentele verschil tussen webdevelopment en alle andere soort development is dat bij webdevelopment alle scripties zelf door ons worden uitgevoerd en vervolgens naar de gebruiker worden verstuurd. Hierbij wordt deze scriptie bij elke request opnieuw uitgevoerd, terwijl dat in andere omgevingen dan webdevelopment slechts één wordt uitgevoerd. Volgens Koch is dit dan ook de grote denkfout die men in het verleden gemaakt heeft.

**Wat moet een echte webdevelopment programmeur kunnen?**
Een webdevelopment programmeur gebruikt volgens Koch wel degelijk tools. Echter zal hij deze tools bestuderen voor dat hij ze werkelijk gebruikt binnen zijn eigen werk. Wat doen deze? Rommelen deze te veel in de DOM? Als er namelijk iets slecht is voor performance, dan is dat ‘lopen rommelen in de DOM’. Volgens Koch denken Webdevelopers hier de weinig over na. Een echte webdeveloper geeft er de voorkeur aan slechts één tool in zijn project te gebruiken. Koch pleit ervoor dat er keuzes worden gemaakt tussen libraries. Boven is ene echte webdeveloper volgens Koch in staat om een middelmatige complexe applicatie geheel zonder tools te schrijven. Dat hoeft dan ook weer niet in elke project, maar minstens 2 á 3 keer per jaar, zodat jezelf kunt begrijpen  wat de browser met jouw code kan doen en welke dingen er fout kunnen gaan. Dat stelt je dan weer in staat om die libraries beter te begrijpen. Volgens Koch ontbreekt deze achtergrondkennis in de webdevelopment-wereld. ‘Ben je niet in staat een website te maken zonder tools, dan ben je geen webdeveloper’, aldus Koch.

#### Wat is mijn kijk op Koch-opinie?
De lezing van Peter Paul Koch was voor mij een eyeopener. Na deze college heb ik webdevelopers gegroepeerd in twee groepen: de échte webdeveloper en de hobbyistische webdeveloper. Je bent namelijk pas echt een webdeveloper als je vanaf nul een website kunt maken met de daar bijhorende principes (semantisch en syntactisch) en eventueel een library gebruikt waarvan de volledig weet hoe deze inwerking treedt en hoe de browser deze library interpreteert. Daartegenover, een hobbyistische webdeveloper bouwt een website op basis van libraries, maar heeft totaal geen idee wat deze voor functie hebben en hoe de browser op deze libraries reageert. Het echte verschil tussen échte webdeveloper en een hobbyistische webdeveloper wordt gemaakt in de kennis over het gedrag van de browser op bepaalde toestand van de code.


### Accessibility
Bram Duvigneau is een webdeveloper en accessibility consultant. Belangrijk detail: hij is blind. Tijdens de college op de Hogeschool van Amsterdam demonstreerde Duvigneau hoe hij het web ervaart. Met behulp van een screenreader en een special toetsenbord doorliep Duvigneau het web. Deze demonstratie opende voor mij persoonlijk een wereld  waar ikzelf hiervoor totaal bewust van was. Uiteraard krijg je tijdens de studie lappentekst onder je neus geschoven over accessibility maken van het web, maar het echte bewustzijn ontstond pas tijdens de lezing van Duvigneau.

Als developer draag je een verantwoordelijkheid om het web ook voor mindervaliden toegankelijk te maken. Dat kan al simpel door je strikt aan de standaarden te houden. Wat mij het meest aangreep was het moment dat Duvigneau een website bezocht die semantisch niet helemaal correct in elkaar zat en dat hij met pijn en moeite kon achterhalen wat er gaande was. Dat was het moment dat ik een bepaalde denkwijze ben gaan vormen over webdevelopers die de toegang tot een website voor mindervaliden versperren, doordat zij onverantwoord coderen. Als webdeveloper ben je een soort bruggenbouwer. Je baant een weg naar het einddoel van de weggebruiker en daar draag je een bepaalde verantwoordelijkheid. Als een belangrijke brug niet voor iedereen toegankelijk is, dan heb je duidelijk iets niet goed gedaan. Ik ben dan ook van mening dat het standaard in het takenpakket van een developer moet zitten dat een website toegankelijk moet zijn voor iedereen, dus ook voor mindervaliden.

#### Web Content Accessibility Guidelines (WCAG)
De  World Wide Web Consortium (W3C) heeft een guideline opgesteld waarin wordt geadviseerd hoe je web content toegankelijk kunt maken, gericht op mensen met een beperking. Deze staat bekend als Web Content Accessibility Guidelines (WCAG).

#### WCAG 2.0
Er is inmiddels een 2.0 versie van de Web Content Accessibility Guidelines. Deze is opgesteld volgens vier principes:

- Waarneembaar (perceivable): alle informatie en alle componenten van de gebruikersinterface moeten waarneembaar zijn door de gebruiker.
- Bedienbaar (operable): alle componenten van de gebruikersinterface en de navigatie moeten bedienbaar zijn door de gebruiker.
- Begrijpelijk (understandable): alle informatie en het gebruik van de interface moet begrijpelijk zijn voor de gebruiker.
- Robuust (robust): content moet voldoende robuust zijn om betrouwbaar geïnterpreteerd te kunnen worden door uiteenlopende soorten gebruikersagenten (user agents), met inbegrip van technische hulpmiddelen (assistive technologies).

##### Referenties
- [World Wide Web Consortium (W3C). (2007, 27 november). Web Content Accessibility Guidelines 2.0.](https://www.w3.org/TR/2007/WD-WCAG20-20071211/)

## Sketchnotes Weekly Nerds

### #1 Stephan Hay (Catawiki) - Ux ?= FeD
![Stephan Hay (Catawiki) - Ux ?= FeD]()

- Maak je eigen Guidelines
- Stop met aannames. Ga zelf ermee aan de slag en maak iets unieks.
- Start met échte content. Géén lorem ipsum.
- Maak breakpoints stapgewijs. Doe dat niet device-gericht.


### #2 Justus Sturkenboom (HvA) - Sketchnotes
![Justus Sturkenboom (HvA) - Sketchnotes]()

- Aanpak Sketchnotes
- Sketchnotes komt tot stand met slechts basis vormen.
- Corrigeer fouten met een hartje, ballon, bloemetje etc.


### #3 Peter Paul Koch (PPK) - Browser bloat
![Peter Paul Koch (PPK) - Browser bloat]()

- Maximaal één library per project
- Frontender moet de browser begrijpen
- Drie kernwaarden van het web: url, bereik en eenvoud van het web.


### #4 Titus Wormer (HvA) - Advanced Git Tips & Tricks
![Titus Wormer (HvA) - Advanced Git Tips & Tricks]()

- Geschiedenis GIT
- Demonstratie GitHub
- License: MIT, GPL, LGPL


### #5 Jasper Moelker (Voorhoede) - DevLovesDes
![Jasper Moelker (Voorhoede) - DevLovesDes]()

- Progressive enhancement vs Gracefull degradation
- Feature detection: baseline - acceptable - enjoyable
- Web for everyone: touch, hear, see, speak


### #6 Bram Duvigneau - Accessibility
![Bram Duvigneau - Accessibility]()

- Coockie-melder zit blinde vaak in de weg.
- Worse web: te veel JavaScript, geen fallbacks, niet voldoende getest.
- Maak DOM-tree toegankelijk door gebruik van strikte principles.


### #7 Peter Peerdeman (Lifely) - RTW en GraphQL
![Peter Peerdeman (Lifely) - RTW en GraphQL]()

- Websockets
- Load balancing


### #8 Niels Leenheer (HTML5test) - Obscure browsers
![Niels Leenheer (HTML5test) - Obscure browsers]()

- IoT == Boring... Make it exciting
- Notificatie-werking brievenbus


### #9 Eva-Lotta Lamm - Sketchnotes
![Eva-Lotta Lamm - Sketchnotes]()

- Loop: thinking - visualisation - reflect & evaluation
- Structure - fidelity - clarity - visual hierarchy


### #10 Nick de Bruijn - Een eigen bedrijf door en met CMD'ers
![Nick de Bruijn - Een eigen bedrijf door en met CMD'ers]()

- Gebruik van frameworks om proces te versnellen.
- Voormalig CMD-student, maar studie nooit afgemaakt.


### #11 Guido Bouman (Q42) - Interaction Engineering
![Guido Bouman (Q42) - Interaction Engineering]()

- Koffiezetapparaat houdt realtime koffie-gebruik bij
- LoRa: gratis verbinding zoals wifi, maar dan heel langzaam.
- Nederlandse developers krijgen techniek goed mee. Staan goed op de kaart.
