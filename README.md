# Half-Hour Activity Log

A tiny, no-login web app to quickly log what you did every 30 minutes so it's easy to stay consistent.

## Run

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Features

- Shows your current half-hour slot automatically.
- One-line logging with Enter-to-save.
- Quick buttons for common activities.
- Edits the current slot if you log again in the same slot.
- Stores everything in browser `localStorage`.
- Simple daily stats (slots, hours tracked, productive slots, break slots).
