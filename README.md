# My Projects

One place to track every project I have built. Newest first.
GitHub profile: https://github.com/rahulsuryvanshi810

| # | Project | Domain | Tech | Started | GitHub | Local folder |
|---|---------|--------|------|---------|--------|--------------|
| 1 | **uplift-targeting** | Data Science / Causal ML | Python, scikit-learn, pandas, matplotlib | 2026-10-11 | [link](https://github.com/rahulsuryvanshi810/uplift-targeting) | `projects/uplift-targeting` |
| 2 | **codesync** | Full-stack / Real-time systems | JavaScript, Yjs (CRDT), WebSockets | 2026-10-10 | [link](https://github.com/rahulsuryvanshi810/codesync) | `projects/codesync` |
| 3 | **sentinel-gateway** | Backend / Distributed systems | JavaScript, Redis (Lua), Prometheus | 2026-10-10 | [link](https://github.com/rahulsuryvanshi810/sentinel-gateway) | `projects/sentinel-gateway` |
| 4 | **llm-gateway** | Backend / AI infrastructure | TypeScript, Fastify, Redis, Prisma, Postgres | 2026-09-29 | [link](https://github.com/rahulsuryvanshi810/llm-gateway) | - |
| 5 | **llm-redteam** | AI safety / Evaluation | Python | 2026-09-29 | [link](https://github.com/rahulsuryvanshi810/llm-redteam) | - |
| 6 | **store-rating-platform** | Full-stack web | React (Vite), Express, PostgreSQL | 2026-09-29 | [link](https://github.com/rahulsuryvanshi810/store-rating-platform) | - |
| 7 | assignment6 | Coursework (web) | Node.js | - | not uploaded | `projects/assignment6` |
| 8 | assign6wad | Coursework (SPA) | - | - | not uploaded | `projects/assign6wad` |

---

## Project details

### 1. uplift-targeting (Data Science)
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

### 2. codesync
Real-time collaborative code editor: CRDT (Yjs) sync over a custom WebSocket server, live cursors, offline editing and sandboxed code execution.

### 3. sentinel-gateway
API gateway with a distributed rate limiter (token bucket, sliding window) on Redis Lua scripts, load balancing, circuit breaking and Prometheus metrics.

### 4. llm-gateway
LLM API gateway in TypeScript: Fastify, Redis caching and rate limiting, Prisma/Postgres API keys, input/output guardrails.

### 5. llm-redteam
Red-teaming harness for LLMs: prompt-injection attack suites, canary-based judging, bootstrap confidence intervals, defense comparison.

### 6. store-rating-platform
Full-stack store rating platform: React (Vite) + Express + PostgreSQL, role-based auth for admins, store owners and users.

---

## How to add a new project
1. Add a row to the table at the top (keep newest first, renumber).
2. Add a section under **Project details** with: one line, data/stack, what you built, results, a resume bullet.
