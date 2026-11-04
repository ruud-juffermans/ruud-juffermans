<h1 align="center">Hi, I'm Ruud</h1>

<p align="center">
  Data & AI Engineer · Amsterdam, NL · open to new roles
</p>

<p align="center">
  <a href="https://ruudjuffermans.nl">Website</a> ·
  <a href="https://ai.ruudjuffermans.nl">Ask my digital twin</a> ·
  <a href="https://www.linkedin.com/in/r-j3">LinkedIn</a> ·
  <a href="https://github.com/datavakwerk">Project code (datavakwerk)</a>
</p>

---

I build modeled data warehouses, tested pipelines and AI systems that only say what they can prove. Most of that work has been in environments where confidential and privacy-sensitive data is the norm: the Dutch National Police and the Netherlands Aerospace Centre (NLR).

## What I'm doing now

- **Data Specialist at the Dutch National Police (Noord-Holland)** since March 2025. Set up data-driven working in a team that didn't have it yet: pipelines in Python and SQL, dimensional models, Power BI reports, and automated tooling for financial and cryptocurrency investigations.
- Before that, **Data Engineer at NLR** on COMPASS, an EU project on digital product passports. Requirements engineering with partners across Europe, data platform architecture, dbt and Power BI.
- Four years making **Udemy courses** on Python, SQL, full-stack development and Hyperledger Fabric (241 students, 4.2/5).

## Projects

All code is public under [@datavakwerk](https://github.com/datavakwerk). Every project runs from an empty directory with one command and has tests and lint in CI.

| Project | What it is | Stack |
| --- | --- | --- |
| [digital-twin](https://github.com/datavakwerk/digital-twin) | LangGraph agent that answers questions about me with sources, streams over SSE, refuses without evidence, and asks for human approval before acting. [Try it live.](https://ai.ruudjuffermans.nl) | Python, FastAPI, LangGraph, Postgres + pgvector, React |
| [strafrecht-rag](https://github.com/datavakwerk/strafrecht-rag) | RAG over 1,906 Dutch criminal-law rulings. Hybrid retrieval (BM25 + embeddings, RRF, cross-encoder rerank) and per-claim citation verification in code. No source, no answer. | Python, SQLite + FTS5, fastembed, Ollama / Claude |
| [nl-vehicle-warehouse](https://github.com/datavakwerk/nl-vehicle-warehouse) | Kimball star schema on ~58M rows of Dutch open vehicle data (RDW + CBS). Three documented grains, SCD type 2 municipalities, custom grain tests on every PR. | Python, dbt, DuckDB, Evidence, GitHub Actions |
| [ov-streaming-pipeline](https://github.com/datavakwerk/ov-streaming-pipeline) | Real-time delay analytics on ~4,900 Dutch public-transport vehicles. Five-minute windows, per-partition watermarks, at-least-once with idempotent sinks, dead-letter queue and replay. 13 containers, zero cost. | Python, Kafka (Redpanda), Postgres, MinIO, Grafana, Streamlit |
| [ruudjuffermans-portfolio](https://github.com/ruud-juffermans/ruudjuffermans-portfolio) | This site: bilingual NL/EN, MDX write-ups, Lighthouse 90+, CLS 0. | Next.js 15, React 19, MUI, next-intl |

## Toolbox

**Data:** Python, SQL, dbt, DuckDB, PostgreSQL, Kafka / Redpanda, Parquet, MinIO, Power BI, data modelling
**AI:** LangGraph, LangChain, RAG, pgvector, fastembed, cross-encoders, evals in CI, LangFuse
**Engineering:** FastAPI, TypeScript, React, Next.js, Docker Compose, GitHub Actions, Prometheus, Grafana
**Also:** on-chain forensics, Hyperledger Fabric, Solidity

---

<p align="center">
  📫 <a href="https://ruudjuffermans.nl/contact">Get in touch</a> · Dutch (native) · English (fluent)
</p>

