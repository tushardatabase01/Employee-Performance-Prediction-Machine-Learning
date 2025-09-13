# Employee-Performance-Prediction-Machine-Learning
Analyzed INX Employee Data to Predict Performance and Develop Actionable HR Solutions
IABAC Project – Employee Performance Prediction

Analyzed employee performance data to predict outcomes and develop practical organizational insights.
This machine learning project applies classification models to assess employee performance and provide data-driven recommendations.

## Project Overview

This project leverages machine learning techniques to predict employee performance based on organizational and individual attributes. The dataset includes department-wise performance details, and the goal is to build a reliable classification model that can support HR decision-making and workforce optimization.

## Objectives

Perform data preprocessing & cleaning.

Conduct Exploratory Data Analysis (EDA) to identify key factors affecting performance.

Train and evaluate multiple classification models.

Compare model performance and select the best approach for prediction.

## Dataset

Dataset file: iabac.xls

Features include:

Department and demographic details

Performance indicators

Standard HR attributes (e.g., experience, scores, ratings)

Target Variable: Performance Category (e.g., Good / Average / Poor)

## Tech Stack

Programming: Python (Jupyter Notebook)

Libraries:

Pandas, NumPy – Data processing

Matplotlib, Seaborn – Visualization

Scikit-learn – ML models, evaluation, and preprocessing

Imbalanced-learn (SMOTE) – Handling class imbalance

## Workflow
## Data Preprocessing

Checked for null/missing values.

Encoded categorical features.

Standardized numerical attributes.

Balanced the dataset using SMOTE.

## Exploratory Data Analysis (EDA)

Department-wise performance distribution.

Correlation heatmaps and feature relationships.

Boxplots and bar charts to visualize key insights.

## Modeling

Applied classification models:

Random Forest

Support Vector Machine (SVM)

Neural Network (MLP Classifier)

Techniques used:

Dimensionality reduction with PCA

Hyperparameter tuning with GridSearchCV

## Evaluation

Metrics:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

## Key Insights

Departmental trends reveal performance variation across business units.

Key predictors include standardized performance indicators and categorical HR attributes.

SMOTE balancing improved fairness across underrepresented classes.

Ensemble models (e.g., Random Forest) showed strong performance with high accuracy.

## Results

Built a reliable classification model for employee performance prediction.

Achieved strong evaluation scores, making the model useful for HR analytics and workforce planning.

Provides explainable insights into which attributes drive employee performance
