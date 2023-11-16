# Machine Learning Model of Movie Recommender System

## Description

In this project, I developed a machine-learning model for a movie recommender system. The model is built using NumPy, Pandas, CSV, Matplotlib, Seaborn, and Scikit-learn. The model analyzes a dataset of movies, calculates the similarity, and recommends similar movies based on the user's preferences.

## Modules Used

Here are the modules that this project uses:

- NumPy
- Pandas
- CSV
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset

This project uses a dataset of movies. The dataset is stored in two CSV files:   
`tmdb_5000_movies.csv` and `tmdb_5000_credits.csv`.  
The 2nd CSV file is too big to upload(about 39 Mb), you can download from:  
https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata      
The dataset contains information about movies such as their titles, overviews, genres, keywords, cast, and crew. 

## How it works

The project extracts the dataset features, transforms dataset column values, and calculates similarity via `cosine_similarity`.

