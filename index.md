## Project Brief

Open Food Facts is a non-profit association of volunteers. 5000+ contributors have added 600 000+ products from 150 countries using phone app. In this project, I will use unsupervised learning to cluster 44304 food datapoints based on 5 selected features- fat, carbohydrates, proteins,	salt, energy,and identify the information from the results.

## Summary

1. Four clusters were selected based on **KElbow Visualizer** and verified with **Silhouette Visualizer**.
![KElbow](/assets/images/your-image.jpg)
2. Carb and Fat are major features that determine the clustering. The clusters are very clear on X/Y face of 3D scatter plot, but not clear on Y/Z or X/Y face.
2. The clusters are consistent with food pyramid. Cluster 3 is lowest layer of the pyramid and then cluster 1, cluster 2 and cluster 0. The consumptions shown in Silhouette Visualizer are also consistent with large amount on cluster 3 and 1. 
3. People are trying to eat healthily because “natural” and “organic “pop up many times.

