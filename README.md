# RL-intro
Author: Maarten Fish

## A collection of insightful notebooks and learning tools
Big thanks to my internship mentor [Jeroen](https://github.com/jeroenboeye) and the rest of the team for reviewing my notebooks.

# [Reinforcement Learning: An introduction (pdf)](http://incompleteideas.net/book/RLbook2020.pdf)
Python exploration as a supplement to the 'RL bible' by Richard S. Sutton and Andrew G. Barto

# Part One:
Chapter 2: **Multi-armed Bandits**  
[k_armed_bandit.ipynb](https://github.com/FishMaarten/RL-intro/blob/master/Notebooks/Part1/k_armed_bandit.ipynb):
**Epsilon-greedy** action selection for **exploration vs exploitation** trade-off

Chapter 3: **Finite Markov Decision Process**  
Chapter 4: **Dynamic Programming**  
[grid_world.ipynb](https://github.com/FishMaarten/RL-intro/blob/master/Notebooks/Part1/grid_world.ipynb):
Introducing gridworld with the MDP, **value estimation and control for optimal policy**

Chapter 5: **Monte Carlo Methods**  
[blackjack_mc.ipynb](https://github.com/FishMaarten/RL-intro/blob/master/Notebooks/Part1/blackjack_mc.ipynb):
**OOP blackjack agent & environment** episodic learning using MC for unknowns in MDP

Chapter 6: **Temporal-Difference Learning**  
[temporal_difference.ipynb](https://github.com/FishMaarten/RL-intro/blob/master/Notebooks/Part1/temporal_difference.ipynb):
**On-policy vs off-policy** effects and improvements on some interesting gridworlds.  
[tic_tac_toe.ipynb](https://github.com/FishMaarten/RL-intro/blob/master/Notebooks/Part1/tic_tac_toe.ipynb):
Testing current understanding after first 6 chapters, **Adversarial Q-learning Maker vs Breaker**

Chapter 7: **n-step Bootstrapping**  
[n_step_bootstrap.ipynb](https://github.com/FishMaarten/RL-intro/blob/master/Notebooks/Part1/n_step_bootstrap.ipynb):
**Full recap 1-step TD** and how to modify them to **multi-step** learning algorithms

Chapter 8: **Planning and Learning with Tabular Methods**  
[planning_and_learning.ipynb](https://github.com/FishMaarten/RL-intro/blob/master/Notebooks/Part1/planning_and_learning.ipynb):
Introduction of **long term planning** using **DynaQ** model or **Prioritised Sweeping** stack

# Want to further explore these notebooks?
Run these commands in the terminal:
```
$ git clone https://github.com/FishMaarten/RL-intro
$ cd RL-intro
$ jupyter notebook
```
#### This will clone the repository onto your local machine where you can run the notebooks' code in jupyter
Make sure you have **jupyter** [**installed**](https://jupyter.org/install)... Also comes **pre-installed with** [**anaconda**](https://anaconda.org)
