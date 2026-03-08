# DHC-ML-Task_3
Heart Disease Prediction: A machine learning project using Logistic Regression and Decision Trees to predict heart disease presence based on various health parameters, with detailed EDA and feature importance analysis.
```markdown
# Heart Disease Prediction

## Task Objective
The primary objective of this project is to predict the presence of heart disease in patients based on various health parameters. This involves cleaning and preprocessing the dataset, training a machine learning model, and evaluating its performance.

## Dataset Used
The dataset used for this project is the "Heart Disease Data" obtained from Kaggle (`redwankarimsony/heart-disease-data`). It contains various features related to heart health, including age, sex, chest pain type, cholesterol levels, and more. The dataset was preprocessed to handle missing values and encode categorical features.

## Models Applied
1.  **Logistic Regression**: Used as the primary classification model for predicting heart disease.
2.  **Decision Tree Classifier**: Used specifically for determining feature importance.

## Key Results and Findings
*   **Logistic Regression Model Performance**:
    *   **Accuracy**: 0.8833 (approximately 88.33%)
    *   **ROC-AUC Score**: 0.9394 (indicating good separability between classes)
*   **Confusion Matrix Analysis**:
    *   **True Negatives (TN)**: 33 (Correctly identified as no heart disease)
    *   **True Positives (TP)**: 20 (Correctly identified as having heart disease)
    *   **False Positives (FP)**: 2 (Incorrectly identified as having heart disease when they did not)
    *   **False Negatives (FN)**: 5 (Incorrectly identified as not having heart disease when they did)
*   **Feature Importance (from Decision Tree Classifier)**:
    The most influential features in predicting heart disease, ordered by importance, are:
    1.  `cp` (Chest Pain Type)
    2.  `ca` (Number of major vessels colored by fluoroscopy)
    3.  `chol` (Serum Cholestoral in mg/dl)
    4.  `id` (Patient ID - though this might be an artifact of the model rather than a true medical indicator)
    5.  `thalch` (Maximum heart rate achieved)

This analysis provides a good foundation for understanding the factors contributing to heart disease and demonstrates the effectiveness of the applied machine learning models.
```
