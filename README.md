# Vigilant Lamp — CS Learning & Interview Prep Hub

> A living, personal reference for anyone studying, working in, or interviewing for roles in computer science — from students to senior engineers.

---

## Quick Navigation

| Track | Interview Rounds | Jump To |
|---|---|---|
| Software Development Engineer (SDE) | Recruiter → Technical → Onsite Loop | [SDE Track](#1-software-development-engineer-sde) |
| Data Engineer / Data Scientist | Recruiter → Technical → Onsite Loop (3–4 rounds) | [DE/DS Track](#2-data-engineer--data-scientist) |
| Forward Deployed Engineer (FDE) | 7-round process | [FDE Track](#3-forward-deployed-engineer-fde) |

---

## Personal Tracker

> This section is a living log. Update it as you go.

### Currently Learning
<!-- Add what you're actively studying right now -->
- 

### Currently Working On
<!-- Active projects, side projects, work tasks -->
- 

### Reading List
<!-- Books, papers, blog posts, newsletters in progress -->
- 

### Open Source Contributions
<!-- PRs, issues, reviews you've made or are working on -->
- 

### Open Projects
<!-- Personal/side projects you're building -->
- 

### Ideas & Notes
<!-- Raw ideas, things to explore, shower thoughts -->
- 

---

## Career Tracks

---

### 1. Software Development Engineer (SDE)

#### Interview Process

| Round | What's Tested | Notes |
|---|---|---|
| Recruiter Screen | Background, compensation, motivation | Know your resume cold; have comp range ready |
| Technical Screen | DS&A (1–2 problems), sometimes take-home | Usually 45–60 min on a shared editor |
| Onsite Loop (3–5 rounds) | Coding, System Design, Behavioral | Mix of depth depends on level (see below) |

#### Round Depth by Experience Level

| Experience | Coding Focus | System Design Focus | Behavioral |
|---|---|---|---|
| New Grad / 0–2 yrs | Medium LC, core DS&A | Basic design (URL shortener, chat) | Culture fit, learning agility |
| Mid-level / 3–6 yrs | Medium–Hard LC, OOP | Distributed systems basics | Ownership, scope, impact |
| Senior / 7+ yrs | Hard LC (occasionally), architecture tradeoffs | Large-scale design, ambiguity handling | Leadership, cross-functional influence |

#### Topics to Study

**Data Structures & Algorithms**
- Arrays, Strings, Hashmaps
- Trees (Binary Tree, BST, Trie)
- Graphs (BFS, DFS, Topological Sort, Union-Find)
- Heaps / Priority Queues
- Dynamic Programming (1D, 2D, interval, knapsack)
- Sliding Window, Two Pointers, Binary Search
- Backtracking
- Sorting & Searching

**System Design**
- Horizontal vs Vertical Scaling
- Load Balancers, CDNs, DNS
- SQL vs NoSQL; when to use each
- Caching (Redis, Memcached, CDN layers)
- Message Queues (Kafka, SQS, RabbitMQ)
- Consistent Hashing, Sharding, Replication
- CAP Theorem, BASE vs ACID
- Rate Limiting, API Gateway
- Common design problems: URL shortener, Twitter feed, Dropbox, YouTube, Uber

**Behavioral**
- STAR format (Situation, Task, Action, Result)
- Leadership principles (especially if interviewing at Amazon)
- Conflict resolution, ambiguous situations, failure stories

#### SDE Resources

- [Tech Interview Handbook — Yangshun Tay](https://github.com/yangshun/tech-interview-handbook) — most complete end-to-end SDE prep guide
- [System Design Primer — Donnemartin](https://github.com/donnemartin/system-design-primer) — canonical system design reference
- [SDE Interview & Prep Roadmap — aasthas2022](https://github.com/aasthas2022/SDE-Interview-and-Prep-Roadmap) — checklist-style across 10 domains
- [What Happens When — alex](https://github.com/alex/what-happens-when) — deep dive into "what happens when you type google.com"
- [Build Your Own X — codecrafters](https://github.com/codecrafters-io/build-your-own-x) — build interpreters, DBs, git, etc. from scratch
- [roadmap.sh/backend](https://roadmap.sh/backend) — backend skills visual roadmap
- [Grind 75 / NeetCode](https://neetcode.io/) — curated problem sets by pattern

#### LeetCode Problem Tracker (Grind 100)

| Pattern | Problem | Difficulty | Status |
|---|---|---|---|
| Hashmaps | [Two Sum](https://leetcode.com/problems/two-sum?envType=problem-list-v2&envId=xoqag3yj) | Easy | |
| Sliding Window | | | |
| Binary Search | | | |
| Trees | | | |
| Graphs | | | |
| DP | | | |
| Backtracking | | | |
| Heaps | | | |

#### System Design Cheatsheet

| Concept | One-liner | Go-to resource |
|---|---|---|
| Load Balancer | Distributes traffic across servers | Nginx, AWS ALB |
| CDN | Caches static assets closer to users | Cloudflare, Akamai |
| Message Queue | Decouples producers from consumers | Kafka, SQS |
| Caching | Reduces DB load for hot reads | Redis (cache-aside pattern) |
| Sharding | Horizontal partitioning of DB | Consistent hashing |
| Rate Limiting | Protects services from abuse | Token bucket, leaky bucket |

---

### 2. Data Engineer / Data Scientist

#### Interview Process

| Round | What's Tested | Notes |
|---|---|---|
| Recruiter Phone Screen | Background, comp, role fit | Know your data stack and past impact |
| Technical Screen | SQL, Python, stats fundamentals | Often take-home or live coding |
| Onsite / Final Loop (3–4 rounds) | See specialized rounds below | |

**Specialized Onsite Rounds**

| Round | Data Engineer Focus | Data Scientist Focus |
|---|---|---|
| Coding / SQL | Pipeline design, complex SQL queries | Feature engineering, pandas/SQL |
| Data Modeling | Schema design, ETL patterns | Experimental design, A/B testing |
| System Design | Data pipeline architecture | ML system design (training/serving) |
| Case Study / Analytics | Data quality, debugging pipelines | Business metrics, hypothesis testing |
| Behavioral | Cross-functional collab, data ownership | Stakeholder communication, uncertainty |

#### Round Depth by Experience Level

| Experience | Technical Depth | Design Scope | Leadership |
|---|---|---|---|
| Entry / 0–2 yrs | SQL window functions, basic Python | Simple ETL, batch pipelines | Individual contributor |
| Mid / 3–5 yrs | Distributed systems (Spark, Flink), orchestration (Airflow) | Streaming + batch, data modeling | Project ownership |
| Senior / 6+ yrs | System architecture, data platform design | Multi-team data mesh, governance | Strategy, mentorship |

#### Topics to Study

**Data Engineering**
- SQL: window functions, CTEs, query optimization
- Python: pandas, PySpark, data manipulation
- Batch vs Streaming pipelines (Spark, Flink, Kafka)
- Orchestration: Airflow, dbt, Prefect
- Cloud data warehouses: BigQuery, Snowflake, Redshift
- Data modeling: Star/Snowflake schema, Data Vault
- Data quality: Great Expectations, dbt tests
- Storage formats: Parquet, Delta Lake, Iceberg

**Data Science / ML**
- Probability & statistics fundamentals
- A/B testing, hypothesis testing, p-values
- Classical ML: regression, classification, clustering, trees
- Feature engineering and selection
- Model evaluation: precision/recall, ROC-AUC, RMSE
- SQL for analysis and feature extraction
- Python: scikit-learn, pandas, numpy
- MLOps basics: model serving, experiment tracking (MLflow)

#### DE / DS Resources

- [roadmap.sh/data-engineer](https://roadmap.sh/data-engineer) — visual skills roadmap for data engineers
- [Designing Data-Intensive Applications — Kleppmann](https://dataintensive.net/) — essential book for distributed data systems
- [The Practical SQL Book](https://www.practicalsql.com/) — SQL from basics to advanced
- [Made With ML](https://madewithml.com/) — end-to-end ML system design
- [Data Engineering Zoomcamp — DataTalks.Club](https://github.com/DataTalks-Club/data-engineering-zoomcamp) — free hands-on DE course
- [Chip Huyen — ML Interviews Book](https://huyenchip.com/ml-interviews-book/) — ML interview deep dive

---

### 3. Forward Deployed Engineer (FDE)

> FDEs sit at the intersection of engineering and consulting. They build technical solutions directly with customers, requiring both deep technical skill and strong communication/business acumen.

#### Interview Process

| Round | What's Tested | Who You Meet |
|---|---|---|
| Recruiter Screen | Background, motivation, comp | Recruiter |
| Hiring Manager Screen | Role fit, experience, ambition | HM or Senior FDE |
| Coding & Algorithms | DS&A, implementation | Engineer |
| System Design | Scalable architecture, APIs | Senior Engineer |
| Customer Case Study | Problem decomposition, solutioning | FDE Lead |
| Client Simulation | Communication, discovery, live demo | Cross-functional panel |
| Behavioral Interview | Leadership, ambiguity, ownership | HM or Director |

#### Round Depth by Experience Level

| Experience | Coding | Design | Customer/Consulting |
|---|---|---|---|
| Entry / 0–2 yrs | Medium LC, scripting | Basic REST APIs, DB schemas | Active listening, basic discovery |
| Mid / 3–5 yrs | Medium-Hard LC, system scripting | Distributed systems, data pipelines | Requirement gathering, scoping |
| Senior / 6+ yrs | Architecture tradeoffs > pure coding | Platform design, multi-tenant systems | MECE thinking, exec-level communication |

#### Topics to Study

**Technical (Engineering Side)**
- Coding: Python, Go, SQL — proficiency at medium-hard LC level
- APIs: REST, GraphQL, webhooks, pagination
- Data: SQL, BigQuery, dbt, Spark basics
- Cloud: GCP (preferred at many FDE shops), AWS, Azure fundamentals
- Infrastructure: Docker, Kubernetes basics, Terraform
- AI/ML: RAG systems, LLM APIs, embeddings, vector DBs
- Observability: Prometheus, Grafana, logging best practices

**Consulting & Communication (Customer Side)**
- Discovery methodology: understand the problem before proposing a solution
- MECE framework (Mutually Exclusive, Collectively Exhaustive)
- Pyramid Principle for structured communication
- Stakeholder management: technical vs non-technical audiences
- Scope management: how to say no, how to phase work
- Case study formats: problem → hypothesis → analysis → recommendation
- C.A.S.E. diagnostic framework (Context, Approach, Solution, Evaluation)

**Common FDE Interview Scenarios**
- "Design a fraud detection system for a fintech customer"
- "A customer's Kafka pipeline is dropping messages — walk us through your debugging approach"
- "A VP wants a dashboard in 2 weeks. Their engineering team disagrees on the schema. What do you do?"
- "Demo a RAG-based Q&A system to a non-technical audience"

#### FDE Resources

- [Awesome FDE Roadmap — pierpaolo28](https://github.com/pierpaolo28/Awesome-FDE-Roadmap) — structured 10-section FDE guide
- [FDE Roadmap — thecoder8890](https://github.com/thecoder8890/forward-deployed-engineer-roadmap) — career path, portfolio, and interview breakdown
- [roadmap.sh/forward-deployed-engineer](https://roadmap.sh/forward-deployed-engineer) — visual FDE skills roadmap
- [Free 8-Week FDE Roadmap — Abhijay Vuyyuru](https://abhijayvuyyuru.substack.com/p/the-free-8-week-roadmap-to-become) — structured weekly plan
- [Learn how to build a database in C](https://cstack.github.io/db_tutorial/) — deep systems fundamentals

---

## Foundation & Core Skills

> Applies across all three tracks. Master these and every interview gets easier.

### Databases

| Topic | Key Concepts | Resources |
|---|---|---|
| SQL | Joins, window functions, CTEs, indexes | [SQLZoo](https://sqlzoo.net/), [Mode SQL Tutorial](https://mode.com/sql-tutorial/) |
| Relational DBs | ACID, normalization, query plans | PostgreSQL docs |
| NoSQL | CAP theorem, eventual consistency, use cases | MongoDB, DynamoDB docs |
| Data Warehouses | Columnar storage, partitioning | BigQuery, Snowflake docs |
| Time-series | Append-only workloads, downsampling | InfluxDB, TimescaleDB |

### Networking & Systems

| Topic | Key Concepts |
|---|---|
| HTTP/HTTPS | Request/response cycle, headers, status codes, TLS |
| DNS | Resolution chain, TTL, record types |
| TCP/IP | Handshake, reliability vs UDP tradeoffs |
| REST vs gRPC | Protocol comparison, when to use each |
| OS Basics | Processes vs threads, memory management, file systems |

### Cloud & DevOps

| Topic | Tools to Know |
|---|---|
| Containers | Docker (build, run, compose) |
| Orchestration | Kubernetes (pods, services, deployments) |
| IaC | Terraform basics |
| CI/CD | GitHub Actions, Jenkins |
| Cloud Platforms | GCP, AWS, Azure — at least one deeply |
| Observability | Prometheus, Grafana, structured logging |

---

## General Resources

### Building Things From Scratch
- [Build Your Own X](https://github.com/codecrafters-io/build-your-own-x) — build a DB, compiler, shell, git, etc.
- [Project-Based Learning](https://github.com/practical-tutorials/project-based-learning) — tutorials organized by language/topic
- [Build a DB in C](https://cstack.github.io/db_tutorial/) — deep dive into database internals

### Developer Roadmaps & Reference
- [developer-roadmap — kamranahmedse](https://github.com/kamranahmedse/developer-roadmap) — comprehensive role-based roadmaps
- [roadmap.sh](https://roadmap.sh/) — visual roadmaps for frontend, backend, devops, data, and more
- [Best Websites for Programmers](https://github.com/sdmg15/Best-websites-a-programmer-should-visit/) — curated list of essential programmer sites

### APIs & Design Tools
- [Public APIs](https://github.com/public-apis/public-apis) — free APIs to build projects with
- [Design Resources for Developers — Traversy](https://github.com/bradtraversy/design-resources-for-developers) — UI/UX tools and resources

---

## Contributing / Updating This Doc

This is a personal, living document. Suggested workflow:
1. Move items from **Ideas** → **Currently Working On** when you start
2. Move from **Currently Working On** → note the outcome (shipped, learned, abandoned + why)
3. Update the **LeetCode tracker** and **Cheatsheet** as you practice
4. Add new resources under the relevant track as you find good ones
