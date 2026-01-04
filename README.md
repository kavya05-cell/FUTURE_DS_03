# Student Satisfaction Survey Analysis

## Overview
This project analyzes student satisfaction survey data collected across multiple courses.
The analysis computes weighted average satisfaction scores, derives sentiment indicators,
and visualizes insights using charts and word clouds.

## Dataset
- Student_Satisfaction_Survey.csv (raw data)
- Student_Satisfaction_Final_With_Sentiment.csv (processed data)

## Methodology
- Data cleaning and preprocessing
- Weighted average calculation from rating distributions
- Synthetic feedback generation
- Sentiment analysis using TextBlob and VADER
- Visualization using matplotlib and wordcloud

## Tools & Libraries
- Python
- Pandas
- Matplotlib
- TextBlob
- VADER Sentiment
- WordCloud

## Outputs
- Satisfaction distribution charts
- Course-wise performance graphs
- Sentiment distribution
- Word clouds

## Note
Sentiment analysis was performed on synthetically generated feedback
based on rating distributions, as the original dataset did not include
free-text responses.
