---
layout: homepage
---

## About Me

I am an M.Eng. student in Software Engineering at Sichuan University, expected to graduate in June 2027. My research develops AI methods for drug discovery, with a focus on molecular generation and optimization under structural and property constraints; I work on these problems at Sichuan University and West China Hospital. For doctoral study, I am interested in building controllable generative models and scientific agents that can reason with domain tools and adaptively improve computational and experimental workflows.

## Research Interests

- **AI for Drug Discovery:** molecular generation and optimization under complex structural and property constraints.
- **Generative Modeling:** controllable and reliable generative models for scientific domains.
- **Scientific Agents:** agentic systems that can plan, use scientific tools, and adaptively optimize experimental or computational workflows.

## Selected Research

### MASCOT: Multi-Agent Molecular Optimization for Anesthetic Discovery

**Problem.** Multi-objective molecular optimization requires search strategies to adapt as property bottlenecks change.

**Idea.** MASCOT uses specialized LLM agents to adapt objectives, search strategies, and trajectory memory, while a chemically constrained graph editor performs auditable molecular modifications.

**Outcome.** MASCOT outperformed competing methods across six benchmark settings and achieved 3.6× the docking-score improvement of the strongest baseline on SARS-CoV-2 Mpro. Applied to remimazolam, it generated 2,729 unique candidates and supported the progression from RM-1 synthesis to RM-7, a rapid-recovery intravenous anesthetic candidate identified through subsequent derivatization and experimental screening.

### TargetSA: Adaptive Simulated Annealing for Target-Specific Drug Design

**Problem.** Target-specific molecular optimization requires efficient exploration of a large, discrete chemical space.

**Idea.** TargetSA combines a history-guided GNN for identifying promising editing sites with four graph-edit operations and reversible simulated annealing.

**Outcome.** Across 100 CrossDocked2020 pockets, TargetSA achieved a mean Vina score of −9.09, with 79.4% of generated molecules outperforming their corresponding reference ligands.

### Additional Research

**Flexible-Pocket 3D Molecular Generation.** Developed an E(3)-equivariant diffusion prototype that jointly models de novo ligand generation and pocket conformational refinement. This work characterized practical challenges in flexible protein-ligand generation, including limited apo-to-holo supervision, coupled sampling errors, and training–inference mismatch.

**Spectral Graph Diffusion.** Investigated Laplacian spectra as representations of global connectivity and ring topology for molecular graph generation. Experiments on QM9 and ZINC250K indicated that spectral features are more suitable as auxiliary guidance than as a standalone generation space because they do not sufficiently preserve local chemical constraints.

{% include publications.md %}

## Education

**Sichuan University**  
M.Eng. in Software Engineering, 2024–2027 (expected)

**Sichuan University**  
B.Eng. in Software Engineering, 2020–2024

*Summer Workshop, National University of Singapore School of Computing, 2022.*

## Selected Honors

- **National Scholarship** (2023)
- **Outstanding Graduate of Sichuan Province** (2024)
- **Outstanding Graduate Student, Sichuan University** (2025)
- **National First Prize**, China Robotics and Artificial Intelligence Competition (2023)

See my [CV](./assets/files/xuezhe_cv.pdf) for additional honors and awards.
