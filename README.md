## Movie Recommendation System


## Overview
Movie Recommendation System is a Machine Learning project that recommends movies similar to a selected movie using Content-Based Filtering. The system analyzes genres, cast, crew, keywords, and movie overviews to generate accurate recommendations.

## Features
Search movies by title
Top 5 similar movie recommendations
Content-Based Filtering
NLP-based feature extraction
Cosine Similarity recommendation engine
Fast and user-friendly interface
Streamlit web application
Technologies Used
Python
Pandas
NumPy
Scikit-learn
NLTK
Streamlit
Pickle

## Project Structure
Movie-Recommendation-System/
│
├── dataset/
│   ├── tmdb_5000_movies.csv
│   └── tmdb_5000_credits.csv
│
├── model.py
├── app.py
├── movie_dict.pkl
├── similarity.pkl
├── requirements.txt
└── README.md
## How It Works
Load movie and credits datasets.
Merge and preprocess data.
Extract genres, keywords, cast, crew, and overview.
Create tags for each movie.
Convert text into vectors using CountVectorizer.
Calculate similarity scores using Cosine Similarity.
Recommend the most similar movies.
## Installation

Clone the repository:

git clone https://github.com/yourusername/Movie-Recommendation-System.git

Navigate to the project directory:

cd Movie-Recommendation-System

Install dependencies:

pip install -r requirements.txt

Run the application:

streamlit run app.py
Dataset

TMDB 5000 Movie Dataset

## Files:

tmdb_5000_movies.csv
tmdb_5000_credits.csv
Machine Learning Concepts
Natural Language Processing (NLP)
Content-Based Filtering
Feature Engineering
Count Vectorization
Cosine Similarity
Future Enhancements
Collaborative Filtering
Hybrid Recommendation System
User Authentication
Movie Ratings and Reviews
Watchlist Feature
Genre-Based Filtering
Applications
OTT Platforms
Movie Discovery Apps
Entertainment Websites
Recommendation Systems Learning
Results

The system provides fast and accurate movie recommendations by comparing content similarity between movies, making movie discovery easier and more personalized.
