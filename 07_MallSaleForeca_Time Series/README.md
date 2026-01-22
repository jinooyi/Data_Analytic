# Mall Sales Forecasting (Time Series - Prophet)

## Project Summary
This project forecasts mall sales using **time series modeling with Prophet**. The emphasis is on identifying trend/seasonality and producing a forward-looking forecast with uncertainty intervals.

## What I Built
- Time series preparation (date indexing, resampling where needed)
- Prophet model training
- Forecast generation and component interpretation (trend and seasonality)

## Key Outputs
- Forecast curve (yhat) with uncertainty bands (yhat_lower / yhat_upper)
- Components plot that separates:
  - long-term trend
  - seasonal patterns

## Interpretation & Conclusion
- The forecast provides:
  - a central estimate of expected sales over time
  - a confidence range that reflects uncertainty
- By inspecting Prophet components:
  - **Trend** explains long-run growth/decline
  - **Seasonality** highlights repeating cycles (useful for planning)
- Conclusion: The model produces an interpretable forecasting view that supports business planning around expected demand patterns and seasonal peaks.

## How to Read the Prophet Plots
- **Forecast Plot**
  - If uncertainty bands widen, predictions become less certain farther into the future.
- **Components Plot**
  - Seasonal peaks suggest timing for staffing/inventory adjustments.

## Key Visuals
- ![Sales Trend](images/sales_trend.png)
- ![Prophet Forecast](images/prophet_forecast.png)
- ![Prophet Components](images/prophet_components.png)

## Skills Demonstrated
Time Series Analysis · Forecasting · Prophet · Trend/Seasonality Interpretation · Business Planning Insight
