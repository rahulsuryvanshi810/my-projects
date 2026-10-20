# Projects Done

Every finished project, with where it lives and what was completed.
Last updated: 2026-10-20

## Completed projects

| # | Project | Type | Status | GitHub | On my PC |
|---|---------|------|--------|--------|----------|
| 1 | darkstore-pulse-bi | BI / Power BI + Tableau | ✅ Done, public, tests passing, live dashboard (.pbix/.twbx to add) | https://github.com/rahulsuryvanshi810/darkstore-pulse-bi | `C:\Users\Rahul\projects\darkstore-pulse-bi` |
| 2 | customer-churn-prediction | Machine Learning / Classification | ✅ Done, public, tests passing | https://github.com/rahulsuryvanshi810/customer-churn-prediction | `C:\Users\Rahul\projects\customer-churn-prediction` |
| 3 | music-store-sql-analysis | Data Analysis / SQL | ✅ Done, public, tests passing | https://github.com/rahulsuryvanshi810/music-store-sql-analysis | `C:\Users\Rahul\projects\music-store-sql-analysis` |
| 4 | uplift-targeting | Data Science / Causal ML | ✅ Done, public, tests passing | https://github.com/rahulsuryvanshi810/uplift-targeting | `C:\Users\Rahul\projects\uplift-targeting` |
| 5 | codesync | Full-stack / Real-time | ✅ Done, public | https://github.com/rahulsuryvanshi810/codesync | `C:\Users\Rahul\projects\codesync` |
| 6 | sentinel-gateway | Backend / Distributed systems | ✅ Done, public | https://github.com/rahulsuryvanshi810/sentinel-gateway | `C:\Users\Rahul\projects\sentinel-gateway` |
| 7 | llm-gateway | Backend / AI infrastructure | ✅ Done, public | https://github.com/rahulsuryvanshi810/llm-gateway | GitHub only |
| 8 | llm-redteam | AI safety / Evaluation | ✅ Done, public | https://github.com/rahulsuryvanshi810/llm-redteam | GitHub only |
| 9 | store-rating-platform | Full-stack web | ✅ Done, public | https://github.com/rahulsuryvanshi810/store-rating-platform | GitHub only |
| 10 | my-projects (this tracker) | Project list | ✅ Done, public | https://github.com/rahulsuryvanshi810/my-projects | `C:\Users\Rahul\projects\my-projects` |
| 11 | Profile README | GitHub profile | ✅ Done, public | https://github.com/rahulsuryvanshi810 | `C:\Users\Rahul\projects\rahulsuryvanshi810` |

Not uploaded (coursework, local only): `assignment6`, `assign6wad` in `C:\Users\Rahul\projects`.

## Work log

### 2026-10-20
- [x] Built **darkstore-pulse-bi**: quick-commerce operations BI on 97k orders from 8 Pune dark stores. Python generator + analysis + 8 tests, Power BI kit (Power Query, 50+ DAX, theme, guide), Tableau kit (calcs, LODs, story), live web dashboard on GitHub Pages.
- [ ] Build `DarkStore_Pulse.pbix` (Power BI Desktop) and `DarkStore_Pulse.twbx` (Tableau Public) from the guides; add screenshots.

### 2026-10-19
- [x] Built **customer-churn-prediction**: IBM Telco data, 3 models with CV, ROC-AUC 0.85, top-30% risk reaches 65% of churners, CSV risk scores, 5 tests. Replaced SafeCity AI on resume.
- [x] Built **music-store-sql-analysis**: 12 SQL business questions on the Chinook database (joins, CTEs, window functions), CSV exports for Power BI, charts, 6 reconciliation tests. Added to resume (replaced Sentinel) and GitHub profile.

### 2026-10-11
- [x] Built **uplift-targeting** data science project:
  - Models: S/T/X-learners and class transformation, written from scratch.
  - Evaluation: Qini curves with bootstrap confidence intervals, IPW policy evaluation.
  - Quality: 12 unit tests and 4 charts.
- [x] Uploaded uplift-targeting to GitHub (public); automatic tests passed.
- [x] Created project list (`README.md` in this repo) and uploaded it.
- [x] Updated GitHub profile README: data science focus, featured projects table, link to project list.
- [x] Made every repo public (8 of 8).
- [ ] Pin top 6 repos on profile (manual: profile → **Customize your pins**).

## Key result to remember (uplift-targeting)
- Women's e-mail: model targets the top 50% of customers and captures **75% of the lift**. Random targeting gets 50% and a "likely buyer" model gets 59%.
- Men's e-mail: no model beats random, so the right call is to send it to everyone.
