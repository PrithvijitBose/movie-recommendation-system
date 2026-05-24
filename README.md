# 🎬 AI Movie Recommendation System

An AI-powered movie recommendation system built using Machine Learning, FastAPI, and Streamlit.

The system recommends movies based on content similarity using TF-IDF vectorization and cosine similarity, while integrating TMDB API for posters and movie metadata.

## 🚀 Features

- Movie recommendation engine
- TF-IDF based similarity matching
- FastAPI backend API
- Streamlit frontend UI
- TMDB poster integration
- Responsive recommendation cards
- Cloud deployment with Render + Streamlit Cloud

---

## 🛠 Tech Stack

### Machine Learning
- Scikit-learn
- TF-IDF Vectorizer
- Cosine Similarity
- Pandas
- NumPy
- NLTK

### Backend
- FastAPI
- Uvicorn

### Frontend
- Streamlit

### Deployment
- Render (Backend)
- Streamlit Cloud (Frontend)

---

## 📂 Project Structure

```bash
movie-recommendation-system/
│
├── app.py
├── main.py
├── requirements.txt
├── runtime.txt
├── .env.example
├── df.pkl
├── tfidf.pkl
├── tfidf_matrix.pkl
├── indices.pkl
└── README.md
```

---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/movie-recommendation-system.git
cd movie-recommendation-system
```

---

### 2️⃣ Create Virtual Environment

```bash
py -3.11 -m venv .venv
```

Activate environment:

#### Windows

```bash
.venv\Scripts\activate
```

---

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Create Environment Variables

Create a `.env` file:

```env
TMDB_API_KEY=your_tmdb_api_key
BACKEND_URL=http://localhost:8000
```

---

### 5️⃣ Run FastAPI Backend

```bash
uvicorn main:app --reload
```

Backend runs at:

```text
http://localhost:8000
```

---

### 6️⃣ Run Streamlit Frontend

```bash
streamlit run app.py
```

Frontend runs at:

```text
http://localhost:8501
```

---

## 🌐 Deployment

### Backend
Deploy FastAPI backend on Render.

### Frontend
Deploy Streamlit frontend on Streamlit Cloud.

---

## 📌 Future Improvements

- Mood-based recommendations
- Semantic search using transformers
- Personalized recommendations
- Hybrid recommendation system
- Recommendation explanations

---

## 📄 License

This project is for educational and portfolio purposes.
