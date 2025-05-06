# Connect 4 Reinforcement Learning Agents

This repository explores the development of Connect 4-playing agents using reinforcement learning. Multiple training approaches were implemented and evaluated, including policy gradient methods, DQNs, and actor-critic models. The goal is to compare the performance of different strategies through structured simulations and head-to-head tournaments.

## Files

| File Name                   | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| `Policy_gradients.ipynb`   | Trains a Connect 4 agent using a policy gradient approach.                  |
| `FinalModelComparison.ipynb` | Loads various models (Keras and PyTorch) and compares them in test scenarios. |
| `RoundRobinTournament.ipynb` | Runs a round-robin tournament to evaluate all models against each other.     |
| `TrainedModel.h5`          | A trained Keras model for Connect 4 based on reinforcement learning.        |
| `Connect4_RL_ProjectReport.pdf` | Project report detailing each specific step and task of this project. |

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/connect4-rl.git
   cd connect4-rl
2. Install required dependencies:
   ```bash
   pip instsall tensorflow torch numpy
4. Open and run the notebooks using Jupyter or your preferred environment.

## Project Overview
The core objective of this project is to build Connect 4 agents that learn to play through reinforcement learning. The notebooks support training, loading, and evaluating models using different learning algorithms. Results are compared through gameplay simulations and tournament-style evaluations.
