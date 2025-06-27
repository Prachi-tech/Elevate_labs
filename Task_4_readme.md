# Task 4: Binary Classification with Logistic Regression

## Objective
Build a binary classifier to distinguish between benign and malignant breast tumors using the Breast Cancer Wisconsin Dataset.

## Dataset
- Breast Cancer Wisconsin Dataset from Kaggle.
- 569 samples with 30 features.
- Target: Diagnosis (Benign = 0, Malignant = 1).

## Methodology
- Data preprocessing: cleaned, mapped target labels, dropped irrelevant columns.
- Split data into train (80%) and test (20%) sets with stratification.
- Standardized features using `StandardScaler`.
- Trained logistic regression model using Scikit-learn.
- Evaluated using confusion matrix, precision, recall, F1-score, and ROC-AUC.
- Tuned classification threshold to improve recall.

## Results
- Achieved ~96% accuracy.
- ROC-AUC score of 1.00, indicating excellent model performance.
- Threshold tuning improved recall, reducing false negatives.

## Tools Used
- Python, Pandas, Scikit-learn, Matplotlib
