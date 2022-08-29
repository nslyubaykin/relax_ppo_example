# Example PPO implementation with [ReLAx](https://github.com/nslyubaykin/relax)

This repository contains an [implementation](https://github.com/nslyubaykin/relax_ppo_example/blob/master/ppo_example.ipynb) of proximal policy optimization (PPO) with ReLAx.

PPO actor was trained on Ant-v2 Mujoco Gym environment for 4m env-steps. 

The graph of average return vs training step is shown below (`batch_size=40000`):

![ppo_training](https://github.com/nslyubaykin/relax_ppo_example/blob/master/ppo_training.png)

__Resulting Policy__:

https://user-images.githubusercontent.com/67604207/187160002-9357e3b7-ebc6-4880-8e44-37f92e6e2ebf.mp4
