# homework3
# Assignment 3 – Sentiment Analysis with AWS

## Problem
The goal of this assignment is to compare sentiment across multiple news-related texts using cloud-based services.

## Data Sources
- English article (Wikipedia)
- Second English article (Wikipedia)
- Non-English article translated to English using AWS Translate

## Methodology
Texts were collected, translated when necessary, and analyzed using Amazon Comprehend for sentiment classification. Results were aggregated and visualized using Python.

## AWS Services Used
- Amazon Comprehend (sentiment analysis)
- Amazon Translate (language translation)

## Results
Sentiment scores indicate that most texts are classified as neutral, which is expected for informational news content. Some variation appears in negative and mixed sentiment across sources.

## Cost Estimation
All AWS services were used within the free tier limits. Estimated cost is negligible (< $1).

## Limitations
- News articles tend to be neutral in tone
- Scraping limitations required use of alternative data sources
