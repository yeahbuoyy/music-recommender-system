# music-recommender-system
This program is a machine learning model that uses the concept of cosine similarity to do content-based filtering on the Spotify dataset. The program generates a "similarity score" for each song based on its acoustic features such as acousticness, danceability, energy, and tempo, among others. Using this score, the program compares and retrieves the top 5 songs that are most similar to a given song.

The program takes an artist's name and a selected song as input and returns the most similar songs by other artists. The program first checks whether the selected song is present in the dataset for the given artist. If it is not present, it returns an error message. The program then computes the cosine similarity between the selected song and all other songs in the dataset using the acoustic features of the songs. The songs with the highest similarity scores are then returned as the top 5 most similar songs. This program is useful for creating personalized playlists for users based on their music preferences.