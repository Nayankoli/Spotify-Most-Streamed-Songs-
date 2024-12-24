# Spotify-Most-Streamed-Songs-
# About Project - 
This file contains a detailed data dictionary for a Spotify Most Streamed Songs dataset, providing information on track details, streaming metrics across platforms, and musical attributes. It serves as a guide for analyzing trends in music popularity and composition.
This project not only explores the depths of 2023's chart-toppers but also leverages Python and the Spotify Web APIs.Here Python script is used that interacts with the Spotify Web API and a pandas DataFrame to retrieve track details including the cover URL for a list of tracks provided in an Excel file.Using a pandas DataFrame, we retrieve intricate track details, from beats and danceability to album cover In this project, we meticulously calculate average streams per year, dissect streams by track and artist names, and analyze trends based on release dates, top songs, their danceability, valence, energy levels, and instrumental content🎵📊🔍

# About the Dataset - 
This dataset contains comprehensive information on some of the most streamed songs on Spotify, enriched with additional insights from other popular streaming platforms like Apple Music, Deezer, and Shazam. It is ideal for music analysts, data scientists, and machine learning enthusiasts who are interested in exploring trends and characteristics of popular music tracks.

# Attribute Information:

Here is the meaning of each column in the dataset:
1. track_name: Name of the song.
2. artist(s)_name: Name of the artist(s) performing the song.
3. artist_count: Number of artists contributing to the song.
4. released_year, released_month, released_day: Release date details.
5. in_spotify_playlists: Number of Spotify playlists the song is featured in.
6. in_spotify_charts: Rank of the song on Spotify charts.
7. streams: Total number of streams on Spotify.
8. in_apple_playlists, in_apple_charts: Presence in Apple Music playlists and charts.
9. in_deezer_playlists, in_deezer_charts: Presence in Deezer playlists and charts.
10.in_shazam_charts: Rank on Shazam charts.
11. bpm: Beats per minute, representing the tempo of the song.
12. key: Key of the song.
13. mode: Indicates whether the song is in a major or minor mode.
14. danceability_%: Suitability of the song for dancing.
15. valence_%: Positivity of the song’s musical content.
16. valence_%: Positivity of the song’s musical content.
17. acousticness_%: Acoustic sound presence in the song.
18. instrumentalness_%: Proportion of instrumental content in the track.
19. liveness_%: Presence of live performance elements.
20. speechiness_%: Amount of spoken words in the song.
21. cover_url: Here we can see the url of the song.

# Technology Used :-
 Visual Studio Code (VS Code).

# Steps covered - 
1) Importing Dataset.
2) Exploratory Data Analysis(EDA)
3) Trating Null Values
4) Seperating Numerical and Categorical Columns in Dataset.
5) Description of Dataset.
6) Identifying The Outliers.
7) Removing Outliers.
8) Checking Skewness
9) Training Testing Dataset.
10) Regression Algorithms
