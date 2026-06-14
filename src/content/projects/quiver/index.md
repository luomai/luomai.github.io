---
title: Quiver
description: Low-latency GPU graph-learning runtime for scaling PyG workloads across machines.
category: Software
tags:
  - machine-learning-systems
github: https://github.com/quiver-team/torch-quiver
featured: true
date: '2021-10-31'
github_stars: 304
github_stars_url: https://github.com/quiver-team/torch-quiver/stargazers
---
The primary motivation for the Quiver project is to make it easy to take a PyG script and scale it across many GPUs and CPUs. A typical scenario is: Quiver users can leverage the high-level APIs and rich examples of PyG to design graph learning algorithms, and then use Quiver to scale PyG algorithms to run at large scale. To make such scaling efficient, Quiver has several features:

* **High performance**: Quiver enables GPUs to be efficiently used in accelerating performance-critical graph learning tasks: graph sampling, feature collection and data-parallel training. Quiver thus can out-perform PyG and DGL even with a single GPU, especially when processing large-scale datasets and models.

* **High scalability**: Quiver can achieve (super) linear scalability in distributed graph learning. This is contributed by Quiver's novel communication-efficient data/processor management techniques and effective usage of fast networking technologies (e.g., NVLink and RDMA).

* **Easy to use**: Quiver requires only a few new lines of code in existing PyG programs and it has no external heavy dependency. Quiver is thus easy to be adopted by PyG users and integrated into production clusters.
