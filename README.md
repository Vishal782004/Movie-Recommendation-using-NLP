# 🎬 Movie Recommendation System using NLP (TF‑IDF) & FastAPI
# Project Overview
This project is a content‑based movie recommendation system built using Natural Language Processing (NLP) techniques.
It recommends similar movies based on movie descriptions using TF‑IDF vectorization and cosine similarity. 
The backend is powered by FastAPI, and a simple Streamlit frontend is used for user interaction.The system also integrates
with the TMDB API to fetch movie posters and additional details, providing a richer user experience.

![image alt]([image_url](https://github.com/Vishal782004/Movie-Recommendation-using-NLP/blob/be03e34f2411d22a41c303d6cf18ec654c0e23be/Movie_Recommendation.png?raw=true))


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
- Cosine Similarity

# How It Works

1) Movie overviews are cleaned and preprocessed
2) Text data is converted into numerical vectors using TF‑IDF
3) Cosine similarity is computed between movie vectors
4) Given a movie title, the system finds the most similar movies
5) Movie posters and extra details are fetched using TMDB API

# How to Run the Project Locally
1) Clone the Repository
   - git clone https://github.com/your-username/Movie-Recommendation-using-NLP.git
     cd movie-rec-main
2) Create Virtual Environment
   - python -m venv .venv
   - source .venv/bin/activate
3) Install Dependencies
   - pip install -r requirements.txt
4) Setup Environment Variables
   - TMDB_API_KEY=your_tmdb_api_key
5) Run FastAPI Backend
   - uvicorn main:app --reload
6) Run Streamlit Frontend
   - streamlit run app.py

# Dataset
- Source: TMDB Movies Metadata
- Contains movie titles, overviews, genres, ratings, and release dates

# Deployment
- Backend can be deployed on Render / Railway / AWS / Azure
- Frontend can be deployed on Streamlit Cloud

# Future Improvements
- Hybrid recommendation (content + collaborative)
- User login & watch history
- Advanced embeddings (Word2Vec / BERT)
- Improved UI/UX









