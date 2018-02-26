# Deep reinforcement learning using PyTorch

## Environment
You need to install the following to run this Notebook:
1. PyTorch with Python 3.6.X
2. OpenAI Gym

## Gym Folder
I have implemented REINFORCE and ACTOR-CRITIC in the gym folder.

These are a general description of the Notebooks under that folder:

1. gym/pg-cartpole.ipynb    
This Notebook implements PyTorch's REINFORCE and ACTOR-CRITIC agents for OpenAI's Cartpole. It demonstrates the superiority of Actor-Critic over REINFORCE.

2. gym/reinforce.ipynb    
This Notebook ran Karpathy's numpy implementation of REINFORCE on PONG to 30K episodes. It then adapted PyTorch's REINFORCE agent for Pong and enables it to run with GPU acceleration.

3. gym/actor-critic.ipynb    
This Notebook adapted PyTorch's ACTOR_CRITIC agent for Pong and enables it to run with GPU acceleration.

4. gym/eval_model.ipynb    
This Notebook analyzes the content the model and history files, allowing users to generate images of the weight parameters and plots of scores versus training episodes.

5. gym/downsample.ipynb    
This Notebook look at different ways of downsampling PONG's images down to 40x40 or 80x80 frames.
