# EV Efficiency Prediction

This project uses machine learning to predict the efficiency of electric vehicles (EVs) based on multiple input features such as vehicle age, driving style, make, distance driven, and charging behavior.

## Features Used

- `Vehicle Age` — Age of the EV in years
- `Driving Style` — Categorical or encoded (e.g., conservative, average, aggressive)
- `Vehicle Make` — Brand or manufacturer (one-hot or label encoded)
- `Distance Driven` — Total distance covered in km or miles
- `Charging Behavior` — Average charge cycles or amount charged per trip

## Objective

Predict EV energy efficiency (e.g., km/kWh or Wh/km) using a regression model.

## Model

- Model used: `MLPRegressor` (Multi-layer Perceptron)
- Framework: `scikit-learn`
- Data preprocessing: encoding categorical features, normalization
- Evaluation: Mean Squared Error (MSE), R² Score

## Getting Started

### 1. Install Dependencies

```bash
pip install scikit-learn pandas numpy matplotlib
