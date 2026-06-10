# spotify-recommendation-system
# Spotify Recommendation System

A content-based music recommendation system built using Spotify audio features and machine learning techniques. The system recommends songs that are similar to a given track based on their audio characteristics.

## Overview

This project uses Spotify track data to generate song recommendations. Audio features such as danceability, energy, valence, and tempo are used to represent each song. Principal Component Analysis (PCA) is applied for dimensionality reduction, and Nearest Neighbors with cosine distance is used to find similar songs.

## Dataset

The project uses a Spotify tracks dataset containing approximately 70,000 songs along with their audio features.

### Features Used

* Danceability
* Energy
* Valence
* Tempo

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* PCA
* Nearest Neighbors

## Methodology

### 1. Data Preprocessing

* Removed missing values
* Removed duplicate tracks
* Selected relevant audio features

### 2. Feature Scaling

* Applied MinMaxScaler to normalize feature values

### 3. Dimensionality Reduction

* Used Principal Component Analysis (PCA) to reduce feature dimensions while preserving important information

### 4. Recommendation Engine

* Implemented Nearest Neighbors using cosine distance
* Retrieved songs with similar audio characteristics

## Project Workflow

1. Load Spotify dataset
2. Clean and preprocess data
3. Scale audio features
4. Apply PCA
5. Train Nearest Neighbors model
6. Generate recommendations for a selected song

## Example

Input Song:

Comedy – Gen Hoshino

Output:

The system returns a list of songs with similar audio characteristics based on feature similarity.

## Future Improvements

* Hybrid recommendation system
* User preference-based recommendations
* Interactive web interface
* Evaluation using recommendation system metrics

## Author

Matta Sai Santosh
