# Text Classification

## Data
Train and test set can be accessed through dropbox (see jupyter notebook).

## Task
Predict movie genre based on plot summary.

## Data Processing

### Data Cleaning
1. Remove backslashes
2. Keep only english alphabets
3. Strip extra white spaces
4. Normalize text
5. Remove stopwords
6. Stemming

### Tf-Idf Vectorizer
Convert text to a matrix of TF-IDF features. For the parameters in the Tf-Idf Vectorizer, used english stopwords, set ngram_range to (1,2) and set max features to 150000.

## Models
Many models have been tried and two of them are reported.
1. (Multinomial) Logistic Regression
2. Stochastic Gradient Descent Classifier
