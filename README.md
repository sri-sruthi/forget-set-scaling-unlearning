# Machine Unlearning in Image Classification

This repository contains the experimental code used in the paper:

**Understanding Machine Unlearning in Image Classification:  
Forget-Set Scaling, Dataset Complexity, and Approximate vs. Exact Unlearning Trade-offs**

## Overview

The repository provides a reproducible implementation of:
- Gradient Ascent (GA) based approximate unlearning
- SISA-based exact unlearning
- Forget-set scaling analysis
- CIFAR-10 and CIFAR-100 experiments
- Multi-metric evaluation (forget, retain, test accuracy)

## Repository Structure
```
notebooks/
└── Machine_Unlearning_Research.ipynb
```

## Datasets

The experiments use publicly available datasets:
- CIFAR-10
- CIFAR-100

Download from:  
https://www.cs.toronto.edu/~kriz/cifar.html

## Requirements

- Python ≥ 3.8  
- PyTorch ≥ 1.12  

Install dependencies:
```bash
pip install -r requirements.txt
```

## Running the Experiments

Open the notebook:
```bash
jupyter notebook notebooks/Machine_Unlearning_Research.ipynb
```

The notebook contains:
- Baseline training
- Forget-set construction
- GA and SISA unlearning
- Metric computation and plots

## Reproducibility

All experiments use fixed random seeds to ensure deterministic results.

## License

This project is released under the MIT License.
