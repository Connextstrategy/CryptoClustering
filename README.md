# Python Rutgers Bootcamp Challenge - CryptoClustering

This activity is broken down into multiple deliverables to include a javascript application, an already created index file, and a dashboard viable via a web browser. 

## Description

In this assignment, you’ll use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

## Instructions

1. Rename the Crypto_Clustering_starter_code.ipynb file as Crypto_Clustering.ipynb.

2. Load the crypto_market_data.csv into a DataFrame.

3. Get the summary statistics and plot the data to see what the data looks like before proceeding.

## Prepare the Data

* Use the StandardScaler() module from scikit-learn to normalize the data from the CSV file.

* Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.

- The first five rows of the scaled DataFrame should appear as follows:

![Screenshot 2023-11-13 143742](https://github.com/Connextstrategy/CryptoClustering/assets/18508699/e2ee7df3-1d4a-4561-a19a-6dc1627fd9c5)

## Find the Best Value for k Using the Original Scaled DataFrame

* Use the elbow method to find the best value for k using the following steps:
  * Create a list with the number of k values from 1 to 11.
  * Create an empty list to store the inertia values.
  * Create a for loop to compute the inertia with each possible value of k.
  * Create a dictionary with the data to plot the elbow curve.
  * Plot a line chart with all the inertia values computed with the different values of k to visually identify the optimal value for k.
  * Answer the following question in your notebook: What is the best value for k?

### Dependencies

* Using Visual Studio Code for coding and data visualizations
* Web browser to show data visualizations (Google Chrome used but coudl be Mozilla or another)
* Use index to initiate data visualization
* Use app file in static folder to understand code for application

### Installing

* No modifications needed to be made to files/folders

## Help

* Use console.log inside of your JavaScript code to see what your data looks like at each step.

* Refer to the Plotly.js documentationLinks to an external site. when building the plots.

## Authors

Christopher Manfredi

## Version History
