# Rumah Data AI Office

Founder-led, modular office simulator for Rumah Data. The interface is designed for GitHub Pages on a **public GitHub Free repository**.

## Included divisions
- **Creative** — data-driven content production.
- **Marketing** — audience, market, trend, competitor, and content-performance research.
- **Investment** — instrument screening, fundamental analysis, valuation, and risk scenarios. Outputs are decision support, not automatic trade instructions.
- **Research** — research ideation, literature mapping, methodology, and research development.
- **Website Development** — planned module for a later stage.
- **Game Development** — planned module for a later stage.

## Run locally
Open `app/index.html` in a modern browser. No build step or API key is needed.

## Publish with GitHub Free
1. Create a **Public** repository named `rumah-data-ai-office`.
2. Upload the contents of this folder to the repository root (so `index.html` remains inside `app/`).
3. In repository Settings → Pages, choose **Deploy from a branch**, branch `main`, folder `/ (root)` only if you move `app/index.html` to root; easiest option is to set Pages source to GitHub Actions or copy `app/index.html` to root as `index.html`.
4. For the simplest setup, copy `app/index.html` to repository root and select `main` / `root` in Pages settings.
5. Wait for deployment and open the Pages URL.

## Important limitations
- This is a **simulation prototype**, not a live autonomous AI office. Staff assignments and workflows are user-triggered simulations.
- No live web research, market feed, stock-price feed, AI model, automatic scheduler, or actual publication is connected.
- Investment analysis is not personalized financial advice. Verify current data and risks independently; the app never places trades.
- Data is stored in browser `localStorage` on the current device/browser. It does not sync between devices. Use Export JSON for backup.
- A public repository means the source code is public. Never commit passwords, API keys, personal data, private datasets, or confidential research.
- Anyone who can open the public Pages URL can access the app interface. Do not put confidential information in it.

## Architecture
`config/divisions.json` and `config/employees.json` define divisions and staff. `app/index.html` is the current self-contained prototype. `src/` contains future modular architecture notes; it is not yet a production backend.
