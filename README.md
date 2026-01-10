# 🎬 Movie Recommendation System using NLP (TF‑IDF) & FastAPI
# Project Overview
This project is a content‑based movie recommendation system built using Natural Language Processing (NLP) techniques.
It recommends similar movies based on movie descriptions using TF‑IDF vectorization and cosine similarity. 
The backend is powered by FastAPI, and a simple Streamlit frontend is used for user interaction.The system also integrates
with the TMDB API to fetch movie posters and additional details, providing a richer user experience.

# Features
- Content‑based movie recommendation
- NLP preprocessing on movie overviews
- TF‑IDF vectorization for feature extraction
- Cosine similarity for finding similar movies
- FastAPI backend with REST endpoints
- Streamlit frontend UI
- TMDB API integration for posters & metadata
- Deployed‑ready architecture

# Technologies Used
# Backend
- Python
- FastAPI
- Uvicorn
- Pandas
- NumPy
- Scikit‑learn
- SciPy
- HTTPX
  
# Frontend 
- Streamlit
  
# NLP & ML 
- TF‑IDF Vectorizer

# Project Structure
movie-rec-main/
│
├── app.py # Streamlit frontend
├── main.py # FastAPI backend
├── movies.ipynb # Data preprocessing & model building
├── movies_metadata.csv # Dataset
├── requirements.txt # Project dependencies
├── runtime.txt # Runtime configuration (for deployment)
└── .env # Environment variables (TMDB API key)
- Cosine Similarity
