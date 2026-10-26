# DAT 260 – Emerging Technologies and Big Data

**Ahmed Ahmed**  

Southern New Hampshire University  

This repository contains selected coursework from DAT 260. The projects focus on reinforcement learning, deep Q-networks, and practical applications of machine learning concepts.

---

## Projects

### 1. Assignment 5 – CartPole Deep Q-Learning
**File:** `Assignment5_CartPole_DQN.html`

In this assignment I implemented and experimented with a Deep Q-Network (DQN) agent on the classic CartPole environment.

**Key concepts covered:**
- Reinforcement learning fundamentals (states, actions, rewards, episodes)
- Deep Q-Network architecture (input layer → two hidden layers with ReLU → output layer)
- Experience replay and target network
- Hyperparameter experiments:
  - Exploration rate (epsilon and decay)
  - Discount factor (gamma)
  - Learning rate

The notebook includes analysis of how changes to exploration, discount factor, and learning rate affected the agent’s ability to solve the environment (average reward ≥ 195 over 100 consecutive episodes).

---

### 2. Project Two – Treasure Hunt Game (Q-Learning / Deep Q-Learning)
**File:** `ProjectTwo_TreasureHunt.html`

This project implements a pirate treasure-hunt game using reinforcement learning. The agent (pirate) learns to navigate a maze to reach the treasure while avoiding obstacles.

**Key features:**
- Custom maze environment
- Q-learning / deep Q-network training loop
- Training progress tracking (win rate, loss, episode count)
- Visualization of the learned path from starting position to the treasure

After training, the agent successfully finds a path from the top-left corner to the treasure located in the bottom-right corner.

---

## How to View the 
