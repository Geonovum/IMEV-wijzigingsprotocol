## Gebruik van het wijzigingsprotocol 

Het protocol schrijft een vast stramien voor het wijzigen van de standaard voor. Het protocol benoemt de fasen en de op te leveren resultaten. Belangrijk zijn de randvoorwaarden en uitgangspunten. De gebruikers van het informatiemodel Externe Veiligheid betrekken wij bij het wijzigen van het model. We zetten op en rij welke betrokkenen er zijn.

### Protocol versus proces

De titel van dit document geeft aan dat het hier om een protocol gaat. Toch wordt in dit document ook gesproken over processen. Een <b>wijzigingsprotocol </b>beschrijft de <i>manier waarop</i> wijzigingen in het Informatiemodel Externe Veiligheid plaatsvinden: het <b>wijzigingsproces</b>. In het protocol zijn basisbegrippen en uitgangspunten uiteengezet voor het wijzigingsproces, bijvoorbeeld wat onder nieuwe en volgende versies verstaan wordt en wanneer deze verwacht mogen worden. De daadwerkelijke planning van een nieuwe versie wordt in overleg met de opdrachtgever en eigenaar van de standaard, het ministerie van Infrastructuur en Waterstaat, en de beheerder van de Register Externe Veiligheid (REV) periodiek afgestemd.
Met behulp van dit wijzigingsprotocol voor het Informatiemodel Externe Veiligheid geeft Geonovum:


<ul>
<li>inzicht in het behandel- en besluitproces dat ten grondslag ligt aan het versiebeheer;</li>
<li>inzicht in de wijzigingsverzoeken;</li>
<li>inzicht in een voorgestelde wijziging van de standaard;</li>
<li>stabiliteit aan de standaard;</li>
<li>continuïteit aan de standaard;</li>
<li>een eenduidige aanpak.</li>
</ul>

### Releasebeleid  
#### Nieuwe versie van de standaard

Een release van een standaard is een nieuwe uitgave van de standaard. De nieuwe release kenmerkt zich ten opzichte van de oude versie door een hoger versienummer. Een release betreft 1 product van een standaard of is een bundel van meerdere producten van de betreffende standaard. Bij de release is ieder product is voorzien een nieuw versienummer conform X.Y.Z schrijfwijze (zie hierna) en een status. Het JSON-schema en de voorbeeldbestanden hebben zo ieder hun eigen versienummer. 

Bij een standaard in beheer horen ook afspraken over het versiebeheer. Versies van een standaard zijn er in verschillende gradaties die elk een relatie hebben met een voorgaande versie. De wijzigingen documenteren wij en leggen wij vast in een apart document bij de uitgebrachte versie van de standaard. De gebruiker kan zo nagaan op welke plaatsen de betreffende standaard gewijzigd is.
Elk product van onze standaarden voorzien wij van een versienummer. Dit doen wij conform Semantic Versioning (SemVer). Elk product heeft zijn eigen versienummer conform X.Y.Z schrijfwijze, bijvoorbeeld versie 2.1.0 (=X.Y.Z):


<ul><li><b>X-wijzigingen</b> Dit zijn grote wijzigingen die de structuur van de standaard veranderen. Hierdoor zijn X-wijzigingen niet backwards compatible. Frequentie: in overleg met de opdrachtgever.</li></ul> 

<ul><li><b>Y-wijzigingen</b> Dit zijn wijzigingen die niet de structuur veranderen. Dit kunnen bijvoorbeeld updates zijn of inhoudelijke aanpassingen aan objecten, attributen of waardelijsten of de reikwijdte van de standaard. Deze wijzigingen zijn backwards compatible. Frequentie</u>: in overleg met de opdrachtgever.</li> </ul>

<ul><li><b>Z-wijzigingen</b> Dit zijn in feite oplossingen van technische fouten of verbeteringen van technische aard. Deze wijzigingen zijn backwards compatible. Frequentie: zo spoedig mogelijk na constatering.</li> </ul>

### Consultatie
Met het doorontwikkelen van het informatiemodel leveren wij nieuwe versies van de producten van de IMEV op. Doel van een consultatie is ons netwerk, de gebruikers van de standaard en de ketenpartners, te raadplegen; wij vragen hen om advies, zodat het IMEV zo goed mogelijk aansluit op de werkprocessen van de eindgebruikers van de standaarden. 
De consultaties zijn openbaar/ publiek en daardoor mag iedereen reageren op de nieuwe versie. Consultaties duren minimaal 3 weken en maximaal 8 weken. Bekendmaking gebeurt via de Geonovum website en wordt bekendgemaakt door middel van een nieuwsbericht op de website van Geonovum en via de website van het Register Externe Veiligheid. We attenderen de gebruikers en de ketenpartners via de REV- nieuwsbrief. Wanneer en hoe lang een consultatie plaatst vindt, is afhankelijk van proces varianten bij wijzigingen (zie paragraaf procesvarianten).

#### Oudere versie van een standaard

Na het uitbrengen van een nieuwe versie van een bij Geonovum in beheer zijnde standaard blijven oudere versies beschikbaar en zijn vindbaar via de <a href='https://www.geonovum.nl/geo-standaarden/informatiemodel-externe-veiligheid' target='_blank'>Geonovum website</a> en de registers (de <a href='https://definities.geostandaarden.nl' target='_blank'>conceptenbibliotheek</a>, het <a href='https://register.geostandaarden.nl' target='_blank'>technisch register</a> en het <a href='https://docs.geostandaarden.nl' target='_blank'>documentenregister</a>). Een nieuwe versie dwingt daarmee geen directe overstap af bij de gebruikers, tenzij anders (bijvoorbeeld wettelijk, bij ministeriële regeling) bepaald. Na het uitbrengen van de nieuwe versie van een standaard wordt de ontwikkeling van de oude versie stopgezet.

De SemVer-methodiek schrijft backwards compatibility voor op het Y-niveau.  

Voor het onderhoud en de ondersteuning van een oude versie van een standaard gelden de volgende uitgangspunten:

<ul><li>Aan een oude versie worden geen nieuwe features toegevoegd, geen aanpassingen gedaan op X en Y niveau na het uitbrengen van een nieuwe versie. Verzoeken om aanpassing en wijziging voor nieuwe functionaliteit worden niet meer voor de oude standaard in behandeling genomen maar doorgegeven aan het ontwikkelteam. Correcties (Z-wijzigingen) worden wel uitgevoerd op de vorige versies zolang deze nog ondersteund worden.</li>
<li>Bij oplevering van een nieuwe versie wordt de voorgaande versie nog een van te voren vastgestelde periode ondersteund. De duur van de overgangsperiode wordt mede bepaald door de omvang van de wijzigingen (X, Y en Z wijzigingen op de vorige versies), de staat van ontwikkeling van de standaard, en of de standaard in voorlopig dan wel permanent beheer is.</li>
<li>De duur van de ondersteuningsperiode voor de diverse soorten versies moet nog worden vastgesteld. Tot aan inwerkingtreden van de Omgevingswet, waar de Informatiemodel Externe Veiligheidsrisico's ook onder valt, zal naar verwachting de ondersteuningsperiode van verschillende versies anders zijn, dan in de periode van permanent beheer zonder dat daarnaast nog grootschalige ontwikkeling van de standaard plaatsvindt.</li>
</ul>

### <a name='_Ref482110995'></a>Proces varianten

In paragraaf <a href='#releasebeleid'>2.2<a></a> zijn de X, Y en Z wijzigingen uitgelegd. Voor wijzigingen kent Geonovum twee proces varianten. Eén voor X en Y wijzigingen en één voor Z wijzigingen.

<b>Proces voor X en Y wijzigingen</b>

X en Y wijzigingen vergen volledige afstemming en het doorlopen van alle in paragraaf 3.1 beschreven fasen: Inhoud, Toetsing, Besluitvorming en Implementatie. Voor de inhoudelijke fase worden niet alleen de experts en leveranciers betrokken vanuit reguliere overleggen maar ook extra bijeenkomsten met vertegenwoordiging van belangrijke stakeholders en gebruikers. Het resultaat van de besprekingen is het aanscherpen van de wijzigingsverzoeken en het wijzigingsvoorstel. Gedurende de fase ‘Toetsing’ vindt een consultatie (zie paragraaf 2.2.2) van het wijzigingsvoorstel plaats waardoor alle gebruikers van het IMEV en geïnteresseerden in staat worden gesteld te reageren op de komende wijziging. Het wijzigingsvoorstel inclusief de consultatiereacties wordt voorgelegd aan de IMEV Adviesgroep. De Adviesgroep adviseert het Ministerie van IenW (zie figuur 1). Besluitvorming over vaststelling van een nieuwe versie van het model vindt plaats door IenW. 

<b>Proces voor Z wijzigingen</b>

Dit betreft kleine wijzigingen die door Geonovum worden uitgevoerd en opgeleverd; dit wordt een bugfix genoemd. De inhoudelijke fase wordt door het beheerteam IMEV van Geonovum gedaan. Toetsing vindt plaats door middel van werksessies met experts en softwareleveranciers. Besluitvorming vindt plaats in afstemming met het Ministerie van IenW. Geonovum publiceert de nieuwe versie op de Geonovum website en informeert direct het Ministerie van IenW, de Adviesgroep en de softwareleveranciers. Bekendmaking gebeurt via de Geonovum website en wordt bekendgemaakt door middel van een nieuwsbericht op de website van Geonovum en via de website van het Register Externe Veiligheid. We attenderen de gebruikers en de ketenpartners via de REV- nieuwsbrief.


### Betrokkenen

De volgende groepen en instanties (actoren) zijn betrokken bij het wijzigingsproces van het Informatiemodel:

<ul>
<li>IMEV-Aviesgroep</li>
<li>Expert- en gebruikersgroepen</li>
<li>Softwareleveranciers</li>
<li>Geonovum</li>
<li>Rijkswaterstaat</li>
<li>Ministerie van Infrastructuur en Waterstaat</li>
</ul>

<figure style='width: 75%;'><a name='_Ref503260625'></a><img src='media/image5.png' alt='media/image5.png'></img>
<figcaption><a name='_Ref503260625'></a>Betrokkenen bij wijzigingen van het Informatiemodel Externe Veiligheid</figcaption></figure>

Het IMEV-beheerteam bij <b>Geonovum</b> ontvangt wijzigingsverzoeken ter verbetering van het informatiemodel, gebruik en de bruikbaarheid van het informatiemodel. De wijzigingsverzoeken worden getoetst en van baten en impactanalyses voorzien, door de verzoeken te toetsen bij experts, softwareleveranciers en de beheerder van het REV. 
De <b>expert- en gebruikersgroepen</b> rondom het REV en het IMEV leveren input op de wijzigingsverzoeken en daarmee doorontwikkeling van het IMEV. Ook toetsen wij de wijzigingsverzoeken bij de <b>softwareleveranciers</b> en <b>Rijkswaterstaat</b> als beheerder van het REV en vragen wij hen ons te adviseren. 
De wijzigingsverzoeken worden door het IMEV-beheerteam gebundeld tot een zelfstandig leesbaar wijzigingsvoorstel dat in verschillende iteraties bij het IMEV Adviesgroep wordt voorgelegd. De <b>IMEV Adviesgroep</b> stuurt op verbinding en samenhang bij de doorontwikkeling van het informatiemodel. Zij brengt advies uit op de door Geonovum voorgestelde wijzigingsvoorstel en legt dit advies voor aan het <b>Ministerie van Infrastructuur en Waterstaat</b> ter besluitvorming. De Directie Omgevingsveiligheid & Milieurisico’s van het ministerie besluit over de voorgestelde wijziging. Bij een positief besluit werkt Geonovum aan de oplevering van de nieuwe versie van het IMEV en gaat over op implementatieondersteuning. 

