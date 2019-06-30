# Control-Furuta
codes for control of furuta pendulum with reinforcement learning

ddpg: refer to RL-Adventure-2(https://github.com/higgsfield/RL-Adventure-2/blob/master/5.ddpg.ipynb)

ppo: refer to pg_travel(https://github.com/reinforcement-learning-kr/pg_travel/blob/master/mujoco/agent/ppo_gae.py)

hyperparameter:
1. ddpg
hyperparameter | value  
------|------  
state space dim | 10  
control space dim | 1  
total num. policy params | 40960  
steps per iteration | 3000  
