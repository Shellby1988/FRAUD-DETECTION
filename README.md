# Fraud Detection with Machine Learning

This repository contains code for fraud detection using machine learning models. The aim is to detect fraudulent activities accurately based on the provided dataset.

## Introduction

Fraudulent activities pose significant risks to businesses and individuals alike. Machine learning algorithms can help in automatically identifying such activities based on historical data patterns. This project utilizes popular machine learning algorithms to detect fraud and evaluate their performance using cross-validation techniques.

## Dataset

The dataset used for this project contains information about various transactions, including features like transaction amount, location, time, etc. Each transaction is labeled as either fraudulent (class 1) or legitimate (class 0).

## Models

Two machine learning models were trained and evaluated for fraud detection:

### XGBoost Classifier

- Precision: 0.97
- Recall: 0.97
- F1-Score: 0.97
- Accuracy: 0.97

Confusion Matrix:
```
[[1502   25]
 [  28  414]]
```

### Decision Tree Classifier

- Precision: 0.95
- Recall: 0.95
- F1-Score: 0.95
- Accuracy: 0.95

Confusion Matrix:
```
[[1454   73]
 [  30  412]]
```

## Cross-Validation

To improve the robustness of the models, cross-validation techniques were employed. Cross-validation helps in obtaining a more generalized performance estimate of the model by splitting the dataset into multiple subsets for training and testing.

## Conclusion

This project demonstrates the application of machine learning techniques for fraud detection. By leveraging cross-validation, the models can provide more reliable predictions, helping businesses in identifying and preventing fraudulent activities effectively.

---
