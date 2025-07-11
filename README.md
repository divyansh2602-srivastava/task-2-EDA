# task-2-EDA

# Titanic Dataset - Data Cleaning and Exploratory Data Analysis (EDA)

## 📌 Task Overview

This repository contains Task 2 of my Data Science Internship at Prodigy Infotech. The objective of this task is to:

- Perform **Data Cleaning** on a dataset (Titanic dataset from Kaggle)
- Conduct **Exploratory Data Analysis (EDA)** to uncover patterns, relationships, and trends
- Generate visualizations to support insights

---

## 📂 Dataset

The dataset used is the famous [Titanic dataset](https://www.kaggle.com/c/titanic/data) available on Kaggle. It provides data about the passengers aboard the RMS Titanic and whether they survived.

Key features include:

- `PassengerId`
- `Pclass`
- `Name`
- `Sex`
- `Age`
- `SibSp`
- `Parch`
- `Ticket`
- `Fare`
- `Cabin`
- `Embarked`
- `Survived` (Target variable)

---

## 🔧 Steps Performed

### 1. Data Cleaning
- Checked for null or missing values
- Filled or dropped missing values as appropriate
- Converted categorical variables into numerical (encoding)
- Removed irrelevant columns (like `PassengerId`, `Name`, etc.)

### 2. Exploratory Data Analysis (EDA)
- Univariate and bivariate analysis using visualizations
- Explored the relationship between survival and features such as:
  - Gender
  - Passenger Class
  - Age Groups
  - Fare Ranges
  - Embarked location
- Generated histograms, count plots, bar charts, heatmaps

### 3. Key Insights
- Female passengers had a much higher survival rate than males
- Passengers in first class had a higher chance of survival
- Younger passengers tended to survive more
- Embarked location showed mild correlation with survival

---

## 📊 Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

