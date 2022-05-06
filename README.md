# Hierarchical Clustering on my Spotify saved tracks

<img src="image/spotify.jpg" alt="drawing" width="700"/>

# Abstract

In this project we are going to use my personal dataset, a list of 103 songs that I have saved on my Spotify account (and completely forgot abouth them). The dataset was created using the Spotify API, see Jupyter Notebook 00_Spotify_Scraper for details on how to do this.


We are trying to use numerical values of the song assigned by Spotify's users like **energy**, **liveness**, **speechness**, **tempo**, **acousticness**, etc.. to cluster the songs.

For this project we will take a look at an alternative approach to K Means clustering, popularly known as the Hierarchical Clustering. The hierarchical Clustering technique differs from K Means or K Mode, where the underlying algorithm of how the clustering mechanism works is different. K Means relies on a combination of centroid and euclidean distance to form clusters, hierarchical clustering on the other hand uses agglomerative or divisive techniques to perform clustering. Hierarchical clustering allows visualization of clusters using dendrograms that can help in better interpretation of results through meaningful taxonomies. Creating a dendrogram doesn’t require us to specify the number of clusters upfront.

Check this cool [article](https://towardsdatascience.com/hierarchical-clustering-in-python-using-dendrogram-and-cophenetic-correlation-8d41a08f7eab) for more info.
