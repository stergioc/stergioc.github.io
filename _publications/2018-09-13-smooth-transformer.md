---
layout: page
title:  "Linear and Deformable Image Registration with 3D Convolutional Neural Networks"
date:   2018-09-13 00:00:00 +0100
categories: [Learning Based Registration]
tags: paper
image: /assets/img/miccai18.png
published_at: MICCAI RAMBO Workshop 2018
---

Stergios Christodoulidis, Mihir Sahasrabudhe, Maria Vakalopoulou, Guillaume Chassagnon, Marie-Pierre Revel, Stavroula Mougiakakou, Nikos Paragios

*MICCAI 2018, workshop on Image Analysis for Moving Organ, Breast, and Thoracic Images (RAMBO)*

[[proceedings](https://link.springer.com/chapter/10.1007/978-3-030-00946-5_2){:target="_blank"}], [[arxiv](https://arxiv.org/abs/1809.06226){:target="_blank"}], [[code](https://github.com/stergioc/smooth-transformer){:target="_blank"}]

<div class="row">
    <div class="mx-auto w-75 pb-5">
        <img src="/assets/img/miccai18.png" width="100%"/>
    </div>
</div>

**Abstract:** Image registration and in particular deformable registration methods are pillars of medical imaging. Inspired by the recent advances in deep learning, we propose in this paper, a novel convolutional neural network architecture that couples linear and deformable registration within a unified architecture endowed with near real-time performance. Our framework is modular with respect to the global transformation component, as well as with respect to the similarity function while it guarantees smooth displacement fields. We evaluate the performance of our network on the challenging problem of MRI lung registration, and demonstrate superior performance with respect to state of the art elastic registration methods. The proposed deformation (between inspiration & expiration) was considered within a clinically relevant task of interstitial lung disease (ILD) classification and showed promising results.

<pre>
@inproceedings{stergios2018linear,
  title={Linear and deformable image registration with 3d convolutional neural networks},
  author={Stergios, Christodoulidis and Mihir, Sahasrabudhe and Maria, Vakalopoulou and Guillaume, Chassagnon and Marie-Pierre, Revel and Stavroula, Mougiakakou and Nikos, Paragios},
  booktitle={Image Analysis for Moving Organ, Breast, and Thoracic Images: Third International Workshop, RAMBO 2018, Fourth International Workshop, BIA 2018, and First International Workshop, TIA 2018, Held in Conjunction with MICCAI 2018, Granada, Spain, September 16 and 20, 2018, Proceedings 3},
  pages={13--22},
  year={2018},
  organization={Springer}
}
</pre>