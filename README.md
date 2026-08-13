# Pete Royce

**Applied AI / LLM Systems Engineer** at HappiDost.ai. Freelance AI & ML engineer since 2023.
I build the infrastructure layer under LLM products — durable agent runtimes, retrieval engines, evaluation harnesses — plus the ML pipelines and platforms around them.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pete-royce-saldanha/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/peteroyce)

```text
Focus     durable execution for agents · hybrid retrieval · LLM evaluation · MLOps
Flagship  keel — journal every step, resume after a crash, cap the spend, replay the trajectory
Working   Python · TypeScript · FastAPI · Next.js · PostgreSQL · Claude API · MCP
```

---

## Tech

| | |
|---|---|
| **LLM systems** | Claude API, OpenAI API, MCP, RAG pipelines, agent runtimes, OpenTelemetry |
| **ML / AI** | PyTorch, HuggingFace Transformers, scikit-learn, XGBoost, LightGBM, SHAP, Optuna |
| **MLOps** | MLflow, Docker, GitHub Actions, Prometheus |
| **Languages** | Python, TypeScript, JavaScript, Kotlin, Rust, Solidity |
| **Backend** | FastAPI, Node.js, Express, SQLAlchemy, Prisma, Drizzle |
| **Data** | PostgreSQL, MongoDB, Redis, ChromaDB, SQLite, pandas |

---

## LLM infrastructure

| Project | What it does |
|---------|-------------|
| **[keel](https://github.com/peteroyce/keel)** | **Durable runtime for LLM agents.** Journals every model and tool call *before* executing it, so a run survives process death and resumes where it stopped. Budgets are enforced pre-flight rather than discovered on the invoice, and recorded traces replay offline in CI to catch behavioural regressions. Deterministic parallel fan-out, MCP-native tool registry, OTel spans, pluggable JSONL/Postgres journals. |
| [nexusearch](https://github.com/peteroyce/nexusearch) | Hybrid neural search — BM25 inverted index plus HNSW vector ANN, RRF and convex fusion, cross-encoder and Claude reranking, MMR diversification, NDCG/MRR evaluation with paired-t significance testing |
| [evalkit](https://github.com/peteroyce/evalkit) | LLM evaluation framework — LLM-as-judge, Elo ratings, async batch scoring, multi-provider across OpenAI, Anthropic and any OpenAI-compatible endpoint |
| [devscope-mcp](https://github.com/peteroyce/devscope-mcp) | MCP server giving Claude live access to a GitHub workspace — PR reviews, issue triage, repo search, digest reports |
| [paperwise](https://github.com/peteroyce/paperwise) | PDF question answering over a RAG pipeline, with exact page-level citations (Claude + ChromaDB) |

## ML & data science

| Project | What it does |
|---------|-------------|
| [trustrank](https://github.com/peteroyce/trustrank) | Entity reputation and trust scoring — multi-dimensional Bayesian updating, manipulation detection (CUSUM, coordination and reciprocal-network checks), trust-graph propagation via Louvain and Katz centrality, per-signal explainability |
| [spectral](https://github.com/peteroyce/spectral) | Real-time time-series anomaly detection — six detectors (Z-score, MAD, Grubbs, isolation forest, spectral-residual FFT, LSTM autoencoder) behind one ensemble, with WebSocket streaming |
| [nonprofit-risk-model](https://github.com/peteroyce/nonprofit-risk-model) | XGBoost classifier predicting IRS revocation of nonprofit tax-exempt status, trained on 1.8M public IRS records with SHAP explainability |
| [medscan](https://github.com/peteroyce/medscan) | PubMedBERT fine-tuned to classify the rhetorical role of sentences in medical abstracts — **89.1% accuracy**, against 82.8% for the best TF-IDF baseline |
| [mlflow-credit-risk](https://github.com/peteroyce/mlflow-credit-risk) | Credit-risk pipeline with Optuna hyperparameter tuning, MLflow experiment tracking and model registry, SHAP explanations |
| [driftwatch](https://github.com/peteroyce/driftwatch) | Production ML monitoring — data drift, concept drift, prediction anomalies and feature-importance shift, with REST API, CLI and alerting |
| [docminer](https://github.com/peteroyce/docminer) | Document intelligence pipeline — OCR, layout analysis and NER turning PDFs and scans into structured data |
| [clipsearch](https://github.com/peteroyce/clipsearch) | Multi-modal semantic search over images and text using CLIP embeddings |

## Platforms & full-stack

| Project | What it does |
|---------|-------------|
| [orbit-crm](https://github.com/peteroyce/orbit-crm) | White-label AI-powered CRM — FastAPI, Next.js, PostgreSQL and Redis, deployed via Terraform modules for ECS and ElastiCache |
| [thavare](https://github.com/peteroyce/thavare) | Production Ayurvedic skincare storefront — Next.js 16, Drizzle ORM, Razorpay payments, Shiprocket fulfilment with retry cron, Playwright E2E |
| [CharityGuard](https://github.com/peteroyce/CharityGuard) | Charity fraud detection — AI risk scoring against 559K IRS nonprofit records, with donations recorded on an Ethereum Solidity contract |
| [ledgr](https://github.com/peteroyce/ledgr) | Double-entry personal-finance REST API — accounts, multi-currency conversion, recurring rules, spending analytics |
| [kuration](https://github.com/peteroyce/kuration) | Semantic bookmark API — links embedded at save time, so they are retrievable by meaning rather than by title text |
| [wavechat](https://github.com/peteroyce/wavechat) | Self-hostable real-time chat — named rooms, presence, typing indicators, reactions and persisted history over one Socket.IO connection |

## Tools & apps

| Project | What it does |
|---------|-------------|
| [snipd](https://github.com/peteroyce/snipd) | Local-first CLI snippet manager — tag, full-text search and copy snippets from a single SQLite database |
| [logsense](https://github.com/peteroyce/logsense) | Terminal-native log intelligence — parses arbitrary formats, clusters error patterns, detects anomalies, fires Slack alerts |
| [JatreNammaPride](https://github.com/peteroyce/JatreNammaPride) | Android guide to Karnataka's traditional Jatres — Kotlin, Jetpack Compose, MVVM, Firebase |
| [deepgram-voice-to-text-tauri](https://github.com/peteroyce/deepgram-voice-to-text-tauri) | Cross-platform desktop real-time transcription — Tauri 2, React, TypeScript, Rust |

---

## Open source contributions

[FastAPI](https://github.com/fastapi/fastapi) · [SHAP](https://github.com/shap/shap) · [Chroma](https://github.com/chroma-core/chroma) · [Deepgram JS SDK](https://github.com/deepgram/deepgram-js-sdk) · [MCP Servers](https://github.com/modelcontextprotocol/servers) · [UiPath Python](https://github.com/UiPath/uipath-python)
