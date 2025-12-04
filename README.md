# **MKEvo: A Cognitive Runtime for LLM Continuity, Identity & Deterministic Governance**

![License](https://img.shields.io/badge/license-GPLv3-blue.svg)
![Status](https://img.shields.io/badge/status-Active%20Prototyping-orange)
![Version](https://img.shields.io/badge/whitepaper-v1.7-green)

> **"The LLM can be replaced. The identity cannot."**

**MKEvo** is an open-source, LLM-agnostic **cognitive runtime** that adds *continuity*, *identity*, *governance* and *structured memory* on top of any Large Language Model.
It transforms stateless predictors into persistent, governed cognitive agents.

Modern LLMs operate in **isolated, ephemeral episodes**. They have no enduring identity, no stable governance, no temporal thread, and no safe cognitive structure.

MKEvo proposes a shift:

### **The agent is not the model.

The agent is the architecture.**

By externalizing identity, enforcing deterministic governance, and structuring memory and attention according to cognitive science, MKEvo implements **functional pseudo-consciousness** — not consciousness itself, but its architectural prerequisites.

---

# 🧠 **Why MKEvo? (The Problem & The Shift)**

LLMs lack:

* ❌ Persistence
* ❌ Identity
* ❌ State transitions
* ❌ Self-model
* ❌ Memory governance
* ❌ Temporal continuity
* ❌ Controlled attention
* ❌ Constitutional safety

Most agent frameworks simply wrap the LLM with tools and hope for coherence.

**MKEvo inverts the hierarchy.**
The **Consciousness State Controller (CSC)** governs how cognition occurs.
The LLM becomes a *component*, not the decision-maker.

---

# 🌐 **Theoretical Foundations (v1.7 Expanded)**

MKEvo’s architecture is grounded in well-established cognitive and phenomenological theories, mapped into computational mechanisms:

### **🔹 Global Workspace Theory (GWT)**

A bottleneck workspace integrates memory, goals, identity, and constraints before LLM generation.

### **🔹 Attention Schema Theory (AST)**

The agent maintains a simplified self-model of its mode, bandwidth, and safety level.

### **🔹 Husserl’s Internal Time Consciousness**

Implemented through:

* **Retention** → Episodic memory window
* **Primal impression** → Current mode + workspace state
* **Protention** → Self-simulation (10–20 token preview)

### **🔹 Phenomenological Stability**

Identity, values, constraints, and semantic threads evolve slowly and deterministically, never drifting due to LLM randomness.

This grounding is described in depth in the Whitepaper v1.7.

---

# 💠 **Key Features**

## **1. LLM-Agnostic Cognitive Runtime**

Models can be swapped (GPT, Claude, Llama, local models) without losing identity or memory.

## **2. Consciousness State Controller (CSC)**

Deterministic executive layer selecting operational modes:

* Narrative
* Analytic-Deliberative
* Executive
* Exploratory
* Critical-Metacognitive
* Consolidation
* Emergency-Safe

The LLM cannot choose its own mode or behavior.

## **3. Structured Memory Architecture**

* **Episodic Memory** — time-indexed experiences
* **Semantic Memory** — stable knowledge clusters
* **Identity Store** — traits, values, constraints
* **Procedural Memory** — skills and reasoning macros

Includes hygiene rules:

* reality checks
* uncertainty tagging
* dual summarization
* versioning of clusters

## **4. Constitutional Layer**

Every output passes through:

1. critique
2. revision
3. approval/blocking

Architectural safety, not prompt hacks.

## **5. Self-Simulation (Protention)**

Preview of the first **10–20 tokens** to catch unsafe or incoherent paths before they reach the user.

## **6. Consolidation Mode**

Offline restructuring of memory under inactivity or memory pressure:

* deduplication
* semantic abstraction
* identity refinement
* cold storage pruning

---

# 🔁 **Cognitive Turn Cycle (v1.7)**

```
User Input
 ↓
Consciousness State Controller (CSC)
 ↓
Mode Selection
 ↓
Memory Retrieval & Attentional Gating
 ↓
LLM Generation (mode-shaped)
 ↓
Self-Simulation (protention preview)
 ↓
Constitutional Review
 ↓
Final Output
 ↓
Memory Write (policy-based)
```

---

# 🧱 **Architecture Overview**

```
core/
  ├── csc/                 # deterministic state controller
  ├── workspace/           # GWT-inspired bottleneck
  ├── self_model/          # attention schema
  └── simulation/          # protention engine

memory/
  ├── episodic/
  ├── semantic/
  ├── identity/
  └── procedural/

modes/                     # 7 operational modes

governance/
  ├── constitution/
  └── safety_pipeline/

llm/
  ├── openai/
  ├── ollama/
  └── vllm/

tools/
  └── adapters/
```

---

# 🛠️ **Current Status (Prototyping & PoC Development)**

* ✔️ Whitepaper v1.7 (RFC)
* ✔️ Final PoC architecture defined (minimal runtime)
* 🚧 Implementing CSC, workspace, episodic memory, and mode registry
* 🚧 Integrating local LLMs via vLLM / LM Studio on **NVIDIA DGX Spark**
* ⏳ Alpha runtime (date TBD)

---

# ⚙️ **Why NVIDIA DGX Spark?**

The DGX Spark provides:

* ultra-low latency local inference
* 128 GB unified memory → supports near-200B models
* privacy-preserving cognitive loops
* high-frequency turn cycles for protention + governance

It enables **real-time experimentation** with a cognitive agent architecture designed to run *entirely offline*.

---

# 📖 **Whitepaper**

📄 **[MKEvo Whitepaper v1.7 (RFC)](./docs/MKEvo_Whitepaper.md)**
Includes full theory, architecture diagrams, mode definitions, memory protocols, and deployment strategy.

---

# 🔄 **What’s New in v1.7**

* Expanded cognitive foundations (GWT, AST, Internal Time Consciousness)
* Formal protention mechanism (token-level preview)
* Deterministic governance refined (CSC as executive)
* Consolidation Mode formalized
* Memory hygiene protocols extended
* Deployment strategy for DGX Spark
* Narrative clarity and tighter conceptual framing

---

# 🤝 **Contributing**

Contributions are welcome:

* Issues & bug reports
* Architectural discussions
* Runtime implementation
* Cognitive or theoretical insights

Connect on LinkedIn or via GitHub.

---

# ⚖️ **License**

GPLv3 — free to use, modify, and distribute under the same license.

---

# 📚 **Citation**

```
Albert Rosado Corrius. (2025). MKEvo: A Cognitive Runtime Architecture
for LLM Continuity, Identity and Deterministic Governance.
Released under the GNU General Public License v3.0.
```

