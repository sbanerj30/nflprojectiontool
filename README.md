# NFL 2026 Fantasy Projections

A top-down fantasy football projection tool for the 2026 NFL season.

## What it does

- **Team projections** — edit pass/rush attempts, yards, and TDs for all 32 teams. Defaults are 3-year averages from PFR (2023–2025).
- **Player shares** — *(coming soon)* distribute team totals to players via target/rush share inputs
- **Valuation gaps** — *(coming soon)* compare your projections vs ADP/consensus to find edges

## Data

Historical data sourced from Pro Football Reference team offense stats, 2023–2025 seasons (all 17-game).

## Tech

Single `index.html` file. No build step, no dependencies. Projections persist in `localStorage`.

## Deployment

Deployed on Vercel. Push to `main` to auto-deploy.
