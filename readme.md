```python
# Linear Regression from Scratch using Gradient Descent
# Author: Cedric Errol P. Oporto
# Date: October 2025
```
# Housing Price Prediction

This project demonstrates a linear regression approach to predict housing prices using Python. The analysis and model development are documented in the `linear-regression.ipynb` notebook.

## What it does
- Implements gradient descent optimization
- Uses Mean Squared Error (MSE) as cost function
- Includes feature selection via correlation and mutual information
- Evaluates model using RMSE, MAE, and R²
- Compares top features using different selection strategies

## Dataset

- **Source:** [Kaggle - Housing Price Prediction Dataset](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction/)
- The dataset contains various features related to houses, such as location, size, number of rooms, and price.

## How to Run

1. Download the dataset from Kaggle.
2. Open and run the `linear-regression.ipynb` notebook.
3. Follow the steps in the notebook to preprocess data, train the model, and evaluate results.

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas, numpy, matplotlib, scikit-learn

## 📈 Results
| Feature Selection | R² | RMSE |
|-------------------|----|------|
| Correlation (Top 10) | 0.681 | ₱989k |
| Mutual Information (Top 10) | 0.671 | ₱1.00M |


## 📊 Visuals
Correlation 
<img width="706" height="565" alt="image" src="https://github.com/user-attachments/assets/200f0536-91e5-4e60-81cb-7f1f21a7e521" />
Mutual Information
<img width="705" height="564" alt="image" src="https://github.com/user-attachments/assets/10c21f57-55c1-4030-b4da-e299497e2719" />



