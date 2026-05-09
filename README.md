# DayPlan

Day planner & schedule manager PWA. Part of the same app suite as HabitTrack and CalTrack.

## Features

- **Day view** — Add tasks with start time, duration, and category. Drag to reorder; times auto-cascade. Tap to edit or move tasks between days.
- **Week view** — See all 7 days at a glance with task previews. Tap any day to drill in.
- **Month view** — Calendar grid with category-colored dots. Tap a day to jump to it.
- **Templates** — Save any day's schedule as a reusable template, then stamp it onto future dates.
- **Settings** — Default duration, day start/end, gap between tasks, JSON export/import, full reset.

## Setup

1. Push all files to a GitHub repo
2. Enable GitHub Pages (Settings → Pages → main branch)
3. Open the Pages URL in iOS Safari
4. Tap Share → Add to Home Screen

## Files

- `index.html` — The entire app (single file, no build step)
- `manifest.json` — PWA manifest
- `sw.js` — Service worker for offline support
- `icon-192.png` — Home screen icon
- `icon-512.png` — Splash screen icon

## Data

All data stored in localStorage. Use Settings → Export to back up as JSON.
