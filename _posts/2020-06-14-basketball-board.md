---
title: Always-In Basketball Backboard
date: 2020-06-14
permalink: /posts/2020/06-basketball-board
excerpt_separator: <!--more-->
toc: true
tags:
  - Gaussian sampling
  - Linear regression
---

Create a basketball backboard that can make your shot always in. [GitHub Repo](https://github.com/GlowingHorse/BasketballHoop){: .btn .btn-green}

<!--more-->

Youtube and Weibo have a very popular video. In simple terms, it is how to design a backboard that can make your shot always ing. I used Python to implement the code according to the author's ideas. Judging from the simulation results, this backboard can achieve a perfect shot when shooting from most positions on the court.

- Weibo link (with Chinese subtitles): [https://weibo.com/2214257545/J0xG8otx5](https://weibo.com/2214257545/J0xG8otx5)
- Original YouTube link: [https://www.youtube.com/watch?v=vtN4tkvcBMA&t=551s](https://www.youtube.com/watch?v=vtN4tkvcBMA&t=551s)

### Introduction to the process:
* First divide the backboard into many small pieces, and then shoot at a parabola with different speeds and different angles at different positions on the basketball court. After hitting the board (hit a small backboard), calculate the pop-up angle and the desired angle respectively, and then adjust this small backboard according to the normal vector. The normal vector that needs to be adjusted for all small backboards and the normal vector before the adjustment form an objective estimation function.
* Then he kept shooting and adjusted the normal vector of small backboards, and finally got a backboard that could be scored anyway after convergence. But this backboard is still composed of many small blocks, not continuous. In order to be more realistic, these discrete small pieces are fitted into a smooth surface as much as possible.

### Technology applied:
* Shot data-> Gaussian distribution sampling (the original author used Monte Carlo)
* Calculate incidence angle and pop-up angle-> High school physical parabolic motion + coordinate system conversion
* Speed after rebound-> High school physical elastic collision
* Error estimation function-> sum of n sub-functions of n small blocks + coordinate ascent algorithm
* Smooth rebound-> Linear regression model

### Problem analysis:
In the end, my result is not as beautiful as the original video. It may be because the formula of the parabolic movement is deviated. In addition, I did not consider the motion curve of the first half of the basketball when shooting. On the whole, there are many details that can be improved. For example, the influence of the centrifugal force of the ball rotation on the ejection angle and the influence of the air resistance during the ball movement should also be considered. The algorithm for the physical characteristics is expected.

![](/images/post/basketball-board/all-in-basketball-hoop.gif){: .align-center .fifty-percentage-resize-img}s