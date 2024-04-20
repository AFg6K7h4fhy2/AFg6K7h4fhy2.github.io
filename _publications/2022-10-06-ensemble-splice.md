---
title: "EnsembleSplice: Ensemble Deep Learning Model For Splice Site Prediction"
collection: publications
permalink: /publication/2022-10-06-ensemble-splice
excerpt: 'This paper constitutes a small advance towards the highly accurate detection of donor and acceptor splice sites regions across species-diverse nucleotide sequence data.'
date: 2022-10-06
paperurl: 'https://link.springer.com/article/10.1186/s12859-022-04971-w'
citation: 'Akpokiro, Victor, Trevor Martin, and Oluwatosin Oluwadare. "EnsembleSplice: ensemble deep learning model for splice site prediction." BMC bioinformatics 23, no. 1 (2022): 413.'
---

_The Abstract is reproduced below, for full paper, please access the appropriate links_

# Abstract 

## Background

Identifying splice site regions is an important step in the genomic DNA sequencing pipelines of biomedical and pharmaceutical research. Within this research purview, efficient and accurate splice site detection is highly desirable, and a variety of computational models have been developed toward this end. Neural network architectures have recently been shown to outperform classical machine learning approaches for the task of splice site prediction. Despite these advances, there is still considerable potential for improvement, especially regarding model prediction accuracy. 

## Results

Given these deficits, we propose EnsembleSplice, an ensemble learning architecture made up of four (4) distinct convolutional neural networks (CNN) model architecture combination that outperform existing splice site detection methods in the experimental evaluation metrics considered including the accuracies and error rates. We trained and tested a variety of ensembles made up of CNNs and DNNs using the five-fold cross-validation method to identify the model that performed the best across the evaluation and diversity metrics. As a result, we developed our diverse and highly effective splice site (SS) detection model, which we evaluated using two (2) genomic _Homo sapiens_ datasets and the _Arabidopsis thaliana_ dataset. The results showed that for of the _Homo sapiens_ EnsembleSplice achieved accuracies of 94.16% for one of the acceptor splice sites and 95.97% for donor splice sites, with an error rate for the same _Homo sapiens_ dataset, 4.03% for the donor splice sites and 5.84% for the acceptor splice sites datasets.

## Conclusions

Our five-fold cross validation ensured the prediction accuracy of our models are consistent. For reproducibility, all the datasets used, models generated, and results in our work are publicly available in our GitHub repository here: <https://github.com/OluwadareLab/EnsembleSplice>
