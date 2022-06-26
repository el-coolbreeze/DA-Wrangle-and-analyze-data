# DA-Wrangle-and-analyze-data

The goal of this project is to wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations.

# Data Gathering 

The data for this project involved three datasets, they were gathered as follows:

- The WeRateDogs Twitter archive ('twitter-archive-enhanced.csv' file): this
dataset was provided by Udacity and was downloaded manually via the provided
download link.

- The tweet image predictions ('image_predictions.tsv' file): this dataset contains
the results obtained from running every image in the WeRateDogs twitter archive
through a neural network for the purpose of classifying different breeds of dogs.
This file was downloaded programmatically using python's request library and the
provided URL from Udacity.

- Additional data from the Twitter API: for this file, using the 'tweet_id' in the
WeRateDogs Twitter archive dataset, I successfully queried and downloaded the
'favorite_count' and 'retweet_count' for each 'tweet_id' using Python's tweepy
library from Twitter's API.

# Assessing Data
The dataset was assessed to identify several quality and tidiness issues with each issue documented.

# Cleaning Data
The quality and tidiness issue documented were cleaned using the define-code-test framework

# Storing Data
The cleaned master dataset was stored in a CSV file called 'twitter_archive_master.csv'

# Analyses and Visualizations
The master dataset was analyzed with visualizations made from the insights gained from within.