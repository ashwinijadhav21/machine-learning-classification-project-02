#customer personality analysis

Built an end-to-end Customer Personality Analysis & Churn Prediction system using machine learning techniques such as Logistic Regression and Decision Tree. Applied WOE (Weight of Evidence) and Information Value (IV) for feature engineering and selection.
The project includes model evaluation using standard metrics and advanced business analytics like Roll Rate Analysis and Vintage Analysis to understand customer behavior and churn patterns.

📌 Project Overview

This project implements an end-to-end Customer Personality Analysis & Churn Prediction system using an industry-standard machine learning pipeline.
The goal is to classify customers as Churn (Bad) or Non-Churn (Good) while also performing key analytics such as Roll Rate Analysis and Vintage Analysis.

⚙️ Key Features

🔹 Feature Engineering

Time-based bucketing
Weight of Evidence (WOE) Encoding
Information Value (IV) Analysis
Feature selection based on IV

🔹 Machine Learning Models

Logistic Regression
Decision Tree Classifier
K-Fold Cross Validation

🔹 Model Evaluation

Accuracy, Precision, Recall, F1 Score
Confusion Matrix
ROC Curve & AUC

🔹 Customer Analytics

Roll Rate Analysis
Vintage (Cohort) Analysis

| File                    | Description                    |
| ----------------------- | ------------------------------ |
| iv_values.csv           | Feature importance using IV    |
| transformed_dataset.csv | Dataset with WOE & IV features |
| final_model_metrics.csv | Model performance summary      |
| model_predictions.csv   | Actual vs predicted values     |
| roll_rate.csv           | Time-based churn trends        |
| vintage_analysis.csv    | Cohort-wise customer analysis  |

🧠 Key Insights

WOE transformation improves model interpretability
Logistic Regression performs well on structured data
Decision Tree captures non-linear relationships
Time-based cohorts reveal changing customer behavior

🚀 Tools & Technologies

Python (Pandas, NumPy)
Scikit-learn
Matplotlib
PyCharm

📌 Conclusion

This project demonstrates a complete Customer Analytics & Churn Modeling pipeline, combining Machine Learning with Business Insights.
It reflects real-world practices used in marketing analytics, CRM systems, and customer retention strategies.

