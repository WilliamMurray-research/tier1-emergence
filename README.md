# tier1-emergence

Simulation engine, graph substrates, and analysis tools for the Tier‑1 Emergence research program. This repository provides the computational framework used to study first‑order emergent behaviour in structured dynamical systems, with a focus on non‑backtracking propagation on mesoscale graphs.

---

## Purpose

`tier1-emergence` is the **experimental substrate** for investigating how structure gives rise to behaviour.  
It provides:

- graph construction utilities (Euclidean, hyperbolic, modular)
- non‑backtracking propagation rules and frontier‑based simulation
- tools for measuring attractors, coherence, and emergent structure
- analysis pipelines for detecting first‑order emergence
- reproducible configurations for large‑scale experiments

This repository complements the theoretical and manuscript work in  
`tier1-emergence-papers`.

---

## Components

- **Graph Substrates**  
  Structured, modular, and curved‑geometry graphs for controlled experiments.  
  `/graphs/`

- **Simulation Engine**  
  Non‑backtracking dynamics, frontier propagation, and state‑update rules.  
  `/engine/`

- **Analysis Tools**  
  Attractor detection, coherence metrics, information‑flow analysis.  
  `/analysis/`

- **Experiment Configurations**  
  Parameter sets and reproducible experiment definitions.  
  `/experiments/`

---

## Research Context

This engine supports the study of **first‑order emergence**:  
global intelligent behaviour arising from local interactions.

It is designed to scale toward experiments probing **second‑order emergence**  
(self‑modelling dynamics) as described in the Two‑Tier Emergence Hypothesis.

For theoretical background, see:  
https://github.com/WilliamMurray-research/tier1-emergence-papers

---

## Licensing

- **Code:** MIT License  
- **Documentation and figures:** CC BY‑4.0

---

## Status

Active research codebase. APIs and structures may evolve as experiments progress.
