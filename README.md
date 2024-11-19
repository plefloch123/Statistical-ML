# Personal Notes for Statistical Machine Learning for Severity Prediction of Atopic Dermatitis (AD)

This repository is dedicated to the exploration and implementation of **Statistical Machine Learning** techniques, with a primary focus on **Bayesian inference**, **Markov Chain Monte Carlo (MCMC)**, and **Hamiltonian Monte Carlo (HMC)** methods. It is part of a comprehensive project aimed at predicting the **severity of Atopic Dermatitis (AD)** through **time series analysis**. 

The work is inspired by and aligned with research conducted by the [Tanaka Group](https://www.rtanakagroup.com/publications/eczemapred), particularly their advancements in **EczemaPred**.

## Features

- **Bayesian Inference**:
  - Latent variable models for subjective symptom progression.
  - Random walk priors for temporal dynamics.
  - Binomial state-space models for observation generation.

- **MCMC and HMC Methods**:
  - Implementation of Gibbs Sampling and Metropolis-Hastings.
  - Exploration of posterior distributions for AD severity scores.
  - Efficient sampling of high-dimensional posterior distributions.

- **Time Series Analysis**:
  - Probabilistic models tailored to medical datasets.
  - Metrics such as **Ranked Probability Scores (RPS)** and **Log Predictive Density (LPD)** for model evaluation.

- **Simulation and Visualization**:
  - Synthetic data generation for AD severity modeling.
  - Detailed plots of latent state transitions, transformed variables, and observed data.

## Research Context

The project is part of a broader effort to develop personalized, data-driven models for predicting the progression of **atopic dermatitis severity** based on time series data. It integrates modern Bayesian techniques with domain-specific insights into dermatological conditions.

For more details on the research background, visit the [Tanaka Group's publication page](https://www.rtanakagroup.com/publications/eczemapred).

## Structure of the Repository

- **`bayesian_eczema_severity_model`**: explanation of the model taken from the paper "Personalized prediction of daily eczema severity scores using a mechanistic machine learning model". [paper link](https://pubmed.ncbi.nlm.nih.gov/32750186/)
- **`eczemapred_model`**: explantion and small implementation/simulation of the eczemapred model from the paper "EczemaPred: A computational framework for personalised prediction of eczema severity dynamics". [paper link](https://onlinelibrary.wiley.com/doi/10.1002/clt2.12140)
- **`metrics`**: Going over some different metrics to asses time series prediction.
- **`mcmc_introduction`**: Intro to MCMC and HMC

## Getting Started

To clone and run this repository:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-name>
   ```

2. Setup the environement:
   ```bash
    conda env create -f requirements.yaml
    conda activate statml_ad
   ```

## Citation

Tanaka, R., et al. EczemaPred: Machine Learning Approaches for Predicting the Severity of Atopic Dermatitis. Available at Tanaka Group.