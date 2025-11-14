## Tabular RL / Dynamic Programming

This repository contains implementations of classic tabular Reinforcement Learning algorithms based on Dynamic Programming (DP). These are model-based algorithms that assume full knowledge of the environment’s dynamics (transition probabilities and rewards).

It is designed to demonstrate exact solution methods for small, fully tabular environments. The algorithms included are suitable for educational purposes and benchmarking in environments such as:

FrozenLake-v1

CliffWalking-v0

Taxi-v3

Algorithms implemented:

Value Iteration: Finds the optimal value function and policy by iteratively applying the Bellman optimality equation.

Policy Iteration: Alternates between evaluating a policy exactly and improving it greedily until convergence.

⚠ Note: These algorithms require access to the environment’s transition model (P(s'|s,a)) and reward function. For Gymnasium environments, you may need Gym version 0.21 or custom tabular environments.
