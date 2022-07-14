# Spam/Ham Classifier

## Overview
This is a simple SPAM/HAM Classification from a list of messages.

## Motivation
What could be a perfect way to utilize summer holidays period? Like most of you, I spend my time in family business, coding and reading some latest research papers on weekends. So i got more interest on Data Science,and i have started research on that and learnt Data Science and to explore more i started Projects on ML and NLP. This is one of my simple NLP projects *Classifying SPAM or HAM depending on message*

## Technical Aspect

I have collected a dataset with messages containing both SPAM and HAM messages, Now **SPAM** is taken as **1** and **HAM** is taken as **0** for classification

This project is divided into two parts:

**1. Pre-Processing:**\
       - Tokenization — convert sentences to words\
       - Removing unnecessary punctuation, tags\
       - Removing stop words — frequent words such as ”the”, ”is”, etc. that do not have specific semantic\
       - Stemming — words are reduced to a root by removing inflection through dropping unnecessary characters, usually a suffix.\
       - Lemmatization — Another approach to remove inflection by determining the part of speech and utilizing detailed database of the language.\
       - Bag of Words\
       - TF-IDF
       
 **2. Model Building:**\
       - From the vectors we have got we will build a model\
       - From the entire data we will split in to train and test data.\
       - we will train a model using train data, here we used *Naive Bayes Classifier* for SPAM/HAM Classification.\
       - After Training we validate a model using Test data.\
       - Observe the metrics

## Result
![image](https://user-images.githubusercontent.com/70332477/179002380-3a024d4c-0b2f-4e21-b454-36cd09cab8a4.png)
![image](https://user-images.githubusercontent.com/70332477/179002396-5b2578d8-4820-4685-ad9b-180a8bd5eb1a.png)
![image](https://user-images.githubusercontent.com/70332477/179002411-0dffbda8-c5e2-4ec5-8ebf-6962efb79a5f.png)


             
## Installation  
The Code is written in Python 3.9

