---
layout: page
title:  "Radiology Data Quantification"
date:   2021-08-25 11:00:00 +0100
categories: project
image: /assets/img/img1.png
short_desc: Deep Learning methods for the quantification of interstitial lung diseases.
---

## AI-driven quantification, staging and outcome prediction of COVID-19 pneumonia

<img src="https://ars.els-cdn.com/content/image/1-s2.0-S1361841520302243-fx1_lrg.jpg" width="100%"/>

Coronavirus disease 2019 (COVID-19) emerged in 2019 and disseminated around the world rapidly. Computed tomography (CT) imaging has been proven to be an important tool for screening, disease quantification and staging. The latter is of extreme importance for organizational anticipation (availability of intensive care unit beds, patient management planning) as well as to accelerate drug development through rapid, reproducible and quantified assessment of treatment response. Even if currently there are no specific guidelines for the staging of the patients, CT together with some clinical and biological biomarkers are used. In this study, we collected a multi-center cohort and we investigated the use of medical imaging and artificial intelligence for disease quantification, staging and outcome prediction. Our approach relies on automatic deep learning-based disease quantification using an ensemble of architectures, and a data-driven consensus for the staging and outcome prediction of the patients fusing imaging biomarkers with clinical and biological attributes. Highly promising results on multiple external/independent evaluation cohorts as well as comparisons with expert human readers demonstrate the potentials of our approach.

[[doi](https://doi.org/10.1016/j.media.2020.101860)]

## Semantic Segmentation of Pathological Lung Tissue with Dilated Fully Convolutional Networks

<img src="/assets/img/jbhi18.png" width="100%"/>

Early and accurate diagnosis of interstitial lung diseases (ILDs) is crucial for making treatment decisions, but can be challenging even for experienced radiologists. The diagnostic procedure is based on the detection and recognition of the different ILD pathologies in thoracic CT scans, yet their manifestation often appears similar. In this study, we propose the use of a deep purely convolutional neural network for the semantic segmentation of ILD patterns, as the basic component of a computer aided diagnosis (CAD) system for ILDs. The proposed CNN, which consists of convolutional layers with dilated filters, takes as input a lung CT image of arbitrary size and outputs the corresponding label map. We trained and tested the network on a dataset of 172 sparsely annotated CT scans, within a cross-validation scheme. The training was performed in an end-to-end and semi-supervised fashion, utilizing both labeled and non-labeled image regions. The experimental results show significant performance improvement with respect to the state of the art.

[[doi](https://doi.org/10.1109/JBHI.2018.2818620)], [[arxiv](https://arxiv.org/abs/1803.06167)], [[code](https://github.com/intact-project/LungNet)]

## Lung pattern classification for interstitial lung diseases using a deep convolutional neural network

<img src="https://ieeexplore.ieee.org/mediastore_new/IEEE/content/media/42/7463083/7422082/7422082-fig-3-source-small.gif" width="100%"/>

Automated tissue characterization is one of the most crucial components of a computer aided diagnosis (CAD) system for interstitial lung diseases (ILDs). Although much research has been conducted in this field, the problem remains challenging. Deep learning techniques have recently achieved impressive results in a variety of computer vision problems, raising expectations that they might be applied in other domains, such as medical image analysis. In this paper, we propose and evaluate a convolutional neural network (CNN), designed for the classification of ILD patterns. The proposed network consists of 5 convolutional layers with 2 × 2 kernels and LeakyReLU activations, followed by average pooling with size equal to the size of the final feature maps and three dense layers. The last dense layer has 7 outputs, equivalent to the classes considered: healthy, ground glass opacity (GGO), micronodules, consolidation, reticulation, honeycombing and a combination of GGO/reticulation. To train and evaluate the CNN, we used a dataset of 14696 image patches, derived by 120 CT scans from different scanners and hospitals. To the best of our knowledge, this is the first deep CNN designed for the specific problem. A comparative analysis proved the effectiveness of the proposed CNN against previous methods in a challenging dataset. The classification performance ( ~ 85.5%) demonstrated the potential of CNNs in analyzing lung patterns. Future work includes, extending the CNN to three-dimensional data provided by CT volume scans and integrating the proposed method into a CAD system that aims to provide differential diagnosis for ILDs as a supportive tool for radiologists.

[[doi](http://dx.doi.org/10.1109/TMI.2016.2535865)], [[code](https://github.com/intact-project/ild-cnn)]