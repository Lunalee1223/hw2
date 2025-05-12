
# Super Tic-Tac-Toe — Reinforcement Learning Agent

This project implements a Deep Q-Network (DQN) agent trained to play **Super Tic-Tac-Toe**, a stochastic board game with shifting move mechanics.

## Overview

Super Tic-Tac-Toe is played on a cross-shaped board consisting of five 4×4 grids, totaling 80 playable cells. Each move has a 50% chance of success; otherwise, it is randomly shifted to a neighboring cell. The game is won by forming:

- Four contiguous marks in any row or column, or
- Five contiguous marks on a main cross-diagonal.

## Project Structure

```
.
├── tf_ttt.ipynb    # Main training code (Jupyter Notebook)
├── report.pdf      # Final project report
├── README.md       # Project description
```

## How to Run

1. Open `tf_ttt.ipynb` using Jupyter Notebook.
2. Run all cells to train the agent and evaluate its performance.
3. Learning curve and evaluation results are logged or plotted within the notebook.

## Summary

The agent uses a 3-layer DQN trained with self-play. Evaluation against a stochastic baseline (ε = 0.2) shows a 67% win rate. The TD-loss curve confirms convergence, and qualitative behaviors such as center preference and shift avoidance emerge during training.

## Citation

This project was completed as part of coursework in reinforcement learning, Spring 2025.
