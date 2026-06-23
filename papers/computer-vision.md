# 计算机视觉 Computer Vision

本页用于整理计算机视觉方向的重要论文、综述、教程与代码资源。

## 入门综述 / 学习入口

### Stanford CS231n
- 链接：<https://cs231n.stanford.edu/2023>
- 简介：CV + 深度学习方向最经典的课程入口之一。
- 推荐理由：课程本身就相当于一份系统的“视觉方向知识地图”。

## 经典论文

### AlexNet — ImageNet Classification with Deep Convolutional Neural Networks
- 链接：<https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-network>
- 简介：深度 CNN 在 ImageNet 上的里程碑工作。
- 推荐理由：是现代深度视觉时代的起点之一。

### VGG — Very Deep Convolutional Networks for Large-Scale Image Recognition
- 链接：<https://arxiv.org/abs/1409.1556>
- 简介：系统展示“加深网络”带来的效果。
- 推荐理由：结构规则、易理解，是很多后续模型的基础参考。

### ResNet — Deep Residual Learning for Image Recognition
- 链接：<https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf>
- 简介：提出残差连接，解决深层网络训练问题。
- 推荐理由：经典中的经典，读懂它对后续看很多视觉论文都很重要。

### U-Net — Convolutional Networks for Biomedical Image Segmentation
- 链接：<https://arxiv.org/abs/1505.04597>
- 简介：分割任务经典架构。
- 推荐理由：编码器-解码器 + skip connection 的思路影响深远。

### ViT — An Image is Worth 16x16 Words
- 链接：<https://arxiv.org/abs/2010.11929>
- 简介：把 Transformer 系统引入图像分类。
- 推荐理由：理解视觉 Transformer 的重要起点。

### Mask R-CNN
- 链接：<https://arxiv.org/abs/1703.06870>
- 简介：目标检测与实例分割经典论文。
- 推荐理由：至今仍是理解检测 / 分割两阶段方法的必读材料。

## 近期代表资源

### CLIP
- 论文：<https://openai.com/research/clip>
- 代码：<https://github.com/openai/CLIP>
- 简介：视觉-语言预训练代表性工作。
- 推荐理由：适合理解多模态表示学习。

## 代码资源

### MMDetection
- 链接：<https://github.com/open-mmlab/mmdetection>
- 简介：CV 研究与复现常用工具箱。
- 推荐理由：做检测、分割类实验时很实用。
