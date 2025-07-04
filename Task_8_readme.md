# 🧠 Task 8: Customer Segmentation using K-Means Clustering

This project focuses on segmenting customers from the **Mall Customers dataset** using **K-Means Clustering**, a popular unsupervised machine learning algorithm. The goal is to identify groups of customers with similar behaviors to help businesses make data-driven decisions.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📁 Dataset

- **Filename:** `Mall_Customers.csv`
- **Features Used:**
  - `Annual Income (k$)`
  - `Spending Score (1-100)`

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## 🧩 Objective

To classify mall customers into distinct segments based on their annual income and spending behavior, enabling businesses to:
- Identify high-value customers
- Design targeted marketing strategies
- Understand different spending patterns

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## 🛠️ Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (`KMeans`)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## 📊 Steps Performed

1. **Data Loading and Exploration**
   - Loaded the dataset using `pandas`
   - Checked for missing values and data types

2. **Feature Selection**
   - Selected relevant features: `Annual Income (k$)` and `Spending Score (1-100)`

3. **Finding Optimal Clusters (Elbow Method)**
   - Used the Elbow Method to identify the optimal number of clusters (k = 5)

4. **Applying K-Means Clustering**
   - Applied K-Means algorithm to group customers into 5 clusters

5. **Visualization**
   - Visualized the clusters with colored scatter plots
   - Highlighted centroids of each cluster

6. **Cluster Analysis**
   - Added a new column `Cluster` to the dataset
   - Interpreted the characteristics of each customer group

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## 🔍 Cluster Insights

| Cluster | Avg. Income | Avg. Score | Segment Type                     |
|--------:|-------------|-------------|----------------------------------|
| 0       | 55.3        | 49.5        | Medium income, medium spending   |
| 1       | 86.5        | 82.1        | High income, high spending ⭐     |
| 2       | 25.7        | 79.4        | Low income, high spending        |
| 3       | 88.2        | 17.1        | High income, low spending        |
| 4       | 26.3        | 20.9        | Low income, low spending         |

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## ✅ Conclusion

This project successfully segmented customers into 5 distinct groups based on income and spending behavior. The results provide actionable insights for marketing and business strategy.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
