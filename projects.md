---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

# Car Racer

<img src="/files/carracertd3.png" width="500" height="500" />

In this project, I tackle a simple autonomous driving problem by utilizing Deep Reinforcement Learning. I use OpenAI gym's "CarRacing-v0" learning environment.

- Unlike other approches that use PPO, I implemented TD3 algorithm.

- Rather than using raw screen pixel info, My algorithm extracts LiDar-like features and combines them with IMU sensor data. This approach shrinks the state-space of the problem with a minimal information loss and enables TD3 to solve a signigicantly low-dimensional problem.

- I have also added additional components for the reward signal of the problem. If the vehicle completely leaves the track, then the episode finishes with a penalty. I also observe vehicle stays stationary in some early stages of the training process. So, I penalize the agent and the episode if the vehicle remains stationary for a certain number of time step. This procedure indirectly affects the replay buffer and helps the TD3 agent to update its parameters through more uncorrelated samples.


[Code & Performance](https://github.com/doganjr/carRaceTD3)


