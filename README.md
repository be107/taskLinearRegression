# Multiple Linear Regression Project

## 📌 Overview
This project implements a **Multiple Linear Regression** model from scratch using Python.  
The model predicts employee income based on **age** and **experience**.  

## ⚙️ Features
- Custom class `multipleLinearRegression` with:
  - `fit()` for training using gradient descent
  - `predict()` for making predictions
  - `plot()` for visualizing the regression plane in 3D
- Evaluation metrics:
  - Sum of Squared Errors (SSE)
  - Mean Squared Error (MSE)
  

## 📊 Results
- The model successfully learned the relationship between age, experience, and income.  
- The **average prediction error** between actual and predicted values is **1305.72**.  
- Considering that income values range between **30,000 and 60,000**, this error is relatively small.  
- ✅ The model is performing well and provides reliable predictions.

## 🖼️ Visualization
- 3D scatter plot of the data points (blue).  
- Regression plane (red) showing the fitted model.  
- Adjustable viewing angles to inspect the plane from different sides.

## 🚀 Next Steps
- Compare with `sklearn.LinearRegression` for benchmarking.  
- Experiment with non-linear models (Polynomial Regression, Random Forest).  
- Add percentage error evaluation for clearer performance insights.
