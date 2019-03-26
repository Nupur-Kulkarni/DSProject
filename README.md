Star Rating Prediction using Yelp reviews

1. Pre-process the reviews to remove punctuation marks and stop words. Also, reviews are converted to lowercase.
2. Apply stemming to reviews.
3. Now, extract features from reviews.
    I have implemented this project using two approaches for extracting features out of Yelp reviews:
    1. TF-IDF approach that gives a feature vector of variable length
    2. Using word embeddings that gives feature vector of fixed length. This is done using Doc2Vec library of gensim.
4. Classify feature vectors to predict star rating. SVM and Logistic Regression classification algorithms have been used to compare classification accuracy of these two for this problem.
