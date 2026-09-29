# Data science portfolio

Source for [Michael Caan's portfolio](https://mcaan.github.io/), hosted with GitHub Pages.

The homepage is a responsive static page in `index.html` and `styles.css`. Each card opens a concise case study under `projects/`, with links to the full code and README in its GitHub repository. The sidebar links to the résumé, GitHub, and LinkedIn; the bio remains a placeholder.

## Projects

| Project | Focus | Case study | Repository |
| --- | --- | --- | --- |
| Customer LTV and Churn Predictions | RFM segmentation, CLV forecasting, and churn modeling | [Case study](projects/customer-ltv-churn.html) | [LTV-Churn-Online-Retail](https://github.com/mcaan/LTV-Churn-Online-Retail) |
| NCAA March Madness 2026 | Predictive modeling, feature engineering, and evaluation objectives | [Case study](projects/march-madness.html) | [NCAA-March-Madness-2026](https://github.com/mcaan/NCAA-March-Madness-2026) |
| Product notification experiment | Randomized A/B test and conversion–retention trade-off | [Case study](projects/notification-ab-test.html) | [Product-Notification-AB-Test](https://github.com/mcaan/Product-Notification-AB-Test) |
| Mental health in tech | Survey harmonization, segmentation, and treatment-seeking propensity | [Case study](projects/mental-health-tech.html) | [Open-Sourcing-Mental-Health](https://github.com/mcaan/Open-Sourcing-Mental-Health) |

## Local preview

Run `python -m http.server 8000` in this repository, then open `http://localhost:8000/`. The page uses no build step or external assets.

## Publishing

In repository **Settings → Pages**, set **Source** to **Deploy from a branch**, select `main` and `/(root)`, and save. The `.nojekyll` file makes GitHub Pages serve the static files directly. Check the Pages settings for the published URL after deployment.

To clone the project repositories locally too, use `git clone --recurse-submodules https://github.com/mcaan/mcaan.github.io.git`. To update pinned project revisions, run `git submodule update --remote` and commit the changed submodule pointers.
