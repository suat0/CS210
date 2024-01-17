# CS210 Project Repository

## Overview

Welcome to the CS210 Project Repository, an insightful journey into personal preferences in movies and music using data analytics. This project harnesses the power of data from two popular platforms, IMDb and Spotify, to delve into the nuances of individual taste in entertainment.

### Data Acquisition and Analysis

#### IMDb Data:
- **Method**: Web scraping with Python's Selenium and BeautifulSoup.
- **Process**:
  - Automated login using Chrome webdriver.
  - Scraping personal ratings, movie titles, directors, genres, and other pertinent data.
  - Merging scraped data with additional details like IMDb ratings, duration, and release year.
  - Note: Some data inconsistencies were addressed, such as missing IMDb ratings for shows with non-English titles.

#### Spotify Data:
- **Method**: Utilizing the Spotify API.
- **Challenge**: Songs lack genre data; resolved by extracting genres using artist IDs.

### Machine Learning Application
- **Model**: Random Forest Tree.
- **Training**: 80% of personal movie ratings.
- **Testing**: Remaining 20%.
- **Application**: Predicting ratings for a personal watchlist.
- **Unique Approach**: Analyzing Spotify data for genre preferences.

### Objectives and Insights
- **Primary Goal**: To understand and analyze personal trends and preferences in movies and music.
- **Key Findings**:
  - Dominant movie genre preference: Drama, amongst a diverse range.
  - Rating behavior: Tendency to rate movies lower than their average IMDb scores.
  - Music preferences: Strong inclination towards rock music, with morning listening habits.
<img width="582" alt="image" src="https://github.com/suat0/CS210/assets/105522910/2c9500a0-d33b-45f2-8858-a6a95c72b3c0">

<img width="516" alt="image" src="https://github.com/suat0/CS210/assets/105522910/ab24ffd9-cf10-4dba-ae53-a2441450024a">

<img width="556" alt="image" src="https://github.com/suat0/CS210/assets/105522910/22843e8f-a616-40e5-9b2b-44526b37c8f8">

<img width="464" alt="image" src="https://github.com/suat0/CS210/assets/105522910/e1aa5631-05eb-4f75-9790-95c9148b3674">

### Statistical Analysis
- **Null Hypothesis**: I watch and listen diverse genres.
- **Diversity in Taste**: Explored through 66 unique movie genres and 83 music genres.
- **Statistical Test**: P-value of 0.23134171389514172 indicates a significant diversity in taste when considering a 0.05 significance level.

### Visual Representations
- Graphs and charts illustrating the distribution of ratings, genre preferences, and more, providing a visual narrative of the findings.

### Usage Guidelines
- **Execution**: The provided Jupyter Notebook is structured for step-by-step execution.
- **Dependencies**: Ensure all necessary libraries (selenium, matplotlib, numpy, pandas, sklearn, seaborn) are installed.

### About the Author
Suat Emre Karabıçak

### Additional Resources
- **Presentation Video**: Access the project presentation video [here](https://drive.google.com/drive/folders/1xkIP7TTlolK6VJtu_ZkYwXAZz2D0a5RQ?usp=share_link).

