# Qiskit Global Summer School 2025 - Labs Repository

Welcome to my comprehensive repository for the **Qiskit Global Summer School 2025** labs! This repository contains completed solutions for Lab-0, Lab-1, and Lab-2, along with work-in-progress solutions for Lab-3, Lab-4, and the Functions Labs.

## 📚 Repository Structure

```
├── lab-0/           # ✅ COMPLETED - Hello Quantum World
├── lab-1/           # ✅ COMPLETED - Quantum Foundations  
├── lab-2/           # 🔄 IN PROGRESS - Cutting Through the Noise
├── lab-3/           # 🔄 IN PROGRESS - Quantum Chemistry Simulation
├── lab-4/           # 🔄 IN PROGRESS - Quantum Error Correction
└── functions-labs/  # 🔄 IN PROGRESS - Industry Partner Functions
```

## 🚀 Lab Overview

### Lab-0: Hello Quantum World! ✅
**Status: COMPLETED**

This introductory lab covers the fundamentals of getting started with Qiskit and quantum computing.

**Key Topics:**
- Installation of Qiskit and grader setup
- IBM Cloud API token configuration  
- Creating and optimizing quantum circuits
- Generating a three-qubit GHZ state using Qiskit patterns
- Circuit execution on simulators and real quantum hardware
- Post-processing and visualization of quantum results

**Exercises:**
- Environment setup and troubleshooting
- GHZ state preparation and analysis
- **Bonus Challenge:** Running circuits on actual quantum hardware

### Lab-1: Quantum Foundations Through Experiments ✅  
**Status: COMPLETED**

Deep dive into fundamental quantum phenomena through hands-on Qiskit experiments.

**Key Topics:**
- **Superposition & Interference:** Double-slit experiment, Schrödinger's Cat
- **Quantum Measurement:** Understanding measurement effects on quantum states
- **Entanglement:** CHSH Game, Quantum Teleportation protocols

**Exercises:**
1. **Double-slit Experiment** - Quantum circuit implementation with interference patterns
2. **Schrödinger's Cat** - Interactive widget with RX(θ) gate and measurement
3. **Which-Path Detection** - Observing decoherence effects
4. **CHSH Game** - Bell state preparation and quantum advantage demonstration  
5. **CHSH Analysis** - Win probability calculations vs classical limits
6. **Quantum Teleportation** - Complete 3-qubit protocol with dynamic circuits
7. **Teleportation Verification** - Statevector simulation and Bloch sphere visualization

### Lab-2: Cutting Through the Noise ✅
**Status: COMPLETED** 

Advanced techniques for quantum noise characterization and mitigation using Max-cut optimization problems.

**Key Topics:**
- Quantum noise sources and characterization
- QAOA (Quantum Approximate Optimization Algorithm) implementation
- Graph-to-Hamiltonian mappings for optimization problems
- Transpiler optimization for quantum circuits
- Zero Noise Extrapolation (ZNE) error mitigation

**Exercises:**
1. **Best Qubits Analysis** - Finding optimal qubits by T1, T2, gate fidelities, and readout errors
2. **Graph to Hamiltonian** - Converting optimization problems to Ising Hamiltonians  
3. **Error Estimation** - Calculating total circuit errors across different backends
4. **Layout Optimization** - Finding qubit layouts with minimal two-qubit gate errors
5. **Transpiler Optimization** - Using transpiler for optimal circuit layout
6. **ZNE Implementation** - Global and local folding techniques for error mitigation

### Lab-3: Quantum Chemistry with Sample-based Quantum Diagonalization 🔄
**Status: IN PROGRESS**

Exploration of quantum chemistry simulation using the Sample-based Quantum Diagonalization (SQD) method.

**Key Topics:**
- Variational Quantum Eigensolver (VQE) fundamentals
- Sample-based Quantum Diagonalization (SQD) algorithm
- N₂ molecule simulation in various basis sets
- Quantum chemistry Hamiltonian construction
- Ansatz optimization for molecular systems

**Exercises:**
- Hamiltonian size calculations for O₂ molecule
- VQE vs SQD algorithm comparison
- N₂ molecule simulation with error mitigation
- Ansatz improvement techniques
- **Bonus:** Real hardware execution with advanced error mitigation

### Lab-4: Quantum Error Correction Fundamentals 🔄  
**Status: IN PROGRESS**

Comprehensive introduction to quantum error correction from basic concepts to fault-tolerant quantum computing.

**Key Topics:**
- **Classical Error Correction:** [n,k,d] codes, Hamming distance, repetition codes
- **Quantum Error Correction:** Stabilizer formalism, 3-qubit bit-flip code, CSS codes
- **Advanced QEC:** Steane code, QLDPC codes, Toric codes, Surface codes

**Exercises:**
1. Classical and quantum lookup table decoders
2. Syndrome measurement circuit construction  
3. Parity check matrix construction for advanced codes
4. Logical qubit counting via matrix rank calculations
5. Implementation of stabilizer measurements
6. Advanced QEC architecture analysis

## 🏢 Functions Labs: Industry Partner Collaborations 🔄
**Status: IN PROGRESS**

Exclusive access to cutting-edge quantum functions from leading industry partners.

### Available Functions:

#### 🔬 **Algorithmiq - Tensor Network Error Mitigation (TEM)**
- **Focus:** Many-body physics simulations with advanced error mitigation
- **Application:** Kicked Ising model simulation on 91+ qubits
- **Key Features:** Tensor network-based error correction, real device optimization

#### 🌊 **ColibriTD - QUICK-PDE Solver**  
- **Focus:** Computational Fluid Dynamics on quantum computers
- **Application:** Solving Burger's equation for non-viscous fluid flow
- **Key Features:** H-DES (Hybrid Differential Equation Solver), multi-physics problems

#### 💰 **Global Data Quantum - Portfolio Optimizer**
- **Focus:** Dynamic portfolio optimization using quantum algorithms  
- **Application:** Multi-period investment strategy optimization
- **Key Features:** QUBO formulation, risk-return optimization, transaction cost minimization

#### ⚡ **Kipu Quantum - Iskay Optimizer**
- **Focus:** Binary optimization using BF-DCQO algorithm
- **Application:** QUBO and HUBO problem solving with up to 156 qubits
- **Key Features:** Non-variational quantum optimization, counterdiabatic protocols

#### 🔄 **Multiverse Computing** - Advanced Optimization Functions
#### 🎛️ **Q-CTRL** - Quantum Control Optimization  
#### 🛡️ **QEDMA** - Error Suppression and Mitigation
#### 🚀 **Qunova** - Quantum Algorithm Implementations

## 🤝 Contributing

This repository welcomes contributions! Whether you're looking to:
- Complete the remaining exercises in Lab-2, Lab-3 and Lab-4
- Explore the Functions Labs with industry partners
- Add alternative solution approaches
- Improve documentation and explanations
- Add visualizations and analysis tools

### How to Contribute:
1. Fork this repository
2. Create a feature branch (`git checkout -b feature/lab-improvement`)
3. Make your changes and test thoroughly
4. Add clear documentation and comments
5. Submit a pull request with detailed description

### Areas Needing Contribution:
- [ ] Complete Lab-3 quantum chemistry exercises
- [ ] Finish Lab-4 quantum error correction implementations  
- [ ] Explore all 8 Functions Labs from industry partners
- [ ] Add comprehensive test suites
- [ ] Create interactive visualizations
- [ ] Develop additional learning resources

## 🛠️ Setup and Requirements

### Prerequisites:
```bash
# Core Qiskit packages
pip install qiskit[visualization]
pip install qiskit-ibm-runtime
pip install qiskit-aer

# Additional dependencies
pip install matplotlib numpy pandas
pip install qiskit-algorithms qiskit-optimization
pip install networkx rustworkx

# For Functions Labs
pip install qiskit-ibm-catalog
pip install qiskit-serverless
```

### IBM Quantum Platform Setup:
1. Create account at [IBM Quantum Platform](https://quantum.ibm.com/)
2. Get your API token from account settings
3. Configure your environment with the token
4. **For Functions Labs:** Requires Premium or Flex Plan access

## 📖 Learning Resources

- **Official QGSS Materials:** [Qiskit Community Repository](https://github.com/qiskit-community/qgss-2025)
- **Qiskit Textbook:** [Learn Quantum Computing](https://qiskit.org/textbook/)
- **IBM Quantum Network:** [Educational Resources](https://quantum.ibm.com/learning)
- **Qiskit YouTube:** [Video Tutorials](https://www.youtube.com/c/qiskit)

## 📋 Current Status Summary

| Lab | Status | Progress | Key Features |
|-----|--------|----------|--------------|
| Lab-0 | ✅ Complete | 100% | GHZ states, hardware execution |
| Lab-1 | ✅ Complete | 100% | Quantum foundations, teleportation |  
| Lab-2 | 🔄 In Progress | 65% | Noise mitigation, QAOA |
| Lab-3 | 🔄 In Progress | 40% | Quantum chemistry, SQD |
| Lab-4 | 🔄 In Progress | 35% | Quantum error correction |
| Functions | 🔄 In Progress | 25% | Industry partnerships |

## 🌟 Highlights and Achievements

- **Real Hardware Experience:** Successfully executed quantum circuits on IBM quantum computers
- **Advanced Algorithms:** Implemented QAOA, VQE, and error mitigation techniques  
- **Industry Applications:** Explored cutting-edge quantum functions from leading companies
- **Comprehensive Coverage:** From basic concepts to advanced quantum error correction

## 📞 Contact and Support

Feel free to open issues for:
- Questions about specific exercises
- Bug reports or code improvements
- Suggestions for additional features
- Collaboration opportunities

*This repository represents hands-on learning and experimentation with quantum computing concepts through the prestigious Qiskit Global Summer School 2025 program.*

**Happy Quantum Computing! 🚀⚛️**
