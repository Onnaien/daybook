# Daybook

A single-file, no-build-step time-tracking calendar you can self-host or just open locally. Drag to log hours against a project, see weekly and daily totals, and keep notes — all stored privately in your own browser (nothing is sent to a server).

<!-- Add a screenshot here once you have one, e.g.: ![Daybook screenshot](docs/screenshot.png) -->

## Features

- Weekly calendar (full week or work-week view) covering the full 24-hour day, with adjustable row height and column width
- Click-drag to create a time entry, drag edges to resize, drag the body to move it (even across days)
- Drag a project straight from the sidebar onto the calendar to log time
- Copy/paste entries (`Ctrl/Cmd+C` / `Ctrl/Cmd+V`), right-click menu, keyboard shortcuts
- Per-entry comments (press `E` on a selected entry, or use the ✎ button)
- "Daily overview" panel: hours per project per day, with an optional per-project daily comment field (toggle per project)
- Free-form notes panel, resizable, collapsible, with adjustable text size
- Everything persists in `localStorage` — private per browser, nothing leaves your machine
- Responsive layout; works on mobile

## Using it

**Online:** open `index.html` via GitHub Pages (see below), or download the file and open it directly in any browser — no server required.

**Self-hosting:** it's one static HTML file. Drop it on any static host (GitHub Pages, Netlify, Vercel, S3, etc.) or serve it from your own web server.

## Enabling GitHub Pages for this repo

1. Go to **Settings → Pages**
2. Under "Build and deployment", set **Source** to "Deploy from a branch"
3. Choose the `main` branch and `/ (root)` folder
4. Save — your copy will be live at `https://<your-username>.github.io/<repo-name>/` within a minute or two

## Data & privacy

All data (projects, time entries, notes) is stored in the browser's `localStorage`, scoped to wherever the page is hosted. Nothing is transmitted anywhere. Clearing your browser's site data for this page will erase it — there's no built-in export yet (see Contributing if you'd like to add one).

## Contributing

Issues and pull requests are welcome — bug reports, feature ideas, or just forks for your own tweaks. This started as a single-purpose personal tool, so there's plenty of room for things like CSV export, multi-device sync, or recurring entries if someone wants to take them on.

## License

MIT — see [LICENSE](LICENSE).
