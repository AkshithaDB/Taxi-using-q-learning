


# Taxi-v3 using Q-Learning

This project implements **Q-learning** to train an agent in the **Taxi-v3 environment** from OpenAI Gym. The goal is to navigate a taxi in a 5x5 grid, pick up a passenger, and drop them off at the correct destination while optimizing for minimal penalties.

## Features
- Uses **OpenAI Gym's Taxi-v3** environment.
- Implements **Q-learning**, a reinforcement learning algorithm.
- Trains an agent to efficiently complete taxi rides.
- Saves and loads the trained **Q-table**.

## Installation & Requirements
*Pygame

*Pyvirtualdisplay

## Explanation
The state space consists of 500 discrete states (taxi position, passenger location, destination).
The action space consists of 6 discrete actions (move in 4 directions, pick up, and drop off).
The Q-table is updated using the Bellman equation to maximize future rewards.

In the second file, learning parameters are modified. 
epsilon is set to zero which allows random exploration.
Epsilon decay is used to update the Q-table accurately for future returns. 
Through this, the agent is able to make acccurate drop and pick up. 


## File Structure
taxi-using-q-learning.ipynb: Jupyter Notebook implementing Q-learning for Taxi-v3.

Taxi with modified parameters.ipynb: Jupyter Notebook implementing Q-learning with modified parameters.
