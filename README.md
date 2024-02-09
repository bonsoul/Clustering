# Clustering

Using feature values, clustering is a machine learning technique that divides training examples into groups according to similarities. By defining an entity's position in n-dimensional space using vector coordinates defined by numeric attributes, it finds clusters of related entities that are kept apart from other groups.

Since,the dataset contains six data points (or features) for each instance (observation) of a seed.

Six-dimensional space is difficult to visualize in a three-dimensional world, or on a two-dimensional plot, principle Component Analysis (PCA) is applied. 

### Principle Component Analysis (PCA)
A mathematical technique that converts six-dimensional feature values into two-dimensional coordinates and analyzes feature correlations by summarizing observations as two principle components.

To know how many clusters to separate your data into? within cluster sum of squares (WCSS)  is applied.

### Within cluster sum of squares (WCSS)
 A metric often used to measure this tightness is the within cluster sum of squares (WCSS), with lower values meaning that the data points are closer. You can then plot the WCSS for each model.

 #Training a clustering model
### K-Means

The feature values are vectorized to define n-dimensional coordinates (where n is the number of features). 

## Assumption

One of the fundamental problems with clustering - without known class labels,one does not know how many clusters to separate the data into?
