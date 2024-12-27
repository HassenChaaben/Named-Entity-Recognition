
# Named-Entity-Recognition

## Overview : 
This project focuses on Named Entity Recognition (NER), a subtask of information extraction that seeks to locate and classify named entities mentioned in unstructured text into predefined categories such as the names of persons, organizations, locations, Dates, Disease , Chemical .

## Features : 
- Accurate and efficient named entity recognition 

## Installation : 

To install the necessary dependencies, run:
bash
### pip install spacy
###  pip install scispacy
###  pip install https://s3-us-west-2.amazonaws.com/ai2-s2-scispacy/releases/v0.5.4/en_ner_bc5cdr_md-0.5.4.tar.gz
###  pip install transformers datasets torch scikit-learn


## Introduction : 
Named Entity Recognition (NER) is a fundamental problem in Natural Language Processing (NLP) that aims to locate and classify named entities in unstructured text into predefined categories. This project focuses on building a robust NER pipeline for extracting key medical entities from text, including diseases, chemicals, organizations, persons, geopolitical entities, and dates.

## Project Description : 
The project consists of the following stages:

## Data Preprocessing: 
Extracting and compiling text from JSON files, cleaning text, and performing named entity recognition using both biomedical and general-purpose models.
## Exploratory Data Analysis (EDA): 
Conducting a comprehensive EDA pipeline to understand the dataset structure, token distribution, and NER tag distribution.
## Error Analysis and Correction: 
Analyzing and correcting errors in NER annotations using a predefined corpus.
## Model Fine-Tuning: 
Fine-tuning a pre-trained BERT model on the annotated dataset to improve its performance on the NER task.
## Evaluation and Inference: 
Evaluating the fine-tuned model using precision, recall, and F1-score metrics and deploying it for inference.

## Features of the Dataset
The dataset consists of the following features:

### Tokens: The smallest unit of text, typically a word, punctuation, or symbol.
###  POS (Part of Speech): The grammatical role of a word in a sentence, such as noun, verb, adjective, etc.
###  DEP (Dependency Label): The syntactic relationship between tokens in a sentence.
###  Lemma: The base or dictionary form of a word.

## BERT-Base-Cased Architecture
The project uses the BERT-base-cased architecture, which consists of:

### Embeddings: Token embeddings, position embeddings, and segment embeddings.
### Encoder: A series of identical layers, each consisting of multi-head attention and feed-forward network.
### Pooler: A layer that reduces the sequence of vectors to a single vector representation.
### Output: A vector representation of the input text.
### Fine-Tuning the BERT Model
The project fine-tunes the pre-trained BERT model on the annotated dataset using the Hugging Face Transformers library.

## Evaluation Metrics : 
The project uses the following evaluation metrics:

Precision: The proportion of entities correctly identified by the model.
Recall: The proportion of actual entities that the model successfully identified.
F1-Score: The harmonic mean of precision and recall.

## Conclusion : 
This project aims to build a robust NER pipeline for extracting key medical entities from text. Due to resource limitations, the fine-tuning process and deployment were not completed, but the project provides a solid foundation for future work. With appropriate resources and a longer project duration, better results can be achieved.
