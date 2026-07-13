# Networking & Systems

← [Home](../README.md)

---

## Networking

| Topic | Key Concepts |
|---|---|
| HTTP/HTTPS | Request/response cycle, methods, headers, status codes, TLS handshake |
| DNS | Resolution chain (recursive resolver → root → TLD → authoritative), TTL, A/CNAME/MX records |
| TCP/IP | 3-way handshake, reliability, flow control, vs UDP tradeoffs |
| REST vs gRPC | JSON + HTTP/1.1 vs Protobuf + HTTP/2; when to choose each |
| WebSockets | Persistent bidirectional connection; use cases (chat, live feeds) |
| CDN | Edge caches, cache invalidation, origin pull vs push |
| Load Balancing | Round-robin, least connections, sticky sessions, L4 vs L7 |

## Operating Systems

| Topic | Key Concepts |
|---|---|
| Processes vs Threads | Memory isolation, context switching, GIL in Python |
| Concurrency | Mutexes, semaphores, deadlock, race conditions |
| Memory | Stack vs heap, virtual memory, paging |
| File Systems | inodes, file descriptors, buffered vs direct I/O |
| Signals | SIGKILL, SIGTERM, SIGHUP — how processes handle shutdown |

## What Happens When You Type google.com

> A classic interview question. Know this end to end.

1. Browser checks cache (local, OS, router)
2. DNS resolution → IP address
3. TCP connection (3-way handshake)
4. TLS handshake (for HTTPS)
5. HTTP GET request sent
6. Server processes, returns response
7. Browser parses HTML, fetches sub-resources (CSS, JS, images)
8. Page renders

Reference: [github.com/alex/what-happens-when](https://github.com/alex/what-happens-when)

## Notes
<!-- Add your own observations, gotchas, or summaries here -->
- 
