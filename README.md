# Project Information

**Project Name**: Quantum Walks and Monte Carlo

**Team Name**: KiDa

# Team Information
**1.** **Name**: Kirill Vyskubov, **ID**: gst-Qeve8dmXLVTMqyj

**2.** **Name**: Danil Vyskubov,  **ID**: gst-0QcrPsUq9OPHwGs

# Summary 

## Aim
This project explores the quantum mechanical analogs of classical probability systems, in particular, the Galton board and quantum walks, to demonstrate how quantum effects can generate unique statistical distributions. The primary aims are:

Simulate Quantum-Enhanced Randomness: Compare classical (normal/exponential) and quantum (hadamard quantum walk) distributions.
Lay Groundwork for Applications: Develop scalable and efficient quantum circuits for random number generation, optimization, and physical system modeling.

## Value
Educational Insight: The quantum Galton board bridges classical probability and quantum mechanics, making quantum effects such as superposition, entanglement, and interference tangible.

Algorithmic Development: Provides skills of algorithm prototyping for implementing quantum Galton board and quantum walks, which underpin advances in quantum search and optimization.

## Implementation
The project was implemented in Qiskit, leveraging:

### 1) Quantum Galton Board
Circuit Design:

Used Hadamard gates for unbiased pegs (normal distribution)

Replaced with Rx(θ) gates for biased pegs (exponential distribution)

### 2) Quantum Walk
Core Operations:

Coin Flip: Hadamard gate creates superposition (|0⟩ + |1⟩)

Conditional Shift: CNOT gates update position qubits based on the coin state.

### 3) Simulation & Visualization
Backend: AerSimulator for noiseless, all-to-all connectivity sampling.

Post-Processing: Mapped quantum measurements to physical positions and plotted distributions using Matplotlib.

## Applications

### Cryptography:

Quantum walks generate certifiable randomness for encryption keys.

Example: Secure random numbers for quantum key distribution (QKD).

### Financial Modeling:

Simulates non-Gaussian market fluctuations better than classical random walks.

### Biology & Chemistry:

Models energy transfer in photosynthetic complexes via quantum walk dynamics.

### Optimization:

Quantum walks enable O(√N) search speeds in unstructured databases (Grover’s algorithm variant).

## Conclusion
This project demonstrates how quantum systems can outperform classical analogs in generating complex distributions and solving computational problems. By implementing a quantum Galton board and quantum walks, it provides a visual framework for quantum probabilities and opens opportunities for high-quality randomness generation and quantum-enhanced algorithms

