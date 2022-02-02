---
title: "Attribution-Based Pruning"
layout: single-portfolio
excerpt: "<img src='/images/research/AttrPrune/attr-prune-teaser.jpg' alt=''>"
collection: research
order_number: 40
header: 
  og_image: "research/AttrPrune/attr-prune-teaser.jpg"
---

Network pruning is a general technique to reduce the weight size and inference time in edge devices. The common idea of network pruning is to rank all convolutional kernels with respect to their contributions to the overall performance under a specific task. Different from the pruning method designed for multiple-class detection networks, our pruning method is aimed at the scene of single class, such as **mango** detection in orchard. Specially, we propose a general pruning method to reduce a large-scale detection network into a small and single-class detection network based on our proposed attribution calculation method. The experiments show that our method can significantly shrink the model size and computation cost with little accuracy loss.

![](/images/research/AttrPrune/attr-prune-teaser.jpg){: .align-center .percentage-resize-img}

![](/images/research/AttrPrune/detMangoResultb.jpg){: .align-center .small-percentage-resize-img}

## Article

"An attribution-based pruning method for real-time mango detection with YOLO network." *Computers and Electronics in Agriculture*. [Article](https://www.sciencedirect.com/science/article/pii/S0168169919313717?dgcid=author){: .btn .btn-green} [GitHub Repo](https://github.com/GlowingHorse/Fast-Mango-Detection){: .btn .btn-green}

## Other Applications

We also find this method can be easily applied to other similar scenes. In OpenCV AI competition, we use the pruning method to design a fast **strawberry** detection network and apply it to a mobile device named [OAK-D](https://opencv.org/opencv-ai-competition-2021/#introSection) (a neural computating CPU + a binocular stereo camera). [GitHub Repo](https://github.com/GlowingHorse/OAKD-yolov4-tiny-tf2-strawberry){: .btn .btn-green}

![](/images/research/AttrPrune/detect_strawberry.png){: .align-center .percentage-resize-img}

![](/images/research/AttrPrune/detect_strawberry2.png){: .align-center .percentage-resize-img}
