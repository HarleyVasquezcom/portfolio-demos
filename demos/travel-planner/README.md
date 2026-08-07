# Travel Planner — Brutalist Explorer

A single-file travel planner with a harsh neo-brutalist look: pure white, 3px black borders, hard offset shadows and amber solid buttons.

## Features

- Trip CRUD: name, destination, country, start/end dates, an editable multi-line plan
- Trips sorted by start date; search by destination/country
- Unified preparation checklist grouped into Documentation, Packing and Booking
- Timeline view comparing trips horizontally (pure CSS)
- Export / import trips as JSON
- Persistence via localStorage (try/catch guarded)
- Accessible: labeled controls, focus rings, keyboard operable
- Single-file, no CDN, no external images

## Run

```bash
vercel --prod
```