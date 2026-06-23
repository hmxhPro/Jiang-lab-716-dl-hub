# 车道线检测 Lane Detection

本页面向组内“基于深度学习的车道线检测”方向，整理综述、经典论文、常用基准与代码资源。

## 入门综述

### Lane Detection: A Survey with New Results
- 链接：<https://cg.cs.tsinghua.edu.cn/people/~mtj/publications/JCST2020-LineDetectionSurvey.pdf>
- 简介：车道线检测方向经典综述。
- 推荐理由：适合快速了解任务定义、数据集和方法演化。

### Monocular Lane Detection Based on Deep Learning: A Survey
- 链接：<https://arxiv.org/abs/2411.16316>
- 简介：较新的单目车道线检测综述。
- 推荐理由：适合了解近年的问题设定和研究趋势。

## 必读代表论文

### SCNN — Spatial as Deep: Spatial CNN for Traffic Scene Understanding
- 链接：<https://aaai.org/papers/12301-spatial-as-deep-spatial-cnn-for-traffic-scene-understanding/>
- 简介：较早的 lane detection 经典工作之一。
- 推荐理由：适合理解结构信息在车道线检测中的作用。

### LaneNet: Real-Time Lane Detection Networks for Autonomous Driving
- 链接：<https://arxiv.org/abs/1807.01726>
- 简介：实时车道线检测代表工作。
- 推荐理由：适合理解分阶段 lane detection 思路。

### Ultra Fast Structure-aware Deep Lane Detection
- 链接：<https://arxiv.org/abs/2004.11757>
- 代码：<https://github.com/cfzd/Ultra-Fast-Lane-Detection>
- 简介：UFLD，实时性与效果兼顾的经典方法。
- 推荐理由：如果你们组做工程落地或实时检测，这篇非常值得读。

### CLRNet: Cross Layer Refinement Network for Lane Detection
- 链接：<https://arxiv.org/abs/2203.10350>
- 代码：<https://github.com/Turoad/CLRNet>
- 简介：CVPR 2022 代表方法。
- 推荐理由：适合作为较新的高质量 baseline。

## 常用数据集 / 工具

### TuSimple Lane Detection Benchmark
- 链接：<https://github.com/TuSimple/tusimple-benchmark>
- 简介：车道线检测常用基准之一。
- 推荐理由：适合入门和快速复现实验。

### LaneDet Toolbox
- 链接：<https://github.com/Turoad/lanedet>
- 简介：整合了 SCNN、RESA、UFLD、LaneATT、CondLane 等多种方法。
- 推荐理由：很适合组内统一维护 lane detection baseline。

## 建议阅读顺序

1. 先读综述，理解车道线检测的任务定义与评测方式。
2. 再读 SCNN、LaneNet，理解早期方法。
3. 然后重点读 UFLD、CLRNet，作为当前更实用的 baseline。
4. 实验上优先从 TuSimple + LaneDet / UFLD 代码开始。
