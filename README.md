## Overview

Seismic activity analysis plays a crucial role in disaster preparedness and risk mitigation. This project focuses on identifying earthquake-prone regions by applying the **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** algorithm to historical earthquake data. The model detects natural clusters of seismic events based on geographic density, enabling the identification of high-risk seismic hotspots.

Unlike traditional clustering methods, DBSCAN does not require predefining the number of clusters and is highly effective in handling noisy geospatial data, making it well-suited for seismic analysis.


## Objectives

- Analyze historical earthquake data using unsupervised learning techniques
- Identify dense regions of seismic activity (hotspots)
- Distinguish noise or isolated earthquake events
- Support disaster risk assessment and geospatial decision-making


## Dataset

The dataset contains historical earthquake records with key attributes such as:

- Latitude
- Longitude
- Magnitude
- Depth
- Timestamp

The analysis primarily utilizes **latitude and longitude** to perform spatial clustering.


## Methodology

1. **Data Collection & Cleaning**
    - Removal of missing or invalid location values
    - Filtering relevant seismic attributes
2. **Feature Selection**
    - Geographic coordinates (latitude, longitude) used for clustering
3. **Data Scaling**
    - Standardization of spatial features to ensure effective distance-based clustering
4. **Clustering with DBSCAN**
    - Density-based clustering applied to detect seismic hotspots
    - Automatic identification of noise and outliers
5. **Visualization**
    - Clusters plotted on 2D maps for intuitive interpretation
    - Hotspots visually distinguished from sparse regions


## Why DBSCAN?

- Does not require the number of clusters in advance
- Effectively handles noise and outliers
- Suitable for irregular cluster shapes
- Ideal for geospatial and seismic datasets


## Results

- Successfully identified multiple seismic hotspots
- Isolated low-density earthquake events marked as noise
- Revealed spatial patterns not easily visible through traditional analysis


## Applications

- Earthquake risk zoning
- Disaster management planning
- Urban development and infrastructure safety
- Geospatial intelligence and environmental analysis


## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn


## Conclusion

This project demonstrates the effectiveness of density-based clustering techniques in uncovering meaningful seismic patterns. By leveraging DBSCAN, the system provides a reliable and scalable approach to identifying earthquake-prone regions, contributing valuable insights for risk analysis and disaster preparedness.
