# 🧠 K-Means Clustering - Customer Segmentation

## 📌 Objective
Perform unsupervised learning using K-Means clustering to segment mall customers based on their purchasing behavior.

## 🛠️ Tools Used
- Python, Pandas, Matplotlib, Seaborn
- Scikit-learn (for scaling, PCA, KMeans, silhouette score)

## 📂 Dataset
**Mall_Customers.csv** — contains details like Age, Annual Income, and Spending Score of customers.

## ✅ Task Workflow
1. **Load and preprocess** data (remove non-numeric columns, scale features)
2. **Visualize** data using PCA (2D projection)
3. **Apply K-Means** clustering (initially with K=3)
4. Use **Elbow Method** to determine optimal number of clusters
5. Refit KMeans with best `K` and **visualize final clusters**
6. **Evaluate** clustering performance using **Silhouette Score**

## 📊 Outputs
- `output/elbow_plot.png` – elbow method plot
- `output/cluster_k5.png` – final cluster visualization (K=5)
- `output/pca_projection.png` – 2D PCA scatter before clustering

## 📈 Result
The K-Means algorithm successfully segmented customers into distinct groups. Silhouette Score helped validate cluster quality, and PCA enabled clear visual interpretation.
