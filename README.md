# Tanmay Joddar

Backend engineer and CS undergrad (B.Tech IT) . 
I build systems that sit at the intersection of backend infrastructure, Web3, and AI — things that are useful to run in production, not just impressive in a demo.

Currently contributing to [GreedyBear](https://github.com/intelowlproject/GreedyBear) under The Honeynet Project. GSoC 2026 applicant (Project #6 — Injection/Event Collector API).

---

### Projects

**[apidrift-cli](https://github.com/tanmayjoddar/apidrift)**  
CLI tool that snapshots API response *shapes* — field names and types, never actual data — and diffs them across versions, environments, or deploys. One command catches a `userId: string → number` before it silently breaks clients at 3am. CI-native: exits with code 1 on breaking changes, so it gates deploys without extra config. Published on npm.

**[CuraBlock](https://github.com/tanmayjoddar/CuraBlock-ETHGlobal)**  
Web3 security wallet with an AI fraud detection model scanning 18 dimensions of wallet behavior, a quadratic voting DAO (voting power = √tokens staked, so whales can't dominate), and soulbound on-chain reputation stored as Base64-encoded JSON directly in the contract — no IPFS, no server dependency. The interesting design decision: `getDAOScamBoost()` feeds community-confirmed scam addresses back into the ML model's risk scoring, so the system improves with every vote. 8 production Solidity contracts on Monad Testnet. Full-stack: React + Go (Gin) + PostgreSQL + Python/scikit-learn.

**[FloodMesh](https://github.com/tanmayjoddar/FloodMesh-Disaster-Resilient-Messaging)**  
Disaster-resilient mesh messaging that routes over Bluetooth and Wi-Fi Direct when the internet is down. E2E encrypted, offline-first, deployed to Vercel (26 production deployments).

---

## Open Source Contributions 
-Contributed to the open-source project [GreedyBear](https://github.com/intelowlproject/GreedyBear) with multiple merged pull requests focused on bug fixes, data extraction reliability, GeoIP enrichment, IOC merging logic, and testing improvements.

### Merged Pull Requests

| PR | Contribution |
|---|---|
| [#1217](https://github.com/intelowlproject/GreedyBear/pull/1217) | Fixed Cowrie timestamp parsing using `parse_timestamp()` to ensure proper session event extraction |
| [#1178](https://github.com/intelowlproject/GreedyBear/pull/1178) | Fixed GeoIP enrichment bug by scanning all hits in `iocs_from_hits()` |
| [#1010](https://github.com/intelowlproject/GreedyBear/pull/1010) | Added sorting guard in `_update_days_seen` to prevent corrupted `days_seen` ordering |
| [#1005](https://github.com/intelowlproject/GreedyBear/pull/1005) | Added test coverage for `ClusterCommandSequences.run()` |
| [#974](https://github.com/intelowlproject/GreedyBear/pull/974) | Improved IOC merging logic using proper `first_seen` and `last_seen` semantics |
| [#933](https://github.com/intelowlproject/GreedyBear/pull/933) | Propagated `firehol_categories` correctly in `_merge_iocs` |
| [#885](https://github.com/intelowlproject/GreedyBear/pull/885) | Replaced regex-based IP validation with Python `ipaddress` standard library |

### Highlights
- 7 merged pull requests
- Contributions approved and merged by project maintainers
- Worked on cybersecurity-focused backend and enrichment pipelines
- Submitted a GSoC 2026 proposal for the Injection/Event Collector API (Project #6)

🔗 View all merged PRs:  
https://github.com/intelowlproject/GreedyBear/pulls?q=is%3Apr+is%3Amerged+author%3Atanmayjoddar

---

### Stack

**Backend** — Node.js · Python (Django · DRF · FastAPI) · Go (Gin) · PHP (Laravel)  
**Infra** — Docker · Kubernetes · AWS · Redis · RabbitMQ · GitHub Actions · Nginx  
**Web3** — Solidity · OpenZeppelin · ethers.js · IPFS · Hardhat  
**DB** — PostgreSQL · MongoDB · MySQL  

---

[Email](mailto:tanmayjoddar17@gmail.com) · [LinkedIn](https://www.linkedin.com/in/tanmay-joddar-67107427a/) · [GitHub](https://github.com/tanmayjoddar) · [Twitter](https://x.com/joddar_tan8236)
