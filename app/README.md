# Time is capital — publish to GitHub Pages

1. On github.com, create a new **public** repository, e.g. `time-capital`.
2. **Add file → Upload files**. Drag in everything in this folder: `index.html`, `sw.js`, `manifest.webmanifest`, `icon-180.png`, `icon-192.png`, `icon-512.png`. Commit.
3. Repo **Settings → Pages**. Source: *Deploy from a branch*, branch `main`, folder `/ (root)`. Save.
4. After ~1 minute your app is at `https://<your-username>.github.io/time-capital/`.
5. On iPhone, open that URL **in Safari** → Share → **Add to Home Screen**. Open it from the home screen from now on.

## Updating
Upload the new `index.html` (replace). Also bump `CACHE = 'tic-v2'` in `sw.js` if you change other files. Your data is on the phone, not in the repo — updates never erase it. Open the app twice after an update to get the new version.

## Your data
Stored in this browser on this phone only. Use **Settings → Export backup** weekly (saves to Files). **Import backup** restores it.
