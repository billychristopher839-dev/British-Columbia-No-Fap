# British Columbia — The Road to #1

A single-file habit game. You play the **Province of British Columbia**, climbing from
last place in the Confederation to **#1** over **155 strong days**. Every day you stay on
track, BC charters its next **real city**, in the exact order they were historically
incorporated — from New Westminster (1860) all the way to Mission (2021) — lighting up on
an interactive provincial system map.

## In-game guide
First launch opens a short welcome, and the **How to Play** tab explains everything any time.

## How to play
- **Stayed strong today** → charters the next city + builds your streak.
- **Log a slip** → −3 points and your streak resets, but every city you've built stays on the map.
- **Streak bonuses:** 7d +5 · 14d +10 · 30d +20 · 45d +25 · 60d +30 · 90d +60.
- Reach **155 strong days** and British Columbia tops the nation.

## Features
- Interactive SVG system map of BC (zoom, pan, tap any city, optional charter routes).
- Daily / weekly / monthly progress views with an editable calendar (tap any past day to fix or backfill it).
- Charter Register of every founded city with its real incorporation year.
- Points Ledger, live "Confederation Standing" leaderboard, export / import progress.
- Saves automatically (`window.storage` when available, otherwise `localStorage`).

## Run it
Just open `index.html` in a browser, or deploy with **GitHub Pages**:
1. Push these files to a repo.
2. Settings → Pages → deploy from branch (root).
3. Open the published URL. (`.nojekyll` is included so it serves as-is.)

Cities and incorporation dates are real and historically ordered. The "Confederation
Standing" index is a motivational game device, not official statistics.
