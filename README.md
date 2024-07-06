# Spotify Tracks Genre Classification

Welcome to the Spotify Tracks Genre Classification project! This repository contains the code and documentation for classifying music genres using machine learning models.

## Contributors

| NRP        | Name                        |
| ---------- | --------------------------- |
| 5025211102 | Adhira Riyanti Amanda |
| 5025211187 | Altriska Izzati K. H.       |
| 5025211199 | Gracetriana Survinta S.       |


## Project Overview
In the era of digital music streaming, platforms like Spotify provide access to millions of tracks with various genres. Classifying these tracks into genres can enhance user experience by providing better recommendations and organization. This project focuses on classifying Spotify tracks into three main genres: EDM, Rock, and Blue Notes using three machine learning algorithms: Support Vector Machine (SVM), Artificial Neural Network (ANN), and Extreme Gradient Boosting (XGBoost).

## Project Goals
- Evaluate Different Models: Compare the performance of SVM, ANN, and XGBoost in classifying music genres.
- Normalization Impact: Analyze how data normalization affects model performance.
- Cross-Validation Impact: Examine the impact of cross-validation on model optimization.

## Dataset
The dataset used in this project was sourced from the Spotify API and contains over 144,000 tracks with 15 features such as danceability, energy, and tempo. The dataset was preprocessed to include only the necessary features and grouped into the target genres.

- Source: Spotify Tracks Dataset on Hugging Face
- Features: Popularity, Duration, Explicit, Danceability, Energy, Key, Loudness, Mode, Speechiness, Acousticness, Instrumentalness, Liveness, Valence, Tempo, Time Signature.
Target Genres: EDM, Rock, Blue Notes.

## Methodology
- Data Preprocessing: Cleaning the dataset, handling missing values, and normalizing features.
- Model Training: Training SVM, ANN, and XGBoost models with and without normalization.
- Cross-Validation: Implementing k-fold cross-validation to evaluate model robustness.
- Model Evaluation: Comparing model performance using metrics like accuracy, precision, recall, and F1-score.

## Results
- Model Performance: XGBoost showed the highest accuracy followed by SVM and ANN.
- Normalization: Models performed better with normalized data. XGBoost's performance remained consistent regardless of whether normalization was applied or not.
- Cross-Validation: Cross-validation improved model stability and performance.

## Conclusion
The project demonstrates that XGBoost outperforms SVM and ANN in classifying Spotify tracks into genres in this dataset. Normalization and cross-validation significantly enhance model performance, making them crucial steps in the machine learning workflow. Notably, XGBoost's insensitivity to normalization makes it a robust choice for datasets where feature scaling may be inconsistent or unnecessary.

## Future Work
- Expand Genre Classification: Include more genres for a broader classification system.
- Feature Engineering: Explore additional features and their impact on model performance.
- Recommendation System: Integrate the model into a system to recommend genres based on user preferences.


