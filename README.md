
# Movie Recommendation System

This Movie Recommendation System suggests movies based on a user's favorite movie using content-based filtering. It analyzes the genres, keywords, cast, and director of movies to find similar movies. The system uses a TF-IDF vectorizer to convert text data into numerical feature vectors and then calculates similarity scores using cosine similarity.


## Run Locally

### Prerequisites
Ensure you have Python installed along with the necessary libraries:
```bash
pip install numpy pandas scikit-learn
```
Clone the repository
```bash
git clone https://github.com/KPkm25/movie-recommendation
```
Ensure your dataset (movies.csv) is in the same directory as your script.

Run the script:
```bash
python movie_recommendation_system.py
```
## Features

- **Content-Based Filtering:** Recommends movies based on the content (genres, keywords, cast, director) of the user's favorite movie.
- **TF-IDF Vectorizer:** Converts text data into numerical feature vectors for similarity comparison.
- **Cosine Similarity:** Measures similarity between movies based on their feature vectors.
- **Closest Match Finder:** Handles slight variations in movie title input to find the closest match in the dataset.
- **Top Recommendations:** Provides the top N similar movies based on similarity scores.



## Tech Stack

- **Python:** Programming language used.
- **NumPy:** Library for numerical computations.
- **Pandas:** Library for data manipulation and analysis.
- **scikit-learn:** Machine learning library for vectorization and similarity calculations.
- **difflib:** Module for finding the closest match to handle user input variations.
- **pickle:** Module for saving and loading the model objects.



## Usage/Examples

```bash

Enter your favourite movie name: The Godfather
Movies suggested for you:
1. The Godfather: Part II
2. Goodfellas
3. Scarface
4. The Godfather: Part III
5. Casino
```
