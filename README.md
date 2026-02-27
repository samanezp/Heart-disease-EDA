# Heart Disease - Exploratory Data Analysis (EDA)

## 📌 Overview
This project presents an Exploratory Data Analysis (EDA) of the Heart Disease dataset.  
The objective is to explore clinical patterns, understand feature relationships, and identify variables that may contribute to heart disease prediction.

---

## 📌 Objectives
- Understand dataset structure and feature types  
- Analyze numerical and categorical distributions  
- Examine relationships between variables  
- Identify key features associated with heart disease  

---

## 📂 Dataset
The dataset contains 303 patient records with 14 features, including:

- Age  
- Resting blood pressure (`trestbps`)  
- Serum cholesterol (`chol`)  
- Maximum heart rate achieved (`thalach`)  
- ST depression (`oldpeak`)  
- Chest pain type (`cp`)  
- Exercise-induced angina (`exang`)  
- Number of major vessels (`ca`)  
- Thalassemia result (`thal`)  

**Target variable:**  
- `0` → No heart disease  
- `1` → Presence of heart disease  

Source: UCI Machine Learning Repository / Kaggle

---

## 📌 Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📌 Key Insights
- `oldpeak` and `thalach` show strong separation between target classes.  
- Categorical features such as `cp`, `ca`, and `thal` exhibit meaningful distribution differences.  
- Among binary variables, `exang` demonstrates notable structural associations.  
- Several numerical features show scale differences and outliers.

---

## 📌 Conclusion
The analysis highlights several influential clinical indicators relevant to heart disease prediction.  
These findings provide a strong foundation for subsequent machine learning modeling.

---


📌 This project focuses on exploratory analysis only. Future work may include feature engineering and predictive modeling.
