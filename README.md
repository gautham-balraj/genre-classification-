# genre-classification-
Genre classification of given audio using Tensorflow 

dataset source: https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification?select=Data


This project utilizes the GTZAN Genre Classification dataset, comprising 1,000 audio tracks, each lasting 30 seconds. This dataset is renowned as the MNIST equivalent for sound, encompassing 10 distinct genres, with each genre represented by a set of 100 tracks.

The dataset encompasses the following genres:

Blues
Classical
Country
Disco
Hip-hop
Jazz
Metal
Pop
Reggae
Rock


Within the dataset, there are two primary folders:

Genres original: This folder contains the 10 genres, each housing 100 audio files, all uniformly 30 seconds in length.

Moreover, the dataset features two essential CSV files. One file encapsulates audio file features, with each song (30 seconds long) showcasing a mean and variance computed across various audio features. The second CSV file mirrors the structure of the first, but the songs are segmented into 3-second audio files, offering a more granular perspective on the audio characteristics.

For modeling purposes, TensorFlow's artificial neural network (ANN) has been employed, harnessing the power of deep learning to analyze and classify audio data, providing a robust foundation for genre classification within this project.
