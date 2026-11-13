# RNN-Question-Answer-Prediction

# RNN Question Answer Prediction using PyTorch

## Project Overview
This project implements a simple Question Answer Prediction system using a Recurrent Neural Network (RNN) with PyTorch.

The model takes a question as input and predicts an answer word based on the learned vocabulary.

## Technologies Used
- Python
- PyTorch
- Pandas
- NumPy

## Model Architecture
The model consists of three main layers:

1. **Embedding Layer** – Converts word indices into dense vectors.
2. **RNN Layer** – Processes the input sequence and learns sequential patterns.
3. **Fully Connected Layer** – Predicts the answer token from the vocabulary.

## Workflow
1. Load and preprocess the dataset.
2. Build a vocabulary.
3. Convert text into numerical token indices.
4. Create a custom PyTorch Dataset and DataLoader.
5. Train the RNN model.
6. Predict answers using the trained model.

## Training
- Model: Simple RNN
- Embedding Dimension: 50
- Hidden Size: 64
- Epochs: 50
- Loss Function: Cross Entropy Loss

## Prediction
The model accepts a text question and predicts an answer using the trained RNN model.

## Future Improvements
- Improve prediction accuracy.
- Support multi-word answer generation.
- Train with a larger dataset.
- Experiment with LSTM and GRU architectures.

## Author
Shakowat Hassan Tasin
