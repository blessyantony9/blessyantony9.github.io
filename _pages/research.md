---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

{% include base_path %}

# Research Projects
## Modeling Viral Evolution
Learn and predict the zoonotic evolution of viruses with the goal of preparing for the emergence of new pathogens. Constructing new deep learning architectures to learn from viral protein sequences (datasets: UniProt KB and NCBI Virus).

## Predictive Models of Long COVID
Prediction of the poorly understood post-acute sequelae of SARS-CoV-2 infection (PASC, or long COVID) based on information derived from the electronic health records (EHRs) of acute COVID-19 infection available in the [National COVID Cohort Collaborative](https://ncats.nih.gov/n3c) — the largest harmonized repository of EHRs of COVID-19 patients in the US.

- Trained logistic regression and random forest models using features such as the symptoms experienced by the COVID-19 patients, the drugs ordered or administered to them, the measures of COVID-19 treatment, comorbidities, and demographic information. Labeled COVID-19 patients diagnosed with U09.9 ICD10-CM code as long COVID patients.
- Leveraged Boruta method for feature selection and k-fold cross-validation based hyperparameter search for optimal model configuration yielding mean AUROC of 0.70
 - Computed the local interpretation of predictions using SHAP method and performed novel cross-site analysis to evaluate the impact of different data sources on long COVID prediction models and their generalizability.

Publication Status: Manuscript under review.

## Aarogya – An Intelligent Multi-Agent Pediatric System
An intelligent system offering pediatric services to counter the infant mortality rate caused by the unavailability of pediatricians in rural India. The project was funded by the Department of Science and Technology, Government of India through the Innovation and Entrepreneurship Development Center at Fr.Conceicao Rodrigues College of Engineering.
- Implemented intelligent agents, using Java Agent Development Framework 4.3.3, to gather information using an adaptive questionnaire, ascertain the disease and prescribe treatment.
- Developed an android application as the user interface for patients requiring the services of the intelligent system.

# Coursework Projects

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