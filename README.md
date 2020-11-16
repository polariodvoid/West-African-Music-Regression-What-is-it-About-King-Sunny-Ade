# data601homework3
Homework 3 doing a linear regression 
<h1>Overview</h1>
<p>This Repo contains the report also known as the Juptyer notebook, the images included with the exploratory analysis, also the data csv file. The notebook explores the audio features of a West African music playlist titled "West African classics (Afrobeat, Highlife, Juju, Afrojazz, Afro-blues, etc) from the user Jonas Grönlund.</p>
<h2>Goals and Motivation</h2>
<p>The motivation was from experiences at Nigerian functions and observing the music being different from music typically heard on the radio, and the television. The features would like to be seen to identify certain patterns, specfically the relationship between the instrumentalness and the danceibility. These two especially since from what I've noticed from from the songs on the playlist are the many sections where they are no vocal to be heard and the instruments players just 'jam' out for lack of a better term.
  </p>
<h3>Data</h3>
<p>The Spotify API was used and the libary Spotipy was installed to analyse the playlist. The audio features present on the dataframe are  artist, album, track_name, track_id, danceability, energy, key, loudness, mode, speechiness, instrumentalness, liveness, valence, tempo, duration_ms, time_signature. Some of these features are self explanatory if you are familar with music, some are not or are deceiving. Track_id unique identifier of the song. Danceability is how suitable a track is for dancing based on a combination of the various details on the song like tempo, rhythm stability, beat strength, and overall regularity. Energy is how intense or fast a song like danceability based a number of factors like dynamic range, perceived loudness, timbre, onset rate, and general entropy. Mode is what tye of scale the scale the song is on it can be either major or minor. Valence is the measure of whther the song was happy or sad, outputting a float between 0 and 1. Instrumentalness is the lack of vocals, ohhs and ahhs are considered instrumental in this case, a float between 0 and 1. Speechiness is the presence of voacls Further information can be found here on Spotify's website. https://developer.spotify.com/documentation/web-api/reference/tracks/get-audio-features/
In our findings a relationship between instrumnetalness and danceiblity was not found. A low insturmentalness was found with majorite tracks. As seen with the scatter plots. I think this was due to the definition of the variable and I would like to look at possiblily the acouticness or the enrgy in relation with dancability next time.</p> 
<h4>Table of Content</h4>
1. Technical Notebook
2. Image of King Sunny Ade
3. Data
4. Visuals of Plots 
<h5>Table of Content</h5>
<p>Spotipy, Sklearn, Matplotlib, and Pandas</p>
