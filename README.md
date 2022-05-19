# Introduction to Partial Differential Equations: Theory and Computations

A Jupyter notebook based introduction to the theory and computations of classical partial differential equations including Poisson's equation, the heat equation, and the wave equation. A semi-deep dive into the convergence theory of Fourier series is also included. The numerical estimation of solutions is presented on geometrically simple domains using classic finite difference schemes. 

This material serves as the textbook for the *MATH 4733/5733: Partial Differential Equations* course at CU Denver.

## Chapter outline

### Chapter 1: Preliminaries (Calculus, Linear Algebra, ODEs, and Python)  

- Chp1Sec0.ipynb - Overview/Table of Contents for Chapter 

- Chp1Sec1.ipynb - Calculus, Symbolic Computations, and Manufactured Solutions 

  - Calculus concepts and the use of sympy in Python for symbolic calculations 

  - The importance of manufactured solutions and the role that sympy can play in constructing them 

- Chp1Sec2.ipynb - Approximations and Rates of Convergence

  - How to estimate ROC with regression and watching out for finite precision arithmetic issues 

  - Emphasis on finite difference approximations to derivatives of a function and examples of estimating the ROC 

  - Introduces some plotting in Python 

- Chp1Sec3.ipynb - Numerical Estimation of an ODE 

  - Forward and backward Euler method derivations and implementations  

  - Estimating ROCs 

  - Numerical stability 

- Chp1Sec4.ipynb - Stability of a Differential Equation 

  - The concept of stability presented through the lens of continuity and the difference from numerical stability 

  - Examples of defining, proving, and demonstrating stability for linear and nonlinear problems 

- Chp1Sec5.ipynb - Linear Algebra 

  - Discretizing a PDE leads to a system of algebraic equations (motivation), so we review important concepts related to the numerical solution of PDEs 

  - Topics: Linear independence, rank, inner products, eigenvalues/vectors, positive definiteness 

- Chp1Sec6.ipynb - Exercises 

### Chapter 2: Elliptic PDEs, Poisson’s Equation, and a 2-point BVP 

- Chp2Sec0.ipynb - Overview/Table of Contents for Chapter 

- Chp2Sec1.ipynb - Poisson’s Equation and a 2-point BVP 

- Chp2Sec2.ipynb - A Finite Difference Approximation in 1-D 

- Chp2Sec3.ipynb - Properties of Continuous and Discrete Solutions 

- Chp2Sec4.ipynb - A Brief Tutorial on Adjoint-Based A Posteriori Error Analysis 

- Chp2Sec5.ipynb - Eigenvalues and Eigenfunctions/Eigenvectors 

- Chp2Sec6.ipynb - Poisson’s Equation in Two Space Dimensions 

  - Rectangular domains and separation of variables 

  - Disc domains and separation of variables 

  - A Finite Difference Approximation on Rectangular Domains 

- Chp2Sec7.ipynb - Exercises 

### Chapter 3: Parabolic PDEs, the Heat Equation, and a Deep Dive into Fourier Series 

- Chp3Sec0.ipynb - Overview/Table of Contents for Chapter 

- Chp3Sec1.ipynb - The Heat Equation on the Real Line (A Cauchy Problem)  

- Chp3Sec2.ipynb - The Heat Equation on a Bounded Interval and Formal Solutions 

- Chp3Sec3.ipynb - Fourier Series (A Deep Dive) 

- Chp3Sec4.ipynb - Finite Difference Approximations 

- Chp3Sec5.ipynb - Exercises 

### Chapter 4: Hyperbolic PDEs and the Wave Equation 

- Chp4Sec0.ipynb - Overview/Table of Contents for Chapter 

- Chp4Sec1.ipynb - First-Order Equations and the Method of Characteristics 

- Chp4Sec2.ipynb - The Wave Equation on the Real Line (A Cauchy Problem) 

- Chp4Sec3.ipynb - The Wave Equation on a Bounded Interval and Formal Solutions 

- Chp4Sec4.ipynb - Finite Difference Approximations 

- Chp4Sec5.ipynb - Exercises 

### Chapter 5: A Taste of Modern PDE Theory 

- Structure to be determined 

## Creative Commons License Information
<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/80x15.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Introduction to Partial Differential Equations: Theory and Computations</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/CU-Denver-MathStats-OER/Intro-PDEs-Theory-and-Computations" property="cc:attributionName" rel="cc:attributionURL">Troy Butler</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/CU-Denver-MathStats-OER/Intro-PDEs-Theory-and-Computations" rel="dct:source">https://github.com/CU-Denver-MathStats-OER/Intro-PDEs-Theory-and-Computations</a>.
