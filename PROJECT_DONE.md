# Projects Done

Every finished project, with where it lives and what was completed.
Last updated: 2026-10-24

## Completed projects

| # | Project | Type | Status | GitHub | On my PC |
|---|---------|------|--------|--------|----------|
| 1 | bullscope | BI / Finance analytics | ✅ Done, tests passing, live dashboard (.pbix/.twbx to add) | https://github.com/rahulsuryvanshi810/bullscope | `C:\Users\Rahul\projects\GitHub-Projects\bullscope` |
| 2 | darkstore-pulse-bi | BI / Power BI + Tableau | ✅ Done, public, tests passing, live dashboard (.pbix/.twbx to add) | https://github.com/rahulsuryvanshi810/darkstore-pulse-bi | `C:\Users\Rahul\projects\GitHub-Projects\darkstore-pulse-bi` |
| 3 | customer-churn-prediction | Machine Learning / Classification | ✅ Done, public, tests passing | https://github.com/rahulsuryvanshi810/customer-churn-prediction | `C:\Users\Rahul\projects\GitHub-Projects\customer-churn-prediction` |
| 4 | music-store-sql-analysis | Data Analysis / SQL | ✅ Done, public, tests passing | https://github.com/rahulsuryvanshi810/music-store-sql-analysis | `C:\Users\Rahul\projects\GitHub-Projects\music-store-sql-analysis` |
| 5 | uplift-targeting | Data Science / Causal ML | ✅ Done, public, tests passing | https://github.com/rahulsuryvanshi810/uplift-targeting | `C:\Users\Rahul\projects\GitHub-Projects\uplift-targeting` |
| 6 | codesync | Full-stack / Real-time | ✅ Done, public | https://github.com/rahulsuryvanshi810/codesync | `C:\Users\Rahul\projects\GitHub-Projects\codesync` |
| 7 | sentinel-gateway | Backend / Distributed systems | ✅ Done, public | https://github.com/rahulsuryvanshi810/sentinel-gateway | `C:\Users\Rahul\projects\GitHub-Projects\sentinel-gateway` |
| 8 | llm-gateway | Backend / AI infrastructure | ✅ Done, public | https://github.com/rahulsuryvanshi810/llm-gateway | `C:\Users\Rahul\projects\GitHub-Projects\llm-gateway` |
| 9 | llm-redteam | AI safety / Evaluation | ✅ Done, public | https://github.com/rahulsuryvanshi810/llm-redteam | `C:\Users\Rahul\projects\GitHub-Projects\llm-redteam` |
| 10 | store-rating-platform | Full-stack web | ✅ Done, public | https://github.com/rahulsuryvanshi810/store-rating-platform | `C:\Users\Rahul\projects\GitHub-Projects\store-rating-platform` |
| 11 | my-projects (this tracker) | Project list | ✅ Done, public | https://github.com/rahulsuryvanshi810/my-projects | `C:\Users\Rahul\projects\GitHub-Projects\my-projects` |
| 12 | Profile README | GitHub profile | ✅ Done, public | https://github.com/rahulsuryvanshi810 | `C:\Users\Rahul\projects\GitHub-Projects\rahulsuryvanshi810` |

All GitHub repos are downloaded in `C:\Users\Rahul\projects\GitHub-Projects` (Desktop shortcut: **My Projects**).

Not uploaded (local only): `assignment6`, `assign6wad`, `golu-chiku-1hr`, `neon-galaxy-defender`, `neuro-racer` in `C:\Users\Rahul\projects\Local-Only-Projects`.

## Work log

### 2026-10-24
- [x] Built **bullscope**: Indian stock market, F&O and mutual fund analytics. Real NSE/BSE prices (51 stocks, 11 indices, since Jan 2023) and 80 fund NAVs plus live search of any AMFI fund; 8-page web dashboard (buy/sell flow, option chain + strategy builder, fund screener, holdings and stakes, advisor); Power BI PBIP with 77 DAX measures; Tableau workbook; 8 tests; daily GitHub Actions refresh.
- [ ] Open the PBIP in Power BI Desktop, refresh, save `BullScope.pbix` and screenshots; publish the Tableau workbook to Tableau Public.

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
