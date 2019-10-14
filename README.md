# Movies recommendation system

## Introduction

Recommendation systems use ratings
that users have given items to make specific recommendations to users.
Companies like Amazon that sell many products to many customers
and permit these customers to rate their products
are able to collect massive data sets that
can be used to predict what rating a given user will give a specific item. Items for which a high rating is predicted for specific users
are then recommended to that user.  

Netflix uses recommendation systems to predict how many stars
a user will give a specific movie.  

Unfortunately, the Netflix data is not publicly available.
But the GroupLens research lab generated their own database
with over 20 million ratings for over 27,000 movies
by more than 138,000 users. This project will explore data set such as movie, genre, user rating and using machine learning model to create a movie recommendation system.  

## Content
A movie recommendation system is based on using the MovieLens dataset (free data that you can find on https://grouplens.org/datasets/movielens/latest/). 


Movie rating predictions will be compared and evaluated to the true ratings in the validation set using the residual mean squared error (RMSE) on a test set. We define ![yui](https://latex.codecogs.com/gif.latex?%5Cinline%20y_%7Bu%2Ci%7D) as the rating for movie ![i](https://latex.codecogs.com/gif.latex?%5Cinline%20i) by user ![u](https://latex.codecogs.com/gif.latex?%5Cinline%20u) and denote our prediction with ![hatY_{u,i}](https://latex.codecogs.com/gif.latex?%5Cinline%20%5Chat%7By%7D_%7Bu%2Ci%7D). The RMSE is then defined as:      

![](https://latex.codecogs.com/gif.latex?%5Cdpi%7B120%7D%20%5Cmbox%7BRMSE%7D%20%3D%20%5Csqrt%7B%5Cfrac%7B1%7D%7BN%7D%5Csum_%7Bu%2Ci%7D%5E%7BN%7D%28%5Chat%7By%7D_%7Bu%2Ci%7D%20-y_%7Bu%2Ci%7D%29%5E2%7D)

The project composed 2 files: a report in .md format and R script that that generates predicted movie ratings and calculates RMSE. 

**Walk-Through**


## Reference

Movie Data set can be found on https://grouplens.org/datasets/movielens/latest/)
