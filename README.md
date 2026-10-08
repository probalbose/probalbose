### Hi, I'm Probal 👋

Principal Site Reliability Engineer in Dublin. I run reliability for real-time ML inference in payments: over a billion transactions a day, with SLOs, observability and incident response for systems where failure reaches people fast. I'm also a PhD candidate at University College Dublin, studying cryptocurrency limit-order-book microstructure with Hawkes processes, information theory and echo state networks.

🌐 [probalbose.com](https://probalbose.com) · 💼 [LinkedIn](https://www.linkedin.com/in/probal-bose-principal-site-reliability-engineer)

#### What's here

- **[SafeGuard](https://github.com/probalbose/safeguard)**: real-time content-safety decisioning built on production fraud-detection architecture. It runs a layered pipeline (enrichment, deterministic rules, a gated classifier and a pure policy function) and returns allow / review / block verdicts with reason codes. Failed stages degrade toward human review, shadow mode tests new policies on live traffic, and decision events stream to an audit trail. Python, FastAPI, Redis, Kafka.
- **[Reading the Greek](https://probalbose.com/books/reading-the-greek/)**: my book on mathematical notation, in paperback and on Kindle. One source produces both editions (Quarto and XeLaTeX for print, a custom EPUB pipeline for Kindle), and every code listing is executed and checked against the printed output.
- **[lob-continuity](https://github.com/probalbose/lob-continuity)**: a typed Python library that detects silent sequence-continuity gaps in limit-order-book update streams and marks invalid segments instead of interpolating across them. Built for my PhD order-book data pipeline.
- **[jsonlz](https://github.com/probalbose/jsonl-compress)**: a lossless compressor for order-book JSONL archives in pure Python. It uses order-book-aware transforms and its own entropy coder, and reaches about 16× on BTCUSDT depth captures versus about 8× for gzip -9.
- **[Parallax](https://github.com/probalbose/parallax)**: a paired Python and Rust lab for measuring what LLM training actually costs on real hardware. Early stage, open to contributors.
- **[probalbose.com](https://github.com/probalbose/probalbose.com)**: my personal site, plain static HTML built with a small Python script.

#### In preparation

- **Order-book research pipeline**: live ingestion of 13 Binance pairs into TimescaleDB, with order-book reconstruction, instrumented with eBPF and OpenTelemetry. Public release in preparation.

#### Toolbox

Python · Rust · C++ · SQL · Kubernetes · Prometheus / Grafana · OpenTelemetry · eBPF · Kafka · TimescaleDB · MCP / LLM systems
