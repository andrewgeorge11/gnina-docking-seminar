# GNINA Flexible Docking on 5HT1B Receptor States

##  Project Overview
This project implements rigid and flexible protein-ligand docking experiments using **GNINA** on the **5HT1B receptor**, comparing active and inactive states. We explore eight experimental configurations to evaluate ligand binding and conformational impact using RMSD.

## Tools Used
- GNINA (for docking)
- PDBFixer (protein preparation)
- Open Babel (.sdf format)
- PyMOL (visualization)

##  Structure
- notebooks: Workflow implementation in Jupyter
_ proteins: 4IAQ (inactive), 6G79 (active) PDBs
- ligands: Ligands 2GM and EP5 (.sdf)
- docking_results: Results CSVs (1–8 experiments)
- images: Binding pose visualizations


##  Experiments Summary
The goal of this experiment is to try to reproduce the activation of the 5HT1B serotonin receptor by simulating its conformational changes in the binding pocket.
Two structures of the 5HT1B receptor are used: 4IAQ, which represents the inactive state, and 6G79, which is in the active state with its co-crystallized ligand.
Using flexible docking, the ligand from 6G79 will be docked into the binding site of 4IAQ. 
This approach will simulate the receptor's activation by introducing an active-state ligand to the inactive structure. 
By analyzing the resulting conformational changes and comparing them to the active 6G79 structure, this experiment aims to model how ligand binding drives receptor activation.

## Results
Rigid docking consistently outperformed flexible docking, yielding lower RMSD values and more accurate ligand poses across redocking and cross-docking experiments.
Cross-docking introduced higher RMSDs, highlighting the specificity of ligand–protein interactions and the challenge of binding in non-native conformations.


##  Author
Andrew Zaki  M.Sc. Bioinformatics, Saarland University
Denis Semkin  M.Sc. Bioinformatics, Saarland University

