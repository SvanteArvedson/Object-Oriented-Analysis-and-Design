#Review Henrik Garbrielsson
Review av diagrammet: [http://homepage.lnu.se/student/hg222aa/uml/workshop1.html](http://homepage.lnu.se/student/hg222aa/uml/workshop1.html "till diagrammet")

Review gjord av Svante Arvedson (ba222ec).

##Positiv feedback
<dl>
    <dt>Speglar verkligheten</dt>
    <dd>Diagrammet speglar i stort s�tt verkligheten och b�tklubbens 
        verksamhet. De flesta objekten �r inte mjukvarurelaterade</dd>
    <dt>F�ljer scopet f�r betyg 3</dt>
    <dd>Diagrammet f�ljer scopet f�r betyg 3 p� ett bra s�tt. 
        I princip inget on�digt inneh�ll f�r att beskriva anv�ndningsfallen 
        f�r betyg 3.</dd>
    <dt>Namngivning</dt>
    <dd>Bra namngivning av objekten g�r det l�tt att koppla diagrammet 
        till kraven.</dd>
</dl>

##Negativ feedback
<dl>
    <dt>Mjukvarurelaterade objekt</dt>
    <dd>Objektet <i>Login</i> k�nns kopplat till mjukvara snarare �n 
        till b�tklubbens verksamhet. I kraven f�r mjukvaran ska en 
        anv�ndare kunna logga in, men i vilken del av b�tklubbens 
        praktiska verksamhet ska man logga in?</dd>
    <dt>Objekten saknar attriut</dt>
    <dd>Samtliga objekt i diagrammet saknar attribut. Till viss del 
        har ni f�rs�kt ge objekten egenskaper genom att koppla dem 
        till andra objekt, exempelvis [B�t]->[Djup], men det �r 
        inte tanken att UML-objekt ska anv�ndas p� det s�ttet.</dd>
    <dt>Associationerna saknar namn</dt>
    <dd>Samtliga associationer i diagrammet saknar namn. Namn p� 
        associationerna �r n�dv�ndigt f�r att digrammet ska bli 
        komplett och l�tt att f�rst�. Nu kr�vs det av l�saren att 
        hen sj�lv har l�st kraven f�r att hen ska f�rst� vad 
        associationerna ber�ttar. �ven l�sriktningen b�r markeras 
        ut i vissa fall, d� standardriktingen inte alltid fungerar.</dd>
    <dt>Ingen association till Kalender eller Kalenderh�ndelse</dt>
    <dd>Det finns ingen association till objekten Kalender och 
        Kalenderh�ndelse. Detta skapar en felaktig bild av b�tklubbens 
        verksamhet och speglar inte kraven. Enligt diagrammet s� 
        anv�nder b�tklubben inte n�gon kalender �verhuvudtaget.</dd>
</dl>

##F�rslag p� �ndringar
<dl>
    <dt>L�gg till attribut</dt>
    <dd>Byt ut en del av klasserna till attribut ist�llet. Unders�k 
        kraven f�r att hitta relevanta attribut.</dd>
    <dt>Namnge associationerna</dt>
    <dd>Ge alla associationerna taande namn och en l�srikting s� 
        att det klart framg�r vad associationerna ber�ttar om dom�nen.</dd>
    <dt>Ta bort mjukvarurelaterade objekt</dt>
    <dd>Objektet <i>Login</i> �r kopplat till en mjukvara. Jag f�resl�r 
        d�rf�r att ni tar bort det objketet. Fundera ocks� p� om objektet 
        <i>Bokning</i> skulle kunna d�pas till n�got annat som p� ett 
        tydligare s�tt upplyser om objektets ansvar.</dd>
</dl>

##Summering
Som utvecklare k�nner jag att jag kan f�rst� diagrammet, efter att jag har 
satt mig in i kraven. Utan f�rf�rst�else hade jag haft sv�rt att tolka diagrammet. 
Jag tror att en dom�nexpert skulle kunna f�rst� om hen fick hj�lp och f�rklaringar, 
men frist�ende s� skulle diagrammet vara sv�rt att f�rst�.    
Om attribut och namn p� assosiationerna l�gg till s� skulle jag bed�mma diagrammet 
som godk�nt enligt kraven f�r betyg 3, men som det ser ut just nu s� r�cker det 
inte.