# 🎬 Movie Recommendation System

A collaborative filtering-based movie recommendation system built using the MovieLens 100K dataset. The project predicts similar movies based on user ratings using Pearson correlation.

## 📁 Dataset

- **Source**: [MovieLens 100K Dataset on Kaggle](https://www.kaggle.com/datasets/grouplens/movielens-100k-dataset)
- **Files Used**:
  - `u.data` – Ratings file (user_id, item_id, rating, timestamp)
  - `u.item` – Movie titles file (item_id, title, genres...)

## 🛠️ Tools Used

- Python 🐍
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

## 📊 Project Workflow

### 1. Data Loading and Merging
- Loaded `u.data` and `u.item` files.
- Merged them to attach movie titles to user ratings.

### 2. Exploratory Data Analysis (EDA)
- Identified most rated movies.
- Analyzed distribution of ratings.

### 3. User-Movie Matrix Creation
- Created a pivot table with users as rows and movie titles as columns.
- Each cell contains the user's rating for that movie.

### 4. Recommendation System
- For a selected movie (e.g., "Star Wars (1977)"), calculated Pearson correlation with every other movie.
- Filtered top correlated movies with at least 100 ratings.

### 5. Visualization
- Plotted correlation scores of top recommended movies.


## 🚀 How to Run

1. Download the dataset from [here](https://www.kaggle.com/datasets/grouplens/movielens-100k-dataset).
2. Place `u.data` and `u.item` in your project folder.
3. Run the Jupyter Notebook or Google Colab with the code provided.

## 📌 Future Improvements

- Implement matrix factorization (SVD).
- Add user-based collaborative filtering.
- Use deep learning for hybrid recommendations.

## 👨‍💻 Author

- [vaishnav-DA]

---











