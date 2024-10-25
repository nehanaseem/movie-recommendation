Movie Recommender System

A Movie Recommender System that suggests similar movies based on content-based filtering techniques. This project leverages machine learning algorithms, including TF-IDF vectorization and cosine similarity, to identify and recommend movies with similar metadata. The application is designed to help users discover new movies based on the content of movies they already like.

Project Overview:

The Movie Recommender System uses a dataset of movie metadata to generate recommendations based on a selected movie's content. The system calculates similarities between movies using content features (such as overviews and genres) and outputs a list of similar movies. For each recommendation, it also retrieves and displays movie posters using The Movie Database (TMDB) API.

Features:

Content-Based Filtering: Recommends movies similar to the user-provided movie.

TF-IDF Vectorization: Converts movie descriptions into numerical values for similarity calculation.

Cosine Similarity: Measures similarity between movies based on the TF-IDF vectors.

Movie Poster Retrieval: Dynamically fetches and displays posters for recommended movies using TMDB API.

How It Works:

The Movie Recommender System follows these steps:

User Input: The user provides the name of a movie they like.

Data Processing: The system retrieves the overview and metadata of the selected movie and uses TF-IDF to convert text data into vector form.

Similarity Calculation: Cosine similarity is computed between the provided movie and all others in the dataset to identify similar movies.

Recommendations Output: The system returns the top 10 most similar movies, along with their posters from the TMDB API.

Technologies Used:

Programming Language: Python

Libraries:

Pandas: Data manipulation

NumPy: Numerical operations

Scikit-Learn: Machine learning, including TF-IDF and cosine similarity

Requests: API requests to TMDB for movie posters

API: The Movie Database (TMDB) API

Conclusion:

The Movie Recommender System is a solid proof of concept that leverages content-based filtering techniques to provide movie recommendations. It successfully uses movie metadata and textual content to generate relevant suggestions. The project demonstrates the potential of machine learning algorithms like TF-IDF and cosine similarity in practical applications. With future enhancements, this system could be extended to provide personalized recommendations and be integrated into larger platforms.
