# Music-genre-classification
Flask app to predict the genre of a given track based on a set of features

# Understanding the problem statement
The dataset contains recors documenting musical tracks alognside their information such as the track's title, artist, danceability, key and more. The goal of this project is to understand how these features are pre-determinal of the genre to which the music track belongs to. 
The end goal of the project is to utilize classification algorithms and techniques to allow us to predict which category the track belongs to genre wise.


# Data collection:
- The dataset used for this project could be found on Kaggle [here](https://www.kaggle.com/datasets/vicsuperman/prediction-of-music-genre).

# Dataset Features:
- The dataset has 50005 rows.
- The datset has 18 columns.

## Categorical columns:
- **artist_name**: name of the artist who made the track
- **track_name** : name of the track
- **key**:  the primary or most frequently occurring pitch or chord that provides a sense of stability and resolution in the music.
- **mode**:  Imagine a musical mode as a unique set of notes that give a song its special feeling or mood. Think of these modes like different "flavors" of scales. Each mode starts and ends on a different note, and this note is like a home base for the music.
- **music_genre**: the genre to which the track belongs to.

## Numerical Columns:
- **popularity**: how popular this musical track is, it is unclear with respect to what criteria exactly, but the assumption here is that the popularity of the track corresponds to its position in a music ranking chart of some sort.
- **acousticness**: the track's acousticness
- **danceability**: how danceable is this track
- **duration_ms**: the duration of the track in ms
- **energy**: The speed of the music can significantly impact its energy level. Fast tempos tend to create a higher-energy feeling, while slower tempos often result in a more relaxed atmosphere.
- **instrumentalness**: 
- **liveness**:
- **loudness**:
- **speechiness**:
- **tempo**: The speed of the music. Fast tempos tend to create a higher-energy feeling, while slower tempos often result in a more relaxed atmosphere. Usually measured in beats per minute (BPM)
- **valence**:


