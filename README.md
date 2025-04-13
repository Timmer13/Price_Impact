# Efficient Trading with Price Impact

This repository implements and visualizes models and strategies inspired by the paper *Efficient Trading with Price Impact*. It combines classical financial modeling with deep learning to analyze optimal trade execution in the presence of market impact.

## Overview

The project includes the following components:

1. **Model Construction and Analysis**
   - Linear Obizhaeva-Wang (OW) Model
   - Nonlinear Almgren-Fisher-Schied (AFS) Model
   - Distribution visualization of price impact

2. **Optimal Execution Strategy (Linear Impact)**
   - Reimplementation of the optimal strategy under linear impact assumptions
   - Generation of Sharpe ratio plots (Section 6.2 of the original paper)

3. **Deep Learning-Based Strategy**
   - Neural network model for discrete-time trading strategy (Appendix C.2)
   - Visualization of training loss across network structures

## Data

The project uses a merged dataset combining MBO and MBP-1 data. Key fields include:
- Bid fill / Ask fill
- Signed volume
- Best bid / Best ask

This dataset is necessary for modeling market impact and training neural networks.

## Repository Contents

- `Efficient_Trading_with_Price_Impact.ipynb`: Main notebook with implementation and plots.
- `merged_data.csv`: Dataset (not included in this repository).