# Indian Equity Opening Gap Analysis

Interactive GitHub Pages dashboard comparing historical opening-gap performance for Nifty 100, the remaining Nifty 500 constituents, and the Nifty 500 overall.

## How to view
Open `index.html` in a browser, or enable GitHub Pages in repository Settings → Pages → Deploy from a branch → `main` / root.

## Coverage
18 November 2025 – 17 November 2026, 246 trading sessions, 496 matched Nifty 500 stocks including 100 Nifty 100 stocks. 76,122 nonnegative-gap observations.

## Methods
Opening gap = (open − previous close) / previous close × 100. Intraday return = (close − open) / open × 100. Each qualifying stock-day is one observation. Results assume buying at open and selling at close, no stop-loss, before trading costs.

## Limitations
Current constituent snapshots create survivorship/look-ahead bias. Published opening prices may not be achievable. Corporate-action effects, costs, slippage and liquidity constraints are not independently verified. High-gap groups have small sample sizes. This is exploratory historical analysis, not an investment strategy or advice.

## Data rights
This repository contains only manually transcribed aggregate statistics and no raw NSE Bhavcopy files. Review applicable NSE and NSE Indices data-use terms before redistribution or commercial reuse.

## Technologies
HTML, CSS, JavaScript, Chart.js (loaded from CDN). No backend, credentials or database required.
