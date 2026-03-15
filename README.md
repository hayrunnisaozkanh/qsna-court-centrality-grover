# Quantum Social Network Analysis of Judicial Centrality using Grover's Algorithm
Applying Grover's Search Algorithm to identify the most central court in a directed judicial network using Quantum Social Network Analysis (QSNA).

## About
Applying Grover's Search Algorithm to identify the most central court in a directed judicial network using Quantum Social Network Analysis (QSNA: It applies quantum algorithms to classical social network analysis (SNA), promising potential speedups over classical approaches. SNA analyzes relationships (edges) between nodes — such as persons, institutions, or courts — using measures like degree centrality).

This notebook is prepared to model a directed graph that shows relationships between courts. In-degree centrality of the courts is computed, and the most central court is identified using Grover's Search Algorithm.

## Motivation
I developed this project because the intersection of law and quantum computing is my fundamental research interest. This project specifically explores Quantum Social Network Analysis (QSNA) as a tool for legal analysis. I am an LL.M. candidate in Information and Technology Law at the Social Sciences University of Ankara, and my thesis focuses on quantum computing and law.

## Requirements
To run this notebook, these libraries are required:
- NetworkX
- Matplotlib
- Qiskit
- Qiskit-Aer
- NumPy

## Results
The results of the in-degree centrality measurement show that the Supreme Court has a 1.0 score, while others have 0.0. The Grover's Search Algorithm determined the Supreme Court as the most central court.

## Future Work
**Precedent Graphs:** Courts refer to precedents while settling cases. We can model these citation networks as a graph. Modeling these citation networks as a graph would allow QSNA techniques to identify the most influential precedents.
**Quantum-Assisted Legal Analytics:** Quantum algorithms could be applied to wider and more complex data sets, such as analyzing case decisions.

## Author
Hayrunnisa Özkan
LL.M. Candidate in Information and Technology Law at the Social Sciences University of Ankara

March 2026
