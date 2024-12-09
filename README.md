# Sequence Tagging on Penn Treebank dataset
## Dataset
The Treebank corpora provide a syntactic parse for each sentence. The NLTK data package includes a 10% sample of the Penn Treebank (in treebank). This dataset was used for the purpose of performing Sequence Tagging.

## Objective
Perform Sequence tagging on the treebank dataset to achieve an accuracy above 90%.

## Methodology
LSTM model was trained to learn the sequence tags on the training dataset. This model was then used to predict sequence tags on the test set.

It was observed that batch normalization and dropout layer were required after input and hidden layers to reduce overfitting on the training data.

Finally the model was evaluated on the test set.
