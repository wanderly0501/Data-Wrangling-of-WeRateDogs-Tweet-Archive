# Data Wrangling of WeRateDogs Tweet Archive
## Overview
This project wrangled, analyzed and visualized the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a twitter account that rates people's dogs with a humorous comment. The output are two files storing clean data.
## Installing
- Install Jupyter Notebook to run `wrangle_act.ipynb`.
- Need consumer_key, consumer_secret, access_token, access_secret to query from Twitter API.
- Require the following libraries installed.

- numpy
- pandas
- requests
- json
- matplotlib.pyplot

## Files
- `act_report`: Communicates the insights and displays the Visualizations produced from the wrangled data.
- `image_prediction.tsv`: Data downloaded using Requests library and URL.
- `tweet_json.txt`: Data gathered from twitter API.
- `twitter-archive-enhanced.csv`: File downloaded from Udacity.
- `twitter_archive_master.csv`: The clean DataFrame 1.
- `twitter_image_predictions.csv`: The clean DataFrame 2.
- `wrangle_act.ipynb`: The main file containing all the gathering, wrangling and analyzing work.
- `wrangle_report`: Briefly describes my wrangling efforts.
## Table of Contents
#### Gather Data
- Gather data from file on hand
- Download file using Requests library and URL
- Gather data from twitter API using Python's Tweepy library and store data
#### Assess Data
#### Clean Data
#### Store Data
#### Analyze and Visualize Data
- Visualization
- Insight
## Resources
- Twitter API
- Files downloaded from Udacity
