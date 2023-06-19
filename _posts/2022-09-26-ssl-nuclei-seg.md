---
layout: page
title:  "Self-Supervised Nuclei Segmentation in Histopathological Images Using Attention"
date:   2022-09-26 10:00:00 +0100
categories: [Computational Pathology]
tags: paper
image: /assets/img/miccai20.png
short_desc: Region-guided CycleGANs for stain transfer
---

## Self-Supervised Nuclei Segmentation in Histopathological Images Using Attention

<img src="/assets/img/miccai20.png" alt="miccai20" width="100%"/>

Segmentation and accurate localization of nuclei in histopathological images is a very challenging problem, with most existing approaches adopting a supervised strategy. These methods usually rely on manual annotations that require a lot of time and effort from medical experts. In this study, we present a self-supervised approach for segmentation of nuclei for whole slide histopathology images. Our method works on the assumption that the size and texture of nuclei can determine the magnification at which a patch is extracted. We show that the identification of the magnification level for tiles can generate a preliminary self-supervision signal to locate nuclei. We further show that by appropriately constraining our model it is possible to retrieve meaningful segmentation maps as an auxiliary output to the primary magnification identification task. Our experiments show that with standard post-processing, our method can outperform other unsupervised nuclei segmentation approaches and report similar performance with supervised ones on the publicly available MoNuSeg dataset. Our code and models are available online?? to facilitate further research.

[[proceedings](https://link.springer.com/chapter/10.1007/978-3-030-59722-1_38)], [[arxiv](https://arxiv.org/abs/2007.08373)], [[code](https://github.com/msahasrabudhe/miccai2020_self_sup_nuclei_seg)]