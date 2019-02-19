# Movie Recommender System
Using the [datasets](https://github.com/warriorkitty/orientlens/tree/master/movielens) colleccted from the Movielens [website](http://movielens.org), we construct a function that take the user index as input and prints out titles to 10 movies that users like them have watched but they haven't.

## Cosine Similarity
We consider each user as a vector with dimension = #no of movies, and the value at a coordinate = rating of the respective movie. The cosine similarity between 2 users is defined as the cosine of the angle between their 2 vectors.

## Likeness Score
Calculated for each user and movie as a sum of ratings weighted by user similarity.
We rank the movies based on this score.
