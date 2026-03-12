# Fake News Detection using BERT

## Introduction
Fake news spreads misinformation and can mislead people. Detecting fake news automatically using Natural Language Processing (NLP) can help reduce the spread of false information. In this project, a Fake News Detection system is built using a pretrained BERT model.

## Objective
The goal of this project is to classify news articles as **Fake** or **Real** using a transformer-based model.

## Dataset
The dataset used for this project is the **FA-KES Dataset**.  
It contains news articles along with labels indicating whether the news is fake or real.

## Technologies Used
- Python  
- Transformers Library  
- PyTorch  
- Scikit-learn  
- Pandas  
- Matplotlib / Seaborn  
- Google Colab  

## Model Used
The model used in this project is **BERT (bert-base-uncased)**, which is a pretrained transformer model widely used for NLP tasks.

## Project Workflow
1. Load and explore the dataset.
2. Clean and prepare the text data.
3. Tokenize the text using BERT tokenizer.
4. Split the dataset into training and validation sets.
5. Fine-tune the BERT model for fake news classification.
6. Evaluate the model using performance metrics.

## Evaluation Metrics
The model performance is evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

## Results
The trained model was evaluated on the validation dataset and the performance metrics were generated using a classification report and confusion matrix.

## Future Improvements
- Train the model for more epochs
- Handle class imbalance
- Compare results with other transformer models like DistilBERT

## Conclusion
This project demonstrates how transformer-based models like BERT can be used for fake news detection. With further improvements and more training data, the performance of the model can be improved.

## Author
Tejashwini S N 
