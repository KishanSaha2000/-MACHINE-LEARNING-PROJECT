# -MACHINE-LEARNING-PROJECT

# Movie Recommendation System using Collaborative Filtering

Overview:
This project builds a movie recommendation system using collaborative filtering in Python. Collaborative filtering suggests movies based on similarities in movie genres, keywords, cast, and crew information. The system uses data from The Movie Database (TMDb) to recommend movies that users are likely to enjoy based on their preferences.

Project Overview:
Two datasets, `tmdb_5000_movies.csv` and `tmdb_5000_credits.csv`, are merged to consolidate movie information like titles, genres, keywords, cast, and crew.
Movie details such as genres, keywords, cast, and crew are extracted and processed into lists suitable for analysis.
Textual features are transformed into numerical vectors using CountVectorizer to compute similarities between movies.
 Cosine similarity is used to measure how similar movies are based on their vectorized features.
 A function recommends movies similar to a given title by sorting and displaying the top matches based on similarity scores.

# House Price Prediction Project 

This project focuses on predicting house prices, leveraging a dataset sourced from Kaggle. The dataset contains various features such as location, size, total square footage, number of bathrooms
, and other relevant attributes that influence house prices. The goal is to build a machine learning model that can accurately predict house prices based on these features.

Project Overview

The project starts with data exploration and cleaning. Steps include handling missing values, feature engineering (such as extracting number of bedrooms from the 'size' column), and converting range values to average where applicable.
 Feature engineering includes creating new features like 'price per square feet' and handling outliers based on location and price per square feet.
 Three regression models are trained and evaluated: Linear Regression, Lasso Regression, and Ridge Regression. The models are implemented using scikit-learn pipelines to streamline data preprocessing and model fitting.
 The models are evaluated using the R^2 score to measure their predictive performance on a holdout test set. The R^2 score indicates how well the model fits the data.
 Once a satisfactory model is selected based on performance metrics, it can be deployed for predicting house prices in Bengaluru based on new input data.


