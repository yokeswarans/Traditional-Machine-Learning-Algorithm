# Linear Regression on Height–Weight Dataset

A simple demonstration of fitting and comparing two linear models—`sklearn`’s `LinearRegression` and statsmodels’ Ordinary Least Squares (OLS)—on a synthetic height vs. weight dataset.


## Project Overview

This repository contains code to:

1. Generate a realistic dataset of 50 height (cm) and weight (kg) pairs  
2. Split the data into training and test sets  
3. Fit two linear models:  
   - **`sklearn.linear_model.LinearRegression`**  
   - **`statsmodels.api.OLS`** (Ordinary Least Squares)  
4. Compare the learned coefficients and metrics (e.g., R², MSE)

## Dataset

- **File:** `height_weight_data.csv`  
- **Columns:**  
  - `Height_cm` — Human height in centimeters  
  - `Weight_kg` — Human weight in kilograms  



## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your‑username/Traditional-Machine-Learning-Algorithm.git
   cd Traditional-Machine-Learning-Algorithm
