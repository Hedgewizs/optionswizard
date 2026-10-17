# OptionsWizard — site source

Tim's own finance/stock education site about mechanical premium-selling options strategies.
Static HTML + one shared stylesheet. No build step, no frameworks — GitHub Pages ready.

## Page map

| File | Language | Content |
|---|---|---|
| `index.html` | EN | Home: hero, core philosophy, flagship formula (16Δ / 45 DTE / IVR 50+ / 50% profit / 21 DTE), strategy cards, starter links |
| `strategies.html` | EN | The Playbook: short strangle (flagship), iron condor, cash-secured puts + wheel, covered calls, Jade Lizard, credit spreads, ratio spreads, broken-wing butterfly, diagonals |
| `rules.html` | EN | The 16 mechanical rules (numbered), incl. VIX-scaled buying-power table |
| `metrics.html` | EN | Key metrics: IV Rank (+formula), IV percentile, expected move, delta-as-probability, POP, probability of touch, BPR, beta-weighted delta, concentration |
| `mistakes.html` | EN | Loser management (rolling the untested side, 21-DTE beats P/L stops), sizing as survival, 6 classic beginner mistakes |
| `tw/index.html` … `tw/mistakes.html` | 繁體中文（台灣） | Full Traditional Chinese mirrors of all 5 pages |
| `styles.css` | — | Shared stylesheet: dark finance theme, green/gold accents, sticky nav, mobile responsive |

## Conventions

- Every page: sticky header with nav links + EN/中文 language switcher (links to the same page in the other language), footer disclaimer on every page (educational only, not financial advice).
- Links are relative: root pages use `strategies.html` / `tw/index.html`; `/tw/` pages use `../index.html` and `../styles.css`. Works both locally and under a GitHub Pages project path (`hedgewizs.github.io/optionswizard/`).
- Mobile nav: hamburger button toggles `.main-nav.open` via a small inline script.

## Content rules (do not break)

- All copy is original. Never mention tastytrade, tastylive, Tom Sosnoff, or any of their show/presenter names or branding. Strategy facts and numbers are stated in Tim's own words.
- Footer disclaimer must stay on every page.
