
Tweet Clustering with K-Means
This project performs tweet clustering using the K-Means algorithm and calculates the similarity between tweets using the Jaccard distance. The goal of this project is to cluster tweets into groups based on the similarity of their content. It includes the preprocessing of tweets, running K-means for clustering, and visualizing the results.

Table of Contents
Project Description

Technologies Used

How to Run the Code

Results

Contributing

Project Description
This project performs the following steps:

Preprocessing Tweets: The input tweets are cleaned by removing unnecessary characters such as @mentions, hashtags, URLs, and ensuring that the text is in lowercase.

Jaccard Distance: The similarity between tweets is calculated using the Jaccard distance, which measures the similarity of two sets by comparing the intersection and union of words.

K-Means Clustering: The K-Means algorithm is used to cluster the tweets into k clusters. The value of k is set to 3 by default and is incremented in each experiment.

SSE Calculation: The Sum of Squared Errors (SSE) is computed after each clustering experiment, providing insight into how well the clustering was performed.

Plotting Results: The clustering results are plotted on a graph with the number of clusters (k) on the x-axis and the corresponding SSE values on the y-axis.

Technologies Used
Python

Libraries: re, numpy, matplotlib

Algorithm: K-Means Clustering

Jaccard Distance for measuring tweet similarity
