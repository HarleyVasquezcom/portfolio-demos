# Notes Vault - Editorial Notebook

A self-contained, dependency-free, single-file notes manager styled as a scientific editorial notebook. Every note renders lightweight Markdown-like formatting (headings, bullets, checklists, inline code) without any virtual DOM or libraries.

## Features

- Vault of notes in a notebook-style sidebar with live text search and position numbers.
- Create, edit, delete, and duplicate notes.
- Markdown-like editor with a custom, dependency-free renderer: `#`/`##` headings, `-` bullets, `- [ ]` / `- [x]` checklists, and `inline code`.
- Write / Preview tabs.
- Autosave with a 500ms debounce, persisted to `localStorage` under key `notes-vault-v1` (wrapped in try/catch).
- Pin your favorite notes and Live note counter.
- Export a single note as `.md`, or the whole vault as `.json` (Blob download).
- Import a vault by dragging a `.json` file onto the window, via the file picker, or by pasting JSON (Blob / FileReader).
- Editorial scientific-light theme: warm paper background, serif typography, ink + bordeaux accent, ruled lines, and a framed hint box. No CDN, no images.
- Accessible: aria labels/roles, visible focus rings, keyboard operable controls.

## Run

```bash
vercel --prod
```