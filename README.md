# Web-Typografie | Stella Niewenhuis

Als je doof bent, of als je om een andere reden geen geluid kunt horen, dan mis je veel informatie als je een film kijkt. Knisperende voetstappen, langzaam aanzwellende muziek, nerveus getik op een deur, je hoort het natuurlijk allemaal niet. Nu bestaat er zoiets als closed caption, wat een type ondertiteling is waarbij ook dingen als omgevingsgeluiden en de muziek beschreven worden. Hierdoor krijgt een kijker die informatie wel binnen.

Alleen wordt die auditieve informatie nogal neutraal beschreven. Het geluid van huilend persoon zou bijvoorbeeld beschreven kunnen worden als snikgeluid op de achtergrond. En iemand die lacht zou geschreven kunnen worden als iemand lacht. Heel neutraal, bijna zakelijk, en bovendien allebei in precies hetzelfde neutrale lettertype. Terwijl het toch echt over twee heel verschillende emoties gaat.

Dat kan visueel sterker.

De afgelopen 3 weken heb ik dit bij twee fragmenten van Blade Runner 2049 (tijdens de baseline test in het begin van de film en het einde) mogen doen. Door middel van HTML en CSS was het aan mij de taak om de geluiden en closed capions te visualiseren zodat de user experience voor Marie zou verbeteren. 

# Marie is doof
Wij ontwerpen voor Marie en zij is doof. Dat betekent dat zij geen geluid hoort en communiceert met gebarentaal. Zij kan niet praten. Door middel van een tolk hebben wij kennis met haar gemaakt. Even kort op een rijtje wat info over haar: 

- Ze houdt erg van lezen
- Ze trillingen van heel hard geluid kan ze voelen 
- Ze kan heel snel de ondertitels lezen
- Het is vaak lastig om echt de spanning van een film te voelen. 



# Test 1

## Het ontwerp 

Ik had voor test 1 alleen het eerste fragment uitgewerkt. Waar ik me op had gefocust, was in eerste instantie de positie van de close captions. Ik probeerde vanalles uit; boven het scherm tekst en onder het scherm tekst, of links onder en rechts onder. Uiteindelijk had ik voor het laatste gekozen. De stem van de machine had ik links uitgelijnd van het scherm en de stem van K had ik rechts uitgelijnd. Verder had ik stem 4 in het midden uitgelijnd. Verder had ik een fel blauwe dropshadow op de video-placeholder gezet die ik van kleur liet veranderen bij de climax voor het einde van frament 2 (waar ingezoomd wordt op de hoofdpersoon). Hierbij veranderde ook de grootte en dikte van de letters op dat moment. Ik hoopte natuurlijk dat dit iets zou doen met Marie... 

## Feedback Marie 

- De ondertitels waren nu niet fijn te lezen. Het leek wel alsof ze naar een tenniswedstrijd aan het kijken was. 
- De climax kwam totaal niet over. 
- Ze vond de blauwe video-placeholder te abstract. Als de kleursveranding van de dropshadow staat voor verandering van het geluid, dan wil ze weten wat dat geluid dan is. 
- Comments erbij zou ze dus fijn vinden. 
- Marie vond het cool dat ik had gedacht aan hoe ik de letters wilde weergeven (niet meteen zichtbaar, maar woord voor woord).

## Feedback Vasilis
- Vasilis vond dat ik goed bezig was en vertelde eigenlijk aan ons alledrie (Rebecca Lisa en ik), dat we vooral moesten kijken naar hoe we het geluid zouden gaan visualiseren. We waren nu best wel bezig geweest met de closed captions zelf namelijk.

# Test 2

## Mijn ontwerp

Ik heb veel aangepast na de eerste feedback van Marie. Zo heb ik zelf tekst toegevoegd om duidelijker te maken om wat voor geluid het gaat. Daarvoor heb ik best wel een tijdje nagedacht over de juiste tekst (in het Engels).  Ook het implementeren van de 'nieuwe tekst' ging niet erg makkelijk helaas, dus daar was ik veel tijd aan kwijt waardoor ik nog steeds alleen bezig was met het eerste fragment. Verder heb ik de closed captions een glow meegegeven en de achtergrond donkerder gemaakt zodat het er nog spannender uit zou zien. Ook heb de closed captions op 1 regel gezet i.p.v. links - rechts. Door middel van kleur heb ik onderscheid gemaakt tussen de stemmen. De extra tekst heb ik onder de closed captions gezet.  

## Feedback Marie 

- Ze vond het in het algemeen goed wat ik had. Dat was het eerste wat ze zei. 
- Ze was super enthousiast over de sfeer/kleur gebruik en het glow effect op de tekst. 
- De tekst was goed te lezen.  
- Ze vond het cool dat ik ook een shake animatie in de 'extra tekst had toegevoegd'.  
- Ze zei dat ik nog moest kijken naar de uiting van de beschrijving. Er zat nu wel een animatie in de tekst maar nog niet in de video-placeholder (alleen op de plek van de climax). Daar kon ik nog naar gaan kijken. 
- De climax kwam heel goed op haar over, ze voelde 'm echt goed (ik vroeg hier specifiek naar). 

## Feedback Vasilis
- Vond de algemene sfeer erg goed. 
- Vond de climax niet goed over komen (dit heb ik daarna nog snel aangepast voordat we de tekst met Marie hadden. Ik had de letters van SUDDDEN SILENCE groter gemaakt). 

# Eindresultaat - de belangrijkste ontwerpkeuzes

## Font

Ik hebben gekozen voor het Brenner font omdat er keuze was uit veel verschillende fonts. In het begin had ik Brenner Display voor de Machine en Brenner Mono voor K. Maar uiteindelijk ben ik toch gegaan voor Mono bij alle tekst maar heb ik gevarieerd in italic, normal en light. Verder heb ik bij de stem van de machine een roze dropshadow gezet. Ook heb ik voor deze font gekozen vanwege de goede leesbaarheid.


<img width="1086" alt="Schermafbeelding 2020-05-29 om 07 30 12" src="https://user-images.githubusercontent.com/45544342/83224748-7343dd00-a17e-11ea-91d2-1ea284936943.png">

De roze dropshadow bij de machine/ in combinatie met blauwe hightlights. De woorden worden 1 voor 1 laten zien bij het eerste fragment. Bij het tweede fragment wordt alles meteen laten zien omdat er meer spanning is en het sneller gaat. 

<img width="1098" alt="Schermafbeelding 2020-05-29 om 07 38 37" src="https://user-images.githubusercontent.com/45544342/83225168-78555c00-a17f-11ea-8b80-661a3b54a568.png">

Het was lastig om hier een foto van te maken. Maar er is veel variatie in hoe de tekst verschijnt bij K. Zo zijn de antwoorden van K light wanneer de baseline test nog niet is begonnen en verschijnt het antwoord in een keer. Wanneer hij bezig is met de baseline test, zie je de tekst al staan alleen worden de woorden 1 voor 1 dikgedrukt. Dit heb ik gedaan om naar voren te laten komen dat hij een stuk tekst voorleest wat in zijn systeem zit. Daarom staat het er al, maar worden de woorden 1 voor 1 dikker. Bij fragment 2 zijn is dit effect weggehaald en zie je alles in 1 keer. Dat heb ik gedaan om het directer te laten overkomen, omdat er in fragment 2 meer spanning is. Ook heeft K meer meegemaakt in de film waardoor hij het riedeltje niet echt meer voorleest. 


## Geluid - de ontwerpbelangrijkste keuzes

<img width="1102" alt="Schermafbeelding 2020-05-29 om 07 43 02" src="https://user-images.githubusercontent.com/45544342/83225663-92dc0500-a180-11ea-846b-50bec370cb3f.png">

Na de feedback van Marie, heb ik naast de animaties in de toegevoegde tekts, tegelijkertijd een animatie (denk aan shaken van het scherm, bewegen van het scherm etc.) gezet op de video-placeholder. Zo is de beschrijving echt gelinkt aan de omschrijving, en geeft de kleursverandering en het ritme en van de beweging van de video-placeholder ook meer over het ritme van het geluid en de trillingen. Marie had vertelt dat ze trillingen wel kan horen. 

<img width="1680" alt="Schermafbeelding 2020-05-29 om 07 49 46" src="https://user-images.githubusercontent.com/45544342/83225880-04b44e80-a181-11ea-8505-1ff7d8024300.png">


<img width="1680" alt="Schermafbeelding 2020-05-29 om 07 54 02" src="https://user-images.githubusercontent.com/45544342/83226202-b5bae900-a181-11ea-8e91-dab56d810bf7.png">

Het scherm wordt langzaam gevuld met grijze waas. Dit grote effect heb ik bedacht voor het laatste fragment, omdat je de muziek continue best hard hoort en deze tot het einde doorgaat. De spanning houdt aan. Ik wilde een groot verschil maken met het eerste fragment. Aan het einde wordt het scherm helemaal rood gevuld. Ik heb telkens bij de geluidsanimaties gebruik gemaakt van een wisseling van blauw naar rood. Dat heb ik hier ook gedaan alleen dan veel extremer. 

Aan het einde heb ik ook nog een blink gemaakt, waarbij het scherm net even wegvalt en het geluid even stopt, voor de conclusie van de test: 'Your not even close to baseline'.

# Exclusive Design Principles

## 1. Study situation
Het was een hele grote uitdaging om je echt in te kunnen leven in iemand die niet kan horen, iets dat voor jou (en bijna iedereen) super normaal is. Door in contact te komen, en vragen te kunnen stellen aan iemand, in dit geval Marie die doof is en waar we voor ontwerpen, kom je echt veel te weten. Naast dat ik alle gesprekken met Marie echt een eye openere vond, vond ik het ook heel interessant dat Marie soms zei als iemand vroeg : "Mis je nog wat?', en Marie antwoordde: 'Ik weet niet hoe het normaal is, dus weet ik ook niet wat ik mis'. Het was echt aan ons de taak om het geluid aan haar over te brengen, maar door een ander middel dan we gewend zijn. Maar ook was het interessant om te zien dat bepaalde dingen bij haar gewoon echt niet aansloegen. Het testen is super handig geweest om haar echt beter te begrijpen. 


## 2. Ignore conventions
Ik ben wel out of the box gegaan en heb alles wat meer overdreven. Vooral bij het tweede gedeelte. Geluid zie je natuurlijk normaal gesproken niet, dus het is niet normaal dat het wordt gevisualiseerd. In dit geval pak ik het anders aan en probeer ik visueel juist het geluid te weergeven, zodat het voor Marie duidelijk is wat er gebeurt met het geluid. Zo zal haar ervaring beter en minder saai worden. 


## 3. Prioritese identity
We hebben bij dit project veel contact gehad met Marie, en haar veel kunnen vragen. Bij het kennismakingsgesprek leerde je veel over haar situatie en tijdens het testen kwam je erachter dat heel veel dingen die voor mij logisch zijn, voor haar niet logisch zijn. Ze vond de glow van mijn tekst en de donkere achtergrond wel heel sfeervol en dat heb ik daarom ook zo gelaten. 
Verder heb ik telkens haar feedback zo goed mogelijk geprobeerd te bewerken. Het belangrijkste is ook wel geweest om het fragment steeds ZONDER GELUID af te spelen en te bedenken of het genoeg met Marie zou doen. 


## 4. Add nonsense
Sommige dingen die ik heb toegepast zijn best wel ongebruikelijk en overdreven. Zoals de bewegingen van de video-placeholder bv. Maar dat geeft juist helemaal niet omdat er voor Marie een heel deel van de ervaring mist, namelijk geluid. 
Je kunt dat als het ware compenseren door meer met beweging en visualisaties te doen, zodat Marie een betere (en niet zo'n saaie) ervaring heeft. Nou moet ik wel zeggen dat ik het niet too much heb gedaan omdat Marie niet BLIND is. Ook vind ik dat je niet teveel met het beeld in de film moet doen omdat er ook door de regisseur is nagedacht over hoe dingen worden laten zien. Het versterken van wat er te zien is/wat er gebeurt en dat gelijktrekken aan de visualisaties van het geluid, zijn naar mijn mening het belangrijkst. Met behulp van de feedback van Marie heb ik het zo veel mogelijk naar hand willen zetten. Wat ik zelf vooral belanrgijk vond en haar graag wilde meegeven van de film, waren de climaxen en het verschil tussen fragment 1 en 2. Naast het toevoegen van steeds losse elementen en wat overdreven dingen, heb ik geprobeerd die verhaallijnen niet teveel te onderbreken.  



# Waar liep ik tegenop bij dit project? 
- Ik heb het vooral heel onhandig aangepakt met mijn code. In het begin wist ik niet waar ik moest beginnen en keek ik naar het voorbeeld in de voorgeschreven code. Ik heb toen alle losse woorden in CSS uitgetypt! Ben daar wel 2 uur mee bezig geweest. 
- Ik ben vaak lang bezig geweest met het centreren van teskt etc.  Zo had ik zelf tekst toegevoegd in html, maar omdat dit onder elkaar stond als verschillende regels, had ik elk stukje tekst handmatig aangepast wat betreft de positie. Uiteindelijk kwam ik erachter dat je met position absolute kunt instellen dat ze allemaal op dezelfde regel staan. 
- Verder heb ik met zoveel dingen zoooooo lang gezeten voordat het lukte. Een voorbeeld: Het vergroten van het scherm (en dat de inhoud meeschaalt), bleek je in Javascript te kunnen aanpassen. Dat wist ik niet dus ik heb lopen zoeken in Javascript!
- Ik kwam erachter dat je een bepaalde animatie niet meerdere keren kunt gebruiken op hetzelfde element. Dat wist ik eerst ook niet,  dus niks werkt op een gegeven moment. Uiteindelijk hoorde ik het van een klasgenoot. 

# Wat heb ik geleerd? 
- Ik heb bij dit vak vooral geleerd om je heel erg in te leven in iemand met een beperking. Ik kwam er tijdens het ontwerpen echt achter dat het een enorme zoektocht was om Marie te kunnen overtuigen. Zelf dacht ik bij de eerste test dat ik het al best aardig voor elkaar had, maar dat bleek dan achteraf totaal niet aan te slaan. Ik heb dit project ervaren als UX met de nadruk op Visual Design. Een erg interessante combi! 
- Ik heb veel meer geleerd over css aimaties! Ben zelf niet zo'n ster in code maar ik moet zeggen dat ik aardig tevreden ben met hoe het is geworden:)



































