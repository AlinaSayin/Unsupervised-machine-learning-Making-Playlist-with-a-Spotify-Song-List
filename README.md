# Unsupervised-machine-learning-Making-a-Playlist-with-a-Spotify-Song-List 

Getting Started
This is my 6th project in my coding school and we learnd about unsupervised machine learning.
In this I use a dataset that has been collected from the Spotify API and contains the audio features (name, artist, danceability, energy, key, loudness, mode, speechiness, acousticness, instrumentalness, liveness, valence, tempo, type, duration_ms, time_signature, id, html) for a few thousand songs, and use a basic clustering algorithm such as K-Means to divide the dataset into a few clusters (which will become playlists)

Prerequisites
Requirements for the Project

import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.preprocessing import MinMaxScaler
from sklearn.cluster import KMeans
from sklearn.preprocessing import StandardScaler
from sklearn.feature_selection import VarianceThreshold
import sklearn.metrics as metrics
import sklearn.cluster as cluster
from yellowbrick.cluster import SilhouetteVisualizer
from yellowbrick.datasets import load_nfl
from sklearn.metrics import silhouette_score
import random

Built With
Python in Google colab 

Authors
Me and my school (wbs coding school)
