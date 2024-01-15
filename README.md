# CS210

## Overview

Welcome to the CS210 Project Repository! In this project, I analyzed my IMDb ratings and Spotify data. Moreover, I tried to examine whether my movie taste and my music taste is diverse. At the end, I trained a machine learning model to predict my Watchlist that I scraped from IMDb website.


### Overview
In the web scraping phase, data is extracted from IMDb. This involves using advanced web scraping techniques to navigate through IMDb's pages and gather essential data, such as movie titles, genres, ratings, and more.

### Tools and Techniques

I used Selenium and BeautifulSoup libraries of Python to get my ratings. Initially, I created a Chrome webdriver. Then I redirected the driver to login page and send the keys for my account. Once I logged in driver get the page that contains my ratings. Before I write the HTML contents of the website to a file, there was a button to export your ratings data. However, it doesn't contain the stars information. Therefore, I scraped the stars, directors, title, genres, my ratings and votes myself. Then I merged that csv file with my dataframe to get the IMDb rating, duration and year because these informations cannot be scraped from that HTMLs. 

For my Spotify data, I used Spotify API.

As a machine learning model, I trained random forest tree. I used %80 of my ratings to train the model, and %20 of them to test the model. Then I gave my watchlist for model to predict my ratings. 

### Key Aspects
The IMDb rating of some shows couldn't be find from the csv file, because csv file contains the original name of those shows not the english name. Therefore, I dropped the IMDb ratings of those. 

In Spotify, songs do not have genres. Therefore, I used artists' ids to find the genres of my top tracks.

### Objective
The goal here is to analyze various movie genres to understand trends, preferences and do the same for the spotify data to observe the diversity of genres of both my movie taste and my music taste.

### Findings

My Hypothesis was that I have a diverse taste in musics and movies. I turns out that even though I like to watch a specific genre (Drama) more than others, I have watched 66 unique genres. Same goes for my music taste. I usually listen rock music but in general I have listened 83 unique genres. 

<img width="828" alt="image" src="https://github.com/suat0/CS210/assets/105522910/60601819-5a53-4ecf-9978-a34e691d6a90">

<img width="392" alt="Screenshot 2024-01-16 at 00 16 59" src="https://github.com/suat0/CS210/assets/105522910/9f4c9625-c161-4112-a04e-2250ef89e5cc">

### Usage

This Jupyter Notebook can be run cell-by-cell to reproduce the analyses. Ensure all dependencies are installed and data sources are correctly linked before executing the cells.

### Dependencies

All the dependencies are included in the beginning of the ipynb. (selenium, matplotlib, numpy, pandas, sklearn, seaborn)

### Conclusion

In conclusion, I found interesting things about my habits and my taste. Also p-value of the movie genres and music genres is 0.23134171389514172. Therefore, if I accept 0.05 as my significance level, I cannot falsify my null hypothesis.

<img width="249" alt="Screenshot 2024-01-16 at 00 36 24" src="https://github.com/suat0/CS210/assets/105522910/04aefee4-7a57-4522-890b-2bd8e1d2c9bf">

### Author

Suat Emre Karabıçak
