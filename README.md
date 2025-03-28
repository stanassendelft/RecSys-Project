# RecSys-Project
My recommendation system

This project was developed as part of the course System Development for Marketing at the Amsterdam University of Applied Sciences, within the Digital Driven Business Master's program.

Recommender Systems Project — Stan Assendelft 
- Course: System Development for Marketing
- Program: Master Digital Driven Business
- Institution: Amsterdam University of Applied Sciences
- Author: Stan Assendelft

This repository contains two collaborative filtering-based recommendation systems built for different datasets and domains:

- Jester Joke Recommendation System (Joke_RecSys.ipynb)
- Netflix Movie Recommendation System (Netflix_RecSys.ipynb)

Both projects were developed for academic purposes to explore and compare the effectiveness of two widely-used recommendation algorithms: K-Nearest Neighbors (KNN) and Singular Value Decomposition (SVD).

Objectives
- Investigate how well KNN and SVD can predict user preferences.
- Analyse accuracy and computational performance.
- Explore improvements through hyperparameter tuning.
- Compare model outcomes across domains (jokes vs. movies).

File Structure
RECSYS PROJECT - STAN ASSENDELFT
- Joke_RecSys.ipynb                # Notebook for the Jester joke recommender
- Netflix_RecSys.ipynb             # Notebook for the Netflix movie recommender
- Moviedataupdated.csv             # Combined movie ratings + metadata
- movie_titles.csv                 # Original movie titles metadata
- movie_titles_updated.csv         # Cleaned movie titles (for merging)
- training_set.zip                 # Raw Netflix dataset (unzipped in use)
- training_set/                    # Folder with unzipped Netflix training data

Algorithms Used
1. K-Nearest Neighbors (KNN)
- Manual KNN implementation using cosine similarity and neighborhood averaging.
- Surprise KNNBasic for item-based and user-based filtering with hyperparameter tuning.

2. Singular Value Decomposition (SVD)
- Matrix factorization technique from the surprise library.
- Grid search performed to optimize number of factors, regularization, and learning rate.
