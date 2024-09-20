# ROC and AUC

## ROC (Receiver Operating Characteristic) Curve:

The ROC curve is a graphical representation of a classification model's performance. It plots the True Positive Rate (TPR) against the False Positive Rate (FPR) at various threshold levels. The TPR is also knowns as recall or sensitivity, while the FPR represents the proportion of negative instances incorrectly classified as positive.

- True Positive Rate (TPR): Measures the proportion of actual positives correctly identified
  $\frac{TP}{TP + FN}$
- False Positive Rate (FPR): Measures the proportion of actual negatives incorrectly identified as positive
  $\frac{FP}{FP + TN}$

  A ROC curve helps to visualize how well the model is distinguishing between positive and negative classes. A perfect classifier has a ROC curve that passes through the top-left corner, achiving a TPR of 1 and FPR of 0

## AUC (Area Under the Curve):
  
  AUC represents the area under the ROC curve. It is a single scalar value that summarizes the performance of a classification model. The value of AUC ranges from 0 to 1:
  - AUC = 1: Perfect Classifier
  - AUC = 0.5: Random Guess (No discrimination capability)
  - AUC < 0.5: Worse than random

  A higher AUC value indicates a better-performing model, with 1 being a perfect model.
