# Sentiment-Analysis-LSTM
This notebook describes the implementation of a recurrent neural network (long-short-term memory) that performs sentiment analysis. 

>Using an RNN rather than a strict feedforward network is more accurate since we can include information about the *sequence* of words. 

Here we'll use a dataset of movie reviews, accompanied by sentiment labels: positive or negative.

The architecture for this network is shown below.

>**First, we'll pass in words to an embedding layer.**
>
>**After input words are passed to an embedding layer, the new embeddings will be passed to LSTM cells.**
>
>**Finally, the LSTM outputs will go to a sigmoid output layer.**

We'll calculate the loss by comparing the output of the last sigmoid layer at the last time step and the training label (pos or neg).
