# Cryptocurrencies

An exploration of unsupervised machine learning using KMeans and Principle Component Analysis in Python.

This repo employs the following Python libraries:

* Pandas
* hvplot
* plotly
* sklearn preprocessing (Standard and MinMaxScaler), decomposition (for PCA), and cluster (for KMeans)

the clustering_crypto.ipynb file:

* Cleans and preprocesses a csv file containing information on various cryptocurrencies, encodes labels to create 98 total features, and then scales the data using the Standard Scaler

* Conducts dimensionality reduction on the data into three principle components

* Uses an elbow curve to determine which amount of clusters will explain the most amount of variance in the data without over-fitting the model

* Trains a KMeans algorithm on the PCA data to create cluster labels for the data

* Visualizes the clusters created by the KMeans algorithm in a 3d plotly chart using the three principle components, and on a 2d chart with scaled features