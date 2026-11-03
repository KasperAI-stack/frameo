# Kasper til Frameo

En personlig landingpage til ansøgningen som Performance & Marketing Automation Manager hos Frameo i Aarhus (rekrutteringen sker via Kold+Partners). Siden er bygget på koden fra ed-siden (repoet ed, som bygger på Understory, Cozze, Maki og hey-kasper.dk) med ny tekst, Frameos farver og Frameos logo.

## Mappen

- site/: selve hjemmesiden. Det er kun denne mappe, der kommer online.
  - index.html: forsiden med al teksten
  - cv.html og ansoegning.html: CV'et og ansøgningen bygget op som PDF'erne i assets/pdf/. Ret teksten begge steder.
  - css/dokument.css: designet til CV og ansøgning (Figtree, farverne aflæst fra PDF'erne)
  - en/: de engelske udgaver (index.html, cv.html og application.html). Sprogvælgeren DA/EN i toppen skifter mellem dem.
  - 404.html: siden, der vises, hvis adressen er forkert
  - css/styles.css: farver og design. Frameos farver (rød #FF2637 og mørkeblå #2A2B45) står øverst under `:root`.
  - js/main.js: små forbedringer, fx agentvælgeren i toppen og temaknappen
  - assets/frameo-logo.svg og frameo-logo-hvid.svg: Frameos logo, ryddet op fra frameo.com, i rødt og i hvidt til footeren
  - assets/dokument/: billederne fra PDF'erne (memoji-toppen, foto, firmalogoer, Frameos runde logo og skærmbilleder fra HeyOtto Studio)
  - assets/og-image.jpg og og-image-en.jpg: billedet, der vises, når linket deles på LinkedIn eller i en mail
- netlify.toml: fortæller Netlify, at site/ skal publiceres.

## Linket

Siden ligger på GitHub Pages: https://kasperai-stack.github.io/frameo/ (engelsk: https://kasperai-stack.github.io/frameo/en/)

Den bliver opdateret automatisk, hver gang der pushes til main (se .github/workflows/pages.yml).

## Se siden på din egen computer

1. Åbn en terminal i mappen.
2. Skriv `npx serve site` og åbn adressen, der vises i terminalen.

## Godt at vide

- Siden skal ikke kunne findes på Google. Den har `noindex` i HTML'en, i netlify.toml og i robots.txt.
- Der er ingen Google Tag Manager, cookies eller formular på siden. Kontakt sker via "Kald til samtale" (mail til kasmussen80@gmail.com) og telefon.
- Teksten følger Kaspers stemme: "I" og "jer" til Frameo, ingen tankestreger og ingen opdigtede tal. Fakta kommer fra jobopslaget, frameo.com og Kaspers CV og ansøgning.
