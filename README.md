# MHSC-Metaheuristic-Cloud-Energy-Optimization
Hybrid Bat-Genetic metaheuristic for energy-aware workflow scheduling in cloud datacenters (tri-objective optimization: energy, throughput, execution time).

## 🔗 DOI
https://doi.org/10.1016/j.future.2024.107624

Published in: Future Generation Computer Systems (Elsevier)

---

## 🌍 Overview

Cloud datacenters currently account for nearly 1% of global electricity consumption and approximately 2% of worldwide carbon emissions.

As scientific and enterprise workflows grow in scale and dependency, optimizing energy consumption without sacrificing throughput or execution time becomes a critical challenge.

MHSC introduces a sensitivity-driven hybrid metaheuristic framework that merges Genetic Algorithm (GA) and Bat Algorithm to achieve tri-objective optimization in cloud workflow scheduling.

The method simultaneously optimizes:

- Energy Consumption
- Execution Time
- Throughput

---

## 🚨 The Core Challenge

Cloud workflow scheduling is:

- NP-Complete
- Multi-objective
- Energy-sensitive
- Dependency-constrained

Traditional schedulers optimize one parameter at the expense of others.

Energy ↓ often means Execution Time ↑  
Throughput ↑ often means Energy ↑  

A balanced solution requires intelligent global search beyond single-objective heuristics.

---

## 💡 The MHSC Innovation

MHSC integrates:

- Hybrid Bat + Genetic search
- Sensitivity rate computing
- Linear programming for inertia generation
- Intelligent threshold detection
- Workflow input clustering
- Deadline-aware task mapping
- Neighborhood-based quality link prediction

The hybridization enables:

- Faster escape from local optima
- Reduced iteration counts
- Improved convergence speed
- Balanced tri-objective trade-off

---

## 📊 Experimental Improvements

Compared to baseline approaches:

- Energy consumption improved by 6.4%
- Execution time reduced by 8.1%
- Throughput increased under high node dependency
- Better scalability as workflow size grows

Performance advantage increases as task dependencies increase.

---

## 🔬 Technical Architecture

The MHSC pipeline:

1. Input classification based on deadline constraints
2. Hybrid Genetic distribution of workflow tasks
3. Bat-based inertia and exploration control
4. Sensitivity-driven threshold adaptation
5. Multi-objective fitness evaluation

Objective Function balances:

- Energy Model
- Execution Time Model
- Throughput Maximization

---

## 🌱 Why It Matters

Green computing is no longer optional.

Datacenters face:

- Energy cost escalation
- Carbon regulation pressure
- SLA constraints
- Resource scalability demands

MHSC provides a sustainable scheduling framework for:

- Scientific workflows (astronomy, bioinformatics, physics)
- Enterprise cloud systems
- DevOps pipelines
- HPC cloud platforms

---

## 🧠 Keywords

Cloud Computing • Workflow Scheduling • Metaheuristic • Bat Algorithm • Genetic Algorithm • Multi-objective Optimization • Green Computing • Energy-aware Systems • Sustainable Datacenters • High Performance Computing

---

## 📄 Publication Details

Title:
MHSC: A meta-heuristic method to optimize throughput and energy using sensitivity rate computing

Authors:
A. Ghorbannia Delavar  
R. Akraminejad  
F. Kazemipour  

Journal:
Future Generation Computer Systems

DOI:
10.1016/j.future.2024.107624

---

## 📚 Citation (APA)

Ghorbannia Delavar, A., Akraminejad, R., & Kazemipour, F. (2025). MHSC: A meta-heuristic method to optimize throughput and energy using sensitivity rate computing. Future Generation Computer Systems. https://doi.org/10.1016/j.future.2024.107624

---

## 📚 Citation (BibTeX)

@article{MHSC2025,
  title={MHSC: A meta-heuristic method to optimize throughput and energy using sensitivity rate computing},
  author={Ghorbannia Delavar, Arash and Akraminejad, Reza and Kazemipour, Farhad},
  journal={Future Generation Computer Systems},
  year={2025},
  doi={10.1016/j.future.2024.107624}
}

---

## 🏫 Affiliation

Department of Computer Engineering  
Payame Noor University, Tehran, Iran

---

## ⚖ License

This repository is created for academic indexing and visibility purposes.  
All publication rights belong to the journal publisher.

---

## ⭐ Impact

This repository contributes to structured digital indexing of high-impact cloud optimization research (2022–2025) to enhance discoverability across GitHub, search engines, and academic ecosystems.
