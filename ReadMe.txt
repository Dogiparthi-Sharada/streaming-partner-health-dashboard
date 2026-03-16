# Streaming Partner Health Dashboard

An end-to-end analytics and NLP pipeline that monitors Google Play Store reviews for streaming partners such as Disney+ and Max.

## Project Overview

This project pulls live Google Play reviews, applies machine learning-based sentiment analysis and NLP topic detection, stores structured outputs in Airtable, and visualizes partner health metrics in a dashboard.

## Features

- Google Play review scraping
- Large-scale review dataset creation
- Random Forest sentiment classification
- Topic detection for issue categorization
- Airtable API integration
- Executive dashboard with KPIs and trend monitoring

## Tech Stack

- Python
- Pandas
- Scikit-learn
- Airtable API
- Jupyter Notebook

## Dashboard KPIs

- Total Reviews Monitored
- Negative Reviews
- PMO Escalations
- Negative Sentiment Rate (%)

## Visualizations

- Average Rating by Streaming Partner
- Negative Reviews Trend Over Time
- Top Negative Issues by Topic
- PMO Review Queue

## Pipeline

Google Play Reviews -> Python Scraper -> Sentiment Model -> Topic Detection -> Airtable -> Dashboard

## Notes

This project was built as a partner sentiment and ecosystem analytics workflow for streaming platform monitoring.