# GEO-WRECKED! 🌍

A **"You Don't Know Jack!"-style** geography trivia game built to help prepare for 8th grade GeoBee competitions.

## Play It

Just open `index.html` in your browser. That's it — no build step, no install, no server needed.

> **Tip:** Edge and Chrome have the best text-to-speech voices for the announcer feature.

## What's Inside

- **297 fact-checked geography questions** across 5 difficulty tiers
- Snarky game-show host with voice narration (Web Speech API)
- Timer pressure, streak bonuses, and score multipliers
- Questions shuffle every game — 25 per session from a pool of 297
- Fun facts after every answer for actual learning
- Category variety algorithm ensures a good mix each playthrough

## Difficulty Tiers

| Round | Name | Questions | Level |
|-------|------|-----------|-------|
| 1 | Warm Up Your Globe | 64 in pool | Easy |
| 2 | Getting Warmer | 59 in pool | Medium |
| 3 | No More Mr. Nice Globe | 56 in pool | Hard |
| 4 | The Gauntlet | 61 in pool | Very Hard |
| 5 | Championship Round | 57 in pool | Expert |

## Tech

Single-file React app transpiled in-browser via Babel. No build tools required. Uses Web Audio API for sound effects and Web Speech API for voice narration.

## Files

- `index.html` — The playable game (open this in a browser)
- `geobee-game.jsx` — Raw React component source

## License

MIT
