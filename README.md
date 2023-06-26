# Movie-Data-Analysis

**Authors**: Steven Hui, Jimmy Mclaughlin, Justin Phan

## Overview

We conducted exploratory data analysis on movie data from Box Office Mojo, IMDB, Rotten Tomatoes, TheMovieDB, and The Numbers to recommened movie genres that are the best for our business stakeholders who are just taking part of the movie industry.

## Business Situation

Our team has decided to create a new movie studio to take part in the recent growth of the movie industry. Before doing so, we analyzed past movie data to determine the most profitable genres, studios, and directors and the potential risks associated with them. 

## Data Information

Movie data was taken from Box Office Mojo, IMDB, Rotten Tomatoes, TheMovieDB, and the Numbers. The file formats were of csv files except IMDB which was a sql database file. These files included, but were not limited to, the title, release date, budget, revenue, and genre of thousands of movies. 

## Methods

First, we created a new column for each database that concatanated the title and release of each movie. Movie titles alone couldn't have been used as the primary key merger because of duplicate names. The merging process naturally stripped the data of many rows because all the databases consisted of a very limited subset of movies that were the same. The dataset was stripped further during the actual data cleaning process. We removed movies that had no information on budget, revenue, release date, studio, genre, or director information. The final data set roughly had 1,100 rows which was filtered down from a few tens of thousands rows. We then grouped movies based on a few categories: movie genre, affiliated director, and production studio.

We proposed a few reommendations for creating a start-up movie company. These recommendations were based on the movies grouped by their movie genre, affiliated director, and producted studio which were then ranked by their respective return on investments. 

## Results

![image](https://github.com/xuqc01/movie-data-analysis/assets/38637431/88d1dc56-f804-4c7c-9b4a-c62f8f201d9b)

![image](https://github.com/xuqc01/movie-data-analysis/assets/38637431/b6a80545-b200-4ca8-8014-13463a5ead68)

![image](https://github.com/xuqc01/movie-data-analysis/assets/38637431/1f080dfb-e54b-49a6-9fce-be841f45aa84)

![image](https://github.com/xuqc01/movie-data-analysis/assets/38637431/a64f070d-7f38-4023-bc7e-5f7634617c27)




## Conclusions

