# World Cup 2026 — Build Your Bracket

A fun, interactive bracket predictor for the 2026 FIFA World Cup (Canada · Mexico · USA).
The whole point: **it's never locked.** Most sites freeze once the tournament starts — this one
lets you rank groups, pick your 8 best third-place teams, and call every knockout match whenever you want.

It's a **single `index.html` file** — no build step, no dependencies, no account. Your picks save
automatically in your browser.

## Features
- All 48 teams in the real 12 groups from the official December 2025 draw
- Tap to rank each group; top 2 advance automatically
- Choose any 8 of the 12 third-place teams — they're slotted into the bracket using FIFA's
  official Round-of-32 allocation rules (no team ever meets its own group early)
- Full knockout tree: Round of 32 → Round of 16 → Quarters → Semis → Third place → Final
- **Golden path:** crown a champion and their entire route lights up gold across the bracket
- "Surprise me" fills a random bracket; "Clear all" starts over
- Works on phone and desktop

## Run it locally
Just open `index.html` in any browser. That's it.

## Put it on GitHub (and host it free with GitHub Pages)
1. Create a new repository on GitHub (e.g. `world-cup-2026-bracket`).
2. Upload `index.html` (and this `README.md`) — use **Add file → Upload files**, or:
   ```bash
   git init
   git add index.html README.md
   git commit -m "World Cup 2026 bracket"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/world-cup-2026-bracket.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source = Deploy from a branch**, pick **Branch = main**,
   folder **/(root)**, and **Save**.
5. Wait ~1 minute. Your bracket is live at:
   `https://YOUR_USERNAME.github.io/world-cup-2026-bracket/`

Because the file is named `index.html`, Pages serves it automatically — no extra config.

## Notes
Independent fan project. Team and bracket data are from the official 2026 World Cup draw and match
schedule. Not affiliated with FIFA. FIFA World Cup™ is a trademark of FIFA.
