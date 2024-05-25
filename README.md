# Spotify Data Mining

## Introduction

The Spotify Data Mining project explores audio features data collected from Spotify for songs released between 1960 and 2020. The goal is to gain insights into what makes a "hit" song and how the characteristics of hits have evolved over time. This analysis could benefit artists and record labels in understanding trends and making informed decisions.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Data](#data)
- [Analysis](#analysis)
- [Results](#results)
- [Discussion](#discussion)
- [References](#references)

## Project Structure

    - SotifyDataMining.ipynb: Jupyter notebooks used for exploratory data analysis.
    - SpotifyData.pdf: Analysis of trends found through data mining
    - README.md: This README file.

## Data

The dataset contains various audio features of songs such as:

- Acousticness: Measures whether the track is acoustic.
- Danceability: Describes how suitable a track is for dancing based on tempo, rhythm stability, beat strength, and overall regularity.
- Instrumentalness: Predicts whether a track contains no vocals.
- Key: Indicates the key the track is in.
- Liveness: Detects the presence of an audience in the recording.
- Loudness: Overall loudness of a track in decibels.
- Mode: Indicates the modality (major or minor) of a track.
- Speechiness: Detects the presence of spoken words in a track.
- Tempo: Overall estimated tempo of a track in beats per minute.
- Time Signature: Notational convention to specify how many beats are in each bar.
- Valence: Measures the musical positiveness conveyed by a track.

## Analysis

The analysis is divided into several key questions:

    How do audio features change over time?
        Descriptive statistics and visualization of trends over the years.

    Can we find different genres by clustering?
        K-means clustering based on time signatures and audio features.

    Can we see what audio features imply a hit?
        Association rules to identify combinations of features that correlate with hit songs.

    Which audio features have the highest impact on being a hit?
        Logistic Regression and Naive Bayes Classifier to predict hits.

## Results
Descriptive Statistics:

- Box plots and other visualizations show the changes in audio features over time.
Clustering

- K-means clustering reveals patterns in audio features that correspond to different time signatures and possible genres.
Association Rules

- Association rules identify combinations of features that are commonly found in hit songs.
Predictive Models

- Logistic Regression and Naive Bayes Classifier models provide insights into which features have the most significant impact on a song becoming a hit.
Discussion

The analysis reveals that certain features such as danceability, energy, valence, and tempo are critical in predicting hit songs. Clustering results indicate that some audio features are better predictors of genre than others. The predictive models show a high accuracy rate, making them useful tools for artists and record labels.
References

    Middlebrook, Kai, and Kian Sheik. “SONG HIT PREDICTION: Predicting Billboard Hits Using Spotify Data.” ArXiv, 2019.
    “Web API Reference: Spotify for Developers.” Spotify.
    Georgieva, Elena, et al. “Hitpredict: Predicting Hit Songs ... - cs229.Stanford.edu.” Stanford Computer Science 229: Machine Learning, 2018.

For more detailed information, please refer to the full documentation and analysis notebooks included in the project repository.
