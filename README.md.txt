# Movie Recommendation System

A machine learning project that builds a movie recommendation engine using:
- Collaborative Filtering (User-Based)
- Content-Based Filtering (TF-IDF)

---

## Project Objective

To recommend movies to users based on:
- Similar user preferences
- Movie genre similarity

---

## Techniques Used

### 1. Collaborative Filtering
- User-user cosine similarity
- Weighted rating prediction

### 2. Content-Based Filtering
- TF-IDF on genres
- Cosine similarity between movies

---

## Dataset

MovieLens dataset:
- 100,836 ratings
- 9,742 movies
- 610 usersatings

Files used:
- movies.csv
- ratings.csv
- tags.csv

---

## Workflow

1. Load & merge datasets
2. Exploratory Data Analysis
3. Build user-item matrix
4. Compute similarity matrix
5. Predict ratings
6. Build recommendation engine
7. Content-based filtering model
8. Evaluate performance

---

## Results

| Model | Metric |
|------|--------|
| Collaborative Filtering | RMSE ~ 0.78 |
| Content-Based | Precision@10 ~ 0.52 |


## Sample Recommendation

**Input:**
Toy Story (1995)

**Output:**
- Toy Story 2
- Monsters Inc
- A Bug’s Life
- Finding Nemo

---

## Visualizations

### Rating Distribution
[Rating Distribution](images/rating_distribution.png)

### Top Movies
[Top Movies](images/top_movies.png)

### Recommendations Example
[Recommendations](images/recommendation_example.png)
