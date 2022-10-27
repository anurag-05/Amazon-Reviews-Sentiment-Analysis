# Amazon-Reviews-Sentiment-Analysis

## Project Description:
This project does the sentiment analysis of Amazon Reviews using two different approaches, and then comparing them.

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
