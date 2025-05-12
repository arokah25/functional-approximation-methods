# Functional Approximation with Taylor, Fourier, and Neural Networks

This notebook explores several classical and modern techniques for approximating continuous functions on the interval \([-π, π]\), including:

- Taylor polynomial approximation of \(\sin(x)\)
- Fourier series approximation of \(f(x) = e^{-|x|}\)
- Mean squared error (MSE) evaluation and convergence visualization
- Theoretical discussion of the Universal Approximation Theorem for neural networks

## Contents

### Part A: Taylor Approximation of \(\sin(x)\)
- Implements Taylor polynomials of increasing degree (1, 3, 5, 7, 9, 11)
- Plots approximations against the true function
- Demonstrates pointwise convergence centered at zero

### Part B: Fourier Series Approximation of \(f(x) = e^{-|x|}\)
- Constructs Fourier approximations using different truncation levels \(N\)
- Plots approximation vs true function over \([-π, π]\)
- Computes and visualizes MSE as a function of \(N\)
- Uses the trapezoidal rule to approximate the integrals involved

### Part C: Theoretical Discussion
- Summarizes the Universal Approximation Theorem
- Discusses the tradeoff between shallow and deep neural networks in approximating non-smooth or composite functions
- Explains why depth can yield more efficient representations than width alone

## Dependencies

- NumPy
- Matplotlib
- Scikit-learn
- PyTorch (only used in Part C)

All dependencies are standard and can be installed via `pip install numpy matplotlib scikit-learn torch`.

## How to Run

You can run the notebook in:
- Jupyter Notebook or JupyterLab
- Google Colab (no setup required)

No datasets are required.

## Purpose

This project was developed as part of a coursework assignment in functional approximation and optimization. It serves both as a mathematical demonstration of classic approximation theory and a theoretical bridge to modern machine learning approaches.
