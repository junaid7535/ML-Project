# ML-Project

Build an Detecting Anomalous Transaction  model using machine learning in Python. The steps will be:

## 1. Data Preprocessing

Handle missing values (if any).
Convert categorical variables into numerical form.
Extract useful time-based features from TransactionDate.

## 2. Feature Engineering

Compute transaction frequency per account.
Calculate the time difference between consecutive transactions.
Identify unusual transaction amounts.

## 3. Fraud Labeling (Anomaly Detection)

Use statistical thresholds (e.g., Z-score, IQR) to detect outliers.
Flag transactions with high risk based on past patterns.

## 4. Model Training

Use supervised (if fraud labels are available) or unsupervised (if not) learning methods.
Possible models: Logistic Regression, Random Forest, XGBoost, or an Autoencoder (for anomaly detection).

## 5. Model Evaluation
Evaluate using accuracy, precision, recall, F1-score, and AUC-ROC.
