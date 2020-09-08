# Toxic Words Challenge

Text comments can be harmful. The Toxic Words Challenge classifies each text into none/ some classes, such as "toxic", "severe_toxic", "obscene", "threat", "insult", "identity_hate".

#### Task

Build a neural network to identify the categories of the text. It is a multi-label classification challenge.

#### Dataset

The dataset consists of 159,571 observations. It was split into training and test sets (80-20 split). The training set was then split into training and validation set during model fitting (80-20 split).

## Results

Three different models were tried: 

1. LSTM
2. RNN
3. Convolutional 1D

These models performed similarly well. On the test set, these models gave an accuracy of 0.994.
