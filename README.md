# Sentiment-Analysis-LSTM
This notebook describes the implementation of a long-short-term memory (LSTM) that performs sentiment analysis. Using an LSTM rather than a strict feedforward network is more accurate as it captures information about the *sequence* of words. 

A dataset of movie reviews was used, accompanied by sentiment labels: positive or negative.

The architecture for this network is shown below:

>**First, the words are passed to an embedding layer.**
>
>**After input words are passed to an embedding layer, the new embeddings are passed to LSTM cells.**
>
>**Finally, the LSTM outputs will go to a sigmoid output layer.**

The loss is calculated by comparing the output of the last sigmoid layer at the last time step and the training label (pos or neg).

The project was completed as part of the Deep Learning with PyTorch course on Udacity.
