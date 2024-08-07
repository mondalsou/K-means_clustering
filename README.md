# Objective

Getting familiar with K-means clustering, deciding the value of K, and metrics to evaluate clusters.

# Steps

1. **Start a Jupyter notebook container.**
2. **Load the iris dataset:** For now, we will ignore the target values and focus purely on unsupervised learning.
3. **Data Pre-processing:** Scale all the features.
4. **Optional: Dimensionality Reduction to avoid multicollinearity.** Try all methods:
   - **PCA components of the features:**
     - Components based on minimum variance (0.7/0.8)
     - 2 or 3 components so they can be visualized
   - **UMAP components of the features:** 2 or 3 components so they can be visualized
   - **Dropping the highly correlated features:** If three features have high correlation, then two are dropped and one is kept.
5. **Decide K value for K-means:**
   - Use the elbow plot method.
   - Use silhouette analysis method.
6. **Evaluate the clusters:** Use silhouette score as the metric.
7. **Visualize the clusters:**
   - If the features used had only 2-3 dimensions, plot directly and color according to cluster.
   - If the features use more dimensions, first get 2 or 3 components using UMAP/PCA/TSNE/PacMAP and plot them (color according to cluster).
