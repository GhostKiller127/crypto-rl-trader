# AI Crypto Trading Algorithm
A reinforcement learning-based cryptocurrency trading algorithm implemented in JAX, capable of performing both long and short trades on Bybit futures.


## Overview
This project implements a distributed off-policy reinforcement learning algorithm with a meta learner, inspired by the [GDI paper](https://arxiv.org/pdf/2206.03192). It utilizes the memory-efficient state space model [S5](https://arxiv.org/pdf/2208.04933) and operates on 15-minute intervals.


## Technical Implementation

### Current Architecture
- Distributed off-policy reinforcement learning
- Custom crypto trading environment (similar to OpenAI Gym)
- Memory-efficient state space model (S5)
- JAX implementation for efficient execution
- Supports both long and short positions on Bybit futures

### Development Roadmap
1. Price Prediction Enhancement
   - State-of-the-art time series forecasting
   - Multi-head prediction architecture
   - Uncertainty estimation

2. Advanced Search Strategies
   - Hybrid RL architecture
   - Model-based planning
   - Dynamic search optimization

For detailed technical information, performance metrics, development plans, and visualizations, please visit the [WandB Report](https://api.wandb.ai/links/ghostkiller2070/dfrptapm).


## Project Structure
- `Reinforcement Learning/`: Main RL implementation
- `Bybit/`: Trading interface
- `S5/`: State space model architecture
- `S5_pendulum/`: Testing environment


## References

### Reinforcement Learning Architecture
- [GDI: Generalized Data Distribution Iteration](https://arxiv.org/pdf/2206.03192) - Base architecture inspiration
- [CASA: Critic AS an Actor](https://arxiv.org/pdf/2105.03923) - Precursor to GDI
- [DICE](https://arxiv.org/pdf/2106.00707) - Precursor to GDI
- [MEME: Human-level Atari 200x faster](https://arxiv.org/pdf/2209.07550) - Deepmind
- [Agent57: Outperforming the Atari Human Benchmark](https://arxiv.org/pdf/2003.13350) - Deepmind
- [R2D2: Recurrent Experience Replay in Distributed Reinforcement Learning](https://openreview.net/pdf?id=r1lyTjAqYX) - Deepmind


### State Space Models (SSM)
- [S5](https://arxiv.org/pdf/2208.04933) - Multi-input multi-output architecture (MIMO)
- [S4D](https://arxiv.org/pdf/2206.11893) - Diagonal simplification of S4
- [S4](https://arxiv.org/pdf/2111.00396) - Original Structured State Space sequence model

For a complete list of references and their influence on this project, please visit the [WandB Report](https://api.wandb.ai/links/ghostkiller2070/dfrptapm).


## License & Copyright
© Ali Keysan 2024. All rights reserved.

This code repository is shared publicly for demonstration purposes only. 
No license is granted to use, copy, modify, or distribute this software for any purpose.
