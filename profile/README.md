# 🏥 MedMemory AI Ecosystem

Welcome to the official open-source home of **MedMemory AI**! We are building a private, local-first intelligent framework designed to transform scattered, complex medical records into clean, queryable lifelong health timelines.

Our core mission is complete clinical data privacy—processing sensitive medical health data entirely on local devices using advanced RAG pipelines.

---

## 🗺️ System Architecture Overview

MedMemory AI is decoupled into specialized, independent modules:

*   **[docs](https://github.com/MedMemory-AI/docs)**: Centralized technical specifications, architecture diagrams, database designs, and API references hosted via MkDocs-Material.
*   **[server](https://github.com/MedMemory-AI/server)**: High-performance local RAG backend engineered with FastAPI, LangChain, Qdrant Vector DB, and PostgreSQL, powered by local Ollama models.
*   **[android-app](https://github.com/MedMemory-AI/android-app)**: Cross-platform user interface built with React Native to handle secure local workflows and visualization.

---

## 🛠️ The Local Open-Source Stack

We intentionally rely on powerful open-source and local primitives to maintain strict zero-cloud data isolation:
*   **Orchestration:** LangChain / Python
*   **Local Compute Engine:** Ollama (`llama3.2`, `mxbai-embed-large`)
*   **Parsing Pipeline:** Docling (for advanced table and structural extraction)
*   **Data Layer:** PostgreSQL (Chronological facts) & Qdrant (Dense vector semantic search)

---

## 🚀 Contributing to Our OSS Programs

We proudly welcome contributors from global open-source programs like **GirlScript Summer of Code (GSSoC)**, **Open Source Connect of India**, and independent developers!

### How to Get Started:
1. Review our global [Contributing Guidelines](./CONTRIBUTING.md) and [Code of Conduct](./CODE_OF_CONDUCT.md).
2. Head over to the specific repository (`server` or `android-app`) you want to work on.
3. Browse the **Issues** tab, look for `good first issue` or `help wanted` tags, and ask to be assigned.
4. Always build your features on a dedicated branch (`feat/your-feature`) and open a Pull Request against `main`.

---

## ⚖️ License & Privacy Guardrail
This project is open-source under the MIT License. Because we handle simulated or real health data inputs, all implementations must prioritize strictly local, offline execution. No telemetry or clinical document fragments should ever leave the user's local machine environment.
