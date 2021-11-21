# DQN: Navigation
This project was provided by the Deep Reinforcement Learning Nanodegree Course of Udacity.

![Alt Text](https://video.udacity-data.com/topher/2018/June/5b1ab4b0_banana/banana.gif)

# Dependency
Python 3<br/>
Pytorch<br/>
UnityEnvironment<br/>

# Project Overview
The goal is to train an agent to navigate (and collect bananas!) in a large, square world using deep Q network.

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

0 - move forward.<br/>
1 - move backward.<br/>
2 - turn left.<br/>
3 - turn right.<br/>
The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

