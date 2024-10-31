---
layout: page
title:  "Deep learning-based concurrent brain registration and tumor segmentation"
date:   2020-03-20 00:00:00 +0100
categories: [Learning Based Registration]
tags: paper
image: https://www.frontiersin.org/files/Articles/482795/fncom-14-00017-HTML-r2/image_m/fncom-14-00017-g005.jpg
published_at: Frontiers in Computational Neuroscience 2020
---

Théo Estienne, Marvin Lerousseau, Maria Vakalopoulou, Emilie Alvarez Andres, Enzo Battistella, Alexandre Carré, Siddhartha Chandra, Stergios Christodoulidis, et al. 

*Frontiers in Computational Neuroscience, Frontiers 2020*

[[doi](https://doi.org/10.3389/fncom.2020.00017)]

<div class="row">
    <div class="mx-auto w-75 pb-5">
        <img src="https://www.frontiersin.org/files/Articles/482795/fncom-14-00017-HTML-r2/image_m/fncom-14-00017-g005.jpg" width="100%"/>
    </div>
</div>

**Abstract:** Image registration and segmentation are the two most studied problems in medical image analysis. Deep learning algorithms have recently gained a lot of attention due to their success and state of the art results in varieties of problems and communities. In this paper, we propose a novel, efficient, and multi-task algorithm that addresses the problems of image registration and brain tumor segmentation jointly. Our method exploits the dependencies between these tasks through a natural coupling of their interdependencies during inference. In particular, constraints in correspondences are relaxed within the registration objective function in the regions of tumors, that are automatically recovered resulting in tumor volume preservation. We evaluated the performance of our formulation both quantitatively and qualitatively for registration and segmentation problems on two publicly available datasets (BraTS 2018 and OASIS 3), reporting competitive results with other recent state of the art methods.

<pre>
@article{estienne2020deep,
  title={Deep learning-based concurrent brain registration and tumor segmentation},
  author={Estienne, Th{\'e}o and Lerousseau, Marvin and Vakalopoulou, Maria and Alvarez Andres, Emilie and Battistella, Enzo and Carr{\'e}, Alexandre and Chandra, Siddhartha and Christodoulidis, Stergios and Sahasrabudhe, Mihir and Sun, Roger and others},
  journal={Frontiers in computational neuroscience},
  pages={17},
  year={2020},
  publisher={Frontiers}
}
</pre>