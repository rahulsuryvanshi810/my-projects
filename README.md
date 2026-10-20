# My Projects

One place to track every project I have built. Newest first.

Finished work and progress log: [PROJECT_DONE.md](PROJECT_DONE.md)

GitHub profile: https://github.com/rahulsuryvanshi810

| # | Project | Domain | Tech | Started | GitHub | Local folder |
|---|---------|--------|------|---------|--------|--------------|
| 1 | **darkstore-pulse-bi** | BI / Data Analysis | Power BI (DAX, Power Query), Tableau (LOD), Python, Chart.js | 2026-10-20 | [link](https://github.com/rahulsuryvanshi810/darkstore-pulse-bi) · [live](https://rahulsuryvanshi810.github.io/darkstore-pulse-bi/) | `projects/GitHub-Projects/darkstore-pulse-bi` |
| 2 | **customer-churn-prediction** | Machine Learning / Classification | Python, scikit-learn, pandas, matplotlib | 2026-10-19 | [link](https://github.com/rahulsuryvanshi810/customer-churn-prediction) | `projects/GitHub-Projects/customer-churn-prediction` |
| 3 | **music-store-sql-analysis** | Data Analysis / SQL | SQL (SQLite), Python, pandas, matplotlib | 2026-10-19 | [link](https://github.com/rahulsuryvanshi810/music-store-sql-analysis) | `projects/GitHub-Projects/music-store-sql-analysis` |
| 4 | **uplift-targeting** | Data Science / Causal ML | Python, scikit-learn, pandas, matplotlib | 2026-10-11 | [link](https://github.com/rahulsuryvanshi810/uplift-targeting) | `projects/GitHub-Projects/uplift-targeting` |
| 5 | **codesync** | Full-stack / Real-time systems | JavaScript, Yjs (CRDT), WebSockets | 2026-10-10 | [link](https://github.com/rahulsuryvanshi810/codesync) | `projects/GitHub-Projects/codesync` |
| 6 | **sentinel-gateway** | Backend / Distributed systems | JavaScript, Redis (Lua), Prometheus | 2026-10-10 | [link](https://github.com/rahulsuryvanshi810/sentinel-gateway) | `projects/GitHub-Projects/sentinel-gateway` |
| 7 | **llm-gateway** | Backend / AI infrastructure | TypeScript, Fastify, Redis, Prisma, Postgres | 2026-09-29 | [link](https://github.com/rahulsuryvanshi810/llm-gateway) | `projects/GitHub-Projects/llm-gateway` |
| 8 | **llm-redteam** | AI safety / Evaluation | Python | 2026-09-29 | [link](https://github.com/rahulsuryvanshi810/llm-redteam) | `projects/GitHub-Projects/llm-redteam` |
| 9 | **store-rating-platform** | Full-stack web | React (Vite), Express, PostgreSQL | 2026-09-29 | [link](https://github.com/rahulsuryvanshi810/store-rating-platform) | `projects/GitHub-Projects/store-rating-platform` |
| 10 | assignment6 | Coursework (web) | Node.js | - | not uploaded | `projects/Local-Only-Projects/assignment6` |
| 11 | assign6wad | Coursework (SPA) | - | - | not uploaded | `projects/Local-Only-Projects/assign6wad` |

---

## Project details

### 1. darkstore-pulse-bi (Business Intelligence: Power BI + Tableau)
**One line:** Can a 10-minute delivery promise survive Pune's evening rush, the monsoon and Diwali? Operations analytics for 8 quick-commerce dark stores.

- **Data:** synthetic (generated from documented business rules), star schema: 97,050 orders, 305k order lines, 20,436 customers, 12 months (Oct 2025 - Sep 2026).
- **What I built:** Python data generator + analysis + 8 data-quality tests; Power BI kit (Power Query, 50+ DAX measures, what-if SLA parameter, RLS, custom theme, 6-page build guide); Tableau kit (flat extract, LOD/table calcs, parameters, set actions, 5-point Story); live interactive web dashboard on GitHub Pages.
- **Headline results:** only 54% of orders meet the 10-min promise (Koregaon Park 76% vs Hinjewadi 30%); rain days drop on-time 59.5% -> 40.2%; 20+ min orders average 1.7 stars; Diwali +73% orders; paid-ads customers order 39% less.
- **Resume bullet:** *Built Power BI and Tableau dashboards (50+ DAX measures, LOD cohorts, what-if SLA parameter) on 97k quick-commerce orders from 8 Pune dark stores; found only 54% met the 10-minute promise, with rain days and the evening rush driving most breaches.*
- **TODO:** build the .pbix and .twbx in the apps with the guides, add screenshots, publish to Tableau Public.

### 2. customer-churn-prediction (Machine Learning)
**One line:** Predicts which telecom customers will leave and ranks them by risk for a retention team.

- **Data:** IBM Telco Customer Churn, 7,043 customers, 26.5% churned.
- **What I built:** cleaning, 3 models (logistic regression, random forest, gradient boosting) compared with 5-fold CV, held-out test, permutation importance, risk scores + bands exported as CSV, 5 tests.
- **Headline results:** ROC-AUC 0.85; calling the top 30% riskiest reaches 65% of churners; month-to-month contracts churn 42.7% vs 2.8% on 2-year.
- **Resume bullet:** *Predicted churn for 7,043 customers (ROC-AUC 0.85); calling the top 30% by risk reaches 65% of all churners.*

### 3. music-store-sql-analysis (Data Analysis / SQL)
**One line:** Answers 12 business questions about a digital music store's sales with SQL.

- **Data:** Chinook sample database (public teaching dataset): 412 invoices, 59 customers, 3,503 tracks, 2021-2025.
- **What I built:** 12 SQL queries (joins, CTEs, subqueries, RANK/NTILE/LAG window functions, running totals); Python runner exporting CSVs for Power BI and charts; 6 reconciliation tests.
- **Headline results:** top 5 countries = 59% of revenue; Rock = 35.5% of sales; 43.4% of tracks never sold; 235-day average gap between a customer's orders.
- **Resume bullet:** *Answered 12 business questions on 412 invoices with SQL joins, CTEs and window functions; found the top 5 countries drive 59% of revenue and 43% of the catalogue never sold.*

### 4. uplift-targeting (Data Science)
**One line:** Predicts which customers buy *because of* a marketing e-mail, not just who buys, then decides who should be e-mailed.

- **Data:** Hillstrom randomized e-mail experiment, 64,000 real customers in 3 random groups.
- **What I built:** S-, T- and X-learners and class transformation implemented from scratch; Qini curves with bootstrap confidence intervals; IPW off-policy evaluation of targeting policies; 12 unit tests; GitHub Actions CI.
- **Headline results:**
  - Women's e-mail: emailing the top 50% picked by the model captures 75% of the total lift (random targeting: 50%; a classic "likely buyer" model: 59%).
  - Men's e-mail: no model beats random, so the right decision is to send it to everyone.
- **Interview talking points:**
  - Why a "response model" is the wrong objective.
  - Why uplift can't be measured per customer, and how Qini curves solve that.
  - How IPW evaluates a policy that was never run.
  - Why I recommended *not* deploying a model for the Men's e-mail.
- **Resume bullet:** *Built a causal uplift-modeling pipeline on a 64k-customer randomized experiment (S/T/X-learners, Qini AUC with bootstrap CIs, IPW policy evaluation); identified a targeting policy capturing 75% of campaign lift with 50% of the e-mail volume.*

### 5. codesync
Real-time collaborative code editor: CRDT (Yjs) sync over a custom WebSocket server, live cursors, offline editing and sandboxed code execution.

### 6. sentinel-gateway
API gateway with a distributed rate limiter (token bucket, sliding window) on Redis Lua scripts, load balancing, circuit breaking and Prometheus metrics.

### 7. llm-gateway
LLM API gateway in TypeScript: Fastify, Redis caching and rate limiting, Prisma/Postgres API keys, input/output guardrails.

### 8. llm-redteam
Red-teaming harness for LLMs: prompt-injection attack suites, canary-based judging, bootstrap confidence intervals, defense comparison.

### 9. store-rating-platform
Full-stack store rating platform: React (Vite) + Express + PostgreSQL, role-based auth for admins, store owners and users.

---

## How to add a new project
1. Add a row to the table at the top (keep newest first, renumber).
2. Add a section under **Project details** with: one line, data/stack, what you built, results, a resume bullet.
3. Save it to GitHub, from the `C:\Users\Rahul\projects\my-projects` folder:
   ```
   git add README.md
   git commit -m "Add <project name>"
   git push
   ```
