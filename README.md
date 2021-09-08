# RLCycleA2C    
Lcycle (pronounced as "recycle") is a reinforcement learning (RL) agents framework. RLcycle provides ready-made RL agents, as well as reusable components for easy prototyping.

Currently, RLcycle provides:

DQN + enhancements, Distributional: C51, Quantile Regression, Rainbow-DQN.
Noisy Networks for parameter space noise
A2C (data parallel) and A3C (gradient parallel).
DDPG, both Lillicrap et al. (2015) and Fujimoto et al., (2018) versions.
Soft Actor Critic with automatic entropy coefficient tuning.
Prioritized Experience Replay and n-step updates for all off-policy algorithms.
RLcycle uses:

PyTorch for computations and building and optimizing models.
Hydra for configuring and building agents.
Ray for parallelizing learning.
WandB for logging training and testing.
See below for an introduction and guide to using RLcycle, performance benchmarks, and future plans.


Getting Started
To install:

conda create --name myenv python=3.6.9 pip
conda activate myenv
git clone https://github.com/cyoon1729/RLcycle.git
cd RLcycle
pip install -U -r requirements.txt
pip install -e .
