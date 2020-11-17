---
title: "Dynamic Coronary Roadmapping via Catheter Tip Tracking in X-ray Fluoroscopy with Deep Learning based Bayesian Filtering"
collection: publications
permalink: /publication/ma2020dynamic
excerpt: <b>Hua Ma</b>, Ihor Smal, Joost Daemen, Theo van Walsum
date: 2020-04-01
pubtype: "journal"
venue: 'Medical Image Analysis'
ga: /images/ga/dcr.png
# paperurl: 'http://academicpages.github.io/files/paper3.pdf'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---
**Hua Ma**, Ihor Smal, Joost Daemen, Theo van Walsum

### ABSTRACT:

Percutaneous coronary intervention (PCI) is typically performed with image guidance using X-ray angiograms in which coronary arteries are opacified with X-ray opaque contrast agents. Interventional cardiologists typically navigate instruments using non-contrast-enhanced fluoroscopic images, since higher use of contrast agents increases the risk of kidney failure. When using fluoroscopic images, the interventional cardiologist needs to rely on a mental anatomical reconstruction. This paper reports on the development of a novel dynamic coronary roadmapping approach for improving visual feedback and reducing contrast use during PCI. The approach compensates cardiac and respiratory induced vessel motion by ECG alignment and catheter tip tracking in X-ray fluoroscopy, respectively. In particular, for accurate and robust tracking of the catheter tip, we proposed a new deep learning based Bayesian filtering method that integrates the detection outcome of a convolutional neural network and the motion estimation between frames using a particle filtering framework. The proposed roadmapping and tracking approaches were validated on clinical X-ray images, achieving accurate performance on both catheter tip tracking and dynamic coronary roadmapping experiments. In addition, our approach runs in real-time on a computer with a single GPU and has the potential to be integrated into the clinical workflow of PCI procedures, providing cardiologists with visual guidance during interventions without the need of extra use of contrast agent.

### KEYWORDS:

Dynamic coronary roadmapping, X-ray fluoroscopy, Catheter tip tracking, Deep learning, Bayesian filtering, Particle filter.

[Download paper here](https://arxiv.org/pdf/2001.03801.pdf)

### Demo video of dynamic coronary roadmapping

![DCR demo](/images/dcr/dcr.gif)


**Recommended citation**

<pre>
@article{ma2020dynamic,
  title={Dynamic coronary roadmapping via catheter tip tracking in X-ray fluoroscopy with deep learning based Bayesian filtering},
  author={Ma, Hua and Smal, Ihor and Daemen, Joost and van Walsum, Theo},
  journal={Medical Image Analysis},
  volume={61},
  pages={101634},
  year={2020},
  publisher={Elsevier}
}
</pre>