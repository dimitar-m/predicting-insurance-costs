# Data-Driven Medical Cost Predictions to Support Strategic Pricing

This project builds and evaluates a linear regression model to predict individual medical charges based on demographic and lifestyle features. The goal is to provide a data-driven approach that supports more informed insurance pricing strategies.

## How to Run  
- Open the latest version of the project in **NBViewer**:  
  [View in NBViewer](https://nbviewer.org/github/dimitar-m/predicting-insurance-costs/blob/master/predicting-medical-insurance-costs.ipynb)
  
## Project Goals
- Predict individual insurance charges using structured patient data
- Improve model accuracy using log transformation
- Evaluate model performance with relevant metrics

## Dataset
The analysis uses the [Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance), which includes demographic and health-related variables such as:
- Age
- Sex
- BMI
- Number of children
- Smoking status
- Region
- Insurance charges

## Methods
- Exploratory data analysis (EDA)
- Feature selection using correlation and domain logic
- Linear regression with log-transformed target
- Evaluation on training and test sets (MAE, MSE, RMSE, R²)
- Residual analysis and actual vs predicted visualization

## Results Summary
- **R² (log scale):** 0.80 on test data
- **RMSE (original scale):** ~$7,695
- **Visual analysis:** Strong alignment between actual and predicted values, especially in mid-range costs

## Key Takeaway
Log transformation significantly improved model performance by reducing the influence of high-cost outliers, resulting in more stable and interpretable predictions for strategic decision-making.
