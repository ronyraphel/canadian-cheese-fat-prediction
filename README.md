# 🧀 Canadian Cheese Fat Level Prediction

## Summary

This project focuses on predicting the **fat level of Canadian cheeses** using machine learning techniques. By leveraging manufacturing characteristics, milk type, and moisture content, the model classifies cheeses into fat categories such as **Low Fat**, **Medium Fat**, and **High Fat**.

This project was completed as a **final-year academic project** during my **Bachelor’s degree in Computer Science at Trent University**.

---

## 📘 Project Context
The goal of this project was to apply real-world machine learning techniques to a structured dataset and demonstrate the complete ML lifecycle from data preprocessing to model evaluation and interpretation.

---

## 🎯 Problem Statement

Cheese fat content is an important attribute for:

- Nutritional labeling  
- Product categorization for retailers  
- Quality control for manufacturers  

This project frames fat-level prediction as a **multi-class classification problem**, aiming to outperform baseline approaches while managing moderate class imbalance.

---

## 📊 Dataset

The dataset contains structured information on Canadian cheeses, including:

- Moisture percentage  
- Milk type and treatment  
- Manufacturing and category details  
- Organic classification  

All personally identifiable or sensitive data has been excluded. The dataset was used strictly for **academic and analytical purposes**.

---

## 🧠 Methodology 

### 1. Data Preparation
- Removed non-informative identifiers and descriptive fields  
- Handled missing values using appropriate imputation strategies  
- Applied feature scaling to numerical data  
- Performed one-hot encoding on categorical features  

### 2. Exploratory Data Analysis
- Visualized fat-level distribution  
- Analyzed relationships between moisture content, milk type, and fat levels  
- Identified moisture percentage as a strong predictive signal  

### 3. Model Development
The following models were implemented and evaluated:

- **Baseline Model (Dummy Classifier)**  
  Used to establish a minimum performance benchmark  

- **Logistic Regression**  
  Served as an interpretable linear model with class balancing  

- **Random Forest Classifier**  
  Selected as the final model due to superior performance and robustness  

### 4. Hyperparameter Tuning
- Performed grid search with cross-validation  
- Optimized using **weighted F1-score** to address class imbalance  

---

## 📈 Results

- **Final Model:** Tuned Random Forest Classifier  
- **Test Accuracy:** ~83.7%  
- **Baseline Accuracy:** ~65.5%  
- **Improvement Over Baseline:** ~18%  
- **Weighted F1 Score:** ~83.7%  

---

## 🔍 Key Findings

- **Moisture Percentage** is the strongest predictor of fat level  
- **Milk Type (Cow)** is strongly associated with higher-fat cheeses  
- **Manufacturing method** contributes additional predictive value  

These results align well with established **food science principles**.

---

## 🧬 Feature Importance

The most influential features identified by the Random Forest model include:

- Moisture Percentage  
- Milk Type (Cow)  
- Manufacturing Method (Industrial)  

---

## ⚠️ Limitations & Future Work

- Increase dataset size to improve class balance  
- Incorporate text-based features using NLP techniques  
- Explore advanced models such as Gradient Boosting or XGBoost  
- Add model explainability tools (e.g., SHAP)  

---

## 🛠️ Technologies Used

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Altair  
- Jupyter Notebook  

---

## 🎓 Learning Outcomes

Through this project, I gained hands-on experience in:

- End-to-end machine learning pipelines  
- Feature engineering and preprocessing  
- Model evaluation and comparison  
- Applying machine learning to real-world datasets  

---

## 👤 Author

Rony Raphel, March 2025
Bachelor of Computer Science – Trent University  
Machine Learning | Software Development 
