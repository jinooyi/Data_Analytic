# Promotion Forecasting (Random Forest)

## Project Summary
This project uses **Random Forest** to forecast promotion outcomes. The key focus is understanding performance under class imbalance and interpreting why accuracy alone can be misleading.

## What I Built
- Random Forest classifier for promotion outcome prediction
- Evaluation using accuracy, classification report, and confusion matrix
- Interpretation of minority-class performance (business-critical outcomes)

## Key Results
- **Accuracy:** ~0.8752  
- **Confusion Matrix:**
  - TN = 16403, FP = 60
  - FN = 2337, TP = 400
- Report highlights (important):
  - Minority class recall is low (shown as ~0.15 in the notebook)

## Interpretation & Conclusion
- While accuracy is high (**~87.5%**), the confusion matrix shows the model misses many positive cases:
  - **FN = 2337** is large relative to **TP = 400**.
- Conclusion: The model performs very well on the majority class (non-events) but is **weak at catching true positive promotion outcomes**. In promotion forecasting, positives are often the most valuable cases, so the key takeaway is:
  - **High accuracy does not equal high business value** when the important class is rare.

## How to Read the Results (The Important Part)
- If the “positive” class represents successful promotions / valuable outcomes:
  - **Low recall** means the model fails to identify many of them.
- Confusion matrix is the clearest indicator here:
  - many positives are being labeled as negatives.

## Key Visuals
- ![Confusion Matrix](images/confusion_matrix.png)
- ![Feature Importance](images/feature_importance.png)

## Skills Demonstrated
Random Forest · Ensemble Learning · Imbalanced Classification Evaluation · Confusion Matrix Interpretation · Feature Importance
