# Project Title: Sentiment Analysis with CNN-LSTM

Description:
This repository contains a sentiment analysis model built using a Convolutional Neural Network (CNN) and Long Short-Term Memory (LSTM) network. The model is trained on a dataset from Kaggle and is capable of classifying text as positive, negative, or neutral.

Dataset:
The dataset used for this project is sourced from Kaggle. It consists of text data and corresponding sentiment labels.

Data Preprocessing:

Data Cleaning: Removed noise, such as HTML tags, special characters, and extra whitespace.
Tokenization: Split text into individual words.
Padding: Ensured sequences have a fixed length for model input.
Word Embedding: Converted words into numerical representations using a pre-trained word embedding model (GloVe).
Model Architecture:
The model architecture consists of the following layers:

Embedding Layer: Maps words to dense vectors.
Convolutional Layer: Extracts local features from the sequence.
Max Pooling Layer: Reduces dimensionality and captures the most important features.
LSTM Layer: Captures long-range dependencies in the text.
Dense Layer: Performs classification.
Model Training:

Hyperparameter Tuning: Experiment with different hyperparameters to optimize performance.
Training: Train the model on the preprocessed dataset using an appropriate loss function  and optimizer (e.g., Adam).
Model Evaluation:

Evaluation Metrics: Calculate accuracy, precision, recall, and F1-score to assess the model's performance.
Confusion Matrix: Visualize the model's predictions and true labels to understand its strengths and weaknesses.
Real-world Application:
The trained model can be used for various real-world applications, including:

Product Reviews Analysis: Analyze customer reviews to identify product strengths and weaknesses.
Social Media Sentiment Analysis: Monitor public opinion on brands or products.
Customer Feedback Analysis: Understand customer feedback to improve products and services.
