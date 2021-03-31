---
title: "Reinforcement Learning"
date: 2021-03-30T21:48:37-04:00
draft: false
tags: ["rl", "robotics","english"]
series: ["RL"]
categories: ["Learning"]
img: ""
summary: "Lecture notes for WPI CS525 RL."
---

# Reinforcement Learning 
## Lecture 1
Sparse reward -- only get the reward at the very last step (e.g. win or lose)

Differences between RL and other machine learning paradises:

AI planning --> known the environment dynamics --enumerate
Supervised Learning --> Learning with labels
Unsupervised Learning --> Learning without labels
Imitation Learning --> Reverse Reinforcement Learning

4 key aspects of RL:
- Optimization
- Exploration
- Generalization
- Delayed consequences

## Supervised Learning 
Optimization -- minimize the miss classified loss
Generalization -- from training data to test data

## Unsupervised Learning 
Optimization -- minimize the total distance 
Generalization -- choose an smallest distance to one centroid

## Imitation Learning 
Optimization. --maximize the similarity of the observed data
Generalization 
Delay consequences -- Maybe --Because the problem itself might be a time-sequence problem
No Exploration
