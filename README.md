# Enabling Uncertainty Estimation in Iterative Neural Networks

![Project Page](./src/teaser.gif)

[![arXiv](https://img.shields.io/badge/cs.CV-arXiv%3A2403.16732-blue?logo=arxiv&color=red)](https://arxiv.org/abs/2403.16732)
[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&color=blue)](https://www.python.org/downloads/release/python-31014/)
[![Pytorch](https://img.shields.io/badge/Pytorch-2.2.1-blue?logo=pytorch&color=blue)](https://pytorch.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow)](https://github.com/cvlab-epfl/iter_unc/blob/main/LICENSE)

### [Project Page](https://www.norange.io/projects/unc_iter/) | [ICML Paper]()

## Abstract

Turning pass-through network architectures into iterative ones, which use their own output as input, is a well-known approach for boosting performance. In this paper, we argue that such architectures offer an additional benefit: The convergence rate of their successive outputs is highly correlated with the accuracy of the value to which they converge. Thus, we can use the convergence rate as a useful proxy for uncertainty. This results in an approach to uncertainty estimation that provides state-of-the-art estimates at a much lower computational cost than techniques like Ensembles, and without requiring any modifications to the original iterative model. We demonstrate its practical value by embedding it in two application domains: road detection in aerial images and the estimation of aerodynamic properties of 2D and 3D shapes. 
