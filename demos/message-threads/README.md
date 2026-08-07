# Message Threads

Local chat-like thread manager with a warm "paper chat" look — serif type, terracotta accent and per-thread drafts.

## Features

- Create / open / delete conversation threads, each with a name and its own message list
- Send messages with Enter (Shift+Enter for newline) with timestamp per message
- Author picker (You / Partner / Team) with colored initial avatars
- Lightweight markdown in message text: `**bold**`, `*italic*`, `` `code` ``
- Global search over every message; a hit navigates to its thread and flashes the match
- Per-thread composer draft saved automatically when you switch threads
- Reply-in-chain: quote any message so the reply renders with the original inline
- `localStorage` persistence per thread under `threads-<id>` (try/catch guarded), plus full JSON export
- Accessible: semantic roles, ARIA labels, visible focus rings, full keyboard use
- No CDN, no external images, single-file

## Run

```bash
vercel --prod
```