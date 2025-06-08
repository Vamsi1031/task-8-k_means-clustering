# task-8
# K-Means Clustering on Mall Customers Dataset

# Objective
Perform unsupervised learning using K-Means clustering to segment customers based on income and spending score.

# Dataset
Mall_Customers.csv – includes customer features like Gender, Age, Annual Income, and Spending Score.

# Steps Followed
1. Loaded and preprocessed the dataset.
2. Selected relevant features: `Annual Income (k$)` and `Spending Score (1-100)`.
3. Used the **Elbow Method** to find the optimal number of clusters (K).
4. Fitted KMeans with optimal K (e.g., K=5).
5. Visualized the clusters with color coding.
6. Evaluated clustering using **Silhouette Score**.

# Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- PCA (optional for visualization)

# Output
- Plotted Elbow Graph
- Clustered scatter plot of customers
- Silhouette Score printed in the console

# Result
K-Means successfully segmented the customers into distinct clusters based on income and spending behavior.

