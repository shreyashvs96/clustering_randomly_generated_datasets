# clustering_randomly_generated_data
To validate choice of clustering algorithms and related parameters by experimenting with randomly generated datasets

Advantages of DBSCAN and OPTICS over k-means or hierarchical clustering:
- They are not biased to finding spherical clusters and can in fact find clusters of varying and complex shapes.
- They are not biased to finding clusters of equal diameter and can identify both very wide and very tight clusters in the same dataset.
- They are seemingly unique among clustering algorithms in that cases that do not fall within regions of high enough density are put into a separate “noise” cluster. This is often a desirable property, because it helps to prevent overfitting the data and allows us to focus on cases for which the evidence of cluster membership is stronger.
