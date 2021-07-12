# udacity-dqn

This project consists of training a Deep Q-Network (DQN) on the Banana Unity ML-Agents environment. This environment has a state space with 37 dimensions, and four discrete actions. A reward of +1 is provided for every yellow banana collected, and -1 for every blue banana. We consider the environment solved when the agent gets a reward of more than 13 over 100.

To train the agent, run all cells in Navigation.ipynb

## Dependencies

To install all dependencies on Ubuntu, follow the instructions below:

1. Create (and activate) a new environment with Python 3.6.

	- __Linux__ or __Mac__: 
	```bash
	conda create --name drlnd python=3.6
	source activate drlnd
	```
	- __Windows__: 
	```bash
	conda create --name drlnd python=3.6 
	activate drlnd
	```
	
2. Follow the instructions in [this repository](https://github.com/openai/gym) to perform a minimal install of OpenAI gym.  
	- Next, install the **classic control** environment group by following the instructions [here](https://github.com/openai/gym#classic-control).
	- Then, install the **box2d** environment group by following the instructions [here](https://github.com/openai/gym#box2d).
	
3. Clone the repository (if you haven't already!), and navigate to the `python/` folder.  Then, install several dependencies.
```bash
git clone https://github.com/udacity/deep-reinforcement-learning.git
cd deep-reinforcement-learning/python
pip install .
```

4. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `drlnd` environment.  
```bash
python -m ipykernel install --user --name drlnd --display-name "drlnd"
```

5. Before running code in a notebook, change the kernel to match the `drlnd` environment by using the drop-down `Kernel` menu. 

6. Download the environment from https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_Novis.zip and unzip it in the project's directory
