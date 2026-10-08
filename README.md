# Angelica Ekman – Portfolio

## Beskrivning och målgrupp

En responsiv portfolio för Angelica Ekman, blivande webb- och apputvecklare. Webbplatsen riktar sig till personer som vill se exempel på arbete och komma i kontakt. Projektkorten länkar till projekt på GitHub.

## Kravchecklista

- [x] Tre HTML-sidor: startsida, projekt och kontakt.
- [x] Semantiska element: `header`, `nav`, `main`, `section`, `article` och `footer`.
- [x] Flexbox på startsidans hero och kontaktlayout/formulär.
- [x] CSS Grid för projektkorten.
- [x] Mobil-först CSS med brytpunkter vid 480 px och 768 px.
- [x] Responsiv bild med beskrivande alt-text, rubrikhierarki och läsbart radavstånd.
- [x] Formulär med etiketter, obligatoriska fält och e-postfält.
- [x] Beskrivande navigationslänkar och tangentbordsfokusmarkering.
- [x] Alla sex projektkort länkar till respektive GitHub-repository och har hover- och fokusmarkering.
- [x] CSS-filer ligger i `/styles` och bildresursen i `/assets`.
- [x] Validera alla HTML-filer på [W3C HTML Validator](https://validator.w3.org/) och CSS-filer på [W3C CSS Validator](https://jigsaw.w3.org/css-validator/): 0 fel.
- [x] Publicera via Netlify

## Köra lokalt

Öppna `index.html` i en webbläsare. Alternativt kan projektmappen startas med en lokal statisk webbserver och öppnas via dess lokala adress. Webbplatsen kräver ingen byggprocess.

## Kända brister / att göra

- Kontaktformuläret använder `mailto:` och öppnar besökarens e-postprogram. För faktisk formulärhantering behöver det kopplas till en formulärtjänst eller server.
