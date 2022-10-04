# Phase 1 Project – Movie Analysis

## Overview
The purpose of this project was to discover which types of films are currently performing "the best" at the box office in order to inform a company attempting to enter into the film industry. For the purposes of this analysis, I take "the best" to mean those which are the most profitable, and thus made my deductions based on metrics of **net profit** and **Return on investment (ROI)**. I compared films in the database based upon the correlations between their afformentioned metrics and runtime, genre, actors, writers, and directors.

## Business Understanding
Which genres, writers, and directors are associated with the highest net profit and ROI?  More succinctly, which aspects of a film best predict it's profitability and success?

Both net profit and ROI are good markers of profitability, but ROI factors in cost more so than net profit. Thus, if cost/budget is not a concern, net profit is preferred over ROI and vice versa if budget is a concern.

The conclusions drawn from this analysis should prove beneficial to stakeholders entering into the film production industry, as well as veterans, in determining the characteristics of future films to create.

## Data
I utilized the *TMDB 5000 Movie Dataset* available on [kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata).
This database contains information about 5,000 relevant films'
- Title
- Profit
- Budget
- Genre
- Cast
- Crew
- Runtime

### Visualizations
![Correlations](https://user-images.githubusercontent.com/63984796/192377124-5c149d70-80a6-4604-b7f8-7af50d49e5c5.png)
![DirectorsWrites](https://user-images.githubusercontent.com/63984796/192377130-1040fff3-f9a1-445e-8eaf-539cbd83c426.png)
![genres](https://user-images.githubusercontent.com/63984796/192377131-8276313c-caeb-412e-8dbe-0454a6246ca6.png)


# Conclusion and Discussion of Limitations

Using the information from the previous cell in conjunction with those prior, I am able to make reccomendations about 4 potential films that would be highly profitable.

#### To Maximize Net Profit
The top two genres by net profit are Animation and Family. Grouping the top Writers and Directors by these genres, two potential movies are:
1. An **Animated** film *written* by **Timothy Harris** and *directed* by **Karey Kirkpatrick**.
2. A **Family** film *written* by **Herschel Weingrod** and *directed* by **Michael Apted**.

#### To Maximize ROI
The top two genres by ROI are Music and Horror. Grouping the top Writers and Directors by these genres, two potential movies are:
1. A **Musical** film *written* by **Jason Segel** and *directed* by **Robert Wise**.
2. A **Horror** film *written* by **Laura Lau** and *directed* by **Scott Derrickson**.

## Limitations
Several limitations were proposed by the data used in this process. One would of course be the sample size. While 5000 is large enough to draw statistical conclusions, more is always better; particularly when making conclusions about individuals involved. With more samples, it is unlikely the genre analysis would have changed, but it is possible that the analysis of successful writers, directors, and actors would have been different. Secondly, this database did not have data corresponding to the rating of the films. From several other online analyses with similar goals, It would seem that rating may be an important marker correlating with profitability. 
