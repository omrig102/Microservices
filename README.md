# Weekly Plan

Two developers, one shared weekly rhythm. The goal is to get hired: stay sharp on fundamentals, practice interviews, and build a portfolio project each.

| Day | Hours | Focus |
|---|---|---|
| Sunday | 08:00-13:00 | LeetCode |
| Monday | Flexible | Job search, interviews, catch-up |
| Tuesday | 08:00-13:00 | System design |
| Wednesday | 10:00-12:00 | AI |
| Thursday | 08:00-13:00 | Project |
| Friday-Saturday | Off | Rest |

**Rule:** a real interview always takes priority. Move the missed session to Monday.

---

## Sunday - LeetCode (08:00-13:00)

| Time | Activity |
|---|---|
| 08:00-08:20 | Learn the week's pattern (NeetCode video or notes) |
| 08:20-10:20 | Each of you solves the same 3 problems in Java, alone, with a 35-minute timer per problem |
| 10:20-10:35 | Break |
| 10:35-11:35 | Mock interviews: each of you interviews the other for 30 minutes on a new problem with the same pattern, thinking out loud and stating the time and space complexity |
| 11:35-12:30 | Review the problems either of you didn't solve, and write a short note on the pattern in a shared `leetcode-notes/` repo |
| 12:30-13:00 | One timed problem from a different pattern (Top Interview 150) |

**Pattern rotation (one per week):**
1. Arrays and hashing
2. Two pointers and sliding window
3. Stack and monotonic stack
4. Binary search
5. Linked lists
6. Trees (DFS/BFS)
7. Heaps and tries
8. Backtracking
9. Graphs (BFS, DFS, topological sort, union-find)
10. 1D dynamic programming
11. 2D dynamic programming
12. Intervals and greedy
13. Bit manipulation and math
14. Mixed review and a timed mock contest

After week 14: the NeetCode 150 problems you haven't solved yet, plus the weekly LeetCode contest.

---

## Monday - Job search and buffer (flexible)

- Apply to 5-10 tailored jobs each, and ask former colleagues for referrals.
- Update the shared job tracker: company, stage, contact, next step.
- Add every question you were asked in real interviews to the "asked in interviews" log.
- Make up any session you missed during the week.

---

## Tuesday - System design (08:00-13:00)

| Time | Activity |
|---|---|
| 08:00-09:00 | Study the week's main problem (Alex Xu's books, ByteByteGo, Hello Interview) |
| 09:00-09:50 | Mock 1: one of you is the candidate for the main problem; the other plays the interviewer and pushes back |
| 10:00-10:50 | Mock 2: swap roles and use the backup problem |
| 11:00-12:00 | Technology deep dive |
| 12:00-13:00 | Discuss one chapter of *Designing Data-Intensive Applications*, plus anything from the "asked in interviews" log |

**Mock structure:** requirements, rough capacity estimates, API, data model, high-level design, deep dives, bottlenecks and trade-offs.

**Topic rotation:**

| Week | Main problem | Backup problem | Deep dive |
|---|---|---|---|
| 1 | URL shortener | Pastebin | Postgres: indexes, EXPLAIN, MVCC, isolation levels |
| 2 | Rate limiter | API gateway | Redis: data structures, eviction, persistence, cluster |
| 3 | Notification system | Email service | Kafka: partitions, consumer groups, rebalancing, exactly-once |
| 4 | News feed | Instagram | Cassandra: partition and clustering keys, consistency levels |
| 5 | Chat (WhatsApp) | Presence service | MongoDB: data modeling, indexes, aggregation, sharding |
| 6 | Payment system | Wallet | Oracle vs Postgres, distributed transactions, sagas |
| 7 | Ticket booking | Hotel booking | Concurrency and locking strategies |
| 8 | Ride sharing (Uber) | Proximity service | Kubernetes and OpenShift |
| 9 | Search autocomplete | Web crawler | Spring Boot internals, virtual threads |
| 10 | Metrics and monitoring | Logging pipeline | Prometheus, Grafana, Splunk, OpenTelemetry |
| 11 | Distributed job scheduler | CI/CD system | Jenkins, GitLab, Bitbucket, deployment strategies |
| 12 | LLM chatbot with RAG | AI code assistant | LLM system design |
| 13 | Your own project | The other's project | Present your design as an interview and defend it |
| 14 | Weakest topics from the "asked in interviews" log | - | - |

---

## Wednesday - AI (10:00-12:00)

| Time | Activity |
|---|---|
| 10:00-10:40 | Learn the week's topic together |
| 10:40-11:40 | Hands-on exercises in a separate AI sandbox repo (not part of the projects) |
| 11:40-12:00 | Show each other what you built; each of you writes 3 interview-ready bullet points on the topic |

**Topic rotation:**
1. LLM basics: tokens, context window, temperature, choosing a model
2. Prompting and structured output
3. Embeddings and vector search
4. Retrieval-augmented generation (RAG)
5. Tool calling
6. MCP (Model Context Protocol)
7. Agents and multi-step workflows
8. Evaluating LLM output
9. Guardrails and prompt injection
10. Cost, latency and observability
11. AI-assisted development: coding agents, AI code review
12. AI news review
13. Hardening your sandbox work
14. Demo to each other

---

## Thursday - Project (08:00-13:00)

Each of you designs and builds your own project, alone, from its brief:

- Developer A: `ShopFlow-Requirements.pdf` (online store with flash sales)
- Developer B: `TicketFlow-Requirements.pdf` (event ticket booking)

| Time | Activity |
|---|---|
| 08:00-08:15 | Stand-up: what you did last week, what you'll do today, what's blocking you |
| 08:15-11:30 | Design and build in your own repo |
| 11:30-12:20 | Review each other's pull requests or design documents |
| 12:20-13:00 | Demo your progress, discuss the design decisions, then a short retro |

**Suggested milestones** (adjust them to your own design):
- **Weeks 1-2:** design document, architecture diagrams and decision records; review them together as a design interview.
- **Weeks 3-8:** core features and the hardest correctness problem (overselling stock in ShopFlow, double-booking a seat in TicketFlow).
- **Weeks 9-11:** observability and CI pipelines.
- **Weeks 12-13:** Kubernetes and OpenShift deployment.
- **Week 14:** load tests, failure experiments, README and demo video.

---

## Shared tools

- **Job tracker:** company, role, stage, contact, next step, date.
- **"Asked in interviews" log:** every real interview question; feeds Tuesday and Sunday topics.
- **Project boards:** one per project, kept by its owner.
- **`leetcode-notes/` repo:** one note per pattern.
