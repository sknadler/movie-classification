# Multilabel Classification for Movie Genres

Samantha Nadler<br>
**CSC 149:** Introduction to Text Mining<br>
Prof. Simona Doboli

This is my final project for CSC 149: Introduction to Text Mining at Hofstra University. I was tasked with classifying an unlabeled movie into at least one movie genre, with the goal of submitting predictions to the "Predicting Movie Genres from Plot Summaries" competition on <a href = "https://www.kaggle.com/competitions/predict-movie-genres-from-plot-summaries">Kaggle.

Streaming services use genre categorizations to organize movies and recommend new movies to users based on their watch history, but genre classification is not rigid, as a single movie can pull from various genres and be categorized into several distinct genres on streaming services. This project considers both traditional machine learning and deep learning techniques to classify a movie into at least one genre category. After using a multi-label binarizer to convert lists of genres as the training label as a singular output for each movie, I built a naive Bayes model from scratch and also implemented a BERT model from HuggingFace to calculate upwards to a 0.660 F1 score.
