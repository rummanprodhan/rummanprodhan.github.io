---
title: "M1M2: deep-learning-based real-time emotion recognition from neural activity"
collection: publications
category: manuscripts
permalink: /publication/2022-11-03-mdpi-sensor-journal-m1m2-deep-learning-based-real-time-emotion-recognition
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2022-11-03
venue: 'Journal: MDPI Sensor'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://www.mdpi.com/1424-8220/22/21/8467'
citation: 'Akter, S., Prodhan, R. A., Pias, T. S., Eisenberg, D., & Fresneda Fernandez, J. (2022). M1M2: deep-learning-based real-time emotion recognition from neural activity. Sensors, 22(21), 8467.'
---

Abstract: Emotion recognition, or the ability of computers to interpret people’s emotional states, is a very active research area with vast applications to improve people’s lives. However, most image-based emotion recognition techniques are flawed, as humans can intentionally hide their emotions by changing facial expressions. Consequently, brain signals are being used to detect human emotions with improved accuracy, but most proposed systems demonstrate poor performance as EEG signals are difficult to classify using standard machine learning and deep learning techniques. This paper proposes two convolutional neural network (CNN) models (M1: heavily parameterized CNN model and M2: lightly parameterized CNN model) coupled with elegant feature extraction methods for effective recognition. In this study, the most popular EEG benchmark dataset, the DEAP, is utilized with two of its labels, valence, and arousal, for binary classification. We use Fast Fourier Transformation to extract the frequency domain features, convolutional layers for deep features, and complementary features to represent the dataset. The M1 and M2 CNN models achieve nearly perfect accuracy of 99.89% and 99.22%, respectively, which outperform every previous state-of-the-art model. We empirically demonstrate that the M2 model requires only 2 seconds of EEG signal for 99.22% accuracy, and it can achieve over 96% accuracy with only 125 milliseconds of EEG data for valence classification. Moreover, the proposed M2 model achieves 96.8% accuracy on valence using only 10% of the training dataset, demonstrating our proposed system’s effectiveness. Documented implementation codes for every experiment are published for reproducibility.

## Authors

**Sumya Akter**<sup>1†</sup>, **Rumman Ahmed Prodhan**<sup>1†</sup>, **Tanmoy Sarkar Pias**<sup>2*</sup>, **David Eisenberg**<sup>3*</sup>, and **Jorge Fresneda Fernandez**<sup>1</sup>

1. Martin Tuchman School of Management, New Jersey Institute of Technology, Newark, NJ 07102, USA  
2. Department of Computer Science, Virginia Tech, Blacksburg, VA 24061, USA  
3. Department of Information Systems, Ying Wu College of Computing, New Jersey Institute of Technology, Newark, NJ 07102, USA  

*Authors to whom correspondence should be addressed.  
†These authors contributed equally to this work.
