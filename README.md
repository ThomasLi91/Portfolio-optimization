# Portfolio-optimization

We first show how most of the current deep learning portfolio optimization networks are flawed and we pioneer the correct way to build a permuation equivariant neural network (deepsets) suited for this task. We will then combine this novel idea with the use of differentiable convex optimization layers to help the network to learn to optimize the weights with less data and making it more
robust to noisy data. Our permuation equivariant networks all outperform current deeplearning models and when paired with the right optimization layer,
it is truly able to pick up non linear correlations between assets and beat by
a significant margin popular benchmarks used today such as Markowitz with
shrinkage [23], risk parity [36] and uniform allocation [9]
