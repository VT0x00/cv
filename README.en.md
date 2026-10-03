# Vladimir T.
**Junior Go Developer (Backend)**

Saint Petersburg | Remote | Part-time

Telegram: @vt0x00 | GitHub: github.com/VT0x00 | Email: nil

**Desired Role:** Junior Go Developer / Backend Developer

---

## Summary

Junior Go developer, currently a first-year student. Developed several Go pet projects: a distributed key-value store based on Raft and a CLI wallet for TON. Currently building the backend for a survey platform using a microservices architecture. Proficient with the `micro` framework, gRPC, Protobuf, PostgreSQL, Docker, and Prometheus.

---

## Skills

- **Languages:** Go (primary), Python, C++ (basic), Bash, SQL
- **Backend:** `micro` framework, gRPC, Protobuf (proto3), REST, microservices
- **Databases:** PostgreSQL, SQLite
- **Infrastructure:** Linux, Docker, Docker Compose, Git
- **Monitoring:** Prometheus, Grafana
- **Testing:** `go test`, table-driven tests
- **Tools:** VS Code, Helix, protoc, grpcurl, Make

---

## Projects

### DeKVS — Distributed Key-Value Store
**Stack:** Go, HashiCorp Raft, gRPC, Protobuf, PostgreSQL, Prometheus, Grafana, Docker.
**GitHub:** github.com/VT0x00/dekvs

A fault-tolerant distributed storage system featuring Raft consensus and a gRPC API. **Accomplishments:**
- Implemented a 6-node cluster featuring automatic leader election and log replication.
- Designed a gRPC service with `Put`, `Get`, and `Delete` operations, as well as batch operations.
- Configured automatic node connection to the cluster upon startup.
- Added health/status endpoints and metric collection via Prometheus.
- Prepared Grafana dashboards for cluster state visualization.
- Created a `docker-compose.yml` file to launch the entire cluster with a single command.

**Result:** The project can be deployed using `docker-compose up -d --build`; documentation covers both local and containerized execution.

---

### VyborOk — Survey and Voting Platform
**Stack:** Go 1.21+, `micro v3` (`micro-server-http/v3`), Protobuf, PostgreSQL 16, Redis (planned), NATS (planned), Docker Compose.
**GitHub:** github.com/VT0x00/VyborOk

Backend for a survey platform. Early-stage MVP: authentication is complete; surveys, voting, and statistics features are currently under development.

**Accomplishments:**
- Implemented registration, login, refresh tokens, JWT authorization, and profile retrieval.
- Designed the API using Protobuf with `micro.api.http` annotations.
- Configured database migrations and PostgreSQL interaction via `make migrate-up`.
- Implemented public and private profiles using an `is_private` field and companion `*_set` fields for proto3 compatibility.
- Set up infrastructure using Docker Compose (Postgres, Redis, NATS). - Documented the API in the README, including `curl` request examples for each endpoint.

**Result:** The server starts via the `make run` command, a health check is available at `/health`, and all key endpoints are documented.

---

### TonVault — CLI wallet for TON
**Stack:** Go, TON blockchain SDK.
**GitHub:** github.com/VT0x00/TonVault

A feature-rich CLI wallet for managing wallets on the TON network.

**What I did:**
- Implemented wallet management, token transfers, and transaction history viewing.
- Built a CLI interface for interacting with the blockchain.

---

### bookserver-micro — microservice-based online library backend
**Stack:** Go, `micro`.
**GitHub:** github.com/VT0x00/bookserver-micro

An educational project for practicing microservice architecture using the `micro` framework.

---

## Open Source / Activity

- GitHub profile: 164 contributions over the past year.
- Public projects: `dekvs`, `VyborOk`, `TonVault`, `bookserver-micro`, etc.

---

## Education

**Secondary education.** Currently a first-year student at BSTU "VOENMEH" named after D.F. Ustinov.

---

## Additional Information

- English: Intermediate level — able to read technical documentation.
<!-- - Open to remote work and flexible schedules. -->
- Interests: Distributed systems, blockchain, microservices.
