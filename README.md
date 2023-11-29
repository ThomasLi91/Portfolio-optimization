# Portfolio-optimization (Public Version)

**Public Paper** : https://github.com/ThomasLi91/Portfolio-optimization/blob/main/Thomas_LI_MAP595_Cubist_Systematic.pdf

My internship project at **Cubist Systematic Strategies (Point72)** in New York. (03/2023 - 07/2023). I was largely **autonomous** during the internship and the findings here were found on my own. The original subject only suggested to look at the **differentiable convex optimization layers** paper (https://proceedings.neurips.cc/paper/2019/file/9ce3c52fc54362e22053399d3181c638-Paper.pdf).

We first show how most of the current deep learning portfolio optimization networks are flawed and we pioneer the correct way to build a permuation equivariant neural network (**deepsets** : https://proceedings.neurips.cc/paper/2017/file/f22e4747da1aa27e363d86d40ff442fe-Paper.pdf) suited for this task. Not only does it assure us that the network will give us this permutation equivariant property, but il also largely decreases the number of trainable parameters used.
We will then combine this novel idea with the use of differentiable convex optimization layers to help the network to learn to optimize the weights with less data and making it more
robust to noisy data. Our permuation equivariant networks all outperform current deeplearning models and when paired with the right optimization layer,
it is truly able to pick up non linear correlations between assets and beat by
a significant margin popular benchmarks used today such as Markowitz with
shrinkage [23], risk parity [36] and uniform allocation [9]

Major contributions to the package Deepdow : https://deepdow.readthedocs.io/en/latest/

![image](https://github.com/ThomasLi91/Portfolio-optimization/assets/96530384/d2d363d7-258c-4f7c-9321-2d99c8a8c788)

