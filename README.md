# Titanic-Exploratory-Data-Analysis-EDA-Python-Pandas-Seaborn
EDA of the Titanic dataset as part of Data Analyst Internship Task 5 — includes data cleaning, visualization, statistical exploration, insights, and answers to 7 EDA interview questions using Python, Pandas, Matplotlib, and Seaborn.

# 🚢 Titanic — Exploratory Data Analysis (EDA)

## 📌 Overview
This project is part of my **Data Analyst Internship (Task 5)**, focusing on **Exploratory Data Analysis** of the Titanic dataset using **Python, Pandas, Matplotlib, and Seaborn**.

The goal is to extract insights, identify patterns, and visualize relationships between passenger attributes and survival rates.

---

## 📂 Dataset
- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- **Files Used**: `train.csv`
- **Target Variable**: `Survived` (0 = Did not survive, 1 = Survived)

---

## 🛠 Tools & Libraries
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---
<img width="2880" height="1800" alt="5 A" src="https://github.com/user-attachments/assets/34ae73e1-c8d9-4d33-b926-0c8571c8967d" />

## 🔍 Steps Performed
1. **Data Loading & Inspection**
   - Used `.info()`, `.describe()`, `.value_counts()` for basic exploration.
2. **Data Cleaning**
   - Handled missing values in `Age`, `Embarked`, `Fare`.
   - Created derived features: `Title`, `FamilySize`, `IsAlone`, `HasCabin`.
3. **Univariate Analysis**
   - Histograms, countplots, and boxplots for single-column exploration.
4. **Bivariate Analysis**
   - Relationships between `Survived` and `Sex`, `Pclass`, `Age`, `FamilySize`.
5. **Multivariate Analysis**
   - Combined categorical variables to check interaction effects.
6. **Correlation Analysis**
   - Heatmap and pairplot to detect patterns and feature relationships.
7. **Observations**
   - Added insights after each visual.
8. **Summary**
   - Final key takeaways highlighting survival patterns.
9. **Interview Questions**
   - Answered all 7 EDA-related questions from the task PDF.

<img width="2880" height="1800" alt="5 B" src="https://github.com/user-attachments/assets/2d502b72-f119-4efd-bea9-de6be46c3043" />

---
![Uploading 5 B (2).png…]()


## 📊 Key Insights
- Females had a significantly higher survival rate than males.
- 1st class passengers had a higher chance of survival compared to 3rd class.
- Higher fare and presence of a cabin were positively correlated with survival.
- Children had better chances of survival compared to middle-aged passengers.
- Moderate family sizes tended to have higher survival rates.

<img width="2880" height="1800" alt="5 F" src="https://github.com/user-attachments/assets/6fd10cf2-7978-4ce2-8ec2-9c3dc217eefb" />

---

## ELEVATE LABS INTERNSHIP TASK 5
