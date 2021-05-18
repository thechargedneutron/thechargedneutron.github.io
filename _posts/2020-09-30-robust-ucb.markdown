---
title: "Bandit algorithms: Letting go of logarithmic regret for statistical robustness"
layout: post
<!-- date: 2016-01-23 22:10 -->
tag: ucb, stochastic-control, theory
image: /assets/images/nus-logo.jpg
headerImage: false
projects: true
hidden: true # don't count this post in blog pagination
subtitle: Includes projects prior to May 2018
description: 
category: publication
<!-- author: kumarashutosh -->
excerpt: "Artificial Intelligence and Statistics (AISTATS), 13th-15th April 2021, Online Conference"
excerpt2: Kumar Ashutosh, Jayakrishnan Nair, Anmol Kagrecha, Krishna Jagannathan
paper_link: https://arxiv.org/abs/2006.12038
externalLink: false
year: year2017
image:
  feature: "robust_ucb.png"
---

### Preprint

[https://arxiv.org/abs/2006.12038](https://arxiv.org/abs/2006.12038)

Please cite as:

```bibtex
@misc{ashutosh2020bandit,
      title={Bandit algorithms: Letting go of logarithmic regret for statistical robustness}, 
      author={Kumar Ashutosh and Jayakrishnan Nair and Anmol Kagrecha and Krishna Jagannathan},
      year={2020},
      eprint={2006.12038},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```

### Motivation &nbsp;

Classical Multi-armed Bandit Algorithms are designed for some fixed distribution of reward functions. In fact, in most of the algorithms, the parameters of the reward distributions are indeed 'baked' into the algorithm. We study the problem of MAB problems when the reward distribution is not known, or the parameters are not known a-priori. These issues are quite natural, since the parameter estimation is itself prone to noise and outliers. Our proposed algorithms achieve a regret slightly worse than logarithmic while being statistically robust.

### Update &nbsp;

This blog will be updated once the paper is accepted at AISTATS 2021. 