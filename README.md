# Movie Recommendation System

This is a simple movie recommendation system that suggests movies based on user input. The system uses cosine similarity to find movies that are similar to the one entered by the user.

## Features

- **Data Collection and Pre-Processing**: The system loads movie data from a CSV file and pre-processes it by combining relevant features such as genres, keywords, tagline, cast, and director.
- **Cosine Similarity**: The system calculates the similarity between movies using cosine similarity on TF-IDF vectors.
- **User Input**: The user can input their favorite movie, and the system will find the closest match from the dataset.
- **Recommendation**: The system recommends up to 30 movies that are most similar to the user's input.

## Dependencies

- `numpy`
- `pandas`
- `difflib`
- `scikit-learn`
