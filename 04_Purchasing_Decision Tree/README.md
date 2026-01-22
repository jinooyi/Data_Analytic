# Purchase Prediction (Decision Tree)

## Project Summary
This project predicts purchase outcomes using a **Decision Tree** model. The emphasis is on balancing performance with interpretability, enabling clear reasoning about the decision logic.

## What I Built
- Decision Tree classifier for purchase prediction
- Evaluation using accuracy and confusion matrix
- Interpretability using tree structure and feature importance

## Key Results
- **Accuracy:** 0.7879  
- **Confusion Matrix:**
  - TN = 151, FP = 10
  - FN = 40, TP = 96

## Interpretation & Conclusion
- The model achieves **~78.8% accuracy**, indicating solid performance for a highly interpretable approach.
- Error profile:
  - **Very low FP (10):** few incorrect positive predictions
  - **Higher FN (40):** more missed positive cases than incorrect positives
- Conclusion: The decision tree is **high-precision oriented** (again depending on which class is “positive”), producing few false alarms but missing some true positives. This is useful when it’s important to avoid incorrectly predicting a purchase.

## How to Read the Results
- **Low FP** suggests conservative positive predictions.
- **Higher FN** suggests some real buyers are not identified by t
