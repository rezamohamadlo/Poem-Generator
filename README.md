# Shakespeare-Text-Generator

**Shakespeare-Text-Generator** is a text generation project using LSTM and n-grams to generate poetic text based on Shakespearean sonnets. This project leverages deep learning techniques to predict and generate the next words in a sequence, creating new lines of sonnets.

## Overview

This project uses a dataset of Shakespearean sonnets to train an LSTM-based neural network model for text generation. The model is trained to predict the next word in a sequence and can generate extended text based on an initial seed phrase.

## Features

- **Text Generation**: Generate poetic text based on the seed text using a trained LSTM model.
- **N-Gram Sequences**: Create and use n-gram sequences for training the model.
- **Model Training**: Train an LSTM model on the sonnet dataset and evaluate its performance.
- **Visualization**: Plot training accuracy and loss to monitor model performance.

## Getting Started

### Prerequisites

Ensure you have the following Python libraries installed:

- TensorFlow
- NumPy
- Matplotlib
- Google Colab (for downloading files)

You can install the necessary libraries using pip:

```bash
pip install tensorflow numpy matplotlib gdown
