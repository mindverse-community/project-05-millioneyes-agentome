# 🧠 Million-Eyes Project  
### *A Multi-Agent AI System for Cognitive Surveillance Intelligence*  
**Developed by Mindverse Computing**

---

## 🌐 Overview

The **Million-Eyes Project** is a Megha-scale AI initiative to develop an **intelligent surveillance connectome**—a hierarchical, recursive network of AI agents that collectively simulate perception, memory, reasoning, and system-level awareness.

Unlike traditional software development, **Million-Eyes is being written by AI agents**. These agents are organized in layers, each with a dedicated function: from architectural vision to instruction writing, prompt engineering, code generation, testing, and feedback.

This repository contains the auto-generated codebase, agent instructions, prompts, test logs, and supporting workflows — all built under the Mindverse Multi-Agent Development Framework.

---

## 🧱 Multi-Agent Development Stack

| Layer | Agent Role | Responsibility |
|-------|------------|----------------|
| **0** | AI Architect | Defines vision, architecture, design manifest |
| **1** | Coordinator Agent | Decomposes the system, assigns modules |
| **2** | Promoter Agents | Write formal module instructions |
| **3** | Prompter Agents | Generate executable prompts for coders |
| **4** | Coder Agents | Write code from prompts |
| **5** | Evaluation & Feedback Agents | Test, validate, and refine code |

---

## 🔁 Recursive Feedback & Shared Memory

All agents log to a shared vector database (e.g., ChromaDB), allowing:
- Prompt → Code → Test traceability
- Iterative learning from prior decisions
- Feedback-guided refinement at scale

---

## 🧠 Intelligence Stack: Surveillance System Roles

| Layer | Agent Type | Function |
|-------|------------|----------|
| Sense Layer | Camera Agents | Object detection, NLP-based message generation |
| Memory Layer | Memory Agents | Historical event storage and retrieval |
| Intellect Layer | Intellect Agents | Inference, prediction, reasoning |
| Sync Layer | Sync Agents | Stream synchronization and fusion |
| Report Layer | Visualization Agent | Narrative generation and dashboard outputs |

---

## 🔄 Workflow Diagram (Mermaid)

```mermaid
graph TD

A[AI Architect] --> B[Vision Document]
A --> C[Design Manifest]
A --> D[Meta-Prompt Plan]

B --> E[Coordinator Agent]
C --> E
D --> E

E --> F1[Module Map]
E --> F2[Workflow Plan]
E --> G1[Promoter Agent 1]
E --> G2[Promoter Agent 2]

G1 --> H1[Instruction: CameraProcessor]
G2 --> H2[Instruction: MemoryVectorizer]

H1 --> I1[Prompter Agent A]
H2 --> I2[Prompter Agent B]

I1 --> J1[Prompt: CameraProcessor]
I2 --> J2[Prompt: MemoryVectorizer]

J1 --> K1[Coder Agent X]
J2 --> K2[Coder Agent Y]

K1 --> L1[Module: camera_processor.py]
K2 --> L2[Module: memory_vectorizer.py]

L1 --> M1[Evaluation Agent α]
L2 --> M2[Evaluation Agent β]

M1 --> N1[Test Report: CameraProcessor]
M2 --> N2[Test Report: MemoryVectorizer]

N1 --> I1
N2 --> I2
````

---

## 📁 Folder Structure

```bash
million-eyes/
├── architect/
│   ├── vision.md
│   ├── design_manifest.yaml
│   └── meta_prompt_plan.json
├── coordinator/
│   ├── module_map.yaml
│   ├── workflow_plan.yaml
├── promoters/
│   └── instructions/
│       ├── camera_processor.md
│       └── memory_vectorizer.md
├── prompters/
│   └── prompts/
│       ├── camera_processor_prompt.yaml
│       └── memory_vectorizer_prompt.yaml
├── coders/
│   └── src/
│       └── millioneyes/
│           ├── camera_processor.py
│           └── memory_vectorizer.py
├── evaluators/
│   └── tests/
│       ├── test_camera_processor.py
│       └── test_memory_vectorizer.py
├── feedback/
│   ├── refactor_camera_processor.md
│   └── evaluation_summary.md
├── memory/
│   ├── chroma_vector_store/
│   └── prompt_code_trace.json
└── README.md
```

---

## ⚙️ Tooling & Stack

| Purpose                | Tool                              |
| ---------------------- | --------------------------------- |
| Prompt & orchestration | LangChain, LangGraph              |
| Code generation        | GPT-4, OpenAI Codex               |
| Testing                | LangSmith, Phoenix                |
| Memory                 | ChromaDB, FAISS                   |
| Project workflow       | GitHub Actions, AutoDoc pipelines |

---

## 🚀 Contributing

This project is fully AI-generated, but **human reviewers, vision refiners, and systems architects** are welcome to collaborate by:

* Defining new modules
* Reviewing architecture decisions
* Suggesting agent-level improvements

Start by reading:
📄 `architect/vision.md`
📜 `coordinator/module_map.yaml`

Then follow the logs in `/memory` to understand system evolution.

---

## 📌 Summary

The **Million-Eyes Project** is not just another surveillance platform.
It is a demonstration of **autonomous, recursive software architecture**—designed and developed by AI agents that understand vision, structure code, simulate modules, and refine themselves iteratively.

This repository contains the entire AI-generated lifecycle: from architectural intent to evaluated, production-grade components.
You're not just reading code. You're witnessing a new kind of engineering.

Welcome to the era of AI that builds AI.

