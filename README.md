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


