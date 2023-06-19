---
layout: page
title:  "Lung pattern classification for interstitial lung diseases using a deep convolutional neural network"
date:   2016-05-01 00:00:00 +0100
categories: [Radiology Data Quantification]
tags: paper
image: https://ieeexplore.ieee.org/mediastore_new/IEEE/content/media/42/7463083/7422082/7422082-fig-3-source-small.gif
---

<div class="row">
    <div class="mx-auto w-75 pb-5">
        <img src="https://ieeexplore.ieee.org/mediastore_new/IEEE/content/media/42/7463083/7422082/7422082-fig-3-source-small.gif" width="100%"/>
    </div>
</div>

**Abstract:** Automated tissue characterization is one of the most crucial components of a computer aided diagnosis (CAD) system for interstitial lung diseases (ILDs). Although much research has been conducted in this field, the problem remains challenging. Deep learning techniques have recently achieved impressive results in a variety of computer vision problems, raising expectations that they might be applied in other domains, such as medical image analysis. In this paper, we propose and evaluate a convolutional neural network (CNN), designed for the classification of ILD patterns. The proposed network consists of 5 convolutional layers with 2 × 2 kernels and LeakyReLU activations, followed by average pooling with size equal to the size of the final feature maps and three dense layers. The last dense layer has 7 outputs, equivalent to the classes considered: healthy, ground glass opacity (GGO), micronodules, consolidation, reticulation, honeycombing and a combination of GGO/reticulation. To train and evaluate the CNN, we used a dataset of 14696 image patches, derived by 120 CT scans from different scanners and hospitals. To the best of our knowledge, this is the first deep CNN designed for the specific problem. A comparative analysis proved the effectiveness of the proposed CNN against previous methods in a challenging dataset. The classification performance ( ~ 85.5%) demonstrated the potential of CNNs in analyzing lung patterns. Future work includes, extending the CNN to three-dimensional data provided by CT volume scans and integrating the proposed method into a CAD system that aims to provide differential diagnosis for ILDs as a supportive tool for radiologists.

[[doi](http://dx.doi.org/10.1109/TMI.2016.2535865)], [[code](https://github.com/intact-project/ild-cnn)]