---
title: "ML: Reinforcement from scratch"
date: 2019-03-21
permalink: /posts/2019/03/reinforcement/
tags:
  - adavanced
  - machine learning
  - python
---

_Machine Learning: An article explores reinforcement learning._

### What is Reinforcement learning?

Whether we are playing chess or learning to drive a car, we are acutely aware of how our environment responds to what we do, and we seek to influence what happens through our behavior. Reinforcement Learning
learns from interaction. The task of it is to learn how to behave to achieve a goal. 

#### Some features of reinforcement learning

Reinforcement learning 1) much more focused on goal-directed learning, and 2) it explicitly considers the whole problem of a goal-directed agent interacting with an uncertain environment.

### Different types of learning

1) **Supervised Learning** is learning from a training set of labeled examples provided by a knowledgable external supervisor. The object of this kind of learning is for the system to extrapolate, or generalize, its responses so that it acts correctly in situations not present in the training set.

2) **Unsupervised Learning** is typically about finding structure hidden in collections of unlabeled data.

3) **Reinforcement Learning** is trying to maximize a reward signal instead of trying to find hidden structure.

### Markov decision processes

#### Firstly, we have to clarify the decision

A single decision is made from multiple discrete actions, and each action has an associated reward. The goal is to maximize the reward. We can pick the action with the largest reward each time (e.g. *greedy*). 

The problem of reinforcement learning using ideas from dynamical systems theory, specifically, as the optimal control of incompletely-known Markov decision processes. The basic idea is simply to capture the most important aspects of the real problem facing a learning agent interacting over time with its environment to achieve a goal. **Each decision affects subsequent decisons.** 1) A learning agent must be able to sense the state of its environment to some extent and must be able to take actions that aspect the state. 2) The agent also must have a goal or goals relating to the state of the environment.

### Exploration vs Exploitation

One of the challenges that arise in reinforcement learning, and not in other kinds of learning, is the trade-off between exploration and exploitation. To obtain a lot of reward, a reinforcement learning agent must prefer actions that it has tried in the past and found to be effective in producing reward. But to discover such actions, it has to try actions that it has not selected before. The agent has to exploit what it has already experienced in order to obtain reward, but it also has to explore in order to make better
action selections in the future. The agent must try a variety of actions and progressively favor those that appear to be best.



All involve interaction between an active decision-making agent and its environment, within which the agent seeks to achieve a goal despite uncertainty about its environment. The agent’s actions are permitted to affect the future state of the environment (e.g., the next chess position, the level of reservoirs of the refinery, the robot’s next location and the future charge level of its battery), thereby a↵ecting the actions and opportunities available to the agent at later times. Correct choice requires taking into account indirect, delayed consequences of actions, and thus may require foresight or planning.

the effects of actions cannot be fully predicted; thus the agent must monitor its environment frequently and react appropriately. the agent can use its experience to improve its performance over time.

### Elements of Reinforcement Learning

**Policy**, **Reward**, **Value function**, and **Model of the environment**.

Policy defines the learning agent's way of behaving at a given time. It is a mapping from perceived states of the environment to actions to be taken when in those states.

Reward defines the goal of a reinforcement learning problem. The environment returns the agent a value as reward at each step. The goal of the learning is simply maximize the rewards.

Value function is different with the reward signal. It defines what is good running the policy from the step, rather than an immediate step.

Model of the environment mimics the behavoir of the environment. It allows infereence to be made about how the environment will behave.


### Off policy vs On policy

The on-policy learners evaluate the policy that is used to make decisions. It is influeneced by
exploration policy. Off-policy method evaluate policy that is different from what has been used to
generate the data, it is not dependent on the exploration policy. 

For example: 
On-policy learner: SARSA; 

Off-policy learner: Q-learning.


