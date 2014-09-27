#Review Henrik Garbrielsson
Review av diagrammet: [http://homepage.lnu.se/student/hg222aa/uml/workshop1.html](http://homepage.lnu.se/student/hg222aa/uml/workshop1.html "till diagrammet")

Review gjord av Svante Arvedson (ba222ec).

##Positiv feedback
<dl>
    <dt>Speglar verkligheten</dt>
    <dd>Diagrammet speglar i stort sätt verkligheten och båtklubbens 
        verksamhet. De flesta objekten är inte mjukvarurelaterade</dd>
    <dt>Följer scopet för betyg 3</dt>
    <dd>Diagrammet följer scopet för betyg 3 på ett bra sätt. 
        I princip inget onödigt innehåll för att beskriva användningsfallen 
        för betyg 3.</dd>
    <dt>Namngivning</dt>
    <dd>Bra namngivning av objekten gör det lätt att koppla diagrammet 
        till kraven.</dd>
</dl>

##Negativ feedback
<dl>
    <dt>Mjukvarurelaterade objekt</dt>
    <dd>Objektet <i>Login</i> känns kopplat till mjukvara snarare än 
        till båtklubbens verksamhet. I kraven för mjukvaran ska en 
        användare kunna logga in, men i vilken del av båtklubbens 
        praktiska verksamhet ska man logga in?</dd>
    <dt>Objekten saknar attriut</dt>
    <dd>Samtliga objekt i diagrammet saknar attribut. Till viss del 
        har ni försökt ge objekten egenskaper genom att koppla dem 
        till andra objekt, exempelvis [Båt]->[Djup], men det är 
        inte tanken att UML-objekt ska användas på det sättet.</dd>
    <dt>Associationerna saknar namn</dt>
    <dd>Samtliga associationer i diagrammet saknar namn. Namn på 
        associationerna är nödvändigt för att digrammet ska bli 
        komplett och lätt att förstå. Nu krävs det av läsaren att 
        hen själv har läst kraven för att hen ska förstå vad 
        associationerna berättar. Även läsriktningen bör markeras 
        ut i vissa fall, då standardriktingen inte alltid fungerar.</dd>
    <dt>Ingen association till Kalender eller Kalenderhändelse</dt>
    <dd>Det finns ingen association till objekten Kalender och 
        Kalenderhändelse. Detta skapar en felaktig bild av båtklubbens 
        verksamhet och speglar inte kraven. Enligt diagrammet så 
        använder båtklubben inte någon kalender överhuvudtaget.</dd>
</dl>

##Förslag på ändringar
<dl>
    <dt>Lägg till attribut</dt>
    <dd>Byt ut en del av klasserna till attribut istället. Undersök 
        kraven för att hitta relevanta attribut.</dd>
    <dt>Namnge associationerna</dt>
    <dd>Ge alla associationerna taande namn och en läsrikting så 
        att det klart framgår vad associationerna berättar om domänen.</dd>
    <dt>Ta bort mjukvarurelaterade objekt</dt>
    <dd>Objektet <i>Login</i> är kopplat till en mjukvara. Jag föreslår 
        därför att ni tar bort det objketet. Fundera också på om objektet 
        <i>Bokning</i> skulle kunna döpas till något annat som på ett 
        tydligare sätt upplyser om objektets ansvar.</dd>
</dl>

##Summering
Som utvecklare känner jag att jag kan förstå diagrammet, efter att jag har 
satt mig in i kraven. Utan förförståelse hade jag haft svårt att tolka diagrammet. 
Jag tror att en domänexpert skulle kunna förstå om hen fick hjälp och förklaringar, 
men fristående så skulle diagrammet vara svårt att förstå.    
Om attribut och namn på assosiationerna lägg till så skulle jag bedömma diagrammet 
som godkänt enligt kraven för betyg 3, men som det ser ut just nu så räcker det 
inte.