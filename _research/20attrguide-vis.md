---
title: "Attribution-Guided Visualization Explanation"
layout: single-portfolio
excerpt: "<img src='/images/research/AttrGuideVis/intro.jpg' alt=''>"
collection: research
order_number: 20
header: 
  og_image: "research/AttrGuideVis/intro.jpg"
---

Given the critical need for more reliable autonomous driving models, explainability has become a focal point within the research community. In testing autonomous driving models, even slight perception differences can dramatically influence decision-making processes. Understanding the specific reasons why a model decides to stop or keep forward remains a significant challenge. This paper presents a novel attribution-guided visualization method aimed at exploring the triggers behind decision shifts, providing clear insights into the underlying why and why not of such decisions. More specifically, we propose the cumulative layer fusion attribution method that identifies the parameters most critical to decision-making. These attributions then inform the visualization updates, ensuring that changes in decisions are driven only by modifications to critical information. Furthermore, we develop an indirect regularization method that increase visualization quality without necessitating extra hyperparameters. Experiments on large datasets demonstrate that our method produces valuable visualization explanations and outperforms state-of-the-art methods in both qualitative and quantitative evaluations.

![](/images/research/AttrGuideVis/method.png){: .align-center .percentage-resize-img}

![](/images/research/AttrGuideVis/intro.jpg){: .align-center .percentage-resize-img}

## Article
"Exploring Decision Shifts in Autonomous Driving with Attribution-Guided Visualization." *IEEE Transactions on Intelligent Transportation Systems*. [Article](https://shirui-homepage.com/){: .btn} [GitHub Repo](https://github.com/GlowingHorse/){: .btn}

"Visualization comparison of vision transformers and convolutional neural networks." *IEEE Transactions on Multimedia*. [Article](https://ieeexplore.ieee.org/document/10179930){: .btn} [GitHub Repo](https://github.com/GlowingHorse/NetVisCompare){: .btn}

"Understanding contributing neurons via attribution visualizations." *Neurocomputing*. [Article](https://www.sciencedirect.com/science/article/abs/pii/S092523122300615X){: .btn} [GitHub Repo](https://github.com/GlowingHorse/Attribution-Visualization){: .btn}

"Group visualization of class-discriminative features." *Neural Networks*. [Article](https://www.sciencedirect.com/science/article/pii/S0893608020301969){: .btn} [GitHub Repo](https://github.com/GlowingHorse/Class-Discriminative-Vis){: .btn}

## Other Applications
To obtain an intuitive and integral understanding of neuron attributions, we propose a novel viewpoint to interpret neuron attributions of an entire layer, *i.e.,* visualizing their meanings integrally. This video shows how the mask and neural network visualization are generated.

<video width="300" class="align-center" controls>
    <source src="/images/research/AttrVis/vis-gen-horizontal.mp4" type="video/mp4">
</video>
