# ETF Research Terminal

Institutional-grade research terminal covering 18 long-duration ETFs across four sleeves — Foundational Core, Growth Engine, Dividend & Quality, and Diversifiers — with an interactive return simulator and four model portfolio allocations.

---

## Features

- **Core Coverage (18 ETFs)** — Full thesis writeups with AUM, expense ratio, holdings count, and yield for VTI, VOO, SPLG, ITOT, QQQM, SCHG, VUG, VGT, SCHD, DGRO, QUAL, VIG, VXUS, IEFA, AVUV, VYM, IJR, and BND.
- **Return Simulator** — Pick any ETF (auto-loads its long-run CAGR default), set initial capital, monthly contribution, and time horizon. Outputs terminal value, total contributed, growth, and growth multiple, with a year-by-year balance chart.
- **Model Portfolios** — Four framework allocations: Set & Forget (3-fund), Growth Sleeve (aggressive), Quality & Income (balanced), Core-Satellite (institutional-style).
- **Methodology** — Inclusion screen, what was excluded and why, how to use the terminal.

## Stack

- Single-file HTML, no build pipeline
- Chart.js 4.4.0 via CDN
- Libre Baskerville + JetBrains Mono via Google Fonts
- Zero external dependencies beyond the above CDNs

## Deploying to GitHub Pages

1. Create a new repo on GitHub (any name you like, e.g. `etf-research-terminal`).
2. Upload the contents of this folder (`index.html`, `README.md`, `.nojekyll`) to the repo root.
3. Go to **Settings → Pages**.
4. Under **Source**, select **Deploy from a branch**, choose `main` (or `master`), folder `/ (root)`.
5. Save. The site will be live at `https://<your-username>.github.io/<repo-name>/` in 30–60 seconds.

The `.nojekyll` file is included so GitHub Pages serves the HTML directly without running Jekyll preprocessing.

### Quick deploy via CLI

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

Then enable Pages in the repo settings as above.

## Disclaimers

Educational and research-oriented content. **Not investment advice.** Past performance does not predict future returns. Fund AUM, expense ratios, and yield figures are point-in-time approximations — cross-reference with fund sponsor sites before transacting.

## License

Personal use. No warranty.
