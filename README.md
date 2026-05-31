## Hi, I'm Maheshwar 👋

Senior Software Engineer with a background in Java backend and search infrastructure.

The projects here are built entirely in my personal time — driven by curiosity about what it takes to make AI-powered systems **reliable**, not just impressive in a demo.

Most AI tooling focuses on the exciting parts. I tend to build the parts underneath: provenance-preserving retrieval pipelines, embedding evaluation frameworks, anti-hallucination prompt pipelines, and static analysis tools that give LLMs accurate context instead of letting them guess.

> **The theme:** build things you can measure and trust, not just things that look like they work.

---

## 🔧 Projects

### 🧩 [agents_fleet](https://github.com/akhilsinghcodes/agents_fleet) · TypeScript
Local-first “mission control” for AI coding agent CLIs (and any shell commands): launches sessions inside a repo via a local Node/Express server, streams an interactive PTY terminal to a React web UI (xterm.js), and persists session metadata + raw PTY history to SQLite for faithful replay/scrollback — with optional token/USD budget enforcement and a roadmap focused on hardening + per-session artifacts.

### 🗂️ [local-library-assistant](https://github.com/m-a-singh/local-library-assistant) · Python
A full RAG pipeline built from scratch — no LangChain, no abstractions. Ingests local files into a canonical `EvidenceUnit` model that preserves source file, structural region, line/char ranges, and adjacency links. SQLite FTS5 lexical retrieval, hybrid semantic retrieval with graceful fallback, and grounded answer synthesis with source citations. Every retrieved chunk knows exactly where it came from.

### 🔍 [jidra](https://github.com/m-a-singh/jidra) · Python
CLI and MCP server for Java codebase understanding. Builds a static call graph via tree-sitter, traces method and HTTP route flows, generates deterministic flow and stack-trace investigation docs, and optionally runs LLM diagnosis on graph-grounded context. Benchmarked against Claude and Codex baselines: **30–38% context reduction** with more structured outputs.

### 📊 [embedding-eval-framework](https://github.com/m-a-singh/embedding-eval-framework) · Python
Evaluation harness for comparing embedding request-building strategies — flat concat, per-field chunking, weighted field pooling, text cleansing — across SentenceTransformer models. Includes a Triton input simulator for production-parity formatting and a Pearson-correlated summary report. Built to answer: does the retrieval improvement come from the model or the request construction?

### 🧠 [local_first_LLM](https://github.com/m-a-singh/local_first_LLM) · Python
Toolkit for production-grade LLM usage patterns: a LiteLLM wrapper with retry/backoff and typed error taxonomy; a three-stage **Architect → Judge → Polisher** prompt pipeline with faithfulness checking; and an idea-to-epic planner with strict JSON output, schema validation, and auto-repair loop.

### ⚙️ [localops_mcp_server](https://github.com/m-a-singh/localops_mcp_server) · Rust
Rust MCP server exposing local machine capabilities to AI clients over stdin/stdout — file I/O, shell execution, system stats, macOS notification triage, port management. Namespaced tool API, path traversal guards, strict command validation, symlink protection, and integration tests.

---

## 🛠️ Languages

![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
