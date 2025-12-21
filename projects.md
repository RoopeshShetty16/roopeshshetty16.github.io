---
layout: default
title: Projects & Case Studies
---

# Projects & Case Studies

Selected engineering projects demonstrating simulation, automation, and product development capabilities.

---

## 1. E-Bike and Accessory Simulation Platform

**Challenge:** Establish a robust simulation framework for e-bike and accessory platforms to evaluate structural and thermomechanical performance under realistic load and vibration conditions.

**Approach:**
- Set up end-to-end simulation chains in Ansys Workbench and LS-Dyna
- Defined non-linear contact behaviour between components
- Implemented material models (plastic/hyperelastic) for realistic behaviour
- Created assembly-level load cases for static, transient, and modal analysis

**Tools Used:** Ansys Workbench, Ansys Mechanical, LS-Dyna, SpaceClaim, Python, MAPDL scripting

**Outcome:** Enabled early-stage virtual validation, reduced dependency on late physical tests, and provided a standardized approach for platform-level performance and reliability assessments.

---

## 2. ECU & DC-DC Converter Thermomechanical Reliability

**Challenge:** Understand and mitigate thermomechanical and structural risks in ECU and DC-DC converter assemblies exposed to combined mechanical and thermal loads.

**Approach:**
- Built detailed component- and assembly-level models
- Captured PCB constraints, connector interfaces, and housing interactions
- Evaluated stress, deformation, and critical regions across operating scenarios
- Performed taboo zone assessment and tolerance-driven assembly variation studies

**Tools Used:** Ansys Workbench, Ansys Mechanical, LS-Dyna, HyperMesh

**Outcome:** Identified critical design risks, informed layout and mechanical design changes, and contributed to more robust electronics packaging and mounting concepts.

---

## 3. Press-Fit & Cold Weld Joint Evaluation Methodology

**Challenge:** Need for a reliable, simulation-driven methodology to evaluate press-fit and cold weld joints early in product development, avoiding late failures and over-testing.

**Approach:**
- Performed explicit simulations in LS-Dyna to study insertion behaviour
- Optimized velocity and mass scaling parameters for computational efficiency
- Refined contact and material modelling for realistic joint behaviour
- Compared and tuned results for both component and assembly configurations

**Tools Used:** LS-Dyna, HyperMesh, Ansys Workbench, Python

**Outcome:** Contributed to standardized press-fit cold weld evaluation methods used in development, improving prediction accuracy and reducing time spent on trial-and-error physical experiments.

---

## 4. Simulation Workflow Automation Suite

**Challenge:** High manual effort and inconsistency in pre-processing, solver debugging, and reporting across CAE projects.

**Approach:**
Developed multiple Python- and script-based tools:

**Divergence Debugging Tool**
- Analyzes solver logs and highlights instability root causes
- Identifies contact issues, material problems, and time-stepping concerns
- Result: 60% reduction in solver debugging time

**Selective Soldering PreProcessor**
- Fully automates geometry preparation and setup for selective soldering simulations
- Eliminates manual configuration and setup variability
- Result: 75% faster selective soldering setup

**Automated Reporting Pipeline**
- Generates standardized simulation reports from result files and templates
- Creates consistent visualizations and documentation
- Result: 50% less manual reporting effort

**Tools Used:** Python, Ansys Mechanical scripting, SpaceClaim scripting, pandas, numpy, matplotlib

**Overall Impact:** Achieved 10–40% reduction in simulation turnaround, freeing engineers to focus on model quality and interpretation.

---

## 5. SAE BAJA Off-Road Racing Vehicle (Team SAENIEKS)

**Challenge:** Design and build a competitive off-road racing vehicle under strict rules, performance targets, and resource constraints.

**Role & Responsibilities:**
- Managed a 40+ member team as Team Captain
- Led vehicle dynamics and electronics subsystems
- Designed uprights and suspension assemblies using DFM/DFA principles
- Created proof-of-concept DAQ system for capturing performance data

**Approach:**
- Applied systems thinking to balance performance, reliability, and cost
- Integrated design, analysis, and manufacturing considerations
- Developed data acquisition solution to feed real-world performance back into design
- Demonstrated closed-loop design validation methodology

**Tools Used:** SolidWorks, NX/Fusion 360, basic FEA, embedded/electronics integration

**Outcome:** Achieved top-10 national finish among 170+ teams, demonstrated end-to-end product development capability, and validated the use of data-driven design in a student racing environment.

---

## Additional Achievements

**Bosch Fit-fest 2025 Hackathon**
- Runner-up in Data Analytics / Anomaly Detection and Trend Forecasting tracks
- Developed data-driven software solution extending beyond traditional mechanical scope
- Demonstrated ability to frame engineering problems as data science challenges

**Certifications:**
- Certified Reliability Engineer (CRE) – ARAI
- SolidWorks Certified Associate (CSWA)
- Additive Manufacturing Certification
- Automation in Manufacturing (NPTEL)
- Autodesk CAD/CAM/CAE Certification
- Machine Learning Statistical Foundations

---

## Skills Summary

**Simulation & CAE:**
- Non-linear FEA (thermomechanical, static, transient, modal, vibration)
- Joints and assemblies (press-fit, cold weld, PCB taboo zones)
- Contact-heavy structures and tolerance-driven assemblies

**Programming & Automation:**
- Python, MATLAB, Ansys Mechanical scripting (MAPDL)
- Pre/post-processing automation, solver log analysis
- Reporting pipelines and data manipulation

**CAD & Product Development:**
- SolidWorks, NX, Fusion 360, SpaceClaim
- DFM/DFA principles, design optimization
- Cross-functional R&D collaboration

**Domains:**
- Electronic products (ECU, DC-DC, e-bike systems)
- Off-road vehicles and mechanical subsystems
- Reliability-driven design decisions

---

[← Back to Home](/)
```

---

## Summary of Directory Structure:
```
RoopeshShetty16.github.io/
│
├── _config.yml
├── index.md
├── simulation.md
├── automation.md
├── projects.md
│
├── _layouts/
│   └── default.html
│
└── assets/
    ├── css/
    │   └── style.scss
    ├── Roopesh_Profile.png  (upload your photo here)
    └── PyAnsys-Ecosystem.png
