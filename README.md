## Hi, I'm Maheshwar(Akhil) 👋

Senior Software Engineer with a background in Java backend.

The projects here are built entirely in my personal time — driven by curiosity about what it takes to make AI-powered systems **reliable**, not just impressive in a demo.

Most AI tooling focuses on the exciting parts. I tend to build the parts underneath: provenance-preserving retrieval pipelines, embedding evaluation frameworks, anti-hallucination prompt pipelines, and static analysis tools that give LLMs accurate context instead of letting them guess.

> **The theme:** build things you can measure and trust, not just things that look like they work.

---

## 🔧 Projects

### 🧩 [agents_fleet](https://github.com/akhilsinghcodes/agents_fleet) · TypeScript
Local-first “mission control” for AI coding agent CLIs (and any shell commands): launches sessions inside a repo via a local Node/Express server, streams an interactive PTY terminal to a React web UI (xterm.js), and persists session metadata + raw PTY history to SQLite for faithful replay/scrollback — with optional token/USD budget enforcement and a roadmap focused on hardening + per-session artifacts.

### 🔍 [jidra](https://github.com/m-a-singh/jidra) · Python
CLI and MCP server for Java codebase analysis. Builds a static call graph via AST parsing, validates against Spring beans to remove phantom edges, generates minimal noise-free context for LLM workflows. Proven: **87-95% token reduction** (10,811→869 tokens) with **zero false negatives** and **100% business logic coverage**.

---

## 🛠️ Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
