# Aurora Spectrum - Web Audio Visualizer

Single-file live audio spectrum visualizer built on the Web Audio API. Deep-space
aurora theme: near-black violet canvas, cyan/magenta/violet gradients and glow.

## Features

- **Live spectrum bars** - FFT via `AnalyserNode`, logarithmic frequency mapping.
- **Three visualization modes** - `BARS`, `WAVE` (time-domain oscilloscope) and
  `ORB` (radial ring), switched by tabs.
- **Microphone capture** - `getUserMedia` streams your mic into the analyser
  (button: MIC).
- **Demo tone fallback** - internal oscillator chord + LFO lowpass sweep plays
  with zero input and no permission (button: DEMO TONE). Used automatically if
  mic permission is denied or unsupported.
- **Sensitivity pre-gain** - live gain slider (0..2x).
- **RMS + peak meter** - numeric HUD and an animated amplitude bar.
- **Pause / resume** - suspends the audio context and freezes rendering.
- No CDN, no external images, no dependencies. Only ASCII in the runtime.

## How it was tested
- **Syntax**: the `script` block was extracted and run through Node's
  `new Function` - parses without error.
- **Character check**: zero non-ASCII characters in the script block.
- **Smoke test (manual)**: open the file and the app boots in DEMO TONE - a
  chord should audibly play and the spectrum animate immediately, with no file,
  permission or server needed. Switch BARS / WAVE / ORB, drag SENS, press
  PAUSE/RESUME, then MIC to request the microphone.

## Run
```bash
vercel --prod
```