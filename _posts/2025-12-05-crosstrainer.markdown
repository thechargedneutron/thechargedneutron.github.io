---
title: "Learning Skill-Attributes for Transferable Assessment in Video"
layout: post
<!-- date: 2016-01-23 22:10 -->
tag: vision
image: /assets/images/nus-logo.jpg
headerImage: false
projects: true
hidden: true # don't count this post in blog pagination
subtitle: Includes projects prior to May 2018
description: 
category: publication-ut
<!-- author: kumarashutosh -->
excerpt: "Neural Information Processing Systems (NeurIPS), December 2025"
excerpt2: <u>Kumar Ashutosh</u>, Kristen Grauman
paper_link: https://arxiv.org/abs/2511.13993
project_page: https://vision.cs.utexas.edu/projects/CrossTrainer/
externalLink: false
year: year2017
image:
  feature: "crosstrainer.png"
---

Please refer to the project page: [https://vision.cs.utexas.edu/projects/CrossTrainer/](https://vision.cs.utexas.edu/projects/task_graph/) and the paper: [https://arxiv.org/abs/2511.13993](https://arxiv.org/abs/2511.13993)

### Abstract &nbsp;

Skill assessment from video entails rating the quality of a person's physical performance and explaining what could be done better. Today's models specialize for an individual sport, and suffer from the high cost and scarcity of expert-level supervision across the long tail of sports. Towards closing that gap, we explore transferable video representations for skill assessment. Our CrossTrainer approach discovers skill-attributes, such as balance, control, and hand positioning -- whose meaning transcends the boundaries of any given sport, then trains a multimodal language model to generate actionable feedback for a novel video, e.g., "lift hands more to generate more power" as well as its proficiency level, e.g., early expert. We validate the new model on multiple datasets for both cross-sport (transfer) and intra-sport (in-domain) settings, where it achieves gains up to 60% relative to the state of the art. By abstracting out the shared behaviors indicative of human skill, the proposed video representation generalizes substantially better than an array of existing techniques, enriching today's multimodal large language models.
