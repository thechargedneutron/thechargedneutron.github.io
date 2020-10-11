---
title: "Hardware Performance Analysis of Mobile-Based Augmented Reality Systems"
layout: post
<!-- date: 2016-01-23 22:10 -->
tag: AR, research, IEEE
image: /assets/images/nus-logo.jpg
headerImage: false
projects: true
hidden: true # don't count this post in blog pagination
subtitle: Includes projects prior to May 2018
description: 
category: publication
<!-- author: kumarashutosh -->
excerpt: "IEEE Conference on Computational Performance Evaluation (ComPE), 2nd - 4th July 2020, Online Conference"
excerpt2: Kumar Ashutosh
paper_link: https://ieeexplore.ieee.org/document/9200079/
presentation_link: docs/compe_presentation.pdf
externalLink: false
year: year2017
image:
  feature: "nehu_paper.png"
---

### Paper

[https://ieeexplore.ieee.org/document/9200079/](https://ieeexplore.ieee.org/document/9200079/)

Please cite as:

```bibtex
@INPROCEEDINGS{9200079,
  author={K. {Ashutosh}},
  booktitle={2020 International Conference on Computational Performance Evaluation (ComPE)}, 
  title={Hardware Performance Analysis of Mobile-Based Augmented Reality Systems}, 
  year={2020},
  volume={},
  number={},
  pages={671-675},}
```

### Motivation

This work is primarily motivated by my previous experiments with mobile-based Augmented Reality. I have done several AR projects previously. I observed that the performance of AR applications is dependent on the hardware being used. Naturally, it is crucial to understand and compare the hardwares involved in building AR systems. Also, the accuracy and precision is important in considering the feasibility for an application. For example, if the mobile device has an error of 10 meters in calculating its position, the device cannot be used for very fine AR application. If such applications are made, they will be hegely errenous. Two important hardwares are considered in this work - the Global Positioning System (GPS) and Battery. Both are described briefly in the following sections.

### Global Positioning System (GPS)

The GPS chip installed in the mobile devices are manufactured by different manufacturers and therefore, are sometimes inconsistent and error prone. This may lead to a degraded performance of mobile AR systems. In this work, we compare three mobile devices - Apple iPhone XR, Xiaomi Note 6 Pro and Xiaomi Note 7 Pro. There are three experiments that were done as part of this work. Firstly, we analyze fluctuations in GPS reading in an outdoor environment. Secondly, we compare the fluctuations in GPS readings in an indoor setting. In both cases, we observe an error of the order of a few meters. However, it is evident that the performance is worse in an indoor environment compared to outdoor setting. Finally, we analyze drift in GPS position after a random walk for some time. All these readings demonstrates anomalies which could hamper the performance of AR systems. Therefore, AR systems which require centi-meter level of accuracy is currently unsatisfiable by the current hardware systems.

### Battery Performance

Finally, we also compare the battery performance due to AR systems. Computer generated 3D meshes are computationally expensive and runs mainly on GPUs. Therefore, it is important to analyze the battery performance given the future score of AR-based applications. In this experiment, we observe that AR games with moving 3D models consumes significantly more battery power than conventional camera apps in mobile devices. Therefore, the battery performance should also be enhanced in order to make it compatible with state-of-the-art AR technologies.

### Conclusion

The paper first discusses applications of AR in various fields including healthcare, advertising and education. Next, we discuss the hardware challenges associated with it.We mainly focus on GPS performance and also on battery performance.