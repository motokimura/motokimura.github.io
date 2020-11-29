---
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

## 4th Place Solution for SpaceNet-6 Challenge

Won the 4th place (**top 1%** amoung 400+ teams) at SpaceNet-6 competition held as a aprt of CVPR'20 EarthVision workshop.

In SpaceNet-6 competition, participants were asked to extract building footprints from SAR (Synthetic Aperature Radar) remote sensing imageries.
I developed an effective pipeline combining deep learning based instance segmentation and LGBM (Light Gradient Boosting Machine) post-processing.

See [competition offitial page](https://spacenet.ai/earthvision2020/),
[slides](https://speakerdeck.com/motokimura/4th-place-solution-for-spacenet6-challenge),
[video](https://youtu.be/3t6RN03oR5E),
and [GitHub repository](https://github.com/SpaceNetChallenge/SpaceNet_SAR_Buildings_Solutions/tree/master/4-motokimura) for details.

<img src="/images/portfolio_spacenet6_01.png" width="750">

<img src="/images/portfolio_spacenet6_02.png" width="750">

## Monocular 3D Human Recognition

Implemented ["A simple yet effective baseline for 3d human pose estimation" [Martinez+, ICCV'17]](https://arxiv.org/abs/1705.03098) in PyTorch and reproduced the performance of the original Tensorflow implementation. See [GitHub repository](https://github.com/motokimura/3d-pose-baseline-pytorch).

By integrating this with a monocular object-specific distance estimation method, I've constructed a **monocular** 3D human recoginition system.

<img src="/images/portfolio_3d_human_recognition_01.gif" width="600">

## Gaussian YOLOv3 in PyTorch

Implemented ["Gaussian YOLOv3: An Accurate and Fast Object Detector Using Localization Uncertainty for Autonomous Driving" [Choi+, ICCV'19]](https://arxiv.org/abs/1904.04620) in PyTorch and reproduced the performance of the original Darknet implementation.

See [GitHub repository](https://github.com/motokimura/PyTorch_Gaussian_YOLOv3) for details.

<img src="/images/portfolio_gaussian_yolov3_01.png" width="700">


## Car Counting in Aerail Images

Developed a convolutional neural network to count cars in aerial images.

See [GitHub repository](https://github.com/motokimura/cowc_car_counting) and [blog post (in Japanese)](https://qiita.com/motokimura/items/d155d532a5f1dd02089c) for details.

<img src="/images/portfolio_car_counting_01.png" width="700">
