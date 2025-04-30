---
title: Optical chip enables hybrid neural network
summary: Combining optical chips with traditional electronic hardware, we have developed a hybrid neural network that can be used to directly detect the properties of photons. Hybrid neural networks demonstrate stronger robustness in photon purity estimation and can even estimate purity in the case of incomplete measurements.
#date: 2023-10-24
type: docs
math: false
tags:
  - optical chip
image:
  caption: 'Embed rich media such as videos and LaTeX math'
---


## 🧑🏻‍🔧️ Experimental platform

The optical chip can be controlled by changing phase of light in each path, which is realized by adjusting voltage on the electrode patches. I have designed and set up the platform including voltage-control system, temperature-control module and light-coupling system.

{{< figure src="chip.jpg" caption="Experimental platform for optical chip" alt="screen reader text" width="90%" >}}


## 💻 Hybrid neural network

The hybrid quantum-classical neural network has following advantages:
- Self-adaptive
- Avoid theoretical calculation of post process
- Robust against static noise

{{< figure src="2.jpg" caption="Concept of hybrid quantum-classical neural network with optical chip. (a) General neural network architecture composed of an unitary transformation and classical neural network layers including active functions. (b) Unitary evolution on the input light with interferometers on a optical chip. The output is transferred to electron signals by light detectors." alt="screen reader text" width="70%" >}}
