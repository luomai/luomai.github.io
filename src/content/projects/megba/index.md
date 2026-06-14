---
title: MegBA
description: Distributed GPU bundle-adjustment library for large-scale 3D reconstruction workloads.
category: Software
tags:
  - machine-learning-systems
github: https://github.com/MegviiRobot/MegBA
featured: true
date: '2022-10-31'
github_stars: 491
github_stars_url: https://github.com/MegviiRobot/MegBA/stargazers
---
MegBA is a fast and distributed library for large-scale Bundle Adjustment (BA). MegBA has a novel end-to-end vectorised BA algorithm which can fully exploit the massive parallel cores on GPUs, thus speeding up the entire BA computation. It also has a novel distributed BA algorithm that can automatically partition BA problems, and solve BA sub-problems using distributed GPUs. The GPUs synchronise intermediate solving state using network-efficient collective communication, and the synchronisation is designed to minimise communication cost. MegBA has a memory-efficient GPU runtime and it exposes g2o-compatible APIs. Experiments show that MegBA can out-perform state-of-the-art BA libraries (i.e., Ceres and DeepLM) by ~50x and ~5x respectively, in public large-scale BA benchmarks.
