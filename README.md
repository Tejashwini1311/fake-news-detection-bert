# Fake News Detection using BERT

## Problem Statement
Fake news spreads quickly on the internet and can mislead people.  
The aim of this project is to build a machine learning model that can classify news articles as **Fake** or **Real** using Natural Language Processing techniques.

## Dataset
In this project, the FA-KES dataset was used.  
The dataset contains news articles along with labels indicating whether the news is fake or real.

The dataset includes:
- Article title
- Article content
- Source
- Date
- Label

## Approach
The following steps were performed in this project:

1. Loaded and explored the dataset
2. Combined article title and article content into one text column
3. Tokenized the text using a pretrained BERT tokenizer
4. Split the dataset into training and validation sets
5. Fine-tuned a pretrained BERT model for text classification
6. Evaluated the model using different evaluation metrics

## Model Used
The model used in this project is **bert-base-uncased**, a pretrained transformer model available in the Hugging Face Transformers library.

BERT (Bidirectional Encoder Representations from Transformers) is widely used for Natural Language Processing tasks such as text classification, sentiment analysis, and question answering.

## Evaluation Metrics
The model performance was evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The results were displayed using a classification report and confusion matrix.

## Error Analysis
Some predictions were incorrect because certain news headlines contain strong or sensational words that are often seen in fake news.  
This caused the model to sometimes classify real news as fake or fake news as real.

## Model Improvement
The model performance can be improved in several ways:

- Training the model for more epochs
- Tuning the learning rate
- Handling class imbalance in the dataset
- Comparing the results with other transformer models like DistilBERT

## Key Learnings
Through this project I learned:

- How to work with real-world NLP datasets
- How tokenization works in transformer models
- How to fine-tune a pretrained BERT model using Hugging Face Transformers
- How to evaluate a classification model using different metrics

## Project Demo Video
Add your explanation video link here.

Example:
Video Link: https://youtube.com/your-video-link

## Author
Tejashwini S N
