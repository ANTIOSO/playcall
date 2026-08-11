# GB Play Caller 🏈

An AI‑style play‑calling helper for the GameBlazers **Play Caller** daily mini‑game.
Upload or paste a screenshot of the pre‑snap defense and it reads the look, down &
distance, and coverage odds, then recommends the play that gives you the best shot at a
scoring drive — with the reasoning, the risk, and a backup call.

**Live app (after you turn on Pages):** `https://YOUR-USERNAME.github.io/gb-playcaller/`

## What's inside
- **index.html** — the Scanner. Paste or upload a screenshot → get the call. Everything runs
  in your browser; an on‑device text reader does the reading, so nothing is sent to a server.
- **play-caller-assistant.html** — a manual version: tap the pre‑snap look and set the
  coverage odds by hand if you'd rather not use a screenshot.
- **play-caller.skill** — a Claude skill. Save it and paste screenshots to Claude for the
  same calls on any device.

## Put it on your phone (like an app)
1. Turn on GitHub Pages (below).
2. On your iPhone, open the live URL in **Safari**.
3. Tap **Share → Add to Home Screen**. It launches full‑screen with its own icon.

## Turn on GitHub Pages
In your repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch →
Branch: `main` / `root` → Save.** Wait about a minute, then visit the URL above.

## How the call is made
The engine weighs each play — Run, Screen, Short, Play‑Action, Deep — against the likely
coverages, aiming to convert first downs and reach the end zone while avoiding
drive‑ending turnovers. On 4th down (no read) it plays the percentages for the distance.
The matchup numbers are tuned estimates, not official data — treat it as a smart
assistant, not gospel.

## Notes
Not affiliated with or endorsed by GameBlazers. Built for personal use. See `LICENSE`.
