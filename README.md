Introduction

The aim of the work is to learn sequence to sequence (seq2seq) models. Introduced for the first time in 2014 by Google, a sequence to sequence model aims to map a fixed-length input with a fixed-length output where the length of the input and output may differ. From the high-level view, a seq2seq model has encoder, decoder and intermediate step as its main components. The class tutorial shows an excellent example of a minimalistic implementation of seq2seq model. The goal of the homework is to make this model efficient using batches and analyze the models' performance.

The overall architechture of the class tutorial was kept which is uses a single LSTM layer with one direction on both the encoder and decoder. Two models were designed. One with attention and another without attention. Both models works with batches of input. The model with attention achieved 98.80% accuracy on test test.

Dataset

The task uses a toy dataset from automatically-generated data. It has 20000 records for training and 5000 for validation. The test dataset of 2000 records are fixed (provided in a text file: test.txt). The test dataset is different in terms of length of input and output compared to training and validation dataset


Results:

--model.pt--

The best model with attention (model.pt) is trained on CPU.
'device' is set to 'cpu' at notebook

--model-1.pt--

Model with no-attention (model-1.pt) is trained on CPU.
'device' is set to 'cpu' at notebook

