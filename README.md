# Data science portfolio

Source for [Michael Caan's portfolio](https://mcaan.github.io/portfolio/), hosted with GitHub Pages.

The homepage is a minimal static page in `index.html` and `styles.css`. The three project repositories are tracked as Git submodules; the homepage links directly to their GitHub READMEs for full methods, limitations, notebooks, and data-access notes.

## Projects

| Project | Focus | Repository |
| --- | --- | --- |
| Product notification experiment | Randomized A/B test and conversion–retention trade-off | [Product-Notification-AB-Test](https://github.com/mcaan/Product-Notification-AB-Test) |
| NCAA March Madness 2026 | Predictive modeling, feature engineering, and evaluation objectives | [NCAA-March-Madness-2026](https://github.com/mcaan/NCAA-March-Madness-2026) |
| Mental health in tech | Survey harmonization, segmentation, and treatment-seeking propensity | [Open-Sourcing-Mental-Health](https://github.com/mcaan/Open-Sourcing-Mental-Health) |

## Local preview

Run `python -m http.server 8000` in this repository, then open `http://localhost:8000/`. The page uses no build step or external assets.

## Publishing

In repository **Settings → Pages**, set **Source** to **Deploy from a branch**, select `main` and `/(root)`, and save. The `.nojekyll` file makes GitHub Pages serve the static files directly. Check the Pages settings for the published URL after deployment.

To clone the project repositories locally too, use `git clone --recurse-submodules https://github.com/mcaan/portfolio.git`. To update pinned project revisions, run `git submodule update --remote` and commit the changed submodule pointers.
