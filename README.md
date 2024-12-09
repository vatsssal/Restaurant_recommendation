# Geolocation-Based Restaurant Recommendation System

## Overview
This project builds a restaurant recommendation system that suggests restaurants based on the user's geolocation (latitude and longitude). It uses KMeans clustering for grouping restaurants and Plotly for visualizing the geographic data. The system provides recommendations based on user location and restaurant reviews.

## Tools & Technologies
- **Libraries**: KMeans Clustering, Plotly, GeoPandas, Pandas, NumPy, Scikit-learn
- **Platform**: Google Colab
- **Other**: Python, Jupyter Notebook

## Steps Involved:
1. **Data Acquisition**: Loaded a dataset of restaurants with their reviews and geographic locations.
2. **Data Preprocessing**: Cleaned and preprocessed the dataset, visualized geographic locations, and handled missing data.
3. **Clustering**: Applied KMeans clustering to group restaurants based on their location and reviews.
4. **Visualization**: Used Plotly and GeoPandas to visualize the restaurant locations and clusters on a map.
5. **Recommendation System**: Developed a function that takes geographic data as input and outputs restaurant recommendations based on the nearest cluster.

## How to Run:
1. Clone the repository:
   ```bash
   git clone https://github.com/vatsssal/RestaurantRecommendation
