# Bayesian Methods for Estimation Under Uncertainty  
## A Critical Soil Test Value Application

This repository provides reproducible code accompanying the manuscript:

Roa, G.A., Spooner, J., Kerns, A.W., Hefley, T.J., & Ruiz Diaz, D.A.  
*Bayesian Methods for Estimation Under Uncertainty: A Critical Soil Test Value Application*  

---

## Purpose

This repository demonstrates how to:

- Compare frequentist and Bayesian quadratic-plateau (QP) models.
- Estimate critical soil test values (CSTV).
- Quantify uncertainty using bootstrap confidence intervals and Bayesian credible intervals.
- Compute posterior probabilities of yield gain.
- Integrate structural uncertainty using Bayesian model averaging (BMA).

The focus is on transparent uncertainty quantification in agronomic threshold estimation.

---

## Files

- `01-frequentist-vs-bayesian-qp.qmd`  
  Comparison of QP and Bayesian QP, including bootstrap and posterior uncertainty.

- `02-bayesian-response-probability-qp.qmd`  
  Posterior probability of yield gain and response-risk interpretation.

- `03-bayesian-model-averaging-cstv.qmd`  
  Bayesian model averaging across QP, LP, and exponential response models.

- `Data_example.xlsx`  
  Example dataset for reproducibility.

---

## Software Requirements

Analyses were conducted in R using:

- `brms` (Bayesian estimation via Stan)
- `nlraa`
- `bridgesampling`
- `tidyverse`

To use `brms`, a working C++ toolchain is required:

- **Windows:** RTools  
- **macOS:** Xcode Command Line Tools  
- **Linux:** build-essential / GCC toolchain  

Stan must compile models locally for Bayesian estimation.

---

## Data

The full experimental dataset from the manuscript is not publicly available.  
A simulated example dataset is included for reproducibility.

---

## Citation

If using this repository, please cite the associated manuscript.
