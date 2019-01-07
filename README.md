# YoutubeDataExtract
This repo contains some functions I wrote to extract youtube data easily from a channel. Many of the existing solutions on the web for Youtube data tend to retrieve video by keyword searches or popularity, instead of retrieving videos by an uploaded username. This is where the function retrieve_all_from_channel() comes in.

Just enter the channel's name into the function retrieve_all_from_channel() and it will return a dataframe of 11 features consisting of:

['title', 'description', 'date', 'channel', 'num_tags', 'duration', 'viewcount', 'likecount', 'dislikecount', 'commentcount', 'topics']

Check out the juypter notebook for the code an example! Note you will need an api key to access the youtubedataapi! See here for more info: https://developers.google.com/youtube/v3/getting-started
