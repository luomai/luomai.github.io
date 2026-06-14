---
title: TorchOpt
description: PyTorch library for differentiable optimization, meta-learning, and implicit or zero-order gradients.
category: Software
tags:
  - machine-learning-systems
github: https://github.com/metaopt/torchopt
featured: true
date: '2022-10-31'
github_stars: 630
github_stars_url: https://github.com/metaopt/torchopt/stargazers
---
TorchOpt is an efficient library for differentiable optimization built upon PyTorch. TorchOpt is:

* **Comprehensive**: TorchOpt provides three differentiation modes - explicit differentiation, implicit differentiation, and zero-order differentiation for handling different differentiable optimization situations.

* **Flexible**: TorchOpt provides both functional and objective-oriented API for users' different preferences. Users can implement differentiable optimization in JAX-like or PyTorch-like style.

* **Efficient**: TorchOpt provides (1) CPU/GPU acceleration differentiable optimizer (2) RPC-based distributed training framework (3) Fast Tree Operations, to largely increase the training efficiency for bi-level optimization problems.

Beyond differentiable optimization, TorchOpt can also be regarded as a functional optimizer that enables JAX-like composable functional optimizer for PyTorch. With TorchOpt, users can easily conduct neural network optimization in PyTorch with a functional style optimizer, similar to Optax in JAX.
