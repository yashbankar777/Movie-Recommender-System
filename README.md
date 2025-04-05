🎬 Content-Based Movie Recommendation System using NLP

🧠 Project Overview

This project implements a content-based movie recommender that suggests similar movies based on textual features like overview, genre, keywords, cast, and crew. By combining these features and applying NLP with cosine similarity, the model can return the most similar movies to any selected title from the dataset.

📊 Key Features

📚 Data Merging & Cleaning:

Merged TMDB movies and credits datasets. Parsed and extracted useful columns (genres, cast, keywords, crew) using ast.literal_eval.

🔍 Text Processing & Feature Engineering

Removed spaces from multi-word entities for better matching.

Constructed a unified tags feature by combining important attributes.

Applied CountVectorizer to convert text into numerical vectors.

🧮 Similarity Measurement

Used cosine similarity to find the most relevant matches.

Implemented a custom recommend() function that takes a movie name and returns top 5 similar movies.

💾 Serialization

Stored processed data and similarity matrix using pickle for efficient model deployment and retrieval.

📁 Dataset

TMDB 5000 Movies Dataset

Source: Kaggle Dataset
