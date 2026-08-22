# Pocket Calm 🫧

A gentle breathing meditation for busy days. Pick **1, 5, or 8 minutes** and
breathe along with a little cloud companion — inhale, hold, exhale — with soft
chimes to open and close the session.

- **Made for on-the-go.** Quick to start, works on a phone, discreet.
- **No accounts, no server, nothing tracked.** Runs entirely in the browser.
- **Kind to eyes-closed sessions.** Wall-clock timing plus a screen wake lock
  keep the session accurate and the display awake, so the closing chime always
  lands.
- **One file.** Everything lives in `index.html` (inline CSS + JS). Chimes are
  generated live with the Web Audio API — no audio files, works offline.

## Run it locally

Open `index.html` in your browser, or serve the folder:

```bash
node _serve.js   # then visit http://localhost:8892
```

## Host it on GitHub Pages

1. Push this folder to a GitHub repo.
2. **Settings → Pages → Deploy from a branch**, branch `main`, folder `/(root)`.
3. Live at `https://<username>.github.io/<repo>/` in a minute or two.

## Ideas for later

- More companions to choose from.
- An optional ambient sound toggle.
- A gentle daily reminder.
