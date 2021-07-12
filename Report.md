# Report

We used a Deep Q-Network (DQN) trained over 2000 episodes with a maximum timesteps per episode of 1000, and an epsilon value going from 1.0 to 0.01 with an epsilon decay of 0.995. The model uses two neural networks that each consist of three linear layers. The neural nets have an input size equal to the number of states (37) and an output size equal to the number of actions (4). The hidden layers have 64 nodes.

The model used a buffer size of 1e5, a batch size of 64, a discount factor (gamma) of 0.99, a tau factor for the update of the target network of 1e-3 and a learning rate of 5e-4. Updates occur every 4 time steps.

The average reward obtained over the last 100 episodes was of 15.70. The progression can be seen on the following graph:

![image](https://user-images.githubusercontent.com/38821613/125259636-7ee45b80-e2cd-11eb-95fd-594e78a02531.png)

Using the threshold of an average score of 13 over 100 episodes, the environment has been solved after 600 episodes.

These results could be improved by using the six improvement to DQN used in the Rainbow algorithm (https://arxiv.org/abs/1710.02298)
