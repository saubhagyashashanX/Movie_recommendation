# 🎬 Movie Recommendation System

An end-to-end **content-based movie recommendation system** that recommends movies based on their similarity to a selected movie.

The project uses **NLP techniques, TF-IDF vectorization, and cosine similarity** to identify movies with similar content. The recommendation engine is exposed through a **FastAPI backend** and connected to an interactive **Streamlit frontend**.

---

## 🚀 Features

- 🎥 Content-based movie recommendations
- 🔤 NLP-based text preprocessing
- 📊 TF-IDF feature extraction
- 📐 Cosine similarity for finding similar movies
- ⚡ FastAPI REST API
- 🖥️ Interactive Streamlit frontend
- 🔄 Real-time recommendations through API
- 📦 Precomputed ML artifacts stored using Pickle
- 🌐 Deployment-ready architecture

---

## 🧠 How It Works

The recommendation pipeline follows these steps:

```text
Movie Dataset
      ↓
Data Cleaning
      ↓
Text Preprocessing
      ↓
Feature Engineering
      ↓
TF-IDF Vectorization
      ↓
TF-IDF Matrix
      ↓
Cosine Similarity
      ↓
Top-N Similar Movies
      ↓
FastAPI
      ↓
Streamlit Frontend
