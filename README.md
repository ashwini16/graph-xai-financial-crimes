# Graph XAI for Financial Crimes

This repository contains research code, experiments, and analysis for studying **graph-based machine learning** and **explainable AI (XAI)** methods in the context of **financial crime detection**.

The project focuses on large-scale **synthetic transaction networks** generated using agent-based AML simulators, enabling controlled investigation of **temporal dynamics, graph structure, and explainability methods** under known ground-truth laundering behaviors.

---

## Research Agenda

This repository supports a coherent research program consisting of **three related papers**:

### 📄 Paper 1 — XAI Benchmarking Across Models
**Goal:**  
Evaluate and compare explainable AI techniques across diverse modeling paradigms and data modalities.

**Focus:**
- Tabular, temporal, and simple synthetic datasets
- Linear models, tree-based models, and neural networks
- Model-agnostic vs model-specific XAI methods
- Stability, faithfulness, and failure modes of explanations

---

### 📄 Paper 2 — Graph Learning for Financial Crime
**Goal:**  
Analyze how graph structure and temporal dynamics improve financial crime detection.

**Focus:**
- Transaction graph construction
- Temporal laundering bursts
- Degree-based role analysis
- Graph neural networks vs tabular baselines
- Leakage-safe temporal evaluation

---

### 📄 Paper 3 — Explainable Graph Learning for Financial Crime
**Goal:**  
Assess graph explainability methods under controlled, ground-truth conditions.

**Focus:**
- Subgraph explanations
- Node and edge attribution
- Temporal explanations
- Counterfactual graph reasoning
- Quantitative evaluation of explanation faithfulness

---

## Dataset

All experiments are conducted on **synthetic financial transaction data** generated using agent-based AML simulators (e.g., IBM AMLworld-style generators).

**Key properties:**
- Encodes known money-laundering typologies
- Includes temporal bursts and coordinated activity
- Provides complete ground-truth labels
- Enables objective evaluation of explainability methods

⚠️ **Disclaimer:**  
Results and structural patterns reflect the assumptions of the synthetic data generator and should not be interpreted as empirical claims about real-world financial systems.

---

## Repository Structure

```text
graph-xai-financial-crimes/
├── core/                  # Shared infrastructure (data, graphs, metrics)
├── papers/                # Paper-specific experiments and results
├── notebooks/             # EDA and exploratory analysis
├── figures/               # Paper-ready figures
├── requirements.txt
└── README.md
