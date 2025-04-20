# 🎥 CineMatch – Movie Recommendation System

**CineMatch** is a content-based movie recommendation web app built using **Streamlit** and powered by **TMDB API**.  
It suggests similar movies based on a selected title and shows movie posters, director, cast, rating, and description.

---

## 🔍 Features

- 🔎 Search for any movie from your dataset  
- 🎯 Get top 5 similar movie recommendations  
- 🖼️ Display posters using TMDB API  
- 🎬 View director and cast details  
- ⭐ Show movie ratings and overviews  
- 💻 Built using Python, Streamlit, scikit-learn, and TMDB API

---

## 📦 Dataset

We use a custom cleaned version of IMDb data:  
**`imdb_clean.csv`** containing:
- `title`
- `genre`
- `director`
- `release_year`, etc.

---

## 🛠️ Tech Stack

| Tool | Usage |
|------|-------|
| **Python** | Core language |
| **Streamlit** | Web UI |
| **scikit-learn** | TF-IDF + Cosine Similarity |
| **TMDB API** | Movie posters, overview, cast, director |
| **Pandas / NumPy** | Data wrangling |
| **Requests** | API requests |

---

## 🚀 How To Run Locally

```bash
# Clone the repo
git clone https://github.com/yourusername/movie-recommender-system.git
cd movie-recommender-system

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
