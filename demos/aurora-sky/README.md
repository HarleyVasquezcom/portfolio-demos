# Aurora Sky

Generative canvas animation of aurora wave layers that drag with your pointer. Three palettes and click-spawned meteor streaks.

## Features

- Layered sine-wave "aurora" ribbons rendered on `<canvas>`
- Pointer-reactive distortion across X and Y axes
- 3 palette modes (aurora, coral, vector) via HUD controls
- FPS meter + meteor streak effect on control clicks
- Deviceless single-file (no build step, no dependencies)

## Run

```bash
vercel --prod
# or open index.html directly in any browser
```

## Design note

Metallic dark zinc background with emerald/cyan accents to match the portfolio system. Uses `requestAnimationFrame`-based RAF loop with a lightweight rolling FPS counter.