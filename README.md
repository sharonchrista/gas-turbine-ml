# Gas Turbine Electrical Output Prediction

This repository contains the implementation of a deep learning model for predicting the electrical output of a micro gas turbine based on dynamic input conditions. It includes preprocessing, visualization, transition detection, and LSTM/GRU/Transformer-based models.

## Contents

- `gas_turbine_4.5.ipynb` – Main Jupyter notebook with data preprocessing, modeling, and visualizations.
- `train.zip` – Training data (normalized or raw time series).
- `test.zip` – Testing data for evaluation and inference.
- `lstm_turbine_model.pth` – Saved PyTorch model file (LSTM architecture) for predicting turbine electrical output.

## Problem Statement

Given dynamic operational data (input voltage, fuel flow, etc.), predict the **electrical power output** of a micro gas turbine system. The goal is to handle both **stationary and transition phases** effectively.

---

## Key Features

- Transition phase detection and visual labeling
- LSTM/GRU-based time series models
- Comparison across different model configurations
- Ablation study results
- Normalized input/output for stable training

---

## Requirements
Python 3.11+
NumPy, Pandas
Matplotlib, Seaborn
Scikit-learn
PyTorch

## To retrain the model or experiment further, refer to the `gas_turbine_4.5.ipynb` notebook.
