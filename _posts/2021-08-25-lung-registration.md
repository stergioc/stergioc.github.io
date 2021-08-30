---
layout: page
title:  "Learning Based Registration"
date:   2021-08-25 10:00:00 +0100
categories: project
image: /assets/img/img2.png
short_desc: Unsupervised registration using deep learning applied on medical and remote sensing data.
---

## Exploring Deep Registration Latent Spaces

<img src="/assets/img/dart21.png" width="100%"/>

Explainability of deep neural networks is one of the most challenging and interesting problems in the field. In this study, we investigate the topic focusing on the interpretability of deep learning-based registration methods. In particular, with the appropriate model architecture and using a simple linear projection, we decompose the encoding space, generating a new basis, and we empirically show that this basis captures various decomposed anatomically aware geometrical transformations. We perform experiments using two different datasets focusing on lungs and hippocampus MRI. We show that such an approach can decompose the highly convoluted latent spaces of registration pipelines in an orthogonal space with several interesting properties. We hope that this work could shed some light on a better understanding of deep learning-based registration methods.

[[arxiv](https://arxiv.org/abs/2107.11238)]

## Deep learning-based concurrent brain registration and tumor segmentation

<img src="https://www.frontiersin.org/files/Articles/482795/fncom-14-00017-HTML-r2/image_m/fncom-14-00017-g005.jpg" width="100%"/>

Image registration and segmentation are the two most studied problems in medical image analysis. Deep learning algorithms have recently gained a lot of attention due to their success and state of the art results in varieties of problems and communities. In this paper, we propose a novel, efficient, and multi-task algorithm that addresses the problems of image registration and brain tumor segmentation jointly. Our method exploits the dependencies between these tasks through a natural coupling of their interdependencies during inference. In particular, constraints in correspondences are relaxed within the registration objective function in the regions of tumors, that are automatically recovered resulting in tumor volume preservation. We evaluated the performance of our formulation both quantitatively and qualitatively for registration and segmentation problems on two publicly available datasets (BraTS 2018 and OASIS 3), reporting competitive results with other recent state of the art methods.

[[doi](https://doi.org/10.3389/fncom.2020.00017)]

## Image registration of satellite imagery with deep convolutional neural networks

<img src="/assets/img/igarss19.png" width="100%"/>

Image registration in multimodal, multitemporal satellite imagery is one of the most important problems in remote sensing and essential for a number of other tasks such as change detection and image fusion. In this paper, inspired by the recent success of deep learning approaches we propose a novel convolutional neural network architecture that couples linear and deformable approaches for accurate alignment of remote sensing imagery. The proposed method is completely unsupervised, ensures smooth displacement fields and provides real time registration on a pair of images. We evaluate the performance of our method using a challenging multitemporal dataset of very high resolution satellite images and compare its performance with a state of the art elastic registration method based on graphical models. Both quantitative and qualitative results prove the high potentials of our method.

[[proceedings](https://doi.org/10.1109/IGARSS.2019.8898220)], [[pdf](https://hal.inria.fr/hal-02422555/file/Image_Registration_with_CNNs.pdf)]

## Linear and Deformable Image Registration with 3D Convolutional Neural Networks

<img src="/assets/img/miccai18.png" width="100%"/>

Image registration and in particular deformable registration methods are pillars of medical imaging. Inspired by the recent advances in deep learning, we propose in this paper, a novel convolutional neural network architecture that couples linear and deformable registration within a unified architecture endowed with near real-time performance. Our framework is modular with respect to the global transformation component, as well as with respect to the similarity function while it guarantees smooth displacement fields. We evaluate the performance of our network on the challenging problem of MRI lung registration, and demonstrate superior performance with respect to state of the art elastic registration methods. The proposed deformation (between inspiration & expiration) was considered within a clinically relevant task of interstitial lung disease (ILD) classification and showed promising results.

[[proceedings](https://link.springer.com/chapter/10.1007/978-3-030-00946-5_2)], [[arxiv](https://arxiv.org/abs/1809.06226)], [[code](https://github.com/stergioc/smooth-transformer)]