---
title: "Free-Swinging Garment Deformation"
layout: single-portfolio
excerpt: "<img src='/images/research/PSDUNet/overview.jpg' alt=''>"
collection: research
order_number: 140
header: 
  og_image: "research/PSDUNet/overview.jpg"
---

Due to the highly nonlinear behavior of clothing, modelling fine-scale garment deformation on arbitrary meshes under varied conditions within a unified network poses a significant challenge. Existing methods often compromise on either model generalization, deformation quality, or runtime speed, making them less suitable for real-world applications. To address it, we propose to incorporate multi-source graph construction and pooling to achieve a novel graph learning scheme. We first introduce methods for extracting cues from different deformation correlations and transform the garment mesh into a comprehensive graph enriched with deformation-related information. To enhance the learning capability and generalizability of the model, we present structure-preserving pooling and unpooling strategies for the mesh deformation task, thereby improving information propagation across the mesh and enhancing the realism of deformation. Lastly, we conduct an attribution analysis and visualize the contribution of various vertices in the graph to the output, providing insights into the deformation behavior. The experimental results demonstrate superior performance against state-of-the-art methods. 

![](/images/research/PSDUNet/overview.jpg){: .align-center .percentage-resize-img}

## Article

"Efficient Deformation Learning of Varied Garments with a Structure-Preserving Multilevel Framework." *ACM SIGGRAPH Symposium on Interactive 3D Graphics and Games*. [Article](https://i3dsymposium.org/2024/papers.html#learning-to-move){: .btn} [GitHub Repo](https://github.com/GlowingHorse/){: .btn}

"SwinGar: Spectrum-inspired neural dynamic deformation for free-swinging garments." *IEEE Transactions on Visualization and Computer Graphics (Presented at Pacific Graphics 2024)*. [Article](https://ieeexplore.ieee.org/abstract/document/10371781){: .btn} [GitHub Repo](https://github.com/GlowingHorse/){: .btn}
