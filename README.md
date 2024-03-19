# vanilla-rnn from scratch

1. We first create a simple RNN from scratch. The loss functions, and activation functions are customizable new loss and activations can be created by subclassing. Backpropagation through time is implemented modularly.

  The forward and backward flow for a cell is as follows: 
  
<img width="450" alt="image" src="https://github.com/samarthsingla/rnn-from-scratch/assets/25768584/1e7d5e77-08ef-4e29-b12e-f5ccdf02ed25">

2. Then I use this to model Open, Low, High prices of GOOGL for the year 2021 and 2022.
The results are as follows:

<img width="450" alt="image" src="https://github.com/samarthsingla/rnn-from-scratch/assets/25768584/f9eb3797-60f6-47c7-a8af-3b290698f83e">

Due to limited training and shortcomings of RNN (failure to model long range dependencies etc.) the predictions are not up to the mark, although they do model the trend broadly for all the signals.
We may try using LSTMs and GRUs for predicting these prices and hope to see improvements.

