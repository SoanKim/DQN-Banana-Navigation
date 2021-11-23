# DQN: Navigation
This project was provided by [the Deep Reinforcement Learning Nanodegree Course of Udacity.](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893) The agent was trained in Deep Q Network. The DQN (Deep Q-Network) algorithm was developed by [DeepMind in 2015.](https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf) It was able to solve a wide range of Atari games (some to superhuman level) by combining reinforcement learning and deep neural networks at scale. The algorithm was developed by enhancing a classic RL algorithm called Q-Learning with deep neural networks and a technique called experience replay.

# Environment
The project environment is similar to, but not identical to the Banana Collector environment on the Unity [ML-Agents GitHub page](https://github.com/Unity-Technologies/ml-agents/blob/main/docs/Learning-Environment-Examples.md#banana-collector).

![Alt Text](https://video.udacity-data.com/topher/2018/June/5b1ab4b0_banana/banana.gif)

# Dependency
Python 3.6+ [install](https://www.python.org/downloads/) <br/> 
Pytorch 1.1+ [install](https://pytorch.org/get-started/locally/) <br/>
mlagents 0.27.0+ [install](https://pypi.org/project/mlagents/)<br/>

# The Goal of the Project
The goal is to train an agent to navigate (and collect bananas!) in a large, square world using deep Q network. 

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of the agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

``0`` - move forward<br/>
``1`` - move backward <br/>
``2`` - turn left <br/>
``3`` - turn right <br/>
The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

