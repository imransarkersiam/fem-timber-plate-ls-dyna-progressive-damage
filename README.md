# Finite Element Modelling of a Timber Plate Using LS-DYNA  
### Progressive Damage Analysis using MAT_054

> 🔬 A finite element analysis project focused on simulating progressive damage, stiffness degradation, and post-peak softening behaviour of timber using LS-DYNA.

---

## 📖 Overview
This project presents a detailed **Finite Element Modelling (FEM)** study of a timber plate subjected to uniaxial tensile loading. The objective is to investigate the **mechanical response and progressive damage behaviour** using a damage-based constitutive model (**MAT_054**) in LS-DYNA.

The study emphasizes:
- Accurate simulation of **damage initiation and evolution**
- Representation of **nonlinear material behaviour**
- Analysis of **post-peak softening and residual strength**

---

## ⚠️ Problem Statement
Timber and composite materials exhibit **anisotropic and progressive failure behaviour**, which cannot be accurately captured using conventional linear or elastic models.

Traditional design approaches often:
- Ignore **damage evolution**
- Fail to capture **post-peak behaviour**
- Underestimate **structural performance and safety**

👉 Therefore, advanced numerical modelling is required to simulate the **complete mechanical response**, including stiffness degradation and progressive failure.

---

## 🎯 Objectives
- Develop a finite element model of a timber plate under tensile loading  
- Implement **MAT_054 damage model** in LS-DYNA  
- Analyse **stress–time and displacement–time responses**  
- Derive and interpret **stress–strain behaviour**  
- Investigate **damage initiation and propagation**  
- Evaluate **post-peak softening and residual strength**  

---

## 🧩 Numerical Modelling Approach

### Geometry
- Total length: **140 mm**
- Gauge length: **80 mm**
- Grip regions: **30 mm (each side)**

### Mesh Strategy
- Structured mesh with **2 mm element size**
- ~70 elements along loading direction
- Ensures:
  - Accurate stress distribution
  - Numerical stability
  - Proper damage capture

### Boundary Conditions
- One end: Fully constrained  
- Other end: **Displacement-controlled loading**

---

## 🧪 Material Modelling (MAT_054)

The material behaviour is defined using a **damage-based composite model**, capable of capturing:

- Elastic response  
- Damage initiation  
- Stiffness degradation  
- Residual load-carrying capacity  

👉 This enables realistic simulation of **progressive failure mechanisms** in anisotropic materials.

---

## 📊 Key Results & Findings

- ✔ Initial **linear elastic behaviour** followed by nonlinear response  
- ✔ Peak stress ≈ **27 MPa**  
- ✔ Clear **damage initiation and evolution**  
- ✔ Significant **post-peak softening behaviour**  
- ✔ Smooth and stable displacement response  
- ✔ Presence of **residual strength after failure**

👉 The results confirm that the model successfully captures **progressive damage instead of brittle failure**.

---

## 🖼️ Simulation Results

### 🔹 Structured Mesh
![Mesh](images/mesh-model.png)

### 🔹 Stress Distribution (von Mises)
![Stress Distribution](images/stress-distribution.png)

### 🔹 Stress–Time Response
![Stress-Time](images/stress-time-curve.png)

### 🔹 Displacement–Time Response
![Displacement-Time](images/displacement-time-curve.png)

### 🔹 Stress–Strain Behaviour
![Stress-Strain](images/stress-strain-curve.png)

---

## 🏗️ Engineering Significance
This study demonstrates how FEM can be used for:

- Structural safety assessment  
- Damage modelling of anisotropic materials  
- FEM-based design validation  
- Timber and composite structural analysis  

👉 Particularly valuable for:
- Sustainable construction materials  
- Advanced structural simulations  
- Research-oriented engineering applications  

---

## 🛠️ Tools & Technologies
- LS-DYNA  
- LS-PrePost  
- Microsoft Excel  
- Microsoft Word  

---

## 💡 Skills Demonstrated
- Finite Element Modelling (FEM)  
- Constitutive damage modelling  
- Mesh discretisation strategy  
- Structural behaviour analysis  
- Simulation result interpretation  
- Engineering problem-solving  

---

## 📄 Full Project Report
📥 [Download Complete Report (PDF)](./FEM_Project_Timber_Damage_Analysis_LS-DYNA.pdf)

---

## 👨‍💻 Author
**Imran Sarker Siam**  
B.Sc. in Building Engineering & Construction Management  
Rajshahi University of Engineering & Technology (RUET), Bangladesh  

---

## 📌 Notes
This repository is created for **academic and professional portfolio purposes**, showcasing advanced simulation and modelling skills in structural engineering.

---

⭐ If you find this project useful, feel free to star the repository!
