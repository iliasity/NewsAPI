# NewsAPI
We're getting a large chunk of our information from https://www.newscatcherapi.com/!

Train Sentiment Analysis: Dutch vs. French Railway Markets

Project Overview

This project investigates how the sentiment of travelers in the Dutch closed-access railway market and the French open-access railway market influences their choice of transportation: flight, bus, or train. We analyze publicly available traveler reviews, social media comments, and transport-related news articles to uncover sentiment patterns.

Research Question

How does the sentiment of travelers in the Dutch closed-access railway market and the French open-access railway market influence their choice of taking a flight, bus, or train?

Objectives

Compare sentiment trends between the Dutch and French railway markets.

Analyze how sentiment impacts travelers’ preferences for trains, buses, or flights.

Provide data-driven insights on improving customer experience in railway transport.

Data Sources

NewsCatcher API (news articles related to public transport)

Public transport forums and reviews

Social media platforms

Methodology

Data Collection: Use NewsCatcher API and web scraping tools to gather relevant transport sentiment data.

Sentiment Analysis: Apply Natural Language Processing (NLP) models to classify and analyze sentiment.

Comparative Analysis: Contrast results from Dutch and French railway market contexts.

Tech Stack

Languages: Python (for data processing and analysis)

Libraries: Pandas, NLTK, SpaCy, scikit-learn

APIs: NewsCatcher API, social media APIs (if applicable)

Tools: Jupyter Notebook, GitHub for version control

Why This Matters

Understanding how sentiment shapes transport decisions can guide policymakers and transport companies in designing better services and reducing reliance on less sustainable transport modes.

Repository Structure

├── data               # Raw and processed datasets
├── notebooks          # Jupyter notebooks with analysis code
├── src                # Source code for data processing and analysis
├── reports            # Generated reports and visualizations
├── README.md          # Project overview and setup instructions
└── LICENSE            # License information

How to Use This Repository

Clone the repository:

git clone https://github.com/yourusername/train-sentiment-analysis.git

Install dependencies:

pip install -r requirements.txt

Run the analysis:

jupyter notebook

