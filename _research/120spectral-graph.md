---
title: "Spectrum Garment Deformation"
layout: single-portfolio
excerpt: "<img src='/images/research/SpectralGraph/figOverview.jpg' alt=''>"
collection: research
order_number: 120
header: 
  og_image: "research/SpectralGraph/figOverview.jpg"
---

We present a novel solution for mesh-based deformation simulation from a spectral perspective. Unlike existing approaches that demand separate training for each garment or body type and often struggle to produce rich folds and lifelike dynamics, our method achieves the quality of physics-based simulations while maintaining superior efficiency within a unified model. The key to achieve this lies in the development of a spectrum-enhanced deformation network, a result of in-depth theoretical analysis bridging neural networks and garment deformations. This enhancement compels the network to focus on learning spectral information predominantly within the frequency band associated with intricate deformations. Furthermore, building upon standard blend skinning techniques, we introduce target-aware temporal skinning weights. The weights describe how the underlying human skeleton dynamically affects the mesh vertices according to the garment and body shape, as well as the motion state. We validate our method on various garments, bodies, and motions through extensive ablation studies. Finally, we conduct comparisons to confirm its superiority in generalization, deformation quality, and performance over several state-of-the-art methods.

![](/images/research/SpectralGraph/figOverview.jpg){: .align-center .percentage-resize-img}

## Article

"Spectrum-Enhanced Graph Attention Network for Garment Mesh Deformation." *IEEE Transactions on Pattern Analysis and Machine Intelligence*. [Article](https://shirui-homepage.com/){: .btn} [GitHub Repo](https://github.com/GlowingHorse/){: .btn}

<!-- <video width="300" class="align-center" controls>
    <source src="/images/research/SEGA/sega-supp-lowest.mp4" type="video/mp4">
</video> -->
