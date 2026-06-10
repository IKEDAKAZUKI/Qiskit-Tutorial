<div align="center">

# Qiskit Tutorial

### From quantum-circuit fundamentals to research-level quantum simulation with Qiskit

[![Qiskit](https://img.shields.io/badge/Qiskit-Quantum%20SDK-6929C4)](https://www.ibm.com/quantum/qiskit)
[![Python](https://img.shields.io/badge/Python-3.x-blue)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![QET DOI](https://img.shields.io/badge/PhysRevApplied-10.1103%2FPhysRevApplied.20.024051-blue)](https://doi.org/10.1103/PhysRevApplied.20.024051)
[![JHEP DOI](https://img.shields.io/badge/JHEP-10.1007%2FJHEP02%282025%29118-red)](https://doi.org/10.1007/JHEP02%282025%29118)

<br>

**Gate operations · Measurements · Time evolution · Quantum teleportation · Quantum energy teleportation · Gauge theory · Green’s functions · Hadamard tests**

</div>

---

## Overview

This repository provides a compact but research-oriented collection of **Qiskit tutorials** for quantum information science, quantum many-body physics, and quantum simulation.

The notebooks begin with the foundations of quantum circuits and measurements, then progress toward advanced topics including:

- universal quantum gate operations,
- quantum measurement and expectation values,
- time evolution and quench dynamics,
- Ising-model simulations and phase transitions,
- adiabatic algorithms and adiabatic state preparation,
- quantum teleportation,
- quantum energy teleportation,
- lattice gauge theory simulations,
- Green’s functions, two-point functions, and Hadamard tests.

The goal is to provide practical, executable examples of quantum-computing techniques that are useful for modern quantum physics research.

---

## Repository contents

| Topic | Notebook | Run |
|---|---|---|
| Qiskit fundamentals, measurement, time evolution, Ising model, phase transition | [`Qiskit_Tutorial.ipynb`](Qiskit_Tutorial.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/IKEDAKAZUKI/Qiskit-Tutorial/blob/main/Qiskit_Tutorial.ipynb) |
| Quantum teleportation | [`Quantum_Teleportation.ipynb`](Quantum_Teleportation.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/IKEDAKAZUKI/Qiskit-Tutorial/blob/main/Quantum_Teleportation.ipynb) |
| Quantum energy teleportation | [`Quantum_Energy_Teleportation.ipynb`](Quantum_Energy_Teleportation.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/IKEDAKAZUKI/Qiskit-Tutorial/blob/main/Quantum_Energy_Teleportation.ipynb) |
| Quantum simulation of gauge theory: Schwinger model | [`Quantum_simulation_of_Schwinger_model.ipynb`](Quantum_simulation_of_Schwinger_model.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/IKEDAKAZUKI/Qiskit-Tutorial/blob/main/Quantum_simulation_of_Schwinger_model.ipynb) |
| Green’s functions, two-point functions, n-point correlation functions, Hadamard test | [`Quantum_computation_of_n_point_correpation_functions.ipynb`](Quantum_computation_of_n_point_correpation_functions.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/IKEDAKAZUKI/Qiskit-Tutorial/blob/main/Quantum_computation_of_n_point_correpation_functions.ipynb) |

> Note: the filename `Quantum_computation_of_n_point_correpation_functions.ipynb` is kept as it appears in the repository.

---

## Learning path

### 1. Qiskit fundamentals

Start with:

```text
Qiskit_Tutorial.ipynb
```

This notebook introduces the basic workflow of quantum programming with Qiskit:

- creating quantum circuits,
- applying one-qubit and two-qubit gates,
- measuring quantum states,
- running circuits on simulators,
- visualizing measurement outcomes,
- computing expectation values,
- working with density matrices,
- computing entanglement entropy,
- simulating time evolution,
- studying the Ising model and phase-transition dynamics.

---

### 2. Quantum teleportation

Continue with:

```text
Quantum_Teleportation.ipynb
```

This notebook demonstrates the standard quantum teleportation protocol using elementary quantum gates, entanglement, Bell measurements, and classical feed-forward operations.

It provides a useful bridge between basic circuit construction and more advanced protocols based on local operations and classical communication.

---

### 3. Quantum energy teleportation

The notebook

```text
Quantum_Energy_Teleportation.ipynb
```

introduces the circuit-level implementation of **quantum energy teleportation**.

For the complete research code and updated hardware demonstrations, see the related repository:

```text
https://github.com/IKEDAKAZUKI/Quantum-Energy-Teleportation
```

This tutorial is connected to the experimental demonstration reported in:

> K. Ikeda,  
> **“Demonstration of Quantum Energy Teleportation on Superconducting Quantum Hardware,”**  
> *Physical Review Applied* **20**, 024051 (2023).  
> DOI: [10.1103/PhysRevApplied.20.024051](https://doi.org/10.1103/PhysRevApplied.20.024051)  
> arXiv: [2301.02666](https://arxiv.org/abs/2301.02666)

---

### 4. Quantum simulation of gauge theory

The notebook

```text
Quantum_simulation_of_Schwinger_model.ipynb
```

develops a Qiskit-based tutorial for the quantum simulation of the massive Schwinger model, a `1+1` dimensional `U(1)` lattice gauge theory.

Topics include:

- the Schwinger-model Lagrangian,
- lattice Hamiltonian formulation,
- Jordan-Wigner transformation,
- spin Hamiltonian representation,
- local charge operators,
- static and dynamical simulations,
- adiabatic state preparation,
- phase-transition demonstrations using time-dependent Hamiltonians.

This notebook is intended as a gateway from introductory quantum circuits to quantum simulation in high-energy physics.

---

### 5. Green’s functions, two-point functions, and Hadamard tests

The notebook

```text
Quantum_computation_of_n_point_correpation_functions.ipynb
```

covers quantum-computing methods for correlation functions and Hadamard-test-based measurements.

Topics include:

- Hadamard test circuits,
- real and imaginary parts of transition amplitudes,
- two-point correlation functions,
- n-point correlation functions,
- Green’s-function-style observables,
- quantum simulation workflows relevant to lattice field theory.

This part is connected to the research context of real-time quantum simulation for timelike correlation functions:

> J. Barata, K. Ikeda, S. Mukherjee, J. Raghoonanan,  
> **“Towards a real-time computation of timelike hadronic vacuum polarization and light-by-light scattering: Schwinger Model tests,”**  
> *Journal of High Energy Physics* **2025**, 118 (2025).  
> DOI: [10.1007/JHEP02(2025)118](https://doi.org/10.1007/JHEP02%282025%29118)

---

## Quick start

Clone the repository:

```bash
git clone https://github.com/IKEDAKAZUKI/Qiskit-Tutorial.git
cd Qiskit-Tutorial
```

Create a Python virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate
```

For Windows PowerShell:

```bash
.venv\Scripts\Activate.ps1
```

Install the recommended packages:

```bash
pip install qiskit qiskit-aer numpy scipy matplotlib jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Then open any of the tutorial notebooks.

---

## Running in Google Colab

Each notebook can also be opened directly in Google Colab using the badges in the table above.

For Colab execution, run the package-installation cell at the beginning of each notebook before executing the remaining cells.

---

## Suggested order of study

For students and researchers new to Qiskit, the recommended order is:

```text
1. Qiskit_Tutorial.ipynb
2. Quantum_Teleportation.ipynb
3. Quantum_Energy_Teleportation.ipynb
4. Quantum_simulation_of_Schwinger_model.ipynb
5. Quantum_computation_of_n_point_correpation_functions.ipynb
```

This sequence moves from basic circuit operations to research-level applications in quantum many-body dynamics and lattice gauge theory.

---

## Repository structure

```text
.
├── Qiskit_Tutorial.ipynb
├── Quantum_Teleportation.ipynb
├── Quantum_Energy_Teleportation.ipynb
├── Quantum_simulation_of_Schwinger_model.ipynb
├── Quantum_computation_of_n_point_correpation_functions.ipynb
├── LICENSE
└── README.md
```

---

## Related repository

For the complete implementation of quantum energy teleportation on IBM Quantum systems, see:

```text
https://github.com/IKEDAKAZUKI/Quantum-Energy-Teleportation
```

That repository includes the full QET demonstration, updated 2025 workflows, and error-mitigation examples for IBM Quantum hardware.

---

## References

### Quantum energy teleportation

K. Ikeda,  
**“Demonstration of Quantum Energy Teleportation on Superconducting Quantum Hardware,”**  
*Physical Review Applied* **20**, 024051 (2023).  
DOI: [10.1103/PhysRevApplied.20.024051](https://doi.org/10.1103/PhysRevApplied.20.024051)  
arXiv: [2301.02666](https://arxiv.org/abs/2301.02666)

### Green’s functions, two-point functions, and Hadamard tests

J. Barata, K. Ikeda, S. Mukherjee, J. Raghoonanan,  
**“Towards a real-time computation of timelike hadronic vacuum polarization and light-by-light scattering: Schwinger Model tests,”**  
*Journal of High Energy Physics* **2025**, 118 (2025).  
DOI: [10.1007/JHEP02(2025)118](https://doi.org/10.1007/JHEP02%282025%29118)

---

## Citation

If you use the quantum energy teleportation tutorial, please cite:

```bibtex
@article{Ikeda2023QET,
  author  = {Ikeda, Kazuki},
  title   = {Demonstration of Quantum Energy Teleportation on Superconducting Quantum Hardware},
  journal = {Physical Review Applied},
  volume  = {20},
  pages   = {024051},
  year    = {2023},
  doi     = {10.1103/PhysRevApplied.20.024051}
}
```

If you use the Green’s-function, two-point-function, or Hadamard-test tutorial in connection with real-time Schwinger-model simulations, please cite:

```bibtex
@article{Barata2025SchwingerTimelike,
  author  = {Barata, Jo{\~a}o and Ikeda, Kazuki and Mukherjee, Swagato and Raghoonanan, Jonathan},
  title   = {Towards a Real-Time Computation of Timelike Hadronic Vacuum Polarization and Light-by-Light Scattering: Schwinger Model Tests},
  journal = {Journal of High Energy Physics},
  volume  = {2025},
  pages   = {118},
  year    = {2025},
  doi     = {10.1007/JHEP02(2025)118}
}
```

---

## License

This repository is released under the [MIT License](LICENSE).

---

<div align="center">

**Qiskit Tutorial · Quantum Simulation · Quantum Information · Lattice Gauge Theory**

</div>
