# Project: Wrangling and Analyze Data

## Introduction

In this project, Python and its libraries, will be utilized to gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it.

The dataset for this project is the tweet archive of Twitter user [@dog_rates](https://twitter.com/dog_rates), also known as [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs). WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 9 million followers and has received international media coverage.

**Goal**: Wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations.

## Data Wrangling

The data wrangling procedure includes the following steps:

1. Data Gathering
2. Data Assessment
3. Data Cleaning

### Data Gathering

In this project, data was gathered from three sources in three different formats. The data gathered are as follows:

-   WeRateDogs Twitter Archive: This file was provided in CSV format.
-   Image Predictions: This file is a TSV file that is hosted on Udacity server.
-   Tweets: To retrieve tweets from Twitter API, the Tweepy package was used to get the status of each tweet by passing the tweet_id as a parameter to get_status method. The json package was used to read the response, which was in JSON format and the response was writing to a text file tweet_json.txt.

### Data Assessment

The datasets were assessed both visually and programmatically.

### Data Cleaning

Copies of the three data frames where created and all identify quality and tidiness issues were resolved using the Define-Code-Test framework.

At the end of the cleaning process, the clean DataFrame was stored in a CSV file as twitter_archive_master.csv, which was now ready for analysis.

## Analysis & Visualization

From the data set the following insights were derived:

1. Average Number of Dog Ratings Per Day
2. The Top 15 most popular dog breed
3. Platform for tweeting dog ratings
