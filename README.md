# Streaming Partner Health Dashboard

An end-to-end analytics and NLP pipeline that monitors Google Play Store reviews for streaming partners such as **Disney+** and **Max**.

The system ingests live reviews, applies **machine learning–based sentiment analysis and topic detection**, stores structured data in **Airtable**, and visualizes partner health metrics through a monitoring dashboard.

---

## Project Overview

This project simulates a **partner ecosystem monitoring platform**.  
User feedback from Google Play is automatically collected and analyzed to detect negative sentiment trends and operational issues affecting streaming partners.

The pipeline performs:

- Automated Google Play review scraping
- Machine learning sentiment classification
- NLP topic detection
- Structured ingestion into Airtable
- Dashboard visualization of partner health metrics

---

## Key Features

- Google Play review scraping for **Disney+** and **Max**
- Large-scale review dataset creation (20k reviews)
- **Random Forest NLP sentiment classification**
- **Topic detection** for issue categorization
- Airtable API integration
- Executive dashboard with KPIs and trend monitoring

---

## Tech Stack

- **Python**
- **Pandas**
- **Scikit-learn**
- **Google Play Scraper**
- **Airtable API**
- **Jupyter Notebook**

---

## Dashboard KPIs

The dashboard provides an executive overview of platform performance:

- **Total Reviews Monitored**
- **Negative Reviews**
- **PMO Escalations**
- **Negative Sentiment Rate (%)**

---

## Visualizations

The dashboard includes the following analytics views:

- **Average Rating by Streaming Partner**
- **Negative Reviews Trend Over Time**
- **Top Negative Issues by Topic**
- **PMO Review Queue**

These visualizations help quickly identify service disruptions and user-experience issues affecting streaming partners.

---

## Data Pipeline

Google Play Reviews
↓
Python Scraper
↓
Sentiment Model (Random Forest NLP)
↓
Topic Detection
↓
Airtable Data Layer
↓
Partner Health Dashboard


---

## Dashboard Preview

![Dashboard Preview](dashboard_screenshot.png)

---

## Notes

This project demonstrates how **machine learning, API integration, and analytics dashboards** can be combined to monitor partner ecosystem health and detect emerging issues from user feedback.
