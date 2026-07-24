### Hello there, I'm Ennio 💫

<!--
**EnnioEnnio/EnnioEnnio** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

🔭 **Currently Working On:**
 
- **M.Sc. Computer Science (Systems Track) @ Hasso Plattner Institute:** Master's project on optimizing the execution of recurring SQL patterns in analytical workloads (Data Engineering Systems chair).
- **Master's thesis (topic search):** Exploring LLM inference systems, attention variants, KV-cache/state management, and serving-engine internals.

🌱 **What I'm Learning:**
 
- **LLM inference internals:** paged KV caching, prefix reuse, speculative decoding and how linear/hybrid attention (Gated DeltaNet, KDA) changes the memory-management game.
- Reading my way through **vLLM and SGLang internals**, with the goal of contributing upstream.
- **Hardware-conscious data processing:** cache-aware layouts and low-level performance work in C++/Go, building on database-engine coursework.

🧪 **Selected Projects:**
 
- **[Hash vs. Sort Aggregation on Many-Core CPUs](https://github.com/hyrise/hyrise/tree/dpmh25-hash-aggregation)** (C++, Hyrise, TPC-H): a 16-variant benchmark across threading, optimization level, and group cardinality — lock-free hash tables with fuzzy ticketing, radix/counting sort, AVX2 SIMD aggregation. The classic 14× hash-vs-sort gap shrinks below 1.3× once both sides are optimized, and sort wins multi-threaded at high cardinality.
- **[luen — a search engine in Go](https://github.com/EnnioEnnio/luen-search-engine)** (Go, MS MARCO, gRPC): a full-text engine built from scratch. SPIMI-style external indexing under a ~1 GB heap budget producing a ~44 GB on-disk index over the full MS MARCO corpus, disk serving via offset-addressed postings with an LRU cache, BM25 behind a boolean/phrase query parser, and hybrid semantic search through a Python gRPC embedding service.
- **[Model Search Beyond Classification](https://github.com/EnnioEnnio/MLSys)** (PyTorch, Slurm/A100): adapted Alsatian/SHiFT-style proxy ranking to regression over a 16-encoder pool, a 5-seed regret study against a random-ranking null, plus a cost breakdown showing feature extraction dominates proxy wall-clock (73–78%).
- **[RL for Algorithm Discovery](https://github.com/EnnioEnnio/rlad_bst)** (PPO, Gymnasium): trained an agent to program a tiny VM that builds BSTs from sorted arrays. Environment design, reward shaping, and action masking mattered far more than agent architecture.

🏗️ **Past Work:**
 
- **Trade Republic (Berlin) — Platform Engineering & DevEx Intern (2025):** CI/CD reliability, Go-based compliance tooling, and AI-usage observability pipelines.
- **GDTQ (Potsdam) — Data & Software Engineering, Working Student (2021–2025):** Data pipelines and numerical optimization for quantitative trading.
- **Mount Sinai Health System (via HPI):** LLM/RAG natural-language interface to clinical records on SAP HANA.
