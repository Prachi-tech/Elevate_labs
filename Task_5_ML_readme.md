# Task 5: Decision Trees and Random Forests 🌳🌲

## 🎯 Objective
The goal of this task is to apply tree-based machine learning models — **Decision Trees** and **Random Forests** — for classification. The task involves training, visualization, avoiding overfitting, and evaluating model performance.

---

## 🛠️ Tools & Libraries
- Python
- Scikit-learn
- Graphviz
- Pandas, NumPy
- Matplotlib, Seaborn

---

## 📊 Dataset
- **Filename**: `heart.csv`
- **Description**: Dataset used for binary classification (e.g., predicting heart disease)
- **Target Variable**: `"target"` (1 = Disease, 0 = No Disease)

---

## 🔍 Steps Performed

### 1. Train a Decision Tree Classifier
- Used `DecisionTreeClassifier` from `sklearn`
- Visualized the tree using `graphviz`

### 2. Analyze Overfitting
- Controlled tree complexity using `max_depth=4`
- Compared full vs. pruned decision tree accuracy

### 3. Train a Random Forest
- Used `RandomForestClassifier` with 100 trees
- Achieved high accuracy on the test set

### 4. Feature Importance
- Extracted and visualized top feature importances
- Plotted using Seaborn's barplot

### 5. Cross-Validation
- Performed 5-fold cross-validation
- Evaluated generalization ability with mean accuracy

---

## ✅ Results

| Model                | Accuracy       |
|---------------------|----------------|
| Pruned Decision Tree| 0.80           |
| Random Forest       | 0.985          |
| Cross-Validation Avg| 0.997          |

---

## 📌 Conclusion
- **Random Forest** performed significantly better than the Decision Tree.
- Cross-validation confirmed excellent model generalization.
- Feature importance provided valuable insights into key predictors of heart disease.

---

## 📁 Files Included
- `task5_ML_internship.ipynb` — Full implementation (Jupyter Notebook)
- `heart.csv` — Dataset used for training and testing


---


