---
title: Explain Adversarial Attack
date: 2021-08-10
permalink: /posts/2021/08-adv-explainer
excerpt_separator: <!--more-->
toc: true
tags:
  - Adversarial sample
  - Visualization system
---

A toy demo showing the features lost in **adversarial attacks**. [Toy Demo](https://shirui-homepage.com/AdvExplainer/){: .btn}

<!--more-->

Adversarial attacks mean modifying the input image and then making the neural network fail to recognize the image at all.
However, it is difficult to understand exactly what changes the network produces as a result of the adversarial attack.

I would like to develop an intuitive interface to show the features that are present in the original image. As well as the features that are missing in the adversarial sample.

The development of [this front-end interface](https://shirui-homepage.com/AdvExplainer/) is still a work in progress. 
