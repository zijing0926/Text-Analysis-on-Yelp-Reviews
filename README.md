# Text-Analysis-on-Yelp-Reviews
This project uses NLP to build models predicting Yelp star ratings based on text reviews. To process text data, this project uses Hash Vectorizer and later tries TFIDF Vectorizer including bigrams as the transformer. The estimator used here is Ridge. In order to make accurate predictions, this project uses GridSearchCV to find the best parameters for both the transformer and the estimator. Lastly, utilizing the Counter Vectorizer, this project also finds the 100 most common food bigrams, by calculating: p(w_1w_2)/p(w_1) * p(w_2)

Skills:
NLP, Machine Learning Pipeline, GridSearchCV, Ridge, Count Vectorizer, Hash Vectorizer, TFIDF Vectorizer
