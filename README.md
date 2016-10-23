# Numerical Methods in Finance
This repository contains code examples from Numerical Methods in Finance [NMiF](https://wwwf.imperial.ac.uk/~ajacquie/) as well as code from MOOCs which contained an element of numerical methods or mathematical modelling:

### Finance Related
* Financial Markets
* Pricing Options with Mathematical Models
* Computational Finance
* Mathematical Methods for Finance
* Business Analytics

### Non Finance Related
* Statistical Mechanics
* Ordinary Differential Equations
* Calculus
* Statistics
* Complex Analysis
* Linear Algebra
* Scientific Computing
* High Performance Scientific Computing 
* Practical Numerical Methods
* Algorithms
* Discrete Mathematical Modelling

### Table of Contents
1. Lattice (Tree) Methods
   * Discrete time metods for Option Pricing.
   * Includes **_CRR_** (Cox-Ross-Rubenstein) binomial options pricing model.
2. Monte Carlo Methods
   * Random Paths Simulation of financial models using Monte Carlo techniques.
   * Includes simulation of **_CIR_** (Cox-Ingersoll- Ross) model for interest rates.
3. Finite Difference Methods for PDEs
   * Discretisation schemes used to model the **_Black-Scholes_** (constant volatility) Heat (Diffusion) Equation.
   * Includes Explicit, Implicit, and Crank Nicolson schemes.
   * Includes Stability and Convergence analysis.
   * Includes numerical solutions of systems of linear equations (Gauss-Seidel, SOR, and Conjugate Gradient).
4. Fourier Transform & Integration Methods
   * Stochastic Volatility with Complete Markets Example: **_CEV_** (Constant Elasticity of Variance) Model
   * Stochastic Volatility with Incomplete Markets Example: **_Heston Model_**.
   * Mathematical methods (Characteristic Function, Quadrature Methods, and Fast Fourier Transform) to derive and compute the Heston model.
   * Includes **_Carr Maden_** formula for option pricing using the FFT.
   * Includes (parallel) code for Quadrature Methods.
5. Model Calibration
   * Root finding and optimisation techniques to compute **_implied volatility_** (Black-Scholes) and **_implied volatility surface_** (Heston) for model calibration.
6. Linear Programming
   * Constrained Optimisation techniques to compute implied volatility and to **_maximise (optimise) expected portfolio returns_**.


