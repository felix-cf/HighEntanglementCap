## High-Entanglement Capabilities for Variational Quantum Algorithms: The Poisson Equation Case

This repository contains the data and code used for the paper https://arxiv.org/abs/2406.10156.

Abstract:
The discretized Poisson equation matrix (DPEM) in 1D has been shown to require an exponentially large number of terms when decomposed in the Pauli basis when solving numerical linear algebra problems on a quantum computer. Additionally, traditional ansatz for Variational Quantum Algorithms (VQAs) that are used to heuristically solve linear systems (such as the DPEM) have many parameters, making them harder to train. This research attempts to resolve these problems by utilizing the IonQ Aria quantum computer capabilities that boast all-to-all connectivity of qubits. We propose a decomposition of the DPEM that is based on 2- or 3-qubit entanglement gates and is shown to have $O(1)$ terms with respect to system size, with one term having an $O(n^2)$ circuit depth and the rest having only an $O(1)$ circuit depth (where $n$ is the number of qubits defining the system size). Additionally, we introduce the Globally-Entangling Ansatz which reduces the parameter space of the quantum ansatz while maintaining enough expressibility to find the solution. To test these new improvements, we ran numerical simulations to examine how well the VQAs performed with varying system sizes, showing that the new setup offers an improved scaling of the number of iterations required for convergence compared to Hardware-Efficient Ansatz.

The presentation listed was presented at the Johns Hopkins University Applied Math Department's 2024 MATRX Undergraduate Conference as a lecture. 

https://github.com/felix-cf/HighEntanglementCap/blob/main/Quantum%20Computing%20for%20Computational%20Fluid%20Dynamics_%20The%20Poisson%20Equation.pdf

The poster was also presented at the 2024 MATRX Undergraduate conference and won the first place prize. 

https://github.com/felix-cf/HighEntanglementCap/blob/main/qc_for_cfd.pdf

2024 MATRX Undergraduate Conference website: https://www.ams.jhu.edu/matrx2024/
