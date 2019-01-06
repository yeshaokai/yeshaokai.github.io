---
title: "A Unified Framework of DNN Weight Pruning and Weight Clustering/Quantization Using ADMM"
collection: publications
permalink: /publication/Weight Pruning and Clustering/Quantization
excerpt: "<img src='/images/ADMM_quantization.png' style='max-height:150px;'>"

date: 2018-11-5
venue: "NECV"

citation: '<b>Shaokai Ye</b> *, Tianyun Zhang*, Kaiqi Zhang, 
Jiayu Li, Jiaming Xie, Yun Liang, Sijia Liu, Xue Lin, Yanzhi Wang 
<i>New England Computer Vision </i> <b>NECV(Oral)</b>'
---
<img src='/images/ADMM_quantization.png' style='max-height:300px;'>

[[ArXiv]](https://arxiv.org/pdf/1811.01907.pdf)

## Abstract
Many model compression techniques of Deep Neural Networks (DNNs) have been investigated, including weight
pruning, weight clustering and quantization, etc. Weight
pruning leverages the redundancy in the number of weights
in DNNs, while weight clustering/quantization leverages the
redundancy in the number of bit representations of weights.
They can be effectively combined in order to exploit the maximum degree of redundancy. However, there lacks a systematic investigation in literature towards this direction.
In this paper, we fill this void and develop a unified, systematic framework of DNN weight pruning and clustering/quantization using Alternating Direction Method of Multipliers (ADMM), a powerful technique in optimization theory to deal with non-convex optimization problems. Both
DNN weight pruning and clustering/quantization, as well
as their combinations, can be solved in a unified manner.
For further performance improvement in this framework, we
adopt multiple techniques including iterative weight quantization and retraining, joint weight clustering training and
centroid updating, weight clustering retraining, etc. The proposed framework achieves significant improvements both in
individual weight pruning and clustering/quantization problems, as well as their combinations. For weight pruning alone,
we achieve 167× weight reduction in LeNet-5, 24.7× in
AlexNet, and 23.4× in VGGNet, without any accuracy loss.
For the combination of DNN weight pruning and clustering/quantization, we achieve 1,910× and 210× storage reduction of weight data on LeNet-5 and AlexNet, respectively,
without accuracy loss. Our codes and models are released at
the link http://bit.ly/2D3F0np