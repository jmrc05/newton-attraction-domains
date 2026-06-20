# Newton-Raphson Fractal Generation and Attraction Domains

<div align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white" alt="Numpy" />
  <img src="https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white" alt="Matplotlib" />
  <img src="https://img.shields.io/badge/SymPy-3B5526?style=for-the-badge&logo=python&logoColor=white" alt="SymPy" />
</div>

---

## Overview

This project focuses on the numerical resolution of non-linear systems of equations using the Newton-Raphson method. The core objective is to compute and visually render the domains of attraction (basins of attraction) for the different roots of a highly complex system, generating fractal patterns that illustrate the iterative convergence behavior based on initial starting points.

## Mathematical Foundation

The algorithm evaluates a dense grid of initial complex conditions and iterates the multidimensional Newton-Raphson formula. The specific non-linear system addressed in this numerical simulation involves high-degree polynomials that produce intricate boundaries between the basins of attraction.

The method requires the continuous evaluation of the system's Jacobian matrix. To handle the symbolic differentiation and algebraic manipulation before numerical evaluation, the implementation relies heavily on Python's symbolic mathematics capabilities.

## Execution and Installation

Clone the repository to your local machine and install the required scientific libraries:

```bash
git clone [https://github.com/jmrc05/newton-raphson-fractals.git](https://github.com/jmrc05/newton-raphson-fractals.git)
cd newton-raphson-fractals
pip install numpy matplotlib jupyter sympy
