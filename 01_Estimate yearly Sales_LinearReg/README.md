# Sales Forecasting (Linear Regression)

## Project Summary
This project estimates **yearly sales** using a **Linear Regression** model. The goal is to produce a baseline forecasting model that is easy to interpret and to quantify typical prediction error in the same unit as sales.

## What I Built
- A linear regression model trained on the provided sales dataset
- Evaluation using error metrics (MSE, RMSE)
- Visual checks to understand model fit (Actual vs Predicted, residual behavior)

## Key Results
- **MSE:** 473.27  
- **RMSE:** 21.75

## Interpretation & Conclusion
- **RMSE = 21.75** means the model’s predictions are typically off by about **~21.75 sales units** on average.
- This result establishes a **clear baseline**: we now know the expected magnitude of forecasting error from a simple linear model.
- The model is most useful when:
  - stakeholders want an interpretable relationship between features and sales, and  
  - a baseline forecast is acceptable for planning ranges rather than exact values.

## How to Read the Charts (What to Look For)
- **Actual vs Predicted**
  - Points close to the diagonal line indicate strong fit.
  - Wide scatter indicates higher variance in errors.
- **Residual Plot**
  - Random spread around zero suggests the linear model is reasonable.
  - A visible curve or funnel pattern suggests systematic error.

## Key Visuals
Place the exported images in `images/` and embed them here:
- ![Actual vs Predicted](images/actual_vs_predicted.png)
- ![Residuals](images/residuals.png)

## Skills Demonstrated
Linear Regression · Model Evaluation (MSE/RMSE) · EDA · Model Interpretation · Data Visualization
