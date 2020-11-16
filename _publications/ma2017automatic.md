---
title: "Automatic Online Layer Separation for Vessel Enhancement in X-ray Angiograms for Percutaneous Coronary Interventions"
collection: publications
permalink: /publication/ma2017automatic
excerpt: '**Hua Ma**, Ayla Hoogendoorn, Evelyn Regar, Wiro J. Niessen, Theo van Walsum'
date: 2017-07-01
pubtype: "journal"
venue: 'Medical Image Analysis'
# paperurl: 'http://academicpages.github.io/files/paper2.pdf'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
**Hua Ma**, Ayla Hoogendoorn, Evelyn Regar, Wiro J. Niessen, Theo van Walsum

### ABSTRACT:

Percutaneous coronary intervention is a minimally invasive procedure that is usually performed under image guidance using X-ray angiograms in which coronary arteries are opacified with contrast agent. In X-ray images, 3D objects are projected on a 2D plane, generating semi-transparent layers that overlap each other. The overlapping of structures makes robust automatic information processing of the X-ray images, such as vessel extraction which is highly relevant to support smart image guidance, challenging. In this paper, we propose an automatic online layer separation approach that robustly separates interventional X-ray angiograms into three layers: a breathing layer, a quasi-static layer and a vessel layer that contains information of coronary arteries and medical instruments. The method uses morphological closing and an online robust PCA algorithm to separate the three layers. The proposed layer separation method ran fast and was demonstrated to significantly improve the vessel visibility in clinical X-ray images and showed better performance than other related online or prospective approaches. The potential of the proposed approach was demonstrated by enhancing contrast of vessels in X-ray images with low vessel contrast, which would facilitate the use of reduced amount of contrast agent to prevent contrast-induced side effects.

### KEYWORDS:

Layer separation; Online robust PCA; Vessel enhancement; X-ray angiograms

[Download paper here](https://huamia.github.io/files/papers/media2017automatic.pdf)

### Demo videos of online layer separation for an X-ray angiogram

<style>
.fig_div {
  width: 25%;
  padding: 3px;
}
figcaption {
  text-align: center;
  width: 100%;
}
</style>

<div style="display: flex">
  <div class="fig_div">
    <figure>
      <img src="/images/layer_sep/orig_40.gif">
      <figcaption>X-ray Angiogram</figcaption>
    </figure>
  </div>
  <div class="fig_div">
    <figure>
      <img src="/images/layer_sep/breath_40.gif">
      <figcaption>Breathing Layer</figcaption>
    </figure>
  </div>
  <div class="fig_div">
    <figure>
      <img src="/images/layer_sep/static_40.gif">
      <figcaption>Quasi-static Layer</figcaption>
    </figure>
  </div>
  <div class="fig_div">
    <figure>
      <img src="/images/layer_sep/vessel_40.gif">
      <figcaption>Vessel Layer</figcaption>
    </figure>
  </div>
</div>


**Recommended citation**

<pre>
@article{ma2017automatic,
  title={Automatic online layer separation for vessel enhancement in X-ray angiograms for percutaneous coronary interventions},
  author={Ma, Hua and Hoogendoorn, Ayla and Regar, Evelyn and Niessen, Wiro J and van Walsum, Theo},
  journal={Medical image analysis},
  volume={39},
  pages={145--161},
  year={2017},
  publisher={Elsevier}
}
</pre>
