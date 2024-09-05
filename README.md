# Shakespeare-Text-Generator
(This project has been as a programing assignment of course "Natural Language Processing in Tensorflow" in Coursera website.
## Overview

The **Shakespeare-Text-Generator** project is designed to generate text in the style of Shakespearean sonnets using a neural network model. By leveraging the power of Long Short-Term Memory (LSTM) networks, this project can generate coherent and stylistically similar text based on an initial seed input. The model is built using TensorFlow and Keras and includes components for data preprocessing, model training, and text generation.

## Key Components

1. **Data Download and Preprocessing:**
   - **`sonnets.txt`**: Contains a dataset of Shakespearean sonnets used for training the model.
   - Text data is processed by converting it to lowercase, tokenizing it into sequences, and creating n-gram sequences. Sequences are then padded to ensure uniform input size.

2. **Model Architecture:**
   - **Embedding Layer:** Converts integer word indices into dense vector representations.
   - **Bidirectional LSTM Layer:** Processes the input sequences in both forward and backward directions to capture context.
   - **Dense Layer:** Outputs a probability distribution over the vocabulary for each word position.

3. **Training:**
   - The model is trained for 50 epochs using categorical crossentropy loss and the Adam optimizer. Training metrics such as accuracy and loss are visualized to monitor performance.

4. **Text Generation:**
   - Given a seed text, the model generates subsequent text by predicting the next word in the sequence iteratively until the desired length is reached.

