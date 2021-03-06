![](https://github.com/andri27-ts/60_Days_RL_Challenge/blob/master/images/logo5.png)

# 强化学习60天
[英文地址](https://github.com/andri27-ts/60_Days_RL_Challenge)

### 我为了你我设计这个挑战：在这60天里深入学习“深度强化学习”。
你肯定听说过 [Deepmind with AlphaGo Zero](https://www.youtube.com/watch?time_continue=24&v=tXlM99xPQC8) 和
[OpenAI in Dota 2](https://www.youtube.com/watch?v=l92J1UvHf6M) 取得的惊人成绩！
你难道不想知道他们是如何工作的吗？现在正是你我最终学会“深度强化学习”，并应用到已有项目的时机。

> 终极目标是使用这些多功能的技术，并应用他们到各种重要的真实世界问题中。**Demis Hassabis**

这个项目引导你完成从最基本的到高级的AlphaGo Zero深度强化学习算法。你可以发现**按周组织的主题**和**建议学习资源**。
同时，每周我会提供用Python实现的**应用实例**，帮助你更好地消化理论。

### 前提
* 了解Python和PyTorch
* 机器学习
* 了解深度学习（MLP，CNN和RNN）

## 项目（待定）
 - **Q-learning**
 - **DQN**
 - **AC2**
 - **ES**
 - **AlphaGo Zero**

## 第一周 - 强化学习介绍

 - #### [强化学习简介](https://space.bilibili.com/253856984/#/)
 - #### [强化学习课程CS294](https://space.bilibili.com/23852932/#/)
 - #### [强化学习：像素乒乓大战](http://ju.outofmemory.cn/entry/319445)

## 第二周 - 强化学习基础: *MDP, Dynamic Programming and Model-Free Control*

> 忘记过去的人，终将重蹈覆辙。 - **George Santayana**

在这一周，我们将会学习基本的强化学习内容，我们将通过评估和优化表示策略和状态的函数去定义现实世界的各类问题。
----

### 理论材料

 - #### [马尔科夫决策过程](https://www.youtube.com/watch?v=lfHX2hHRMVQ&list=PLzuuYNsE1EZAXYR4FJ75jcJseBmo4KQ9-&index=2) - RL by David Silver
   马尔科夫决策过程定义强化学习问题
   - 马尔科夫过程
   - 马尔科夫决策过程

 - #### [动态规划设计](https://www.youtube.com/watch?v=Nd1-UUMVfz4&list=PLzuuYNsE1EZAXYR4FJ75jcJseBmo4KQ9-&index=3) - RL by David Silver
   如何解决马尔科夫决策问题
   - 策略迭代
   - 价值迭代

 - #### [无模型预测](https://www.youtube.com/watch?v=PnHCvfgC_ZA&index=4&list=PLzuuYNsE1EZAXYR4FJ75jcJseBmo4KQ9-) - RL by David Silver
   评估无模型马尔科夫决策过程的价值函数
   - 蒙特卡罗学习
   - 时间差分学习
   - TD(λ)

 - #### [无模型约束](https://www.youtube.com/watch?v=0g4j2k_Ggc4&list=PLzuuYNsE1EZAXYR4FJ75jcJseBmo4KQ9-&index=5) - RL by David Silver
   优化无模型卡尔科夫决策过程价值函数
   - Ɛ贪婪策略迭代
   - GLIE蒙特卡罗搜索
   - SARSA
   - 重要性采样

----

### 本周项目

[Q-learning解决冰冻湖问题](Week2/frozenlake_Qlearning.ipynb). 在本练习中，你将学会使用SARSA或者Q-learning.

----

#### 想知道更多
- 阅读该书的第3,4,5,6,7章节 [Reinforcement Learning An Introduction - Sutton, Barto](https://web.stanford.edu/class/psych209/Readings/SuttonBartoIPRLBook2ndEd.pdf)


## Week 3 - Value Function Approximation and DQN

## Week 4 - A2C and A3C

## Week 5 - RL in continous space - TRPO/PPO

## Week 6 - Evolution Strategies and Genetic Algorithms

## Week 7 - I2A

## Week 8 - AlphaGoZero + Bonus

## Last 4 days - Review + sharing


## 强化学习论文

## 强化学习资源

:tv: [Deep Reinforcement Learning](https://www.youtube.com/playlist?list=PLkFD6_40KJIznC9CDbVTjAF2oyt8_VAe3) - UC Berkeley class by Levine, check [here](http://rail.eecs.berkeley.edu/deeprlcourse/) their site.

:tv: [Reinforcement Learning course](https://www.youtube.com/watch?v=2pWv7GOvuf0&list=PLqYmG7hTraZDM-OYHWgPebj2MfCFzFObQ) - by David Silver, DeepMind. Great introductory lectures by Silver, a lead researcher on AlphaGo. They follow the book Reinforcement Learning by Sutton & Barto.

:notebook: [Reinforcement Learning: An Introduction](https://www.amazon.com/Reinforcement-Learning-Introduction-Adaptive-Computation/dp/0262193981/ref=sr_1_2?s=books&ie=UTF8&qid=1535898372&sr=1-2&keywords=reinforcement+learning+sutton) - by Sutton & Barto. The "Bible" of reinforcement learning. [Here](https://web.stanford.edu/class/psych209/Readings/SuttonBartoIPRLBook2ndEd.pdf) you can find the PDF draft of the second version.


## 额外的资源

:books: [Awesome Reinforcement Learning](https://github.com/aikorea/awesome-rl). A curated list of resources dedicated to reinforcement learning
