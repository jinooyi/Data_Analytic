# Customer Segmentation (K-Means + PCA)

## Project Summary
This project segments customers using **K-Means clustering** and applies **PCA** to visualize clusters in a reduced 2D space. The objective is to discover meaningful customer groups for marketing and strategy.

## What I Built
- K-Means clustering model to group customers
- PCA transformation for visualization and dimensionality reduction
- Cluster quality evaluation using silhouette score

## Key Results
- **Silhouette Score:** 0.3881

## Interpretation & Conclusion
- Silhouette scores range from -1 to 1.  
  A score around **0.388** indicates **moderate cluster separation**:
  - Clusters exist and are distinguishable,
  - but overlap is present (common in real customer datasets).
- Conclusion: The segmentation is **usable for exploratory customer grouping** and can support marketing hypotheses (e.g., different spending/engagement profiles), especially when combined with cluster profiling summaries (means/medians per cluster).

## How to Read the Result
- Higher silhouette = clearer separation.
- Moderate silhouette is still valuable if clusters show meaningful differences:
  - spending level
  - frequency
  - demographic/behavior patterns

## Key Visuals
- ![Elbow Method](images/elbow_method.png)
- ![PCA Cluster Scatter](images/pca_clusters.png)
- ![Cluster Profiles](images/cluster_profile.png)

## Skills Demonstrated
K-Means · PCA · Unsupervised Learning · Cluster Evaluation · Customer Analytics · Visualization
