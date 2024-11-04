# Vallarit_Python-Exploratory-Data-Analysis-on-Spotify-2023-Dataset
Python - Exploratory Data Analysis on Spotify 2023 Dataset

In this deliverable, you will perform an exploratory data analysis (EDA) on a dataset containing information about popular tracks on Most Streamed Spotify Songs 2023 (https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023Links to an external site.). This task aims to analyze, visualize, and interpret the data to extract meaningful insights.

# GENERAL GUIDELINES:

1. Begin by familiarizing yourself with the structure of the dataset. Check for missing values and data types, and perform an initial exploration to understand the different features available.
2. Provide summary statistics to give an overview of key metrics such as the number of streams, release dates, and musical attributes (e.g., BPM, danceability).
3. Use appropriate visualizations (e.g., bar charts, histograms, scatter plots) to uncover trends and patterns in the data. Ensure that your plots are well-labeled and easy to interpret.
4. Investigate correlations between different variables and provide insights based on your findings. Explore relationships between streams and other musical characteristics like tempo, energy, or playlists.
5. Based on your analysis, offer any insights or recommendations regarding the tracks, artists, or musical trends that could be useful for understanding what makes a track popular.

# GUIDE QUESTIONS:
You are expected to answer the following questions using your analysis:

## Overview of Dataset
- How many rows and columns does the dataset contain?
- What are the data types of each column? Are there any missing values?

#### Explanation:
- There are 953 rows and 23 columns in total for the dataset.
- The data types of each column are a combination of strings and integers. The track_name, artist(s)_name, key and mode are strings, the rest are integers. There are some missing values in some columns of the dataset, like the shazam charts, deezer charts, and the key columns.

## Basic Descriptive Statistics
- What are the mean, median, and standard deviation of the streams column?
- What is the distribution of released_year and artist_count? Are there any noticeable trends or outliers?

#### Explanation:
- The mean, median, and standard deviation of the streams column are:
  - Mean: 514137424.93907565
  - Median: 290530915.0
  - Standard Deviation: 566856949.0388832
#### Explanation (Distribution of Released Year):
  - For the distribution of the released year, the outliers here can be the fact that back in the 20th century, before the popularization of digital streaming services, there weren't any means of acquiring music tracks through the use of the internet or digitally, only through physical means such as vinyl, cd, radios, television, and other forms of medium for music before the 21st century. Compared to newer releases of music, they have become more popular since they are much more accessible through online means, such as through digital streaming services or platforms, as seen in the abrupt rise of music in 2020.
![image](https://github.com/user-attachments/assets/16476ac0-8c29-40df-a0dd-1e854eeb3ba1)

#### Explanation (Distribution of Artist Count):
  - The distribution of the artist count above indicates the number of artists that produced music, we can see the trend that single artists made more distributions than collaborating artists, meaning the outliers here are the few tracks with a high number of artists producing in those tracks indicate that it may be special projects or collaborations.
![image](https://github.com/user-attachments/assets/67b89a68-b537-4d25-8117-23cfffdc2ec6)


## Top Performers
- Which track has the highest number of streams? Display the top 5 most streamed tracks.
- Who are the top 5 most frequent artists based on the number of tracks in the dataset?

#### Explanation:
- The track with the highest number of streams comes from The Weeknd's "Blinding Lights" with 3.703895e+09 listens (3.7 Billion+ listens)
![image](https://github.com/user-attachments/assets/e888ede4-d01e-488a-8cf9-2b04056b3324)

- Based on the number of tracks in the dataset, the top 5 most frequent artists are Taylor Swift, The Weeknd, SZA, Bad Bunny, and Harry Styles.

![image](https://github.com/user-attachments/assets/2b636053-2df5-48c4-ba2b-9b7130ebc9ee)
## Temporal Trends
- Analyze the trends in the number of tracks released over time. Plot the number of tracks released per year.
- Does the number of tracks released per month follow any noticeable patterns? Which month sees the most releases?

#### Explanation (Number of tracks yearly)
  - In 2022, the year with the highest number of tracks released. The possible cause of this is the steady recovery due to the COVID-19 Pandemic, meaning more artists have the chance to resume producing music tracks in music studios, this can also be attributed to the fact that digital streaming platforms are becoming popular, especially with TikTok and YouTube have promoted dance video trends with corresponding tracks that are part of the 2022 trends.
![image](https://github.com/user-attachments/assets/a091a79b-b339-4e10-bb9a-5f8a48601bef)


#### Explanation (Number of tracks monthly)
  - January and May have the most tracks released. January can be attributed to the fact that it is a new year, and after the holiday break. This means that listeners look for more music and are intrigued by the fact that possibly new, innovative music can be released and be pleasing to their ears, and also the fact that the music tracks aren't as saturated as compared to later on the year. May is sometime during the summer, meaning a lot of people have time on their hands to listen to other music.
![image](https://github.com/user-attachments/assets/403d2d45-e4eb-469a-a1e1-44d6483045f8)


## Genre and Music Characteristics
- Examine the correlation between streams and musical attributes like bpm, danceability_%, and energy_%. Which attributes seem to influence streams the most?
- Is there a correlation between danceability_% and energy_%? How about valence_% and acousticness_%?

## Platform Popularity
- How do the numbers of tracks in spotify_playlists, spotify_charts, and apple_playlists compare? Which platform seems to favor the most popular tracks?

## Advanced Analysis
- Based on the streams data, can you identify any patterns among tracks with the same key or mode (Major vs. Minor)?
- Do certain genres or artists consistently appear in more playlists or charts? Perform an analysis to compare the most frequently appearing artists in playlists or charts.
