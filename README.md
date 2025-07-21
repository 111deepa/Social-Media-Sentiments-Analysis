

# 📊 Social Media Sentiment Analysis Dashboard

https://github.com/111deepa/Social-Media-Sentiments-Analysis/blob/main/Social%20Media%20Sentiments/Dashboard/home.jpg

## 📌 Table of Contents

* [Introduction](#introduction)
* [Business Problem](#business-problem)
* [Objectives](#objectives)
* [Data Understanding](#data-understanding)
* [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
* [NLP Preprocessing](#nlp-preprocessing)
* [Sentiment Analysis](#sentiment-analysis)
* [Modeling](#modeling)
* [Power BI Dashboard](#power-bi-dashboard)
* [Recommendations](#recommendations)
* [Author](#author)

---

## Introduction

This project performs sentiment analysis on social media posts (Twitter, Instagram, Facebook) to understand public opinion and brand perception. The focus is to provide insights through interactive **Power BI dashboards**, especially from **Twitter** data.

---

## Business Problem

Brands often struggle to understand how users feel about them on social media. This project helps identify:

* How people react (Positive, Negative, Neutral)
* Which countries or platforms generate more engagement
* Overall trends and emotional response toward a brand

---

## Objectives

1. **Perform sentiment analysis** using Natural Language Processing (NLP)
2. **Create Power BI dashboards** to visualize sentiment by platform
3. **Extract key insights** from social media trends and user behavior

---

## Data Understanding

* **Source**: Dataset downloaded from **Kaggle**
* **Fields**: `ID',	'Entity',	'Text',	'Sentiment',	'Timestamp',	'User',	'Platform',	'Hashtags',	'Retweets',	'Likes',	'Country',	'Year',	'Month',	'Day',	'Hour',	'MainSentiment',	'Emotion',	'Cleaned_Text', 'Sentiment_Score',	'Sentiment_Predicted',	'Text_Length'
<img width="1891" height="25" alt="image" src="https://github.com/user-attachments/assets/bcaad9c4-9328-4aff-b6bf-6701e26120bd" />

* Platforms include **Twitter**, **Facebook**, and **Instagram**

---

## Exploratory Data Analysis (EDA)

EDA performed using:

* Distribution of Sentiments
* Platform-wise Sentiment Spread
* Country-wise Engagement
* Word Frequency and Length of Posts

---

## NLP Preprocessing

Performed the following preprocessing steps:

* Removing URLs, mentions, hashtags, emojis
* Tokenization
* Lowercasing
* Lemmatization
* Stopword Removal

---

## Sentiment Analysis

* Used **VADER Sentiment Analyzer**
* Labels: `Positive`, `Negative`, `Neutral`
* Sentiment applied across all platforms but focused on Twitter for dashboard

---

## Modeling (Optional)

* Model: Logistic Regression (Baseline)
* TF-IDF Vectorizer used for feature extraction
* Accuracy and confusion matrix analyzed

---

## Power BI Dashboard

Dashboard pages created:

1. **Twitter Dashboard**

   * Donut Chart: % of Sentiments
   * Bar Chart: Country-wise Sentiment Count
   * Line Chart: Sentiment Trend Over Time
   * KPI Cards: Total Posts, Likes, Retweets
   * Word Cloud: Common words in tweets

2. **Facebook & Instagram Dashboards**

   * Similar layout with platform-based filters

> **Filters used in each visual:**
> `Platform = Twitter` (or Instagram/Facebook accordingly)

> Word Cloud Visual:
> Insert from Power BI > Marketplace > Search "Word Cloud"

---

## Recommendations

* Track Twitter sentiment in real-time for customer support and PR.
* Compare sentiment across platforms for marketing insights.
* Use word cloud to identify trending topics and hashtags.
* Create alerts for spikes in negative sentiment.

---

## Author

**Deepa Kumari**
