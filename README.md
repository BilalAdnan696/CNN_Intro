# TF-Sentiment-Analysis

Performed Sentiment analysis on the amazon mobile electronics dataset provided my tensorflow datasets.

For the preprcesing the data was tokenized sing tensorflow tokenizer and then it was split and fed into the model.
The model capacity is not that large it consisits of an embedding layer, bidirectional layers so that the gets a complete look at the reviews in both directions
the last layers consist of a dense layer and a sigmoid activation function because the required output is binary either 0 which determines that the review was negative 
or 1 which tells us that the review was positive
