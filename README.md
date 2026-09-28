# Data science portfolio

Source for [Michael Caan's portfolio](https://mcaan.github.io/), hosted with GitHub Pages.

The homepage is a responsive static page in `index.html` and `styles.css`. All four project cards link to their GitHub repositories. The résumé link opens `resume.html`; profile photo and bio remain placeholders.

## Projects

| Project | Focus | Repository |
| --- | --- | --- |
| Customer LTV and Churn Predictions | RFM segmentation, CLV forecasting, and churn modeling | [LTV-Churn-Online-Retail](https://github.com/mcaan/LTV-Churn-Online-Retail) |
| NCAA March Madness 2026 | Predictive modeling, feature engineering, and evaluation objectives | [NCAA-March-Madness-2026](https://github.com/mcaan/NCAA-March-Madness-2026) |
| Product notification experiment | Randomized A/B test and conversion–retention trade-off | [Product-Notification-AB-Test](https://github.com/mcaan/Product-Notification-AB-Test) |
| Mental health in tech | Survey harmonization, segmentation, and treatment-seeking propensity | [Open-Sourcing-Mental-Health](https://github.com/mcaan/Open-Sourcing-Mental-Health) |

## Local preview

Run `python -m http.server 8000` in this repository, then open `http://localhost:8000/`. The page uses no build step or external assets.

## Publishing

In repository **Settings → Pages**, set **Source** to **Deploy from a branch**, select `main` and `/(root)`, and save. The `.nojekyll` file makes GitHub Pages serve the static files directly. Check the Pages settings for the published URL after deployment.

To clone the project repositories locally too, use `git clone --recurse-submodules https://github.com/mcaan/mcaan.github.io.git`. To update pinned project revisions, run `git submodule update --remote` and commit the changed submodule pointers.
