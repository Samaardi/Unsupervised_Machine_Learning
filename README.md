# Unsupervised_Machine_Learning
### Project Overview
In this project, I clustered 5,000 Spotify songs using unsupervised machine learning.

### Methodology
1. **Data Cleaning:** Cleaned the data to remove duplicates and empty values.
2. **Feature Selection:** Chose features like `danceability`, `valence`, `loudness`, `energy`, `acousticness`, etc., for clustering.
3. **Clustering:** Used KMeans for clustering the songs based on the selected features.
4. **Dimensionality Reduction:** Applied PCA to enhance clustering efficiency and interpretability.
5. **Data Standardization:** Standardized the data using MinMaxScaler to scale features between 0 and 1.
6. **Determining Clusters:** Used the Elbow Method based on Inertia score and Silhouette score to determine the optimal number of clusters.
7. **Playlist Creation:** Generated playlists based on KMeans clustering of similar songs closest to their cluster centers.

