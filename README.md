# KMeans_Clustering-TSF
Task 2:   Exploring_Unsupervised_Machine_Learning


The Problem Statement is from the given ‘Iris’ dataset, predict the optimum number of clusters and represent it visually. This is done using KMeans Clustering. The code starts with the importing of important libraries followed by some Data exploration and Data  Visualzation. The very next step is to do a little of feature engineering. The target column is of Object type(categorical values), so we converted them to integer type using apply function on the column "Species". To standardized all the column values, I have used StandardScaler which will bring all the Feature-values on a same level. The optimal value of K is decided by the elbow-method, followed by building of KMeans Model. The last step is predict the values, compare with the actual values followed by visualization of the Clusters.  
