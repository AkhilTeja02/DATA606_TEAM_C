# DATA606_TEAM_C
## Tittle: Sentiment Analysis and Trend Detection in Social Media Data


### What is it about? ​

This project explores the use of sentiment analysis and trend detection techniques on social media data in various domains among them we chose finance and healthcare.

### why this project is choosen ?

Gain insights from social media - Social media platforms provide a vast amount of user-generated data reflecting public opinion and sentiment. Analyzing this data can offer valuable insights into various topics.​

### Research question: ​

*Finance Domain*: Can sentiment analysis of social media posts about specific companies (Tesla, Nvidia, Apple) combined with financial data from Yfinance predict stock price movements for the following day?​

*Healthcare Domain*: Can NLP techniques be used to identify potentially signaling posts of anxiety and depression on social media platforms?​

The rapid proliferation of social media platforms has transformed the landscape of data analysis, providing an unprecedented opportunity to gain insights into various domains, including finance and healthcare. This project focuses on leveraging sentiment analysis and trend detection techniques on social media data sourced from Reddit to tackle significant challenges in these fields.

Predicting stock price movements remains a central challenge in finance. Traditional methods rely heavily on historical data and technical indicators, often neglecting real-time sentiment from social media platforms. Our goal was to improve stock price prediction accuracy by integrating sentiment analysis from Reddit posts with financial data. Specifically, we aimed to predict the movements of companies like Tesla, Nvidia, and Apple based on user sentiment expressed on related subreddits. Our results demonstrated that integrating sentiment data significantly enhanced stock movement predictions.

In healthcare, detecting signals of anxiety and depression from social media posts presents another significant challenge. Existing research primarily focused on specific aspects such as suicide risk or support seeking, often overlooking language patterns and community-specific contexts. Our aim was to develop a methodology combining sentiment analysis, linguistic pattern analysis, and topic modeling to accurately detect signals of anxiety and depression from Reddit posts in relevant subreddits like r/anxiety, r/depression, and r/mentalhealth. Our classification model achieved an impressive F1 score of 0.91 in accurately identifying posts indicative of depression or anxiety.

Previous research in finance predominantly relied on time series analysis methodologies like ARIMA/SARIMA for financial forecasting. While insightful, these methods often struggle to capture real-time sentiment dynamics. Similarly, existing healthcare literature lacked granularity in distinguishing between mental health conditions and communities, hindering signal detection accuracy. Our approach bridges these gaps by integrating sentiment analysis with advanced machine learning techniques.

The dataset comprises Reddit posts from finance-related subreddits (Tesla, Nvidia, Apple) and healthcare-related subreddits (r/anxiety, r/depression, r/mentalhealth, r/socialanxiety). The finance dataset spans from January 1, 2023, to February 14, 2024, with approximately 350,672 posts, while the healthcare dataset covers September 1, 2023, to February 14, 2024, with around 156,400 posts. Each post includes attributes such as name, created_utc, id, score, subreddit, title, and selftext, forming the basis of our analyses.
