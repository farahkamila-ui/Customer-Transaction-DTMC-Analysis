# Customer-Transaction-DTMC-Analysis
Developed a Discrete-Time Markov Chain model to analyze customer transaction behavior using a monthly banking dataset containing 120,000 observations from 10,000 customers. The study examined customer movement across transaction activity segments and estimated long-term behavioral patterns through transition probability and steady-state analysis.

## Overview

This project applies a **Discrete-Time Markov Chain (DTMC)** to analyze customer transaction behavior using a monthly banking transaction dataset. The objective is to model customer movement across transaction activity levels and estimate long-term behavioral patterns through transition probability analysis and stationary distribution.

The analysis was conducted using a dataset containing **120,000 monthly observations from 10,000 customers** over a one-year period.

## Objectives

- Analyze customer transaction dynamics over time.
- Construct a Discrete-Time Markov Chain model.
- Estimate transition probabilities between customer activity states.
- Compute stationary distribution and long-term customer behavior.
- Evaluate customer mobility and state persistence.

## Dataset

- **Source:** Customer Retention Time Series Dataset (Kaggle)
- **Observations:** 120,000
- **Customers:** 10,000
- **Period:** January–December 2024

## Methodology

1. Data preprocessing
2. Customer segmentation using transaction quartiles
3. State space construction:
   - Low (L)
   - Medium (M)
   - High (H)
   - Very High (VH)
4. Transition probability matrix estimation
5. Multi-step transition analysis
6. Stationary distribution computation
7. Convergence and customer behavior analysis

## Key Results

- Constructed a **4-state Discrete-Time Markov Chain** representing customer transaction activity.
- Estimated a transition probability matrix from **110,000 observed state transitions**.
- Computed the stationary distribution:

| State | Long-term Probability |
|--------|----------------------:|
| Low | 29.68% |
| Medium | 26.10% |
| High | 22.88% |
| Very High | 21.34% |

- Verified that the Markov Chain is **irreducible** and **aperiodic**, ensuring a unique stationary distribution.
- Observed rapid convergence to steady-state behavior within only a few transition steps.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Report

The complete project report is available here:
[Customer Transaction Behavior Analysis Using Discrete-Time Markov Chain.pdf](https://github.com/user-attachments/files/30361750/Customer.Transaction.Behavior.Analysis.Using.Discrete-Time.Markov.Chain.pdf)
 

## Authors

This project was developed as the final project for the **Stochastic Models I** course at the **Faculty of Mathematics and Natural Sciences, Universitas Indonesia**.

**Team Members**
- Farah Kamila
- Alia Hafsa Humaira
- Azmy Qonita
- Adinda Ayrahasna Khairunnisa
