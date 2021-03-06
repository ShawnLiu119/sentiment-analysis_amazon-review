# Sentiment Analysis - Amazon Review

**Data**

The data used for this analysis is a set of product reviews on the Mr. Coffee 12 Cup Programmable Coffee Maker.The data collected spans from 2017 to present, with 6,789 reviews and 7,221 global ratings. Each review is received from a customer that has purchased the product previously who gives their opinion on the product for others to review. Each rating is based on a 5-star scale, resulting in all the ratings to be ranged from 1-star to 5-star with no half or quarter stars. The fields include Profile Name, Review, Datetime, and Rating as shown in the table below.

![image](https://user-images.githubusercontent.com/43327902/147958242-1cb6bff0-bc28-4c1f-b0a2-7f392c236547.png)


**Model**

Basically, I used multiple tokenizer(including TFIDF and spaCy) to extract features from the cleaned data and feed the processed data into ML and deep learning classification models (including Logistic Classification, RandomForest, CNN and RNN). Here is the general process
![image](https://user-images.githubusercontent.com/43327902/147958661-c7a19ed1-2266-4cb8-95e0-1d0744e8dc45.png)


