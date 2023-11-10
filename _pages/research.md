---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

{% include base_path %}

# Research Projects
## Modeling Viral Evolution
Learn and predict the zoonotic evolution of viruses with the goal of preparing for the emergence of new pathogens. 
Build computational models to predict the mutations that enable an animal virus to shift hosts and adapt to human cells.
This complex problem of zoonosis prediction can be solved in a two-fold manner - 

- Host Prediction: Given the protein sequence of a virus, predict which host(s) the virus will infect.
- Mutation Prediction: Interpret the host prediction models to identify the mutations causing host shift.

Talk: [Zoonosis Prediction Using Language Models](https://iscb.junolive.co/ismb2023/library/search/ISMBECCB2023_1710)

Poster: [Zoonosis Prediction Using Language Models Poster](/files/2023-07-06-ismb-zoonosis-prediction-using-language-models-poster.pdf)

## Predictive Models of Long COVID
Prediction of the poorly understood post-acute sequelae of SARS-CoV-2 infection (PASC, or long COVID) based on information derived from the electronic health records (EHRs) of acute COVID-19 infection available in the [National COVID Cohort Collaborative](https://ncats.nih.gov/n3c) — the largest harmonized repository of EHRs of COVID-19 patients in the US.

- Trained logistic regression and random forest models using features such as the symptoms experienced by the COVID-19 patients, the drugs ordered or administered to them, the measures of COVID-19 treatment, comorbidities, and demographic information. Labeled COVID-19 patients diagnosed with U09.9 ICD10-CM code as long COVID patients.
- Leveraged Boruta method for feature selection and k-fold cross-validation based hyperparameter search for optimal model configuration yielding mean AUROC of 0.70
 - Computed the local interpretation of predictions using SHAP method and performed novel cross-site analysis to evaluate the impact of different data sources on long COVID prediction models and their generalizability.

Publication: [Predictive Models of Long COVID](https://doi.org/10.1016/j.ebiom.2023.104777) 

## Aarogya – An Intelligent Multi-Agent Pediatric System
An intelligent system offering pediatric services to counter the infant mortality rate caused by the unavailability of pediatricians in rural India. The project was funded by the Department of Science and Technology, Government of India through the Innovation and Entrepreneurship Development Center at Fr.Conceicao Rodrigues College of Engineering.
- Implemented intelligent agents, using Java Agent Development Framework 4.3.3, to gather information using an adaptive questionnaire, ascertain the disease and prescribe treatment.
- Developed an android application as the user interface for patients requiring the services of the intelligent system.