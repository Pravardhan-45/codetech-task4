# 🎬 Movie Recommender System (Task 4)

This project is a simple movie recommendation system built using the [Surprise](https://surpriselib.com/) library. It utilizes matrix factorization (SVD) on the built-in MovieLens 100K dataset to predict user ratings and recommend movies.

---

## 📁 Dataset

We use the **MovieLens 100k** dataset, which comes preloaded with the `surprise` library.

- 100,000 ratings from 943 users on 1,682 movies.
- Each user has rated at least 20 movies.

---

## ⚙️ Features

- Matrix Factorization using **SVD** algorithm
- Model evaluation using:
  - **RMSE** (Root Mean Square Error)
  - **MAE** (Mean Absolute Error)
- 5-Fold **Cross Validation**
- Generate **Top-5 movie recommendations** for a specific user

---

## 📦 Libraries Used

```python
surprise
matplotlib
pandas
sklearn
