# AI & Privacybeleid — Précon

Eén-pagina interne microsite die samenvat hoe Précon omgaat met AI-tools: de
kansen en risico's, het verschil tussen Copilot Chat ("Basic") en Microsoft
365 Copilot ("Premium"), welke informatie wel/niet gedeeld mag worden met
AI-tools, en welke stappen je moet nemen als je toch met gevoelige data wilt
werken (verwijderen, anonimiseren, correct redigeren in plaats van alleen
een laag overheen plakken).

Gebaseerd op het interne conceptdocument `AI intern beleid Précon 2026 DRAFT.docx`.
Dit is geen juridisch eindoordeel — bij twijfel over een specifiek geval altijd
Compliance/IT raadplegen.

## Lokaal bekijken

Geen build-stap nodig, het is een statische pagina:

```bash
open index.html
```

of serveer de map met een simpele webserver:

```bash
python3 -m http.server 8000
```

## Structuur

- `index.html` — inhoud en opbouw van de pagina
- `styles.css` — Précon-huisstijl (navy/oranje, Overpass + Libre Baskerville)
- `app.js` — scroll-navigatie (highlight van het actieve onderdeel in de menubalk)
