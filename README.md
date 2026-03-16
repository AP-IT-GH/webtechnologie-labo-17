# Oefeningen labo 17

Zorg dat je de volgende folderstructuur volgt:

```
webtechnologie/
├─ labo-01/
│  ├─ oefening-01/
│  │  ├─ index.html
│  │  ├─ images/
│  │  │  ├─ image-1.jpg 
│  │  │  └─ image-n.jpg 
│  │  ├─ css/
│  │  │   ├─ reset.css
│  │  │   └─ style.css
│  │  ├─ data/
│  │  │   ├─ datafile-1.json
│  │  │   └─ datafile-2.json
│  │  └─ js/
│  │     └─ script.js
│  ├─ oefening-02/
│  └─ oefening-n/
├─ labo-02/
└─ labo-n/      
```

- Gebruik steeds JS modules om globale variabelen te vermijden (`<script type="module" src="./path/to/script.js" defer></script>`)
- Zet je Javascript file steeds in strict mode (`"use strict"`);
- Volg de [Coding Guidelines](https://apwt.gitbook.io/webtechnologie/coding-guidelines)

## oefening 1: tekst plaatsen

### leerdoelen

* een HTML-element selecteren o.b.v. id
* de inhoud van een HTML-element wijzigen

### functionele analyse 

Jouw programma gaat de titel op een website aanpassen naar de inhoud van een variabele.

### technische analyse 

In jouw HTML voorzie je een h1-element met als tekst "Hello world!".

Plaats in jouw code de tekst "Welkom op onze website" in een `const`. Gebruik deze `const` om de `h1` op de website aan te passen.

### voorbeeldinteractie

![voorbeeldinteractie](./voorbeeldinteractie-tekst-plaatsen.avif)

## Oefening 2: Attributen lezen

### leerdoelen

* Een HTML-element selecteren op basis van id
* Attributen van een HTML-element lezen

### functionele analyse 

Lees de waarde van het "src"-attribuut van een afbeelding en toon deze in de console.

### technische analyse

Voeg in jouw HTML een img-element toe met een id, bijvoorbeeld "myImage", en een standaardbron, bijvoorbeeld "afbeelding.png".

In jouw JavaScript-code selecteer je dit img-element op basis van het id "myImage" en lees je de waarde van het "src"-attribuut. Toon deze waarde vervolgens in de console.

### voorbeeldinteractie

![voorbeeldinteractie](./voorbeeldinteractie-attributen-lezen.avif)

## oefening 3: attributen wijzigen

### leerdoelen

* een HTML-element selecteren op basis van tag
* attributen van een HTML-element wijzigen

### functionele analyse 

Je moet de bron van een afbeelding wijzigen op basis van een variabele.

### technische analyse 

In jouw HTML heb je een img-element met een id "myImage" en een standaardbron, bijvoorbeeld "afbeelding.png".

Maak in jouw JavaScript-code een variabele met de naam `newSource` en wijs hieraan een nieuwe afbeeldings-URL toe.

Selecteer het img-element op de pagina op basis van het id "myImage" en wijzig het attribuut "src" naar de waarde van de variabele `newSource`. Zo moet de afbeelding op de website veranderen afhankelijk van de nieuwe bron die je hebt opgegeven.

### voorbeeldinteractie
![voorbeeldinteractie](./voorbeeldinteractie-attributen-wijzigen.avif)

## oefening 4: stijlen aanpassen

### leerdoelen

* een HTML-element selecteren op basis van id
* stijlen van een HTML-element wijzigen

### functionele analyse 

Pas de tekstkleur van een alinea aan op basis van een variabele.

### technische analyse 

Voeg in jouw HTML een paar p-elementen toe met verschillende tekstinhoud en verschillende klasses, bijvoorbeeld `.red`.

Maak een variabele met de naam `red` en wijs hieraan een kleurwaarde toe, bijvoorbeeld "rood".

Selecteer de p-elementen op de pagina op basis van de klasse en pas de tekstkleur aan naar de waarde van de variabele. Hierdoor moeten de paragrafen een nieuwe tekstkleur hebben.

### voorbeeldinteractie

![voorbeeldinteractie](./voorbeeldinteractie-stijl-aanpassen.avif)

## oefening 5: elementen verwijderen

### leerdoelen

* bestaande HTML-elementen verwijderen

### functionele analyse 

Verwijder een item uit een lijst.

### technische analyse 

In jouw HTML, creëer een ongeordende lijst (ul) met enkele lijstitems (li).

Selecteer een bestaand lijstitem (je kunt bijvoorbeeld het eerste lijstitem selecteren) en verwijder dit item uit de lijst.

### voorbeeldinteractie

![voorbeeldinteractie](./voorbeeldinteractie-element-verwijderen.avif)

## oefening 6: tekstinhoud lezen

### leerdoelen

* Een HTML-element selecteren op basis van tag
* De inhoud van een HTML-element lezen

### functionele analyse 

Lees de tekstinhoud van een paragraaf en toon deze in de console.

### technische analyse 

Voeg in jouw HTML een p-element toe met wat tekstinhoud.

In jouw JavaScript-code, selecteer dit p-element op basis van de tag en lees de tekstinhoud ervan. Toon deze tekst vervolgens in de console.

### voorbeeldinteractie

![voorbeeldinteractie](./voorbeeldinteractie-tekstinhoud-lezen.avif)

## oefening 7: stijlen lezen

### leerdoelen

* Een HTML-element selecteren op basis van id
* Stijlinformatie van een HTML-element lezen

### functionele analyse 

Lees de achtergrondkleur van een div-element met een specifieke id en toon deze in de console.

### technische analyse 

Voeg in jouw HTML een div-element toe met een id, bijvoorbeeld `bg-grey`, en pas wat stijlen toe, zoals achtergrondkleur.

In jouw JavaScript-code, selecteer dit div-element op basis van de id en lees de achtergrondkleur. Toon deze kleur vervolgens in de console.

### voorbeeldinteractie

![voorbeeldinteractie](./voorbeeldinteractie-stijlen-lezen.avif)

## oefening 8: elementen toevoegen

### leerdoelen

* Nieuwe HTML-elementen maken
* Bestaande HTML-elementen wijzigen

### functionele analyse 

Voeg een nieuw item toe aan een lijst.

### technische analyse 

In jouw HTML, creëer een ongeordende lijst (ul) met enkele lijstitems (li).

In jouw JavaScript-code, maak een nieuw li-element aan met de tekst "Nieuw Item" en voeg dit toe aan de bestaande ul. Toon het resultaat in de console.

Deze oefening laat zien hoe je dynamisch nieuwe elementen aan een pagina kunt toevoegen.

### voorbeeldinteractie
![voorbeeldinteractie](./voorbeeldinteractie-elementen-toevoegen.avif)

## oefening 9: eerste event afhandelen

### leerdoelen

* kennismaken met een event listener in JavaScript

### functionele analyse

Reageer op een muisklik op een knop door een bericht in de console weer te geven.

### technische analyse

In jouw HTML plaats je een button-element met een id, bijvoorbeeld "myAction" en wat tekst, bijvoorbeeld "Klik op mij".

In jouw JavaScript-code selecteer je deze button op basis van het id en voeg je er een event listener aan toe om te reageren op het "click"-event.

Wanneer de knop wordt geklikt, toon dan "er werd op mij geklikt" in de console.

### voorbeeldinteractie
![voorbeeldinteractie](./voorbeeldinteractie-eerste-event.gif)

## oefening 10: reageren in DOM

### leerdoelen

* kennismaken met een event listener in JavaScript
* DOM-manipulatie naar aanleiding van event

### functionele analyse

Reageer op een muisklik op een knop door een bericht op de website weer te geven.

### technische analyse

In jouw HTML plaats je een button-element met een id, bijvoorbeeld "myAction" en wat tekst, bijvoorbeeld "Klik op mij". Daaronder plaats je een p-element met een id, bijvoorbeeld "myText". Je laat de p nog leeg.

In jouw JavaScript-code selecteer je deze button op basis van het id en voeg je er een event listener aan toe om te reageren op het "click"-event.

Wanneer de knop wordt geklikt, toon dan "er werd op mij geklikt" in de p.

### voorbeeldinteractie

![voorbeeldinteractie](./voorbeeldinteractie-reageren-in-dom.gif)

## oefening 11: reageren op form event

### leerdoelen

* form event gebruiken
* default voorkomen

### functionele analyse

Wanneer een gebruiker het formulier verzendt, toon je de naam van de gebruiker op het scherm.

### technische analyse

Op jouw pagina staat een formulier met daarin 1 veld, nl. "voornaam".

Wanneer de gebruiker het veld heeft ingevuld (tip: required) en het formulier verzendt, zal jouw code voorkomen dat het formulier verzonden wordt.

Je toont de ingevulde naam van de gebruiker op het scherm in een welkomstboodschap.

### voorbeeldinteractie

![voorbeeldinteractie](./voorbeeldinteractie-reageren-form-event.gif)

## oefening 12: reageren op invoer van gebruiker

### leerdoelen

* keyboard event gebruiken

### functionele analyse

Wanneer een gebruiker in een invoerveld typt, toon je de toetsaanslagen van de gebruiker op het scherm.

### technische analyse

Op jouw pagina staat een invoerveld, nl. "input".

Wanneer de gebruiker iets invult, toon je de ingevulde tekst van de gebruiker op het scherm.

### voorbeeldinteractie

![voorbeeldinteractie](./voorbeeldinteractie-reageren-invoer-gebruiker.gif)

## oefening 13: reageren op muisbeweging

### leerdoelen

* mouse event gebruiken

### functionele analyse

Je geeft de positie van de muis weer op het scherm

### technische analyse

Op jouw pagina staat een tekst, nl.: "Jouw muis bevindt zich op x: 150, y: 300".

Telkens de gebruiker zijn muis beweegt, toon je de nieuwe coördinaten in de tekst.

### voorbeeldinteractie

![voorbeeldinteractie](./voorbeeldinteractie-reageren-muisbeweging.gif)

## oefening 14: DOM-element toevoegen door te klikken

### leerdoelen

* DOM manipulatie
* click event

### functionele analyse

Je voegt lijst-items toe door op een knop te drukken.

### technische analyse

Jouw website bestaat uit een h1 "todo-lijst" en een oplijsten van enkele to-do's.

Er staat een knop onderaan de lijst. Als op deze knop geklikt wordt, zal er een to-do-item bijkomen op de lijst.

### voorbeeldinteractie

![voorbeeldinteractie](./voorbeeldinteractie-dom-manipulatie-na-event.gif)
