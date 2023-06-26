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

Here are bar graphs depicting the return on investment in relation to movie genres, directors associated with the horror genre, and studios associated with the top 4 movie genres, respectively.


![image](https://github.com/xuqc01/movie-data-analysis/assets/38637431/b6a80545-b200-4ca8-8014-13463a5ead68)

The top 5 movie genres of all time are horror, thriller, mystery, documentary, and music with horror generating the largest return on investment of 14.5. 

![image](https://github.com/xuqc01/movie-data-analysis/assets/38637431/1f080dfb-e54b-49a6-9fce-be841f45aa84)

Chris Lofing dominates the horror genre with the largest return on investment of 425. Be aware, as his ROI is extremely large due to his one-hit-wonder movie the Gallows which generated over 40 million dollars with only a budget of $100,000. If you are unconfindent in selecting him as your main director for the horror genre, you can simply select the directors following him in ROI as they all generate a relatively high return. 

![image](https://github.com/xuqc01/movie-data-analysis/assets/38637431/a64f070d-7f38-4023-bc7e-5f7634617c27)

Warner Bros Pictures generates the most ROI across horror, thriller, and mystery films. Sony Pictures generates the largest ROI in music films.


## Conclusions

-**Horror movies are the best genre**: Horror movies are the best movies to produce for a start up movie company because they generate the largest ROI as a result of their extremely low budget costs. Of the horror genre,  the best directors to select range from Chris Lofing, William Brent Bell, Tod Williams, Bradley Parker, and Ariel Schulman. 

-**Consider movie budget alone**: Although it may seem obvious to select a movie characteristic that generates the largest return on investment, the budgets of these movies may not be affordable, therefore, our movie studio would be unable to achieve such a large return. On the other hand, don't be afraid to spend money because for every $1 spent will return over $3 in revenue on average. 

-**Select Warner Bros**: Our movie company should select Warner Bros Pictures as the supporting studio because they generate the largest ROI in terms of horror films. 

## Future Insights

-**Consider actors/actresses**: Actors and actresses may be the reason why a specific genre or movie generates a large ROI. It's important to account for all factors associated with return and their effects on one another.

-**Expand to streaming services**: In the modern day, an abundant of movies are exclusively found on online streaming platforms rather than movie theatres so it's extremely important to consider this outlet as another form of revenue growth. 
