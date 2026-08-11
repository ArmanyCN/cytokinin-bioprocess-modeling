# Cytokinin Bioprocess Modeling

Computational framework developed for the modeling, optimization, and in silico scale-up analysis of cytokinin production by *Trichoderma atroviride*.

This repository contains the Python implementations developed as part of a Master's thesis focused on the computational analysis of cytokinin production.

## Repository overview

The computational workflow includes:

1. Response Surface Methodology (RSM) modeling.
2. Gaussian Process (GP) modeling and uncertainty quantification.
3. Bayesian Optimization (BO) using Expected Improvement.
4. In silico analysis for bioprocess scale-up using a hybrid modeling approach.

## Repository structure

```text
cytokinin-bioprocess-modeling/
│
├── data/          Experimental datasets used in the models
├── notebooks/     Reproducible Jupyter/Google Colab notebooks
├── figures/       Figures generated from the computational analyses
├── results/       Numerical results and optimization outputs
└── src/           Reusable Python functions
