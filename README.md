# Bayesian Cognitive Modeling

**Course Project:** CGS698C – Bayesian Models & Data Analysis  
**Instructor:** Prof. Himanshu Yadav  
**Institute:** IIT Kanpur  
**Duration:** May 2025 – Present  

## Objective
To model and analyze cognitive processes—particularly word recognition—using Bayesian statistical techniques and cognitive hypotheses. Core focus was on deriving posterior distributions, performing inference using simulation-based techniques, and evaluating lexical access hypotheses.

---

## Topics Covered

- Bayesian Inference and Likelihood Functions
- Posterior Estimation using Grid Approximation, Importance Sampling, and MCMC
- Hierarchical Modeling for Cognitive Hypotheses (e.g., Lexical Access)
- Gaussian Models for Reading Times
- Model Evaluation via Posterior Predictive Checks
- Hamiltonian Monte Carlo (HMC) and Sampler Sensitivity Analysis

---

## Repository Structure

Bayesian-Cognitive-Modeling/  
├── README.md  
├── assignments/  
│ ├── Assignment-01.pdf  
│ ├── Assignment-02.pdf  
│ └── Assignment-03.pdf  
├── notebooks/  
│ ├── grid_approximation.ipynb  
│ ├── mcmc_sampler.ipynb  
│ ├── hmc_sampler.ipynb  
│ └── lexical_access_model.ipynb  


---

## Assignment Overview

### [Assignment 01: Bayesian Foundations](assignments/Assignment-01.pdf)
- Introduced probability, discrete & continuous variables
- Visualized likelihood functions for recognition time
- Built intuition around the difference between PDF and likelihood

### [Assignment 02: Posterior Estimation and Cognitive Hypotheses](assignments/Assignment-02.pdf)
- Posterior estimation from binomial & Gaussian data
- Prior vs posterior comparison for real-world data (e.g., reading times)
- Modeled Lexical-Access Hypothesis using hierarchical normal priors

### [Assignment 03: Simulation-Based Inference Techniques](assignments/Assignment-03.pdf)
- Posterior estimation via:
  - Grid approximation
  - Monte Carlo integration
  - Importance Sampling
  - Metropolis-Hastings MCMC
  - Hamiltonian Monte Carlo (HMC)
- Hierarchical regression for RT data: `RT ~ α + β·type`
- Posterior sensitivity analysis and credible intervals

---

##  Highlighted Techniques
-  **Grid Approximation**: Brute-force estimation of posterior density  
-  **Importance Sampling**: Efficient resampling based on proposal distributions  
-  **MCMC (Metropolis-Hastings)**: Random walk sampling using acceptance ratios  
-  **Hamiltonian Monte Carlo**: Gradient-based exploration of posterior landscape  
-  **Truncated Priors**: Constrained modeling of non-negative parameters (e.g., β > 0)  
-  **Credible Intervals**: Bayesian analog to confidence intervals for parameters

---

##  Outcomes

- Verified the **Lexical Access Hypothesis** by quantifying differences in word vs non-word recognition times using hierarchical models.
- Implemented and compared multiple **posterior estimation techniques** to validate theoretical assumptions.
- Visualized and analyzed **posterior sensitivities**, convergence of samplers, and prior influence.

---

##  Contact
For code walkthroughs, reproduction notebooks, or collaboration opportunities, please refer to my resume or connect via LinkedIn.

>  *This repository reflects my applied understanding of Bayesian modeling in cognitive science, integrating both mathematical rigor and experimental data analysis.*
