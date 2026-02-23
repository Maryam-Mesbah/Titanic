# 📊 Titanic – Exploratory Data Analysis Report

## 1️⃣ Objective

The goal of this analysis is to identify key factors that influenced passenger survival and extract actionable insights to guide predictive modeling.

---

## 2️⃣ Target Distribution

* Survival Rate: **38.38%**
* Non-Survival Rate: **61.62%**

The dataset is moderately imbalanced, with more non-survivors than survivors.

---

## 3️⃣ Feature Analysis

### 👩 Gender Analysis

* Female Survival Rate: **74.2%**
* Male Survival Rate: **18.9%**

Gender is the strongest survival determinant, likely reflecting the historical "women and children first" evacuation protocol.

---

### 🎩 Passenger Class (Pclass)

* 1st Class: **63.0% survival**
* 2nd Class: **47.3% survival**
* 3rd Class: **24.2% survival**

There is a strong negative correlation between Pclass and survival (-0.338).
Socio-economic status significantly impacted rescue priority.

---

### 💰 Fare Analysis

* Correlation with Survival: **+0.257**

Higher fares were associated with higher survival probability, reinforcing the socio-economic survival gap.

---

### 🌍 Port of Embarkation

* Cherbourg (C): **55.4%**
* Queenstown (Q): **39.0%**
* Southampton (S): **33.9%**

Passengers from Cherbourg had the highest survival rate, potentially linked to higher class distribution.

---

### 👶 Age Analysis

* Avg Age (Survived): 28.29
* Avg Age (Not Survived): 30.03
* Correlation: **-0.065**

Age shows weak linear correlation, but further segmentation (children vs adults) may reveal non-linear patterns.

---

### 👨‍👩‍👧 Family Features

| Feature | Correlation |
| ------- | ----------- |
| SibSp   | -0.035      |
| Parch   | +0.082      |

Family size had limited direct linear impact, but moderate-sized families may have had better survival coordination.

---

## 4️⃣ Key Insights Summary

1. Gender is the dominant predictive feature.
2. Socio-economic indicators (Class & Fare) strongly influence survival.
3. Age has weak linear influence.
4. Survival patterns reflect structured evacuation behavior rather than randomness.

---

## 5️⃣ Modeling Implications

Based on EDA findings:

* Gender encoding is critical.
* Pclass and Fare must be preserved.
* Interaction features (e.g., FamilySize) may improve performance.
* Non-linear models (Random Forest) may capture hidden interactions better than linear models.

---

# 🎯 Final Recommendation

EDA confirms that survival was primarily determined by structured social priority rules and class hierarchy rather than purely demographic randomness.
😄
