## Xuinnz 
Systems and Backend Development. 
### Projects

| Project | Description | Stack | Code |
| :--- | :--- | :--- | :---: |
| **SAMM** | **Stratified Autonomous Memory Manager** — Offline profile-guided allocator in Zig using `mmap` with K-Means lifetime prediction to pre-bake arena selection. Targets reduced P99 latency and peak RSS in Node.js heap within a 1 GB-constrained backend environment. | `Zig` `Python` `Node.js` | `private` |
| **Ambigui2** | **Tetromino AI Engine** — Dual-state bitboard Tetris AI with Raylib rendering. Bit-parallel collision and line-clear at sub-millisecond per-frame cost. Evolved a 6-weight Dellacherie-inspired heuristic via tournament genetic algorithm, improving average gameplay score **2.70×** across standardized seed evaluation. 750KB WASM Build via Enscripten | `Zig` `Raylib` `Genetic Algorithm` | [→](https://github.com/Xuinnz/ambigui2) |
| **Portfolio Server** | **Zero-Dependency HTTP/1.1 Server** — Built from scratch in Zig: raw POSIX sockets, event-driven core using Linux `epoll` for non-blocking async I/O. 350 KB stripped binary. Deployed on Azure VM behind a Caddy reverse proxy. | `Zig` `epoll` `Caddy` `Azure` | [→](https://github.com/Xuinnz/zig-server) |
| **GabayMed** | **Healthcare Middleware & AI Orchestration** — Two-sided AI healthcare platform. Dual-Agent RAG pipeline on Llama-3: triage agent routes patient concerns to the nearest qualified hospital via vector search; Auditor agent cross-validates against DOH guidelines. *2nd Runner-up — PUP Hackathon: Uthack ang Puhunan* | `React` `React Native` `Supabase` `Llama-3` `Vercel` | [→](https://github.com/Xuinnz/GabayMed) |
| **Tugma** | **Job Matching Platform** — Dual-sided recruitment backend with independent auth flows for job-seekers and recruiters on a shared service layer. Hash-based matching algorithm computing candidate-to-listing alignment scores in O(1). | `Python` `FastAPI` `Supabase` `Docker` | `→` |
| **r-alloc** | **Custom Memory Manager** — C memory allocator using `mmap` with a Node.js N-API bridge. Manual memory control and system-level optimization. | `C` `N-API` `Unix` | [→](https://github.com/Xuinnz/r-alloc) |
| **setra** | **Domain-Specific Language** — A DSL for discrete mathematical computation, built in C from scratch. Core foundation in sets, graphs, relations, and combinatorial logic. | `C` | `→` |
| **ChainGate** | **Decentralized Auth & Analytics** — SIWE (Sign-In with Ethereum) implementation with high-throughput session management and real-time analytics. | `Web3.js` `Redis` `Node.js` | [→](https://github.com/Xuinnz/ChainGate) |
| **Padayon** | **ACID-Compliant Booking System** — Hotel reservation engine with relational database integrity, complex querying, and concurrency handling. | `Express.js` `PostgreSQL` `Vue.js` | [→](https://github.com/Xuinnz/Padayon) |
| **DoneZO** | **Algorithmic Task Scheduler** — Custom prioritization algorithm for time-blocking: urgency decay, difficulty weights, and micro-task bonuses to balance cognitive load into daily 70-point chunks. No SQL — custom flat-file persistence, hand-rolled auth and session management. | `Java` `Java Swing` | [→](https://github.com/Xuinnz/DoneZO) |

---

### Stack

**Languages**

![Zig](https://img.shields.io/badge/Zig-F7A41D?style=flat-square&logo=zig&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)

**Frameworks & Libraries**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)

**Cloud & Infra**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=flat-square&logo=mysql&logoColor=white)
