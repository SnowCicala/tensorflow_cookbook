## [Ch 7: Natural Language Processing](#ch-7-natural-language-processing)

 1. [Introduction](01_Introduction)
  * We introduce methods for turning text into numerical vectors. We introduce the TensorFlow 'embedding' feature as well.
 2. [Working with Bag-of-Words](02_Working_with_Bag_of_Words)
  * Here we use TensorFlow to do a one-hot-encoding of words called bag-of-words.  We use this method and logistic regression to predict if a text message is spam or ham.
 3. [Implementing TF-IDF](03_Implementing_tf_idf)
  * We implement Text Frequency - Inverse Document Frequency (TFIDF) with a combination of Sci-kit Learn and TensorFlow. We perform logistic regression on TFIDF vectors to improve on our spam/ham text-message predictions.
 4. [Working with CBOW](04_Working_With_Skip_Gram_Embeddings)
  * Our first implementation of Word2Vec called, "skip-gram" on a movie review database.
 5. [Working with Skip-Gram](05_Working_With_CBOW_Embeddings)
  * Next, we implement a form of Word2Vec called, "CBOW" (Continuous Bag of Words) on a movie review database.  We also introduce method to saving and loading word embeddings.
 6. [Implementing Word2Vec Example](06_Using_Word2Vec_Embeddings)
  * In this example, we use the prior saved CBOW word embeddings to improve on our TF-IDF logistic regression of movie review sentiment.
 7. [Performing Sentiment Analysis with Doc2Vec](07_Sentiment_Analysis_With_Doc2Vec)
  * Here, we introduce a Doc2Vec method (concatenation of doc and word emebeddings) to improve out logistic model of movie review sentiment.
