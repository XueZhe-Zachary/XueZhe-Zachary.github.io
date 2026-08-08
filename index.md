---
layout: homepage
---

## About Me

I am an M.Eng. student in Software Engineering at Sichuan University, expected to graduate in June 2027. Since June 2022, I have conducted research in AI for drug discovery at the Data Intelligence and Computational Art Laboratory, Sichuan University, and the National-Local Joint Engineering Research Centre of Translational Medicine of Anesthesiology, West China Hospital, Sichuan University.

My research focuses on molecular generation and optimization, protein-ligand modeling, generative modeling, and LLM-based scientific agents.

## Research Interests

- **AI for Drug Discovery:** molecular generation and optimization; protein-ligand modeling
- **Generative Modeling:** autoregressive, diffusion, and flow-based models; controllable and reliable generation
- **LLM-based Scientific Agents:** agent planning, reasoning, and tool use; multi-agent collaboration; scientific workflow automation; closed-loop optimization

{% include publications.md %}

## Research Experience

### AI for Drug Discovery

*Data Intelligence and Computational Art Laboratory, Sichuan University; National-Local Joint Engineering Research Centre of Translational Medicine of Anesthesiology, West China Hospital, Sichuan University*<br>
**June 2022 - Present**

#### TargetSA: Adaptive Simulated Annealing for Target-Specific Drug Design (2024)

- Developed a history-guided GNN to identify promising molecular editing sites and combined four graph-edit operations with reversible simulated annealing.
- Achieved a mean Vina score of -9.09 across 100 CrossDocked2020 pockets; 79.4% of generated molecules outperformed their corresponding reference ligands.
- Published the work as first author in *Bioinformatics* and released an open-source implementation.

#### MASCOT: Multi-Agent Molecular Optimization for Anesthetic Discovery (2024-2026)

- Designed a guardrailed controller-executor framework in which three specialized LLM agents adapt objective priorities, exploration versus refinement, and trajectory memory while a chemically constrained graph editor performs auditable molecular modifications.
- Outperformed competing methods across six benchmark settings, achieving 3.6x the docking-score improvement of the strongest baseline on SARS-CoV-2 Mpro.
- Applied MASCOT to remimazolam, generating 2,729 unique candidates and prioritizing RM-1 for synthesis. Subsequent derivatization and experimental screening advanced RM-7 as a rapid-recovery intravenous anesthetic candidate.
- Co-first-author manuscript in preparation.

#### Flexible-Pocket 3D Molecular Generation for Structure-Based Drug Design (2025)

- Developed an E(3)-equivariant diffusion framework that jointly models de novo ligand generation and pocket conformational refinement through residue transformations, side-chain torsions, and protein-ligand interactions.
- Built an end-to-end prototype and characterized challenges in flexible protein-ligand generation, including limited apo-to-holo supervision, coupled sampling errors, and training-inference mismatch.

#### Spectral Graph Diffusion for Molecular Generation (2026)

- Investigated Laplacian spectra as compact representations of global connectivity and ring topology for diffusion-based molecular graph generation.
- Implemented and evaluated spectral-domain diffusion, Transformer-based graph score models, and spectral guidance on QM9 and ZINC250K.
- Found that spectral features capture global topology but do not sufficiently preserve local chemical constraints, supporting their use as auxiliary guidance rather than a standalone generation space.

## Education

**Sichuan University, College of Computer Science, China**<br>
M.Eng. in Software Engineering, September 2024 - June 2027 (expected)<br>
Overall average: 89.3/100

**Sichuan University, School of Software Engineering, China**<br>
B.Eng. in Software Engineering, September 2020 - June 2024<br>
Overall average: 86.5/100

## Honors & Awards

### Personal Honors

- **National Scholarship**, awarded to the top 0.2% of university students nationwide (2023)
- **Outstanding Graduate of Sichuan Province** (2024)
- **Outstanding Graduate Student, Sichuan University** (2025)
- **Top Ten Students Nominee**, one of 15 nominees for the university's highest student honor (2024)
- **Scholarship for "Star of Reading,"** one of 10 recipients university-wide (2024)
- **Scholarship for Gratitude to Modern Chinese Scientists,** one of 12 recipients university-wide (2023)
- **Scholarship for "Software Elite,"** one of 3 recipients among 213 students (2024)

### Competitions & Innovation Programs

- **National First Prize**, 25th China Robotics and Artificial Intelligence Competition, team leader (2023)
- **Undergraduate Innovation and Entrepreneurship Training Program**, national-level core researcher (2023), provincial-level project leader (2023), and team member (2022)
- **Provincial Second Prize**, 16th China Chengdu International Software Design and Application Competition, team leader (2022)

## Extracurricular

**National University of Singapore, School of Computing, Singapore**<br>
Summer Workshop, May 2022 - July 2022<br>
Third Prize in the Web Mining course; Grade: A

## Skills & Service

- **Programming:** Python, PyTorch, RDKit, Linux
- **Languages:** TOEFL 104 (2022), CET-4 615, CET-6 570
- **Leadership & Service:** Class President (2020-2024); Student Affairs Assistant (2022-2024); Undergraduate Peer Mentor (2024-2025); Teaching Assistant (2024, 2026)
