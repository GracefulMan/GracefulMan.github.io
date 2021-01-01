## 欢迎参观小马学习小屋

大家好，我是小马，想在这里整理一些自己所学的东西，留下一丝痕迹。

## 个人笔记

小马目前在采用强化学习做主动导航的相关研究，对相关内容的知识点进行整理的同时加入了一些自己对内容的理解。具体内容可[见个人笔记](https://www.yuque.com/mahongying?tab=books).

主要内容包括以下几个部分：
* 强化学习基础及算法实现
* 强化学习论文讲解
* 主动导航论文讲解
* 基础的数学知识
* 个人对生活的感想

欢迎大家评论。

### 强化学习基础
已更新章节内容：

* [强化学习简介](https://www.yuque.com/mahongying/reinforcement_learning/introduction)
    * 主要内容：强化学习定义，Policy、Value function和Model的概念。


### 强化学习算法实现
本章内容涉及深度强化学习时，均使用深度学习框架pytorch实现。

已更新算法：

* [Q Learning](https://github.com/GracefulMan/reinforcement_learning/tree/main/Q_learning)
    * model-free
    * off-policy
    * discrete action space(or small action space).
* [Sarsa](https://github.com/GracefulMan/reinforcement_learning/tree/main/Sarsa)
    * model-free
    * on-policy
    * discrete action space(or small action space).
* [Deep Q Learning](https://github.com/GracefulMan/reinforcement_learning/tree/main/DQN)
    * model-free
    * off-policy
    * continuous action space(or large action space).

### 主动导航论文讲解
已更新内容：

* [Learning to Explore Using Neural Active SLAM](https://www.yuque.com/mahongying/navigation/active_neural_slam)
    * 目标：有效探索地图内容
    * 关键词：定位、建图、环境探索
