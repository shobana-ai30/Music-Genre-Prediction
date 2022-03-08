# Music-Genre-Prediction
This project aims to predict the genre of a track from a set of tracks obtained from FMA using the various quantifiable features of tracks such as Acousticness, Energy, Tempo et al with the help of Machine Learning Models

# Files Required to run :
Files required to upload for initial dataset creation are :

● raw_echonest.csv - contains features

● tracks.csv - Contains genre label , with track id

● Merge_Genre.csv - Cleaned file

Change the url location as per the path of these files in your local system.

Merge_Genre can be created at run time by uncommenting the following line :

#df3.to_csv("Merge_Genre.csv", encoding='utf-8')

# Modules Required :
Modules required to print the decision tree

● Graphviz-python

● Pydot

Install through the following steps for conda :

● conda install graphviz-python

● conda install pydot

# Dataset
The raw dataset is collected from the Free Music Archive Dump, with a total of 106574 tracks labeled according to their track id, with features to aid the classification like acousticness, danceability, energy, instrumentalness, liveness, speechiness, tempo andvalence. It also contains 223 temporal features which captures the beat for rhythmic similarity.

The full raw dataset can be downloaded here:

https://drive.google.com/drive/folders/17n6RVgU_TOmgcixlFsqynmXCVqvKdVSd

Our raw dataset is in csv format, with 3 files as follows:

* raw_echonest.csv : various audio and temporal features provided of music tracks of
Spotify (formerly Echonest)

* genres.csv: genres listed according to id and title

* tracks.csv : lists tracks according to its album with features such as track id, duration,
number of times a track is listened to, and, of course, the genres


