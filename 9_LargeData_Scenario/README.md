# Web Analytics Data Wrangling (JSON Flattening + Revenue Analysis)

## Project Summary
This project focuses on transforming raw web analytics data containing **nested JSON fields** into a clean, analysis-ready dataset. It also analyzes revenue behavior, especially the skewed distribution common in e-commerce analytics.

## What I Built
- Flattening pipeline for JSON-like columns (e.g., device, geoNetwork, totals, trafficSource)
- Structured dataframe suitable for analysis and modeling
- Revenue distribution analysis including log transformation for interpretability

## Key Findings (From Notebook Observations)
- Revenue distribution is **highly right-skewed**:
  - most sessions generate zero/low revenue
  - a small fraction generates very high revenue (long tail)
- Log transformation makes revenue patterns more visible and comparable.

## Interpretation & Conclusion
- Because revenue is strongly skewed, averages can be misleading.
- Using log-scaled revenue helps:
  - understand differences between typical sessions
  - reduce the dominance of outliers in analysis
- Conclusion: The transformed dataset and distribution analysis provide a solid foundation for downstream tasks such as channel performance evaluation, conversion modeling, and revenue forecasting.

## How to Read the Plots
- **Raw revenue histogram**
  - confirms long-tail behavior and outlier influence
- **Log revenue histogram**
  - reveals structure among the majority of sessions and supports more stable analysis

## Key Visuals
- ![Revenue Distribution (Raw)](images/revenue_dist_raw.png)
- ![Revenue Distribution (Log)](images/revenue_dist_log.png)

## Skills Demonstrated
Data Wrangling · JSON Flattening · EDA · Distribution Analysis · Log Transform Reasoning · Analytics-ready Feature Creation
