---
layout: homepage
---

## About Me

<p class="about-lines">I am an M.Eng. student in Software Engineering at Sichuan University, advised by <a href="https://scholar.google.com/citations?user=qxNzQfQAAAAJ&hl=en" target="_blank" rel="noopener">Prof. Xianggen Liu</a>, with research conducted in collaboration with West China Hospital.<br>
My research centers on <strong>generative AI and scientific agents</strong>, with drug discovery as a primary application domain, particularly molecular generation and optimization.<br>
<strong>I am currently applying for PhD programs starting in Fall 2027.</strong></p>

## Research Interests

<ul class="research-interests">
  <li><strong>AI for Drug Discovery:</strong> molecular generation and optimization under complex structural and property constraints.</li>
  <li><strong>Generative Modeling:</strong> controllable and reliable generative models for scientific domains.</li>
  <li><strong>Scientific Agents:</strong> agentic systems that can plan, use scientific tools, and adaptively optimize experimental or computational workflows.</li>
</ul>

{% include publications.md %}

## Selected Research

### MASCOT: Multi-Agent Molecular Optimization for Anesthetic Discovery

<div class="research-summary">
  <p><strong>Problem.</strong> Multi-objective molecular optimization requires search strategies to adapt as property bottlenecks change.</p>
  <p><strong>Method.</strong> MASCOT uses specialized LLM agents to adapt objectives, search strategies, and trajectory memory, while a chemically constrained graph editor performs auditable molecular modifications.</p>
  <p><strong>Outcome.</strong> MASCOT outperformed competing methods across six benchmark settings. Applied to remimazolam, it generated 2,729 candidates and ultimately contributed to the identification of RM-7 as a rapid-recovery intravenous anesthetic candidate through synthesis and experimental screening.</p>
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

## Education

<div class="education-list">
  <div class="education-item"><strong>Sichuan University</strong><br>M.Eng. in Software Engineering, 2024–2027 (expected)</div>
  <div class="education-item"><strong>Sichuan University</strong><br>B.Eng. in Software Engineering, 2020–2024</div>
  <div class="education-item"><strong>National University of Singapore</strong><br>Summer Workshop, School of Computing, 2022</div>
</div>

## Selected Honors

<ul class="selected-honors">
  <li><strong>National Scholarship</strong> (2023)</li>
  <li><strong>Outstanding Graduate of Sichuan Province</strong> (2024)</li>
  <li><strong>Top Ten Students Nominee</strong> — 15 nominees for the university’s highest student honor (2024)</li>
  <li><strong>Scholarship for “Star of Reading”</strong> — 10 recipients university-wide (2024)</li>
  <li><strong>Scholarship for Gratitude to Modern Chinese Scientists</strong> — 12 recipients university-wide (2023)</li>
  <li><strong>National First Prize</strong>, China Robotics and Artificial Intelligence Competition (2023)</li>
</ul>

See my [CV](./assets/files/xuezhe_cv.pdf) for additional honors and awards.
