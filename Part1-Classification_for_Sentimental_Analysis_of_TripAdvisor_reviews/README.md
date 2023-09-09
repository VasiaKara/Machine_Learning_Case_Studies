# Part1-Classification_for_Sentimental_Analysis_of_Trip_Advisor_Reviews

In the jupyter notebook we implement a complete sentiment analysis on tripadvisor_hotel_reviews dataset.

Project's Milestones
- Data Presprocessing
  - Check for missing values
  - Discard neutral comments and merge very positive/ positive and very negative/negative messages
  - Check for imbalance in the data
  - Remove punctuation marks
  - Remove stopwords (common english words such as a, an, the etc)
  - Lemmatization, Stemming, Vectorization(Count Vectorizer, tf-idf Vectorizer)
  - Split train and test (and then handle the imbalance detected above)
- Fit models
  - Logistic Regression
  - SVM
  - Naive Bayes
  - Random Forest
  - Boosting
  - Multilayer Perceptron
  ** We apply every model to each of the above three different vectorized data     
- Compare results for every model per vectorizer
