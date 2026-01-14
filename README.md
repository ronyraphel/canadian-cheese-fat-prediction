🧀 Canadian Cheese Fat Level Prediction
Overview

This project focuses on predicting the fat level of Canadian cheeses using machine learning techniques. By leveraging manufacturing details, milk characteristics, and moisture content, the model classifies cheeses into fat categories such as Low Fat, Medium Fat, and High Fat.

The goal is to demonstrate how structured food production data can be transformed into meaningful insights using modern data science workflows.

Problem Statement

Cheese fat content plays an important role in:

Nutritional labeling for consumers

Product categorization for retailers

Quality control and consistency for manufacturers

This project frames fat-level prediction as a multi-class classification problem, aiming to outperform naive baseline approaches while handling moderate class imbalance.

Dataset

The dataset contains structured information on Canadian cheeses, including:

Moisture percentage

Milk type and treatment

Manufacturing and category details

Organic classification

All personally identifiable or sensitive data has been excluded. The dataset is used strictly for educational and analytical purposes.

Approach & Methodology
1. Data Preparation

Removed irrelevant identifiers and descriptive-only fields

Handled missing values using appropriate imputation strategies

Applied scaling to numerical features

Used one-hot encoding for categorical variables

2. Exploratory Data Analysis

Visualized fat-level distribution

Analyzed relationships between moisture content, milk type, and fat levels

Identified early signals suggesting moisture percentage as a strong predictor

3. Modeling

The following models were implemented and evaluated:

Baseline (Dummy Classifier)
Established a reference accuracy using the most frequent class.

Logistic Regression
Used as a linear, interpretable benchmark with class balancing.

Random Forest Classifier
Selected as the final model due to superior performance and robustness.

4. Hyperparameter Tuning

Performed grid search with cross-validation

Optimized for weighted F1-score to address class imbalance

Results

Final Model: Tuned Random Forest

Test Accuracy: ~83.7%

Improvement over Baseline: ~18 percentage points

Weighted F1 Score: ~83.7%

Key Insights

Moisture percentage is the strongest predictor of fat level

Milk type, particularly cow’s milk, shows a notable association with higher fat content

Manufacturing methods also contribute to prediction strength

The model successfully learned meaningful patterns rather than relying on class frequency alone.

Feature Importance

Top contributing features include:

Moisture Percentage

Milk Type (Cow)

Manufacturing Method (Industrial vs Artisan)

These findings align well with established food science principles.

Limitations & Future Improvements

Class balance could be improved with additional data

Text-based features could be incorporated using NLP

Advanced models such as Gradient Boosting or XGBoost could be explored

Model explainability could be enhanced using SHAP or similar tools

Technologies Used

Python

Pandas, NumPy

Scikit-learn

Altair

Jupyter Notebook

Project Motivation

This project was built to strengthen hands-on experience in:

End-to-end machine learning workflows

Feature engineering and preprocessing

Model evaluation and interpretation

Applying ML concepts to real-world, non-traditional datasets

Author

Rony Raphel
Computer Science | Machine Learning & Software Development
