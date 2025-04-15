# Restaurant-Recommendation-System-Machine-learning
This project presents an Enhanced Restaurant Recommendation System leveraging XGBoost and Ensemble Learning with comprehensive Exploratory Data Analysis (EDA) and Clustering Techniques. It utilizes Yelp-like datasets, focusing on Las Vegas, to provide intelligent recommendations based on user preferences and location.

🚀 Features
📍 Geospatial Clustering: Groups restaurants by location using KMeans with Silhouette Score analysis.

📈 EDA Visualizations: Insights into restaurant distributions, review counts, ratings, and check-ins using Plotly, Seaborn, and Matplotlib.

🤖 Model Training: Predicts restaurant star ratings using:

XGBoost Regressor

Voting Regressor (XGBoost + Random Forest)

🌟 Feature Importance Analysis: Visualizes the impact of each feature.

🧠 Recommendation Engine: Recommends top restaurants based on location and (optionally) categories.

📁 Dataset
The dataset is sourced from a Yelp-like JSON file, filtered for Las Vegas restaurants. It includes:

business_id, name, stars, review_count, categories, latitude, longitude

Additional merged data: checkins, tips, and reviews

🧰 Tech Stack
Python Libraries: pandas, numpy, matplotlib, seaborn, plotly, scikit-learn, xgboost

ML Models: XGBoost, RandomForestRegressor, VotingRegressor

Clustering: KMeans, Silhouette Score

Visualization: Seaborn, Matplotlib, Plotly

📌 How It Works
Data Preprocessing:

Loads business, review, check-in, and tip datasets

Filters for Las Vegas restaurants

Cleans and encodes features

EDA:

Maps of restaurant distribution

Bar plots of top-reviewed and top-rated restaurants

Clustering:

Uses KMeans to cluster based on geolocation

Optimal number of clusters chosen via Silhouette Score

Model Training & Evaluation:

Trains on relevant features to predict stars

Compares predictions of different regressors

Recommendations:

Based on cluster and (optionally) user-specified categories

Outputs top restaurants in the given cluster

📷 Sample Visualizations
📌 Map of Restaurants in Las Vegas (Plotly)

📊 Top 10 Restaurants by Rating

🔍 Silhouette Score Plot for KMeans

🧠 Feature Importance from XGBoost

