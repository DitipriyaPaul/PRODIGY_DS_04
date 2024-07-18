## Task 4 (Social Media Sentiment Analysis)
This project analyzes the sentiment of social media posts using the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis tool from NLTK. The analysis includes sentiment distribution, sentiment trends over time, and visualization of common words in positive and negative posts.

Overview

Data Source: A CSV file containing social media posts with 'text' and 'timestamp' columns.
Sentiment Analysis: Utilizes the VADER sentiment analyzer to compute sentiment scores for each post.
Visualizations:
Sentiment distribution histogram.
Sentiment trends over time.
Word clouds for positive and negative sentiments.
Steps

Data Loading: Load the dataset containing social media posts.
Sentiment Analysis: Apply the VADER sentiment analyzer to each post to obtain sentiment scores.
Visualization:
Sentiment Distribution: Plot a histogram of sentiment scores.
Sentiment Trends Over Time: Calculate and plot the average sentiment score over time.
Word Clouds: Generate word clouds for positive and negative sentiment posts.
Requirements

pandas for data manipulation.
nltk for sentiment analysis.
matplotlib and seaborn for data visualization.
wordcloud for generating word clouds.
Usage

Ensure the dataset is named your_dataset.csv and contains 'text' and 'timestamp' columns.
Run the script to perform sentiment analysis and generate visualizations.
