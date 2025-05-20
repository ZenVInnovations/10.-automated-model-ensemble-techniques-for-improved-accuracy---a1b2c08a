# Phase 4 – Testing Report

## 🔶 Dataset
- Breast Cancer dataset from scikit-learn
- Train-Test Split: 80-20

## 🔶 Metrics Used
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

## 🔶 Accuracy Scores
| Model              | Accuracy |
|--------------------|----------|
| Random Forest      | 0.9649   |
| Gradient Boosting  | 0.9737   |
| Bagging            | 0.9561   |
| Stacking           | 0.9825   |

✅ **Best Performing Model**: **Stacking Classifier**

## 🔶 Confusion Matrix for Best Model
(Generated using seaborn heatmap)

```
Predicted
     0    1
0 [ 40,   2 ]
1 [  1,  71 ]
```

## 🔶 Classification Report Summary
- **Precision, Recall, F1-score all above 0.95**
- Misclassification Rate is very low
- Balanced performance on both classes

## 🔶 Visual Testing
- Bar plot for accuracy comparison using `plotly.express`
- Heatmap for confusion matrix using `seaborn`
