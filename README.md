# Spotify Dataset Exploratory Data Analysis (EDA)

This repository contains an exploratory data analysis of a Spotify dataset featuring 114,000 tracks across 125 different genres. The analysis includes data cleaning, feature engineering, data visualization, and hypothesis testing to uncover insights about track attributes and their relationships with popularity and other factors.

## Dataset Overview

The dataset comprises various attributes of Spotify tracks, including:

- `track_id`: Spotify ID for the track
- `artists`: Names of the artists
- `album_name`: Name of the album
- `track_name`: Name of the track
- `popularity`: Popularity score between 0 and 100
- `duration_ms`: Track length in milliseconds
- `explicit`: Whether the track has explicit lyrics
- `danceability`, `energy`, `key`, `loudness`, `mode`, `speechiness`, `acousticness`, `instrumentalness`, `liveness`, `valence`, `tempo`, `time_signature`: Various musical and vocal characteristics
- `track_genre`: Genre of the track

## Project Structure

- `Data_Cleaning.ipynb`: Jupyter notebook for data cleaning processes including handling duplicates, missing values, and outliers.
- `Data_Visualization.ipynb`: Visualizations such as histograms, bar charts, and correlation matrices to understand data distributions and relationships.
- `Hypothesis_Testing.ipynb`: Notebook containing hypothesis tests conducted to validate assumptions about the data.

## Key Insights

- Songs with higher acousticness tend to have more energy.
- Positive or upbeat tracks (high valence) correlate strongly with danceability.
- Explicitness does not significantly affect a song's popularity.
- Most modern songs have a duration exceeding three minutes.

## Hypothesis Testing

We conducted several hypothesis tests, including:
1. Testing if the duration of most songs exceeds 3000 milliseconds.
2. Examining the probability of selecting an explicit song.
3. Analyzing the relationship between song duration and its popularity.

## Visualization Highlights

- **Song Tempo Distribution**: Histograms showing the distribution of song tempos.
- **Popularity Analysis**: Bar charts comparing the popularity of explicit vs. non-explicit songs.
- **Feature Relationships**: Correlation matrices to explore relationships between different attributes.

## Future Work

Further analysis could include:
- Employing machine learning techniques to predict song popularity based on attributes.
- Extensive data modeling to identify deeper insights and patterns.


