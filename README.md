# gene-data-using-unsupervised-learning
Gene data is analyysed using the PCA method
The PCA method is the shorthand for the principal component analysis method.  It makes use of covariance matrices to find correlations between variables and diagonalization of matrices to find igenvectors.

In complex data with many variables, correlations between variables is analysed to first find eigenvectors of mixed data variables.  

The elbow method is then used to isolate the most prominent eigenvectors and discard the rest.

In gene data, many genes are at play in samples.  The most correlated genes are pulled together in igenvectors and then samples.

DBSCAN:  A machine learning algorithm that sorts data points into clusters.
Terminology: 

core point: a point with a minimum number of neighbors within a distance epsilon
borderpoint: a point within a distance of epsilon of the core point but which itself does not have the minimum number of neighbors

Gene Clusters within samples:

samples express different genes.  The raw data lists the sample and the genes expressed within the samples.  PCA and DBSCAN are used to understand which genes are correlated, that is expressed together within different samples.  These methods allow us to group correlated genes together into different clusters
