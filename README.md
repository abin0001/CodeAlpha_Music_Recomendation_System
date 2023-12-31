# Music Recommendation System

This project implements a music recommendation system using machine learning and data from Spotify. It suggests songs based on user-provided tracks and their audio features.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Data Collection](#data-collection)
- [Data Preprocessing](#data-preprocessing)
- [Clustering](#clustering)
- [Song Embedding](#song-embedding)
- [Spotify API](#spotify-api)
- [Recommendation Function](#recommendation-function)
- [How to Use](#how-to-use)
- [License](#license)

## Introduction

Music recommendation systems have become an essential part of music streaming platforms. This project focuses on building a recommendation system that suggests songs based on the characteristics of the provided songs.

## Requirements

To run this project, you will need the following libraries and tools:

- pandas
- scikit-learn
- spotipy (Python library for the Spotify API)
- NumPy
- matplotlib
- Spotify Developer Account (to access the Spotify API)

You can install most of these libraries using pip:

```bash
pip install pandas scikit-learn spotipy numpy matplotlib
```

Additionally, you'll need to obtain your own Spotify Developer credentials (Client ID and Client Secret) to use the Spotify API.

## Data Collection

The project uses song data from Spotify, including audio features and track details. It combines local and Spotify datasets for a broader recommendation system.

## Data Preprocessing

Data preprocessing includes feature scaling and selecting relevant audio features for clustering and recommendation.

## Clustering

The songs are clustered into groups using K-Means clustering, and the clusters are visualized in 2D space using t-SNE.

## Song Embedding

Principal Component Analysis (PCA) is applied to embed songs into 2D space for recommendation.

## Spotify API

The project accesses the Spotify API to fetch additional data for song recommendation.

## Recommendation Function

The recommendation function takes a list of songs and suggests similar tracks based on their audio features and characteristics.

## How to Use

To use this recommendation system, you can provide a list of songs, and it will suggest tracks that are similar in terms of audio features and characteristics.

Make sure to replace your Spotify Developer credentials (Client ID and Client Secret) in the code to access the Spotify API.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
