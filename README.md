# 🐦 Twitter Hashtag Scraper using Tweepy
## 📌 Overview
This Python project utilizes the Tweepy library and Twitter API v2 to extract live tweets from Twitter based on a specific hashtag. In this example, we query tweets containing the hashtag `#IPL` (Indian Premier League).

## ⚙️ Features
- Connects to Twitter API using OAuth 1.0a and Bearer Token (API v2).

- Fetches the most recent tweets containing a user-defined hashtag.

- Retrieves and prints the tweet text in the console.

- Limits the number of tweets returned (in this case, 10 tweets).

- Uses `search_recent_tweets()` for up-to-date results from Twitter API v2.

## 🧰 Tech Stack
- Python 🐍

- Tweepy (Twitter API wrapper)

- Twitter Developer API v2

- Pandas (optional for further analysis or saving data)

## 🚀 How It Works
1. Authenticate with Twitter API using:

2. Consumer Key and Secret

3. Access Token and Secret

4. Bearer Token (for v2 endpoints)

5. Search for tweets using the `#IPL` hashtag.

6. Fetch and display the 10 most recent tweets.

7. Can be adapted to search for any hashtag or keyword.
