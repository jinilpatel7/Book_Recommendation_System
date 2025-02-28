📌 Project Overview

The Book Recommendation System is a machine learning-based application that provides personalized book recommendations using two approaches:

Popularity-Based Recommendations: Suggests the most popular books based on overall ratings and reviews.

Collaborative Filtering: Provides book recommendations based on user preferences and similarity scores.

This system is deployed using Streamlit, allowing users to interactively explore book recommendations.

🔧 Model Building & Deployment

Model Building

Data Preprocessing:

Collected Data.

Cleaned the dataset by handling missing values and duplicates.

Created a pivot table to structure user-book interactions.

Popularity-Based Model:

Aggregated book ratings to determine the most popular books.

Used the top-rated books for recommendation.

Collaborative Filtering Model:

Built a similarity matrix using cosine similarity.

Computed similarity scores between books based on user interactions.

Recommended books similar to a user’s chosen book.

Deployment

Streamlit App Development:

Designed an interactive UI with options for Popularity-Based and Collaborative Filtering recommendations.

Model Serialization:

Saved trained models and similarity matrices using Pickle.

Ensured smooth loading of precomputed data for fast recommendations.

Hosting & Execution:

Deployed the application locally using Streamlit.

Enabled real-time book searches and dynamic recommendations.

📊 How It Works

Select a recommendation method from the sidebar.

If "Popularity-Based" is chosen, the top 50 books are displayed.

If "Collaborative Filtering" is chosen, enter a book name to get recommendations.

The system displays recommended books with their title, author, ratings, and cover images.
