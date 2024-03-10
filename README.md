# Movie Recommendation System using TF-IDF and Sigmoid Kernel

## Overview
This project implements a Movie Recommendation System using the TMDB dataset. The system leverages TF-IDF (Term Frequency-Inverse Document Frequency) for feature extraction and computes the sigmoid kernel between two matrices for enhanced recommendation accuracy. It aims to provide users with personalized movie recommendations based on their preferences and past interactions.

## Features
- **TMDB Dataset**: Utilizes the TMDB dataset for movie information including titles, genres, and descriptions.
- **TF-IDF**: Implements TF-IDF for feature extraction, which assigns weights to terms based on their frequency in a document and across all documents. This helps in capturing the importance of terms in movie descriptions.
- **Sigmoid Kernel**: Computes the sigmoid kernel between two matrices, which measures the similarity between movie features. This kernel function helps in quantifying the similarity between movies based on their TF-IDF features.

## Techniques and Models
- **TF-IDF (Term Frequency-Inverse Document Frequency)**: A numerical statistic used to reflect the importance of a term in a document relative to a collection of documents. In this project, TF-IDF is employed to extract relevant features from movie descriptions and improve the accuracy of recommendations.
- **Sigmoid Kernel**: A kernel function used to measure the similarity between two sets of features. By computing the sigmoid kernel between TF-IDF matrices of movies, the system identifies similar movies and provides recommendations to users.

## Algorithms
- **TF-IDF Algorithm**: Calculates the TF-IDF values for terms in the movie descriptions. It involves counting the frequency of each term in a document, computing the inverse document frequency, and multiplying the two to obtain the TF-IDF score.
- **Sigmoid Kernel Algorithm**: Computes the sigmoid kernel between the TF-IDF matrices of movies. It applies the sigmoid function to the dot product of TF-IDF matrices to measure the similarity between movies based on their feature vectors.
