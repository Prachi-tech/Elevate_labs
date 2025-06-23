# Elevate_labs
Task  given by ElevateLabs in AI ML Internship

# Task 1: Data Cleaning & Preprocessing

### 🎯 Objective:
To clean and prepare raw data for Machine Learning using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

---

## 🛠️ Tools & Libraries Used:
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn (for StandardScaler)

---

## 📋 Steps Completed:

### 1. **Imported Dataset & Explored Basic Info**
- Loaded the dataset using `pandas.read_csv()`.
- Viewed shape, column names, data types, and null values using `.info()`, `.describe()`, and `.isnull().sum()`.

### 2. **Handled Missing Values**
- Filled missing values in `'Age'` and `'Fare'` with the mean.
- Handled `'Embarked'`:
  - If present and not fully empty, filled missing values with mode.
  - If all values were missing, dropped the column.

### 3. **Converted Categorical to Numerical**
- Converted `'Sex'` using `.map({'male': 0, 'female': 1})`.
- Converted `'Embarked'` using `.map({'S': 0, 'C': 1, 'Q': 2})`.

### 4. **Standardized Numerical Features**
- Used `StandardScaler` to normalize `'Age'` and `'Fare'`.

### 5. **Visualized and Removed Outliers**
- Used `sns.boxplot()` to visualize outliers in `'Age'` and `'Fare'`.
- Optionally removed outliers using IQR (Interquartile Range) method.

---

## 📊 Visualization:
Included visualizations like:
- `sns.countplot(x='Survived')` for class distribution
- `sns.boxplot(x='Pclass', y='Age')` to visualize outliers by class

---

## ✅ Final Output:
Cleaned dataset with only relevant columns, all numerical values, and no major outliers.

---

## 📁 Files Included:
- `task1_data_cleaning.ipynb` – Main Jupyter notebook with all code and outputs.
- `README.md` – This file.
- `data/titanic.csv` – Raw dataset.

---

## 🔗 Author:
[Prachi] – B.Tech (IT) | ML Learner |
