### Mihir Deshpande · [mihird94.github.io](https://mihird94.github.io)

Building local-first software, calibrated retrieval engines, and agent memory systems. Focused on transparent primitives, empirical ablations, and native performance over framework bloat.

#### Systems & AI Infrastructure

| Project | Focus |
| :--- | :--- |
| [`forma-office`](https://github.com/mihird94/forma-office) | 7 lightweight native `arm64` macOS office & notebook apps (~8.6 MB, zero Electron), local EmbeddingGemma 2 multimodal search, and a 10-tool MCP server |
| [`global-memory`](https://github.com/mihird94/global-memory) | Cross-harness local memory store — Markdown truth, SQLite FTS5, Ollama embeddings, ONNX `jina-reranker-v1-turbo-en` with a `0.25` calibrated abstention gate, and MCP |
| [`memory-systems-lab`](https://github.com/mihird94/memory-systems-lab) | 5-engine agent memory benchmark arena + from-scratch implementation of Mem0 / Mem0$^g$ (`arXiv:2504.19413`) with temporal supersession and adversarial suites |

#### Applied Science & ML

| Project | Focus |
| :--- | :--- |
| [`qwen3-text-to-sql-lora`](https://github.com/mihird94/qwen3-text-to-sql-lora) | Controlled `bf16` LoRA post-training & mechanistic diagnostics for Qwen3-4B Text-to-SQL — sandboxed SQLite grading, QR-SVD 90%-energy rank, entropy shift, and ablations |

**Active Research Labs (private while iterating):**
- **Causal ML & Uplift Modeling:** From-scratch S/T/X/R-Learners, cross-fitted Double ML, Doubly Robust OPE (AIPW / IPS / SNIPS), and Qini curves (Criteo Uplift schema).
- **Two-Stage Recommender Systems:** Time-decayed co-visitation + PyTorch Two-Tower with InfoNCE & LogQ popularity debiasing → XGBoost LambdaRank (OTTO session schema).
- **Probabilistic & Hierarchical Forecasting:** MinT-Shrinkage reconciliation, multi-quantile GBDT, and Split / CQR / Adaptive Conformal intervals under rolling-origin CV (M5 hierarchy schema).

#### Principles
- **Local-first primitives** over cloud lock-in and framework sprawl.
- **Empirical ablations & calibrated abstention** over unverified retrieval vibes.
- **Inspectable state** — plain-text files and disposable SQLite indices you can audit in seconds.
