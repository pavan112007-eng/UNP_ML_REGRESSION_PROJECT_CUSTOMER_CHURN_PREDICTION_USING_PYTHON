# UNP_ML_CLASSIFICATION_PROJECT_CUSTOMER_CHURN_PREDICTION_USING_PYTHON

This project was completed as part of an academic machine learning project, focusing on predicting customer churn in the telecommunications industry using machine learning and deep learning techniques.

The project aims to develop reliable classification models to identify customers who are likely to leave a telecom service provider by analyzing customer behavior, usage patterns, subscription details, and service-related attributes.

Project Overview
- Worked with a dataset containing 3,150 customer records and 14 attributes collected over 12 months from an Iranian telecommunications company.
- Performed Exploratory Data Analysis (EDA) to understand customer behavior and identify patterns associated with churn.
- Identified and handled data quality issues, including 300 duplicate records, and removed irrelevant features.
- Conducted feature engineering, categorical encoding, and feature scaling to prepare the dataset for machine learning.
- Analyzed correlations, outliers, and multicollinearity using correlation heatmaps, IQR, and Variance Inflation Factor (VIF).
Machine Learning Implementation
- Developed classification models using Logistic Regression, K-Nearest Neighbors (KNN), Decision Tree, and Random Forest.
- Implemented advanced algorithms, including Support Vector Machine (SVM), Gradient Boosting, and Gaussian Naive Bayes.
- Developed an Artificial Neural Network (ANN) using TensorFlow for deep learning-based classification.
- Applied SMOTE to handle class imbalance and improve minority-class prediction.
- Evaluated models using five different training and testing splits (80:20, 75:25, 70:30, 65:35, and 60:40).
- Performed ANN architecture tuning by experimenting with 10 different neural network architectures.

Model Evaluation
- Compared classification models using Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
- Analyzed confusion matrices and model performance to understand classification errors.
- Evaluated model consistency across different train-test splits.
- Compared traditional machine learning models with deep learning architectures to identify the best-performing model.

Project Outcome
- Random Forest achieved the best overall machine learning performance, with 96.14% accuracy, 88.04% F1-score, and 98.36% ROC-AUC.
- ANN (256 → 128 → 64 architecture) achieved 94.56% accuracy, 83.24% F1-score, and 98.51% ROC-AUC.
- Identified customer complaints and non-active account status as the strongest indicators associated with customer churn.
- Demonstrated how machine learning can help telecommunications companies identify potential customer loss and develop targeted customer retention strategies.
The project provided practical experience in data preprocessing, exploratory data analysis, feature engineering, handling imbalanced datasets, machine learning algorithms, deep learning, and model evaluation. It demonstrates an end-to-end machine learning workflow for customer churn prediction and data-driven business decision-making.

This is the Link for Classification Google Colab File : https://drive.google.com/file/d/1ZHzn6RStmP_gEY94oEZ0QaiW2sRY88pC/view?usp=sharing

This is the Link for Classification Presentation : https://docs.google.com/presentation/d/1F_8mVafcp_xnoegwk04euANll_hAjTXM/edit?usp=sharing&ouid=109262187964509531267&rtpof=true&sd=true
