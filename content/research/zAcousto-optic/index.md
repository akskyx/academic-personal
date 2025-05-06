---
title: Acousto-optic effect
summary: This research mainly focuses on how light and sound interact in the water, part of which has been put on the textbook of this teaching experiment to rectify its explanation. 
#date: 2023-10-24
type: docs
math: false
tags:
  - 2020-2024
image:
  caption: 'Embed rich media such as videos and LaTeX math'
---

This research started with an advanced experimental course in the the third year of undergraduate study, where I found some errors in the explanation of experiment "Acousto-optic effect". It interpret the fringe pattern as the results of different transmissivity induced by different refractive index.

After some quantitative calculations, I found that such an obvious fringe pattern can not be caused by variation of transmissivity. Since then, I have learned useful tools including Wolframe Mathematica and COMSOL to explore its more reasonable explanation. Finally, I found the wavefront was the key point and introduced huyghens principle to derive the explanation, and even predicted that the fringe pattern would have periodic focal length due to Talbot effect.

The corrected explanation and corresponding simulation is now presented in the new edtion of the textbook.

## 🎥 Animation

An animation is made to clearly explain how sound wave influnences light:

{{< youtube ygOh8f5qlfc >}}


## 🧑🏻‍🔧️ Experimental setup

{{< figure src="low_f.jpg" caption="Experimental setup of microscope and coupling system" alt="screen reader text" width="100%" >}}

## 💻 Algorithm enhances efficiency

Combining self-learning algorithm with shadow tomography, we propose SLST protocol, which enhances the efficiency in the reconstruction of multiphoton states, including using fewer measurements, having higher accuracy. In addition, by introducing calibration, we observe SLST improves the robustness against experimental imperfections.

{{< figure src="algorithm.jpg" caption="Illustration of the self-learning algorithm and how quantum states are reconstructed by this iterative process" alt="screen reader text" width="100%" >}}



## ⚙️ Metasurface enables this algorithm

Metasurface could realize octahedron POVM, enabling the efficient algorithm mentioned before.

{{< figure src="metasurface.jpg" caption="POVM realized by Metasurface enables this algorithm" alt="screen reader text" width="100%" >}}
