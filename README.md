# Deep Reinforcement Learning Agent for playing tennis game


![Environment](tennis.png)


In this [environment](https://github.com/Unity-Technologies/ml-agents/blob/main/docs/Learning-Environment-Examples.md#tennis), two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). Specifically, After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores. This yields a single score for each episode.

The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5.

## How to get started ?
- Gain a basic understanding of [Unity Environment](https://github.com/Unity-Technologies/ml-agents/blob/main/docs/Learning-Environment-Examples.md#tennis)
- Set up a Python 3.6 Environment to install [Dependencies](https://github.com/udacity/deep-reinforcement-learning#dependencies) involving PyTorch, the ML-Agent toolkit and a few more Python packages.
- Download a Unity Environment for [Windows(64-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)/[Windows(32-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)/[Mac OSX](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)/[LINUX](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
- Run [Tennis.ipynb](https://github.com/SHIVOH/MADDPG-agent-for-playing-tennis/blob/main/Tennis.ipynb)
## My Solution
![image](https://github.com/SHIVOH/MADDPG-agent-for-playing-tennis/blob/main/drl3.png)
- Do checkout my [Report](https://github.com/SHIVOH/MADDPG-agent-for-playing-tennis/blob/main/Report.ipynb) for understanding my implementation
