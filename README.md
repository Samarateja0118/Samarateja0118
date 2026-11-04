# Samarateja Reddy Gutta

Software engineer with 1.5 years of experience building backend and distributed systems. M.S. in Computer Science (Machine Intelligence & Cognition), The George Washington University, May 2026. Based in Washington, D.C. — open to SDE / Backend / AI roles across the U.S. and remote.

At YuppTV I built and operated an event-driven pipeline with Apache Kafka and Amazon SQS ingesting 500,000+ telemetry events per day with zero message loss, shared the on-call rotation for a platform with 10,000+ daily active users, and raised CI test coverage from 55% to 88%.

**[Portfolio](https://portfolio-v2-ecru-beta.vercel.app/)** · **[LinkedIn](https://www.linkedin.com/in/samarateja-reddy)** · **[Email](mailto:samarateja18@gmail.com)**

## Featured projects

Every README below leads with numbers I measured and says plainly what was not measured.

| Project | What it shows | Stack |
|---|---|---|
| **Portico** · [porticointake.com](https://porticointake.com) (private repo) | Multilingual (English/Spanish/French) AI intake and scheduling for immigration law firms: a Claude agent with strict-schema tools books consultations from real calendar availability; 327 test functions in CI | Python, FastAPI, Next.js, PostgreSQL, Anthropic API |
| **[GPU Job Scheduler](https://github.com/Samarateja0118/gpu-scheduler-platform)** | Priorities, preemption and tenant quotas cut critical-job p95 wait from 142.8 to 2.9 min vs FIFO; 150/150 jobs survived node and scheduler kills on k3s; canary auto-rollback in 32 s (GPUs are simulated) | Go, Kubernetes, Helm, Prometheus, Grafana, Terraform, Ansible |
| **[RAG over SEC Filings](https://github.com/Samarateja0118/rag-eval-system)** | Hybrid BM25 + dense search with a cross-encoder reranker over 12,013 pages of FinanceBench filings: Recall@5 0.340 → 0.540, with bootstrap confidence intervals and a failure analysis | Python, ONNX, llama.cpp, FastAPI, Redis |
| **[Multi-Agent Research Platform](https://github.com/Samarateja0118/agentic-research-platform)** | Multi-agent researcher, MCP server, sandboxed CI-triage agent, and the eval harness around them; CI blocks prompt changes that regress. Finding: multi-agent did not beat single-agent at 3x the cost | Python, MCP, Docker, Anthropic SDK |
| **[Streaming + ELT Data Platform](https://github.com/Samarateja0118/data-platform)** | Exactly-once Postgres sink verified through five mid-stream SIGKILLs over 525,722 messages; stream totals reconciled against a dbt batch recount | Redpanda (Kafka API), Python, dbt, Airflow 3, PostgreSQL |
| **[Supply-Chain Deployment Kit](https://github.com/Samarateja0118/fde-supply-chain-platform)** | Document extraction with a 3-way match that auto-approved 0 wrong documents on unseen layouts; demand forecasting and MILP allocation on real retail data; legacy CSV/EBCDIC/REST intake | Python, pdfplumber, LightGBM, SciPy HiGHS, FastAPI |
| **[Distributed Object Storage](https://github.com/Samarateja0118/distributed-object-storage)** | S3-style multi-tenant object store (~11,000 lines, ~113 tests): SHA-256 content-addressed chunks over bidirectional gRPC, JWT tenant isolation, 12 ADRs | Java 21, Spring Boot, gRPC, PostgreSQL, Flyway |
| **[Access AI Gateway](https://github.com/Samarateja0118/access-ai-gateway)** | LLM gateway over a multi-tenant access-control system, with guardrails and an adversarial test suite for indirect prompt injection and cross-tenant exposure | TypeScript, Express, PostgreSQL, MCP |
| **[MLB Projections](https://github.com/Samarateja0118/mlb-player-projections)** + **[MLOps Pipeline](https://github.com/Samarateja0118/mlb-mlops-pipeline)** | Hierarchical Bayesian projections (PyMC, ported to Stan, replicated in R) backtested against Marcel; MLflow registry, bootstrap promotion gate and drift monitoring replayed over 2012-2025 | Python, PyMC, Stan, R, MLflow |

**Also:** [Polymarket forecasting benchmark for LLMs](https://github.com/Samarateja0118/polymarket-forecast-bench) · [TradeWatch trade-policy monitor](https://github.com/Samarateja0118/tradewatch) · [Movie MCP server](https://github.com/Samarateja0118/movie-mcp-server) · [CSV analyst chat](https://github.com/Samarateja0118/Ai-data-agent-for-NLP) · [EEG sleep microstructure research](https://github.com/Samarateja0118/sleep-deprivation-project)

## Tech I work with

Python · Java 21 · Go · TypeScript · SQL · Apache Kafka · Amazon SQS · FastAPI · Spring Boot · PostgreSQL · Redis · Docker · Kubernetes · Helm · Terraform · Prometheus · Grafana · dbt · Apache Airflow · MLflow · Amazon Web Services (AWS) · GitHub Actions · Large Language Models (LLM) · Model Context Protocol (MCP)
