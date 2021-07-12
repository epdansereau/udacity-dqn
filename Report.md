# Report

We used a Deep Q-Network (DQN) trained over 2000 episodes with a maximum timesteps per episode of 1000, and an epsilon value going from 1.0 to 0.01 with an epsilon decay of 0.995. The model uses two neural networks that each consist of three linear layers.

The average reward obtained over the last 100 episodes was of 15.72. The progression can be seen on the following graph:

Using the threshold of an average score of 13 over 100 episodes, the environment has been solved after 600 episodes.

These results could be improved by using the six improvement to DQN used in the Rainbow algorithm (https://arxiv.org/abs/1710.02298)
