# BERT Sentiment Analysis of Movie Reviews

This project implements a sentiment analysis classifier using the BERT transformer model.

## Problem
Automatically classify movie reviews into:
- Positive
- Negative
- Neutral

## Model
The model uses the **BERT (bert-base-uncased)** transformer architecture with a classification layer.

## Architecture
Pipeline:

Input Text  
↓  
Tokenizer  
↓  
BERT Encoder  
↓  
Classification Layer  
↓  
Sentiment Output

## Dataset
Movie review dataset with **3000 labeled reviews**.

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score


## Tools Used
- Python
- PyTorch
- HuggingFace Transformers
- Pandas
- Scikit-learn

