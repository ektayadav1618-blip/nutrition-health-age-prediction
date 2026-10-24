# Nutrition Health Survey – Age Prediction

**Summer Analytics 2026 | Mini-Hackathon | IIT Guwahati**

## Project Overview

This project focuses on predicting age groups using nutrition and health survey data from the NHANES dataset. The challenge involved exploring health-related features, comparing machine learning models, and evaluating their performance on an imbalanced classification problem.

## Objectives

- Explore patterns in nutrition and health-related data.
- Build and compare machine learning classification models.
- Engineer meaningful features from health and metabolic indicators.
- Evaluate model performance using F1 score and cross-validation.

## Methodology

### 1. Exploratory Data Analysis
Examined the dataset and explored relationships between health indicators and the target age groups.

### 2. Feature Engineering
Experimented with derived features involving BMI, glucose, insulin, and other metabolic indicators, including ratios and interaction-based features.

### 3. Model Experimentation
Compared multiple approaches, including Logistic Regression, Decision Trees, Random Forest, Gradient Boosting, and XGBoost.

### 4. Model Optimization
Explored hyperparameter tuning, classification-threshold optimization, and ensemble approaches to investigate potential improvements.

### 5. Model Validation
Used stratified cross-validation and F1 score to assess model performance while accounting for class imbalance.

## Results

The final cross-validation notebook documented the following result:

| Metric | Result |
|---|---|
| Model | XGBoost |
| Validation strategy | 5-fold stratified cross-validation |
| Average validation F1 score | 0.4143 |

*Note: This is the cross-validation result, not the competition leaderboard score.*

## Key Learnings

- A more complex model does not automatically produce better results.
- Feature engineering and model tuning need to be validated experimentally.
- Class imbalance makes choosing an appropriate evaluation metric important.
- Cross-validation helps assess model performance across different data splits.

## Tools and Technologies

- Python
- Pandas and NumPy
- Scikit-learn
- XGBoost
- Jupyter Notebook
- Machine Learning and Feature Engineering

## About the Challenge

This project was developed as part of the Nutrition Health Survey – Age Prediction challenge during Summer Analytics 2026, organized by the Consulting & Analytics Club, IIT Guwahati.
