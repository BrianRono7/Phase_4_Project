# 🎬 Movie Recommendation System (MovieLens 100K)

## 📌 Overview
This project builds a hybrid movie recommendation system using the MovieLens dataset. It combines content-based filtering and collaborative filtering (SVD, KNN, NMF) to deliver personalized top-5 movie suggestions.

## 🎯 Business Context
A subscription-based streaming service aims to increase user engagement by reducing choice fatigue and improving content discovery. This system helps personalize the user experience.

## 📊 Dataset
- **Source:** GroupLens MovieLens 100K
- **Files:** ratings.csv, movies.csv, tags.csv, links.csv
- **Features Used:** Movie genres, user ratings, timestamps

## 💡 Business Understanding

The primary aim is to:
- Understand viewer preferences across genres and titles.
- Use user ratings to infer tastes and generate tailored movie suggestions.
- Enhance strategic decision-making on content curation and investment.

## 🎯 Business Objectives

- Deliver personalized movie recommendations to improve user engagement.
- Increase content consumption to boost revenue.
- Reduce user fatigue from browsing large movie catalogs.
- Improve customer retention by enhancing the platform experience.

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
phase_4_project/
│
├── data/                   # Raw and processed datasets
├── notebooks/              # Exploratory and EDA notebooks
├── src/                    # Modular scripts for modeling and evaluation
├── outputs/                # Evaluation results and visualizations
├── README.md               # Project documentation
└── LICENSE                 # License info

## 🙌 Acknowledgments
Special thanks to *Moringa School* for their mentorship and support, and to the open-source community for resources and inspiration.
