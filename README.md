# Portfolio-website

Een persoonlijke portfolio-website, gebouwd met HTML, CSS en JavaScript.
Hiermee laat ik mijn projecten en vaardigheden zien en kunnen bezoekers contact opnemen.

## naam
 
 ik heet Jared Wagelaar.

 ## leerdoelen

 omgaan met ai en kritish zijn over het gebruik ervan

 ## Mijn favoriete programmeertaal is pyhthon omdat het simpel is


## Inhoud

- [Over mij](#over-mij)
- [Technieken](#technieken)
- [Functies](#functies)
- [Projectstructuur](#projectstructuur)
- [Aan de slag](#aan-de-slag)
- [Aanpassen](#aanpassen)
- [Uitbreiden](#uitbreiden)

## Over mij

Dit portfolio bevat een korte introductie, een sectie met projecten en een contactgedeelte.
Vul in `index.html` je eigen naam, tekst en projecten in.

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
2. Vervang alle plekholders (`[Jouw Naam]`, projectbeschrijvingen, e-mailadres) door eigen tekst.

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

- Projectpagina's met screenshots
- Contactformulier in plaats van alleen e-mail
- Dark mode
- Uitklapbare projectdetails

## Licentie

Eigen gebruik. Zonder toestemming mag dit niet worden verspreid als eindproduct van iemand anders.