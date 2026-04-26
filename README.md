# Pavan Chakravarthi — Portfolio

A minimal, modern, single‑page portfolio for **Pavan Chakravarthi** — Graphic & UI/UX Designer.

## Stack

- Plain HTML, CSS and a tiny vanilla JS file — no build step.
- Inter + Instrument Serif (Google Fonts).
- Light / dark theme with `prefers-color-scheme` and a manual toggle (persisted in `localStorage`).
- Subtle reveal‑on‑scroll animations using `IntersectionObserver`.
- Fully responsive, accessible (skip link, semantic landmarks, reduced‑motion support).

## Run locally

Just open `index.html` in a browser, or serve the directory:

```bash
python3 -m http.server 5173
# then visit http://localhost:5173
```

## Structure

```
.
├── index.html   # Page markup (Hero, About, Experience, Skills, Education, Contact)
├── styles.css   # Design tokens + components
└── script.js    # Theme toggle, sticky nav, reveal-on-scroll
```

## Content

All content (roles, dates, skills, education, contact details) is sourced directly from
Pavan's CV.
