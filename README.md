# Cryptocurrencies

# Purpose of the project:
The purpose of the project is to use unsupervised machine learning to create clusters for various of cryptocurrencies, in order for the client Accountability Accounting to offer cryptocurrency investment portfolio for its customers.

In the process, we used Python's Pandas library to clean, transform the data. Removing data that won't be useful in the machine learning algorithms, transform the text data to numeric data, and to scale and normalize the data. Then we use Scikit-learn's PCA module to reduce the number of the data. And we use Scikit-learn's KMeans module, first we prepare the data and create the elbow curve plot to determine the number of K (clusters), then we train the machine learning model, and to predict the clusters for the cryptocurrencies' data.

We also use the data to create a 3D scatter plat, a 2D scatter plot and a table with the original data plus the data that we transformed and used in the machine learning algorithms.
