---
title: "Autonomous Driving Neuron Attribution"
layout: single-portfolio
excerpt: "<img src='/images/research/DrivingNeuronAttr/fig-method.jpg' alt=''>"
collection: research
order_number: 15
header: 
  og_image: "research/DrivingNeuronAttr/fig-method.jpg"
---

The rapid advancement of autonomous driving technology has transformed transportation, highlighting the necessity for precise attribution of decisions made by these complex models. Traditional path integral methods, which trace critical inputs influencing model predictions via gradient integration, are promising but often produce counterintuitive and unreliable results when applied directly to autonomous driving models. This paper identifies two primary reasons for these inefficiencies: the use of unreliable attribution baselines and integration paths. To address these problems, we propose a novel approach that constructs an open connected space for the baseline, specifically adapted to the unique attributes of driving scenes. Additionally, we implement baseline constraints to ensure the baseline accurately represents features absent in decision-making, thereby creating a solid foundation for accurate attribution computation. We also adjust the integration paths to accommodate the dispersed nature of objects in driving scenarios by using gradient-weighted feature maps, which helps in reducing noise and improving the reliability of attribution results. Extensive experiments demonstrate that our method not only provides reliable and interpretable attributions but also significantly surpasses existing state-of-the-art explanation techniques in both qualitative and quantitative assessments.

![](/images/research/DrivingNeuronAttr/fig-motivation.jpg){: .align-center .percentage-resize-img}

![](/images/research/DrivingNeuronAttr/fig-method.jpg){: .align-center .percentage-resize-img}

## Article

"Reliable Aumann-Shapley Attribution for Autonomous Driving." *Ongoing Work*. [Article](https://shirui-homepage.com/){: .btn} [GitHub Repo](https://github.com/GlowingHorse/){: .btn}

