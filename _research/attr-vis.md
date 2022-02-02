---
title: "Neuron Attribution Visualization"
layout: single-portfolio
excerpt: "<img src='/images/research/AttrVis/attr-vis-teaser.jpg' alt=''>"
collection: research
order_number: 30
header: 
  og_image: "research/AttrVis/attr-vis-teaser.jpg"
---

An attribution result contains tens of thousands of numerical scores. Previous methods generate heatmaps to understand these attribution scores; however, the implications behind neuron attributions can be very different, even if their heatmaps, *i.e.,* their spatial distributions, are highly similar. To obtain an intuitive and integral understanding of neuron attributions, we propose a novel viewpoint to interpret neuron attributions of an entire layer, *i.e.,* visualizing their meanings integrally. The integral visualization enables us to analyze network behaviors of each layer. To filter nonsensical noise caused by irrelevant neurons, we introduce mask perturbation into the visualization objective function, and design the area-constrained mask regularization term where the area constraint can be set arbitrarily. To improve the visualization quality, we design a fractal noise pyramid and dynamically apply the noise to perturb the visualization image during optimization. Both quantitative and qualitative experiments show that the perturbation with fractal noise pyramid can produce the best visual effect among all tested visualization techniques.

![](/images/research/AttrVis/attr-vis-teaser.jpg){: .align-center .fifty-percentage-resize-img}

This video shows how the mask and visualization are generated.

<video width="600" class="align-center" controls>
    <source src="/images/research/AttrVis/vis-gen-horizontal.mp4" type="video/mp4">
</video>

## Article

"Understanding contributing neurons via attribution visualizations." is now in progress.
