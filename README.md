# 📚 Book Recommender System

A Machine Learning based Book Recommender System built using Flask, Pandas, NumPy, and Collaborative Filtering.

The application recommends books similar to a user's selected book using **Cosine Similarity** and displays the **Top 50 Popular Books** based on ratings and user votes.

---

## 🚀 Features

* Top 50 Popular Books Dashboard
* Book Recommendation Engine
* Similar Book Suggestions
* Interactive & Responsive UI
* Modern Animated Book Cards
* Error Handling for Unknown Books
* Flask Web Application
* Fast Recommendation Generation

---

## 🛠️ Tech Stack

### Frontend

* HTML
* CSS
* Bootstrap

### Backend

* Flask

### Machine Learning

* Pandas
* NumPy
* Scikit-Learn

### Deployment

* Render

---

## 🧠 Recommendation Method

The recommendation system uses:

* Collaborative Filtering
* Cosine Similarity

Instead of comparing books using direct numerical distance, Cosine Similarity compares the **pattern of user ratings**, making recommendations more meaningful even when books have different popularity levels.

---

## 📸 Screenshots

### Home Page

![Home Page](Screenshots/Home.png)

### Recommendation Page

![Recommendation Page](Screenshots/Recommend-1.png)

### Recommendation Results

![Results](Screenshots/Result.png)

### Book Not Found

![Book Not Found](Screenshots/BookNotFound.png)

---

## 📂 Project Structure

```text
book-recommender-system/
│
├── app.py
├── books.pkl
├── popular_df.pkl
├── pt.pkl
├── similarity.pkl
├── requirements.txt
├── Procfile
│
├── templates/
│   ├── index.html
│   └── recommend.html
│
├── Screenshots/
│   ├── Home.png
│   ├── Recommend-1.png
│   ├── Result.png
│   └── BookNotFound.png
│
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/JatinAwasthi/book-recommender-system.git
```

Move into the project directory:

```bash
cd book-recommender-system
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python app.py
```

Open in browser:

```text
http://127.0.0.1:5000
```

---

## 📖 How It Works

1. User enters a book name.
2. The system searches for the book in the dataset.
3. Cosine Similarity scores are calculated from the precomputed similarity matrix.
4. Top similar books are selected.
5. Recommended books are displayed with cover images and author information.

---

## 🌐 Live Demo

Add your Render deployment link here:

```text
https://your-app-name.onrender.com
```

---

## 👨‍💻 Author

**Jatin Awasthi**

MCA Student | Machine Learning Enthusiast

GitHub: https://github.com/JatinAwasthi
