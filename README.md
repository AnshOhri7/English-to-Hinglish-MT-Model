# English-to-Hinglish-MT-Model
Welcome to the "English to Hinglish Machine Translation Model" repository! This project is your gateway to the exciting world of machine translation, focusing on converting English text into Hinglish.
There are 2 submissions in this Repository 

## **Submission 1**

# English to Hinglish Translation with 'Parallel corpus of English-Hindi sentence pairs' Dataset



## Overview
This Model focuses on building a Neural Machine Translation (NMT) system to translate English sentences to Hinglish.

## Features
Encoder-Decoder Architecture: The NMT system employs an encoder-decoder architecture, where the encoder encodes the input English sentence into a fixed-size context vector, and the decoder generates the corresponding Hindi translation from the context vector.

Attention Mechanism: To handle longer sentences and capture relevant information effectively, an attention mechanism is integrated. This allows the model to focus on different parts of the input sentence while generating the output.

Data Preprocessing: The project includes data preprocessing steps to clean and normalize input sentences, ensuring better alignment and accuracy in translation.

Training and Evaluation: The model is trained on a parallel corpus of English-Hindi sentence pairs. During training, the model learns to minimize the translation loss. The evaluation process demonstrates the model's translation quality with selected input sentences.

Visualization of Attention: The project offers a visualization of attention weights, showing how the model attends to different parts of the input during translation.

## Usage 
Data Preparation: Prepare your parallel corpus of English-Hindi sentence pairs. Ensure that your data is properly formatted and cleaned.

Model Configuration: Set up the encoder and attention-based decoder architecture in the code. Define the hyperparameters, such as hidden size, learning rate, and dropout rate.

Training: Train the model using the provided training functions. Adjust the number of training iterations, print intervals, and other parameters as needed.

Evaluation and Visualization: Evaluate the model's translation quality using the evaluateAndShowAttention function. Provide your English input sentences and observe both the translated output and attention visualization.

Dependencies
Python 3.x
PyTorch
Matplotlib

## **Submission 2**

# English to Hindi Translation with Hugging Face Transformers

## Overview

This project demonstrates how to perform English-to-Hindi translation using the Hugging Face Transformers library. It leverages the pre-trained "Helsinki-NLP/opus-mt-en-hi" model for accurate translations.

## Features

- Utilizes a machine translation model.
- Customizable translation parameters such as maximum length and beam search.

## Usage

1. Install the necessary dependencies:

   bash,
   transformers
