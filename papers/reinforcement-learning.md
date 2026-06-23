# 强化学习 Reinforcement Learning

本页用于整理强化学习方向的论文、课程与代码资源。

## 入门综述 / 学习入口

### OpenAI Spinning Up in Deep RL
- 链接：<https://openai.com/index/spinning-up-in-deep-rl/>
- 代码：<https://github.com/openai/spinningup>
- 简介：适合入门深度强化学习的经典教学资源。
- 推荐理由：对 PPO、SAC、DDPG、TD3 等主流算法有清晰梳理。

## 经典论文

### DQN — Human-level Control through Deep Reinforcement Learning
- 链接：<https://deepmind-media.storage.googleapis.com/dqn/DQNNaturePaper.pdf>
- 简介：把深度学习和 Q-learning 结合起来的里程碑工作。
- 推荐理由：现代深度强化学习的重要起点。

### PPO — Proximal Policy Optimization Algorithms
- 链接：<https://arxiv.org/abs/1707.06347>
- 简介：最常见的 policy gradient / actor-critic 基线之一。
- 推荐理由：稳定、易用，很多新工作都会拿它做 baseline。

### SAC — Soft Actor-Critic
- 链接：<https://arxiv.org/abs/1801.01290>
- 简介：最大熵强化学习代表方法。
- 推荐理由：连续控制任务里非常重要。

## 近期 / 常用代码资源

### Stable-Baselines3
- 链接：<https://github.com/DLR-RM/stable-baselines3>
- 简介：成熟稳定的 PyTorch RL 工具库。
- 推荐理由：适合快速搭建实验 baseline。

### CleanRL
- 链接：<https://github.com/vwxyzjn/cleanrl>
- 简介：高可读性的单文件 RL 实现。
- 推荐理由：适合阅读源码、改算法和做科研复现。
