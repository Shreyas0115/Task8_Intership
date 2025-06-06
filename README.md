# 🧠 Task 8: Clustering with K-Means

## 🎯 Objective
Perform **unsupervised learning** using **K-Means clustering** on the **Mall Customers dataset** to group customers based on spending behavior and other features.

---

## 📂 Dataset
- **File**: `Mall_Customers.csv`
- **Attributes**:
  - CustomerID (Removed during preprocessing)
  - Gender (Categorical)
  - Age
  - Annual Income (k$)
  - Spending Score (1-100)

---

## 🛠️ Tools & Libraries Used
- Python 3
- pandas
- matplotlib
- scikit-learn (KMeans, PCA, silhouette_score)

---

## 🔍 Workflow

### 1. Data Preprocessing
- Removed the `CustomerID` column
- Label encoded the `Gender` column

### 2. Dimensionality Reduction (PCA)
- Reduced the dataset to 2D for easy visualization

### 3. Elbow Method
- Plotted the **inertia** vs number of clusters (K)
- Identified the optimal K value (e.g., 5)

### 4. K-Means Clustering
- Trained the KMeans model on the preprocessed data
- Assigned cluster labels

### 5. Evaluation
- Calculated **Silhouette Score** to evaluate clustering quality

### 6. Visualization
- Visualized clusters using a scatter plot of PCA-reduced data
- Color-coded the clusters

---

## 📊 Results
- **Optimal Clusters (K)**: 5  
- **Silhouette Score**: ~0.55  
- Clear, well-separated clusters were observed after PCA-based visualization.

---

## 💡 What I Learned

- How K-Means clustering works and why it’s useful for grouping similar data points.
- How to use the **Elbow Method** to determine the best number of clusters.
- Importance of **feature preprocessing** (e.g., label encoding for categorical features).
- How **PCA** helps reduce dimensions for visualization without much loss of information.
- How to evaluate clustering quality using **Silhouette Score**.
- The difference between **clustering** (unsupervised) and **classification** (supervised).

---
