# CryptoClustering

This project is the Module 19 challenge on unsupervised learning.  This challenge uses unsupervised learning, Python, and jupyter notebook to predict whether crypto currency prices are affected by the 24-hour or the 7-day price change.  Other time periods, up to one year, are present in the data for each bitcoin type.  The project reads in csv data called "crypto_market_data" from the "Resources" subfolder and creates a Pandas dataframe.  It then scales the data using the standard scaler from scikit learn.  An elbow plot is created by examing a kmeans model for 11 different values of k, then the kmeans predictions are made using K set to the best value identified from the elbow plot, and hvplot is used to plot the data.   

A similar analysis is then conducted using principle component analysis with three principal components.  The best K for the PCA data is identified using an elbow plot, a kmeans model is created from the PCA data, and hvplot is used to plot the results. 

The final analysis is conducted usings hvplot composite plots to visually compare the two sets of results and the two sets of plots.

The code is designed to be run with juptyer notebook started from the main project directory.
