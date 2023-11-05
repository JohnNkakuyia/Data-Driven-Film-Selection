# Phase 1 Project

# Data-Driven Film Selection for Microsoft's Movie Studio

![title](https://github.com/JohnNkakuyia/Data-Driven-Film-Selection/blob/main/images/microsoft.jpg)

## Overview

This project revolves around leveraging data and analytics of the data link, to identify the most profitable film genres, which will enable Microsoft to strategically position its new movie studio for success in the highly competitive film industry.

## Business Problem Statement:

The objective is to leverage this research to provide actionable insights to the leadership of Microsoft's new movie studio, so that they may make informed decisions regarding the selection of film genres for production.


### The Data

In the folder `zippedData` are movie datasets from:

* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)

used data files:
* imdb.title.basics
* imdb.title.ratings
* bom.movie_gross

  ## Methods
  This project uses descriptive analysis, including description to show the relation on movie genres' popularity and gross income. This can help in making profitable choices and build a positive reputation.
  
  ![average_domestic_rating](https://github.com/JohnNkakuyia/Data-Driven-Film-Selection/blob/main/images/average_domestic_rating.png)

  ## Results
  correlation matrix gives a clear insight that most of the genres are in high demand and yet the domestic gross is quite down

  ![corelation_matrix](https://github.com/JohnNkakuyia/Data-Driven-Film-Selection/blob/main/images/corelation_matrix.jpg)

  combinations of genres that have both high ratings and high gross, as these may be more lucrative.

![domestic_gross](https://github.com/JohnNkakuyia/Data-Driven-Film-Selection/blob/main/images/domestic_gross.jpg)

## Conclusions

This analysis leads to three recommendations for a profitable movie selection

* **Genre Popularity:**  Consider producing movies in highly-rated genres to build a positive reputation.
* **Financial Success:** Examine  genres that generate the highest domestic gross. This can help in making profitable choices.
* **Genre Combinations:** Explore combinations of genres that have both high ratings and high gross, as these may be more lucrative.

### Next Steps

Further analyses could yield additional insights into what will happen in the near future and predict some other factors for movie business success

Here is the [jupyter Notebook](http://localhost:8888/notebooks/Data-Driven%20Film%20Selection%20for%20Microsoft's%20Movie%20Studio.ipynb) and [presentation.pdf](https://github.com/JohnNkakuyia/Data-Driven-Film-Selection/blob/main/presentation.pdf.pdf)link
