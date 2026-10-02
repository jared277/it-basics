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