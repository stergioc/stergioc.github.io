---
layout: page
title:  "Self-Supervised Nuclei Segmentation in Histopathological Images Using Attention"
date:   2020-07-16 00:00:00 +0100
categories: [Computational Pathology]
tags: paper
image: /assets/img/miccai20.png
short_desc: Region-guided CycleGANs for stain transfer
published_at: MICCAI 2020
---

Mihir Sahasrabudhe, Stergios Christodoulidis, Roberto Salgado, Stefan Michiels, Sherene Loi, Fabrice André, Nikos Paragios, Maria Vakalopoulou

*MICCAI 2020*

[[proceedings](https://link.springer.com/chapter/10.1007/978-3-030-59722-1_38){:target="_blank"}], [[arxiv](https://arxiv.org/abs/2007.08373){:target="_blank"}], [[code](https://github.com/msahasrabudhe/miccai2020_self_sup_nuclei_seg){:target="_blank"}]

<div class="row">
    <div class="mx-auto w-75 pb-5">
        <img src="/assets/img/miccai20.png" alt="miccai20" width="100%"/>
    </div>
</div>

**Abstract:** Segmentation and accurate localization of nuclei in histopathological images is a very challenging problem, with most existing approaches adopting a supervised strategy. These methods usually rely on manual annotations that require a lot of time and effort from medical experts. In this study, we present a self-supervised approach for segmentation of nuclei for whole slide histopathology images. Our method works on the assumption that the size and texture of nuclei can determine the magnification at which a patch is extracted. We show that the identification of the magnification level for tiles can generate a preliminary self-supervision signal to locate nuclei. We further show that by appropriately constraining our model it is possible to retrieve meaningful segmentation maps as an auxiliary output to the primary magnification identification task. Our experiments show that with standard post-processing, our method can outperform other unsupervised nuclei segmentation approaches and report similar performance with supervised ones on the publicly available MoNuSeg dataset. Our code and models are available online?? to facilitate further research.

<pre>
@inproceedings{sahasrabudhe2020self,
  title={Self-supervised nuclei segmentation in histopathological images using attention},
  author={Sahasrabudhe, Mihir and Christodoulidis, Stergios and Salgado, Roberto and Michiels, Stefan and Loi, Sherene and Andr{\'e}, Fabrice and Paragios, Nikos and Vakalopoulou, Maria},
  booktitle={Medical Image Computing and Computer Assisted Intervention--MICCAI 2020: 23rd International Conference, Lima, Peru, October 4--8, 2020, Proceedings, Part V 23},
  pages={393--402},
  year={2020},
  organization={Springer}
}
</pre>