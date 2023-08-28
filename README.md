# Gridworld_with_Reinforcement_learning
A simple gridworld environment and an agent that can navigate through it using Q-learning. We set up the environment, define the agent, and then train the agent.

1. The Gridworld Environment:
-A 10x10 grid.
-Start position at the top-left corner.
-Instead of a single goal, we have multiple goals with different rewards.
-A few obstacles in between.

2. The Agent:
-Can move up, down, left, or right.
-Will use Q-learning to learn the optimal policy.
-Sometimes, when the agent decides to take an action, the environment may not necessarily respond as expected. For instance, if the agent decides to move right, there might be a small chance it ends up moving up instead. (slip_prob)
-As the agent learns more about its environment, it should rely less on exploration and more on exploiting the knowledge it has gathered. (decay_epsilon)
