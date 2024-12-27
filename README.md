# Video Game Recommendation System

## Overview

This project implements a recommendation system for video games using collaborative filtering techniques. The system utilizes both User-User and Item-Item collaborative filtering approaches to provide personalized game recommendations based on user ratings and preferences.

## Features

- **User-User Collaborative Filtering**: Recommends games based on the preferences of similar users.
- **Item-Item Collaborative Filtering**: Suggests games similar to those a user has already enjoyed.
- **Data Preprocessing**: Handles missing values and prepares the dataset for analysis.
- **Similarity Calculation**: Utilizes cosine similarity to find similar users or items.
- **Evaluation Metrics**: Implements Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE) for model evaluation.

## Dataset

The project uses the "Video Games Reviews" dataset, which is part of the Amazon product review data collection. The dataset includes:

- User ratings for video games
- Product metadata (e.g., title, price, description)
- User review text and summary

## Implementation Details

### User-User Collaborative Filtering

1. Creates a user-item matrix of ratings
2. Calculates user similarity using cosine similarity
3. Predicts ratings based on similar users' preferences

### Item-Item Collaborative Filtering

1. Constructs an item-item similarity matrix
2. Recommends items similar to those highly rated by the user

## Evaluation

The system's performance is evaluated using:

- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)

## Requirements

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
