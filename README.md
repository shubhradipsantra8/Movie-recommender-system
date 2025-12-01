🎬 Movie Recommender System

A machine learning–based movie recommendation system that suggests movies similar to a user-selected title. It uses content-based filtering, analyzing movie metadata such as genres, cast, crew, keywords, and overview to compute similarity between films.

🚀 Features

Suggests movies based on similarity scores

Uses TF-IDF / CountVectorizer for text vectorization

Cosine similarity for recommendation

Interactive UI built using Streamlit

Clean, fast, and customizable backend

🧠 Tech Stack

Python

Pandas

NumPy

Scikit-Learn

Streamlit

📂 Dataset

This system uses the TMDB 5000 Movies Dataset, containing:

Movie titles

Cast and crew

Genres

Keywords

Overviews

You can download it from Kaggle or use TMDB’s API.

📌 How It Works

Data is cleaned and preprocessed

Text features are combined

Vectorization using CountVectorizer

Similarity matrix computed using cosine similarity

User selects a movie → top 5 closest matches returned
