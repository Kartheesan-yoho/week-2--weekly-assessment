# Week 2 – Machine Learning Assessment

## Project Overview

This project demonstrates the practical implementation of Week 2 Machine Learning concepts using a synthetic bank loan dataset containing 2,000 customer records.

The main objective is to predict loan defaults, estimate loan amounts, and segment customers using machine learning techniques.

## Dataset Information

- **Dataset:** Synthetic Bank Loan Dataset
- **Total Records:** 2,000
- **Target Variable:** `loan_default`
- **Regression Target:** `loan_amount`

### Features

- Age
- Income
- Credit Score
- Loan Amount
- Loan Term
- Employment Years
- Previous Defaults
- Employment Type
- Marital Status
- Education
- Application Date

## Tasks Completed

### Task 1 – Concepts, Data Splitting and Leakage

- Machine Learning concepts
- Stratified train, validation and test splitting
- Decision Tree depth comparison
- Logistic Regression with 5-fold cross-validation
- Data leakage demonstration
- Seven-step Machine Learning workflow

### Task 2 – Preprocessing, Feature Engineering and Pipelines

- SimpleImputer
- KNNImputer
- OneHotEncoder
- OrdinalEncoder
- Feature engineering
- ColumnTransformer
- Scikit-learn Pipeline
- 5-fold cross-validation
- Model saving and loading using Joblib
- Predictions on sample records

### Task 3 – Model Training and Customer Segmentation

**Classification Models**
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

**Regression Models**
- Linear Regression
- Ridge Regression
- Lasso Regression

**Unsupervised Learning**
- K-Means clustering
- Elbow Method
- Silhouette Score
- Customer segment analysis

### Task 4 – Model Evaluation and Hyperparameter Tuning

- Accuracy, Precision, Recall and F1 Score
- Confusion Matrix
- ROC Curve and AUC
- Classification threshold tuning
- Random Forest GridSearchCV
- XGBoost RandomizedSearchCV
- Regression evaluation using MAE, RMSE and R²
- Final model evaluation on the test dataset

## Technologies and Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- XGBoost
- Joblib
- Jupyter Notebook

## Project Files

```text
Week_2_Machine_Learning/
│
├── task1.ipynb
├── task2.ipynb
├── task3.ipynb
├── task4.ipynb
├── task2_pipeline.pkl
├── task1_overfitting.png
├── random_forest_feature_importance.png
├── xgboost_feature_importance.png
├── kmeans_elbow_method.png
├── kmeans_silhouette_scores.png
├── kmeans_cluster_visualization.png
├── task4_roc_curve_comparison.png
└── README.md
```

## Key Results

- Successfully completed all four assessment tasks.
- Compared multiple classification and regression algorithms.
- Implemented preprocessing pipelines and feature engineering.
- Performed hyperparameter optimization.
- Identified Logistic Regression as the best classification model based on validation F1 score.
- Identified Lasso Regression as the best regression model based on validation RMSE.
- Identified six customer segments using K-Means clustering.
- Saved the trained preprocessing pipeline and visualization outputs.

## Conclusion

This assessment provided practical experience with the complete Machine Learning workflow, including data preparation, feature engineering, model training, evaluation, hyperparameter tuning, regression, classification and unsupervised learning.

**Status: Week 2 Machine Learning Assessment Completed.**