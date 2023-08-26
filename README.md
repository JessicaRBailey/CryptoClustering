# CryptoClustering
Challenge 19

This project uses unsupervised machine learning to analyze the price change data for cryptocurrencies. 

First we analyze a scaled version of the full data set, find the best number of clusters to group our data by using an elbow curve, then apply KMeans using the best number of clusters.  

Then we apply principal component analysis (PCA) to reduce the dimensionality of our data down to three features.  Applying an elbow curve result and KMeans to our PCA data yields a dataset that encompasses 89.5% of our original data.  

Finally, applying a feature weight formula helps us understand PCA groupings.  

More detailed analysis is contained within the file Crypto_Clustering.ipynb.
