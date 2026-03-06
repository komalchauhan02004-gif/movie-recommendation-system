# 🎬 Movie Recommendation System

A **Content-Based Movie Recommendation System** built using **Python, Machine Learning, and Streamlit** that suggests movies similar to the one selected by the user.

The system analyzes movie features and recommends the most similar movies using **Cosine Similarity**.

---

## 🚀 Features

- Movie recommendation based on similarity
- Content-based filtering
- Fast recommendation using cosine similarity
- Simple and interactive UI built with Streamlit
- Search and select movies easily

---

## 🧠 Machine Learning Concept

This project uses **Content-Based Filtering**.

Steps involved:

1. Data preprocessing  
2. Feature extraction from movie metadata  
3. Text vectorization  
4. Similarity calculation using **Cosine Similarity**

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Pickle

---

## 📂 Project Structure

```
Movie_Recommendation_System/
│
├── app.py                # Streamlit web app
├── movies.pkl            # Processed movie dataset
├── similarity.pkl        # Similarity matrix
├── data.csv              # Raw dataset
├── background.jpeg       # UI background
├── athenura_movie.ipynb  # Data preprocessing notebook
└── README.md
```

---

## ⚙️ How to Run the Project

### 1️⃣ Clone the repository

```
git clone https://github.com/komalchauhan02004-gif/movie-recommendation-system
```

---

### 2️⃣ Go to project folder

```
cd movie-recommendation-system
```

---

### 3️⃣ Install dependencies

```
pip install -r requirements.txt
```

---

### 4️⃣ Run the Streamlit app

```
streamlit run app.py
```

---

## 🎯 Output

The system recommends **5 similar movies** based on the selected movie.

---

## 📈 Future Improvements

- Add movie posters using TMDB API
- Improve recommendation accuracy
- Deploy the project online
- Add user rating system

---

If you like this project, consider giving it a ⭐ on GitHub.
