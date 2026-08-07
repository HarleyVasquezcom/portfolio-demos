# Kanban Board — Neon Terminal

A single-file kanban board with a dark neon terminal aesthetic. Columns and cards are persisted to localStorage; all state survives reloads.

## Features

- Add / rename (inline) / delete columns with persistent state
- Cards with title, description and multiple tags, edited in a modal
- Native HTML5 drag & drop between columns plus keyboard arrow-move fallback, with drop-zone highlight
- Text filter that hides non-matching empty columns
- Per-column counters and aggregated HUD stats (cards, columns, open, done)
- Reset to a demo board
- Keyboard friendly: `/` focuses search, arrows move focused card, Esc closes modal
- Single-file, no dependencies, zero CDN / zero images

## Run

```bash
vercel --prod
```

Storage key: `kanban-board-v1` (guarded with try/catch for privacy-mode browsers).