# Populist Voter Analysis

This repository contains an in-depth analysis of survey data to explore and identify potential patterns related to populist voters. The analysis includes various statistical techniques such as Principal Component Analysis (PCA), Factor Analysis (FA), clustering methods (K-means, PAM, Kernel K-Means), hierarchical clustering, Expectation-Maximization (EM) clustering, and visualization techniques.

## Data

The data used for this analysis consists of survey responses, with variables covering a wide range of political, social, and demographic aspects. The survey responses are anonymized to maintain participant privacy.

## Analysis Steps

### Principal Component Analysis (PCA)

The analysis begins with PCA to identify underlying patterns in the data. This includes examining the variance explained by each principal component and interpreting the loadings of variables on these components.

### Factor Analysis (FA)

FA is conducted on both scaled and unscaled data to explore underlying factors within the dataset. The uniqueness, proportional variance, and loadings of variables on each factor are analyzed.

### Clustering

#### K-means Clustering

K-means clustering is performed on both scaled and unscaled data to identify natural groupings within the dataset. The optimal number of clusters is determined using silhouette analysis and the elbow method.

#### PAM (Partitioning Around Medoids)

PAM clustering is employed for robust clustering, especially when dealing with outliers. The results are compared with K-means clustering.

#### Kernel K-Means

Kernel K-Means is applied with radial basis kernel functions to capture non-linear relationships in the data. Both scaled and unscaled data are considered.

### Hierarchical Clustering

Hierarchical clustering is performed using Ward's method, and dendrograms are visualized to explore the hierarchical structure of the data.

### EM Clustering

Expectation-Maximization (EM) clustering is utilized to probabilistically assign observations to clusters based on the estimated parameters.

### Visualization

Various visualization techniques, such as biplots, cluster plots, and silhouette plots, are employed to visually interpret the results and understand the structure of the data.

### Conclusion

The README concludes with a summary of findings, insights gained from the analysis, and potential implications related to populist voters. Notable variables contributing to populism are highlighted, and the analysis validates certain sociological theoretical works.

