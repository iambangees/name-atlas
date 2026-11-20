# Name Atlas

**What your name means — and how the world says it.**

A small, hand-curated atlas of names. Type a name and get:

- its meaning and origin (traditional etymologies),
- a plain pronunciation guide ("say it"),
- the shapes the name takes in other languages ("Around the world, this name becomes"),
- what the name sounds like / also means elsewhere ("What the world hears"),
- a shareable link and a downloadable name-card image.

## How it works

One static page (`site/index.html`) plus a curated dataset (`site/data.js`, 691 names and growing: Nigerian — Yoruba, Igbo, Hausa and more — Arabic, European classics, the full Akan day-name week, and names from Asia, Africa and beyond). No backend, no tracking, no accounts. Search runs entirely in the visitor's browser — and it's forgiving: 261 spelling variants and pet forms (Mohammed, Liz, Femi…) resolve to their canonical entry, foreign forms find their home name (Ebubekir → Abubakar, Yakubu → Jacob), and near-miss typos get closest-match suggestions instead of a dead end.

Names not in the atlas yet get an honest "not here yet" with close matches — the atlas grows name by name, and entries are added only when the etymology is solid.

## Live

Published with GitHub Pages from this repo's `gh-pages` branch (the `site/` folder).

## Growing it

To add a name, append an entry to `site/data.js` with: `name`, `meaning`, `origin`, `gender` (M/F/U), `say`, `forms` (language → form), and `sounds` (only where the cross-language note is genuinely solid — no invented meanings).
