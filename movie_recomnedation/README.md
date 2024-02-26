# Movie Recommendation System

This repository contains code for a movie recommendation system using collaborative filtering techniques.

## Introduction

The movie recommendation system is built using Python and leverages the Pandas library for data manipulation and analysis. It utilizes collaborative filtering to recommend movies to users based on their ratings and similarities with other users.

## Dataset

The dataset used in this project consists of movie ratings provided by users. It includes information such as user ID, item ID (movie ID), rating, and timestamp.

The dataset is loaded from a TSV (Tab-Separated Values) file named `m_id.tsv`. Additionally, movie titles are loaded from a CSV file named `Movie_Id_Titles.csv`.

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/movie-recommendation-system.git
    ```

2. Navigate to the project directory:

    ```bash
    cd movie-recommendation-system
    ```

3. Install the required dependencies:

    ```bash
    pip install pandas matplotlib seaborn
    ```

4. Run the Jupyter notebook:

    ```bash
    jupyter notebook
    ```

5. Open the notebook `Movie_Recommendation_System.ipynb` and execute the cells to see the movie recommendations and analysis.

## Results

The system provides recommendations based on user ratings and identifies similar movies using correlation metrics. It also generates visualizations to analyze the distribution of ratings and the number of ratings per movie.


