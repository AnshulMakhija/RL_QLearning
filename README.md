To understand how an agent learns from experience, I built a custom grid environment from scratch where:
  - The agent starts at one corner
  - The goal is in another
  - And it receives +10 reward for reaching the goal, -1 for every move

I implemented the full Q-learning algorithm:
  - Defined the Q-table manually (state x action values)
  - Used ε-greedy exploration to balance exploration and exploitation
  - Updated Q-values using the Bellman equation

Why Q-Learning?
Q-learning is a great first step into RL because:
  - It doesn’t require knowledge of the environment’s model
  - It teaches how value-based methods help agents learn optimal policies
  - It makes you appreciate how trial-and-error translates into decision making
