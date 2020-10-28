# Amazon Reviews Summarization
Before you buy any item on amazon, you definetly check what the reviews say about the product. Most often than not, the reviews are long with a lot of unnecessary details.
In this project, we take these long and inconclusive reviews and return a 5 word summary that tells you the main jist of the entire review.
## Implementation
The data was first cleaned and pre-processed. The entire dataset was then divided into training and testing data. Each of these sets were tokenized. 
An RNN was implemented using LSTMs as the layers. A sequence to sequence model with an encoder-decoder implementation was used. 
After training the model on the training set, it was run on the testing set in the inference mode to get summaries of new reviews.
