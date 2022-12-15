---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
# Reinforcement Learning Based Herd Strategy Development

Leading our team on a competition to design deep reinforcement learning algorithms that learn the most effective offensive, defensive and resource gathering strategies for mixed swarms from air and ground vehicles. The competition is organized by Defence Industry Agency of Turkey. Our team is one of the finalists and competition is ongoing. [Comptetion website](https://y3.ssyz.org.tr/y3/competition/suru)

# Car Racer

<img src="/files/carracertd3.png" width="500" height="500" />

In this project, I tackle a simple autonomous driving problem by utilizing Deep Reinforcement Learning. I use OpenAI gym's "CarRacing-v0" learning environment. Unlike other approches that use PPO, I implemented TD3 algorithm. Rather than using raw screen pixel info, My algorithm extracts LiDar-like features and combines them with IMU sensor data. This approach shrinks the state-space of the problem with a minimal information loss and enables TD3 to solve a signigicantly low-dimensional problem. I add additional components for the reward signal of the problem. If the vehicle completely leaves the track, then the episode finishes with a penalty. I also observe vehicle stays stationary in some early stages of the training process. So, I penalize the agent and the episode if the vehicle remains stationary for a certain number of time step. This procedure indirectly affects the replay buffer and helps the TD3 agent to update its parameters through more uncorrelated samples.
[Code & Performance](https://github.com/doganjr/carRaceTD3)

# Autonomous Vehicle Navigation with Deep Reinforcement Learning (Databoss Inc.)

<img src="/files/autodrive.png" width="500" height="500" />

Developed various reinforcement learning-based navigation algorithms to realize a self-driving military terrain vehicle while reducing any human intervention to a practical and feasible extent. Our algorithms are mainly based on TD3, DDPG, DQN, and their variants with a meaningful reward shaping to navigate a designated vehicle using end-to-end deep reinforcement learning. 

 I supervised a group of undergraduate students for the EEE493/494-Industrial Design Project course and collaborated with Bilkent University. The aim of the project is to navigate an autonomous vehicle that includes Lidar, ZED Camera, and IMU sensors for a point-to-point navigation task by using end-to-end deep reinforcement learning. I also help them with the coding process of the project.

[Video1](https://drive.google.com/file/d/1cydSGHRMMQOVA6G1NzMHNKAsRVR-L5H2/view?usp=sharing)
[Video2](https://drive.google.com/file/d/11ppiVDL1N6hPjpOGDdNeiUHCq9OpRh_J/view?usp=sharing)
[Video3](https://drive.google.com/file/d/1hQEWFOX1yEn9SXGDKCd9fzIOXB6aueHV/view?usp=sharing)
[Video4](https://drive.google.com/file/d/1ccViVKb2jcc8qpcFWS8wiwZjHxQe9GX8/view?usp=sharing)
[Video5](https://drive.google.com/file/d/1zRpX37QBUa9kl7-plpKz8mWobSLt5BX3/view?usp=sharing)

Research Output:
[Paper](https://doganjr.github.io/files/cicek_navtd3.pdf)
[Code & Performance](https://github.com/doganjr/navTD3)

# MarioDQN

<img src="/files/mariodqn.png" width="500" height="500" />

Developed a Mario Agent that uses a variant of the DQN algorithm to accomplish the first stage of the first world of the Mario Game. I utilize Multi Step returns, Frame Stacking, and add more components to the default Reward Function of the learning environment. In the framework of this project, I presented most recent advances in Deep Reinforcement Learning and gave more details on "How to build a DQN agent", some challenges that may occur, and how to solve them. Here is my presentation record (In Turkish): [YouTube Link](https://www.youtube.com/watch?v=d-zQrNVGfFg) [Code & Performance](https://github.com/doganjr/MarioDQN)

# Spatio-temporal Crime Analysis and Prediction (Databoss Inc.)

Built end-to-end machine learning architectures for large-scale online temporal/spatio-temporal prediction. Analyzed complex spatio-temporal data, including traffic and crime. Designed and implemented a mixture of experts system for spatio-temporal crime analysis and prediction framework with statistical and machine learning based approaches.

# Natural Language Processing (Databoss Inc.)

Created anomaly detection algorithms optimized for social media related applications. Developed natural language processing frameworks for sentiment
detection, named entity recognition, and document categorization.