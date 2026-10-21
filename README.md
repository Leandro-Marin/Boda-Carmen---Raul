# Boda Carmen & Raúl 💍

Wedding website for Carmen & Raúl (16 May 2026) — concept, visual design and front-end by **Leandro Marin**.

🔗 **Live:** [bodacarmenyraul.click](https://bodacarmenyraul.click)

## About the project

A single-page invitation that replaces the paper card: guests "open" the invitation by breaking a wax seal and find everything they need for the day in one place — schedule, locations, transport and RSVP.

## Features

- **Envelope intro** – the page stays locked until the guest clicks the wax seal, then the soundtrack starts.
- **Background music** with a play/mute toggle.
- **Live countdown** to the ceremony.
- **Day timeline** – ceremony, bus, aperitivo, banquet, party and return bus.
- **Directions** – Google Maps links to the church and the venue.
- **RSVP form** – attendance, bus service and dietary needs (gluten, lactose, vegetarian, vegan), sent straight to a Google Sheet via Google Apps Script.
- **FAQ accordion** and scroll-reveal animations.
- Responsive layout, custom illustrated SVG assets and WebP photos.

## Tech stack

| | |
|---|---|
| Markup & styles | HTML5, CSS3 (no frameworks) |
| Interactivity | Vanilla JavaScript |
| Fonts | Big Shoulders, Instrument Serif (Google Fonts) |
| Form backend | Google Apps Script → Google Sheets |
| Hosting | GitHub Pages + custom domain |

## Project structure

```
├── index.html      # page markup + inline JS
├── style/
│   └── style.css   # all styles
├── src/            # SVG illustrations, WebP photos, audio
└── CNAME           # custom domain
```

## Run locally

No build step needed:

```bash
git clone https://github.com/Leandro-Marin/Boda-Carmen---Raul.git
cd Boda-Carmen---Raul
open index.html   # or serve with any static server
```

---

Designed & developed by [Leandro Marin](https://leandro-marin.github.io/portfolio-2025/) · Visual + UX/UI Designer, Rome
