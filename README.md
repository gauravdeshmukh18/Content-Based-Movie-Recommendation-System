# Content-Based-Movie-Recommendation-System
Content Based Movie Recommendation System using Machine Learning(Scikit-Learn)
https://github.com/gauravdeshmukh18/Content-Based-Movie-Recommendation-System/blob/main/Readme/Movie.gif?raw=true

## Overview:
We are going to build a model that takes a movie title as an input and output a list of the 5 most similar movies. Firstly, for this we need a mechanism to identify the index of a movie in our metadata DataFrame, given its title.

It turns out that there are (mostly) three ways to build a recommendation engine:

1. Popularity based recommendation engine.
2. Content based recommendation engine.
3. Collaborative filtering based recommendation engine.

But we are going to implement a Content based recommendation system using the scikit-learn library.

## Popular Movies:
![image](https://user-images.githubusercontent.com/103682825/176397333-150fae88-0547-4e07-88ec-817b76eb0e0a.png)

## What is Cosine Similarity and How does it work?
Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space.

It is a numerical value, ranges between 0 to 1 which helps to determine how much two items are similar or close to each other on a scale of 0 to 1. This similarity score is obtained by measuring the similarity between the text details of both of the items.
 ![image](https://user-images.githubusercontent.com/103682825/176416345-5dcc05f6-18c3-4540-ba64-6c079a0f480c.png)

## Conclusion:
In this movie recommendation system, we build a recommender model while taking the inputs of the user and recommended 5 similar movies.
