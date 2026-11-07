# Satyam Kumar

**Backend & Systems Software Engineer**  
Focused on high-concurrency Java backend systems, distributed messaging, and bare-metal x86 operating system development.

[LinkedIn](https://www.linkedin.com/in/satyam-kumar/) • [Email](mailto:krsatyam1002@gmail.com) • [GitHub](https://github.com/satyamk001-tech)

---

### Core Engineering Focus

- **Backend & Distributed Systems**: Java 21 (LTS), Spring Boot 3.4, PostgreSQL, Apache Kafka, Redis, Distributed Caching, Event-Driven Architecture.
- **Systems & OS Development**: C (Freestanding / C99), x86 Assembly (NASM), Protected Mode, Two-Level Paging, Interrupt Descriptor Tables (IDT), Preemptive Scheduling, VFS.
- **Infrastructure & Reliability**: Docker, Testcontainers, GitHub Actions CI/CD, Prometheus, Grafana, Linux Systems Programming.

---

### Featured Projects

#### 1. [DataFlow — Real-Time Event Ingestion & Analytics Pipeline](https://github.com/satyamk001-tech/realtime-data-pipeline)
*High-throughput event streaming and distributed batch processing engine built with Java 21, Apache Kafka, Apache Spark, and Spring Boot.*
- Ingests and validates multi-source event streams with SHA-256 cryptographic checksums and schema integrity verification.
- Implements distributed deduplication and automated data quality quarantine rules using Apache Spark.
- Features an AST-validated analytical query engine using JSqlParser to enforce read-only execution constraints.
- Backed by integration tests via Testcontainers and an automated CI pipeline.

#### 2. [ERAN OS — 32-bit x86 Protected Mode Kernel](https://github.com/satyamk001-tech/Eran-OS)
*Independent x86 operating system kernel built from scratch in freestanding C and NASM assembly.*
- Two-stage bootloader transitioning CPU from 16-bit Real Mode to 32-bit Protected Mode with A20 gate activation.
- Memory management subsystem featuring a bitmap physical frame allocator (PMM), kernel heap, and two-level paging (VMM).
- Preemptive round-robin process scheduler utilizing PIT timer interrupts and Task State Segment (TSS) stack switching.
- Custom Virtual Filesystem (VFS) with ATA PIO hard disk controller support and an interactive system shell.

#### 3. [Samvaad — Distributed Real-Time Communication Platform](https://github.com/satyamk001-tech/Samvaad)
*High-concurrency messaging and WebRTC signaling platform built on Spring Boot, PostgreSQL, Redis, and Apache Kafka.*
- WebSocket STOMP messaging with Redis Pub/Sub presence tracking and active session heartbeat management.
- Reliable event streaming utilizing the Transactional Outbox pattern to guarantee at-least-once delivery.
- Peer-to-peer WebRTC voice/video signaling with ICE/STUN/TURN NAT traversal.
- Stateless authentication with JWT, refresh token rotation, and rate-limited endpoints.

---

### Computer Science Foundations

- **Data Structures & Algorithms**: Algorithmic problem solving in Java / C++ (Arrays, Trees, Graphs, Dynamic Programming).
- **Systems & Networking**: TCP/IP stack mechanics, POSIX concurrency, memory layout, virtual memory, cache coherence.
- **Database Engineering**: ACID isolation levels, indexing strategies (B-Tree, Hash, HNSW), connection pooling, query execution plans.
