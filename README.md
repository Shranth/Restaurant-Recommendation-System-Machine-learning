# Restaurant-Recommendation-System-Machine-learning
This project presents an Enhanced Restaurant Recommendation System leveraging XGBoost and Ensemble Learning with comprehensive Exploratory Data Analysis (EDA) and Clustering Techniques. It utilizes Yelp-like datasets, focusing on Las Vegas, to provide intelligent recommendations based on user preferences and location.

🚀 Features
📍 Geospatial Clustering: Groups restaurants by location using KMeans with Silhouette Score analysis.

📈 EDA Visualizations: Insights into restaurant distributions, review counts, ratings, and check-ins using Plotly, Seaborn, and Matplotlib.

🤖 Model Training: 
Predicts restaurant star ratings using:

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

## Results
![image](https://github.com/user-attachments/assets/bb0381c0-f882-4c88-8ba2-910e4d0a9c6c)

![image](https://github.com/user-attachments/assets/989e64d4-92b9-4832-9a28-52f2818bdf1a)


![image](https://github.com/user-attachments/assets/0b44ca04-4024-4b17-8dd9-d714ad8a29eb)


![image](https://github.com/user-attachments/assets/9fee6126-ebc9-4ece-bdc0-2c0f2ba6e3d3)


![image](https://github.com/user-attachments/assets/ae1d56ad-5a6a-4859-8d2b-bc73d8297258)

![image](https://github.com/user-attachments/assets/1adaa779-3d43-4eb2-92f4-397b41d0effa)

![image](https://github.com/user-attachments/assets/524d8456-3de6-4417-9636-02923868bc21)

![image](https://github.com/user-attachments/assets/6c393c68-dee5-4674-ba43-0fce7811e9c7)


![image](https://github.com/user-attachments/assets/a03b0ee5-97c2-49da-9de6-9d9a1932c292)

![image](https://github.com/user-attachments/assets/33fa8f7d-f3ff-4509-86bb-e5b1038fab8f)




 







 





 
 

 
 


