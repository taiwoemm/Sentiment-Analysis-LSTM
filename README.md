# Sentiment-Analysis-LSTM
This notebook describes the implementation of a recurrent neural network (long-short-term memory) that performs sentiment analysis. 

>Using an RNN rather than a strict feedforward network is more accurate since we can include information about the *sequence* of words. 

A dataset of movie reviews was used, accompanied by sentiment labels: positive or negative.

The architecture for this network is shown below:

>**First, the words are passed to an embedding layer.**
>
>**After input words are passed to an embedding layer, the new embeddings is passed to LSTM cells.**
>
>**Finally, the LSTM outputs will go to a sigmoid output layer.**

The loss is calculated by comparing the output of the last sigmoid layer at the last time step and the training label (pos or neg).

The project was completed as part of the Deep Learning with PyTorch on Udacity
