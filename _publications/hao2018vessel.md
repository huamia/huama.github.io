---
title: "Vessel Layer Separation in X-ray Angiograms with Fully Convolutional Network"
collection: publications
permalink: /publication/hao2018vessel
excerpt: 'Haidong Hao, **Hua Ma**, Theo van Walsum'
date: 2018-03-13
pubtype: "conference"
venue: 'Proc. SPIE 10576, Medical Imaging 2018: Image-Guided Procedures, Robotic Interventions, and Modeling'
# paperurl: 'http://academicpages.github.io/files/paper2.pdf'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
Haidong Hao, **Hua Ma**, Theo van Walsum

### ABSTRACT:

Percutaneous coronary intervention is a minimally-invasive procedure to treat coronary artery disease. In such procedures, X-ray angiography, a real-time imaging technique, is commonly used for image guidance to identify lesion sites and navigate catheters and guide-wires within coronary arteries. Due to the physical nature of X-ray imaging, photon energy undergoes absorption when penetrating tissues, rendering a 2D projection image of a 3D scene, in which semi-transparent structures overlap with each other. The overlapping structures make robust information processing of X-ray images challenging. To tackle this issue, layer separation techniques for X-ray images were proposed to separate those structures into different image layers based on structure appearance or motion pattern. These techniques have been proven effective for vessel enhancement in X-ray angiograms. However, layer separation approaches still suffer either from spurious structures or non-real-time processing, which prevent their application in clinics. Purpose of this work is to investigate whether vessel layer separation from X-ray angiography images is possible via a data-driven strategy. To this end, we develop and evaluate a deep learning based method to extract the vessel layer. More specifically, U-Net, a fully convolutional network architecture, was trained to separate the vessel layer from the background. The results of our experiments show good vessel layer separation on 42 clinical sequences. Compared to the previous state-of-the-art, our proposed method has similar performance but runs much faster, which makes it a potential real-time clinical application.

[Download paper here](https://huamia.github.io/files/papers/spie2018vessel.pdf)

**Recommended citation**

<pre>
@inproceedings{hao2018vessel,
  title={Vessel layer separation in x-ray angiograms with fully convolutional network},
  author={Hao, Haidong and Ma, Hua and van Walsum, Theo},
  booktitle={Medical Imaging 2018: Image-Guided Procedures, Robotic Interventions, and Modeling},
  volume={10576},
  pages={105761V},
  year={2018},
  organization={International Society for Optics and Photonics}
}
</pre>
