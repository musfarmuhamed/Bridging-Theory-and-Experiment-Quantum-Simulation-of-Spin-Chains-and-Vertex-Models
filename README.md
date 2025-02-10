# Bridging Theory and Experiment: Quantum Simulation of Spin Chains and Vertex Models

## Project Overview
This project focuses on simulating quantum many-body systems using quantum hardware. We explore two fundamental models in statistical mechanics and condensed matter physics:
- **The Heisenberg Spin Chain**, simulated on **IonQ’s trapped-ion quantum processor**.
- **The Six-Vertex Model**, implemented on **QuEra’s neutral atom quantum processor**.

Through quantum simulations, we aim to benchmark quantum hardware capabilities against exact mathematical predictions derived from the Bethe Ansatz and Yang-Baxter equations. Detailed project proposal is given in [Comparative Study of the Heisenberg Spin Chain using IonQ and the Six-Vertex Model using QuEra](https://github.com/musfarmuhamed/Bridging-Theory-and-Experiment-Quantum-Simulation-of-Spin-Chains-and-Vertex-Models/blob/main/Proposal_Spin_Chian_Six_Vertex.pdf).


## Key Objectives
- Implement the Heisenberg spin chain on IonQ.
- Implement the Six-Vertex model on QuEra.
- Compare simulation results with theoretical predictions.
- Analyze hardware constraints and quantum noise effects.
- Evaluate quantum error mitigation techniques.

## Motivation
The Heisenberg spin chain and Six-Vertex model are deeply connected through integrability structures. This project provides a first-of-its-kind comparative study to understand the performance of different quantum architectures for simulating many-body quantum interactions.

See my previous work on theory of Heisenberg Spin Chain and Six-Vertex Model in [Heisenberg Spin Chain and Six-Vertex Model](https://github.com/musfarmuhamed/Bridging-Theory-and-Experiment-Quantum-Simulation-of-Spin-Chains-and-Vertex-Models/blob/main/MS_Project-Musfar.pdf).


## Implementation Details
###   1. Heisenberg Spin Chain on IonQ
- Mapping spin operators to qubits using Jordan-Wigner transformation.
- Trotterized time evolution circuits.
- Measurement of ground state energy, correlation functions, and entanglement entropy.
- Error mitigation techniques such as dynamical decoupling.

###   2. Six-Vertex Model on QuEra
- Encoding arrow configurations into a spin-based system.
- Transfer matrix approach implementation using neutral atom arrays.
- Analysis of phase transitions via high-resolution imaging.

###   3. Comparative Study
- Benchmarking results against classical simulations.
- Evaluating hardware-specific limitations and decoherence effects.
- Identifying key challenges and potential optimizations for quantum many-body simulations.

## Expected Outcomes
- Successful implementation of quantum circuits for both models.
- Hardware performance insights for quantum integrability simulations.
- Open-source codebase for further research and experimentation.
- Publications in quantum computing and condensed matter physics journals.

