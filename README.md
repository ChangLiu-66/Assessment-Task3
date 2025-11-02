# Patient Flow Mini-Analytics (A3 Evidence)

**Purpose.** This repo supports my A3 report by demonstrating reproducible analytics and collaboration habits (GitHub Flow, PR review, CI). It uses de-identified / synthetic data for **patient-flow** style metrics.

**Ethics & privacy.**
- Dataset: synthetic (no real PHI). See `docs/dataset_card.md` for fields and de-identification approach.
- Scope & limitations: results are illustrative only; not for clinical decision-making.

**KPIs.**
1. Average wait time (minutes)
2. Length of stay (LOS, days)
3. 7-day revisit (proxy rate)

**Structure.**
- `notebooks/analysis.ipynb` — data wrangling + KPI calculation + visuals
- `docs/sop.md` — Data Handling SOP (v1.1)
- `docs/dataset_card.md` — dataset card + disclosure template

**How to run.**
- Python 3.10+, `pip install -r requirements.txt`
- Open notebook and run all cells.

**Quality gates.**
- GitHub Actions runs lint/tests on PRs to `main`.
Compare!!
