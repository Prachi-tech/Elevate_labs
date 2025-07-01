# 📌 Task 6: K-Nearest Neighbors (KNN) Classification

This project demonstrates the implementation of the **K-Nearest Neighbors (KNN)** classification algorithm using the **Iris dataset**. The goal is to understand how KNN works and evaluate its performance on a real-world dataset.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🛠 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn (for visualization)

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📂 Dataset

- **Name**: Iris Dataset
- **Features**: Sepal Length, Sepal Width, Petal Length, Petal Width
- **Target**: Species (`Setosa`, `Versicolor`, `Virginica`)

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📌 Steps Followed

1. **Data Loading**: Loaded the Iris dataset from a CSV file.
2. **Data Preprocessing**:
   - Dropped unnecessary columns (like `Id`).
   - Encoded categorical labels into numerical format.
   - Standardized features using `StandardScaler`.
3. **Train-Test Split**: Divided the dataset into 80% training and 20% testing.
4. **Model Training**:
   - Used `KNeighborsClassifier` from scikit-learn.
   - Experimented with different values of **K** (1 to 10).
5. **Evaluation**:
   - Identified the best value of K based on highest accuracy.
   - Evaluated the model using accuracy score and confusion matrix.
6. **Visualization**:
   - Plotted K vs Accuracy.
   - Applied PCA to reduce dimensions and visualized decision boundaries.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## ✅ Results

- Achieved high accuracy with optimal value of K.
- The confusion matrix showed clear classification of the three species.
- PCA-based decision boundary plot helped visualize KNN's decision-making.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## 📊 Output Samples

- Accuracy vs K Plot
- Confusion Matrix
- Decision Boundary using PCA

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## 📌 Conclusion

- Implemented KNN classification using the Iris dataset.
- Normalized features for consistent distance calculations.
- Found the best K using evaluation metrics.
- Visualized how KNN separates classes after dimensionality reduction.
- Understood the importance of feature scaling and model tuning in KNN.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
