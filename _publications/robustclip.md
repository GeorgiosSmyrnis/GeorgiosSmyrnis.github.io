---
title: "Inverse Problems Leveraging Pre-trained Contrastive Representations"
collection: publications
permalink: /publication/dclm
excerpt: ''
date: December 2021
venue: 'NeurIPS 2021'
authors: 'Sriram Ravula, Georgios Smyrnis, Matt Jordan, Alexandros G. Dimakis'
paperurl: https://arxiv.org/abs/2110.07439
code: https://github.com/Sriram-Ravula/Contrastive-Inversion
---

# Abstract

We study a new family of inverse problems for recovering representations of corrupted data. We assume access to a pre-trained representation learning network R(x) that operates on clean images, like CLIP. The problem is to recover the representation of an image R(x), if we are only given a corrupted version A(x), for some known forward operator A. We propose a supervised inversion method that uses a contrastive objective to obtain excellent representations for highly corrupted images. Using a linear probe on our robust representations, we achieve a higher accuracy than end-to-end supervised baselines when classifying images with various types of distortions, including blurring, additive noise, and random pixel masking. We evaluate on a subset of ImageNet and observe that our method is robust to varying levels of distortion. Our method outperforms end-to-end baselines even with a fraction of the labeled data in a wide range of forward operators.

Full paper available [here](https://arxiv.org/abs/2110.07439).
