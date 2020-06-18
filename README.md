# Notes for myself:
Machine Learning is the branch of AI that covers the statistical and learning part of artificial intelligence.
## Supervised Learning  
### Decision Tree
When building a decision tree, we want to split the nodes in a way that lowers entropy and increases information gain.</br>
The amount of information disorder in the data. 
### Linear Regression
With linear regression, you can fit a line through the data.</br>
y=a+b_x1 is the equation for a straight line, which can be used to predict the continuous value y. 
### Logistic Regression
The Sigmoid function is the main part of logistic regression, where Sigmoid of 𝜃^𝑇.𝑋, gives us the probability of a point belonging to a class, instead of the value of y directly.</br>
The goal of regression is to build a model to accurately predict the continues value of a dependent variable for an unknown case.

## Unsupervised learning
Unsupervised learning has Less tests (evaluation approaches) and a better controlled environment.</br>
### Clustering
The points that are classified by Density-Based Clustering and do not belong to any cluster, are outliers.</br>
Hierarchical clustering does not require the number of clusters to be specified.
Before running Agglomerative clustering, you need to compute a distance/proximity matrix, which is an n by n table of all distances between each data point in each cluster of your dataset.
### K means Clustering
K-Means is more efficient than Hierarchical clustering for large datasets.</br>
### DBSCAN
Density-Based Spatial Clustering of Applications with Noise (DBSCAN) is a base algorithm for density-based clustering.
DBSCAN can be used when examining spatial data.
DBSCAN can be applied to tasks with arbitrary shaped clusters, or clusters within clusters

## Recommendation System
Content-based recommendation system tries to recommend items to the users based on their profile built upon their preferences and taste.
