# SIS Reaction-Diffusion

Python code for my M.S. thesis in Applied Mathematics at Northern Illinois University.

## Overview
This project numerically simulates spatial SIS (susceptible–infected–susceptible)
epidemic models of the form

$$
\begin{aligned}
S_t &= d_S \Delta S - \beta(x)\frac{SI}{S+I} + \gamma(x) I, \\
I_t &= d_I \Delta I + \beta(x)\frac{SI}{S+I} - \gamma(x) I,
\end{aligned}
$$

with no-flux boundary conditions. The goal is to study the basic reproduction
number $\mathcal{R}_0$ and the asymptotic profiles of the endemic equilibrium
as the diffusion rates $d_S$ or $d_I$ approach zero.

## Structure
- `learning/` – Python practice notebooks
- `solver/` – finite-difference PDE solver (in progress)

## Tools
Python, NumPy, SciPy, Matplotlib

## Status
In progress (expected completion May 2027).
