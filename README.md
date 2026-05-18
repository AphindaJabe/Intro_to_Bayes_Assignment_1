# Introduction to Bayes Assignment 2026

This repository contains the code, analysis, and report for the *Introduction to Bayes Assignment 2026* from the Department of Statistical Sciences at the University of Cape Town.

## Assignment Overview

The assignment is divided into three major sections:

### Question 1 — Bayesian Linear Regression with Gibbs Sampling
This section investigates Bayesian linear regression using the Auto MPG dataset. The objectives include:

- Deriving conditional posterior distributions
- Implementing Gibbs sampling in R
- Generating posterior samples
- Producing trace plots and posterior density plots
- Comparing Bayesian credibility intervals with classical confidence intervals
- Investigating the effect of informative versus vague priors
- Exploring the impact of sample size on the posterior distribution

### Question 2 — Bayesian Search Theory
This section simulates a Bayesian search-and-rescue problem inspired by historical Bayesian search applications during World War II. The project involves:

- Deriving Bayesian updating equations
- Simulating a search process on a 20×20 grid
- Updating posterior probabilities after failed searches
- Visualising probability evolution using heatmaps
- Comparing Bayesian search strategies with random search strategies

### Question 3 — Robust Bayesian Regression with Outliers
This section extends Bayesian linear regression to accommodate outliers through heteroscedastic error variances. Tasks include:

- Deriving posterior distributions for model parameters
- Implementing a Gibbs sampler for the robust model
- Comparing posterior behaviour with the standard regression model
- Assessing convergence through trace plots

---

## Repository Structure

```text
├── code/
│   └── Bayes Assignment 1.qmd
│
├── data/
│   └── auto_mpg_data.csv
│
├── report/
│   └── Bayes_Assignment_1.pdf
│
├── images/
│   ├── trace_plots.pdf
│   ├── trace_plots2.pdf
│   ├── beta_densities.pdf
│   ├── beta_intervals.pdf
│   ├── densities_inf.pdf
│   └── taus_plots.pdf
│
└── README.md
```

---

## Dataset

The assignment uses the **Auto MPG dataset**, originally sourced from the UCI Machine Learning Repository. The dataset contains vehicle characteristics used to model fuel efficiency (`mpg`).

Predictor variables used include:

- Displacement
- Horsepower
- Weight
- Acceleration

All predictors were standardised before modelling.

---

## Methods and Techniques

The following statistical and computational techniques are implemented:

- Bayesian linear regression
- Gibbs sampling
- Inverse-Gamma priors
- Posterior inference
- Credibility intervals
- Bayesian updating
- Bayesian search theory
- Robust regression modelling
- Monte Carlo simulation
- Markov Chain Monte Carlo (MCMC)

---

## Software Requirements

The project was completed in **R** using several libraries, including:

```r
library(MASS)
library(ggplot2)
library(coda)
library(dplyr)
library(tidyr)
```

Additional packages may be required depending on implementation choices.

---

## Reproducibility

To reproduce the analysis:

1. Clone the repository
2. Open the R project or scripts
3. Run the scripts in numerical order
4. Compile the final report using Quarto, RMarkdown, or LaTeX

---

## Authors

- Aphinda Jabe
- Nandi Malinga
- Shantel Mogowane

---

## Academic Integrity

This assignment was completed in accordance with the academic integrity policies of the University of Cape Town. All external sources and references used during the assignment were appropriately acknowledged.
