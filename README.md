# quiskit-fall-fest-2025
PS : Simulate a Variational Quantum Eigensolver (VQE) for the ground state energy of H₂ molecule.

## Overview

VQE is a hybrid algorithm that combines a quantum computer's ability to represent quantum states with a classical optimizer. The goal is to approximate the lowest energy (ground state) of a H₂ molecule.

Workflow:

1. Build the H₂ molecule and get its Hamiltonian
2. Choose an ansatz (your adjustable quantum circuit)
3. Set up the VQE algorithm
4. Run it with a Qiskit simulator to extract the ground-state energy
5. Wrap everything inside Streamlit/Other platform to visualize results interactively