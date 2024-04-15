---
title: CNN
date: 2024/4/7
categories:
  - 深度学习
---

## 性质

CNN（Convolve Neural Network）是一种前馈神经网络

受生物学上感受野的机制提出的

## 结构特点

- 局部连接
- 权值共享
- 池化（pooling）

## 卷积（Convolve）

卷积以后图像的大小

$$
(M-K+2P)/S+1
$$

卷积核参数的个数

$$
UVD+1
$$

每个卷积核都有 UV 个参数再加上偏置项一个参数

### 互相关

互相关是不翻转卷积核的卷积。

## CNN的反向传播算法


