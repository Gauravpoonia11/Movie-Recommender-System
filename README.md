# 🎬 Movie Recommender System

## 📌 Overview

This project is a **content-based movie recommendation system** that suggests similar movies based on user input. It leverages movie metadata such as genres, cast, keywords, and overview to compute similarity between movies.

---

## 🚀 Features

* Recommends **Top 5 similar movies**
* Uses **content-based filtering**
* Efficient similarity computation using **cosine similarity**
* Clean and scalable preprocessing pipeline

---

## 🧠 How It Works

1. Combine multiple movie attributes (genres, cast, keywords, overview) into a single text feature (`tags`)
2. Perform **text preprocessing** (lowercasing, stemming, normalization)
3. Convert text into numerical vectors using **CountVectorizer**
4. Compute similarity using **cosine similarity**
5. Recommend movies based on similarity score

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* NLP techniques (CountVectorizer, stemming)

---

## 📂 Project Structure

```
├── app.py
├── movie_dict.pkl
├── similarity.pkl  (not uploaded)
├── data/
├── README.md
```

### To generate it locally:

```bash
python model.py
```

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
python app.py
```

---

## 📈 Future Improvements

* Add collaborative filtering
* Deploy using Streamlit / Flask
* Improve recommendation accuracy using deep learning

---

## 🔗 Demo / Output

*(Add screenshots here for better impact)*

---

## 🤝 Contribution

Feel free to fork this repository and contribute!

---

## 📬 Contact

For queries, connect via LinkedIn or GitHub.
