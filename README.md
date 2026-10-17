# OptionsWizard — site source

Tim's own finance/stock education site about mechanical premium-selling options strategies.
Static HTML + one shared stylesheet. No build step, no frameworks — GitHub Pages ready.

## Page map

| File | Language | Content |
|---|---|---|
| `index.html` | EN | Home: hero, core philosophy, flagship formula (16Δ / 45 DTE / IVR 50+ / 50% profit / 21 DTE), strategy cards, beginner learning path, starter links |
| `options-basics.html` | EN | Options Basics: beginner course — contracts, calls vs puts, strike/expiration/premium, ITM/ATM/OTM, buying vs selling, intrinsic vs time value, exercise/assignment, why trade options, beginner risks |
| `strategies.html` | EN | The Playbook: short strangle (flagship), iron condor, cash-secured puts + wheel, covered calls, Jade Lizard, credit spreads, ratio spreads, broken-wing butterfly, diagonals |
| `greeks.html` | EN | The Greeks: Delta, Gamma, Theta, Vega, Rho — plain-language explanations, value ranges, seller vs buyer usage, comparison table |
| `rules.html` | EN | The 16 mechanical rules (numbered), incl. VIX-scaled buying-power table |
| `metrics.html` | EN | Key metrics: IV Rank (+formula), IV percentile, expected move, delta-as-probability, POP, probability of touch, BPR, beta-weighted delta, concentration |
| `mistakes.html` | EN | Loser management (rolling the untested side, 21-DTE beats P/L stops), sizing as survival, 6 classic beginner mistakes |
| `tw/*.html` | 繁體中文（台灣） | Full Traditional Chinese mirrors of all 7 pages (入門：選擇權入門；希臘字母：Delta/Gamma/Theta/Vega/Rho) |
| `styles.css` | — | Shared stylesheet: dark finance theme, green/gold accents, sticky nav, mobile responsive |

Nav order (all pages): Home, Basics, Playbook, Greeks, Rules, Metrics, Mistakes — TW: 首頁， 入門， 策略， 希臘字母， 規則， 指標， 誤區. Language switcher links to the same page in the other language.

## Conventions

- Every page: sticky header with nav links + EN/中文 language switcher (links to the same page in the other language), footer disclaimer on every page (educational only, not financial advice).
- Links are relative: root pages use `strategies.html` / `tw/index.html`; `/tw/` pages use `../index.html` and `../styles.css`. Works both locally and under a GitHub Pages project path (`hedgewizs.github.io/optionswizard/`).
- Mobile nav: hamburger button toggles `.main-nav.open` via a small inline script.

## Content rules (do not break)

- All copy is original. Never mention tastytrade, tastylive, Tom Sosnoff, or any of their show/presenter names or branding. Strategy facts and numbers are stated in Tim's own words.
- Footer disclaimer must stay on every page.
