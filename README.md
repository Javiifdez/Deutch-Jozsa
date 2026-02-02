# Deutsch–Jozsa Algorithm – Qiskit Implementation

This repository contains a Jupyter notebook implementing the Deutsch–Jozsa algorithm
using Qiskit, following the standard Map → Optimize → Execute → Post-process workflow.

The notebook compares ideal simulation results with executions on real IBM Quantum
hardware, highlighting the impact of transpilation optimization levels and noise in
the NISQ regime.

## Contents
- `Implementation.ipynb`: main notebook with implementation, execution, and interpretation.

## Notes
Execution on real quantum hardware is optional and controlled via a runtime flag in the notebook.
IBM Quantum credentials are loaded locally via environment variables and are not included
in the repository.
