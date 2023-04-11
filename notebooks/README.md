# Collection of Notebooks for experimentation with different Decision Making Techniques

Jupyter notebooks for testing RL functionality.

## Conda Environment

Install conda environment and necessary dependencies 

```
conda env update --file environment.yml 
conda activate
cd .. 
git submodule init
cd notebooks
```

## Notebook Collection

Short description for topics for each notebook:

|Name|Description|
|----|-----------|
|`actor_critic_experiment`|Experimentation with actor critic implementation from [this](https://towardsdatascience.com/understanding-actor-critic-methods-931b97b6df3f) blog post using [Gymnasium HighwayEnv](https://github.com/Farama-Foundation/HighwayEnv) |
|`ddqn_experiment`|Experimentation with  Dueling DQN algorithm implementation from [this](https://pytorch.org/tutorials/intermediate/reinforcement_q_learning.html) blog post using [Gymnasium HighwayEnv](https://github.com/Farama-Foundation/HighwayEnv) |
|`highway_environment`| Detailed explanation and analysis of [Gymnasium HighwayEnv](https://github.com/Farama-Foundation/HighwayEnv) |
|`maximal_reward_policy_experiment`| Analysis of greedy best reward lookahead algorithms on [Gymnasium HighwayEnv](https://github.com/Farama-Foundation/HighwayEnv) |
|`q_learning_with_dqn`|Experimentation with canonical double DQN implementation from [official Pytorch Website](https://pytorch.org/tutorials/intermediate/reinforcement_q_learning.html)|
|`reinforce_algorithm`|Experimentation with  Dueling DQN algorithm implementation from [this](https://medium.com/@thechrisyoon/deriving-policy-gradients-and-implementing-reinforce-f887949bd63) blog post using [Gymnasium HighwayEnv](https://github.com/Farama-Foundation/HighwayEnv)|
|`rl-agents_experiments`|Experimentation with different out of the box implementations from [rl-agents](https://github.com/eleurent/rl-agents)|
|`stable_baselines3_experiments`|Experimentation with different out of the box implementations from [stable-baselines](https://github.com/DLR-RM/stable-baselines3)|