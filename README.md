# BERT_Spam_Detection-
Spam detection using BERT and the SMS Spam Collection dataset. The model is built with PyTorch and Hugging Face Transformers. The code includes data preprocessing, model training, evaluation, and predictions.


This project demonstrates how to build a spam detection model using BERT with PyTorch and the Hugging Face `transformers` library. The model is trained on the SMS Spam Collection dataset, a commonly used dataset for spam classification.

## Project Overview

The objective of this project is to create an effective spam detection system using BERT, a powerful transformer-based model. The notebook provided in this repository guides you through the process of loading the dataset, preprocessing the text, training the BERT model, evaluating its performance, and making predictions on new text samples.

## Dataset

The dataset used is the [Dataset Card for the SpamAssassin public mail corpus]([https://archive.ics.uci.edu/ml/datasets/sms+spam+collection](https://huggingface.co/datasets/talby/spamassassin)), which a selection of mail messages, suitable for use in testing spam filtering systems assembled by members of the SpamAssassin project. The dataset is available in a tab-separated format and is included in the repository.

Dataset Structure: Data Fields
- **label**: Indicates if the message is 'spam' or 'ham'.
- **group**: Categorized by SpamAssassin into categories: {'hard_ham', 'spam_2', 'spam', 'easy_ham', 'easy_ham_2'}.
- **text**: The normalized text of the message bodies.
- **raw**: The full binary headers and contents of messages.




## Features

- **Data Loading**: Download and extract the SMS Spam Collection dataset.
- **Data Preprocessing**: Encode labels, split data into training and test sets.
- **Model Training**: Train a BERT-based classifier using PyTorch and Hugging Face Transformers.
- **Evaluation**: Evaluate model performance using accuracy and classification report.
- **Prediction**: Make predictions on new SMS messages to classify them as spam or ham.
- **Model Saving and Loading**: Save and load the trained model and tokenizer for future use.

## Requirements

To run the code, you'll need the following Python libraries:

- `transformers`
- `torch`
- `sklearn`
- `pandas`

Install the required libraries using pip:

```bash
pip install transformers torch sklearn pandas

