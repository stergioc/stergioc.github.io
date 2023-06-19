---
layout: page
title:  "Semantic Segmentation of Pathological Lung Tissue with Dilated Fully Convolutional Networks"
date:   2019-03-01 00:00:00 +0100
categories: [Radiology Quantification]
tags: paper
image: /assets/img/jbhi18.png
---

<div class="row">
    <div class="mx-auto w-75 pb-5">
        <img src="/assets/img/jbhi18.png" width="100%"/>
    </div>
</div>

**Abstract:** Early and accurate diagnosis of interstitial lung diseases (ILDs) is crucial for making treatment decisions, but can be challenging even for experienced radiologists. The diagnostic procedure is based on the detection and recognition of the different ILD pathologies in thoracic CT scans, yet their manifestation often appears similar. In this study, we propose the use of a deep purely convolutional neural network for the semantic segmentation of ILD patterns, as the basic component of a computer aided diagnosis (CAD) system for ILDs. The proposed CNN, which consists of convolutional layers with dilated filters, takes as input a lung CT image of arbitrary size and outputs the corresponding label map. We trained and tested the network on a dataset of 172 sparsely annotated CT scans, within a cross-validation scheme. The training was performed in an end-to-end and semi-supervised fashion, utilizing both labeled and non-labeled image regions. The experimental results show significant performance improvement with respect to the state of the art.

[[doi](https://doi.org/10.1109/JBHI.2018.2818620)], [[arxiv](https://arxiv.org/abs/1803.06167)], [[code](https://github.com/intact-project/LungNet)]