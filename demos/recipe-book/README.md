# Recipe Book — Rustic Cozy Cookbook

A single-file recipe manager with a warm, rustic-modern aesthetic (cream paper, café/terracotta accents, serif headings).

## Features

- Recipe CRUD: name, description, time, difficulty, servings, ingredients (amount + unit + name), ordered steps and tags
- Card grid with gradient placeholder covers and a favorites heart
- Text search plus tag / category filter chips
- Detail modal with an interactive ingredient checklist and checkable steps (progress in the card)
- Ingredient scaling to adjust portions
- Reset and demo recipes pre-loaded
- Persistence via localStorage with try/catch
- Accessible: labeled controls, focus rings, keyboard operable
- Single-file, no CDN, no external images

## Run

```bash
vercel --prod
```