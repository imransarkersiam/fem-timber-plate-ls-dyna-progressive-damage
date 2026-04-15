# Finite Element Modelling of a Timber Plate Using LS-DYNA  
### Progressive Damage Analysis using MAT_054

A finite element analysis project investigating the mechanical response and progressive damage behaviour of a timber plate under uniaxial tensile loading using LS-DYNA.

---

## Overview
This project presents a detailed finite element modelling (FEM) study of a timber plate subjected to tensile loading. The analysis focuses on capturing nonlinear material behaviour, including damage initiation, stiffness degradation, and post-peak softening using a damage-based constitutive model (MAT_054).

---

## Problem Statement
Timber and composite materials exhibit anisotropic and progressive failure behaviour, which cannot be accurately represented using conventional linear or elastic models. Traditional design approaches often fail to capture damage evolution and post-peak response, leading to inaccurate estimation of structural performance.

This project addresses this limitation by implementing a damage-based numerical model to simulate the complete mechanical response of timber under tensile loading.

---

## Objectives
- Develop a finite element model of a timber plate under tensile loading  
- Implement the MAT_054 damage model in LS-DYNA  
- Analyse stress–time and displacement–time responses  
- Derive and interpret stress–strain behaviour  
- Investigate damage initiation and evolution  
- Evaluate post-peak softening and residual strength  

---

## Numerical Modelling Approach

### Geometry
- Total length: 140 mm  
- Gauge length: 80 mm  
- Grip regions: 30 mm (each side)  

### Mesh
- Structured mesh with 2 mm element size  
- Approximately 70 elements along loading direction  
- Ensures numerical stability and accurate stress representation  

### Boundary Conditions
- One end fully constrained  
- Displacement-controlled loading applied at the opposite end  

---

## Material Modelling
The material behaviour is defined using MAT_054 in LS-DYNA, a damage-based model capable of representing:
- Elastic response  
- Damage initiation  
- Stiffness degradation  
- Residual load-carrying capacity  

This formulation enables realistic simulation of progressive failure in anisotropic materials.

---

## Key Results
- Linear elastic behaviour followed by nonlinear response  
- Peak stress approximately 27 MPa  
- Progressive damage evolution observed  
- Post-peak softening behaviour captured  
- Stable displacement response throughout the simulation  
- Residual strength retained after peak load  

---

## Results

### Structured Mesh
![Mesh](images/mesh-model.png)

### Stress Distribution
![Stress Distribution](images/stress-distribution.png)

### Stress–Time Response
![Stress-Time](images/stress-time-curve.png)

### Displacement–Time Response
![Displacement-Time](images/displacement-time-curve.png)

### Stress–Strain Behaviour
![Stress-Strain](images/stress-strain-curve.png)

---

## Engineering Significance
This study demonstrates the application of finite element modelling for analysing the structural behaviour of timber-like materials. The approach can be applied in structural safety assessment, design validation, and damage modelling of anisotropic materials.

---

## Tools Used
- LS-DYNA  
- LS-PrePost  
- Microsoft Excel  
- Microsoft Word  

---

## Skills Demonstrated
- Finite Element Modelling (FEM)  
- Constitutive damage modelling  
- Mesh discretisation  
- Structural analysis  
- Simulation result interpretation  

---

## Project Report
[Download the full report (PDF)](./FEM_Project_Timber_Damage_Analysis_LS-DYNA.pdf)

---

## Author
Imran Sarker Siam  
B.Sc. in Building Engineering & Construction Management  
Rajshahi University of Engineering & Technology (RUET), Bangladesh  

---

## Notes
This repository is intended for academic and professional portfolio purposes.
