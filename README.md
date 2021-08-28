# Introduction-to-Precision-Recall-Curves

## Objective:

In this repository I have explored the **Precision-Recall Curves and how it is different from ROC Curves**.

## Some Insights:

**1. ROC Curves:**
![](/images/roc.gif)

As the two distributions separate, the ROC curve approaches the left-top corner, and the AUC value of the curve increases. When the model can perfectly separate the two outcomes, the ROC curve forms a right angle and the AUC becomes 1.

**2. Precision-Recall Curves:**
![](/images/PR.gif)

Similarly to the ROC curve, when the two outcomes separate, precision-recall curves will approach the top-right corner. Typically, a model that produces a precision-recall curve that is closer to the top-right corner is better than a model that produces a precision-recall curve that is skewed towards the bottom of the plot.

**3. Difference Between the ROC and Pecision-Recall Curves:**
![](/images/imbalance.gif)

An ROC curve tends to be more robust to class imbalanace that a precision-recall curve.The precision-recall curve changes shape more drastically than the ROC curve, and the AUC value mostly stays the same.
