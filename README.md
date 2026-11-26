# Terrence Ye Yang

**AI Developer & Applied Researcher** — *Building AI systems that know the edge of their own knowledge.*

🌐 **Homepage & Portfolio:** [**terrenceyeyang.github.io ↗**](https://terrenceyeyang.github.io/) &nbsp;·&nbsp; ✉️ **Contact:** [**terrence.ye.yang@gmail.com**](mailto:terrence.ye.yang@gmail.com)

---

I split my time between applied AI research and hands-on systems engineering. My work centers on **agentic retrieval** for high-accountability domains where a confident wrong answer is costly, **hardware-honest benchmarking** across LLM runtimes and CUDA/SIMD kernels, and **evidence-bound software** that surfaces uncertainty and propagates real failure states instead of masking them.

> **For AI Agents (MCP):** My homepage is also served directly over the Model Context Protocol (`list_projects`, `get_project`, `search`, `homepage://news`) — see [`TerrenceYeYang.github.io/mcp`](https://github.com/TerrenceYeYang/TerrenceYeYang.github.io/tree/main/mcp).

### Recent Dispatches & Open-Source Contributions

- **2026-11 · [Upstream Merged — Tencent/WeKnora #5955](https://github.com/Tencent/WeKnora/pull/5955)** *(38k+ ★)*  
  Scoped PostgreSQL/`pgvector` HNSW compatibility retries in `VectorRetrieve` strictly to `SET LOCAL` failure paths so `BEGIN`, query, or `COMMIT` errors mentioning an HNSW parameter are never overwritten by fallback queries (`+147/−4`, deterministic red/green SQL-mock regression suite).
- **2026-11 · [Release — bwxPixel v0.2.0](https://github.com/TerrenceYeYang/bwxPixel-public/releases/tag/v0.2.0)** · **[RTX 5080 Benchmark Report](https://github.com/TerrenceYeYang/bwxPixel-public/blob/master/docs/BENCHMARK_RTX5080.md)**  
  Multi-arch (`sm_75`–`sm_120`) Windows x64 C ABI DLL for ultra-low-latency pixel conversion — sustaining **4.90 TB/s** (`8.47 µs` at 4K) in hot L2 via CUDA Graph, **902.2 GB/s** (`94.0%` of GDDR7 peak) across a `>512 MiB` cold ring, and **760.9 GB/s** on an AVX2 + non-temporal CPU baseline, verified bit-exact across all `16,777,216` RGB combinations.
- **2026-08 · [Release — OCC v1.0 Binary Preview](https://github.com/TerrenceYeYang/occ-benchmark/releases/tag/v1.0.0)**  
  Reusable screen-to-camera optical transport core with erasure recovery, integrity verification, stable C ABI, and strictly separated physical-device vs. simulator benchmark claims.

### Selected Work

| Project | Focus | Links |
| :--- | :--- | :--- |
| **[PossOnto](https://terrenceyeyang.github.io/#proj-possonto)** | Graph-navigating Agentic RAG with explicit abstention & auditability for regulated domains | [Repo](https://github.com/TerrenceYeYang/PossOnto) · [Overview](https://terrenceyeyang.github.io/#proj-possonto) |
| **[AI-Z](https://terrenceyeyang.github.io/#proj-aiz)** | Desktop benchmark dashboard measuring TTFT, tokens/s, and telemetry across local & cloud LLM runtimes | [Repo](https://github.com/TerrenceYeYang/AI-Z) · [Overview](https://terrenceyeyang.github.io/#proj-aiz) |
| **[ChipSpot Cloud](https://terrenceyeyang.github.io/#proj-chipspot)** | Zero-key B2B component sourcing gateway binding exact part numbers to official QVL/AVL evidence | [Live](https://app.chipspot.workers.dev) · [Overview](https://terrenceyeyang.github.io/#proj-chipspot) |
| **[OCC](https://terrenceyeyang.github.io/#proj-occ)** | Screen-to-camera optical communication core with erasure coding and provenance verification | [Repo](https://github.com/TerrenceYeYang/occ-benchmark) · [v1.0 Binary](https://github.com/TerrenceYeYang/occ-benchmark/releases/tag/v1.0.0) |
| **[bwxPixel](https://terrenceyeyang.github.io/#proj-bwxpixel)** | Blackwell CUDA & AVX2 SIMD pixel-processing library with separated cache/DRAM/PCIe benchmarks | [Public Repo](https://github.com/TerrenceYeYang/bwxPixel-public) · [v0.2 Binary](https://github.com/TerrenceYeYang/bwxPixel-public/releases/tag/v0.2.0) |
| **[EVO DNA Atlas](https://terrenceyeyang.github.io/#proj-evo)** | Public evidence repository and reproducible validation atlas for initialization priors | [Atlas](https://terrenceyeyang.github.io/EVO/) · [Repo](https://github.com/TerrenceYeYang/EVO) |
| **[AICANNOT](https://terrenceyeyang.github.io/#proj-aicannot)** & **[Human-Z](https://terrenceyeyang.github.io/#proj-humanz)** | Community catalog and benchmark threads tracking tasks at the boundary of machine capability | [Live](https://thingsaicantdo.vercel.app/) · [Discussions](https://github.com/TerrenceYeYang/Human-Z/discussions) |

---

📬 Research collaborations, technical inquiries, or benchmark discussions: **[terrence.ye.yang@gmail.com](mailto:terrence.ye.yang@gmail.com)** · **[terrenceyeyang.github.io](https://terrenceyeyang.github.io/)**
