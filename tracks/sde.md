# Software Development Engineer (SDE)

← [Home](../README.md)

---

## Interview Process

| Round | What's Tested | Notes |
|---|---|---|
| Recruiter Screen | Background, compensation, motivation | Know your resume cold; have a comp range ready |
| Technical Screen | DS&A (1–2 problems), sometimes take-home | Usually 45–60 min on a shared editor |
| Onsite Loop (3–5 rounds) | Coding, System Design, Behavioral | Depth depends on level — see table below |

---

## Round Depth by Experience Level

| Experience | Coding | System Design | Behavioral |
|---|---|---|---|
| New Grad / 0–2 yrs | Medium LC, core DS&A | Basic design (URL shortener, chat) | Culture fit, learning agility |
| Mid-level / 3–6 yrs | Medium–Hard LC, OOP | Distributed systems basics | Ownership, scope, impact |
| Senior / 7+ yrs | Architecture tradeoffs > raw LC | Large-scale design, ambiguity handling | Leadership, cross-functional influence |

---

## Topics to Study

### Data Structures & Algorithms

- Arrays, Strings, Hashmaps
- Trees (Binary Tree, BST, Trie)
- Graphs (BFS, DFS, Topological Sort, Union-Find)
- Heaps / Priority Queues
- Dynamic Programming (1D, 2D, interval, knapsack)
- Sliding Window, Two Pointers, Binary Search
- Backtracking
- Sorting & Searching

### System Design

- Horizontal vs Vertical Scaling
- Load Balancers, CDNs, DNS
- SQL vs NoSQL — when to use each
- Caching (Redis, Memcached, CDN layers)
- Message Queues (Kafka, SQS, RabbitMQ)
- Consistent Hashing, Sharding, Replication
- CAP Theorem, BASE vs ACID
- Rate Limiting, API Gateway
- Common problems: URL shortener, Twitter feed, Dropbox, YouTube, Uber

### Behavioral

- STAR format (Situation, Task, Action, Result)
- Leadership principles (especially for Amazon)
- Conflict resolution, ambiguous situations, failure/learning stories

---

## Resources

- [Tech Interview Handbook — Yangshun Tay](https://github.com/yangshun/tech-interview-handbook) — most complete end-to-end SDE prep guide
- [System Design Primer — Donnemartin](https://github.com/donnemartin/system-design-primer) — canonical system design reference
- [SDE Interview & Prep Roadmap — aasthas2022](https://github.com/aasthas2022/SDE-Interview-and-Prep-Roadmap) — checklist-style across 10 domains
- [What Happens When — alex](https://github.com/alex/what-happens-when) — deep dive into "what happens when you type google.com"
- [Build Your Own X — codecrafters](https://github.com/codecrafters-io/build-your-own-x) — build interpreters, DBs, git, etc. from scratch
- [roadmap.sh/backend](https://roadmap.sh/backend) — backend skills visual roadmap
- [NeetCode](https://neetcode.io/) — curated LC problem sets by pattern

---

## LeetCode Tracker (Grind 100)

| Pattern | Problem | Difficulty | Status |
|---|---|---|---|
| Hashmaps | [Two Sum](https://leetcode.com/problems/two-sum?envType=problem-list-v2&envId=xoqag3yj) | Easy | |
| Sliding Window | | | |
| Binary Search | | | |
| Trees | | | |
| Graphs | | | |
| Dynamic Programming | | | |
| Backtracking | | | |
| Heaps | | | |

---

## System Design Cheatsheet

| Concept | One-liner | Go-to tool |
|---|---|---|
| Load Balancer | Distributes traffic across servers | Nginx, AWS ALB |
| CDN | Caches static assets closer to users | Cloudflare, Akamai |
| Message Queue | Decouples producers from consumers | Kafka, SQS |
| Cache | Reduces DB load for hot reads | Redis (cache-aside pattern) |
| Sharding | Horizontal partitioning of a database | Consistent hashing |
| Rate Limiting | Protects services from traffic abuse | Token bucket, leaky bucket |
