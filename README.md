Sentiment Analysis using LSTM
This project implements a Sentiment Analysis model using Long Short-Term Memory (LSTM) neural networks in Python. The model classifies movie reviews as either positive or negative based on the text input.

📌 Project Overview
Sentiment analysis is a Natural Language Processing (NLP) technique used to determine whether textual data is positive, negative, or neutral. In this project, we use the IMDB dataset to train and evaluate an LSTM model that can learn context and patterns in textual reviews and classify their sentiment.

🧠 Model Architecture
Embedding Layer: Transforms word indices into dense vector representations.

LSTM Layer: Captures sequential dependencies in the text data.

Dense Layer: Outputs a binary classification (positive or negative).

🔍 Features
Data preprocessing (padding, tokenization)

LSTM network for sequence modeling

Binary classification (positive/negative sentiment)

Evaluation using accuracy and loss plots

📂 Dataset
IMDB Movie Reviews: Preprocessed dataset with 25,000 training and 25,000 testing samples.

The dataset is loaded via Keras (keras.datasets.imdb).
