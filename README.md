🎬 Movie Recommendation System using NLP, TF-IDF & FastAPI
🔍 Overview

This project is a content-based Movie Recommendation System that suggests movies similar to a user’s selected movie using Natural Language Processing (NLP) techniques. The system analyzes movie metadata such as overview, genres, keywords, cast, and crew, transforms the text into numerical vectors using TF-IDF, and computes similarity using Cosine Similarity.

The trained model is deployed as a production-ready REST API using FastAPI, and a Streamlit frontend is used to interact with the system in real time.

🚀 Features

Content-based movie recommendations

NLP text preprocessing (tokenization, stopword removal, stemming)

TF-IDF vectorization

Cosine similarity–based ranking

FastAPI backend for scalable API access

Streamlit frontend for user interaction

Fully deployed backend & frontend

🛠️ Tech Stack

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn, NLTK

NLP: TF-IDF Vectorizer

Similarity Metric: Cosine Similarity

Backend: FastAPI

Frontend: Streamlit

Deployment: Render (Backend), Streamlit Cloud (Frontend)

📊 Project Workflow

Data Collection & Cleaning

Used TMDB dataset

Handled missing values and merged relevant features

Text Preprocessing

Combined movie metadata into a single text feature

Applied lowercase conversion, stopword removal, and stemming

Vectorization

Converted text data into numerical vectors using TF-IDF

Similarity Calculation

Computed cosine similarity between movies

Retrieved top N most similar movies

Model Serialization

Saved trained vectorizer and similarity matrix using Pickle

API Development

Created REST APIs using FastAPI

Implemented health check and recommendation endpoints

Frontend Integration

Built UI using Streamlit

Connected frontend with backend API

Deployment

Backend deployed on Render

Frontend deployed on Streamlit Cloud

📈 Output

The application returns top movie recommendations instantly based on user input and fetches movie posters and metadata dynamically using TMDB API.

🎯 Learning Outcomes

Built a real-world recommendation engine from scratch

Understood NLP pipelines used in production systems

Learned ML model deployment using FastAPI

Gained experience in full-stack ML application development
