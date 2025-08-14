---
title: 基于NeRF对VR头戴相机进行图像稳定
date: 2023-06-01
external_link: ''
tags:
  - NeRF
  - 三维重建
---

该项目进行于苏黎世联邦理工的Computer Vision and Geometry组。

描述：
  - 在“Depth-Supervised NeRF”的基础上对其流程进行修改和拓展，从而使用深度先验来重建室内环境
  - 实现“Deblur-NeRF”, 通过运动先验来对带有运动模糊的输入图像进行去噪声学习，在VR中渲染模型来实现图像稳定
  - 在只使用有限的训练视角且输入图像有运动噪声的情况下，对卧室环境达到了相对较好的三维重建质量

<!--more-->
