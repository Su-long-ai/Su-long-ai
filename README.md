# Sulong

**AI Agent / Applied AI Engineer · ML Research**

I build **agentic AI systems, RAG backends, long-term memory, multimodal applications, and reproducible ML research pipelines**.

My focus is not just getting a demo to run. I care about the engineering around it: **tool orchestration, memory, retrieval quality, evaluation, data leakage, reproducibility, privacy boundaries, and failure analysis**.

> **2027 graduate · Artificial Intelligence major**  
> Target roles: **AI Agent Engineer · AI Application Algorithm Engineer · Applied AI / ML Engineer**

## Recruiter quick scan

| Project | What I built | What it demonstrates |
| --- | --- | --- |
| **[Multimodal Desktop Agent](https://github.com/Su-long-ai/multimodal-desktop-agent)** | Agent orchestration core with pluggable LLM providers, MCP-style tool namespaces, bounded tool loops, memory backends, voice/avatar adapters and offline tests | **Agent engineering · tool use · memory · modular architecture** |
| **[Human-Gated Multi-Agent Supervisor](https://github.com/Su-long-ai/human-gated-agent-supervisor)** | Local-first agent runtime with leases, heartbeats, isolated state, mailboxes and explicit human gates | **Multi-agent orchestration · state machines · failure containment** |
| **[Medical RAG Assistant](https://github.com/Su-long-ai/medical-rag-assistant)** | FastAPI RAG backend with bounded document ingestion, Chroma retrieval, deterministic routing, optional read-only Neo4j context and SSE streaming | **RAG · AI backend · retrieval · API engineering** |
| **[Rhythm Chart Generation Research](https://github.com/Su-long-ai/rhythm-chart-generation-research)** | Structured sequence-modeling research with deterministic legality checks, causal lane-recency priors, multi-head diagnostics and group-disjoint OOF evaluation | **PyTorch · sequence modeling · leakage-aware evaluation** |
| **[Aegis Financial Intelligence](https://github.com/Su-long-ai/aegis-financial-intelligence-dashboard)** | Local-first event intelligence pipeline with rule fallback, optional LLM enrichment, SQLite audit trail, CLI and dashboard | **LLM applications · structured reasoning · auditable pipelines** |

## Selected private research systems

Some of my largest systems stay private because they contain local datasets, copyrighted media references, user-derived evaluation artifacts, or machine-specific integrations. I publish the engineering ideas without exposing material that should remain private.

### Multi-Agent Autonomous Research & Evaluation Platform

A research platform for coordinating multiple AI research workers under reproducible experiment governance.

- isolated Scientist workspaces and task ownership;
- Lead promotion gates for research results;
- protocol / runner / auditor freezing before formal experiments;
- artifact hashing and traceable handoffs;
- deterministic independent auditing before downstream promotion;
- explicit separation between research, paper validation and live execution.

**Signal:** multi-agent orchestration, research infrastructure, reproducibility, fail-closed evaluation.

### Persistent AI Identity & Long-Term Memory System

A model-independent persistent identity and memory prototype for long-running AI interaction.

- event-sourced identity history and traceable long-term memories;
- human-confirmed memory promotion and versioned persona evolution;
- provider-independent model switching;
- portable identity export / restore;
- offline regression tests and external long-term-memory evaluation;
- explicit separation between initial persona, observed events and retrieved memories.

**Signal:** stateful agents, long-term memory, evaluation, provenance and local-first system design.

### Large-Scale Rhythm-Chart Generation Workspace

The full private research workspace behind the public rhythm-chart showcase.

- audio/MIR evidence extraction and temporal opportunity detection;
- typed gesture and lane-state modeling;
- long-note duration / release scheduling;
- difficulty-aware generation and simplification;
- replay, playability and human-reference diagnostics;
- preregistration, ablations and falsification-oriented experiments.

**Signal:** research depth, structured sequence modeling, experimental discipline.

More detail: **[Private Research Highlights](PRIVATE_RESEARCH_HIGHLIGHTS.md)**

## Engineering strengths

- **Agent systems:** provider abstraction, tool orchestration, bounded execution loops, memory adapters, MCP-style integrations
- **RAG / retrieval:** document ingestion, vector search, deterministic routing, evidence-aware synthesis, graph context
- **ML research:** PyTorch, sequence modeling, CV, RL, leakage-aware splits, grouped OOF evaluation
- **Backend / systems:** FastAPI, SQLite, REST/SSE, CLI tooling, local-first applications
- **Evaluation:** frozen protocols, deterministic checks, negative-result retention, reproducible experiment structure
- **Foundations:** Python, C/C++, data structures & algorithms

## Other projects

- **[Semantic Movie Finder](https://github.com/Su-long-ai/semantic-movie-finder)** — multilingual dense retrieval with SentenceTransformers + FAISS
- **[CLIP + LSTM Image Captioning](https://github.com/Su-long-ai/clip-lstm-image-captioning)** — image captioning with CLIP features, LSTM decoding and beam search
- **[Flood Road Segmentation](https://github.com/Su-long-ai/flood-road-segmentation)** — DeepLabV3+ segmentation pipeline with deterministic data pairing
- **[EV Wireless-Charging DQN](https://github.com/Su-long-ai/ev-wireless-charging-dqn)** — DQN environment with graph action masking and deterministic tests

## Awards

- **16th Lanqiao Cup, Jiangsu Division — First Prize**, C/C++ Programming, University Group B (2025)
- **2025 AIComp Provincial Selection — Third Prize**, algorithm challenge on predicting/recommending users' potential book borrowing

## How I work

I prefer **testable systems over impressive-looking demos**:

- keep evaluation boundaries explicit;
- separate deterministic rules from learned components;
- preserve negative and inconclusive results;
- make private/public boundaries intentional;
- turn experiments into reproducible workflows rather than one-off notebooks.

**Current focus:** AI agents, RAG, persistent memory, multimodal systems, and research-grade evaluation.
