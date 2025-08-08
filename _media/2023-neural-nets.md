---
title: "Neural networks for insurance pricing with frequency and severity data: a benchmark study from data preprocessing to technical tariff."
collection: media
category: manuscripts
permalink: /media/2025-neural-nets
excerpt: ''
date: 2025-3-01
venue: 'North American Actuarial Journal'
codeurl: 'https://github.com/freekholvoet/nnforfreqsevpricing'
slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://arxiv.org/abs/2310.12671'
citation: 'Freek Holvoet, Katrien Antonio, Roel Henckaerts (2023). Neural networks for insurance pricing with frequency and severity data: a benchmark study from data preprocessing to technical tariff. In <i>North Americal Actuarial Journal</i>.'
---

## Abstract
Insurers usually turn to generalized linear models for modelling claim frequency and severity data. Due to their success in other fields, machine learning techniques are gaining popularity within the actuarial toolbox. Our paper contributes to the literature on frequency-severity insurance pricing with machine learning via deep learning structures. We present a benchmark study on four insurance data sets with frequency and severity targets in the presence of multiple types of input features. We compare in detail the performance of: a generalized linear model on binned input data, a gradient-boosted tree model, a feed-forward neural network (FFNN), and the combined actuarial neural network (CANN). Our CANNs combine a baseline prediction established with a GLM and GBM, respectively, with a neural network correction. We explain the data preprocessing steps with specific focus on the multiple types of input features typically present in tabular insurance data sets, such as postal codes, numeric and categorical covariates. Autoencoders are used to embed the categorical variables into the neural network and we explore their potential advantages in a frequency-severity setting. Finally, we construct global surrogate models for the neural nets’ frequency and severity models. These surrogates enable the translation of the essential insights captured by the FFNNs or CANNs to GLMs. As such, a technical tariff table results that can easily be deployed in practice.