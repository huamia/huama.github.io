---
title: "PCA-derived Respiratory Motion Surrogates from X-ray Angiograms for Percutaneous Coronary Interventions"
collection: publications
permalink: /publication/ma2015pca
excerpt: <b>Hua Ma</b>, Gerardo Dibildox, Carl Schultz, Evelyn Regar, Theo van Walsum
date: 2015-04-07
pubtype: "journal"
venue: 'International Journal of Computer Assisted Radiology and Surgery'
ga: /images/ga/surrogates.png
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
**Hua Ma**, Gerardo Dibildox, Carl Schultz, Evelyn Regar, Theo van Walsum

### ABSTRACT:

**Purpose**  Intraoperative coronary motion modeling with motion surrogates enables prospective motion prediction in X-ray angiograms (XA) for percutaneous coronary interventions. The motion of coronary arteries is mainly affected by patients breathing and heartbeat. Purpose of our work is therefore to extract coronary motion surrogates that are related to respiratory and cardiac motion. In particular, we focus on respiratory motion surrogates extraction in this paper.

**Methods**  We propose a fast automatic method for extracting patient-specific respiratory motion surrogate from cardiac XA. The method starts with an image preprocessing step to remove all tubular and curvilinear structures from XA images, such as vessels and guiding catheters, followed by principal component analysis on pixel intensities. The respiratory motion surrogate of an XA image is then obtained by projecting its vessel-removed image onto the first principal component.

**Results**  This breathing motion surrogate was demonstrated to get high correlation with ground truth diaphragm motion (correlation coefficient over 0.9 on average). In comparison with other related methods, the method we developed did not show significant difference (p>0.05), but did improve robustness and run faster on monoplane and biplane data in retrospective and prospective scenarios.

**Conclusions**  we developed and evaluated a method in extraction of respiratory motion surrogate from interventional X-ray images that is easy to implement and runs in real time and thus allows extracting respiratory motion surrogates during interventions.

### KEYWORDS:

Respiratory motion; X-ray angiograms; Principal component analysis; Percutaneous coronary intervention 

[Download paper here](https://link.springer.com/article/10.1007%2Fs11548-015-1185-2)

***Recommended citation***: 

<pre>
@article{ma2015pca,
  title={PCA-derived respiratory motion surrogates from X-ray angiograms for percutaneous coronary interventions},
  author={Ma, Hua and Dibildox, Gerardo and Schultz, Carl and Regar, Evelyn and van Walsum, Theo},
  journal={International Journal of Computer Assisted Radiology and Surgery},
  volume={10},
  number={6},
  pages={695--705},
  year={2015},
  publisher={Springer}
}
</pre>
