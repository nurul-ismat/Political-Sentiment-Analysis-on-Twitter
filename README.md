## 🗳️ Political Sentiment Analysis on Twitter

## Tech Stack: 
Python | Tweepy | Pandas | TextBlob | VADER | Matplotlib | Plotly | Scikit-learn

## Description:
This project performs sentiment analysis on tweets from popular politicians to uncover insights into their tweeting habits, 
stance on major issues, and public support. It uses machine learning and NLP techniques to analyze tweet polarity and subjectivity,
visualize trends, and identify political patterns through data-driven insights.

## ✨ Key Features:
- Collects live tweets using Twitter API (Tweepy) <br>
- Cleans and processes text data with NLP libraries<br>
- Calculates sentiment polarity and subjectivity (TextBlob & VADER)<br>
- Visualizes data with scatter plots, pie charts, and word clouds<br>
- Compares engagement metrics and average tweets per day<br>
- Identifies sentiment trends during major political events<br>

## 📂 File Structure Overview:
- collect_data.py → Fetches tweets and saves them as CSV files
- process_tweets.py → Cleans tweets and adds sentiment metrics
- pie_scatter.py → Visualizes polarity and party-based sentiment differences
- gen_wordcloud.py → Generates positive & negative word clouds
- engagement_plot.py → Plots engagement vs polarity
- average_tweets.py → Shows average tweet frequency
- christchurch_shooting.py → Analyzes sentiment during major events
- data/ → Contains CSV tweet datasets
- Twitter_Sentiment_Analysis.pdf → Project presentation
- Code_Demo.ipynb → Jupyter Notebook demo

## 🔧 Requirements:
pip install tweepy pandas numpy textblob vaderSentiment wordcloud matplotlib plotly plotly-express statistics scikit-learn

## 🎯 Objective:
To analyze and visualize the sentiment dynamics of political figures on Twitter, revealing correlations between tweet tone, political stance, and engagement patterns.
