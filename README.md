# Physics Self-Study

Self-paced, code-driven study of core undergraduate physics — focusing on **mechanics, quantum mechanics, probability, and numerical methods**.  
All notebooks are reproducible using the included Python virtual environment.

---

## 🎯 Objective

Build a rigorous, computational foundation in theoretical physics by:
- Translating analytical derivations into reproducible numerical experiments.  
- Developing intuition for dynamical systems, operator formalism, and probabilistic modeling.  
- Producing a coherent body of work bridging physics and computation.

---

## 📚 Roadmap

### **Taylor – Classical Mechanics**
**Ch. 4–10** → Lagrangians, generalized coordinates, conservation laws, Hamilton’s equations, canonical transformations  
**Goals:** derive and simulate classical systems; connect Hamiltonian form to quantum analogs.  
**Notebooks:**
- Lagrangian and Hamiltonian dynamics  
- Central-force motion and effective potentials  
- Canonical transformations, Poisson brackets  
- Simple and double pendulum simulations  

---

### **Strang – Linear Algebra and Its Applications**
**Core topics:** eigenvalues, eigenvectors, diagonalization, projections, matrix exponentials  
**Goals:** master operator algebra and matrix methods underpinning quantum mechanics.  
**Notebooks:**
- Eigen-decomposition and basis change  
- Gram–Schmidt and orthogonal projections  
- Matrix exponentials `expm(–iHt)` for time evolution  

---

### **Zettili – Quantum Mechanics: Concepts and Applications**
**Ch. 1–6** → wave mechanics, operators, angular momentum, spin, and time evolution  
**Goals:** formal comfort with Hilbert space and operator dynamics; numerical TDSE solutions.  
**Notebooks:**
- Infinite-square-well and harmonic-oscillator eigenstates  
- Spectral decomposition and time evolution  
- Spin-½ systems and expectation values  
- 3×3 ring tight-binding Hamiltonian propagation  

---

### **Ross – A First Course in Probability**
**Core topics:** random variables, joint/conditional distributions, expectations, independence  
**Goals:** bridge probability with statistical mechanics and stochastic modeling.  
**Notebooks:**
- PDF/CDF visualization and expectations  
- Covariance and independence checks  
- Monte Carlo integration and random sampling  

---

### **Schroeder – Thermal Physics** *(optional synthesis)*
**Focus:** ensembles, Boltzmann factors, partition functions  
**Goal:** connect probabilistic mechanics to thermodynamic intuition.  
**Notebook:** derive and simulate canonical ensembles.

---

## 🧮 Tools

**Language:** Python 3.12+  
**Libraries:** `numpy`, `scipy`, `sympy`, `matplotlib`, `jupyter`  
**Environment:** `.venv` (see `requirements.txt`)

---

## 📁 Repository Structure
physics-self-study/
├── notebooks/
│   ├── mechanics/
│   ├── quantum/
│   ├── probability/
│   └── numerics/
└── README.md

---

**Author:** Roger Nguyen  