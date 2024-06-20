# Sketch Processing Papers

A reading list of papers related to sketch processing and applications. This is supplementary to the SGP 2024 course "Fundamentals and Applications of Sketch Processing".

## Content
- [1. 2D Spline Construction](#1-2d-spline-construction)
- [2. 3D Sketching Interface](#2-3d-sketching-interface)
- [3. Sketch Vectorization](#3-sketch-vectorization)
- [4. Sketch Beautification](#4-sketch-beautification)
- [5. Sketch Interpolation](#5-sketch-interpolation)
- 6. Sketch Topology
- 7. Sketch Simplification/Consolidation
  - 7.1 In Drawing System
  - 7.2 Clustering
  - 7.3 Fitting
- 8. Junction Construction/Gap Filling
  - 8.1 Junction Connection
  - 8.2 Region Filling
  - 8.3 ML End-to-End Models
- 9. 2D Sketch Lifting
- 10. 3D Sketch Surfacing
- 11. Sketch-Based Modeling
  - 11.1 Geometric and CAD Models
  - 11.2 Organic Shapes
  - 11.3 Domain Specific
- 12. Sketch-Based Editing
- 13. Sketch-Based Animation Control
  - 13.1 Posing
  - 13.2 Animation
- 14. Sketch Perception Studies
- 15. Learning-Based Sketch Processing
  - 15.1 Sketch Understanding
  - 15.2 Sketch Generation
 
## 1. 2D Spline Construction

| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [Sketching Piecewise Clothoid Curves](https://www.sciencedirect.com/science/article/pii/S0097849309000843) | SBIM 2009 | [[project]](https://www.dgp.toronto.edu/~mccrae/projects/clothoid/) |
| [Sketching Clothoid Splines Using Shortest Paths](https://onlinelibrary.wiley.com/doi/full/10.1111/j.1467-8659.2009.01635.x) | Eurographics 2010 | [[code]](https://github.com/bkmeneguello/cornucopia-lib) |
| [Neatening sketched strokes using piecewise French Curves](https://dl.acm.org/doi/abs/10.1145/2021164.2021190) | SBIM 2011 | [[project]](https://www.dgp.toronto.edu/~mccrae/projects/french/) |
| [Elasticurves: Exploiting Stroke Dynamics and Inertia for the Real-time Neatening of Sketched 2D Curves](https://dl.acm.org/doi/abs/10.1145/2047196.2047246) | UIST 2011 | [[project]](https://www.dgp.toronto.edu/~ythiel/Elasticurves/) |

## 2. 3D Sketching Interface

| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [Interactive Sketch-Based Interfaces and Modelling for Design (Book Chapter 7-10)](https://www.routledge.com/Interactive-Sketch-based-Interfaces-and-Modelling-for-Design/Bonnici-Camilleri/p/book/9788770227704) | River Publishers; 1st edition (2023) | [[chapters]](https://rahularora.xyz/en/) |
| [Experimental Evaluation of Sketching on Surfaces in VR](https://dl.acm.org/doi/10.1145/3025453.3025474) | CHI 2017 | [[code]](https://github.com/rarora7777/VRSketchingStudyCHI17) |
| [CASSIE: Curve and Surface Sketching in Immersive Environments](https://dl.acm.org/doi/10.1145/3411764.3445158) | CHI 2021 | [[project]](https://em-yu.github.io/research/cassie/) |
| [3D-Layers: Bringing Layer-Based Color Editing to VR Painting]() | SIGGRAPH 2024 | [[project]](https://em-yu.github.io/research/3dlayers/) |

## 3. Sketch Vectorization

### Raster sketch cleanup
| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [Learning to Simplify: Fully Convolutional Networks for Rough Sketch Cleanup](https://dl.acm.org/doi/10.1145/2897824.2925972) | SIGGRAPH 2016 | [[project]](https://esslab.jp/~ess/en/research/sketch_master/) |
| [Mastering Sketching: Adversarial Augmentation for Structured Prediction](https://arxiv.org/abs/1703.08966) | SIGGRAPH 2018 | [[project]](https://esslab.jp/~ess/en/research/sketch_master/) |
| [Real-Time Data-Driven Interactive Rough Sketch Inking](https://dl.acm.org/doi/10.1145/3197517.3201370) | SIGGRAPH 2018 | [[project]](https://esslab.jp/~ess/en/research/inking/) |

### Sketch Vectorization
| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [Topology-Driven Vectorization of Clean Line Drawings](https://dl.acm.org/doi/10.1145/2421636.2421640) | SIGGRAPH 2012 | [[project]](https://disneyanimation.com/publications/topology-driven-vectorization-of-clean-line-drawings/) |
| [Fidelity vs. Simplicity: a Global Approach to Line Drawing Vectorization](https://dl.acm.org/doi/10.1145/2897824.2925946) | SIGGRAPH 2016 | [[project]](https://www-sop.inria.fr/reves/Basilic/2016/FLB16/) |
| [Vectorization of Line Drawings via PolyVector Fields](https://arxiv.org/abs/1801.01922) | SIGGRAPH 2019 | [[project]](https://github.com/bmpix/PolyVectorization) |
| [A Benchmark for Rough Sketch Cleanup](https://dl.acm.org/doi/abs/10.1145/3414685.3417784) | SIGGRAPH Asia 2020 | [[project]](https://cragl.cs.gmu.edu/sketchbench/) |
| [Integer‐Grid Sketch Simplification and Vectorization](https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.14075) | SGP 2020 | [[project]](https://www-sop.inria.fr/reves/Basilic/2020/SBBB20/) |
| [Keypoint-Driven Line Drawing Vectorization via PolyVector Flow](https://dl.acm.org/doi/10.1145/3478513.3480529) | SIGGRAPH Asia 2021 | [[project]](https://puhachov.xyz/publications/keypoint-driven-polyvector-flow/) |
| [General Virtual Sketching Framework for Vector Line Art](https://dl.acm.org/doi/abs/10.1145/3450626.3459833) | SIGGRAPH 2021 | [[project]](https://markmohr.github.io/virtual_sketching/) |
| [Deep Sketch Vectorization via Implicit Surface Extraction](https://cragl.cs.gmu.edu/sketchvector/) | SIGGRAPH 2024 | [[project]](https://cragl.cs.gmu.edu/sketchvector/) |

## 4. Sketch Beautification

| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [An Automatic Beautifier for Drawings and Illustrations](https://dl.acm.org/doi/10.1145/325165.325240) | SIGGRAPH 1985| |
| [Interactive Beautification: A Technique for Rapid Geometric Design](https://dl.acm.org/doi/10.1145/263407.263525) | UIST 1997| [[video]](https://open-video.org/details.php?videoid=8221) |
| [PaleoSketch: Accurate Primitive Sketch Recognition and Beautification](https://dl.acm.org/doi/10.1145/1378773.1378775) | IUI 2008| |
| [Towards Beautification of Freehand Sketches Using Suggestions](https://dl.acm.org/doi/10.1145/1572741.1572754) | SBIM 2009| [[project]](https://engineering.purdue.edu/cdesign/wp/towards-beautification-of-freehand-sketches-using-suggestions/) |
| [QuickDraw: Improving Drawing Experience for Geometric Diagrams](https://dl.acm.org/doi/10.1145/2207676.2208550) | CHI 2012| |
| [Advanced Drawing Beautification with ShipShape](https://dl.acm.org/doi/10.1016/j.cag.2016.02.003) | Computers & Graphics 2016 | [[project]](https://dcgi.fel.cvut.cz/home/sykorad/shipshape.html) | 

## 5. Sketch Interpolation

| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [Betweenit An Interactive Tool For Tight Inbetweening](https://onlinelibrary.wiley.com/doi/full/10.1111/j.1467-8659.2009.01630.x) | Eurographics 2010 | [[project]](https://disneyanimation.com/publications/betweenit-an-interactive-tool-for-tight-inbetweening/) [[video]](https://www.youtube.com/watch?v=DuZRNR-6iRo) |
| [Computer-Assisted Animation of Line and Paint in Disney’s Paperman](https://dl.acm.org/doi/10.1145/2343045.2343071) | SIGGRAPH 2012 Talks | [[project]](https://disneyanimation.com/publications/computer-assisted-animation-of-line-and-paint-in-disneys-paperman/) [[video]](https://www.youtube.com/watch?v=84rl-T2yIls) |
| [Joint Stroke Tracing and Correspondence for 2D Animation](https://dl.acm.org/doi/10.1145/3649890) | SIGGRAPH 2024 | [[project]](https://markmohr.github.io/JoSTC/) |

| []() | | [[]]() |
