# 📉 Customer Churn Prediction

## 📌 Overview
Customer churn — also known as customer attrition — occurs when a customer stops using a company’s product or service.  
In competitive markets, **retaining customers** is often more cost-effective than acquiring new ones.  

This project builds a **machine learning classification model** to predict whether a customer will churn based on:
- Demographic data (e.g., gender, senior citizen status, tenure)
- Service-related features (e.g., internet service, phone service, online security)
- Account details (e.g., contract type, monthly charges, payment method)

By identifying customers at **high risk of churning**, companies can take proactive measures to improve retention, minimize revenue loss, and boost customer satisfaction.

---

## 🎯 Project Objective
Develop a **classification model** that:
1. Predicts if a customer will churn.
2. Identifies key factors influencing churn.
3. Helps the business create **data-driven retention strategies**.

---

##  Dataset
- **Name:** `Customer_data`
- **Source:** Provided as part of the project
- **Details:** See `Data Information` document for feature descriptions.

---

## 📦 Project Deliverables

### **1. Data Exploration & Preprocessing **
- Analyzed the dataset for patterns and trends.
- Handled missing values and removed inconsistencies.
- Encoded categorical variables and scaled numerical features.

### **2. Model Development **
- Trained and compared multiple classification algorithms:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
  - XGBoost Classifier
- Tuned hyperparameters for optimal performance.

### **3. Model Evaluation **
- Evaluated models using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
- Selected the **best-performing model** based on a balance of performance metrics.

**Final Model Evaluation Summary (After Hyperparameter Tuning)**

| Model                | Accuracy | Precision | Recall  | F1 Score | ROC-AUC |
|----------------------|----------|-----------|---------|----------|---------|
| XGBoost              | 0.8133   | 0.6884    | 0.5389  | 0.6045   | 0.8648  |
| Logistic Regression  | 0.8204   | 0.6852    | 0.5952  | 0.6370   | 0.8618  |
| Random Forest        | 0.8148   | 0.7029    | 0.5201  | 0.5978   | 0.8598  |
| SVM                  | 0.8197   | 0.6842    | 0.5925  | 0.6351   | 0.8523  |
| KNN                  | 0.7956   | 0.6254    | 0.5684  | 0.5955   | 0.8305  |



## Actions Performed:
- **Data Splitting:** Used train-test split for unbiased evaluation.
- **Hyperparameter Tuning:** Applied GridSearchCV/RandomizedSearchCV for optimization.
- **Documentation:** All preprocessing, modeling, and evaluation steps are recorded.
- **Visualization:** Used graphs to show churn patterns and model performance.

---

## 🛠 Tools & Technologies
- **Programming Language:** Python  
- **Libraries:**
  - pandas, numpy → Data processing
  - matplotlib, seaborn → Visualization
  - scikit-learn → Modeling (Logistic Regression, Decision Tree, Random Forest, SVM, KNN)
  - XGBoost → Gradient boosting
- **Environment:** Jupyter Notebook


