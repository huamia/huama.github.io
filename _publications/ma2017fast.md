---
title: "Fast Prospective Detection of Contrast Inflow in X-ray Angiograms with Convolutional Neural Network and Recurrent Neural Network"
collection: publications
permalink: /publication/ma2017fast
excerpt: '**Hua Ma**, Pierre Ambrosini, Theo van Walsum'
date: 2017-09-04
pubtype: "conference"
venue: 'International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI)'
# paperurl: 'http://academicpages.github.io/files/paper2.pdf'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---
**Hua Ma**, Pierre Ambrosini, Theo van Walsum

### ABSTRACT:

Automatic detection of contrast inflow in X-ray angiographic sequences can facilitate image guidance in computer-assisted cardiac interventions. In this paper, we propose two different approaches for prospective contrast inflow detection. The methods were developed and evaluated to detect contrast frames from X-ray sequences. The first approach trains a convolutional neural network (CNN) to distinguish whether a frame has contrast agent or not. The second method extracts contrast features from images with enhanced vessel structures; the contrast frames are then detected based on changes in the feature curve using long short-term memory (LSTM), a recurrent neural network architecture. Our experiments show that both approaches achieve good performance on detection of the beginning contrast frame from X-ray sequences and are more robust than a state-of-the-art method. As the proposed methods work in prospective settings and run fast, they have the potential of being used in clinical practice.

[Download paper here](https://arxiv.org/pdf/1912.03492.pdf)

**Recommended citation**

<pre>
@inproceedings{ma2017fast,
  title={Fast prospective detection of contrast inflow in X-ray angiograms with convolutional neural network and recurrent neural network},
  author={Ma, Hua and Ambrosini, Pierre and van Walsum, Theo},
  booktitle={International Conference on Medical Image Computing and Computer-Assisted Intervention},
  pages={453--461},
  year={2017},
  organization={Springer}
}
</pre>
