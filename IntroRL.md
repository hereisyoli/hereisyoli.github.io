# IntroRL



• Lecture 1: Overview

• Lecture 2: Markov Decision Process

• Lecture 3: Model-free Prediction and Control

• Lecture 4: On-policy and Off-policy Learning

• Lecture 5: Value Function Approximation

• Lecture 6: Policy Optimization: Foundation

• Lecture 7: Policy Optimization: State of the Art 

• Lecture 8: Model-based RL

• Lecture 9: Case Study on AlphaGo series

• Lecture 10: Case Study on AlphaStar and OpenAI Five

• Lecture 11: Distributed computing and RL system design 

• Lecture 12: Generative Modeling



##### supervising learning 监督学习

- annotated image
- Learns can told what label 标签修正预测
- 数据尽可能没有关联



##### reinforcement learning

- 没有很好反馈，但依然通过环境学习
- <img src="/Users/yoliwu/Library/Application Support/typora-user-images/image-20201020114407683.png" alt="image-2001020114407683" style="zoom:30%;" />





#### Difference between Reinforcement Learning and Supervised Learning

- Sequential data as input (not i.i.d)
- The learner is not told which actions to take, but instead must discover which actions yield the most reward by trying them.
- Trial-and-error exploration (balance between exploration and exploitation)
- There is no supervisor, only a reward signal, which is also delayed

