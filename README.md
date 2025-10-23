# Android-Market-Analysis-Project
Exploratory Data Analysis (EDA) and Sentiment Analysis of the Google Play Store to reveal market trends, optimal app sizing, pricing strategies, and user review sentiment.
Android Market Data Analysis: Trends, Pricing, and User Sentiment

Project Overview

This project performs an in-depth Exploratory Data Analysis (EDA) and Sentiment Analysis on a dataset derived from the Google Play Store and corresponding user reviews. The goal is to uncover key market dynamics, determine effective strategies for app developers, and understand the relationship between factors like app size, price, downloads, and user satisfaction.

The analysis provides actionable insights into what drives app success in the competitive Android marketplace.

Key Findings

This analysis yielded several important conclusions about app performance and market strategy:

Average Rating: The average rating of active apps on the Google Play Store is 4.17.

Optimal Sizing: Most top-rated apps are optimally sized between ~2MB to ~40MB. Paid apps, in particular, are favored when they are light-weighted.

Pricing Strategy: Top-rated paid apps are typically priced between ~1$ to ~30$. Medical and Family apps were found to be the most expensive categories.

Downloads & Reviews: A moderate positive correlation of 0.63 exists between the number of reviews and the number of downloads, suggesting that higher review counts build trust and drive installs.

Sentiment Polarity: Users are notably more grim and harsh while reviewing free apps compared to paid apps, which generally receive more moderate feedback.

Technologies and Libraries

Language: Python

Core Libraries: pandas, numpy

Visualization: matplotlib, seaborn, plotly, wordcloud

Statistical Testing: scipy.stats (for ANOVA)
