# Mid-term Progress Report

## My Weekly Learnings

### In Week 0:
I learned the basics of neural networks using PyTorch. I worked with the MNIST dataset, built a feedforward neural network using inbuilt layers, and implemented training and testing loops manually. This helped me understand forward and backward propagation, loss functions, and optimizers like Adam. I also explored creating a custom model from scratch, gaining insights into low-level tensor operations. Lastly, I visualized predictions and took up challenges like building a network for CIFAR-100 and exploring the Titanic dataset, laying a strong foundation for future deep learning tasks.

### In Week 1:
I implemented tabular Q-learning on OpenAI’s FrozenLake-v1, applying the Bellman update rule and ε-greedy strategy for exploration-exploitation trade-off. I visualized agent convergence using moving average reward plots and Q-table heatmaps. Additionally, I tackled the Multi-Armed Bandit problem using Epsilon-Greedy and Upper Confidence Bound (UCB) approaches. I understood how UCB integrates exploration via confidence bounds, while Epsilon-Greedy relies on stochastic sampling. Tuning hyperparameters like learning rate, ε-decay, and confidence constants helped me analyze convergence speed and policy optimality. These experiments deepened my grasp of value-based RL and its mathematical foundation.

### In Week 2:
In Week 2, we transitioned from tabular Q-learning to Deep Q-Networks (DQN) using PyTorch to handle high-dimensional state spaces. We implemented a DQN agent with experience replay and target networks, training it on CartPole-v1 and a custom Gym-based Snake environment. CartPole showed consistent improvement, achieving average rewards above 160. The Snake agent faced learning challenges due to sparse rewards and complex state transitions, but still demonstrated early learning signs.
