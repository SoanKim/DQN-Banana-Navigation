# Report
This project is based on the code of [solution/Deep_Q_Network_Solution.ipynb solution](https://github.com/udacity/deep-reinforcement-learning/tree/master/dqn/solution).

# Hyperparameters
<pre>
BUFFER_SIZE = int(1e6)  # replay buffer size </br>
BATCH_SIZE = 128        # minibatch size </br>
GAMMA = 0.99            # discount factor </br>
n_episode = 2000        # maximum number of training episodes</br>
max_t = 1000            # maximum number of timesteps per episode</br>
eps_start = 1.0         # starting value of epsilon, for epsilon-greedy action selection</br>
eps_end =0.01           # minimum value of epsilon</br>
eps_decay =0.995        # multiplicative factor (per episode) for decreasing epsilon</br>
</pre>

# The Result Plot
<img src="https://github.com/SoanKim/DQN-Banana-Navigation/blob/main/reward_plot.png" width="400">

# Ideas for Future Work
* Hyperparameters would be fine-tuned.
* [Prioritized Experience Replay](https://arxiv.org/abs/1511.05952) would be implemented. 
* [Dueling Network](https://arxiv.org/pdf/1511.06581.pdf) would be implemented. 
