---
layout: page
title:  "Unsupervised Nuclei Segmentation using Spatial Organization Priors"
date:   2022-09-10 00:00:00 +0100
categories: [Computational Pathology]
tags: paper
image: /assets/img/spatialorg_miccai22.png
short_desc: Region-guided CycleGANs for stain transfer
published_at: MICCAI 2022
---

Loïc Le Bescond, Marvin Lerousseau, Ingrid Garberis, Fabrice André, Stergios Christodoulidis, Maria Vakalopoulou, Hugues Talbot

*MICCAI 2022*

[[preprint](https://hal.archives-ouvertes.fr/hal-03644463/document){:target="_blank"}] [[code](https://github.com/loic-lb/Unsupervised-Nuclei-Segmentation-using-Spatial-Organization-Priors){:target="_blank"}]

<div class="row">
    <div class="mx-auto w-75 pb-5">
        <img src="/assets/img/spatialorg_miccai22.png" alt="miccai22a" width="100%"/>
    </div>
</div>

**Abstract:** In digital pathology, various biomarkers (e.g., KI67, HER2, CD3/CD8) are routinely analyzed by pathologists through immuno-histo-chemistry-stained slides. Identifying these biomarkers on patient biopsies allows for a more informed design of their treatment regimen. The diversity and specificity of these types of images make the availability of annotated databases sparse. Consequently, robust and efficient learning-based diagnostic systems are difficult to develop and apply in a clinical setting. Our study builds on the observation that the overall organization and structure of the observed tissues is similar across different staining protocols.  In this paper, we propose to leverage both the wide availability of hematoxylin-eosin stained databases and the invariance of tissue organization and structure in order to perform unsupervised nuclei segmentation on immunohistochemistry images. We implement and evaluate a generative adversarial method that relies on high-level nuclei distribution priors through comparison with largely available hematoxylin-eosin stained cell nuclei masks. Our approach shows promising results compared to classic unsupervised and supervised methods, as we quantitatively demonstrate on two publicly available datasets.

<pre>
@inproceedings{le2022unsupervised,
  title={Unsupervised Nuclei Segmentation using Spatial Organization Priors},
  author={Le Bescond, Lo{\"\i}c and Lerousseau, Marvin and Garberis, Ingrid and Andr{\'e}, Fabrice and Christodoulidis, Stergios and Vakalopoulou, Maria and Talbot, Hugues},
  booktitle={Medical Image Computing and Computer Assisted Intervention--MICCAI 2022: 25th International Conference, Singapore, September 18--22, 2022, Proceedings, Part II},
  pages={325--335},
  year={2022},
  organization={Springer}
}
</pre>