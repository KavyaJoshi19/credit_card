

# Credit Card Fraud Detection Model

## Overview
This project uses machine learning to detect fraudulent credit card transactions, enhancing security and reducing financial losses. The model analyzes transaction patterns to classify them as legitimate or fraudulent.

## Dataset
- **Features**: Transaction details (scaled numeric values due to privacy).
- **Target**: Fraud status (0 = Legitimate, 1 = Fraudulent).
- **Source**: [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud).

## Objectives
1. Preprocess and explore the dataset to handle class imbalance.
2. Train machine learning models to identify fraudulent transactions.
3. Evaluate model performance using metrics like precision, recall, F1-score, and AUC-ROC.

## Technologies
- **Python Libraries**: Pandas, NumPy, scikit-learn, Matplotlib, Seaborn, imbalanced-learn
- **Tools**: Jupyter Notebook

## Implementation
1. Preprocess data (handle imbalance using techniques like SMOTE).
2. Perform exploratory data analysis (EDA) to identify fraud trends.
3. Train models (Logistic Regression, Random Forest, XGBoost).
4. Evaluate using precision-recall and ROC curves.

## Results
- **Best Model**: XGBoost with high AUC-ROC and recall.
- Accurate detection of fraudulent transactions with minimal false positives.

## Usage
Deploy the model to monitor transactions in real-time, providing alerts for potential fraud.
