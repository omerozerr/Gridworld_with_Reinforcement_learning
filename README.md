
# Gridworld with Reinforcement Learning
A simple gridworld environment and an agent that navigates through it using Q-learning. We set up the environment, define the agent, and then train the agent.

## 1. The Gridworld Environment
#### Grid Size: A 10x10 grid.
#### Start Position: Positioned at the top-left corner.
#### Goals: Instead of a single goal, we have multiple goals with varying rewards.
#### Obstacles: The grid contains a few obstacles the agent must navigate around.
## 2. The Agent
#### Movements: The agent can move up, down, left, or right.
#### Learning Method: Employs Q-learning to deduce the optimal policy.
#### Stochastic Environment: Sometimes, the agent's chosen action might not result in the expected movement. For instance, if the agent opts to move right, there's a slight possibility it could end up moving up. This is governed by slip_prob.
#### Exploration vs. Exploitation: As the agent becomes more familiar with its environment, it increasingly depends on exploiting its accumulated knowledge, decreasing its exploration rate. This is controlled by decay_epsilon.
