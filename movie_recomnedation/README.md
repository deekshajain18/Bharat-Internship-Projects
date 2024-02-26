# Movie Recommendation System using Collaborative Filtering

This repository contains Python code for building a movie recommendation system using collaborative filtering techniques. Collaborative filtering is a method used for making automatic predictions (filtering) about the interests of a user by collecting preferences from many users (collaborating).

## Dataset
The dataset used in this project consists of movie ratings provided by users. It includes the following columns:

user_id: Unique identifier for each user.
item_id: Unique identifier for each movie/item.
rating: Rating given by the user for a particular movie.
timestamp: Timestamp indicating when the rating was provided.
The dataset is loaded from a TSV file (m_id.tsv) and merged with another dataset (Movie_Id_Titles.csv) containing movie titles.

Exploratory Data Analysis (EDA)
The EDA includes the following steps:

Calculating the mean rating and count of ratings for each movie.
Visualizing the distribution of the number of ratings and the ratings themselves using histograms.
Building the Recommendation System
The recommendation system is built using collaborative filtering:

Constructing a user-item matrix where rows represent users, columns represent movies, and each cell contains the rating given by the user to the movie.
Finding similar movies based on user ratings using correlation.
Generating recommendations for a given movie (e.g., "Star Wars (1977)") by identifying movies with high correlation to it.
Usage
Ensure you have Python and the necessary libraries installed (e.g., pandas, matplotlib, seaborn).
Clone this repository.
Run the provided Python script (movie_recommendation.py) to execute the recommendation system.
Explore the generated recommendations and insights.
Results
The results include lists of similar movies for selected titles such as "Star Wars (1977)" and "Liar Liar (1997)" based on user ratings and correlation.

Conclusion
Collaborative filtering provides a powerful method for generating personalized recommendations based on user preferences. This project demonstrates how to implement such a system using Python and pandas, offering insights into movie recommendations for users.
