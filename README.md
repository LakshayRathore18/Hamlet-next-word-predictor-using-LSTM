# Hamlet Next Word Predictor using LSTM

## Overview

A Deep Learning NLP project that predicts the next word in a text sequence using an LSTM model trained on Shakespeare's *Hamlet* from the NLTK Gutenberg Corpus. The project also includes a Streamlit web application for real-time predictions.

## Features

* Next-word prediction using LSTM
* Trained on Shakespeare's *Hamlet*
* Streamlit-based user interface
* Saved model and tokenizer for inference

## Live Demo

🔗 [Hamlet Next Word Predictor](https://hamlet-next-word-predictor-using-lstm-7tmnzsdrzkdvhv9bgwwnjt.streamlit.app/)

## Tech Stack

* Python
* TensorFlow / Keras
* NLTK
* NumPy
* Streamlit

## Model Architecture

* Embedding Layer
* LSTM (150 units)
* Dropout (0.2)
* LSTM (100 units)
* Dense + Softmax Output

## Usage

Run the Streamlit app:

```bash
streamlit run app.py
```

## Project Structure

```text
├── app.py
├── train.py
├── next_word_lstm.h5
├── tokenizer.pickle
├── requirements.txt
└── README.md
```

## Author

Lakshay Rathore