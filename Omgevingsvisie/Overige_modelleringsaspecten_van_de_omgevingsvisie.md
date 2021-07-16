## Overige modelleringsaspecten van de omgevingsvisie

### Standaardindeling omgevingsvisie

#### Toelichting

Om het bestuursorgaan de mogelijkheid te bieden de omgevingsvisie zoveel
mogelijk naar eigen inzicht in te delen, stelt dit toepassingsprofiel slechts
één indelingseis. Die betreft de bijlage met namen en identificatiecodes van de
geografische informatieobjecten.

#### Norm

De Regeling van de omgevingsvisie moet een bijlage met namen en
identificatiecodes van de geografische informatieobjecten bevatten.

### Verwijzing

#### Toelichting

Een stuk tekst kan een verwijzing naar een ander tekstelement of ander document
bevatten. Voorbeelden hiervan zijn:

-   de verwijzing vanuit een begrip in een regel naar de begripsbepaling waarin
    dat begrip wordt gedefinieerd;

-   de verwijzing vanuit een beleidsregel over de toepassing van een open norm
    naar de regel waarin de open norm is vastgelegd;

-   de verwijzing vanuit een artikel naar de artikelsgewijze toelichting op dat
    artikel (en vice versa);

-   de verwijzing vanuit een regel naar een wettelijke bepaling;

-   de verwijzing vanuit een tekstelement in een omgevingsdocument met
    Vrijetekststructuur naar een ander tekstelement in datzelfde of een ander
    omgevingsdocument of in een ander besluit of regeling.

Het gaat hier om een simpele verwijzing; de verhouding tussen het ene
tekstelement en het andere tekstelement of document is niet gekwalificeerd. Met
de hier beschreven verwijzing wordt ook uitdrukkelijk niet de verwijzing vanuit
een Juridische regel, Divisie, Divisietekst of Tekstdeel naar een Locatie of een
OW-object bedoeld.

Het model maakt het mogelijk de hier bedoelde verwijzing te maken. Hiervoor
wordt gebruik gemaakt van de STOP-XML-elementen IntRef (voor verwijzingen tussen
tekstelementen binnen een omgevingsdocument) en ExtRef (voor verwijzingen vanuit
een omgevingsdocument naar tekstelementen in) andere documenten; dat kunnen
omgevingsdocumenten maar ook andere typen documenten zijn). Een verwijzing kan
gemaakt worden naar een tekstelement in de omgevingsvisie zelf, maar ook naar
(een tekstelement in) een ander document.

Bij een verwijzing naar een ander document is aandacht nodig voor de formulering
van de verwijzing. Wanneer een algemene verwijzing naar het andere document
wordt gemaakt, dus zonder te verwijzen naar een specifieke versie daarvan, zou
een wijziging in het andere document onbedoeld kunnen leiden tot wijziging van
de omgevingsvisie zonder dat daar een besluit van het bevoegd gezag aan ten
grondslag ligt. Zo’n algemene verwijzing zonder specifieke versie noemen we een
dynamische verwijzing. Wanneer het ongewenst is dat een wijziging in het andere
document doorwerkt in de omgevingsvisie kan een statische verwijzing worden
gemaakt. Er wordt dan expliciet verwezen naar een specifieke versie van dat
andere document.

Ten behoeve van de goede raadpleegbaarheid van omgevingsvisie wordt sterk
aanbevolen om in ieder geval gebruik te maken van de verwijzing vanuit een
begrip in een regel naar de begripsbepaling waarin dat begrip wordt
gedefinieerd.

#### Norm

Voor het maken van de verwijzing wordt gebruik gemaakt van de generieke
XML-elementen IntRef (voor de verwijzing naar een ander tekstelement in
hetzelfde document) en ExtRef (voor de verwijzing naar (tekstelementen in) een
ander document).

### Onderdelen van de standaard die voor omgevingsdocumenten met Vrijetekststructuur verplicht of noodzakelijk zijn

Een besluit kan pas in werking treden als het is bekendgemaakt, aldus artikel
3:40 Awb. De Bekendmakingswet stelt algemene regels over de bekendmaking. Voor
omgevingsdocumenten[^1] gelden specifieke regels[^2]. Omgevingsdocumenten, en
ontwerpen daarvan, moeten door het betrokken bestuursorgaan elektronisch worden
vormgegeven overeenkomstig STOP, IMOW en het betreffende toepassingsprofiel en
moeten voor publicatie worden aangeleverd aan het bronhouderskoppelvlak van de
LVBB. Daarnaast is in de Omgevingswet bepaald dat omgevingsdocumenten worden
ontsloten via DSO-LV.

[^1]: Omgevingsdocumenten zijn besluiten en andere rechtsfiguren die in de
Omgevingsregeling (de ministeriële regeling bij de Omgevingswet) als zodanig
zijn aangewezen

[^2]: Deze regels zijn vastgelegd in de Regeling standaarden publicaties
Omgevingswet, een ministeriële regeling bij de Bekendmakingswet

#### Juridische verplichtingen voor de bekendmaking

Door de hiervoor genoemde bepalingen geldt een aantal verplichtingen voor het
publiceren van ontwerpen en het juridisch rechtsgeldig bekendmaken van
besluiten. Een besluit tot vaststelling of wijziging van de omgevingsvisie moet
worden vormgegeven overeenkomstig de in paragraaf 4.3 voorgeschreven en op de
omgevingsvisie toegespitste STOP-modellen voor Besluit en Regeling. De tekst in
het Lichaam van de Regeling moet worden gestructureerd overeenkomstig de in
paragraaf 5.2 voorgeschreven specificaties van de Vrijetekststructuur. Van de
tekst kan worden vastgelegd op welke Locatie of Locaties deze van toepassing is.
Bij elkaar horende collecties van Locaties moeten worden vastgesteld in de vorm
van een GIO, waarmee de identiteit en onveranderlijkheid van de geometrie wordt
geborgd. De GIO’s moeten bij het besluit over de regeling worden gevoegd. Als er
een Locatie bij de tekst hoort, moet met een tekstuele aanduiding een verwijzing
naar het GIO gemaakt worden (zie Figuur 14 voor een illustratie). Door deze
verwijzing in de tekst krijgt het GIO juridische status.

#### Annotaties voor de dienstverlening in DSO-LV

Belangrijke resultaten van het annoteren met OW-objecten zijn het herkenbaar op
de kaart weergegeven van de werkingsgebieden van (beleids)tekst en het mogelijk
maken van selecteren en filteren. Annoteren met OW-objecten verhoogt het niveau
van dienstverlening in het Omgevingsloket van DSO-LV. Er is niet wettelijk
bepaald dat en in welke mate geannoteerd moet worden, wel dat daarbij IMOW en
het betreffende toepassingsprofiel moeten worden toegepast. Om het afgesproken
dienstverleningsniveau van DSO-LV te bereiken is het annoteren wel noodzakelijk.

Om het omgevingsdocument met alles wat daar bij hoort in DSO-LV te kunnen tonen,
is het verplicht om, eenmalig per omgevingsdocument, het Regelingsgebied aan te
leveren.

Het annoteren met de overige OW-objecten is alleen mogelijk als die tekst is
geannoteerd met Divisie respectievelijk Divisietekst en Tekstdeel. Door een
Tekstdeel aan een of meer Locaties te koppelen, wordt inzichtelijk waar het
tekstonderdeel van toepassing is. Dat is bij omgevingsdocumenten met
Vrijetekststructuur echter niet verplicht. Als gebruik gemaakt wordt van
Locaties moeten ze voldoen aan de specificaties voor Locatie. Het niet of zeer
beperkt gebruik maken van Locaties geeft een heel beperkt kaartbeeld en zorgt er
voor dat niet inzichtelijk is waar het bevoegd gezag heeft bedoeld dat een
bepaalde (beleids)tekst van toepassing is.

Het aanwijzen van specifieke gebieden in omgevingsdocumenten met
Vrijetekststructuur gebeurt door het annoteren met een van de typen
Gebiedsaanwijzing. Dat zorgt er voor dat die gebieden herkenbaar op de kaart
worden weergegeven en dat er kan worden gefilterd op alle teksten die over een
bepaald type gebied gaan. De annotatie met Gebiedsaanwijzing kan tevens worden
gebruikt om de relatie met een ander omgevingsdocument te versterken, wanneer
daarin dezelfde Gebiedsaanwijzing voor dezelfde Locatie is geannoteerd.

Het attribuut thema zal voor omgevingsdocumenten met Vrijetekststructuur een
belangrijke rol spelen. Daarmee kan worden aangegeven over welk aspect van de
fysieke leefomgeving de tekst gaat. Ook met thema kan de relatie met een ander
omgevingsdocument worden versterkt, als daarin hetzelfde thema is geannoteerd.

Het object Hoofdlijn tenslotte kan worden gebruikt om de informatie inzichtelijk
gestructureerd aan eindgebruikers aan te bieden en een extra filtermogelijkheid
te bieden waardoor bij elkaar horende onderdelen in samenhang getoond kunnen
worden.
