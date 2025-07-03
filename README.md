# Visualizing-Hierarchical-Clustering-with-Dendrograms-Iris-Dataset-
Use scipy to perform Agglomerative Hierarchical Clustering. Create a dendrogram to show merging steps. Cut the tree at a selected level and plot the final cluster labels. from scipy.cluster.hierarchy import dendrogram, linkage linkage_matrix = linkage(X, method='ward')
