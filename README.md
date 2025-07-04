# AIML-TASK-8
# 🤖 AI & ML Internship – Task 8: K-Means Clustering

## 🎯 Objective
This task focuses on performing **unsupervised learning** using the **K-Means clustering algorithm**. You will explore how to group data into clusters, identify patterns, and evaluate clustering performance using visualizations and metrics like the **Silhouette Score**.

---

## 🧰 Tools & Libraries
- Python 3.x
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn (optional)
- Plotly (optional, for interactive plots)

---

## 📦 [Dataset]
- **Dataset:** Mall Customer Segmentation Dataset (https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

---

## 📝 Task Breakdown

### 1. Load and Preprocess Dataset
- Load dataset using Pandas.
- Handle missing values or outliers (if any).
- Normalize or scale features if needed (e.g., `StandardScaler`).

### 2. Visualize Dataset (Optional PCA for 2D View)
- If the dataset is high-dimensional, reduce dimensions using **PCA**.
- Plot using scatter plots to inspect potential clusters visually.

### 3. Fit K-Means and Assign Cluster Labels
- Use `KMeans` from `sklearn.cluster` to fit the data.
- Add cluster labels to the dataset.
- Plot the data points with color-coding by cluster.

### 4. Elbow Method to Find Optimal K
- Loop through different values of `K` (e.g., 1 to 10).
- Plot **Within-Cluster Sum of Squares (WCSS)** to apply the Elbow Method.
- Choose the optimal `K` where the curve bends (elbow point).

### 5. Evaluate Using Silhouette Score
- Use `silhouette_score` from `sklearn.metrics`.
- A higher score indicates better-defined clusters.
- Optionally visualize silhouette plots.

---

## 🔍 Concepts You'll Learn
- **K-Means Clustering**
- **Unsupervised Learning** Concepts
- **Cluster Label Assignment**
- **Elbow Method**
- **Silhouette Score**
- **PCA for Visualization**

---

## 🖼️ Outputs
[Task-8.pdf](https://github.com/user-attachments/files/21053880/Task-8.pdf)
