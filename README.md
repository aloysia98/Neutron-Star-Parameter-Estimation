
---
# Fast Estimation of Neutron Star Parameters Using Neural Networks

This project investigates the use of deep neural networks to estimate neutron star parameters from astrophysical data.

Traditional parameter estimation methods in astrophysics can be computationally expensive. Machine learning models can approximate the inference process and significantly accelerate parameter estimation.

---

## Project Goal

The goal of this project is to develop neural network models that can learn the mapping between observational data and neutron star physical parameters.

Target parameters include:

- Neutron star mass
- Radius

---

## Motivation

Astrophysical parameter estimation is often performed using Bayesian inference techniques that require large computational resources.

Recent work has shown that machine learning methods can provide fast approximations to these inference pipelines, enabling near real-time analysis of astrophysical observations.

This project explores deep learning approaches for efficient parameter prediction.

---

## Methodology

### Data Processing

- Simulated neutron star observational datasets
- Feature extraction from astrophysical signals
- Data normalization and preprocessing

### Model Architecture

Models evaluated include:

- Fully Connected Neural Networks
- Convolutional Neural Networks
- Deep regression networks

Framework:

- PyTorch

---

## Training Pipeline

1. Data preprocessing
2. Train/test split
3. Model training
4. Hyperparameter tuning
5. Evaluation using regression metrics

---

## Evaluation Metrics

Model performance is evaluated using:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## Results

Key observations:

- Neural networks successfully approximate the mapping between input signals and neutron star parameters.
- Deep learning models significantly reduce inference time compared to traditional astrophysical parameter estimation techniques.

---

## Installation

git clone https://github.com/aloysia98/neutron_star_parameter_estimation.git
cd neutron_star_parameter_estimation

## Future Work

- Physics-informed neural networks

- Bayesian neural networks

- Uncertainty estimation

- Training with gravitational wave datasets

## Research Context

Machine learning is increasingly used in astrophysics to accelerate analysis of gravitational wave signals and neutron star observations.

