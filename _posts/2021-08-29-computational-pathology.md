---
layout: page
title:  "Computational Pathology"
date:   2021-08-25 12:00:00 +0100
categories: project
image: /assets/img/img3.png
short_desc: Automatic quantification and biomarker estimation of whole slide images for prediction and prognosis
---

Within the scope of our efforts in computational pathology, we investigate a number of approaches that utilize novel deep learning techniques towards a more reliable analysis of such data.

## Region-guided CycleGANs for Stain Transfer in Whole Slide Images

In whole slide imaging, commonly used staining techniques based on hematoxylin and eosin (H&E) and immunohistochemistry (IHC) stains accentuate different aspects of the tissue landscape. In the case of detecting metastases, IHC provides a distinct readout that is readily interpretable by pathologists. IHC, however, is a more expensive option and not available at all medical centers. Virtually generating IHC images from H&E using deep neural networks becomes an attractive option. Deep generative models such as cycleGANs learn a semantically-consistent mapping between two image domains, while emulating the textural properties of each domain. They are therefore a suitable choice for stain transfer applications. However, they remain fully unsupervised, and possess no mechanism for injecting partial supervisory signals. In this paper, we propose an extension to cycleGANs in the form of a region of interest discriminator, yielding a type of conditional GAN. This allows the cycleGAN to learn from unpaired datasets where, in addition, there is a partial annotation of objects for which one wishes to enforce a consistency. We present a use case on whole slide images, where an IHC stain provides an experimentally-generated signal for metastatic cells. We show the superiority of our approach over prior art in stain transfer on histopathology tiles derived from two datasets.

[[arxiv](https://arxiv.org/abs/2208.12847)] [[code](https://github.com/jcboyd/miccai2022-roigan)]

<img src="/assets/img/roigan_miccai22.png" alt="miccai22b" width="100%"/>

## Unsupervised Nuclei Segmentation using Spatial Organization Priors

In digital pathology, various biomarkers (e.g., KI67, HER2, CD3/CD8) are routinely analyzed by pathologists through immuno-histo-chemistry-stained slides. Identifying these biomarkers on patient biopsies allows for a more informed design of their treatment regimen. The diversity and specificity of these types of images make the availability of annotated databases sparse. Consequently, robust and efficient learning-based diagnostic systems are difficult to develop and apply in a clinical setting. Our study builds on the observation that the overall organization and structure of the observed tissues is similar across different staining protocols.  In this paper, we propose to leverage both the wide availability of hematoxylin-eosin stained databases and the invariance of tissue organization and structure in order to perform unsupervised nuclei segmentation on immunohistochemistry images. We implement and evaluate a generative adversarial method that relies on high-level nuclei distribution priors through comparison with largely available hematoxylin-eosin stained cell nuclei masks. Our approach shows promising results compared to classic unsupervised and supervised methods, as we quantitatively demonstrate on two publicly available datasets.

[[preprint](https://hal.archives-ouvertes.fr/hal-03644463/document)] [[code](https://github.com/loic-lb/Unsupervised-Nuclei-Segmentation-using-Spatial-Organization-Priors)]

<img src="/assets/img/spatialorg_miccai22.png" alt="miccai22a" width="100%"/>

## Self-Supervised Representation Learning using Visual Field Expansion on Digital Pathology

The examination of histopathology images is considered to be the gold  standard  for  the  diagnosis  and  stratification  of  cancer patients. A key challenge in the analysis of such images is their size, which can run into the gigapixels and can require tedious screening by clinicians. With the recent advances in computational medicine, automatic tools have been proposed to assist clinicians in their everyday practice. Such tools typically process these large images by slicing them into tiles that can then be encoded and utilized for different clinical models. In this study, we propose a novel generative framework that can learn powerful representations for such tiles by learning to plausibly expand their visual field. In particular, we developed a progressively grown generative model with the objective of visual field expansion. Thus trained, our model learns to generate different tissue types with fine details, while simultaneously learning powerful representations that can be used for different clinical endpoints, all in a self-supervised way. To evaluate the performance of our model, we conducted classification experiments on CAMELYON17 and CRC benchmark datasets, comparing favorably to other self-supervised and pre-trained strategies that are commonly used in digital pathology. 

[[arxiv](https://arxiv.org/abs/2109.03299)], [[code](https://github.com/jcboyd/cdpath21-gan)]

<img src="/assets/img/cdpath_iccv21.png" alt="iccv21" width="100%"/>

## Self-Supervised Nuclei Segmentation in Histopathological Images Using Attention

Segmentation and accurate localization of nuclei in histopathological images is a very challenging problem, with most existing approaches adopting a supervised strategy. These methods usually rely on manual annotations that require a lot of time and effort from medical experts. In this study, we present a self-supervised approach for segmentation of nuclei for whole slide histopathology images. Our method works on the assumption that the size and texture of nuclei can determine the magnification at which a patch is extracted. We show that the identification of the magnification level for tiles can generate a preliminary self-supervision signal to locate nuclei. We further show that by appropriately constraining our model it is possible to retrieve meaningful segmentation maps as an auxiliary output to the primary magnification identification task. Our experiments show that with standard post-processing, our method can outperform other unsupervised nuclei segmentation approaches and report similar performance with supervised ones on the publicly available MoNuSeg dataset. Our code and models are available online?? to facilitate further research.

[[proceedings](https://link.springer.com/chapter/10.1007/978-3-030-59722-1_38)], [[arxiv](https://arxiv.org/abs/2007.08373)], [[code](https://github.com/msahasrabudhe/miccai2020_self_sup_nuclei_seg)]

<img src="/assets/img/miccai20.png" alt="miccai20" width="100%"/>
