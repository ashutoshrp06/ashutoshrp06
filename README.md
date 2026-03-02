## Building systems that count nanoseconds and money

MSc AI at Edinburgh | Ex-Juniper Networks (3 years in real-time telemetry)

Currently writing code that doesn't make traders cry and teaching machines to think without exploding in production

---

### What I actually do

I spent three years at Juniper Networks making network telemetry systems that either work in microseconds or don't work at all. Real-time data processing, OpenConfig implementations, the kind of infrastructure that keeps networks running while everyone else sleeps.

Now I'm at Edinburgh learning how to make AI systems that survive production. Because brilliant research models are great until they meet actual data.

**Languages I speak fluently**

C++ when performance matters, Python when sanity matters, C when both are optional. Also Scala, Go, SQL, and whatever else the problem demands.

**Current focus**

Building trading systems and low-latency infrastructure. Writing a dissertation on automating benchmark construction for LLMs in finance. Making terminals less hostile to humans. The usual.

---

### Things I've shipped

#### **Friday + DocLM** | Featured
**AI-powered CLI for network engineers who debug infrastructure at 2am**

Production-grade debugging tool that combines a fine-tuned LLM with a fully local RAG pipeline and atomic transaction engine. Diagnoses gRPC failures, TCP tuning disasters, and kernel parameters without sending a single byte to external APIs. Four validation gates prevent hallucinations. Every destructive operation gets a dry-run, user confirmation, and automatic LIFO rollback on failure.

DocLM is the brain behind Friday. LoRA fine-tuned Qwen2.5-Coder-3B trained on network telemetry debugging, gRPC failure patterns, TCP tuning runbooks, and YANG model documentation. Now hosted on HuggingFace for anyone who wants to teach their terminal to speak infrastructure.

`Go` `vLLM` `LoRA` `RAG` `Qdrant` `ONNX`

- [GitHub (Friday)](https://github.com/rtsh13/friday)
- [Project Dashboard](https://tgifriday.vercel.app/)
- [DocLM on HuggingFace](https://huggingface.co/ashutoshrp06/DocLM)

---

#### **Limit Order Book Simulator** | Ongoing
**High-performance LOB in modern C++17 for HFT systems**

Price-time priority matching, O(1) order cancellation, integer arithmetic because floating point errors in trading systems are how you accidentally buy a small country. Cache-friendly data structures that would make an HFT firm nod approvingly. Currently optimizing memory layout and adding SIMD where it makes sense and showing off where it doesn't.

`C++17` `HFT` `Order Matching` `CMake`

- [GitHub](https://github.com/ashutoshrp06/lob-simulator)

---

#### **NASDAQ ITCH Feed Parser** | C++ Systems
**Binary market data feed parser for ITCH 5.0**

Zero-copy parsing, big-endian to little-endian byte swapping, pragma pack structs that match wire format down to the bit. Pairs with the LOB Simulator to reconstruct order books from raw exchange messages. The unglamorous plumbing that runs before your fancy trading algorithm even knows a price exists.

`C++17` `Binary Parsing` `ITCH 5.0` `CMake`

- [GitHub](https://github.com/ashutoshrp06/feed-parser)

---

#### **Multi-Strategy Algorithmic Trading System** | HackTheBurgh 2025
**Production-grade trading platform with three complementary strategies**

Built for Optiver's Challenge. Integrates ML-powered sentiment analysis (85% accuracy on financial news using TF-IDF), statistical arbitrage exploiting cross-listing inefficiencies, and adaptive market making. Complete with circuit breakers, position limits, and automated loss prevention. Because losing money quickly is easy. Losing it slowly while pretending you have a strategy is art.

`Python` `Scikit-learn` `TF-IDF` `Risk Management` `Statistical Arbitrage`

- [GitHub](https://github.com/rtsh13/hacktheburgh-xii)

---

#### **Samantha** | OpenEuler Challenge Finalist
**CLI assistant that teaches your OS to speak human**

Hybrid AI system combining Python LLM reasoning with Go compiled execution. Transforms complex CLI operations into natural language. Non-technical users can perform advanced file operations with 90% fewer commands. Self-correcting agentic workflows, content-aware search using RAG architecture with ChromaDB. Semantic search across filesystems in under 5 seconds. Reached finals at Edinburgh's Huawei-sponsored OpenEuler Challenge.

`Python` `Go` `LangChain` `ChromaDB` `RAG` `HuggingFace`

- [GitHub](https://github.com/ashutoshrp06/samantha)

---

#### **Distributed Sparse Matrix Engine** | Distributed Systems
**High-performance sparse matrix multiplication on Apache Spark**

Implements COO, CSR, and CSC formats with smart format detection. Achieved 2-10x speedup compared to Spark's MLlib. Zero driver bottlenecks, fully distributed computation, no collect() calls anywhere. The kind of project where you spend three days debugging a partitioning strategy and then pretend it was obvious all along.

`Scala` `Apache Spark` `Distributed Computing` `COO/CSR/CSC` `Tensor Ops`

- [GitHub](https://github.com/rtsh13/dune)

---

### MSc Dissertation

**Automating Benchmark Construction in the Financial Domain**

Working with Aveni on building LLM benchmarks that don't age like milk. Multi-agent systems generating evaluation data dynamically for real financial services tasks. Information extraction from call transcripts, document summarization, classification where the stakes are higher than academic bragging rights. The goal is benchmarks that evolve, stay uncontaminated, and measure things that actually matter.

*Institution* - The University of Edinburgh  
*Industry Partner* - Aveni  
*Supervisors* - Alexandra Birch-Mayne, Barry Haddow

---

### Experience highlights

**Juniper Networks** | Software Engineer II (Dec 2023 - Aug 2025)
- Engineered 5+ new data streaming features for JVision real-time telemetry platform
- Led test plan redesign for new product from clean slate
- Resolved 50+ high-priority production bugs, improved system stability by 15%

**Juniper Networks** | Software Engineer I (Aug 2022 - Nov 2023)
- Optimized C/C++ codebase, reduced memory leak instances by 20%
- Implemented and validated multiple OpenConfig YANG data models

**Juniper Networks** | Software Engineering Intern (Feb 2022 - Jul 2022)
- Designed 20+ YANG data models enabling 20+ new hardware platforms
- Built Python automation reducing version control audit time by 95%

---

### Find me elsewhere

[Portfolio Website](https://ashutoshrp06.github.io) | [LinkedIn](https://linkedin.com/in/ashutoshpatil3)

Currently in Edinburgh, occasionally in reality

---

Targeting quant dev and SDE roles at firms where microseconds matter and the coffee is probably excellent.
