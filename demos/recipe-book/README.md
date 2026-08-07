# Recipe Book — Rustic Cozy Cookbook

A warm, single-file recipe manager with full CRUD, search, favorites and serving-scaled ingredients, wrapped in a "rustic cozy" wood-and-coffee aesthetic. No dependencies, no build step.

## Features

- **CRUD recipes** — name, prep time, serving count, category (Breakfast / Lunch / Dinner / Dessert / Drinks), description, an addable ingredients list (quantity + name) and ordered steps
- **Card grid** — gradient cover placeholder with category emoji, category pill, name, short description, time / servings / ingredient count
- **Detail view** — Ingredients and Steps tabs; ingredients act as an interactive checklist (check off as you go)
- **Servings slider** — scales every ingredient quantity proportionally to your chosen serving count
- **Search + category filter**, plus a "Favorites only" switch
- **Favorites** — heart toggle on each card, with a favorites counter
- **Persistence** — saves to `localStorage` key `recipe-book-v1` in a `try/catch` (safe when storage is blocked); ships with 5 demo recipes and a "Reset demo" button
- **Accessible** — semantic headings, `aria` labels, visible focus outlines, Esc closes modals, keyboard-reachable controls
- Single-file HTML+CSS+JS, no CDN, no images

## Design

Rustic cozy: cream `#FBF6EE` background with a thin reclaimed-wood grain, coffee `#B5651D` and terracotta `#C4633A` accents, Georgia serif for titles, monospace for ingredient quantities, and softly-rounded cards.

## Run

```bash
vercel --prod
```