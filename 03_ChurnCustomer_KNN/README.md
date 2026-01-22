# K-Nearest Neighbors (KNN) Classification

## Project Summary
This project applies **K-Nearest Neighbors (KNN)** for classification and evaluates predictive performance using accuracy and a confusion matrix.

## What I Built
- KNN classifier with evaluation on a held-out test set
- Confusion matrix analysis to understand error types
- Model selection concept via k sensitivity (where applicable in the notebook)

## Key Results
- **Accuracy:** 0.7582  
- **Confusion Matrix:**
  - TN = 1353, FP = 194
  - FN = 317, TP = 249

## Interpretation & Conclusion
- The model achieves **~75.8% accuracy**, indicating moderate predictive performance.
- The confusion matrix shows **FN (317) > FP (194)**:
  - The model is more likely to **miss true positives** than to incorrectly flag positives.
- Conclusion: This KNN model provides a reasonable baseline, but its error profile indicates it is **conservative in identifying the positive class** (depending on class labeling), which matters for use cases where catching positives is the priority.

## How to Read the Results
- Accuracy gives overall correctness, but the confusion matrix explains *where* the model fails.
- In many business problems, **FN can be more costly** (missed fraud, missed churn risk, missed buyers).

## Key Visuals
- ![Confusion Matrix](images/confusion_matrix.png)
- ![Accuracy vs K](images/accuracy_vs_k.png)

## Skills Demonstrated
KNN · Distance-based Learning · Classification Evaluation · Confusion Matrix Analysis · Visualization
