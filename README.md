# Sentiment Analysis Using Recurrent Neural Network (RNN)

## Project Description

This project implements a simple Recurrent Neural Network (RNN) for binary sentiment analysis on text. Its primary goal is to classify reviews or other text snippets as either **positive** or **negative** sentiment. The model is trained on a dataset of text reviews and is designed to understand linguistic nuances to make accurate sentiment predictions.

Sentiment analysis is a crucial field within Natural Language Processing (NLP) that enables the automatic understanding of opinions and emotions expressed in textual data. Its practical applications are vast, ranging from brand monitoring and customer feedback analysis to market research.

## Features

* **Binary Sentiment Classification:** Classifies input text into 'Positive' or 'Negative'.
* **Text Preprocessing:** Involves tokenization, stop word removal, and sequence padding to prepare text data for the model.
* **RNN Model:** Builds and trains a Recurrent Neural Network model using TensorFlow/Keras, leveraging RNN's ability to process sequential data.
* **Easy Inference:** A straightforward interface to test sentiment on new sentences.

## Requirements

Ensure you have the following dependencies installed:

* Python 3.x
* TensorFlow / Keras
* NumPy
* Pandas
* NLTK (for text preprocessing)

You can install all necessary dependencies using `pip`:

```bash
pip install tensorflow numpy pandas nltk

import nltk
nltk.download('stopwords')
# nltk.download('punkt') # Optional, if using NLTK's tokenizer
