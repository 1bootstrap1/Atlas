# Atlas Lab Calendar (proof of concept)

Static, single-page app. All schedule data is stored in the browser's `localStorage` on each device.
This repository contains **code only** — never commit exports or backups.

## Deploy (GitHub Pages)
1. Create a repo (e.g. `atlas-calendar`) and push these files to `main`.
2. Settings → Pages → Source: "Deploy from a branch" → `main` / `/ (root)`.
3. Open `https://<username>.github.io/<repo>/` on your phone.
4. Add to Home Screen (iOS: Share → Add to Home Screen; Android: menu → Install app).

## Notes
- Data is per-device and per-URL. Don't rename the repo/URL after entering real data.
- Use the in-app export for backups; store them outside this repo.
- The AI features call api.anthropic.com directly using a key you enter in the app (kept in localStorage).
