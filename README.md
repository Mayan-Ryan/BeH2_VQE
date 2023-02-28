# Ground State Energy Calculation of BeH2 Molecule Using Variational Quantum Eigensolver (VQE) Algorithm in Qiskit Nature

### Introduction:

The accurate calculation of the ground state energy of molecules is an important problem in chemistry and materials science. Quantum computing provides a promising avenue for solving this problem, and VQE is one of the most promising algorithms for ground state energy calculation on quantum computers. This project aims at simulating and calculating the ground state energy of the Beryllium Hydride molecule(BeH2) using the Variational Quantum Eigensolver algorithm. 
The project has been written using qiskit and qiskit-nature on a ipynb file supported by a CUDA enabled GPU. 

### Objectives:

1. Obtained the molecular Hamiltonian for BeH2 using the PySCF driver in Qiskit Nature.The initial state of the hamiltonian has been calculated using the Hartree-Fock Method.
2. Used the JordanWignerMapper to map the molecular Hamiltonian to a qubit Hamiltonian.
3. Implemented VQE algorithm using Qiskit Nature's VQE class, with a Unitary Coupled-Cluster Single and Double excitations ansatz and Gradient Descent optimizer.
4. Used the statevector simulator backend in Qiskit to run the VQE algorithm and obtain the ground state energy of BeH2.
5. Compared the results with exact values obtained from  NumPyMinimumEigensolverFactory algorithm.
