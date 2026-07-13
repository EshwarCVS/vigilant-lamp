# Databases

← [Home](../README.md)

---

## Core Concepts

| Topic | Key Concepts | Go-to Resource |
|---|---|---|
| SQL | Joins, window functions, CTEs, indexes, query plans | [SQLZoo](https://sqlzoo.net/), [Mode SQL Tutorial](https://mode.com/sql-tutorial/) |
| Relational DBs | ACID, normalization (1NF–3NF), transactions | PostgreSQL docs |
| NoSQL | CAP theorem, eventual consistency, document/key-value/column/graph types | MongoDB, DynamoDB docs |
| Data Warehouses | Columnar storage, partitioning, clustering | BigQuery, Snowflake, Redshift docs |
| Time-series | Append-only workloads, downsampling, retention | InfluxDB, TimescaleDB |

---

## SQL Patterns to Know

- `GROUP BY` + aggregates (`COUNT`, `SUM`, `AVG`, `MAX`)
- Window functions: `ROW_NUMBER()`, `RANK()`, `LAG()`, `LEAD()`, `PARTITION BY`
- CTEs (`WITH` clauses) for readable multi-step queries
- Self-joins and correlated subqueries
- Index usage and when the query planner ignores them
- `EXPLAIN` / `EXPLAIN ANALYZE` to read query plans

## When to Use What

| Workload | Use |
|---|---|
| Transactional (OLTP) | PostgreSQL, MySQL |
| Analytical (OLAP) | BigQuery, Snowflake, Redshift |
| Key-value / cache | Redis, DynamoDB |
| Document store | MongoDB |
| Graph traversal | Neo4j |
| Full-text search | Elasticsearch |

## Notes
<!-- Add your own observations, gotchas, or summaries here -->
- 
