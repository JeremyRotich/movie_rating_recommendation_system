Dataset Overview

This project uses the MovieLens Latest Small Dataset, a publicly available dataset developed by the GroupLens Research Group at the University of Minnesota. The dataset contains movie ratings and tags collected from MovieLens users and is commonly used for recommendation system development and evaluation.

Dataset Statistics
Metric	Value
Users	610
Movies	9,742
Ratings	100,836
Tags	3,683
Rating Scale	0.5 – 5.0 Stars
Time Period	March 1996 – September 2018
Dataset Files Used
File	Description
ratings.csv	User ratings for movies
movies.csv	Movie titles and genres
tags.csv	User-generated movie tags
links.csv	Links to IMDb and TMDb movie identifiers
Key Features

ratings.csv

Column	Description
userId	Unique user identifier
movieId	Unique movie identifier
rating	Movie rating given by a user
timestamp	Time when the rating was submitted

movies.csv

Column	Description
movieId	Unique movie identifier
title	Movie title
genres	Movie genre categories
Data Preparation

The following preprocessing steps were performed:

Loaded movie and rating datasets using Pandas.
Checked for missing and duplicate values.
Merged ratings and movie information using movieId.
Converted timestamps into readable date formats where necessary.
Created a user-movie rating matrix for recommendation modeling.
Filtered movies with very few ratings to improve recommendation quality.
Dataset Source

The dataset is publicly available from the GroupLens Research Group:

MovieLens Dataset Repository

Citation

Harper, F. M., & Konstan, J. A. (2015). The MovieLens Datasets: History and Context. ACM Transactions on Interactive Intelligent Systems, 5(4), 19:1–19:19.