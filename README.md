# SpotifyPlaylist

### 🎹What is the 'recipe' for winning tracks?🤔
We sometimes wonder what makes a track successful these days?
With this question in mind, I gathered various information and audio features – danceability, speechiness or liveness – of the top tracks in the last 5 years.

#### Audio Features:
Mood: Danceability, Valence, Energy, Tempo
Properties: Loudness, Speechiness, Instrumentalness
Context: Liveness, Acousticness

#### Column Description:
track_uri: track's unique resource indicator code on Spotify
track: track name
artist: the artist name who performed the track
artist_popularity: the artist's popularity is given a value between 0 and 100, with 100 being the most popular
followers: the total number of followers who follow the artist's Spotify page
artist_genre: the genre in which the artist belongs
track_popularity: the track's popularity is given a value between 0 and 100, with 100 being the most popular
album: album name
year: year
danceability: how suitable the song is for dancing
valence: a value from 0.0 to 1.0 describing the positiveness with higher valence indicates happy, cheerful, euphoric mood
energy: a perceptual measure of intensity and activity
tempo: the overall estimated tempo of a track in beats per minute (BPM)
loudness: the overall loudness of a track in decibels (dB), ranging between -60 and 0 db.
speechiness: the higher the value, the more spoken words the song contains
instrumentalness: the higher the value, the song contains fewer spoken word vocals
liveness: the probability that the song was recorded with a live audience
acousticness: a measure from 0.0 to 1.0 of whether the track is acoustic
In-depth explanation about the audio features could be found [here](https://developer.spotify.com/documentation/web-api/reference/#/operations/get-audio-features).

#### Data Collection:
You can find the data collection process in the public notebook section, [here](https://www.kaggle.com/code/sejungjenn/spotify-api-with-spotipy-collecting-data).

#### Usage:
Discussed the usage of this dataset with fellow Kagglers, and their suggestions could be found [here](https://www.kaggle.com/discussions/questions-and-answers/374408).

#### Acknowledgement
image credits: [istockphoto](https://www.istockphoto.com/kr/search/2/image?phrase=dj)
