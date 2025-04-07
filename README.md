# Machine Learning II Coursework 

Code for the following assignments are available upon request.  
For access to the private repos with my work, feel free to email me at **zeel@uchicago.edu**

## 1. Regularization with Ridge and Lasso Regressions

This assignment demonstrates the application of regularized linear regression techniques on the Diabetes dataset to predict disease progression based on clinical and physiological features. It includes comparison of Ordinary Least Squares (OLS), Ridge, and Lasso regression models, and visualizes how regularization affects model coefficients and feature selection.

### Key Concepts:

a. Multicollinearity detection using correlation matrices and Variance Inflation Factor (VIF)  
b. Data preprocessing: scaling features, managing multicollinearity  
c. Regression techniques:
- OLS (Ordinary Least Squares)  
- Ridge Regression (L2 regularization)  
- Lasso Regression (L1 regularization with automatic feature selection)  

d. Model evaluation using Mean Squared Error (MSE)  
e. Coefficient path visualization to interpret how models respond to different alpha values

## 2. Predict water temperature using scikit-learn regression (gradient descent)

This assignment implements Mini-Batch Gradient Descent to predict water temperature (`T_degC`) using oceanographic features from the `bottle.csv` dataset. It compares performance across different mini-batch sizes and evaluates convergence behavior and generalization capability using key regression metrics.

### Key Concepts:

a. Data cleaning and feature selection for regression modeling  
b. Feature scaling to improve convergence during gradient descent  
c. Parameter estimation using:
- Mini-Batch Gradient Descent (batch sizes: 50, 250, 2000)  
- Comparison with Ordinary Least Squares (scikit-learn’s Linear Regression)

d. Model evaluation using:
- Mean Squared Error (MSE)  
- R-squared (R²)  
- Explained Variance Score  

e. Visualization techniques:
- Cost vs. Epoch plots for each batch size  
- Actual vs. Predicted scatterplots across batch sizes  
- Overlaid comparison of prediction quality for all batch sizes  

f. Interpretation of learning rate role, comparison with normal equation, and understanding early stopping and overfitting detection
