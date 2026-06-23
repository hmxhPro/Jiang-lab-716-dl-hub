# 交通信号灯控制 Traffic Signal Control

本页面向组内“基于强化学习的交通信号灯控制”方向，整理入门综述、代表论文与可直接上手的环境 / 代码资源。

## 入门综述

### A Survey on Traffic Signal Control Methods
- 链接：<https://arxiv.org/abs/1904.08117>
- 配套站点：<https://traffic-signal-control.github.io/survey.html>
- 简介：交通信号控制综述，覆盖传统方法和 RL 方向文献。
- 推荐理由：适合新成员快速建立研究全景。

### Diagnosing Reinforcement Learning for Traffic Signal Control
- 链接：<https://arxiv.org/abs/1905.04716>
- 简介：分析 RL 在交通信号控制中为什么有效、问题在哪里。
- 推荐理由：适合在做实验前先理解任务建模与评测陷阱。

## 必读代表论文

### IntelliLight: A Reinforcement Learning Approach for Intelligent Traffic Light Control
- 链接：<https://jhc.sjtu.edu.cn/~gjzheng/paper/kdd2018_intellilight/kdd2018_intellilight_paper.pdf>
- 简介：较早期的 RL 交通灯控制代表工作之一。
- 推荐理由：适合理解单路口 RL traffic signal control 的基础设定。

### PressLight: Learning Max Pressure Control to Coordinate Traffic Signals in Arterial Network
- 链接：<https://faculty.ist.psu.edu/jessieli/Publications/2019-KDD-presslight.pdf>
- 简介：把 max-pressure 思想与 RL 结合的经典工作。
- 推荐理由：是交通信号控制方向非常有代表性的论文。

### CoLight: Learning Network-level Cooperation for Traffic Signal Control
- 链接：<https://arxiv.org/abs/1905.05717>
- 代码：<https://github.com/wingsweihua/colight>
- 简介：强调多路口协同控制。
- 推荐理由：适合理解多智能体 / 图结构协作思路。

### FRAP: Learning Phase Competition for Traffic Signal Control
- 链接：<https://arxiv.org/abs/1905.04722>
- 简介：从“相位竞争”角度设计交通信号控制模型。
- 推荐理由：在 reward / state 设计之外，方法设计也很有启发。

### AttendLight: Universal Attention-Based Reinforcement Learning Model for Traffic Signal Control
- 链接：<https://arxiv.org/abs/2010.05772>
- 简介：Attention 机制用于交通信号控制的代表工作。
- 推荐理由：适合做方法扩展时参考。

## 环境 / 数据 / 代码

### CityFlow
- 代码：<https://github.com/cityflow-project/CityFlow>
- 论文：<https://arxiv.org/abs/1905.05217>
- 简介：大规模城市交通仿真环境。
- 推荐理由：交通信号灯控制方向非常关键的实验平台。

### RL_signals
- 链接：<https://github.com/traffic-signal-control/RL_signals>
- 简介：交通信号控制方向的论文、数据、模拟器整理仓库。
- 推荐理由：适合查论文脉络和找开源实现。

### LibSignal
- 项目主页：<https://darl-libsignal.github.io/>
- 代码：<https://github.com/DaRL-LibSignal/LibSignal>
- 简介：跨模拟器的 traffic signal control 开源库。
- 推荐理由：适合统一比较不同 RL 方法。

## 建议阅读顺序

1. 先读综述，建立领域地图。
2. 再读 IntelliLight → PressLight → CoLight / FRAP。
3. 同时熟悉 CityFlow、LibSignal 这些实验平台。
4. 最后再结合组内问题设计 reward、state、coordination 方案。
