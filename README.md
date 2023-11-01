# CryptoClustering

__Project Summary__

In the CryptoClustering project, I used Python and unsupervised learning techniques to predict if cryptocurrencies are affected by 24-hour or 7-day price changes. The key steps of the project include:

__Data Preparation:__ I loaded the cryptocurrency market data from the provided crypto_market_data.csv file into a DataFrame. I then standardized the data using the StandardScaler module from scikit-learn.

__Finding the optimal K:__ I applied the elbow method to determine the best value for k (the number of clusters) for K-means clustering. This step involved creating a list of possible k values, computing the inertia values for each k, and plotting an elbow curve to identify the optimal value for k.

__Clustering Cryptocurrencies:__  I clustered the cryptocurrencies using K-means with the best k value found in the PCA data and created a scatter plot to visualize the clusters, with the x-axis representing "price_change_percentage_24h" and the y-axis representing "price_change_percentage_7d."

__Principal Component Analysis (PCA):__ I performed PCA on the original scaled data to reduce the features to three principal components. I then determined the total explained variance of the three principal components.

__Finding the Optimal K for PCA Data:__ Similar to the previous step, I applied the elbow method to find the best value for k when using the PCA data.

__Clustering with PCA Data:__I clustered the cryptocurrencies using K-means with the best k value found in the previous step. I created a scatter plot to visualize the clusters, with the x-axis representing "PC1" and the y-axis representing "PC2."

Screenshots
Here are the screenshots of the elbow plots and scatter plots created during the project:

![Elbow Plot for Original Scaled Data]
(</Users/kaijagregory/Desktop/Screenshot 2023-10-31 at 10.55.32 PM.png>)

![Scatter Plot for Clustering with Original Scaled Data]
(</Users/kaijagregory/Desktop/Screenshot 2023-10-31 at 10.55.45 PM.png>)

![Elbow Plot for PCA Data]
(</Users/kaijagregory/Desktop/Screenshot 2023-10-31 at 10.55.55 PM.png>)

![Scatter Plot for Clustering with PCA Data]
(</Users/kaijagregory/Desktop/Screenshot 2023-10-31 at 10.56.06 PM.png>)

__Conclusion__

The CryptoClustering project demonstrates the use of unsupervised learning techniques, specifically K-means clustering and PCA, to analyze and cluster cryptocurrency market data. The project provides valuable insights into the optimal number of clusters and the impact of using dimensionality reduction techniques like PCA for clustering. This can be useful for understanding how cryptocurrencies behave in response to price changes over different time intervals.

For more details, refer to the Jupyter Notebook (Crypto_Clustering.ipynb) in this repository.

Feel free to reach out if you have any questions or need further assistance.

