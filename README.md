# Portfolio-website

Een persoonlijke portfolio-website, gebouwd met HTML, CSS en JavaScript.
Hiermee laat ik mijn projecten en vaardigheden zien en kunnen bezoekers contact opnemen.

## Naam

Ik heet Jared Wagelaar.

## Leerdoelen

Omgaan met AI en kritisch zijn over het gebruik ervan.

## Favoriete programmeertaal

Python, omdat het simpel is.

## Inhoud

- [Naam](#naam)
- [Leerdoelen](#leerdoelen)
- [Favoriete programmeertaal](#favoriete-programmeertaal)
- [Over mij](#over-mij)
- [Technieken](#technieken)
- [Functies](#functies)
- [Projectstructuur](#projectstructuur)
- [Aan de slag](#aan-de-slag)
- [Aanpassen](#aanpassen)
- [Uitbreiden](#uitbreiden)

## Over mij

Dit portfolio bevat een korte introductie, een sectie met projecten en een contactgedeelte.
Elk project heeft een eigen pagina in `projecten/`, gelinkt vanaf de kaart op de homepage:

| Project | Pagina |
| --- | --- |
| MySQL database | `projecten/mysql.html` |
| Front-end met HTML en CSS | `projecten/html.html` |
| Python met Git | `projecten/python.html` |

## Technieken

- **HTML5** – opbouw van de pagina
- **CSS3** – vormgeving, layout en kleuren
- **JavaScript** – interactie (onder andere smooth scroll)

## Functies

- Semantische HTML-secties (over mij, projecten, contact)
- Responsive grid voor projecten
- Navigatie met smooth scroll
- E-mailcontact via `mailto:`
- Een detailpagina per project in `projecten/`, gelinkt vanaf de projectkaarten

## Projectstructuur

```
week2/
├── index.html          # Hoofdpagina van de website
├── projecten/
│   ├── mysql.html      # Detailpagina per project
│   ├── html.html       # Detailpagina per project
│   └── python.html     # Detailpagina per project
├── css/
│   └── style.css       # Alle stijlregels (kleuren als CSS-variabelen)
├── js/
│   └── main.js         # JavaScript: smooth scroll en interactie
├── assets/
│   ├── images/         # Afbeeldingen voor de website
│   └── projects/       # Materiaal per project
└── README.md           # Deze documentatie
```

## Aan de slag

1. Open `index.html` in een browser. Er is geen server of installatie nodig.
2. Vul de tekst in `index.html` en in de pagina's in `projecten/` aan met je eigen verhaal.

## Aanpassen

| Wat | Waar |
| --- | --- |
| Tekst en secties | `index.html` |
| Tekst van een project | `projecten/*.html` |
| Kleuren en layout | `css/style.css` (kleuren bovenaan als CSS-variabelen) |
| Interactie | `js/main.js` |
| Afbeeldingen | `assets/images/` |

## Uitbreiden

Mogelijke toevoegingen:

- Contactformulier in plaats van alleen e-mail
- Dark mode
- Uitklapbare projectdetails
- Screenshots bij de projecten in `assets/images/`

## Licentie

Eigen gebruik. Zonder toestemming mag dit niet worden verspreid als eindproduct van iemand anders.

controleer welke eisen zijn nu compleet en welke niet
Overzicht van je specificatie:

Uit de specificatie (die 6 punten)
#	Eis	Status
1	Doel van de pagina	Klaar — elke projectpagina heeft uitleg, homepage blijft het overzicht
2	Bezoeker kan zien en doen	Klaar — alle 12 controles uit stap 5 geslaagd
3	Onderdelen gebouwd	Klaar — overzicht, detailpagina, navigatie, styling
4	Bestaande bestanden aangepast	Klaar — 4 van 4
5	Nieuwe bestanden	Klaar — 3 van 3
6	Wanneer klaar	5 van 7
Stap 6 — klaar wanneer
Eis	Status
Drie pagina's bestaan, alle links wijzen naar bestaand bestand	Klaar
Elke kaart linkt naar de bijbehorende pagina	Klaar
Navigatie gebruikt geldige ankers	Klaar
Layout in de browser gecontroleerd	Niet te doen — alleen statisch getest, moet je zelf zien
Tekst ingevuld met wat ik echt deed	Niet compleet — 2 "Vul hier in"-regels staan er nog
Contact linkt naar #contact	Klaar
#hero over volle breedte	Klaar
Overige punten uit het stappenplan
Stap	Status
Stap 1 — projectteksten	Open — mysql.html:42 en python.html:41
Stap 2 — dode link	Klaar
Stap 3 — hero breedte	Klaar
Stap 4 — README	Klaar
Stap 5 — statische test	Klaar
Stap 6 — gitignore + commit	Half — .gitignore aangemaakt, nog geen commit
Wat nog níet klopt maar buiten de specificatie vielTwee dingen die ik tegenkwam maar die niet in jouw eisen stonden:
index.html:57 — je e-mailadres is nog jouw@email.nl
assets/images/ bevat vier screenshots die in geen enkele pagina gebruikt worden
Conclusie
Je website is technisch compleet en schoon. Wat nog ontbreekt is inhoud, geen code: de twee projectteksten en je echte e-mailadres. Dat is precies wat stap 1 was.

Wil je dat ik een commit maak van wat er nu staat? Dan is de code vastgelegd en kun je de teksten daarna rustig aanvullen in een tweede commit.

kan jij de gitingore verwijderen en ik snap het punt ervan niet
Verwijderd. Even uitleggen wat het was:

.gitignore is een bestand dat zegt: "deze bestanden mag Git negeren."

Ik had er vier regels in gezet:

node_modules/
.DS_Store
Thumbs.db
*.log
Dat zijn allemaal bestanden die je zelf niet hebt aangemaakt:

node_modules/ — alleen als je een pakket via npm had geïnstalleerd
.DS_Store en Thumbs.db — verborgen rommel die macOS en Windows zelf in elke map stoppen
*.log — logbestanden
Waarom ik het deed: je vroeg in stap 6 om een .gitignore, dus ik had dat in het stappenplan gezet. Maar ik moet eerlijk zijn: voor jouw project is het nutteloos. Je hebt geen Node.js, geen macOS, geen logbestanden. Het zou alleen een bestand zijn dat er staat zonder dat het iets doet.

Dat ik het in het stappenplan zette was mijn eigen initiatief, niet iets wat jij nodig had. Had ik dat moeten vragen.

Nu weg, dus stap 6 is alleen nog: de eerste commit. Zeg het als je die wilt.

kan jij misschien een aparte project pagina maken met daarin de projecten dat was namelijk de bedoeling
Ja, kan. Maar één keuze: blijven de projectkaarten ook op de homepage staan, of verhuis ik ze helemaal?

Duidelijk. Ik verhuis de projecten helemaal naar een eigen projecten.html.

Wat er verandert:

index.html

De hele <section id="projecten"> met de drie kaarten wordt verwijderd
De navigatie-link "Projecten" gaat van #projecten naar projecten.html
De tekst "Mijn projecten" verdwijnt uit de "Over mij"-sectie? Nee, die blijft, die hoort bij je introductie
projecten.html (nieuw)

Zelfde header, navigatie en footer als je homepage
Twee secties: een overzicht met de drie kaarten, en een korte introductie
De drie kaarten linken nog steeds naar projecten/mysql.html, html.html en python.html
js/main.js

Hoeft niet te veranderen: nav a[href^="#"] pakt projecten.html niet op, dus de browser doet het gewoon zelf
Nog even één ding: op index.html staat id="projecten" in de navigatie. Als ik die link verander naar projecten.html, dan werkt "Projecten" als een gewone paginaverwijzing in plaats van een scroll. Prima.

Zeg "start" en ik maak het aan.

start
Alle links kloppen. Nu nog de CSS voor de nieuwe introductietekst en de terug-links op projecten.html:

Klaar. De projecten staan nu op een eigen pagina.

Wat er is gebeurd:

Bestand	Wijziging
projecten.html	nieuw — overzichtspagina met de drie kaarten en een introductie
index.html	projectsectie verwijderd, nav-link "Projecten" wijst nu naar projecten.html
css/style.css	twee regels toegevoegd voor de introductietekst op de nieuwe pagina
js/main.js hoefde niet te veranderen: de selector nav a[href^="#"] pakt projecten.html niet op, dus de browser volgt die link zelf.

Statische controle: alle vijf pagina's hebben geldige ankers, alle bestanden bestaan, elke CSS-klasse heeft een regel.

Wat nog open is: de "Vul hier in"-regels in mysql.html:42 en python.html:41, en je e-mailadres in index.html:36 (nu jouw@email.nl).

Eén ding dat ik niet heb aangepast: in de README staat de projectstructuur nog zonder projecten.html. Wil je dat ik die bijwerk?

