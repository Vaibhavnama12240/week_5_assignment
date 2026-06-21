# Text Generation using Vanilla RNN, LSTM, and GRU

## Overview

This project implements and compares three recurrent neural network architectures—Vanilla RNN, LSTM, and GRU—for text generation. The models are trained on a text corpus to learn language patterns, contextual relationships, and sequential dependencies, enabling them to generate meaningful text sequences.

## Objectives

* Implement Vanilla RNN, LSTM, and GRU models.
* Train the models on a text corpus.
* Generate text sequences using trained models.
* Compare model performance based on training loss, memory handling, and generated text quality.

## Methodology

1. Load and preprocess the text corpus.
2. Tokenize the text and create input-output sequences.
3. Build and train:

   * Vanilla RNN
   * LSTM
   * GRU
4. Generate text using a seed sequence.
5. Compare model performance.

## Hyperparameters

* Embedding Dimension: 200
* Hidden Units: 128
* Epochs: 200
* Optimizer: Adam
* Loss Function: Categorical Crossentropy

## Results

| Model       | Training Loss | Memory Handling | Long-Term Dependency Learning | Text Quality |
| ----------- | ------------- | --------------- | ----------------------------- | ------------ |
| Vanilla RNN | Higher        | Poor            | Weak                          | Moderate     |
| LSTM        | Lowest        | Excellent       | Strong                        | Best         |
| GRU         | Near Lowest   | Good            | Strong                        | Very Good    |

## Conclusion

The experimental results show that LSTM performs best in terms of learning contextual information and long-term dependencies. GRU provides comparable performance with lower computational complexity, while Vanilla RNN struggles with long-range dependencies due to the vanishing gradient problem.

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib

## Author

Vaibhav Nama
