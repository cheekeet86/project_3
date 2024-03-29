# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 3: Web APIs & Classification

### Problem Statement

- To utilize the Reddit API to scape posts automatically from 2 Subreddits.
- To create and compare different classification models. The models predict which Subreddit a specific post came from. 
- To perform sentiment analysis on post contents. Provide advertising strategies for customers.

### Data Collection

- The posts are scaped using the Reddit API.
- The posts are scaped from 2 popular Subreddits i.e. Board Games and Mobile Games with 2.1 million and 2.8k members respectively.
- The Reddit API extracts the posts in JSON format and the posts are stored as json files for future analysis.

### User Configurations

| Variable Name | Default Value | Description |
| --- | --- | --- |
| scape_data | False | True: Scape data from Reddit and save as json files<br>False: Load json files from input folder |
| scape_index | 0 | if scape_data=True:<br>0: Scape data from subreddits[0]<br>1: Scape data from subreddits[1] |
| num_requests | 50 | Number of Reddit API requests<br>Note: 25 posts are scaped per request. |
| posts_limit | 900 | Number of Posts used (per Subreddit) to build models |
| subreddits | [ boardgames , mobilegames ] | Subreddits List |
| url | https://www.reddit.com/r/ | Base URL for scaping |
| headers | User-agent:Bleep blorp bot 0.1 | User Agent Settings |

### Executive Summary

[Click Here](documents/Executive%20Summary.md)

### References

[Reddit API](https://www.reddit.com/dev/api/)<br>
[Board Games Subreddit](https://www.reddit.com/r/boardgames/)<br>
[Mobile Games Subreddit](https://www.reddit.com/r/mobilegames/)
