# Quantum Computing Exercises

> Academic collection of quantum computing implementations, experiments, and technical analyses using Qiskit, IBM Quantum, and PennyLane.

## Overview

This repository contains a collection of academic exercises and projects developed as part of the **Quantum Computing** coursework at the **Universidad de Antioquia**.

The work explores fundamental concepts of quantum computation through practical implementations, numerical experiments, and technical analysis. The repository combines quantum circuit simulation, quantum machine learning, quantum communication protocols, and exploratory applications of quantum computing.

The main objective is to connect the theoretical foundations of quantum information with practical implementations using current quantum computing frameworks.

## Topics and Applications

The repository covers several areas of quantum computing:

* Quantum circuit construction and simulation
* Quantum teleportation
* Entanglement and multipartite quantum states
* Quantum Key Distribution (QKD) and the BB84 protocol
* Variational Quantum Circuits (VQC)
* Quantum Machine Learning (QML)
* Quantum classifiers and supervised learning
* Classical-to-quantum feature encoding
* Optimization of parameterized quantum circuits
* Experimental execution using IBM Quantum hardware
* Exploratory applications of quantum computing

## Repository Contents

### Quantum Teleportation

[`Quantum_Teleportation.ipynb`](Quantum_Teleportation.ipynb)

Implementation and analysis of quantum teleportation protocols.

The work includes the conventional Bell-state approach and an extended implementation based on a **three-qubit W state**, examining the additional circuit structure and conditional corrections required by multipartite entanglement.

The accompanying PDF provides a convenient document-oriented version of the analysis and results.

### Quantum Key Distribution

[`Quantum_Key_Distribution.ipynb`](Quantum_Key_Distribution.ipynb)

Study and simulation of the **BB84 Quantum Key Distribution protocol**.

The notebook examines the preparation and measurement of quantum states using the computational and diagonal bases, classical basis reconciliation, key extraction, and the effect of an eavesdropper attempting to intercept the quantum channel.

The work also discusses the theoretical principles underlying the security of BB84, including measurement disturbance and the no-cloning theorem.

### Quantum Machine Learning

[`Quantum_Machine_Learning.ipynb`](Quantum_Machine_Learning.ipynb)

Exploration of **Quantum Machine Learning** using PennyLane.

The notebook develops parameterized quantum circuits and variational quantum classifiers, covering concepts such as:

* Feature encoding
* Variational quantum circuits
* Parameterized gates
* Optimization of circuit parameters
* Cost and loss functions
* Batch-based training
* Supervised learning
* Training and unseen-data evaluation
* Comparison between classical and quantum machine learning approaches

The experiments also examine the limitations of the implemented models, including generalization, overfitting, circuit depth, and the effects that quantum measurement and hardware noise may introduce.

### Quantum ML Classifiers

[`Quantum ML Classifiers/`](Quantum%20ML%20Classifiers/)

A collection of two additional exercises focused on quantum classification using **PennyLane**.

The implementations include classical data preprocessing, feature encoding into quantum states, variational circuit construction, parameter optimization, and model evaluation.

The second exercise applies the approach to the **Titanic dataset**, illustrating the complete workflow from data preparation to quantum classification.

Both exercises are provided as Jupyter notebooks together with PDF versions for easier reading.

## Additional Applications

The repository also contains independent technical reports exploring other potential applications of quantum computing:

### Bioinformatics Application

[`Bioinformatics_Application.pdf`](Bioinformatics_Application.pdf)

An exploratory report investigating the potential use of quantum computing techniques in bioinformatics.

### Fractal Creation with Qiskit

[`Fractal_Creation_With Qiskit.pdf`](Fractal_Creation_With%20Qiskit.pdf)

An exploratory application of Qiskit to the generation and study of fractal structures.

These reports complement the practical exercises by examining how quantum computing concepts can be connected to application-oriented problems beyond the core coursework.

## Tools and Technologies

The implementations in this repository primarily use:

* **Python**
* **Qiskit**
* **IBM Quantum**
* **PennyLane**
* **NumPy**
* **Matplotlib**
* **scikit-learn**
* **Jupyter Notebooks**

The projects combine ideal quantum simulation with experiments designed for execution through IBM Quantum services where applicable.

## Computational Approach

The repository follows a practical workflow combining:

1. **Theoretical formulation** of the quantum computing problem.
2. **Quantum circuit design** using established quantum gates and protocols.
3. **Classical preprocessing and optimization** where required.
4. **Quantum simulation or hardware execution**.
5. **Measurement and statistical analysis** of quantum results.
6. **Interpretation of results and discussion of limitations**.

This approach provides practical exposure to the interaction between classical computation and quantum processing, particularly in variational algorithms and quantum machine learning.

## Documentation

For the main notebooks, both the original **`.ipynb`** files and corresponding **`.pdf`** documents are included.

The notebooks preserve the executable implementations and computational results, while the PDF versions provide a more convenient format for reading the theoretical development, methodology, figures, and conclusions without requiring a Jupyter environment.

## Academic Context

This repository was developed as part of undergraduate coursework in **Quantum Computing at Universidad de Antioquia**.

The material represents academic experimentation and implementation rather than production-ready quantum software or original research contributions. Its purpose is to document the development of practical skills in quantum programming, quantum information, and quantum algorithms.

## Repository Structure

```text
Quantum-Computing-Exercises/
│
├── Quantum ML Classifiers/
│   ├── Exercise 1.ipynb
│   ├── Exercise 1.pdf
│   ├── Exercise 2.ipynb
│   └── Exercise 2.pdf
│
├── Quantum_Key_Distribution.ipynb
├── Quantum_Key_Distribution.pdf
│
├── Quantum_Machine_Learning.ipynb
├── Quantum_Machine_Learning.pdf
│
├── Quantum_Teleportation.ipynb
├── Quantum_Teleportation.pdf
│
├── Bioinformatics_Application.pdf
├── Fractal_Creation_With Qiskit.pdf
│
├── README.md
├── LICENSE
└── .gitignore
```

## Project Status

Academic work completed as part of a university course.

The repository is maintained as a technical record of experiments and implementations in quantum computing, with emphasis on **quantum circuits, quantum information, quantum machine learning, and exploratory applications**.
