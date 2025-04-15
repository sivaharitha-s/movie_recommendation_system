# Movie_recommendation_system

# Overview
This project implements a movie recommendation system based on cosine similarity. It uses data about movies, such as genres, keywords, title, and other attributes, to suggest similar movies based on a user's input movie title. The system processes the movie data, calculates similarity scores between movies, and returns a list of similar movies.

# Features

Cosine Similarity: Measures the similarity between movies based on their metadata.

Input: The user is prompted to enter the title of their favorite movie.

Movie Suggestions: The system provides a list of movies similar to the input movie based on calculated similarity scores.

Data Source: The movie data is read from a CSV file (movies.csv), which contains various movie attributes such as genre, keywords, director, and more.

# Steps Involved

# Data Preprocessing:

Clean and process movie data by removing missing values.

Combine relevant movie features such as genres, keywords, title, etc., to create a text representation of each movie.

# Feature Extraction:

Use TF-IDF Vectorizer to convert the combined text data into numerical feature vectors.

Cosine Similarity Calculation:

Calculate the cosine similarity between all movie feature vectors.

# Movie Matching:

Use difflib to find the closest match for the input movie title.

Retrieve the similarity scores for the selected movie and sort them to suggest the most similar movies.

# Output:

Display the most similar movies based on the similarity scores.

# Requirements

pandas for data manipulation.

numpy for numerical operations.

sklearn for the TF-IDF vectorizer and cosine similarity.

difflib for fuzzy matching of movie titles.
