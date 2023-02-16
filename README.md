# YoutubeToSpotify
This Python code uses the YouTube Data API and Spotify API to create a new Spotify playlist containing all of the user's liked videos from YouTube.
The code does the following:

It uses the YouTube Data API to retrieve the user's liked videos from their YouTube account.
For each liked video, it extracts the video title, YouTube URL, song name, and artist name using the youtube_dl library.
It then uses the Spotify API to search for the song on Spotify and get its URI (a unique identifier for the song on Spotify).
It saves all of the relevant information in a dictionary and creates a new playlist on the user's Spotify account.
Finally, it adds all of the songs to the new playlist on the user's Spotify account.
