# 🚢 Titanic Survival Prediction

Predicting passenger survival on the Titanic using exploratory data analysis (EDA) and machine learning.

---

## 📌 Project Overview

This project analyzes the famous **Titanic dataset** to understand which factors influenced passenger survival and builds a predictive model based on those insights.

We explore key features such as gender, passenger class, age, fare, and port of embarkation to uncover meaningful patterns.

---

## 📊 Dataset Summary

* 👥 Total Passengers: 891
* ✅ Survival Rate: **38.38%**
* ❌ Non-Survival Rate: **61.62%**

### 🔹 Gender Distribution

* Male: 577
* Female: 314

### 🔹 Passenger Class

* 1st Class: 216
* 2nd Class: 184
* 3rd Class: 491

### 🔹 Embarked Port

* Southampton (S): 646
* Cherbourg (C): 168
* Queenstown (Q): 77

---

## 🔍 Key Insights

### 👩‍🦰 Survival by Gender

* Female Survival Rate: **74.2%**
* Male Survival Rate: **18.9%**

➡️ Gender was the strongest predictor of survival.

---

### 🎩 Survival by Passenger Class

* 1st Class: **63.0%**
* 2nd Class: **47.3%**
* 3rd Class: **24.2%**

➡️ Higher class passengers had significantly better survival chances.

---

### 🌍 Survival by Port

* Cherbourg (C): **55.4%**
* Queenstown (Q): **39.0%**
* Southampton (S): **33.9%**

---

### 💰 Fare & Survival

* Fare has a **positive correlation (0.25)** with survival.
* Higher ticket prices generally increased survival probability.

---

### 👶 Age & Survival

* Average Age (Survived): 28.29
* Average Age (Not Survived): 30.03

➡️ Age had weak correlation with survival (-0.06).

---

## 📈 Correlation with Survival

| Feature | Correlation |
| ------- | ----------- |
| Fare    | +0.257      |
| Pclass  | -0.338      |
| Age     | -0.065      |
| SibSp   | -0.035      |
| Parch   | +0.082      |

---

## 🧠 Modeling Approach

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Model Training (e.g., Logistic Regression, Random Forest)
* Model Evaluation

---

## 🚀 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn

---

## 📌 Conclusion

The analysis confirms:

* **Women and first-class passengers had the highest survival probability.**
* Socio-economic status (class & fare) strongly influenced survival.
* Family size and age had relatively small impact.

This project demonstrates how structured data analysis can reveal hidden patterns and build meaningful predictive models.

---
