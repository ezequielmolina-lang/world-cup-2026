# Work vs World Cup — Live Fixture 2026

A clean, ad-free, self-updating tracker for the **2026 FIFA World Cup** — every match, every result, in your own timezone.

**Live:** https://ezequielmolina-lang.github.io/world-cup-2026/

- All 104 matches, group stage through the final
- Live scores + match clock, final results, and upcoming kickoffs (auto-converted to your local time)
- Filter by **Live / Today / Upcoming / Results / All**
- Refreshes itself every minute — no ads, no pop-ups, no backend

Single static `index.html`, no build step. Live data comes from ESPN's public soccer scoreboard (keyless, CORS-enabled); results are cached in `localStorage` and the live window re-fetches automatically. Built for the **AI Tuesday** newsletter ⚽
