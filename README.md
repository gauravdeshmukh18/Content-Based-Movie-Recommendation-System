# Content-Based-Movie-Recommendation-System
Content Based Movie Recommendation System using Machine Learning(Scikit-Learn)

## Overview
We are going to build a model that takes a movie title as an input and output a list of the 5 most similar movies. Firstly, for this we need a mechanism to identify the index of a movie in our metadata DataFrame, given its title.

It turns out that there are (mostly) three ways to build a recommendation engine:

1. Popularity based recommendation engine.
2. Content based recommendation engine.
3. Collaborative filtering based recommendation engine.

But we are going to implement a Content based recommendation system using the scikit-learn library.

## Popular Movies

