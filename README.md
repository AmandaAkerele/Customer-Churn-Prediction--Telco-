# Customer-Churn-Prediction--Telco-

# Project Name: Customer Churn Prediction

## Overview

This project focuses on predicting customer churn in a telecommunications company. Customer churn, also known as customer attrition, occurs when customers stop using the services of a company. Predicting customer churn is crucial for businesses to retain valuable customers and take proactive measures to prevent them from leaving.

## Dataset

The dataset used for this project contains information about customer demographics, usage patterns, and historical behavior. It includes features such as customer age, contract type, usage duration, and customer satisfaction ratings.

## Objective

The primary goal of this project is to develop accurate predictive models for customer churn. The specific objectives include:

1. Data Preprocessing: Clean and preprocess the dataset, handling missing values, encoding categorical features, and scaling numerical features as needed.

2. Exploratory Data Analysis (EDA): Perform EDA to gain insights into customer behavior, identify trends, and understand the factors contributing to churn.

3. Model Selection: Evaluate different machine learning algorithms such as Logistic Regression, Random Forest, Gradient Boosting, and Support Vector Machine (SVM) to identify the best-performing model for churn prediction.

4. Model Evaluation: Use appropriate evaluation metrics such as accuracy, precision, recall, F1-score, and the area under the ROC curve (AUC-ROC) to assess the performance of the selected model.

5. Feature Importance: Determine the most influential features contributing to customer churn using techniques like feature importance scores.

## Model Comparison and Evaluation

the results of different machine learning models and their performance under various resampling techniques are presented and compared.

### Model Comparison Metrics

| Model               | Resampling | Precision | Recall | F1-Score | AUC-ROC |
|---------------------|------------|-----------|--------|----------|---------|
| Logistic Regression | Actual     | 0.650     | 0.516  | 0.575    | 0.846   |
| Logistic Regression | SMOTE      | 0.530     | 0.805  | 0.639    | 0.845   |
| Logistic Regression | ADASYN     | 0.497     | 0.850  | 0.627    | 0.846   |
| Random Forest       | Actual     | 0.677     | 0.449  | 0.540    | 0.844   |
| Random Forest       | SMOTE      | 0.575     | 0.658  | 0.613    | 0.839   |
| Random Forest       | ADASYN     | 0.564     | 0.634  | 0.597    | 0.835   |
| Decision Tree       | Actual     | 0.638     | 0.471  | 0.542    | 0.829   |
| Decision Tree       | SMOTE      | 0.570     | 0.607  | 0.588    | 0.812   |
| Decision Tree       | ADASYN     | 0.543     | 0.639  | 0.587    | 0.813   |
| XGBoost             | Actual     | 0.635     | 0.484  | 0.549    | 0.823   |
| XGBoost             | SMOTE      | 0.564     | 0.634  | 0.597    | 0.835   |
| XGBoost             | ADASYN     | 0.552     | 0.636  | 0.591    | 0.836   |
| SVM                 | Actual     | 0.673     | 0.441  | 0.533    | 0.788   |
| SVM                 | SMOTE      | 0.543     | 0.693  | 0.609    | 0.820   |
| SVM                 | ADASYN     | 0.512     | 0.754  | 0.610    | 0.813   |

These results provide insights into the performance of different machine learning models and their effectiveness under different resampling techniques. The decision about the best model and resampling strategy depends on the specific goals and priorities of the project.

## Key Findings

- Exploratory Data Analysis revealed that customers with shorter contract durations and lower satisfaction ratings are more likely to churn.

- Random Forest model outperformed other models in terms of accuracy, precision, recall, and AUC-ROC.

- Features such as contract type, tenure, and customer satisfaction were identified as the most important predictors of customer churn.

## Conclusion

This project demonstrates the importance of predicting customer churn and provides insights into the factors that influence customer decisions to leave a service. The developed predictive model can assist businesses in identifying high-risk customers and implementing strategies to retain them.

## Future Work

- Continuous monitoring and updating of the churn prediction model to adapt to changing customer behaviors and preferences.

- Integration of real-time data streams for immediate identification of potential churn cases.

- Collaboration with marketing teams to develop targeted retention strategies for customers identified as high-risk for churn.

- Incorporation of external data sources, such as customer interactions on social media, for more accurate churn prediction.

---

*Note: This README report provides an overview of the project and its key findings. Detailed code, analysis, and visualizations can be found in the project's Jupyter Notebook or associated documentation.*
