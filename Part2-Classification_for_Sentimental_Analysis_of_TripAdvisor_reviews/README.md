# Part2-Classification for Sentimental Analysis of tripadvisor reviews

In the jupyter notebook we implement a complete sentiment analysis on greek_hotel_reviews and restaurant_reviews datasets. Considering the greek_hotel_reviews the data was collected by scraping the tripadvisor site https://www.tripadvisor.com.gr/ for hotels in Athens Greece or other location in Greece. While restaurant_reviews dataset was downloaded from the following site https://www.kaggle.com/damienbeneschi/krakow-ta-restaurans-data-raw .

For this NLP task we perform several algorithms. These algorithms are presented below:
- VADER knowledge based unsupervised model
- LogisticRegression
- KNeighborsClassifier
- GaussianNB
- RandomForestClassifier
- SVC
- Long Short-Term Memory (LSTM) – Keras Implementation
- AutoSklearnClassifier(from autosklearn.classification import AutoSklearnClassifier)
- Xgboost
- Bidirectional Encoder Representations from Transformer BERT.

To perform the above algorithms, the data had previously been vectorized by TFIDF (term frequency, inverse document frequency) vectorizer.

This repo contains the correspondings jupyter notebooks along with the final report.

