# Breast-Cancer-Analysis
Exploratory data analysis on the Wisconsin's public breast cancer dataset
**Data source: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29**
# Description
1. Initial mathematical analysis (mean, varicance, standard deviation) of the classes in the diagnosis feature
2. Predicting class based on the features available and ranking them by order of their accuracy
3. Building a knn model to predict the classes (accuracy: 3nn = 93%, 5nn = 95%)
4. Manually performing fisher's linear discriminant analysis to reduce dimensionality and then predicting the class using knn (accuracy: 96%)
5. Manually performing principal component analysis and using the principal components to predict class (accuracy: 95%)
6. Manually coding for knn
7. Cluster evaluation using davies bouldin index (for kmeans, with 3,5,7 clusters)
8. Cluster evaluation using purity metric (for kmeans, with 3,5,7 clusters)
