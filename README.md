# NEAT AI Game Learner

## Introduction
This project implements the NeuroEvolution of Augmenting Topologies (NEAT) algorithm to train artificial intelligence agents that learn to play games through evolutionary principles. Unlike traditional neural networks, NEAT evolves both the weights and structure of networks simultaneously.

## What is NEAT?
NEAT is a genetic algorithm that creates artificial neural networks. It starts with simple networks and gradually evolves them to become more complex as needed. This approach mimics biological evolution and often discovers innovative solutions that human designers might overlook.

## How It Works
The algorithm operates through several key mechanisms:
1. **Population Initialization**: Start with a population of simple neural networks
2. **Fitness Evaluation**: Test each network by having it play the game
3. **Selection**: Choose the best-performing networks as parents
4. **Mutation**: Randomly modify network structure (add nodes/connections)
5. **Crossover**: Combine successful networks to create offspring
6. **Speciation**: Protect innovative structures by grouping similar networks

## Advantages Over Traditional Methods
- No need for pre-defined network architectures
- Discovers optimal complexity automatically
- Resistant to local optima through population diversity
- Can solve problems where the solution structure is unknown

## Practical Applications
- Video game AI that adapts to player strategies
- Robotics control systems
- Financial trading algorithms
- Pattern recognition systems

## Implementation Details
The system includes genome representation, fitness functions, and speciation mechanisms. Networks are evaluated in parallel for efficiency, and evolution progress is visualized in real-time.

## Results
Agents typically progress from random movement to sophisticated gameplay within hundreds of generations, demonstrating genuine learning without explicit programming of game strategies.
