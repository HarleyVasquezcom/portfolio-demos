# Palette Loom — Color Palette Generator

Seeded color-palette generator with a golden-angle harmonic mode, per-swatch locking and click-to-copy hex values.

## Features

- Deterministic palettes from a numeric seed (mulberry32 PRNG)
- Harmonic harmony mode using the golden angle for pleasing spacing
- Per-swatch lock so a regenerate keeps your favorites
- Click any hex to copy it to the clipboard
- HSL → hex conversion, fully client-side
- Single-file, no dependencies

## Run

```bash
vercel --prod
```