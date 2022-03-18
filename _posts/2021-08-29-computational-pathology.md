---
layout: page
title:  "Computational Pathology"
date:   2021-08-25 12:00:00 +0100
categories: project
image: /assets/img/img3.png
short_desc: Automatic quantification and biomarker estimation of whole slide images for prediction and prognosis
---

Within the scope of our efforts in computational pathology, we investigate a number of approaches that utilize novel deep learning techniques towards a more reliable analysis of such data.

## Self-Supervised Representation Learning using Visual Field Expansion on Digital Pathology

<img src="/assets/img/cdpath_iccv21.png" alt="iccv21" width="100%"/>

The examination of histopathology images is considered to be the gold  standard  for  the  diagnosis  and  stratification  of  cancer patients. A key challenge in the analysis of such images is their size, which can run into the gigapixels and can require tedious screening by clinicians. With the recent advances in computational medicine, automatic tools have been proposed to assist clinicians in their everyday practice. Such tools typically process these large images by slicing them into tiles that can then be encoded and utilized for different clinical models. In this study, we propose a novel generative framework that can learn powerful representations for such tiles by learning to plausibly expand their visual field. In particular, we developed a progressively grown generative model with the objective of visual field expansion. Thus trained, our model learns to generate different tissue types with fine details, while simultaneously learning powerful representations that can be used for different clinical endpoints, all in a self-supervised way. To evaluate the performance of our model, we conducted classification experiments on CAMELYON17 and CRC benchmark datasets, comparing favorably to other self-supervised and pre-trained strategies that are commonly used in digital pathology. 

[[arxiv](https://arxiv.org/abs/2109.03299)], [[code](https://github.com/jcboyd/cdpath21-gan)]

## Self-Supervised Nuclei Segmentation in Histopathological Images Using Attention

<img src="/assets/img/miccai20.png" alt="miccai20" width="100%"/>

Segmentation and accurate localization of nuclei in histopathological images is a very challenging problem, with most existing approaches adopting a supervised strategy. These methods usually rely on manual annotations that require a lot of time and effort from medical experts. In this study, we present a self-supervised approach for segmentation of nuclei for whole slide histopathology images. Our method works on the assumption that the size and texture of nuclei can determine the magnification at which a patch is extracted. We show that the identification of the magnification level for tiles can generate a preliminary self-supervision signal to locate nuclei. We further show that by appropriately constraining our model it is possible to retrieve meaningful segmentation maps as an auxiliary output to the primary magnification identification task. Our experiments show that with standard post-processing, our method can outperform other unsupervised nuclei segmentation approaches and report similar performance with supervised ones on the publicly available MoNuSeg dataset. Our code and models are available online?? to facilitate further research.

[[proceedings](https://link.springer.com/chapter/10.1007/978-3-030-59722-1_38)], [[arxiv](https://arxiv.org/abs/2007.08373)], [[code](https://github.com/msahasrabudhe/miccai2020_self_sup_nuclei_seg)]
