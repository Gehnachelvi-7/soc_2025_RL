# soc_2025_RL
Race and Learn project 
# Reinforcement Learning Project

This repository documents my weekly progress and learning outcomes as I explore the foundations and applications of Reinforcement Learning (RL). Each week focuses on a different theme, starting from basic programming to deep reinforcement learning methods.

## Project Summary

The goal of this project is to progressively build a solid understanding of reinforcement learning, starting from fundamental Python skills and neural networks, to implementing agents using Q-learning and Deep Q-Networks (DQN). Each week includes hands-on implementations, code, visualizations, and reports.

## Weekly Breakdown

### Week 1: Python Programming & Snake Game with Pygame
In the first week, I revisited core Python concepts and learned the basics of 2D game development using the **Pygame** library. This included working with:
- Game loops and event handling
- Rendering graphics and detecting collisions
- Managing game state and user input

To apply these concepts, I developed a **Snake Game** from scratch. The full source code is available in the [Week1](Week1/)  folder.

### Week 2: Neural Networks & MNIST Digit Classification
Week 2 was focused on understanding the structure and training process of **Neural Networks**, particularly **Convolutional Neural Networks (CNNs)** used in image classification tasks.

Key topics covered:
- Layers, activation functions, loss functions
- Training and evaluation techniques
- Transfer learning overview

I trained a CNN model on the **MNIST dataset** using PyTorch, experimenting with various hyperparameters. All related code, performance graphs, and a short analysis report are provided in the [Week2](Week2/) folder.

### Week 3: Reinforcement Learning Fundamentals & Planning
This week focused on core **Reinforcement Learning concepts**, laying a strong theoretical foundation. I explored:
- **Markov Decision Processes (MDPs)**
- **State-value (V) and action-value (Q) functions**
- **Bellman Equations** and their recursive nature

I also studied **planning methods** like:
- **Value Iteration**
- **Policy Iteration**
- Differences between **model-based** and **model-free** methods

### Week 4: Q-Learning & Deep Q-Networks (DQN)
In the fourth week, I transitioned to practical **model-free RL algorithms**. The focus was on:
- **Q-Learning** in discrete environments
- Implementing **ε-greedy strategies** for exploration
- Using **Experience Replay Buffers** for stability
- Incorporating **Target Networks** to reduce Q-value oscillations

A custom Gridworld was used for initial Q-learning, followed by building a **Deep Q-Network (DQN)** using PyTorch for function approximation. The agent was trained on various scenarios, and performance improvements were visualized through plots and logs.
