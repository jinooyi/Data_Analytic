# Ad Effectiveness Analysis (Logistic Regression)

## Project Summary
This project evaluates advertisement effectiveness by predicting whether a customer will purchase using **Logistic Regression**. The focus is on classification performance and interpreting business impact through the confusion matrix.

## What I Built
- Logistic regression classifier for conversion prediction
- Performance evaluation using accuracy and confusion matrix
- Interpretation of false positives/false negatives for business decisions

## Key Results
- **Accuracy:** 0.90  
- **Confusion Matrix (TN, FP / FN, TP):**
  - TN = 92, FP = 8
  - FN = 12, TP = 88

## Interpretation & Conclusion
- With **90% accuracy**, the model performs strongly overall.
- The confusion matrix shows:
  - **Low false positives (8):** limited wasted targeting (predict purchase but no purchase).
  - **Some false negatives (12):** some missed converters (predict no purchase but they would buy).
- Conclusion: The model is a **reliable conversion predictor** with a small number of classification errors, and the error pattern suggests it is slightly more likely to miss some potential buyers than to incorrectly target non-buyers.

## How to Read the Confusion Matrix (Business Meaning)
- **False Positive (FP):** predicted “buy” but actually “no buy” → wasted spend
- **False Negative (FN):** predicted “no buy” but actually “buy” → missed revenue
Given FP=8 and FN=12, missed opportunities are slightly higher than wasted spend in this run.

## Key Visuals
- ![Confusion Matrix](images/confusion_matrix.png)
- ![Predicted Probability Distribution](images/predicted_probability_hist.png)

## Skills Demonstrated
Logistic Regression · Classification Metrics · Confusion Matrix Interpretation · Probability Thinking · Data Visualization
