## Transformers
# Transformer-based Text Processing with Hugging Face

This repository contains two Jupyter notebooks that demonstrate the use of Hugging Face's Transformers library for text processing tasks, including sequence classification and working with various transformer models.

## Contents

- **Working.ipynb**: A detailed guide on using the `AutoTokenizer` and `TFAutoModelForSequenceClassification` classes from the Hugging Face Transformers library.
- **Transformers.ipynb**: An overview of the Hugging Face Transformers library features and how to use its pre-trained models for various Natural Language Processing (NLP) tasks, including sentiment analysis, text generation, and more.

## Basic Architecture

The general architecture of the transformer models used in these notebooks can be understood in the following way:



## Encoding and Decoding Architecture

Transformers leverage an encoder-decoder architecture, where:

- **Encoder**: Processes the input text by converting it into a set of key-value pairs, enabling the model to understand the context and meaning.
- **Decoder**: Uses the encoded information to generate or classify the output.



## Notebook Descriptions

### 1. Working.ipynb

This notebook provides a hands-on guide to using the `AutoTokenizer` and `TFAutoModelForSequenceClassification` classes:

- **AutoTokenizer**: Automatically selects the appropriate tokenizer for a given model. It converts raw text into token IDs, attention masks, and other inputs required by the model.
- **TFAutoModelForSequenceClassification**: A TensorFlow model class for sequence classification tasks, such as sentiment analysis.

The notebook covers:

- Loading a pre-trained tokenizer.
- Tokenizing text inputs.
- Batch tokenization.
- Decoding tokens back into text.

### 2. Transformers.ipynb

This notebook introduces various features of the Hugging Face Transformers library, including:

- **Sentiment Analysis**: Classify whether a text is positive or negative.
- **Text Generation**: Generate text based on a provided prompt.
- **Named Entity Recognition (NER)**: Label each word in a sentence with its corresponding entity.
- **Question Answering**: Extract answers from a given context based on a question.
- **Summarization**: Generate summaries of long texts.
- **Translation**: Translate text from one language to another.

