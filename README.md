🎬 Movie Recommendation System

A content-based movie recommendation system developed using Python. 
This system uses the TF-IDF Vectorizer to convert movie descriptions into numerical vectors and applies cosine similarity to calculate the similarity between movies. 
It then recommends similar movies based on a selected movie.

Features:

Content-based recommendation: Recommends movies based on movie descriptions and metadata.
TF-IDF Vectorizer: Transforms movie data into numerical vectors.
Cosine Similarity: Calculates the similarity between movies.
Flask Integration: The system is hosted as a web application using Flask.

Project Structure:

Movie-Recommendation-System/

├── Model/                                 # Directory containing trained models

│   ├── movies.joblib                     # Saved movie recommendation model

│   └── similarity.joblib                 # Saved similarity matrix for faster recommendations

├── templates/                             # HTML templates for web pages

│   ├── index.html                        # Home page for movie input

│   ├── layout.html                       # Base layout for web pages

│   └── recommend.html                    # Page displaying recommended movies

├── Movie_Recommendation_System.ipynb      # Jupyter notebook for data processing and model training

├── app.py                                 # Main Flask application

├── movies_data.py                         # Python script for loading and processing movie data

├── requirements.txt                      # Python dependencies

└── README.md                             # Project documentation

Files Overview:

Model/:
movies.joblib: The trained movie recommendation model that provides recommendations based on input.
similarity.joblib: The precomputed similarity matrix to speed up the recommendation process.

templates/:
index.html: The homepage for entering the movie name to get recommendations.
layout.html: The base layout for the web pages, containing common elements like navigation bars.
recommend.html: The page displaying the recommended movies.

Movie_Recommendation_System.ipynb: Jupyter notebook used for data preprocessing, model training, and generating movie recommendations.

app.py: The main Flask application that serves the model and provides a web interface for users.

movies_data.py: Contains functions for loading and processing the movie dataset used by the recommendation system.

requirements.txt: Lists the necessary Python libraries required for the project.

