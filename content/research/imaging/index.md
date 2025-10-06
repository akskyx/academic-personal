---
title: 3D imaging with a simple water-wave-based tunable lens
summary: An independent work. I realized that if water is used in imaging, that would be pretty interesting, so I have run some simulations to validate its feasibility. By applying an external force to oscillate the water surface, a stable capillary wave is generated, forming a periodic convex and concave surface. This dynamic structure can function as a lens with a rapidly shifting focal length. When integrated into an imaging system, this lens enables high-speed depth scanning of the object. The resulting image stack is then processed to reconstruct the depth information of the object, achieving single-shot 3D surface imaging. This method offers an interesting and low-cost solution for 3D imaging.
#date: 2023-10-24
type: docs
math: false
tags:
  - 2025-now
image:
  caption: 'no caption'
---

*This is a recent independent work. I have been thinking what if water is used as a lens, which might be pretty interesting, so I have designed an imaging system and run some simulations to validate its feasibility. I am considering conducting an experimental demonstration in the next step.*

By applying an external force to oscillate the water surface, a stable capillary wave is generated, forming a periodic convex and concave surface. This dynamic structure can function as a lens with a rapidly shifting focal length. When integrated into an imaging system, this lens enables high-speed depth scanning of the object. The resulting image stack is then processed to reconstruct the depth information of the object, achieving single-shot 3D surface imaging. This method offers an interesting and low-cost solution for 3D imaging.


## Schematic of 3D depth reconstruction

{{< figure src="featured.jpg" caption="This system achieves 3D imaging using a simple tunable lens. A ​​standing capillary wave​​ on a liquid's surface creates a ​​variable-focus lens​​. As the lens's focal length rapidly oscillates, the ​​image sensor​​ captures a ​​focal stack​​ of the object. This stack of images at different focus distances is then processed to perform ​​depth reconstruction​​, creating a 3D model." alt="screen reader text" width="100%" >}}

## Simulation results

{{< figure src="simulation.gif" caption="A designed imaging system with water and its corresponding simulation results. **(a)** The measured object distance is plotted against time, where the object distance is defined as the distance between the object plane and the first lens (Lens 1). **​(b)** A 3D visualization of the water surface deformation under external periodic excitation. This simulation is implemented via python according to the shallow water equation. ​**​(c)** Spot diagrams simulated in Ansys Zemax OpticStudio (2024 R1)​ for different object heights.​​ The light intensity distributions at the image plane are shown for object heights of 0 mm, 10 mm, and 20 mm. **​(d)** Schematic of the optical imaging system.​​ The system consists of a shifting object plane, Lens 1 (f=200 mm), a water tank, Lens 2 (f=300 mm), and an image plane. The ray tracing simulation is implemented in Ansys Zemax OpticStudio (2024 R1).​" alt="screen reader text" width="100%" >}}

The simulation results in this figure suggests that it is feasible to use water surface as a tunable lens in an imaging system. The designed imaging system shown in (d) can realize a scanning task, with the scanning depth being about 100 mm and the scanning width being 40 mm.

## Specific realization of standing capillary wave


{{< figure src="water.gif" caption="Using an oscillating ring (the green ring in the figure) to realize standing capillary wave. The diameter of this water tank is 200 mm, and depth of the still water is 35 mm. Since the surface is not in the idle shape, the central area with the diameter being 60 mm is chosen to be the effective area, in oder to mitigate the optical aberration. The ooscillation frequency is 3 Hz." alt="screen reader text" width="100%" >}}




