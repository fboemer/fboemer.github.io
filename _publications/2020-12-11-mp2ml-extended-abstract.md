---
title: "MP2ML: A Mixed-protocol Machine Learning Framework for Private Inference (Extended Abstract)"
collection: publications
permalink: /publications/mp2ml
venue: 'PPMLP 2020 Workshop at CCS 2020; Poster at PPML Workshop at NeurIPS 2020'
paperurl: 'https://dl.acm.org/doi/10.1145/3407023.3407045'
authors: '<b>Fabian Boemer</b>, Rosario Cammarota, Daniel Demmler, Thomas Schneider, Hossein Yalame'
---

Fabian Boemer, Rosario Cammarota, Daniel Demmler, Thomas Schneider, Hossein Yalame


**Abstract**
Privacy-preserving machine learning (PPML) has many applications, from medical image classification and anomaly detection to financial analysis. nGraph-HE enables data scientists to perform private inference of deep learning (DL) models trained using popular frameworks such as TensorFlow. nGraph-HE computes linear layers using the CKKS homomorphic encryption (HE) scheme. The non-polynomial activation functions, such as MaxPool and ReLU, are evaluated in the clear by the data owner who obtains the intermediate feature maps. This leaks the feature maps to the data owner from which it may be possible to deduce the DL model weights. As a result, such protocols may not be suitable for deployment, especially when the DL model is intellectual property.

In this work, we present MP2ML, a machine learning framework which integrates nGraph-HE and the secure two-party computation framework ABY, to overcome the limitations of leaking the intermediate feature maps to the data owner. We introduce a novel scheme for the conversion between CKKS and secure multi-party computation to execute DL inference while maintaining the privacy of both the input data and model weights. MP2ML is compatible with popular DL frameworks such as TensorFlow that can infer pre-trained neural networks with native ReLU activations. We benchmark MP2ML on the CryptoNets network with ReLU activations, on which it achieves a throughput of 33.3 images/s and an accuracy of 98.6%. This throughput matches the previous state-of-the-art work, even though our protocol is more accurate and scalable.
