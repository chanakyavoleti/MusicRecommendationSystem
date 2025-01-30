# MusicRecommendationSystem
Overview

This project implements a music recommendation system using K-means clustering, feature correlation analysis with Yellowbrick, and dimensionality reduction techniques (t-SNE and PCA). The goal is to provide personalized music recommendations based on user preferences.

The dataset contains user-song interactions, including genres, years, artists.

- Initial data exploration revealed insights into song characteristics like 'valence', 'year', 'acousticness', 'danceability', 'duration_ms', 'energy', 'explicit',
 'instrumentalness', 'key', 'liveness', 'loudness', 'mode', 'popularity', 'speechiness', 'tempo'
- Yellowbricks package (https://www.scikit-yb.org/en/latest/index.html) was used to analyze feature correlations and identify relevant features for clustering.

Methodology:
1. Data Preprocessing: Data cleaning, filtering, and normalization.
2. Feature Extraction: Extracting relevant features from the dataset, such as user-song interactions and song attributes.
3. K-means Clustering: Clustering users based on their song preferences using K-means.
4. Dimensionality Reduction: Applying t-SNE and PCA to reduce the dimensionality of the feature space.
5. Recommendation Generation: Generating personalized music recommendations for each user based on their cluster assignments and feature similarities.

Results

- The system recommends songs to users based on their past listening behavior and preferences as input.
- The recommendations are personalized and take into account the user's unique taste profile.

Future Work

- Integrate additional features, such as song genres, moods, and lyrics.
- Experiment with other clustering algorithms and dimensionality reduction techniques.
- Develop a user-friendly interface for users to interact with the recommendation system.
