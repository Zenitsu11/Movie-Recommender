# Web App: A movie recommender application designed using Streamlit.

This project involves building a simple web app using streamlit which helps in providing multiple  movie recommendations to the users after they have watched a particular movie. This project can be said to be on an intermediate level and has really helped us to gain more exposure towards the domain of creating applications and unique aspects of programming involved in the same.

## Prerequisites
Streamlit

## Objective
The project focusses on building an application which will make movie recommendations hassle-free and user friendly depending on the user's last watched movies. This application analyses the recent movie watched by the user and thereby give suggestions based on cosine similarity.
## Project Context
Movie recommendations are a unique concept and are used in various streaming platforms in day to day lives. Recommendations are based on the frequently watched genres or the user's preferences towards certain themes.

Recommendations can be based not just on movies but on songs, TV shows, web series, etc. However, certain applications are not adept in providing suitable and appropriate recommendations.

When it comes to streaming services, no system provides accurate and appropriate recommendations as that of Netflix. Amazon Prime Video and Disney+ Hotstar provide a large variety of viewing content but lose out to Netflix when it comes to providing recommendations.

Spotify, YouTube, Netflix are some applications which provide suitable recommendations. This project provides a user friendly interface and provides appropriate recommendations to the users based on their last watched movie.

It does have certain shortcomings such as the range of recommendations are selectively related just to movies and nothing more. Also, the UI is minimalistic and can have a more graphic outlook.

The application's interface and a walkthrough about it's usage can be accessed using the following link:

https://drive.google.com/file/d/1gj8K3gTEUb0l2sIV537Qr-FL28qEuEal/view?usp=sharing

Now we can discuss the various steps involved in the running of this application and the logic of cosine similarity which forms the basic foundation for the execution of this app.
## What is Cosine Similarity?
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.
## Functioning of the program
Content Based Filtering - They suggest similar items based on a particular item. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. The general idea behind these recommender systems is that if a person liked a particular item, he or she will also like an item that is similar to it.
## Similarity Score
How does it decide which item is most similar to the item user likes? Here we use the similarity scores.
It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.
## Sources of the datasets
TMDB 5000 movies dataset has been used for this project. The dataset can be collected from: https://www.kaggle.com/tmdb/tmdb-movie-metadata
