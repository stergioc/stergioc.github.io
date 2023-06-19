---
layout: page
title:  "Linear and Deformable Image Registration with 3D Convolutional Neural Networks"
date:   2018-09-13 00:00:00 +0100
categories: [Learning Based Registration]
tags: paper
image: /assets/img/miccai18.png
---

<div class="row">
    <div class="mx-auto w-75 pb-5">
        <img src="/assets/img/miccai18.png" width="100%"/>
    </div>
</div>

**Abstract:** Image registration and in particular deformable registration methods are pillars of medical imaging. Inspired by the recent advances in deep learning, we propose in this paper, a novel convolutional neural network architecture that couples linear and deformable registration within a unified architecture endowed with near real-time performance. Our framework is modular with respect to the global transformation component, as well as with respect to the similarity function while it guarantees smooth displacement fields. We evaluate the performance of our network on the challenging problem of MRI lung registration, and demonstrate superior performance with respect to state of the art elastic registration methods. The proposed deformation (between inspiration & expiration) was considered within a clinically relevant task of interstitial lung disease (ILD) classification and showed promising results.

[[proceedings](https://link.springer.com/chapter/10.1007/978-3-030-00946-5_2)], [[arxiv](https://arxiv.org/abs/1809.06226)], [[code](https://github.com/stergioc/smooth-transformer)]