---
layout: homepage
---

## About Me

<p class="about-lines">I am an M.Eng. student in Software Engineering at Sichuan University, advised by <a href="https://scholar.google.com/citations?user=qxNzQfQAAAAJ&hl=en" target="_blank" rel="noopener">Prof. Xianggen Liu</a>, with research conducted in collaboration with West China Hospital.<br>
My research focuses on methodological advances in generative AI and scientific agents, with drug discovery as a primary application domain, particularly molecular generation and optimization.<br>
<strong>I am currently applying for PhD programs starting in Fall 2027</strong> and welcome opportunities to discuss potential research collaborations.</p>

## Research Interests

<ul class="research-interests">
  <li><strong>AI for Drug Discovery:</strong> molecular generation and optimization under complex structural and property constraints.</li>
  <li><strong>Generative Modeling:</strong> controllable and reliable generative models for scientific domains.</li>
  <li><strong>Scientific Agents:</strong> agentic systems that can plan, use scientific tools, and adaptively optimize experimental or computational workflows.</li>
</ul>

## Selected Research

### MASCOT: Multi-Agent Molecular Optimization for Anesthetic Discovery

<div class="research-summary">
  <p><strong>Problem.</strong> Multi-objective molecular optimization requires search strategies to adapt as property bottlenecks change.</p>
  <p><strong>Method.</strong> MASCOT uses specialized LLM agents to adapt objectives, search strategies, and trajectory memory, while a chemically constrained graph editor performs auditable molecular modifications.</p>
  <p><strong>Outcome.</strong> MASCOT outperformed competing methods across six benchmark settings and achieved 3.6× the docking-score improvement of the strongest baseline on SARS-CoV-2 Mpro. Applied to remimazolam, it generated 2,729 unique candidates and supported the progression from RM-1 synthesis to RM-7, a rapid-recovery intravenous anesthetic candidate identified through subsequent derivatization and experimental screening.</p>
</div>

### TargetSA: Adaptive Simulated Annealing for Target-Specific Drug Design

<div class="research-summary">
  <p><strong>Problem.</strong> Target-specific molecular optimization requires efficient exploration of a large, discrete chemical space.</p>
  <p><strong>Method.</strong> TargetSA combines a history-guided GNN for identifying promising editing sites with four graph-edit operations and reversible simulated annealing.</p>
  <p><strong>Outcome.</strong> Across 100 CrossDocked2020 pockets, TargetSA achieved a mean Vina score of −9.09, with 79.4% of generated molecules outperforming their corresponding reference ligands.</p>
</div>

### Additional Research

**Flexible-Pocket 3D Molecular Generation.** Developed an E(3)-equivariant diffusion prototype that jointly models de novo ligand generation and pocket conformational refinement. This work characterized practical challenges in flexible protein-ligand generation, including limited apo-to-holo supervision, coupled sampling errors, and training–inference mismatch.

**Spectral Graph Diffusion.** Investigated Laplacian spectra as representations of global connectivity and ring topology for molecular graph generation. Experiments on QM9 and ZINC250K indicated that spectral features are more suitable as auxiliary guidance than as a standalone generation space because they do not sufficiently preserve local chemical constraints.

{% include publications.md %}

## Education

**Sichuan University**  
M.Eng. in Software Engineering, 2024–2027 (expected)

**Sichuan University**  
B.Eng. in Software Engineering, 2020–2024

**National University of Singapore**  
Summer Workshop, School of Computing, 2022

## Selected Honors

- **National Scholarship** (2023)
- **Outstanding Graduate of Sichuan Province** (2024)
- **Top Ten Students Nominee** — 15 nominees for the university’s highest student honor (2024)
- **Scholarship for “Star of Reading”** — 10 recipients university-wide (2024)
- **Scholarship for Gratitude to Modern Chinese Scientists** — 12 recipients university-wide (2023)
- **National First Prize**, China Robotics and Artificial Intelligence Competition (2023)

See my [CV](./assets/files/xuezhe_cv.pdf) for additional honors and awards.
