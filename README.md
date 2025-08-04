# Penguins-KMeans-Clustering

## Problem
We want to group penguins using their physical features like size and weight. We do not use their species. The goal is to find natural groups using machine learning.

## Solution
We use K-Means clustering. First, we scale the values to make them similar. Then we apply the model to make 3 groups. Each penguin is given a cluster number. We draw simple plots to see how the penguins are grouped.

## What Are We Finding
We are trying to check if the penguins can be grouped using their body measurements. This helps us learn how similar or different they are.

## Columns Used
We use 4 main features for clustering:

- Culmen Length (mm)  
- Culmen Depth (mm)  
- Flipper Length (mm)  
- Body Mass (g)

## Cluster Centers
After clustering, we get the center of each group. These are the average values of each cluster:

- Cluster 0 center: 0.2417, 0.6084, 0.0687, 0.2653
- Cluster 1 center: 0.5615, 0.2265, 0.0681, 0.6641
- Cluster 2 center: 0.6109, 0.6708, 0.0640, 0.3191

## Graph
We made a simple scatter plot.
It shows culmen length vs culmen depth.
Clusters are shown with different colors. The center points are also marked.

## Best K
We used the Elbow method to find the best number of clusters. We tested values from 1 to 9. The graph shows when the error stops dropping fast, that is the best number of clusters.
