# Movie Recommendation System
This project is a content-based movie recommendation system built using Python. It suggests similar movies based on a given input title by analyzing features such as genres, keywords, cast, crew, and more.

### Features
* Uses a cleaned and preprocessed version of the TMDB 5000 Movie Dataset.

* Combines multiple features (genres, overview, cast, crew) into a single 'tags' field.

* Utilizes Vectorization and cosine similarity to measure movie similarity.

* Returns the top 5 similar movies based on content.

### Technologies Used
* Python

* Pandas

* NumPy

* Scikit-learn

* NLTK

* Jupyter Notebook

### How It Works
* Dataset is loaded and cleaned (removing nulls, unnecessary columns, etc.).

* Key features like genres, cast, crew, and overview are extracted and combined.

* Text data is vectorized.

* Similarity between movies is calculated using cosine similarity.

* You can input a movie title and get top recommendations based on its content.
