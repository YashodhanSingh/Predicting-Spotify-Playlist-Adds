# Predicting Spotify Playlist Adds
This project was part of my final capstone project for the [General Assembly Data Science Bootcamp](https://generalassemb.ly/education/data-science/new-york-city) in New York City. 

## Project Description
The main purpose of this project is to demonstrate the skills that I have gained through the GA bootcamp - from data extraction, analysis, to predictive modeling. As my interest lies in music and tech, I wanted to get a better sense of my listening behavior on Spotify. 

Utilizing [Spotipy](https://spotipy.readthedocs.io/en/2.9.0/), I extracted my entire playlist library and it's associated features, as well as my friend's library to compare music tastes. After exploring the relationship between audio features of myself and my friend's music (genre, popularity, liveness, valence, etc), I preprocessed the data and built a supervised machine learning model using Random Forest Classification and Logistic Regression - two popular binary classification algorithms. In essense, the model predicts whether an unheard song will be added to either mine or my friend's playlist. The final product ([spotify.pkl](https://github.com/taku-takamatsu/Predicting-Spotify-Playlist-Adds/blob/master/spotify.pkl)) is a serialized version of my pipeline - which predicted my testing data with 90.7% accuracy.

## Notebooks
The files are split into four main directories. 
1. Script to scrape Spotify: [spotify_api_access.py](https://github.com/taku-takamatsu/Predicting-Spotify-Playlist-Adds/blob/master/spotify_api_access.py)
2. Part 1 - [Data Collection](https://github.com/taku-takamatsu/Predicting-Spotify-Playlist-Adds/blob/master/Part%201%20-%20Data%20Collection.ipynb)
3. Part 2 - [Exploratory Data Analysis](https://github.com/taku-takamatsu/Predicting-Spotify-Playlist-Adds/blob/master/Part%202%20-%20Exploratory%20Data%20Analysis.ipynb) (may take a minute to load)
4. Part 3 - [ML Modeling](https://github.com/taku-takamatsu/Predicting-Spotify-Playlist-Adds/blob/master/Part%203%20-%20Modeling.ipynb) (may take a minute to load)

## Contact
* Taku's [LinkedIn](https://www.linkedin.com/in/taku-takamatsu/)
