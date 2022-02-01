---
title: "Attribution Calculation"
layout: single-portfolio
excerpt: "<img src='/images/research/ASAttrCal/InIntroattrMethodIntro.jpg' alt=''>"
collection: research
order_number: 10
header: 
  og_image: "research/ASAttrCal/InIntroattrMethodIntro.jpg"
---

Aumann--Shapley values are originally designed for evaluating the contribution of a game player based on the marginal difference of the particular output between the case of removing and maintaining this player. It can be applied to calculate attributions in deep networks, if we can achieve feature removing and maintaining. However, we cannot achieve it in neural networks without retraining. As an alternative, a *baseline* expressing the no-signal state is widely used in attribution methods, *i.e.,* instead of actually removing features, the original feature values are replaced with the baseline values. By recalling the definition of Aumann--Shapley method, we first propose two primal baseline properties for calculating baselines to apply Aumann--Shapley values to deep networks. Then, we design an *optimization-based baseline* selection method which is slow but theoretically accurate and a *quadratic approximation* of the optimization-based method which is much faster but slightly worse. The experiments show our methods obviously outperform other alternative baselines and achieve better attributions than other attribution calculation methods.

![](/images/research/ASAttrCal/InIntroattrMethodIntro.jpg){: .align-center .percentage-resize-img}

## Article

"Computing neuron attributions with class-targeted baseline" is now in progress.