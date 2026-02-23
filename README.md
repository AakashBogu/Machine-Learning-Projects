# Machine Learning Projects 🚀

This repository contains end-to-end machine learning projects built using Python and Scikit-Learn.  
Each project includes data preprocessing, model building, evaluation, and results.

---

## 📌 Projects Included

### 1️⃣ Diabetes Prediction
Predict whether a patient has diabetes based on medical diagnostic measurements.

- Algorithms: Logistic Regression
- Dataset: PIMA Indians Diabetes Dataset
- Evaluation: Accuracy, Confusion Matrix
- Status: Completed

🔗 Folder: `/Diabetes-Prediction`

---

### 2️⃣ Movie Recommendation System
A content-based movie recommendation system using similarity metrics.

- Algorithm: K-Nearest Neighbors (Cosine Similarity)
- Technique: Collaborative Filtering
- Dataset: MovieLens Dataset
- Status: Completed

🔗 Folder: `/Movie-Recommendation-System`

---

## 🛠 Tech Stack

- Python
- NumPy
- Pandas
- Scikit-Learn
- Matplotlib / Seaborn

---

## 🎯 Objective

The goal of this repository is to demonstrate practical implementation of core machine learning concepts including:

- Classification
- Recommendation Systems
- Model Evaluation
- Feature Engineering

---

## 👨‍💻 Author

Aakash  
Computer Science Student  

**`create_matrix(df)`**  
Takes the ratings DataFrame and converts it into a sparse CSR matrix. Returns the matrix along with two dictionaries for mapping movie titles to indices and back.

**`recommend_movies(movie_title, X, movie_mapper, movie_inv_mapper, k=5)`**  
Looks up the movie in the matrix, runs KNN, and returns a list of `k` similar movie titles. Returns an error message if the title isn't in the dataset.
