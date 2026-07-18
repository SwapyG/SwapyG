# Swapnil Gaikwad

**Software Engineer | Backend, AI Infrastructure, and Verification Systems**

I design and build production-grade AI systems end to end: distributed backends,
deterministic verification pipelines, and performance-optimized inference. My current
work is Helmric, a verification and accountability layer for AI agents, built solo
across four codebases in Python and Rust.

[LinkedIn](https://www.linkedin.com/in/swapyg/) | [Email](mailto:swapnilg768@gmail.com) | [Helmric](https://helmric.com/)

---

## Featured Project: Helmric

**A verification and governance layer for AI agents.** Helmric checks what an agent
says or does against human-approved rules and source evidence, halts violations for a
named reviewer, and produces cryptographically signed records an auditor can verify
offline, without trusting the platform.

- Deterministic claim-level verification engine (DeBERTa-v3 NLI, int8 quantized):
  validated on 101 real-world grounding failures at a 97.2% catch rate and 100% precision
- Distributed backend in Python (FastAPI, PostgreSQL, Redis) deployed across AWS,
  Heroku, Railway, and Vercel, with a public SDK and REST APIs
- Desktop client security core in Rust (Tauri v2): native Ed25519 signature
  verification proven byte-identical with the Python signing service
- OpenAI-compatible gateway routing to local models first, escalating only verified
  failures: load-tested at 128 requests/minute with zero errors, a 240-request
  concurrent flood fully drained, and a 200x worst-case latency improvement
- Signed, replayable audit records with Merkle-rooted conformance proofs and a
  standalone offline verifier
- Selected for LaunchLAB AI, LaunchPad AI (Bloom), and the Boab AI cohort

**Live:** [helmric.com](https://helmric.com/)

---

## Core Expertise

**Systems and Backend:** Python, Rust, FastAPI, async architecture, REST APIs,
event-driven systems, background workers, multi-tenant API design

**AI Systems:** LLM integration, AI agents, RAG pipelines, NLI-based verification,
structured outputs

**Infrastructure:** PostgreSQL, Redis, SQLite, AWS, Docker, Linux

**Security and Verification:** Ed25519 signing, Merkle proofs, tamper-evident
ledgers, fail-closed design

**Performance Engineering:** CUDA C++, TensorRT, Metal / Core ML, int8 quantization,
memory optimization

---

## Engineering Projects

**GPU-Optimized Diffusion Model (CUDA / TensorRT)**
Custom CUDA kernels for a 2-3x speedup over the PyTorch baseline, 40% VRAM reduction
during training, and 5x inference acceleration via NVIDIA TensorRT in a containerized
deployment.

**Apple Silicon Optimization (Metal / Core ML)**
Ported a CUDA-based diffusion model to Metal and Core ML with custom kernels,
achieving a 2x inference speedup on the Apple Neural Engine; resolved native
memory-corruption faults across the Python/C++/Objective-C boundary.

**Acoustic Traffic Monitoring (Edge AI)**
Spiking Neural Network for low-power acoustic classification: 87% accuracy under
edge constraints, with a quantization-aware training pipeline.

**Real-Time Fraud Detection Pipeline (Kafka / Spark)**
Event-driven streaming architecture on AWS EMR using Apache Kafka, Spark Streaming,
and HBase, classifying transactions as genuine or fraudulent in near real time.

---

## How I Work

- Real systems, not prototypes: everything above is deployed and measured
- Fail-closed by default: no output is presented as verified without a checked signature
- Every performance figure is a measurement, not an estimate
- End-to-end ownership: backend, infrastructure, AI, and the client

---

## Contact

[LinkedIn](https://www.linkedin.com/in/swapyg/) | [Email](mailto:swapnilg768@gmail.com)
