# MovieRecommendation

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MarijaStanojcic/MovieRecommendation/master)

This is my first project learning about recommendation systems. Currently, there are some simple algorithms for popularity model, user similarity and item similarity model. This is still work in progress.

The data is downloaded from the https://grouplens.org/datasets/movielens/1m/

These files contain 1,000,209 anonymous ratings of 3,706 movies made by 6,040 MovieLens users who joined MovieLens in 2000.

There are three recommendation models. 

1. Popularity model

  All users get the same recommendation of most popular movie. To determine what is the popularity score of the movie, Weighted Rating score formula from IMDb was used.
  There is a function for users to search movies for a specific genre and year/years of relase.


2. User-user Colaborative filtering 

  Similarity between users is calculated using cosine similarity. Most popular movies from k most similar users are recommended. 

3. Item-item Colaborative filtering

  Similarity between items is calculated using cosine  similarity. K most similar movies are recommended.

Book used as a help for this project is Recommendation Systems with Python by Rounak Banik from Packt.

This article was also used https://www.analyticsvidhya.com/blog/2018/06/comprehensive-guide-recommendation-engine-python/.
