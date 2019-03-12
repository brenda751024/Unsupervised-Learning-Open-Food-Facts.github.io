Title: food

<a href="https://colab.research.google.com/drive/1HCcUJkc476kODlQCUXgNoWriZRhl9X7o">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## Project Brief

Open Food Facts is a non-profit association of volunteers. 5000+ contributors have added 600 000+ products from 150 countries using phone app. In this project, I will use unsupervised learning to cluster 44304 food datapoints based on 5 selected features- fat, carbohydrates, proteins,	salt, energy,and identify the information from the results.

## Summary

1.Four clusters were selected based on **KElbow Visualizer** and verified with **Silhouette Visualizer**.

<img src="https://raw.githubusercontent.com/brenda751024/assets/master/KElbow.png" width="290"> <img src="https://raw.githubusercontent.com/brenda751024/assets/master/Silhouette.png" width="290">

2.Carb and Fat are major features that determine the clustering. The clusters are very clear on X/Y face of 3D scatter plot, but not clear on Y/Z or X/Y face.

<img src="https://raw.githubusercontent.com/brenda751024/assets/master/3D_XY.png" width="290"><img src="https://raw.githubusercontent.com/brenda751024/assets/master/3D_YZ.png" width="290">

3.The clusters are consistent with food pyramid. Cluster 3 is lowest layer of the pyramid and then cluster 1, cluster 2 and cluster 0. The consumptions shown in Silhouette Visualizer are also consistent with large amount on cluster 3 and 1. 

4.People are trying to eat healthily because “natural” and “organic “pop up many times.

<p align="center">
<img src="https://raw.githubusercontent.com/brenda751024/assets/master/food%20pyramind.png" width="400">

<p align="center">
<img src="https://raw.githubusercontent.com/brenda751024/assets/master/WordCloud.png" width="700">
