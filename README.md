# Micro-Journal

A minimalist, Twitter-inspired personal journaling app built as a single HTML file — no dependencies, no backend, no install.

## Overview

Micro-Journal is a private, text-first daily journal with a clean mobile UI. Write short entries, attach photos, leave personal notes, and mark moments you want to revisit — all stored in the browser.

## Features

- **Compose** — Write entries up to 400 characters with a live circular character counter
- **Comments** — Add private notes to any entry inline
- **Favorites** — Heart any entry to pin it to the Favorites tab
- **Attachments** — Attach up to 2 photos per entry, with a fullscreen preview tap
- **Edit / Delete** — Three-dot menu on every entry lets you edit text inline or delete
- **Search** — Full-text search combined with a month/year date picker
- **Dark Mode** — One-tap toggle in the Profile tab
- **Profile** — Stats (posts, favorites, days), preference toggles, data export placeholder

## Usage

Just open `micro-journal.html` in any modern browser. No server required.

```
open micro-journal.html
```

Everything runs client-side. Photos are stored as base64 in memory (refreshing the page resets state — persistence can be added via `localStorage`).

## Structure

```
micro-journal.html   ← entire app: HTML + CSS + JS in one file
```

## Stack

- Vanilla HTML / CSS / JavaScript
- Zero dependencies
- Inline SVG avatar (no external image requests)
- Responsive mobile layout at 390 × 844 px (iPhone 14 dimensions)

## Screenshots

The UI is presented inside a phone shell and includes four tabs:

| Tab | Description |
|-----|-------------|
| Home | Compose + chronological feed |
| Search | Keyword search + month/year filter |
| Favorites | Hearted entries |
| Profile | Stats + settings |

## License

MIT
