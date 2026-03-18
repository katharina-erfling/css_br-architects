<img width="1888" height="894" alt="Screenshot 2026-03-18 182246" src="https://github.com/user-attachments/assets/a03c9f6b-d25a-4d26-af7d-f0f762f0e891" />

# BR Architects – Portfolio-Website

Eine responsive Architektur-Portfolio-Website, erstellt mit Bootstrap 5 und SCSS.

---

## Technologien

- **HTML5**
- **Bootstrap 5** (lokal eingebunden)
- **SCSS** (kompiliert via Partials)
- **SVG-Icons** (inline, keine externen Abhängigkeiten)
- **JavaScript** (vanilla, Intersection Observer für Scroll-Animationen)
- **Schrift** – Be Vietnam Pro (selbst gehostet, DSGVO-konform)

---

## Features

- Responsives Layout (Mobile, Tablet, Desktop)
- Sticky Navigation mit Schatten beim Scrollen
- Vollbreites Hero-Bild
- Projekt-Bildergrid mit Hover-Zoom-Effekt
- Team-Bereich mit Kontakt-Buttons
- Kontaktformular im minimalistischen Unterstrich-Stil
- Scroll-Einblend-Animationen
- Selbst gehostete Schriften (kein Google Fonts, DSGVO-konform)
- SVG Social-Icons im Footer (keine Icon-Bibliothek nötig)

---

## Projektstruktur

```
/
├── index.html
├── img/
│   ├── architect.jpg
│   ├── house2.jpg
│   ├── house3.jpg
│   ├── house4.jpg
│   ├── house5.jpg
│   ├── team1.jpg – team4.jpg
│   └── map.jpg
├── css/
│   └── main.css            (aus SCSS kompiliert)
├── scss/
│   ├── main.scss           (Master-Datei)
│   ├── _font.scss
│   ├── _set-styles.scss
│   └── _project-styles.scss
├── webfonts/
│   └── BeVietnamPro-*.woff2
└── bootstrap/
    ├── css/
    └── js/
```

---

## Responsive Breakpoints

| Breakpoint | Layout |
|---|---|
| < 576px (Mobile) | 1 Spalte |
| ≥ 576px (Tablet) | 2 Spalten |
| ≥ 992px (Desktop) | 4 Spalten |
