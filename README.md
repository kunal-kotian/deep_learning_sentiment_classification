# A TensorFlow walk-through on using LSTMs to classify sentiment

## Introduction

The tutorial/walk-through on LSTM is here:  
https://github.com/kunal-kotian/deep_learning_sentiment_classification/blob/master/model/sentiment_classifier.ipynb

The notebook above is intended to be a tutorial providing a walk-through and explanation of the steps required to build a variable length sequential input recurrent model in TensorFlow.  

The tutorial covers:  
* Minimal text preprocessing
* Using word embeddings (GloVe)
* TensorFlow?s Dataset API for batching and loading data
* Efficient handling of variable length input

The dataset used in the tutorial consists of Yelp restaurant reviews which are:
* Polarized (1 or 2 stars = negative; 5 stars = positive)
* 400 to 500 characters per review

All steps followed for preprocessing the dataset used in this tutorial can be found in the notebook at:  
https://github.com/kunal-kotian/deep_learning_sentiment_classification/blob/master/filter/filtering_reviews.ipynb

Running the notebook at the link above will help you generate the file `reviews_labeled.feather` used in the `sentiment_classifier` notebook.

