
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
- **popularity**: This numerical feature represents the popularity of each music track. It is likely a value between 0 and 100, where higher values indicate higher popularity. Popularity could be based on metrics like streaming counts, downloads, or social media engagement.

- **acousticness**: Acousticness is a measure of how much a track relies on acoustic (non-electronic) instruments. A value of 0 means the track is entirely electronic, while a value of 1 means it is entirely acoustic.

- **danceability**: Danceability is a measure of how suitable a track is for dancing based on elements like rhythm, tempo, and beat strength. Higher values indicate that the track is more danceable.

- **duration_ms**: This feature represents the duration of each track in milliseconds, indicating how long the track lasts.

- **instrumentalness**: Instrumentalness measures the extent to which a track contains no vocals. A value close to 1 indicates that the track is instrumental, while a value close to 0 indicates that it has vocals.

- **energy**: Energy represents the intensity and activity level of a track. High-energy tracks are generally more lively and fast-paced, while low-energy tracks are calmer and more subdued.

- **liveness**: Liveness measures the presence of an audience during a recording. Higher values suggest that the track was recorded in front of a live audience, while lower values indicate a studio recording.

- **loudness**: Loudness is a measure of the overall volume of a track. It is expressed in decibels (dB), and higher values indicate louder tracks.

- **speechiness**: Speechiness measures the presence of spoken words in a track. Higher values suggest that the track is more like a spoken word or a podcast, while lower values indicate more instrumental music.

- **tempo**: Tempo is the speed or pace of a track, expressed in beats per minute (BPM). It indicates how fast or slow the track is.

- **valence**: Valence measures the musical positiveness or happiness of a track. Higher values indicate more positive and cheerful music, while lower values indicate more negative or sad music.

## ML Task:
Our task is to classify input musical tracks into their corresponding genre. This is a classification problem since the values we are trying to predict are discrete. Specifically, we use a random forest classifier to perform this task since this algorithm suits the diversity of samples and features of our selected dataset.
