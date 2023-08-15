# Music-Recommendation-System
A Machine learning model that recommends similar songs when given a playlist.

This Application uses Spotipy API to extract features of a song. Using the extracted features recommendations are given to the user by the machine learning model. The machine learning model is built on python by using various libraries such as pandas, sklearn, etc. The model is trained using the dataset https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks .
Weights to different features are given using the TF-IDF(Term Frequency-Inverse Document Frequency) algorithm and this is used to give the best recommendations. 

# To run the Application:

1) Clone the repository.
2) Open the terminal in the cloned folder.
3) Run: python wsgi.py

# References
The Application was built using resources of https://towardsdatascience.com/part-iii-building-a-song-recommendation-system-with-spotify-cf76b52705e7
