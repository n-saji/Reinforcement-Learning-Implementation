# Reinforcement Learning Project

## Overview
This project demonstrates a reinforcement learning task where an environment is defined using the **Gymnasium** package. The problem is modeled as a **Markov Decision Process (MDP)**, and two key reinforcement learning methods are implemented:

1. **SARSA** (State-Action-Reward-State-Action)
2. **N-step Double Q-Learning**

## Features
- Custom environment created using Gymnasium.
- Implementation of SARSA for on-policy temporal difference control.
- Implementation of n-step Double Q-Learning for enhanced off-policy learning.
- Comparison of performance metrics between the two methods.

## Getting Started

### Prerequisites
Make sure you have the following installed:
- Python 3.7+
- Gymnasium
- NumPy
- Matplotlib (for visualization)

You can install the dependencies using:
```bash
pip install gymnasium numpy matplotlib
```


## Methods

### SARSA
SARSA is an on-policy algorithm where the agent learns the value of the policy it follows by updating Q-values based on the current state, action, reward, next state, and next action.

### N-step Double Q-Learning
This method combines the strengths of n-step updates with Double Q-Learning to reduce the overestimation bias often seen in standard Q-Learning.

## Results
- Comparative performance analysis of SARSA and n-step Double Q-Learning.
- Plots of reward convergence and policy stability.


## Contributing
If you wish to contribute to this project, follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- The [Gymnasium documentation](https://gymnasium.farama.org/) for guidance on environment creation.
- Reinforcement learning community for inspiring implementations and insights.
