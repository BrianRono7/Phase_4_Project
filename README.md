# 🎬 Movie Recommendation System (MovieLens 100K)

## 📌 Overview
This project builds a hybrid movie recommendation system using the MovieLens dataset. It combines content-based filtering and collaborative filtering (SVD, KNN, NMF) to deliver personalized top-5 movie suggestions.

## 🎯 Business Context
A subscription-based streaming service aims to increase user engagement by reducing choice fatigue and improving content discovery. This system helps personalize the user experience.

## 📊 Dataset
- **Source:** GroupLens MovieLens 100K
- **Files:** ratings.csv, movies.csv, tags.csv, links.csv
- **Features Used:** Movie genres, user ratings, timestamps

## 🧪 Methods
- Data Preprocessing & Feature Engineering
- Content-Based Filtering (TF-IDF on genres)
- Collaborative Filtering (Surprise: SVD, NMF, KNNWithMeans)
- Hybrid Recommender (weighted ensemble)
- Model Evaluation: RMSE, MAE, Precision@5, Recall@5
- Interpretability: Genre influence, latent factor similarity
- Business Simulation: Engagement & diversity metrics

## 🔍 Results
- **Best Model:** Tuned SVD
- **RMSE:** 0.8637
- **Precision@5:** 0.7717
- **Recommendation Diversity:** 92%
- **Projected Engagement Boost:** 23.7%

## 🚀 Future Improvements
- Integrate deep learning methods (e.g. Neural Collaborative Filtering)
- Add implicit feedback and user demographics
- Deploy real-time recommendation engine with online learning

## 📁 Project Structure
