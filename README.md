## Clustering Geolocation Data

Given taxi locations, key clusters of these taxis have been defined. The clusters can help us build service stations for these taxis in an efficient manner.  
I first used K-Means algorithm before moving to more advanced density-based method, Density-Based Spatial Clustering of Applications with Noise, known as DBSCAN. Finally, in order to address some of the shortcomings of DBSCAN, the more advanced Hierarchical DBSCAN (HDBSCAN) was employed.  

The notebook contains the following sections:

- Import Libraries
- Exploratory Data Analysis
- Visualizing Geographical Data
- Clustering Strength / Performance Metric
- K-Means Clustering
- DBSCAN
- Hierarchical DBSCAN
- Addressing Outliers

Please have a look at the notebook [here](clustering-geolocation-data.ipynb), or open it on [Colab](https://drive.google.com/file/d/1RoNadRHPnZwegvWGs35V76PLPBiaYZba/view?usp=sharing).
