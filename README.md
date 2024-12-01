# Error Correction in Quantum Key Distribution using Tree Parity Machines (TPMs)

This project demonstrates the use of Tree Parity Machines (TPMs) for error correction in Quantum Key Distribution (QKD). Alice and Bob synchronize their errored keys by training TPMs, ensuring secure key agreement without revealing sensitive information.

## Features
- **TPM Synchronization**: Implements TPM-based neural network synchronization for error correction.
- **Parameter Exploration**: Simulates various values for weight range, input size, and hidden neurons to achieve optimal synchronization.
- **Efficient Learning**: Identifies optimal parameters to ensure fast learning with minimal iterations.

## Project Overview
In Quantum Communication, noise and eavesdropping introduce errors in the shared key. This project uses TPMs as an artificial neural network model to correct these errors by synchronizing the weights of two networks held by Alice and Bob.

### Key Objectives
1. Synchronize TPMs to correct errors without disclosing key data.
2. Explore a wide range of parameters to accelerate network synchronization.
3. Minimize the number of iterations required for complete learning.

## Simulation Details
- **Weight Range (W)**: Explored multiple ranges to determine the impact on synchronization speed.
- **Number of Inputs (N)**: Tested varying input sizes to optimize learning efficiency.
- **Number of Hidden Neurons (L)**: Adjusted hidden neuron counts for robust and quick convergence.

## Results
- Achieved rapid synchronization through systematic exploration of TPM parameters.
- Reduced iterations required for synchronization, ensuring efficient error correction.

## Technologies Used
- **Python**: Primary programming language.
- **Qiskit**: Quantum computing framework (optional if related to your QKD simulation).
- **NumPy**: Used for numerical computations.
