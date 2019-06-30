# drl_p2

# Summary
Repository for the 2nd project for Deep Reinforcement Learning nanodegree on Udacity.

We apply DDPG to solve a continuous problem where a double-jointed arm can move to target locations

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. 

The task is episodic, and in order to solve the environment, the agent must get an average score of +30 over 100 consecutive episodes.

# Contents

Contains the agent code (`ddpg_agent.py`), neural net code (`model.py`), training notebook (`Continuous_Control.ipynb`), trained model weights for actor (`checkpoint_actor.pth`) and critic (`checkpoint_critic.pth`), and report (`Report.pdf`).

# Instructions

Follow the instructions in `Continuous_Control.ipynb` to train the agent.
