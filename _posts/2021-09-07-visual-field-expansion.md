---
layout: page
title:  "Self-Supervised Representation Learning using Visual Field Expansion on Digital Pathology"
date:   2021-07-21 00:00:00 +0100
categories: [Computational Pathology]
tags: paper
image: /assets/img/cdpath_iccv21.png
short_desc: Region-guided CycleGANs for stain transfer
---

<div class="row">
    <div class="mx-auto w-75 pb-5">
        <img src="/assets/img/cdpath_iccv21.png" alt="iccv21" width="100%"/>
    </div>
</div>

**Abstract:** The examination of histopathology images is considered to be the gold  standard  for  the  diagnosis  and  stratification  of  cancer patients. A key challenge in the analysis of such images is their size, which can run into the gigapixels and can require tedious screening by clinicians. With the recent advances in computational medicine, automatic tools have been proposed to assist clinicians in their everyday practice. Such tools typically process these large images by slicing them into tiles that can then be encoded and utilized for different clinical models. In this study, we propose a novel generative framework that can learn powerful representations for such tiles by learning to plausibly expand their visual field. In particular, we developed a progressively grown generative model with the objective of visual field expansion. Thus trained, our model learns to generate different tissue types with fine details, while simultaneously learning powerful representations that can be used for different clinical endpoints, all in a self-supervised way. To evaluate the performance of our model, we conducted classification experiments on CAMELYON17 and CRC benchmark datasets, comparing favorably to other self-supervised and pre-trained strategies that are commonly used in digital pathology. 

[[arxiv](https://arxiv.org/abs/2109.03299)], [[code](https://github.com/jcboyd/cdpath21-gan)]