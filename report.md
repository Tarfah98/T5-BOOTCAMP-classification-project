# Netflix Awarded Movies/Series Classification Model
By: Rawabi Alharbi, Tarfah Alabbad

## Abstract
The main goal of this project is to create a classification model on Netflix movies and series to predict weather this movie or series is awarded or not.

## Design
The data provided by kaggle has the main information about movies and series on Netflix such as the title, run time, IMDb votes then we cleaned the data and preform EDA to visually present the data, preprocessing then modeling and evaluating the best model with F1 score as our metric.

## Data
In this project we used the data from kaggle on https://www.kaggle.com/ashishgup/netflix-rotten-tomatoes-metacritic-imdb?select=netflix-rotten-tomatoes-metacritic-imdb.csv  it contains 15431 rows with 29 columns.

## Algorithms
we’ve done the data cleaning and removing the nulls and we did some feature engineering by creating new columns, also we transformed the categorical features into label encoder then we split our data and created our baseline model witch was KNN then we wanted to improve the model, we used decision trees and random forest and xgboosted classifier and ensemble stacking and we found that random forest has the best F1 score since it’s our chosen metric because we want to find the tradeoff between recall and precession, then we deployed our model using flask.


## Tools
- Python and Jupyter Notebook
- Numpy and Pandas for data manipulation
- Matplotlib, Seaborn and Tableau for visuializations
- Sklearn for ML algorithms
- HTML/CSS and Flask for the web app

## Communication
In addition to the slides and visuals presented, I will be sharing my work on my github account
* https://github.com/Tarfah98
* https://github.com/RawabiKhalaf
