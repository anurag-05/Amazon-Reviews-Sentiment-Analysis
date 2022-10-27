# Amazon-Reviews-Sentiment-Analysis

## Project Description:
This project does the sentiment analysis of Amazon Reviews using two different approaches, and then comparing them.

* The dataset consists of 568454 records with 10 features.
* The main features include 'Score' (1-5) and 'Text' (on which we are doing the sentiment analysis).
* After completing the sentiment analysis on 'Text', the results are compared with 'Score' to check the correlation.
* The two models used for sentiment analysis are compared with respect to time and accuracy. This is done using Data visualization with pairplot.

## Techniques used

### Natural Language Toolkit
* Used NLTK for tokenization, tagging and parsing.

### VADER Model
* Valence Aware Dictionary and sEntiment Reasoner
* The VADER model is faster, but does not consider the context of the sentence.

### Roberta pretrained model
* This model is pretrained on ~58M tweets and finetuned for sentiment analysis.
* Transformer based model which accounts for the words but also the context related to other words.
* More confident predictions compared to the VADER model.
* More time consuming than the VADER model.
