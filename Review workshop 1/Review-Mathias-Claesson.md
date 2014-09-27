#Review Mathias Claesson
Review av diagrammet: [https://drive.google.com/file/d/0ByhfBb1L7qlZeHE4RnlEZVc1dk0/edit?usp=sharing](https://drive.google.com/file/d/0ByhfBb1L7qlZeHE4RnlEZVc1dk0/edit?usp=sharing "till diagrammet")

Review gjord av Svante Arvedson (ba222ec).

##Positiv feedback
<dl>
    <dt>Speglar verkligheten</dt>
    <dd>Diagrammet speglar i och beskriver båtklubbens verksamhet utan 
        att blanda in mjukvarurelaterade objekt. Bra val av objekt.</dd>
    <dt>Följer scopet för betyg 3</dt>
    <dd>Diagrammet följer scopet för betyg 3 på ett bra sätt. Inget 
        onödigt innehåll för att beskriva användningsfallen 
        för betyg 3.</dd>
    <dt>Namngivning</dt>
    <dd>Bra namngivning av objekten och associationer gör det lätt att 
        koppla diagrammet till kraven.</dd>
    <dt>Bra UML-notation</dt>
    <dd>Diagrammet följer syntax för UML-notation.</dd>
    <dt>Välstrukturerat diagram</dt>
    <dd>Placeringen av objekten gör diagrammet lättöverskådligt och 
        lätt att läsa.</dd>
</dl>

##Negativ feedback
<dl>
    <dt>Vissa ttribut saknas</dt>
    <dd>På vissa av objekten saknas viktiga attribut. Exempelvis så 
        nämner kraven attribut på objekten <i>Medlem</i> och 
        <i>Båt</i> men dessa attribut saknas i diagrammet.</dd>
    <dt>Saknas tolkning av UC8 - Boka båtplatser</dt>
    <dd>Enligt UC8 så är det sekreteraren som bokar båtplatser, 
        detta går en att utläsa av diagrammet. Det är svårt att se i 
        diagrammet hur historiken över placeringar av båtar kan 
        genereras.</dd>
    <dt>Saknas tolkning av UC10-12 - Hantering av kalender och kalenderhändelser</dt>
    <dd>I kraven UC10, UC11 och UC12 så har både sekreterare och 
        medlemmar associationer till objekten Kalender och Kalenderhändelse, 
        men detta kan man inte utläsa av diagrammet.</dd>
    <dt>Gjorda antagande skulle behöva noteras</dt>
    <dd>Diagrammets författare har gjort antaganden om domänen som inte är 
        noterade i kraven, ex att den som registrera en båt också måste vara 
        ägare av båten samt att samtliga medlemmar måste äga minst en båt. 
        Antaganden av denna typen skulle kanske kunna noteras i fritext bredvid 
        diagrammet.</dd>
    <dt>Vissa namngivningar är svåra att tolka</dt>
    <dd>Vissa av namngivningarna är svåra att förstå, exempelvis 
        [Kalenderhändelse]Registrerar[Tidsintervall]</dd>
</dl>

##Förslag på ändringar
<dl>
    <dt>Läs genom UC8, UC10, UC11 och UC12 igen</dt>
    <dd>Läs genom kraven igen och komplettera diagrammet med associationer 
        och attribut.</dd>
    <dt>Skriv ner antaganden</dt>
    <dd>Skriv ner de antaganden som ligger till grund för tolkningen av 
        kraven. Då blir det lättare att förstå varför diagrammet ser ut 
        som det gör.</dd>
    <dt>Kolla genom namnengivningen</dt>
    <dd>Kolla genom namngivningen en gång till och se så att namnen 
        blir till lättolkade meningar.</dd>
</dl>

##Summering
Om komplettering enligt förslagen ovan görs så kommer både utvecklare och 
domänexperter att ha lätt för att läsa och förstå diagrammet. Efter komplettering 
så kommer utvecklaren också med lätthet att kunna använda diagrammet som 
inspiration till en mjukvarudesign.   
Om ovanstående kompletteringar görs så anser jag att diagrammet utan vidare 
kommer att klara kraven för betg 3.