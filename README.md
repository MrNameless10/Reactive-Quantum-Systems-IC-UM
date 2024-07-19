# Reactive Quantum Systems - Interacção e Concorrência 2023/2024

### Learning Outcomes
- Understand the foundational and advanced aspects of reactive and quantum systems.
- Master techniques for specifying, analyzing, and verifying reactive and quantum systems.
- Utilize computational tools for system specification and analysis effectively.

### Syllabus Highlights
- **Reactive Systems**: Concepts of interaction and concurrency, process algebra, and modal logics.
- **Quantum Systems**: Fundamentals of quantum computation, including quantum algorithms like Deutsch-Jozsa and Grover's algorithm.

## Repository Contents
- `QuantumComputing/`: Implementations and explanations of quantum algorithms.
- `ReactiveSystems/`: Models and analyses of various reactive system configurations.
- `Slides/`: Lecture slides that accompany the practical exercises.
- `Exercises/`: Solutions to exercise sheets provided during the lectures.

## Overview
This repository contains solutions and discussions for the assignments and practical exercises related to Reactive Quantum Systems and Interacção e Concorrência for the academic year 2023/2024. The problems include applications of quantum computing algorithms and modeling and verification of concurrent systems using the MCRL2 toolset.

## Contents
- [Quantum Computing Exercises](#quantum-computing-exercises)
  - [Deutsch's Algorithm](#deutschs-algorithm)
  - [Grover's Algorithm](#grovers-algorithm)
- [Concurrent System Modeling](#concurrent-system-modeling)
  - [Traffic Light Controller](#traffic-light-controller)
  - [System Verification and Analysis](#system-verification-and-analysis)

## Quantum Computing Exercises

### Deutsch's Algorithm
**Problem:** Implement Deutsch's algorithm to identify a specific type of Boolean function.
- **Solution:** The implemented algorithm and its detailed explanation are available in [IC_TP.pdf](./Quantum/IC_TP.pdf).
- **Results:** Discussion on the expected versus obtained results.

### Grover's Algorithm
**Problem:** Use Grover's algorithm for database search simulated with a quantum oracle.
- **Parts:**
  - **a)** Basic implementation and optimal iteration calculation.
  - **b)** Modification for multiple element search.
  - **c)** Oracle identification and analysis.
- **Solution and Analysis:** Detailed implementation steps and experimental results are discussed in [IC_TP.pdf](./Quantum/IC_TP.pdf).

## Concurrent System Modeling

### Traffic Light Controller
**Problem 1:** Design and simulate a traffic control system using three interconnected traffic lights.
- **System Model:** Describes the individual traffic lights and controller process.
- **Solution:** Using MCRL2 for modeling and verification. The system initialization and synchronization steps are crucial for ensuring safety properties.
- **Files:** [TrafficModel.mcrl2](./ReactiveSystems/my%20project.mcrl2proj) [TrafficSimulationResults.pdf](./ReactiveSystems/reactiveSystems_Miguel_Freitas_A91635.pdf)

### System Verification and Analysis
**Problem 2:** Application of the expansion theorem to the traffic light controller model.
- **Verification:** Safety and liveness properties are verified, ensuring no two lights show green simultaneously.
- **Performance Analysis:** Discussion on system performance and behavior under various conditions.
- **Expansion Theorem Application:** Detailed steps and results are in [reactiveSystems_Miguel_Freitas_A91635.pdf](./ReactiveSystems/reactiveSystems_Miguel_Freitas_A91635.pdf)

## Lectures and Resources
- [Link to mCRL2 website](http://www.mcrl2.org)
- [Link to Qiskit website](https://qiskit.org)
- Lecture slides and additional resources are provided for deeper understanding and context.

## Contributing
Guidelines for contributing to the repository, ensuring that enhancements align with the coursework's scope.

## Contact
For more information, please contact [Miguel Freitas](mailto:a91635@alunos.uminho.pt)