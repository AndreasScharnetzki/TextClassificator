# TextClassificator

This notebook compares 25 differently tuned NLP models 
(based on logistic regression) and a binary decision tree regarding 
their efficiency to classify a given corpus whether 
the text is a recipe or not.

The idea was to identify what kind of preprocessing (stemmer vs. lemmatizer), 
vectorization (TF-IDF, count vectorization, binary vectorization) 
and regularization would result in the highest true-positive accuracy.
