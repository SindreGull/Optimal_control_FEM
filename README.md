# FEM Solver for Poisson Equation & Optimal Control

## Overview

This project shows my implementation of a finite element solver for the 1D Poisson equation, and how I extended that framework to solve a real-world optimal control problem. The project demonstrates both numerical accuracy and optimization capabilities using Python and mathematical modeling. Specifically, the project:

- Solves the 1D Poisson equation using Galerkin FEM with quadratic basis functions.
- Verifies accuracy through error analysis in the \( H^1 \) and \( L^2 \) norms.
- Extends the solver to an optimal control problem that balances a approximation to a desired state versus cost.
- Visualizes how different values of the cost parameter \( \alpha \) affect the systems ability to match the target state.


## Technologies & tools used

- Python
- Numpy
- Matplotlib
- Jupyter (notebook) 
- LaTex


## Key Skills Demonstrated

- FEM implementation from scratch  
- PDE-constrained optimization using Lagrange multipliers  
- Writing Python code for scientific computing  
- Interpreting and visualizing numerical results  


## Files in This Repository


- FEM_optimization_report.pdf contains an extensive description of theory, calculations, numerical implementation and results.
- Codebase.ipynb contains the Python code for FEM and control solver, as well as the resulting plots.
- README.md is this file.

