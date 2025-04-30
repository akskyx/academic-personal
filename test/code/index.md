---
title: Programming (python)
summary: Python is powerful
#date: 2025-5-1
type: docs
math: false
tags:
  - python
image:
  caption: 'Embed rich media such as videos and LaTeX math'
---

I use python to validate some thoughts and run some simulations and enjoy coding as much as experiment. Having completed many projects with python, common grammar of python is fluent here. The following parts are some special techniques developed in some projects which might be useful in research.  

All codes in my main work **Efficient characterizations of multiphoton states with an ultra-thin optical device** are available in [zenodo](https://doi.org/10.1038/s41467-024-48213-4).

## Global optimization

Optimization is neccessary in some simulation to find the best solution, but in most realistic cases, local optimum exists. Global optimization algorithms like SPSA, SGD and basinhopping could be more likely to find global optimum.

{{< figure src="featured.jpg" caption=" " alt="screen reader text" width="80%" >}}

## Parallel processing

Some simulations require larger circulations. Using `multiprocessing`, we could accelarate the process with all cores and threads of CPU. This is especially efficient when code is run in server.

## Code optimization for high performance

Python is convenient, which saves the time of writing code. But python is kind of slow, compared to C, Fortran, Matlab... 

However, this disadvantage could be mitigated using `numba` in python. This package is tricky and has certain requirements for the code structure.

## Digital image processing

In my class 'Digital Image Processing', I have learned most algorithms related to image processing, which is frequently used in my astronomical photography.

## 3D graph animation

I have used `mayavi` in python to demonstrate how polarization evolves in a 3d bloch sphere. This project has been put on [CSDN](https://blog.csdn.net/skyxak/article/details/122416349) and received 3.5k view.

## Neural network

I have built several classical neural networks for data classification and regression, and a convolutional neural network (CNN) to recongnize stars. Additionally, we designed a hybrid quantum-classical neural network for a quantum task (purity estimation).