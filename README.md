# 🏥 Healthcare Data Preprocessing Project

## 📌 Overview

This project focuses on preparing a healthcare dataset for machine learning by addressing two major real-world issues: **missing values** and **outliers**.

A combination of statistical and model-based techniques is used to improve data quality and reliability before performing predictive analysis.

---

## 🎯 Objective

- Analyze incomplete data  
- Apply appropriate imputation strategies  
- Identify and handle extreme values  
- Build a refined dataset suitable for prediction tasks  

---

## 🧩 Problem Statement

Healthcare datasets often contain missing entries and abnormal values due to inconsistent reporting.

The objective of this project is to clean and preprocess the data to make it suitable for predicting **disease risk levels**.

---

## 📊 Dataset Description

| Feature | Description |
|--------|------------|
| patient_id | Unique identifier |
| age | Patient age |
| gender | Male / Female |
| region | Geographic region |
| bmi | Body Mass Index |
| blood_pressure | Blood pressure level |
| cholesterol | Cholesterol level |
| glucose | Glucose level |
| disease_risk | Target variable (0 = Low, 1 = High) |

---

## 🔍 Missing Data Treatment

Missing values were identified across both numerical and categorical features.

### Techniques Used

- Statistical imputation (mean and median)  
- Most frequent imputation for categorical features  
- Random sampling with missing indicators  
- KNN-based imputation  
- Iterative imputation (MICE)  

---

## ⚠️ Outlier Handling

Certain numerical features contained extreme values that could impact analysis.

### Methods Applied

- Z-score based detection  
- IQR (Interquartile Range) method  
- Percentile-based capping  
- Winsorization  

---

## 🧪 Final Dataset Strategy

After comparing multiple approaches, the following combination was selected:

- Numerical data → Iterative Imputer (MICE)  
- Categorical data → Most frequent strategy  
- Outliers → Winsorization  

---

## 📈 Result

The processed dataset:

- Contains no missing values  
- Has controlled outliers  
- Preserves dataset size  
- Is suitable for machine learning models  

---

## 🛠 Tools & Libraries

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- SciPy  
- Matplotlib  
- Seaborn  

---

## 📚 Key Insights

- Data preprocessing is essential before modeling  
- Different techniques produce different results  
- Advanced imputation methods improve accuracy  
- Outlier handling should avoid unnecessary data loss  

---

## 🔮 Future Scope

- Apply machine learning models for prediction  
- Evaluate model performance  
- Deploy using web frameworks like Streamlit or Flask  

---

## 💡 Conclusion

This project demonstrates how structured preprocessing can transform raw healthcare data into a clean and reliable dataset, forming a strong foundation for predictive analytics.
