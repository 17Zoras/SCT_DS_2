# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This project was completed as **Task 02** during my Data Science internship at **SkillCraft Technology**. The goal was to perform **data cleaning** and **exploratory data analysis (EDA)** on the classic Titanic dataset from Kaggle to uncover hidden patterns, trends, and relationships between variables.

---

## 📌 Task Objective

> **Task 02**:  
Perform data cleaning and exploratory data analysis (EDA) on a dataset of your choice (e.g., Titanic dataset).  
Explore the relationships between variables and identify patterns and trends in the data.

---

## 🗂️ Dataset Overview

- **Dataset**: [Titanic Dataset from Kaggle](https://www.kaggle.com/c/titanic)
- **Rows**: 891  
- **Columns**: 12  
- **Target Variable**: `Survived` (0 = No, 1 = Yes)

The dataset contains information about passengers such as age, sex, class, ticket fare, and whether they survived the Titanic disaster.

---

## 🧹 Data Cleaning Steps

- Removed irrelevant columns (e.g., `Cabin`, `Ticket`, `Name`)
- Handled missing values in `Age` and `Embarked`
- Converted categorical variables (`Sex`, `Embarked`, `Pclass`) into numerical format
- Checked for duplicate entries
- Renamed columns for clarity (if needed)

Cleaned data is saved as: **`cleaned_titanic.csv`**

---

## 📊 Exploratory Data Analysis (EDA)

Key insights from EDA include:

- **Survival Rate**:
  - Overall survival rate: ~38%
  - Women had a much higher survival rate than men
- **Class-wise Survival**:
  - 1st class passengers had the highest chance of survival
  - 3rd class had the lowest
- **Age Distribution**:
  - Children (<10) had better chances of survival
- **Fare Impact**:
  - Higher fare correlates with higher survival
- **Embarkation Point**:
  - Passengers from Cherbourg (`C`) had the highest survival rate

Visualizations were created using **Matplotlib** and **Seaborn**.

---

## 📁 Files Included

| File Name            | Description                                 |
|----------------------|---------------------------------------------|
| `cleaned_titanic.csv`| Cleaned Titanic dataset used for EDA       |
| `titanic_eda.ipynb`  | Jupyter notebook with code and visuals     |
| `README.md`          | This documentation file                    |

---

## 📌 Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook

---

## 📚 Learnings

- Data cleaning techniques for real-world datasets
- Importance of handling missing data and encoding variables
- Generating visual insights using Python libraries
- Understanding the interplay between multiple features in a dataset

---

## 🙌 Acknowledgements

Thanks to **SkillCraft Technology** for this internship opportunity and guidance on real-world data projects.

---

## 🔗 Dataset Source

[Kaggle Titanic Competition](https://www.kaggle.com/c/titanic)

---
