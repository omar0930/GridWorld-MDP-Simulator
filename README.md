# GridWorld MDP Simulator

## Overview
The **GridWorld MDP Simulator** is a reinforcement learning environment that simulates a Markov Decision Process (MDP) in a grid world. It provides a flexible and customizable framework for experimenting with different policies, rewards, and state transitions.

## Features
- Customizable grid size
- Adjustable rewards and penalties
- Policy evaluation and iteration
- Value iteration
- Visualization of state values and policy

## Installation
Clone the repository using:
```bash
git clone https://github.com/omar0930/GridWorld-MDP-Simulator.git
cd GridWorld-MDP-Simulator
```


## Dataset
The simulator does not rely on an external dataset. Instead, it generates a grid-based environment dynamically based on user-defined configurations in `config.py`. Users can specify grid size, reward structure, and transition probabilities to create different scenarios.

## Workflow
1. Initialize the GridWorld environment with specified parameters.
2. Define rewards and penalties for different states.
3. Implement policy evaluation and value iteration algorithms.
4. Run the simulation to update state values iteratively.
5. Generate visualizations of state values and optimal policy.
6. Adjust parameters and rerun the simulation for experimentation.

## Results
After running the simulator, the algorithm iterates through the grid states, updating their values based on rewards and the chosen policy. The final output includes a visualization of state values and a policy map indicating the best move for each state. This demonstrates how the agent learns to navigate the environment effectively, maximizing rewards while avoiding penalties.

## Technologies Used
- Python
- NumPy
- Matplotlib (for visualization)
- Reinforcement Learning concepts (MDP, Value Iteration, Policy Evaluation)
****
