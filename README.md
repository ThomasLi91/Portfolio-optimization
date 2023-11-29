# Portfolio-optimization

Portfolio optimization, a key challenge in finance, has traditionally relied on a
two-step process involving parameter calibration and subsequent optimization
(e.g. forecasting assets’ mean returns and covariance matrix and then applying a Markowitz optimization to get the optimal weights [28]). However, this
approach remains a ”greedy” approach, where inaccuracies in parameter estimation lead to suboptimal allocation decisions. In this research, we propose a
novel approach that integrates prediction and optimization tasks within a single neural network, enabling an end-to-end solution where portfolio allocation
is directly learned from the raw input features which usually are the historical
returns of assets. We first show how most of the current deep learning portfolio
optimization networks are flawed and we pioneer the correct way to build a permuation equivariant neural network (deepsets) suited for this task. We will then combine
this novel idea with the use of differentiable convex optimization layers to help
the network to learn to optimize the weights with less data and making it more
robust to noisy data. Our permuation equivariant networks all outperform current deeplearning models and when paired with the right optimization layer,
it is truly able to pick up non linear correlations between assets and beat by
a significant margin popular benchmarks used today such as Markowitz with
shrinkage [23], risk parity [36] and uniform allocation [9]
