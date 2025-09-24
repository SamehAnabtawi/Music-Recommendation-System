# Music-Recommendation-System
Music recommendation system built on the Million Song Dataset (Taste Profile Subset), applying collaborative filtering and matrix factorization to personalize listening experiences.


Project Overview

This project builds a Music Recommendation System using the Million Song Dataset (Taste Profile Subset). It applies collaborative filtering techniques to suggest songs tailored to user preferences.

Dataset

~2M+ user–song interactions

Filtered to ~1.2M after applying thresholds (min songs/user, min listeners/song)

Techniques Implemented

User-User Collaborative Filtering (Cosine Similarity)

Item-Item Collaborative Filtering

Matrix Factorization (SVD, Co-Clustering)

Ranking Metrics: Precision@K, Recall@K, F1 Score

Results

Optimized model with Precision ~0.41, Recall ~0.39, F1 ~0.40

Hyperparameter tuning improved RMSE to ~1.06

Scalable approach for personalized music discovery

How to Run
jupyter notebook "Music_Recommendation_System_Full_Code_upd.ipynb"
