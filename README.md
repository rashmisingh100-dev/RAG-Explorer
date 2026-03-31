# RAG Explorer 🔍

**An interactive guide to the four ways AI finds answers.**

Most people know AI can answer questions. Few understand *how* it retrieves the right information to do so. RAG Explorer breaks down all four Retrieval Augmented Generation patterns — visually, interactively, and in plain English — so anyone can understand them regardless of technical background.

🔗 **Live:** [rashmisingh100-dev.github.io/RAG-Explorer](https://rashmisingh100-dev.github.io/RAG-Explorer)

---

## What is RAG?

RAG (Retrieval Augmented Generation) is the technique AI systems use to answer questions from your data — rather than relying on general training knowledge alone. There are four distinct patterns, each built for a different problem.

---

## The Four RAG Patterns

### 01 — Traditional RAG
Converts your question into a vector (mathematical fingerprint) and finds the closest matching document chunks via similarity search.
**Best for:** FAQs, HR policy bots, customer support, product documentation.

### 02 — Vectorless RAG
No embeddings. An LLM expands your query into precise terminology, then BM25 scores every document by exact keyword frequency.
**Best for:** Legal contracts, regulatory compliance, medical records, patent research.

### 03 — Graph RAG
An LLM reads documents and builds a knowledge graph — entities connected by labelled edges. Queries traverse the graph hop by hop.
**Best for:** Fraud detection, supply chain risk, org intelligence, drug interaction mapping.

### 04 — Agentic RAG
An AI agent plans, selects tools, executes sub-queries, validates confidence, retries weak results, grounds the answer, then responds.
**Best for:** Financial research, due diligence, competitive intelligence, legal discovery.

---

## What Makes This Different

Every RAG pattern includes a **fully interactive step-by-step demo** — not just a diagram. You watch each step happen in real time:

- Documents chunked and embedded
- Vectors compared with similarity scores
- Keywords extracted and BM25 scored
- Graph nodes lighting up during traversal
- Agent planning, retrying, and validating confidence

Each step is manual — you control the pace. No rushing through animations.

---

## Features

- ✅ Four complete RAG demos with real datasets
- ✅ Manual step-by-step progression — learn at your own pace
- ✅ Plain English explanations at every step
- ✅ "Which RAG suits you?" decision guide
- ✅ No API key required — fully pre-scripted demos
- ✅ Mobile responsive
- ✅ Single HTML file — zero dependencies

---

## Tech Stack

Pure HTML, CSS, and JavaScript. No frameworks. No dependencies. No backend.
One file. Deployable anywhere.

---

## Who This Is For

- **Developers** evaluating which RAG pattern fits their use case
- **Product managers** explaining AI retrieval to stakeholders
- **Business leaders** understanding how enterprise AI actually works
- **Anyone curious** about how AI finds its answers

---

## Author

**Rashmi Singh** — Technical Programme Manager, AI Strategy
Building at the intersection of enterprise AI delivery and technical depth.

[LinkedIn](https://www.linkedin.com/in/rashmisingh100) · [GitHub](https://github.com/rashmisingh100-dev)

---

*Built as part of a personal initiative to make AI concepts genuinely accessible — not just described, but experienced.*
