# yelp-fraudulent-reviews
Analysis and model building for detecting fraudulent reviews on the Yelp Dataset.

In this repository are contained the code for the models tested. We tested both traditional statistical learning models, as well as used transfer learning to build a transformer based classifier, with the transformer being already pretrained.

The traditional models chosen are: logistic regression, naive bayes, and random forest. All models were tested with both count based text embeddings (TFIDF) as well as vector representation (Doc2Vec).

For the transformer based classifier was built by importing the already pretrained BERT backbone layers from the HuggingFace library (bert-base-uncased). The classifier is composed of two linear layers.

The data has been downsampled to account for class imbalance.
