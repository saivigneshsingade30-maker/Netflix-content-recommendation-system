# Netflix-content-recommendation-system
A content-based Netflix recommendation system built using Python, TF-IDF, and cosine similarity.
# Netflix Content Recommendation System

## Project Overview

This project recommends Netflix movies and TV shows based on similarities between their genres and descriptions.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* TF-IDF Vectorization
* Cosine Similarity
* Google Colab

## How It Works

1. Load the Netflix titles dataset.
2. Handle missing genres and descriptions.
3. Combine genres and descriptions into a single text feature.
4. Apply TF-IDF vectorization to convert text into numerical features.
5. Calculate cosine similarity between titles.
6. Recommend the five most similar titles for a selected movie or TV show.

## Example

Input: Stranger Things

Output: Five titles recommended based on their content similarity.

## How to Run

1. Open the notebook in Google Colab.
2. Download the Netflix titles dataset from Kaggle.
3. Upload the CSV file to the notebook.
4. Run the notebook cells in order.
5. Use the recommendation function to test a title.

## Dataset

Netflix Movies and TV Shows dataset:
https://www.kaggle.com/datasets/shivamb/netflix-shows

## Project Status

Week 1 project for a Machine Learning Internship.
