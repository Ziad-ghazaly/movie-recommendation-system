# 🎥 Movie Recommendation System

A collaborative filtering-based engine that recommends similar movies based on user preferences, built using rating data and movie metadata.

---

## 🎯 Project Overview

This system recommends movies similar to a given title using collaborative filtering techniques. It utilizes cosine similarity to measure how close movie preferences are across users.

---

## 📚 Datasets Used

1. **MovieLens Metadata**  
   - `movies.csv`: Contains `movieId`, `title`, `genres`
2. **Ratings Data**  
   - `ratings.csv`: Contains `userId`, `movieId`, `rating`, `timestamp`

📦 Both datasets are part of the [MovieLens 100k dataset](https://grouplens.org/datasets/movielens/100k/), or you can structure them manually if downloaded separately.

---

## ⚙️ Tech Stack

- **Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib
- **Notebook**: Jupyter Notebook

---

## 📈 Recommendation Logic

1. Merge `ratings.csv` and `movies.csv`
2. Build a user-item matrix (rows = users, columns = movies)
3. Compute cosine similarity between movie vectors
4. Recommend top N most similar titles to the selected movie

---

## 📂 Project Structure

```bash
movie-recommendation-system/
├── movie_recommendation_system.ipynb  # Main notebook
├── README.md                          # Project overview

