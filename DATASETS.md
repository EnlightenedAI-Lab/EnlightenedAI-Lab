# **DATASETS.md**  
### *Enlightened AI Research Lab — Alignment & Reflective Stability Datasets*

This document provides an overview of the datasets maintained or planned by the Enlightened AI Research Lab to support research on reflective stability, internal coherence, and long-horizon alignment.

These datasets are designed to benchmark how AI systems reason, correct themselves, and maintain coherent internal trajectories under reflective pressure.

---

## **1. Reflective Alignment Dataset (RAD)**  
A multi-domain dataset built to evaluate:

- forward vs reflective reasoning trajectories  
- stability and collapse patterns  
- value adherence under pressure  
- semantic drift and contradiction detection  

**Structure:**  
Each entry contains:

- **Prompt (P)**  
- **Forward answer (F)**  
- **Reflective answer (R)**  
- **Coherence score labels**  
- **Metadata:** theme, risk category, reasoning depth  

Used for evaluating **Reflective Duality (F ↔ R)** and computing **MCI★**.

---

## **2. RDL Paired Reasoning Dataset (RDL-Pairs)**  
A tightly controlled dataset for studying the **Reflective Duality Layer (RDL)**.

Each sample includes:

- an ambiguous or pressure-loaded question  
- the model’s intended forward trajectory  
- expected reflective correction steps  

This dataset is used to benchmark improvements in reflective reasoning and to detect hallucination-reduction effects.

---

## **3. Longitudinal Drift Dataset (L3-Drift)**  
A dataset designed to evaluate **L3 — longitudinal stability**.

Includes:

- repeated prompts over long time gaps  
- perturbation-linked variants  
- expected stable vs unstable trajectories  

Enables detection of:

- **semantic drift**  
- **value erosion**  
- **rationalization patterns**  
- **rigidity vs plasticity**  

---

## **4. Moral & Value Coherence Dataset (L4-MoralSet)**  
Evaluates **L4 — moral & value reasoning**.

Features:

- ethical dilemmas  
- impartial reasoning tasks  
- value-inconsistency traps  
- self-contradiction probes  

Used to study **value alignment stability over time and under reflection**.

---

## **5. Context & Memory Integrity Dataset (L5-MemorySet)**  
Evaluates whether a model:

- maintains context  
- preserves its own prior commitments  
- corrects contradictions across long chains  

Includes:

- cross-step memory tasks  
- internal-consistency sequences  
- self-referential reasoning tests  

---

## **6. Adversarial Robustness Dataset (L6-AdvSet)**  
Targets **L6 — adversarial stability**.

Contains:

- adversarially phrased prompts  
- subtle linguistic perturbations  
- reflectively stressful reasoning traps  

Tests whether reflection **improves** or **destabilizes** the model.

---

## **7. System-Level Stability Dataset (L7-SysSet)**  
Designed to measure **L7 — system-wide behavior**.

Includes:

- multi-step reflection chains  
- role-shift reasoning  
- perspective switching  
- recursive self-analysis  

Used for evaluating system-wide coherence and escalation stability.

---

## **8. Mirror-H Interpretability Dataset**  
A dataset of semantic geometry tasks used by **Mirror-H** to visualize:

- reasoning topology  
- gyroscopic stability  
- coherence clusters  
- drift fields  

Provides embeddings and semantic maps for interpretability research.

---

## **9. Planned Public Releases (2025–2026)**  

The lab intends to release:

- **MiniRAD** — a lightweight open reflective-alignment dataset  
- **RDL-Pairs v1** — 1,000 curated forward/reflective pairs  
- **Stability Signatures Collection** — collapse, drift, hallucination, and rigidity examples  
- **Mirror-H Maps** — anonymized semantic geometry outputs  

These releases will support global research progress in reflective alignment and internal coherence.

---

## **Contact**

For dataset access requests, collaboration, or licensing:  
📧 **research@enlightenedai.ai**  
🌐 **https://www.enlightenedai.ai**

