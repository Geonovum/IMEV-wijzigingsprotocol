## Inleiding

### Introductie

Geonovum ontwikkelt en beheert het Informatiemodel Externe Veiligheid (IMEV) in opdracht van het minsiterie van Infrastructuur en Waterstaat. Mensen die in de praktijk gebruik maken van dit informatiemodel hebben vragen over de toepassing ervan, willen weten welke ontwikkelingen er spelen, en hebben mogelijk suggesties voor aanpassingen van het informatiemodel.
Het opstellen en gebruik van het protocol is onderdeel van het beheerproces van een standaard. Geonovum voert het beheer en de doorontwikkeling van standaarden, waaronder het Informatiemodel Externe Veiligheid, uit conform het beheer- en ontwikkelmodel voor open standaarden: <a href='https://www.logius.nl/diensten/bomos' target='_blank'>BOMOS</a>.
Wijzigingen in het Informatiemodel Externe Veiligheid worden niet zomaar doorgevoerd; voor de ene gebruiker van het model zal de wijzing gering zijn, voor de ander kan het grote gevolgen hebben. Daar houden wij rekening mee. De gebruikersgroepen van de standaarden en andere betrokkenen in het wijzigingsproces zijn vastgelegd, evenals de belangrijkste taken en verantwoordelijkheden en de momenten waarop zij betrokken zijn in dit proces.

### Waarom een wijzigingsprotocol

In dit wijzigingsprotocol staan de sturende principes achter het wijzigingsproces voor deze standaard die Geonovum: de manier waarop wijzigingen in het Informatiemodel Externe Veiligheid plaatsvinden. Met het protocol wordt elke wijziging van het informatiemodel een voorspelbaar proces voor de ketenpartners en gebruikers van het informatiemodel. In het protocol zijn basisbegrippen en uitgangspunten uiteengezet voor het wijzigingsproces, bijvoorbeeld wat onder nieuwe en volgende versies verstaan wordt, en wanneer deze nieuwe versie(s) verwacht mogen worden. Tevens is een processchema uitgewerkt, dat invulling geeft aan de stappen die de gebruikers en ketenpartners met elkaar doorlopen om tot een wijziging van de geo-standaarden te komen.

### Begrippen

<table style='width: 100%;'><caption></caption>
<colgroup><col id='col1' style='width: 28.25374531835206%;'
<col id='col2' style='width: 71.74625468164794%;'
</colgroup>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><b>Adviesgroep</b>

</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'>Doel van de IMEV Adviesgroep is het sturen op verbinding en samenhang bij de doorontwikkeling van het informatiemodel. Dit doet zij door het controleren van het tot zover doorlopen wijzigingsproces, het wijzigingsvoorstel van advies te voorzien (het al dan niet doorvoeren van de wijzigingen en opleveren van een nieuwe versie van IMEV) en dit advies aan de opdrachtgever voor te leggen. De opdrachtgever besluit of de wijzigingen worden doorgevoerd op het IMEV. 
De bronhouders worden via de koepels IPO, VNG en ODNL vertegenwoordigd in de IMEV Adviesgroep. Ook het ministerie van IenW als opdrachtgever, Rijkswaterstaat als beheerder van het REV en Geonovum als beheerder van het IMEV nemen deel aan deze adviesgroep.


</aside>

</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><b>Expert- en gebruikersgroepen</b>


</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'>De expert- en gebruikersgroepen leveren input voor de impactanalyses van de wijzigingsverzoeken aan het IMEV-beheerteam van Geonovum.

</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><b>IMEV en beheerobjecten</b>

</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'>Het Informatiemodel Externe Veiligheid bevat afspraken over de digitale structuur waarin overheden gegevens vastleggen over de opslag, het transport en het gebruik van gevaarlijke stoffen. Het IMEV bestaat uit:

<ul>
<li><i>Modeldocument</i></li>
<li><i>JSON-schema</i></li>
<li><i>Voorbeeld API-specificatie</i></li>
<li><i>Voorbeeldbestanden</i></li>
<li><i>Het EAP-bestand met UML diagrammen</i></li>
</ul>

</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><b>Wijzigingsprotocol</b>

</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'>Hiermee wordt het geheel van vastgelegde regels en afspraken voor het wijzigen van de standaard en de bijkomende beheerobjecten vastgelegd.

</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><b>Wijzigingsproces</b>

</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'>Het wijzigingsproces is de daadwerkelijke wijziging van het IMEV en/of een van de overige beheerobjecten, op een bepaald moment. Het volledige wijzigingsproces doorloopt de fasen van het wijzigingsprotocol met een datum van inwerkingtreding van de nieuwe versie van het IMEV en haar onderdelen. 

</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><b>Wijzigingsverzoek</b>

</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'>Wijzigingsverzoeken zijn wensen of eisen voor aanpassing van de standaard. Een wijzigingsverzoek wordt door een gebruiker van de standaard ingediend bij de IMEV-helpdesk van bij Geonovum. Volgens de gebruiker moet het Informatiemodel op een bepaald onderdeel met reden worden aangepast of aangevuld voor een betere werking van de standaard. Het wijzigingsverzoek wordt door het IMEV-beheerteam beoordeeld, ingeschat en aan de wensen- en eisenlijst toegevoegd die voor iedereen toegankelijk is via de publieke IMEV werkomgeving op [GitHub]https://github.com/Geonovum/imev-werkomgeving/issues). Een wijzigingsverzoek dat niet wordt ingewilligd, wordt beargumenteerd afgewezen. 

</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'><b>Wijzigingsvoorstel</b> 

</td>
<td align='left' style='border-top: 0.5pt solid #000000; border-left: 0.5pt solid #000000; border-bottom: 0.5pt solid #000000; border-right: 0.5pt solid #000000; background-color: none;'>In het wijzigingsproces worden meerdere wijzigingsverzoeken gebundeld tot één wijzigingsvoorstel voor het wijzigen van de standaard en de bijkomende beheerobjecten. 

</td>
</tr>
</tbody>
</table>
