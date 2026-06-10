# Netflix Recommendation Engine

## Overview
Customer behaviour and its prediction lie at the core of every business model.
Recommendation engines are the much-needed manifestations of the desired predictability of user activity.
Organizations like Netflix and Amazon analyze user activity patterns and suggest products that better suit user needs and choices.

This project creates a recommendation engine from the ground up, where every single user, based on their area of interest and ratings, receives a recommended list of movies best suited for them.

## Objectives
* Find out the list of the most popular and liked genres.
* Create a model that finds the best-suited movie for one user in every genre.
* Find what genre movies have received the best and worst ratings based on user ratings.

## Dataset Information
* **ID:** Contains separate keys for customers and movies.
* **Rating:** A section containing user ratings for all the movies.
* **Genre:** Highlights the category of the movie.
* **Movie Name:** Name of the movie with respect to the movie ID.

## Technologies Used
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Surprise
* **Model:** Singular Value Decomposition (SVD) for Collaborative Filtering

## Getting Started
1. Clone this repository to your local environment.
2. Install the necessary dependencies by running: 
   `pip install pandas numpy matplotlib seaborn scikit-surprise`
3. Open `Netflix_Project.ipynb` in Jupyter Notebook or Google Colab.
4. Run the cells sequentially to process the data, train the SVD model, and generate personalized movie recommendations.
