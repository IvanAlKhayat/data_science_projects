# Phylogenetic Trees with Monte Carlo Simulation

This notebook implements a stochastic model of trait evolution on a phylogenetic tree using *Monte Carlo simulations*.  
The goal was to estimate the likelihood of an observed trait-dependent birth–death tree under a given stochastic differential equation model.

## Problem Description
We considered a phylogenetic tree where a trait \( X_t \) evolves according to an Ornstein–Uhlenbeck–type process with Brownian motion.  
Speciation and extinction rates were trait-dependent, and the observed tree topology included branching times at {1, 2, 2.5}.  
The task was to:
- Simulate the trait dynamics and tree evolution starting from root \( X_0 = 0 \).
- Compute a Monte Carlo estimator \( \hat{L}_N \) for the likelihood of the observed tree and trait paths.
- Assess convergence of the estimator as the number of simulations \( N \) increases.

## Main Components
- *Simulation*: Generated multiple realizations of the tree and continuous trait paths under the given stochastic model.
- *Likelihood Estimation*: Computed the Monte Carlo likelihood estimator based on the observed data.
- *Visualization*:  
  - Plotted simulated trajectories of the trait across branches.  
  - Produced convergence plots showing \( \hat{L}_N \) as a function of the number of simulations \( N \).

## Analysis
The analysis highlights how the likelihood estimator stabilizes as \( N \) increases, demonstrating the convergence behavior of the Monte Carlo method.  
Visual inspection of the trait paths and convergence plots provides insights into both stochastic variability and estimator reliability.
