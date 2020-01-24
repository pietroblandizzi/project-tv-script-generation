# project-tv-script-generation
Generate tv-scripts using an RNN from the Seinfeld dataset.
The project from Udacity Deep Learning Nano degree consists in the implementation of data processing and RNN model to generate a tv script. The dataset used is the Seinfeld dataset.

There is an **LSTM** as well as a **GRU**

## Language and dependenies
The code is written in python.
It requires: python >= 3.0
pytorch
numpy
matplotlib


## How to run: 

The code is written in a ipynb file so it can be run from Jupyter notebook.

There are 3 pre_trained models that can be loaded:
1. trained_rnn.pt: LSTM with 256 hidden units / 2 layers / embedded dim = 300
2. trained_rnn_512.pt: LSTM with 512 hidden units / 2 layers / embedded dim = 300
3. trained_rnn_gru.pt: GRU with 256 hidden units / 2 layers / embedded dim = 300
