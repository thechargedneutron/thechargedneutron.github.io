---
title: "SkillSight: Efficient First-Person Skill Assessment with Gaze"
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
excerpt: "IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), June 2026"
excerpt2: Chi Hsuan Wu, <u>Kumar Ashutosh</u>, Kristen Grauman
paper_link: https://arxiv.org/abs/2511.19629
project_page: https://vision.cs.utexas.edu/projects/skillsight/
externalLink: false
year: year2017
image:
  feature: "skillsight.png"
---

Please refer to the paper: [[https://arxiv.org/abs/2511.19629](https://arxiv.org/abs/2511.19629)].

### Abstract &nbsp;

Egocentric perception on smart glasses could transform how we learn new skills in the physical world, but automatic skill assessment remains a fundamental technical challenge. We introduce SkillSight for power-efficient skill assessment from first-person data. Central to our approach is the hypothesis that skill level is evident not only in how a person performs an activity (video), but also in how they direct their attention when doing so (gaze). Our two-stage framework first learns to jointly model gaze and egocentric video when predicting skill level, then distills a gaze-only student model. At inference, the student model requires only gaze input, drastically reducing power consumption by eliminating continuous video processing. Experiments on three datasets spanning cooking, music, and sports establish, for the first time, the valuable role of gaze in skill understanding across diverse real-world settings. Our SkillSight teacher model achieves state-of-the-art performance, while our gaze-only student variant maintains high accuracy using 73x less power than competing methods. These results pave the way for in-the-wild AI-supported skill learning.