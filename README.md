# Comment-Classifier
A machine learning system which takes a comment as an input and ranks it as offensive or non-offensive (neutral). To measure its effectiveness, the following classification algorithms were used: Naive Bayes, SVM and Random Forest.

### Libraries
1. NumPy 
2. Pandas
3. scikit-learn

### Input
A data set with 6182 comments, extracted from mulitple online platforms like Youtube, Twitter etc...

### Procedure

* #### Preprocess and Text-Cleaning.

* #### Split data (train & test).

* #### Train data with the procedure of k-fold cross validation, under the following classification algorithms: 
  1. Naive Bayes
  2. SVM
  3. Random Forrest

* #### Use test data to evaluate algorithms.

* #### Experimented with TF-IDF (term frequency-inverse document frequency) and POS (parts of speech).

* #### Improvements
  1. Lemmatization
  2. Stopwords
  3. Bigrams
  4. Laplace Smoothing


