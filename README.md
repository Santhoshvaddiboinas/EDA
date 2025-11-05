DATA SETS
i)Adult
ii)Titanic_data
iii)Wine_quality_red
iv)Train_data

This project performs exploratory data analysis (EDA) and classification modeling to predict income levels (salary >50K or <=50K) using census-style tabular data. The workflow includes data cleaning, visualization, feature engineering, and building predictive models.

Table of Contents
Project Overview

Dataset

Exploratory Data Analysis

Feature Engineering & Cleaning

Modeling

Results

Requirements

Usage

Files

Acknowledgements

Project Overview
Apply EDA to explore relationships in demographic and work data.

Clean and preprocess data, handling missing and duplicate values.

Visualize key categorical and numerical features.

Encode categorical features to prepare for machine learning.

Build a classification model to predict income level.

Dataset
Features: age, workclass, fnlwgt, education, education-num, marital-status, occupation, relationship, race, sex, capital-gain, capital-loss, hours-per-week, native-country, salary.

Target: salary (<=50K or >50K).

Exploratory Data Analysis
Data summary and basic statistics.

Distribution and unique value analysis for all features.

Handling missing values and duplicates.

Visualizations: count plots, box plots, histograms, and relationship graphs.

Feature Engineering & Cleaning
Encode categorical variables (workclass, education, marital-status, occupation, relationship, race, sex, native-country).

Impute or drop missing values in critical columns.

Drop columns with low variance or weak predictive power.

Scale or transform numerical columns if required.

Modeling
Train/test split for evaluation.

Feature selection based on importance and relevance.

Classification models (e.g., Logistic Regression, Random Forest, etc.) to predict income class.

Evaluation metrics: accuracy, precision, recall, F1-score, confusion matrix.

Results
Insights into demographic and occupational factors influencing income.

Model performance on test data.

Visualization and interpretation of feature impact.

Requirements
Python 3.7+

pandas, numpy, matplotlib, seaborn, scikit-learn

Jupyter Notebook


