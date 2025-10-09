---
layout: page
title:  "Spatio-Temporal Analysis of Patient-Derived Organoid Videos Using Deep Learning for the Prediction of Drug Efficacy"
date:   2023-08-18 00:00:00 +0100
categories: [Tumor Organoids]
tags: paper
image: /assets/img/spatiotemporal_iccvw23.png
short_desc: HER2 expression in metastatic breast cancer
published_at: ICCV BioImage Computing Workshop 2023
---

Leo Fillioux, Emilie Gontran, Jérôme Cartry, Jacques RR Mathieu, Sabrina Bedja, Alice Boilève, Paul-Henry Cournède, Fanny Jaulin, Stergios Christodoulidis, Maria Vakalopoulou

*ICCV BioImage Computing Workshop, 2023*

[[arxiv](https://arxiv.org/abs/2308.14461){:target="_blank"}]

<div class="row">
    <div class="mx-auto w-75 pb-5">
        <img src="/assets/img/spatiotemporal_iccvw23.png" alt="iccv23" width="100%"/>
    </div>
</div>

**Abstract:** Over the last ten years, Patient-Derived Organoids (PDOs) emerged as the most reliable technology to generate ex-vivo tumor avatars. PDOs retain the main characteristics of their original tumor, making them a system of choice for pre-clinical and clinical studies. In particular, PDOs are attracting interest in the field of Functional Precision Medicine (FPM), which is based upon an ex-vivo drug test in which living tumor cells (such as PDOs) from a specific patient are exposed to a panel of anti-cancer drugs. Currently, the Adenosine Triphosphate (ATP) based cell viability assay is the gold standard test to assess the sensitivity of PDOs to drugs. The readout is measured at the end of the assay from a global PDO population and therefore does not capture single PDO responses and does not provide time resolution of drug effect. To this end, in this study, we explore for the first time the use of powerful large foundation models for the automatic processing of PDO data. In particular, we propose a novel imaging-based high-throughput screening method to assess real-time drug efficacy from a time-lapse microscopy video of PDOs. The recently proposed SAM algorithm for segmentation and DINOv2 model are adapted in a comprehensive pipeline for processing PDO microscopy frames. Moreover, an attention mechanism is proposed for fusing temporal and spatial features in a multiple instance learning setting to predict ATP. We report better results than other non-time-resolved methods, indicating that the temporality of data is an important factor for the prediction of ATP. Extensive ablations shed light on optimizing the experimental setting and automating the prediction both in real-time and for forecasting.

<pre>
@article{fillioux2023spatio,
  title={Spatio-Temporal Analysis of Patient-Derived Organoid Videos Using Deep Learning for the Prediction of Drug Efficacy},
  author={Fillioux, Leo and Gontran, Emilie and Cartry, J{\'e}r{\^o}me and Mathieu, Jacques RR and Bedja, Sabrina and Boil{\`e}ve, Alice and Courn{\`e}de, Paul-Henry and Jaulin, Fanny and Christodoulidis, Stergios and Vakalopoulou, Maria},
  journal={arXiv preprint arXiv:2308.14461},
  year={2023}
}
</pre>