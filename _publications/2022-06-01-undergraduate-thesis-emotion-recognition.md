---
title: "Emotion Recognition from Facial Expression and Brain Signals"
collection: publications
category: undergraduate-thesis
permalink: /publication/2022-06-01-undergraduate-thesis-emotion-recognition
excerpt: 'This thesis explores emotion recognition using facial expressions and EEG signals for improved accuracy.'
date: 2022-06-01
venue: 'Undergraduate Thesis, University of Asia Pacific'
---

**Supervised by:**

Md. Akhtaruzzaman Adnan  
Assistant Professor

**Co-Supervised by:**  
Tanmoy Sarkar Pias  
Lecturer  
Department of Computer Science & Engineering  
University of Asia Pacific

**June 2022**

## Abstract

The goal of this study is to recognize emotions accurately. We have used two different approaches to recognize emotions. One is a real-time system to recognize emotions from facial expressions which can work in both virtual and in-person classroom setups. But sometimes it is hard to understand people’s emotions from their faces. That is why we explored a more reliable way to recognize emotions more precisely. Electroencephalography (EEG), which is used to determine the state of the human brain, can also be used to recognize emotion. Firstly, we designed research to evaluate the effectiveness of multiple machine learning techniques—Naive Bayes, Logistic Regression, XGBoost, SVM, Decision Tree, Random Forest, KNN, and deep learning models—CNN, LSTM, and Bi-LSTM for classifying sentiment from brain signals.

In our experiment, the DEAP dataset is used as a collection of brain signals representing different human sentiments. The DEAP dataset has five labels: Valence, Arousal, Dominance, Liking, and Familiarity. The Fast Fourier transformation (FFT), which shifts the data to the frequency domain, is used to extract features from the time series EEG data. Among all the algorithms, CNN, KNN, and Random Forest achieved the highest accuracy of 96.64%, 95.8%, and 95.28% respectively on the binary classification of valence. The results demonstrate that it is possible to attain accuracy comparable to or even outperform some of the deep learning models by combining appropriate feature extraction techniques (in this case, FFT) with machine learning algorithms.

Lastly, we propose a deep learning strategy to better recognize human emotions using EEG data on all five labels of the DEAP dataset. We leverage multitask machine learning to improve performance by using the capability of residual connections. Furthermore, we classify emotions into three classes for detecting emotional states more precisely. The majority of studies concentrated solely on valence and arousal. To detect emotion in a better way, we take into account valence, arousal, dominance, liking, and familiarity. The results reveal that the proposed approach can accurately predict emotions with an accuracy of 96.85%, 97.10%, 97.19%, 97.03%, and 95.24% for 2-class classification and for 3-class classification 95.92%, 96.02%, 96.63%, 96.08%, and 95.39% for valence, arousal, dominance, liking, and familiarity respectively.

## Access Thesis

[Request Access](https://drive.google.com/file/d/1038cZ_-xGfKMrUHpNd_oQ-_Y0S9iov1q/view?usp=sharing){: .btn .btn-primary }
