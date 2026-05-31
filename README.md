# 📚 Book Recommender System

A Machine Learning based Book Recommender System built using Flask, Pandas, NumPy, and Collaborative Filtering.

The application recommends books similar to the one entered by the user and displays the Top 50 Popular Books based on ratings and votes.

---

## 🚀 Features

- Top 50 Popular Books
- Book Recommendation Engine
- Similar Book Suggestions
- Interactive and Responsive UI
- Animated Book Cards
- Error Handling for Unknown Books
- Flask Backend

---

## 🛠️ Tech Stack

### Frontend
- HTML
- CSS
- Bootstrap

### Backend
- Flask

### Machine Learning
- Pandas
- NumPy
- Scikit-Learn

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
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/book-recommender-system.git
```

Move into the project folder:

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
2. The system finds that book in the dataset.
3. Similarity scores are used to find related books.
4. Top recommendations are displayed with cover images and author details.

---

## 🌐 Live Demo

Deployed using Render.

---

## 👨‍💻 Author

**Jatin Awasthi**

MCA Student @HBTU | Machine Learning Enthusiast

---

