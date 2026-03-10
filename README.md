# Sentiment Analysis of Movie Reviews using BERT

## Overview

This project implements a **Sentiment Analysis classifier** that predicts the emotional tone of movie reviews using **BERT (Bidirectional Encoder Representations from Transformers)**.

The model classifies movie reviews into sentiment categories such as:

- Positive
- Negative
- Neutral

Sentiment analysis helps understand opinions expressed in text and is widely used in many real-world applications.

---

## Applications

Sentiment analysis is commonly used in:

- Product review analysis  
- Social media monitoring  
- Customer feedback analysis  
- Recommendation systems  

---

## Example

| Input Review | Predicted Sentiment |
|--------------|---------------------|
| The movie was amazing and exciting | Positive |
| The movie was boring and slow | Negative |
| The movie was okay but nothing special | Neutral |

---

## Dataset

The project uses the **SetFit/sst5 dataset**.

### Dataset Details

- **SetFit** – A framework designed for few-shot text classification.
- **SST-5 (Stanford Sentiment Treebank)** – A dataset containing movie reviews labeled with **5 sentiment classes**.

---

## Technologies Used

### Programming Language
- Python

### Libraries
- HuggingFace Transformers
- PyTorch
- Pandas
- Scikit-learn

### Development Environment
- Google Colab

---

## Model Architecture

The project uses **BERT**, a transformer-based model that captures contextual relationships between words in a sentence.

### Key Components

#### Self-Attention Mechanism
Allows the model to focus on important words in a sentence.

#### Classification Layer

```
z = Wh + b
```

#### Softmax Layer
Converts model outputs into probability scores for each class.

#### Loss Function
Cross-Entropy Loss is used to optimize the classifier.

---

## Evaluation Metrics

Model performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Loss

---

## Comparison with Other Models

| Model | Accuracy |
|------|----------|
| Naive Bayes | ~75% |
| LSTM | ~82% |
| BERT | ~90% |
| RoBERTa | ~92% |

Transformer-based models achieve **state-of-the-art performance** for sentiment analysis tasks.

---

## Project Workflow

1. Load the SST-5 dataset  
2. Preprocess movie reviews  
3. Tokenize text using BERT tokenizer  
4. Fine-tune BERT model  
5. Train the sentiment classifier  
6. Evaluate using performance metrics  

---

## Results

The BERT model achieves significantly better performance than traditional machine learning models due to its ability to understand **context and semantic meaning in text**.

---

## Future Improvements

- Fine-tuning with larger datasets  
- Using **RoBERTa** or **DeBERTa** models  
- Hyperparameter optimization  
- Deploying the model as an API or web application  

---

## Author

**Nitin**

Course: Natural Language Processing  
Project: Sentiment Analysis Classifier
