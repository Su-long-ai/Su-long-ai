# Private Research Highlights

This page summarizes selected private systems without publishing local datasets, copyrighted media, user-derived artifacts, credentials, or machine-specific integrations.

## 1. Multi-Agent Autonomous Research & Evaluation Platform

**Role:** system designer / research engineer  
**Focus:** multi-agent research orchestration, reproducible experimentation, deterministic auditing

### Problem

AI research workflows easily become hard to trust when multiple agents modify shared code, reuse stale evidence, or promote results without independent verification.

### Design

The system separates research into explicit stages:

```text
Scientist workspace
      |
      v
scope scan -> focused experiment -> local tests -> evidence package
      |
      v
Lead promotion gate
      |
      v
frozen protocol + frozen runner + frozen deterministic auditor
      |
      v
formal execution
      |
      v
independent recomputation / audit
      |
      v
downstream promotion only on audit PASS
```

Key ideas:

- each Scientist works in an isolated workspace instead of editing canonical code directly;
- research submissions bind implementation and evidence artifacts by hash;
- Lead decisions are explicit rather than inferred from chat state;
- formal experiments freeze the protocol and auditor before results exist;
- independent deterministic Python audits recompute results after execution;
- research, paper validation and live execution remain separate states.

### What this demonstrates

- multi-agent orchestration;
- governance-aware AI engineering;
- reproducible ML / quant research infrastructure;
- deterministic validation around stochastic research;
- failure containment and traceability.

---

## 2. Persistent AI Identity & Long-Term Memory System

**Role:** system designer / AI application engineer  
**Focus:** stateful agents, persistent memory, provenance, long-horizon evaluation

### Problem

A long-running AI assistant needs more than chat history. It needs a stable identity model, traceable memory, controlled persona change and portability across model providers.

### Design

```text
conversation / interaction
        |
        v
event ledger ------------------+
        |                      |
        v                      |
memory candidate               |
        |                      |
human confirmation             |
        |                      |
        v                      |
long-term memory --------------+
        |
        v
retrieval -> model context -> response

persona changes require explicit evidence + versioned approval
```

Key ideas:

- identity is stored independently of the model provider;
- memories retain provenance back to source events;
- initial persona configuration is separated from observed experience;
- persona evolution is versioned and human-confirmed;
- identity can be exported and restored without moving credentials;
- retrieval quality is evaluated independently from final answer quality.

### What this demonstrates

- long-term memory architecture;
- stateful agent design;
- provenance-aware data modeling;
- model/provider decoupling;
- evaluation of retrieval bottlenecks rather than only end-answer scores.

---

## 3. Large-Scale Rhythm-Chart Generation Research Workspace

**Role:** ML research engineer  
**Focus:** structured sequence generation, evaluation, human-reference diagnostics

### Research layers

- audio / MIR evidence extraction;
- temporal opportunity detection;
- event retention and recurrence modeling;
- typed gesture and lane-state representation;
- long-note duration and release scheduling;
- difficulty-aware generation and simplification;
- mapper-style, replay and playability diagnostics;
- controlled ablations and preregistered experiments.

The public repository **[Rhythm Chart Generation Research](https://github.com/Su-long-ai/rhythm-chart-generation-research)** is a sanitized, runnable extraction of reusable ideas from this larger workspace.

### What this demonstrates

- structured sequence modeling;
- evaluation design for subjective generation tasks;
- data-leakage control;
- research iteration with negative-result retention;
- separation of hard legality constraints from learned quality signals.

---

## Public / private boundary

Private repositories stay private when publishing them would expose:

- local or licensed datasets;
- copyrighted audio / media references;
- player- or user-derived evaluation artifacts;
- machine-specific integrations;
- large checkpoints and generated artifacts;
- credentials or local operational state.

The public portfolio focuses on **reviewable architecture, runnable examples, tests, and reproducible engineering ideas**.
