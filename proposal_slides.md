---
marp: true
title: Machine Learning Project Proposal
theme: default
paginate: true
---

# Q-Learning for Maze Navigation in Webots
**Author:** Will Lapinel
**Date:** September 15, 2024

---

# Problem and Dataset
- **Problem**: Navigating unknown mazes using reinforcement learning (Q-learning) in a simulated environment (Webots).
- **Goal**: Duplicate the method from a primary paper on Q-learning maze navigation.
- **Dataset/Simulation**: Webots provides the maze environment; the robot learns through exploration and reinforcement.

---

# Primary paper that I will replicate

## **Weiss, Tobias, et al.**

### "Q-Learning for MAZE-Navigation of a TurtleBot." *Artificial Intelligence and Soft Computing*, 2023

- Focus on simulation and real-world environments.

---

# Related Works Survey

1. **Ioannou, Alexandros, et al.**  
   "Deepbots: A Webots-Based Deep Reinforcement Learning Framework for Robotics." *Artificial Intelligence and Soft Computing*, 2021.  
   - Provides an abstraction for RL tasks in Webots.

2. **Spryn, Mitchell.**  
   "Solving A Maze With Q Learning." 2021.  
   - Simple Python Q-learning implementation for maze-solving.

---

# Method

- Replicating the Q-learning algorithm:
   - **State**: Maze grid, robot position.
   - **Action**: Move (left, right, up, down).
   - **Reward**: Positive for reaching the goal, negative for hitting walls.
- Using Webots for simulation and testing.

---

# Timeline
- **October 1 - October 15**: Literature review and initial setup in Webots.
- **October 16 - November 1**: Implementation of Q-learning and maze environment in Webots.
- **November 2 - November 10**: Testing and tweaking the algorithm.
- **November 11 - November 16**: Final evaluation and write-up.

---

# Expected Learning Outcomes
- Understanding how Q-learning adapts to unknown environments.
- Gaining practical experience with Webots for simulating robot navigation tasks.
- Implementing and testing reinforcement learning models in a real-world simulation environment.

---

# References
1. Weiss, Tobias, et al. "From Simulated to Real Environments: Q-Learning for MAZE-Navigation of a TurtleBot." *Artificial Intelligence and Soft Computing*, 2023.
2. Ioannou, Alexandros, et al. "Deepbots: A Webots-Based Deep Reinforcement Learning Framework for Robotics." *Artificial Intelligence and Soft Computing*, 2021.
3. Spryn, Mitchell. "Solving A Maze With Q Learning." 2021.
