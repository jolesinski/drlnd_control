Project 2: Continuous Control
=====================

## Introduction
A solution to Reacher Unity Environment - second project in Udacity's [Deep Reinforcement Learning Nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893).

## Project details
The task is to train an agent to operate a double-jointed arm and reach to the target location.

A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The state space has 33 dimensions corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

This project provides a solution to the second reacher environment, which contains 20 identical agents, each with its own copy of the environment.
In order to solve the environment, the agents must get an average score of +30 (over 100 consecutive episodes, and over all agents).

```
Number of agents: 20
Size of each action: 4
There are 20 agents. Each observes a state with length: 33
The state for the first agent looks like: [ 0.00000000e+00 -4.00000000e+00  0.00000000e+00  1.00000000e+00
 -0.00000000e+00 -0.00000000e+00 -4.37113883e-08  0.00000000e+00
  0.00000000e+00  0.00000000e+00  0.00000000e+00  0.00000000e+00
  0.00000000e+00  0.00000000e+00 -1.00000000e+01  0.00000000e+00
  1.00000000e+00 -0.00000000e+00 -0.00000000e+00 -4.37113883e-08
  0.00000000e+00  0.00000000e+00  0.00000000e+00  0.00000000e+00
  0.00000000e+00  0.00000000e+00  3.25389481e+00 -1.00000000e+00
  7.30836487e+00  0.00000000e+00  1.00000000e+00  0.00000000e+00
  1.23100638e-01]
```

## Getting Started
In order to setup your Python environment, follow the instructions in the [DRLND GitHub repository](https://github.com/udacity/deep-reinforcement-learning/blob/master/README.md#dependencies). This solution was prepared under Ubuntu 20.04 so take the path for Linux setup.

Apart from Python dependencies, Reacher Unity Environment is automatically fetched by the training notebook.

## Instructions
After dependencies and conda environment setup, start jupyter notebook
```
conda activate drlnd
jupyter notebook
```

In jupyter open Continuous_Control.ipynb and select `drlnd` as active kernel.
Run cells up to "4. Train the agent" section if you want to perform training and save model parameters.
Skip section "4. Train the agent" if you want to load pretrained model and evaluate the agent.
