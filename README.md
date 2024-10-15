# team1-ADS505
Applied Data Science for Business

Skincare Review Analysis and User Clustering
This project analyzes a dataset of skincare product reviews. It preprocesses and cleans the data, applies sentiment analysis to the reviews, groups products and users based on review content, and finally uses machine learning to predict which cluster users belong to, based on their reviews.

Project Workflow
1. Data Collection
The dataset consists of reviews for skincare products, including information about the product, review content, user demographics, and more.
2. Data Preprocessing and Cleaning
The review data is cleaned by:
Removing special characters, numbers, and stopwords.
Normalizing text (lowercasing).
Handling missing or null values.
3. Sentiment Analysis
Sentiment analysis is performed on the review text using TextBlob to assign a sentiment polarity score to each review.
This score helps determine the overall sentiment (positive, neutral, or negative) of the review content.
4. Product Grouping Based on Reviews
Reviews are grouped by product, and the sentiment score of reviews is aggregated to understand how different products are perceived by users.
5. User Grouping Based on Reviews
Users are grouped by their review behavior, using their review content to cluster them into distinct groups. This clustering helps identify patterns in how different users review products.
6. Predicting User Clusters Using Naive Bayes
A Naive Bayes classifier is implemented to predict which cluster a user belongs to, based on the content of their reviews. This helps provide insights into user preferences and potential product recommendations.
