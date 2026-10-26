# THE WORLD OF GAULAX — free starter

A static, responsive HTML/CSS/JavaScript starter for the private two-player gaming website.

## Run it
1. Unzip the folder.
2. Open `index.html` in a browser. No build step needed.
3. Internet is used only for Google Fonts; the site still works without them.

## What works in this starter
- Responsive midnight-violet dashboard and four themed game portals.
- Operation Chikofiya with three demo mystery cases and selectable accusations.
- Bhutkika emoji song-riddle quiz.
- Bacchku's Wonderland story-builder and memory match.
- Chocnilla local two-player Snakes & Ladders race.
- Local score persistence via browser `localStorage`.

## Important limitations
This is a playable front-end starter, **not yet a secure online multiplayer website**.
Scores are stored on the current browser only. Clues in the demo are visible on the same device. Separate-device multiplayer, secure private clue delivery, invite-only accounts, shared chat/evidence board, online Ludo and carrom need a backend (for example Supabase) plus server-side authorization and testing. Do not put secret keys in browser code.

## Free hosting ideas
You can host static files on GitHub Pages or another static host. That publishes the front-end only; it does not add multiplayer by itself.
