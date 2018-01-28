# SheHacks Boston Project

## Goal
Create a solution that will help combat the fake news phenomena.

## Competing Categories
- **Google Cloud Platform**

*Google Cloud Platform Award! For the team with the best use of the Google Cloud Platform.*


- **Political Polarization**

*Create a solution that will help combat the fake news phenomena.*


- `She </LEARNS>`

*Beginner Hack Award! For the beginner team (where at least half of team members have never attended a hackathon before) with most ambitous hack.*

## Tools and APIs 
- Python
- Flask
- Google Cloud Natural Language API
- Google Cloud Custom Search API
- Google Cloud Compute Engine
- Google Cloud App Engine

## Implemented Solution
We relied on the Google Cloud Natural Language API to measure the sentiment analysis of different news articles. With the sentiment score of an article, we can infer whether an article is more opinionated or factual. 

We deployed a web application in Flask that uses some of the Google Cloud APIs. It allows the user to enter a phrase, headline, or article. This input is passed to the Natural Language API to get a list of the most relevant keywords in it. Finally, these keywords are used to find similar articles from the following news sources— Fox News, The New York Times, CNN, The Washington Post, Google News, The New Yorker, The Economist, NBC News, ABC News, and CBS News. 

To visually represent the data obtained, a pie graph with the sentiment scores is used to represent the percentage of the similar articles that have a positive, negative, or a neutral tone. 



