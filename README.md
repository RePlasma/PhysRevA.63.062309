# Optimal creation of entanglement using a two-qubit gate

Authors of [paper](https://link.aps.org/doi/10.1103/PhysRevA.63.062309): B. Kraus and J. I. Cirac (2001)

Author of this notebook: Óscar Amaro (2026)

In this paper, 2 metrics of entropy studied in more depth than the others: the von Neumann entanglement entropy (SvN) and the Rènyi.

**Methods:**
- theory/analytical
- numpy
- qiskit statevector
- qiskit aer

**Structure:**
- imports
- functions
- computing results
- plotting

**Obs:**
- In example 1, a generic product state will not necessarily lead to the maximum SvN. We start with state **|00>**
- In example 2, we are plotting many generic random input states and confirming that the maximum Rènyi entropy for a given alpha is indeed the maximum between the theoretical curves for **me** and **ps**
