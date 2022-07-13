# WeRateDogs Analysis

## By Hashim Hashim

## Introduction

WeRateDogs is a twitter account that started in 2015. The account rates people's dogs with humorous comment about the dog. WeRateDogs has over 4 million followers and has received international coverage

## Project Details

For this project, we only wanted original ratings (no retweets) that have images. Not all of the original tweets in the dataset are dog ratings and some are retweets.

Fully assessing and cleaning the entire dataset would require exceptional effort so only a subset of its issues (eight quality issues and two tidiness issues at minimum) needed to be assessed and cleaned.

The tasks for this project were:

Data wrangling, which consisted of:
- Gathering data
- Assessing data
- Cleaning data
- Storing, analyzing, and visualizing the wrangled data
- Reporting on my data analyses and visualizations (act_report.html)

## Data

The project consisted of three dataframes:

- Twitter archive file which was provided by Udacity. 
- Image prediction file which is hosted inside the Udacity servers is downloaded programmatically using the python's request library to get a tsv file then loaded inside the jupyter notebook and saved as image_pred dataframe.
- Json API file obtained by gathering data from twitter APIs using the the tweets id in the twitter archive file. The resulting tweet_json.text file is loaded as a dataframe as json_api dataframe that contained tweet id,retweet counts and favorite counts.

## Insights

In this analysis, a trend is recognised in the number of favorites and the number of retweets. We saw a positive correlation between the the number of retweets and the number of favorites. This shows that there is a high engagement of the WeRateDogs twitter account which reflects followers interests and preferences with dogs.
