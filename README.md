# Sentiment Analysis | Amazon Reviews

## Introduction
Everyday we come across various products in our lives, on the digital medium we swipe across hundreds of product choices under one category. It will be tedious for the customer to make selection. Here comes 'reviews' where customers who have already got that product leave a rating after using them and brief their experience by giving reviews. As we know ratings can be easily sorted and judged whether a product is good or bad. But when it comes to sentence reviews we need to read through every line to make sure the review conveys a positive or negative sense. In the era of artificial intelligence, things like that have got easy with the Natural Langauge Processing(NLP) technology.

## What is sentiment analysis?
Sentiment Analysis is the most common text classification tool that analyses an incoming message and tells whether the underlying sentiment is positive, negative our neutral.Understanding people’s emotions is essential for businesses since customers are able to express their thoughts and feelings more openly than ever before.It is quite hard for a human to go through each single line and identify the emotion being the user experience.Now with technology, we can automatically analyzing customer feedback, from survey responses to social media conversations, brands are able to listen attentively to their customers, and tailor products and services to meet their needs.

## Problem statement
This is the Problem Statement given by AI Variant to classify the customer comments. This would be helpful for the organization to understand Customer feedbacks.

Webportals like Amazon get vast amount of feedback from the users. To go through all the feedback's can be a tedious job. You have to categorize opinions expressed in feedback forums. This can be utilized for feedback management system. We Classification of individual comments/reviews.and we also determining overall rating based on individual comments/reviews. So that company can get a complete idea on feedback's provided by customers and can take care on those particular fields. This makes more loyal Customers to the company, increase in business, fame ,brand value ,profits.

## Objectives of Project
1. Reviews Preprocessing and Cleaning
2. Story Generation and Visualization from reviews
3. Extracting Features from Cleaned reviews
4. Model Building: Sentiment Analysis

## Dataset
We have extracted data from amazon website for the product 'Alexa-Echo dot' using Beautiful Soup.<br>
Goto: https://github.com/ms-jayanth/Web-Scrapping-using-BeautifulSoup

Our dataset:
https://drive.google.com/file/d/1ctlJRkDr6H9XHiiYm6s6cwQlfIl42XXT/view?usp=sharings

## Conclusion
We have done a pretty neat job on classifying all the classes starting from splitting the sentiments based on overall score,text cleaning, customize the stopwords list based on requirement and finally handling imbalance with smote. Here are few insights from the notebook.
<br>
- Consider welcoming ngram in sentiment analysis as one word can't give is proper results and stop words got to be manually checked as they have negative words. It is advised to avoid using stop words in sentiment analysis
- Most of our neutral reviews were actual critic of product from the buyers, so amazon can consider these as feedback and give them to the seller to help them improve their products
- Most of the reviews in this dataset were about quality of audio.
- Balancing the dataset got me a very fruitful accuracy score. Without balancing, I got good precision but very bad recall and inturn affected my f1 score. So balancing the target feature is important
- In sentiment analysis, we build models using various ML algorithms and concentrate on our f1 score where we got an average of 91% by SVM which was the best among all.
