# Reinforcement-Learning

This project explores foundational concepts in reinforcement learning by using the classic Gridworld environment, a simulated robot controller (Crawler), and the famous game of Pacman.

## Table of Contents

* Overview  
* Gridworld Exploration
* Value Iteration
* Policies Exploration
* Q-Learning
* Epsilon-Greedy Strategy
* Pacman Adventures
* Approximate Q-Learning

### Overview
In the Gridworld environment, agents interact with a two-dimensional grid and attempt to reach an exit. It's a simple environment that demonstrates how agents make decisions and learn from their interactions.

### Gridworld Exploration
Gridworld allows users to control agents manually using arrow keys or to let agents act on their own based on predefined algorithms. The default agent moves randomly, but through reinforcement learning algorithms, it can learn to navigate the grid efficiently.

### Value Iteration
Value Iteration is one of the fundamental algorithms in reinforcement learning. It allows agents to determine the best policy by estimating the expected reward for each possible action in each state. In this project, you'll implement a value iteration agent that computes the best action based on a provided MDP.

### Policies Exploration
Gridworld comes with different layouts, and one interesting scenario is the DiscountGrid layout. This layout provides challenges for agents, with risky cliffs and multiple exits. You'll experiment with different parameters to make the agent prefer certain exits and routes over others.

### Q-Learning
Unlike Value Iteration, which uses a known MDP to compute a policy, Q-learning learns by interacting with the environment. You will implement a Q-learning agent that learns from its experiences and estimates the expected reward for state-action pairs.

### Epsilon-Greedy Strategy
To ensure the Q-learning agent explores the environment efficiently, the epsilon-greedy strategy is implemented. This strategy occasionally allows the agent to take a random action, promoting exploration, while usually letting it take the action it believes is best.

### Pacman Adventures
After mastering Gridworld, it's time to move to a more complex environment: Pacman. You'll adapt the Q-learning agent to play Pacman, learning from thousands of games to eventually dominate the ghosts.

### Approximate Q-Learning
As environments become more complex, it becomes infeasible to store Q-values for every possible state-action pair. Approximate Q-learning addresses this by learning weights for features of states. This project provides a chance to experiment with this approach, using both identity features and custom feature extractors.

