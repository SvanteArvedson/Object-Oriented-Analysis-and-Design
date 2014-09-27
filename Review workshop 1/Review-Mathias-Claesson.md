#Review Mathias Claesson
Review av diagrammet: [https://drive.google.com/file/d/0ByhfBb1L7qlZeHE4RnlEZVc1dk0/edit?usp=sharing](https://drive.google.com/file/d/0ByhfBb1L7qlZeHE4RnlEZVc1dk0/edit?usp=sharing "till diagrammet")

Review gjord av Svante Arvedson (ba222ec).

##Positiv feedback
<dl>
    <dt>Speglar verkligheten</dt>
    <dd>Diagrammet speglar i och beskriver b�tklubbens verksamhet utan 
        att blanda in mjukvarurelaterade objekt. Bra val av objekt.</dd>
    <dt>F�ljer scopet f�r betyg 3</dt>
    <dd>Diagrammet f�ljer scopet f�r betyg 3 p� ett bra s�tt. Inget 
        on�digt inneh�ll f�r att beskriva anv�ndningsfallen 
        f�r betyg 3.</dd>
    <dt>Namngivning</dt>
    <dd>Bra namngivning av objekten och associationer g�r det l�tt att 
        koppla diagrammet till kraven.</dd>
    <dt>Bra UML-notation</dt>
    <dd>Diagrammet f�ljer syntax f�r UML-notation.</dd>
    <dt>V�lstrukturerat diagram</dt>
    <dd>Placeringen av objekten g�r diagrammet l�tt�versk�dligt och 
        l�tt att l�sa.</dd>
</dl>

##Negativ feedback
<dl>
    <dt>Vissa ttribut saknas</dt>
    <dd>P� vissa av objekten saknas viktiga attribut. Exempelvis s� 
        n�mner kraven attribut p� objekten <i>Medlem</i> och 
        <i>B�t</i> men dessa attribut saknas i diagrammet.</dd>
    <dt>Saknas tolkning av UC8 - Boka b�tplatser</dt>
    <dd>Enligt UC8 s� �r det sekreteraren som bokar b�tplatser, 
        detta g�r en att utl�sa av diagrammet. Det �r sv�rt att se i 
        diagrammet hur historiken �ver placeringar av b�tar kan 
        genereras.</dd>
    <dt>Saknas tolkning av UC10-12 - Hantering av kalender och kalenderh�ndelser</dt>
    <dd>I kraven UC10, UC11 och UC12 s� har b�de sekreterare och 
        medlemmar associationer till objekten Kalender och Kalenderh�ndelse, 
        men detta kan man inte utl�sa av diagrammet.</dd>
    <dt>Gjorda antagande skulle beh�va noteras</dt>
    <dd>Diagrammets f�rfattare har gjort antaganden om dom�nen som inte �r 
        noterade i kraven, ex att den som registrera en b�t ocks� m�ste vara 
        �gare av b�ten samt att samtliga medlemmar m�ste �ga minst en b�t. 
        Antaganden av denna typen skulle kanske kunna noteras i fritext bredvid 
        diagrammet.</dd>
    <dt>Vissa namngivningar �r sv�ra att tolka</dt>
    <dd>Vissa av namngivningarna �r sv�ra att f�rst�, exempelvis 
        [Kalenderh�ndelse]Registrerar[Tidsintervall]</dd>
</dl>

##F�rslag p� �ndringar
<dl>
    <dt>L�s genom UC8, UC10, UC11 och UC12 igen</dt>
    <dd>L�s genom kraven igen och komplettera diagrammet med associationer 
        och attribut.</dd>
    <dt>Skriv ner antaganden</dt>
    <dd>Skriv ner de antaganden som ligger till grund f�r tolkningen av 
        kraven. D� blir det l�ttare att f�rst� varf�r diagrammet ser ut 
        som det g�r.</dd>
    <dt>Kolla genom namnengivningen</dt>
    <dd>Kolla genom namngivningen en g�ng till och se s� att namnen 
        blir till l�ttolkade meningar.</dd>
</dl>

##Summering
Om komplettering enligt f�rslagen ovan g�rs s� kommer b�de utvecklare och 
dom�nexperter att ha l�tt f�r att l�sa och f�rst� diagrammet. Efter komplettering 
s� kommer utvecklaren ocks� med l�tthet att kunna anv�nda diagrammet som 
inspiration till en mjukvarudesign.   
Om ovanst�ende kompletteringar g�rs s� anser jag att diagrammet utan vidare 
kommer att klara kraven f�r betg 3.