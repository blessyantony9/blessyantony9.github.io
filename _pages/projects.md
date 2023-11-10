---
layout: archive
title: ""
permalink: /projects/
author_profile: true
---

{% include base_path %}

# Coursework Projects

## A time evolving online social network generation algorithm
    
Developed an algorithm - EpiCNet - to generate dynamic, time-evolving, synthetic online social networks for downstream social network analysis tasks.

- Generated networks paralleling real-world social media platforms in terms of network properties such as cluster coefficient, degree distribution, and community structure.
- Designed the algorithm to emulate the evolution of nodes, edges, and communities in the network at different time steps.
- Devised tunable stochastic parameters based on compartmental modeling from epidemiology (for node evolution) and communities (for edge evolution) to allow the generation of varied and realistic synthetic networks.
- Generated sequences of directed and undirected synthetic networks with 100,000 nodes over 100 time steps and observed densification law in the number of nodes, long-tailed degree distribution with friendship paradox, and community structure with a large number of small communities. 


## Analysis Of Contextual And Structural Information Importance In Code Representation Learning
Developed a standardized pipeline of downstream tasks for evaluation of code representational learning models.

- Analyzed efficiency of CodeBERT (contextual) and GraphCodeBERT (contextual + structural) in 1. code summarization and 2. clone detection tasks.
- Used BigCloneBench and CodeSearchNet datasets to benchmark the performance of models in code summarization and clone detection respectively.
- Implemented fine-tuning of pre-trained models from Hugging Face Transformers, evaluated the trained models across ten different randomly sampled test datasets, and computed and compared performance metrics.
- Observed the importance of structural information in learning code embeddings through higher BLEU, AUPRC F1, Precision, and Recall scores for GraphCodeBERT compared to CodeBERT in both downstream tasks.

## SARS-CoV-2 Interactors Identification using Network-Based Label Propagation
Implemented Random Walk with Restarts (RWR) algorithm to discover human proteins interacting with the SARS-CoV-2 virus proteins directly or indirectly.

- Propagated the labels from known human protein interactors in a protein-protein interaction network – STRING and identified unknown virus interactors.
- Additionally exercised the implementation within N3C Data Enclave and executed it on the KG-COVID-19 graph. Enhanced the implementation using sparse matrices to improve performance and reduce memory footprint.
- Compared with external experimentally derived results using Fisher’s Exact Test and Jaccard coefficient.

## Social Media Sentiment Analyzer for COVID-19
Built a model that stratifies Tweets pertaining COVID-19 into 3 sentiment categories to identify posts propagating anti-vaccine misinformation through social media. Tools: scikit-learn, PyTorch, nltk, pandas

- Implemented Logistic Regression, Support Vector Machine (SVM), Long Short-Term Memory Recurrent Neural Network (LSTM-RNN) multi-class classification models using TweetsCOV19 dataset. 
- Performed parameter tuning and 5-fold cross-validation for all models, and evaluated them using Accuracy, Precision, Recall, and F1 scores. Highest accuracy of 98.2% achieved by LSTM-RNN model.
- Added functionality to analyze and classify real-time data by streaming Tweets using Twitter API v2.

## Cancer Diagnosis System using Support Vector Machine
An effective breast cancer classification model constructed using GNU Octave 4.0 to implement Support Vector Machine (SVM) with Gaussian RBF Kernel. The prediction accuracy amplified to ~97% using feature selection based on iterative computation and comparison of F-Scores. 
-  Utilized the Breast Cancer Wisconsin dataset to train and test the built classification model.
- Executed an algorithm to compute F-Scores of attributes and determine an effective feature set for the model.
- Implemented a mechanism to identify optimum kernel configuration and data-splitting ratio for training and validation.