# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 3: Web APIs & Classification

### Problem Statement

- To utilize the Reddit API to scape posts automatically from 2 Subreddits.
- To create and compare 2 Classification models. The models predict which Subreddit a specific post came from. 
- To identify trending games for conversion e.g. from board to mobile games and vice-versa.

### Data Collection

- The posts are scaped using the Reddit API (https://www.reddit.com/dev/api/).
- The posts are scaped from 2 popular Subreddits i.e. Board Games (https://www.reddit.com/r/boardgames/) and Mobile Games (https://www.reddit.com/r/mobilegames/) with 2.1 million and 2.8k members respectively.
- The Reddit API extracts the posts in JSON format and the posts are stored as json files for future analyssis.

### User Configurations

| Variable Name | Default Value | Description |
| --- | --- | --- |
| scape_data | False | True: Scape data from Reddit and save as json files<br>False: Load json files from input folder |
| scape_index | 0 | if scape_data=True<br>0: Scape data from subreddits[0]<br>1: Scape data from subreddits[1] |
| **2** | *Project meets expectations; few (and relatively minor) mistakes.* |
| **3** | *Project demonstrates a thorough understanding of all of the considerations outlined.* |

### Executive Summary

Link:
