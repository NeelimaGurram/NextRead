# NextRead — Book Recommendation System

A machine learning-based book recommendation system built using the Book-Crossing dataset. This project explores both memory-based and model-based collaborative filtering techniques to generate personalized book recommendations.

## Project Overview

This project compares different recommendation approaches:

- User-Based Collaborative Filtering
- Item-Based Collaborative Filtering
- Singular Value Decomposition (SVD)

The goal is to improve recommendation accuracy and handle sparse user-item interaction data effectively.

The project demonstrates how matrix factorization techniques like SVD outperform traditional cosine similarity methods in large-scale recommendation systems.

---

## Dataset

Dataset Used: Book-Crossing Dataset

The dataset contains:

- 278,858 users
- 271,379 books
- 1,149,780 ratings

Files used:
- `Books.csv`
- `Users.csv`
- `Book-Ratings.csv`

Source:
https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Surprise Library
- Matplotlib
- Seaborn

---

## Recommendation Techniques

### 1. Memory-Based Collaborative Filtering

#### User-Based Filtering
Finds similar users based on rating patterns and recommends books liked by similar users.

#### Item-Based Filtering
Finds similar books based on user ratings and recommends related books.

#### Similarity Metric
- Cosine Similarity

---

### 2. Model-Based Collaborative Filtering

#### Singular Value Decomposition (SVD)

SVD performs matrix factorization to:
- Reduce dimensionality
- Capture latent user preferences
- Handle sparse datasets efficiently
- Improve recommendation accuracy

---

## Evaluation Metric

The models were evaluated using:

### Root Mean Square Error (RMSE)

| Model | RMSE |
|---|---|
| User-Based Cosine Similarity | 7.94 |
| Item-Based Cosine Similarity | 7.94 |
| SVD | 1.64 |

SVD significantly outperformed traditional collaborative filtering methods.

---

## Key Features

- Personalized book recommendations
- User-item interaction matrix
- Cosine similarity implementation
- Matrix factorization using SVD
- Performance comparison between recommendation methods
- Handling sparse datasets

---

## Project Workflow

1. Data Cleaning & Preprocessing
2. Feature Engineering
3. Train-Test Split
4. User-Based Collaborative Filtering
5. Item-Based Collaborative Filtering
6. SVD Model Training
7. Evaluation using RMSE
8. Recommendation Generation

---

## Challenges

- Sparse dataset
- Cold start problem
- Scalability issues
- Overfitting risks

---

## Future Improvements

- Hybrid recommendation systems
- SVD++
- Alternating Least Squares (ALS)
- NLP-based content recommendations
- Hyperparameter tuning
- Deep learning recommendation models

---

## Results

The SVD-based recommender system achieved much higher prediction accuracy compared to cosine similarity methods.

This project demonstrates:
- the effectiveness of matrix factorization,
- scalability advantages of model-based methods,
- and practical implementation of recommender systems.

---



---

How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
```

2. Open Jupyter Notebook

```bash
jupyter notebook
```

3. Run the notebook

Execute all cells in sequence.

---

Learning Outcomes

Through this project, I learned:

- Collaborative Filtering
- Recommendation Systems
- Matrix Factorization
- SVD
- Data Preprocessing
- Model Evaluation
- Sparse Data Handling
- Machine Learning Workflow

---

References

- Book-Crossing Dataset
- IBM Collaborative Filtering Documentation
- Matrix Factorization Techniques for Recommender Systems

---

## Author

Neelima Gurram  

