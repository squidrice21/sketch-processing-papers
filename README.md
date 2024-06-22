# Sketch Processing Papers

A reading list of papers related to sketch processing and applications. This is supplementary to the [SGP 2024](https://sgp2024.github.io/) course "Fundamentals and Applications of Sketch Processing".

## Content
- [1. 2D Spline Construction](#1-2d-spline-construction)
- [2. 3D Sketching Interface](#2-3d-sketching-interface)
- [3. Sketch Vectorization](#3-sketch-vectorization)
- [4. Sketch Beautification](#4-sketch-beautification)
- [5. Sketch Interpolation](#5-sketch-interpolation)
- [6. Sketch Topology](#6-sketch-topology)
- [7. Sketch Cleanup/Simplification/Consolidation](#7-sketch-cleanupsimplificationconsolidation)
  - [7.1 In Drawing System](#71-in-drawing-system)
  - [7.2 Clustering](#72-clustering)
  - [7.3 Fitting](#73-fitting)
- [8. Flat Colorization/Junction Reconstruction](#8-flat-colorizationjunction-reconstruction)
  - [8.1 Region Filling](#81-region-filling)
  - [8.2 Junction Connection](#82-junction-connection)
  - [8.3 Learning-Based](#83-learning-based)
- [9. 2D Sketch Lifting](#9-2d-sketch-lifting)
- [10. 3D Sketch Surfacing](#10-3d-sketch-surfacing)
- [11. Sketch-Based Modeling](#11-sketch-based-modeling)
  - [11.1 Organic Shapes](#111-organic-shapes)
  - [11.2 Geometric and CAD Models](#112-geometric-and-cad-models)
  - [11.3 Domain Specific](#113-domain-specific)
- [12. Sketch-Based Editing](#12-sketch-based-editing)
- [13. Sketch-Based Animation Control](#13-sketch-based-animation-control)
  - [13.1 Posing](#131-posing)
  - [13.2 Animation](#132-animation)
- [14. Sketch Perception](#14-sketch-perception)
- [15. Vision Tasks on Sketches](#15-vision-tasks-on-sketches)
  - [15.1 Sketch Understanding](#151-sketch-understanding)
  - [15.2 Sketch Generation](#152-sketch-generation)
 
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
| [ScafoldSketch: Accurate Industrial Design Drawing in VR](https://dl.acm.org/doi/10.1145/3472749.3474756) | UIST 2021 | [[project]](https://cragl.cs.gmu.edu/scaffoldsketch/) |
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

## 6. Sketch Topology

| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [Vector Graphics Complexes](https://dl.acm.org/doi/abs/10.1145/2601097.2601169) | SIGGRAPH 2014 | [[project]](https://www.borisdalstein.com/research/vgc/) |
| [Vector Graphics Animation with Time-Varying Topology](https://dl.acm.org/doi/10.1145/2766913) | SIGGRAPH 2015 | [[project]](https://www.borisdalstein.com/research/vac/) |
| [Flow-Complex-Based Shape Reconstruction From 3D Curve Sketches](https://dl.acm.org/doi/10.1145/2560328) | SIGGRAPH 2014 | [[project]](https://www.cs.toronto.edu/~sadri/page4/files/d76b1e69c42fda288de3495bd502ecd4-13.html) |
| [Differential Operators on Sketches via Alpha Contours](https://dl.acm.org/doi/abs/10.1145/3592420) | SIGGRAPH 2023 | [[project]](https://www-labs.iro.umontreal.ca/~bmpix/AlphaContours/) |

## 7. Sketch Cleanup/Simplification/Consolidation

| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [A Benchmark for Rough Sketch Cleanup](https://dl.acm.org/doi/abs/10.1145/3414685.3417784) | SIGGRAPH Asia 2020 | [[project]](https://cragl.cs.gmu.edu/sketchbench/) |

### 7.1 In Drawing System
| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [A Mark-Based Interaction Paradigm for Free-Hand Drawing](https://dl.acm.org/doi/10.1145/192426.192496) | UIST 1994 |  |
| [ILoveSketch: As-Natural-As-Possible Sketching System for Creating 3D Curve Models](https://dl.acm.org/doi/10.1145/1449715.1449740) | UIST 2008 | [[project]](https://www.dgp.toronto.edu/~shbae/ilovesketch.htm) |
| [Just DrawIt: A 3D Sketching System](https://dl.acm.org/doi/10.5555/2331067.2331084) | SBIM 2012 | |

### 7.2 Clustering
| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [Geometric Clustering for Line Drawing Simplification](https://dl.acm.org/doi/10.1145/1187112.1187227) | EGSR 2005 | [[project]](https://maverick.inria.fr/Publications/2005/BTS05a/index.php) |
| [Efficient and Dynamic Simplification of Line Drawings](https://onlinelibrary.wiley.com/doi/10.1111/j.1467-8659.2008.01151.x) | Eurographics 2008 | |
| [Beautification of Design Sketches Using Trainable Stroke Clustering and Curve Fitting](https://ieeexplore.ieee.org/abstract/document/5710858) | TVCG 2011 | [[data]](http://vdel.me.cmu.edu/vdelresource/publications/2011ieee/Data/) |
| [Closure-aware Sketch Simplification](https://dl.acm.org/doi/10.1145/2816795.2818067) | SIGGRAPH 2015 | [[project]](https://ttwong12.github.io/papers/sketch/sketch.html) |
| [StrokeAggregator: Consolidating Raw Sketches into Artist-Intended Curve Drawings](https://dl.acm.org/doi/10.1145/3197517.3201314) | SIGGRAPH 2018 | [[project]](https://www.cs.ubc.ca/labs/imager/tr/2018/StrokeAggregator/) |
| [StripMaker: Perception-driven Learned Vector Sketch Consolidation]() | SIGGRAPH 2023 | [[project]](https://www.cs.ubc.ca/labs/imager/tr/2023/stripmaker/) |

### 7.3 Fitting
| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [Sketch-Based 3D-Shape Creation for Industrial Styling Design](https://ieeexplore.ieee.org/document/4052500) | CG&A 2007 | |
| [Beautification of Design Sketches Using Trainable Stroke Clustering and Curve Fitting](https://ieeexplore.ieee.org/abstract/document/5710858) | TVCG 2011 | [[data]](http://vdel.me.cmu.edu/vdelresource/publications/2011ieee/Data/) |
| [StrokeStrip: Joint Parameterization and Fitting of Stroke Clusters](https://dl.acm.org/doi/10.1145/3450626.3459777) | SIGGRAPH 2021 | [[project]](https://www.cs.ubc.ca/labs/imager/tr/2021/StrokeStrip/) |

## 8. Flat Colorization/Junction Reconstruction

### 8.1 Region Filling

| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [Vectorizing Cartoon Animations](https://ieeexplore.ieee.org/document/4745633) | TVCG 2009 | |
| [LazyBrush: Flexible Painting Tool for Hand-drawn Cartoons](https://onlinelibrary.wiley.com/doi/full/10.1111/j.1467-8659.2009.01400.x) | Eurographics 2009 | [[project]](https://dcgi.fel.cvut.cz/home/sykorad/lazybrush.html) |
| [Color by Numbers: Interactive Structuring and Vectorization of Sketch Imagery](https://dl.acm.org/doi/10.1145/3411764.3445215) | CHI 2021 | |
| [Delaunay Painting: Perceptual Image Colouring from Raster Contours with Gaps](https://onlinelibrary.wiley.com/doi/10.1111/cgf.14517) | Eurographics 2022 | [[video]](https://www.youtube.com/watch?v=OHst_FAee3Q) |

### 8.2 Junction Connection

| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [Automatic Gap Closing for Freehand Drawing](https://www.semanticscholar.org/paper/Automatic-Gap-Closing-for-Freehand-Drawing-Gangnet-Thong/537e40b0587bb76c1d18599b38212b63e092962a) | SIGGRAPH 1994 Technical Sketch | |
| [Dynamic Planar Map Illustration](https://dl.acm.org/doi/10.1145/1276377.1276415) | SIGGRAPH 2007 | |
| [Handling Gaps for Vector Graphics Coloring](https://dl.acm.org/doi/10.1007/s00371-021-02235-x) | CGI 2021 | [[video]](https://www.youtube.com/watch?v=b4yR9_Wcuac) |
| [A Fast and Efficient Semi-guided Algorithm for Flat Coloring Line-arts](https://diglib.eg.org/items/0aa483d1-5ca6-4a2e-9813-c421e10e3cc7) | Eurographics 2018|  |
| [Endpoint Fusing Method for Axonometric Drawing of Online Freehand Sketched Polyhedrons](https://dl.acm.org/doi/10.1007/s00371-018-1608-5) | The Visual Computer 2020 | |
| [Detecting Viewer-Perceived Intended Vector Sketch Connectivity](https://dl.acm.org/doi/10.1145/3528223.3530097) | SIGGRAPH 2022 | [[project]](https://www.cs.ubc.ca/labs/imager/tr/2022/SketchConnectivity/) |

### 8.3 Learning-Based

| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [Joint Gap Detection and Inpainting of Line Drawings](https://ieeexplore.ieee.org/document/8100094) | CVPR 2017 | [[code]](https://github.com/kaidlc/CVPR2017_linedrawings) |
| [DanbooRegion: An Illustration Region Dataset](https://dl.acm.org/doi/10.1007/978-3-030-58601-0_9) | ECCV 2020 | [[project]](https://lllyasviel.github.io/DanbooRegion/) |
| [User-Guided Line Art Flat Filling with Split Filling Mechanism](https://ieeexplore.ieee.org/document/9578141) | CVPR 2021 | [[project]](https://lllyasviel.github.io/SplitFilling/) |
| [FlatMagic: Improving Flat Colorization through AI-driven Design for Digital Comic Professionals](https://dl.acm.org/doi/10.1145/3491102.3502075) | CHI 2022 | [[project]](https://cragl.cs.gmu.edu/flatmagic/) |

## 9. 2D Sketch Lifting

| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [Optimization-Based Reconstruction of a 3D Object From a Single Freehand Line Drawing](https://dl.acm.org/doi/10.1145/1281500.1281556) | SIGGRAPH 2007 course| |
| [OpenSketch: A Richly-Annotated Dataset of Product Design Sketches](https://dl.acm.org/doi/10.1145/3355089.3356533) | SIGGRAPH Asia 2019 | [[project]](https://ns.inria.fr/d3/OpenSketch/) |
| [Lifting Freehand Concept Sketches into 3D](https://dl.acm.org/doi/10.1145/3414685.3417851) | SIGGRAPH Asia 2020 | [[project]](https://ns.inria.fr/d3/Lift3D/) |
| [Symmetry-driven 3D Reconstruction from Concept Sketches](https://dl.acm.org/doi/10.1145/3528233.3530723) | SIGGRAPH 2022 | [[project]](https://ns.inria.fr/d3/SymmetrySketch/) |

## 10. 3D Sketch Surfacing

| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [SurfaceBrush: From Virtual Reality Drawings to Manifold Surfaces](https://dl.acm.org/doi/10.1145/3306346.3322970) | SIGGRAPH 2019 | [[project]](https://www.cs.ubc.ca/labs/imager/tr/2019/SurfaceBrush/) |
| [Variational Implicit Point Set Surface](https://dl.acm.org/doi/10.1145/3306346.3322994) | SIGGRAPH 2019 | [[code]](https://github.com/adshhzy/VIPSS) |
| [Piecewise-Smooth Surface Fitting onto Unstructured 3D Sketches](https://dl.acm.org/doi/10.1145/3528223.3530100) | SIGGRAPH 2022 | [[project]](https://em-yu.github.io/research/surfacing_3d_sketches/) |
| [Globally Consistent Normal Orientation for Point Clouds by Regularizing the Winding-number Field](https://dl.acm.org/doi/10.1145/3592129) | SIGGRAPH 2023 | [[project]](https://xrvitd.github.io/Projects/GCNO/index.html) |

## 11. Sketch-Based Modeling

### 11.1 Organic Shapes

| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [Teddy: A Sketching Interface for 3D Freeform Design](https://dl.acm.org/doi/10.1145/311535.311602) | SIGGRAPH 1999 | [[project]](https://www-ui.is.s.u-tokyo.ac.jp/~takeo/teddy/teddy.htm) |
| [FiberMesh: Designing Freeform Surfaces with 3D Curves](https://dl.acm.org/doi/10.1145/1276377.1276429) | SIGGRAPH 2007 | [[project]](https://igl.ethz.ch/projects/FiberMesh/index.php) |
| [Ink-and-Ray: Bas-Relief Meshes for Adding Global Illumination Effects to Hand-Drawn Characters](https://dl.acm.org/doi/10.1145/2591011) | SIGGRAPH 2014 | [[project]](https://users.cs.utah.edu/~ladislav/sykora14ink/sykora14ink.html) |
| [Modeling Character Canvases from Cartoon Drawings](https://dl.acm.org/doi/abs/10.1145/2801134) | SIGGRAPH 2015 | [[project]](https://www.cs.ubc.ca/labs/imager/tr/2015/Canvases/) |
| [RodMesh: Two-handed 3D Surface Modeling in Virtual Reality](https://diglib.eg.org/items/ca3dc460-6022-4bb7-bb87-131c122e9a7a) | VMV 2019 | [[project]](https://igl.ethz.ch/projects/rodmesh/) |
| [Monster Mash: A Single-View Approach to Casual 3D Modeling and Animation](https://dl.acm.org/doi/10.1145/3414685.3417805) | SIGGRAPH Asia 2020 | [[project]](https://dcgi.fel.cvut.cz/home/sykorad/monster_mash) |

### 11.2 Geometric and CAD Models

| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [Analytic Drawing of 3D Scaffolds](https://dl.acm.org/doi/10.1145/1618452.1618495) | SIGGRAPH Asia 2009 | [[project]](https://www.dgp.toronto.edu/~rms/pubs/DrawingSGA09.html) |
| [CrossShade: Shading Concept Sketches Using Cross-Section Curves](https://dl.acm.org/doi/10.1145/2185520.2185541) | SIGGRAPH 2012 | [[project]](http://crossshade.com/) |
| [Sketch-to-Design: Context-based Part Assembly](https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.12200) | Computer Graphics Forum 2013 | |
| [True2Form: 3D Curve Networks from 2D Sketches via Selective Regularization](https://dl.acm.org/doi/10.1145/2601097.2601128) | SIGGRAPH 2014 | [[project]](https://www.cs.ubc.ca/labs/imager/tr/2014/True2Form/index.htm) |
| [SENS: Part-Aware Sketch-based Implicit Neural Shape Modeling](https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.15015) | Eurographics 2024 | [[project]](https://alexandrebinninger.com/SENS/) |
| [Sketch2CAD: Sequential CAD Modeling by Sketching in Context](https://dl.acm.org/doi/10.1145/3414685.3417807) | SIGGRAPH Asia 2020 | [[project]](https://geometry.cs.ucl.ac.uk/projects/2020/sketch2cad/) |
| [Free2CAD: Parsing Freehand Drawings Into CAD Commands](https://dl.acm.org/doi/abs/10.1145/3528223.3530133) | SIGGRAPH 2022 | [[project]](https://geometry.cs.ucl.ac.uk/projects/2022/free2cad/) |

### 11.3 Domain Specific

| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [SecondSkin: Sketch-based Construction of Layered 3D Models](https://dl.acm.org/doi/10.1145/2766948) | SIGGRAPH 2015 | [[project]](https://www.dgp.toronto.edu/~depaolic/projects/secondSkin/) |
| [Interactive Sketching of Urban Procedural Models](https://dl.acm.org/doi/10.1145/2897824.2925951) | SIGGRAPH 2016 | [[project]](https://www-sop.inria.fr/reves/Basilic/2016/NGGBB16/) |
| [FoldSketch: Enriching Garments with Physically Reproducible Folds](https://dl.acm.org/doi/10.1145/3197517.3201310) | SIGGRAPH 2018 | [[project]](https://www.cs.ubc.ca/labs/imager/tr/2018/FoldSketch/) |
| [Interactive Liquid Splash Modeling by User Sketches](https://dl.acm.org/doi/abs/10.1145/3414685.3417832) | SIGGRAPH Asia 2020 | [[project]](https://wanghmin.github.io/publication/yan-2020-ils/) |
| [SketchHairSalon: Deep Sketch-based Hair Image Synthesis](https://dl.acm.org/doi/abs/10.1145/3478513.3480502) | SIGGRAPH Asia 2021 | [[project]](https://chufengxiao.github.io/SketchHairSalon/) |

## 12. Sketch-Based Editing

| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [A Sketch-Based Interface for Detail-Preserving Mesh Editing](https://dl.acm.org/doi/10.1145/1186822.1073324) | SIGGRAPH 2005 | [[project]](https://igl.ethz.ch/projects/Laplacian-mesh-processing/sketch-mesh-editing/index.php) |
| [Modeling from Contour Drawings](https://dl.acm.org/doi/10.1145/1572741.1572749) | SBIM 2009 | |
| [Sketching in Gestalt Space: Interactive Shape Abstraction through Perceptual Reasoning](https://onlinelibrary.wiley.com/doi/full/10.1111/cgf.13321) | Computer Graphics Forum 2018 | [[project]](https://vcc.tech/research/2018/3DGestalt) |
| [Sketch2Mesh: Reconstructing and Editing 3D Shapes from Sketches](https://www.computer.org/csdl/proceedings-article/iccv/2021/281200n3003/1BmJsHikEfu) | ICCV 2021 | [[code]](https://github.com/cvlab-epfl/sketch2mesh) |
| [SKED: Sketch-guided Text-based 3D Editing](https://www.computer.org/csdl/proceedings-article/iccv/2023/071800o4561/1TJgXGJgCYg) | ICCV 2023 | [[project]](https://sked-paper.github.io/) |
| [SketchDream: Sketch-based Text-to-3D Generation and Editing]() | SIGGRAPH 2024 | [[project]](https://geometrylearning.com/SketchDream/) |
| [Squidgets: Sketch-based Widget Design and Direct Manipulation of 3D Scenes](https://arxiv.org/abs/2402.06795) | 2024 | |

## 13. Sketch-Based Animation Control

### 13.1 Posing

| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [The Line of Action: an Intuitive Interface for Expressive Character Posing](https://dl.acm.org/doi/10.1145/2508363.2508397) | SIGGRAPH Asia 2013 | [[project]](https://team.inria.fr/imagine/the-line-of-action-an-intuitive-interface-for-expressive-character-posing/) |
| [Differential Blending for Expressive Sketch-Based Posing](https://dl.acm.org/doi/10.1145/2485895.2485916) | SCA 2013 | [[project]](https://cgl.ethz.ch/publications/papers/paperOzt13.php) |
| [Gesture3D: Posing 3D Characters via Gesture Drawings](https://dl.acm.org/doi/10.1145/2980179.2980240) | SIGGRAPH Asia 2016 | [[project]](https://www.cs.ubc.ca/labs/imager/tr/2016/Gesture3D/) |
| [Sketch2Pose: Estimating a 3D Character Pose from a Bitmap Sketch](https://dl.acm.org/doi/10.1145/3528223.3530106) | SIGGRAPH 2022 | [[project]](https://www-labs.iro.umontreal.ca/~bmpix/sketch2pose/) |

### 13.2 Animation

| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [Space-Time Sketching of Character Animation](https://dl.acm.org/doi/10.1145/2766893) | SIGGRAPH 2015 | [[project]](https://team.inria.fr/imagine/space-time-sketching-of-character-animation/) |
| [SketchiMo: Sketch-based Motion Editing for Articulated Characters](https://dl.acm.org/doi/10.1145/2897824.2925970) | SIGGRAPH 2016 | [[project]](https://vml.kaist.ac.kr/main/international/individual/2) |
| [Tangent-Space Optimization for Interactive Animation Control](https://dl.acm.org/doi/10.1145/3306346.3322938) | SIGGRAPH 2019 | [[project]](https://cgl.ethz.ch/publications/papers/paperCic19a.php) |

## 14. Sketch Perception

| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [Where Do People Draw Lines?](https://dl.acm.org/doi/10.1145/1360612.1360687) | SIGGRAPH 2008 | [[project]](https://gfx.cs.princeton.edu/pubs/Cole_2008_WDP/) |
| [How Well Do Line Drawings Depict Shape?](https://dl.acm.org/doi/10.1145/1576246.1531334) | SIGGRAPH 2009 | [[project]](https://gfx.cs.princeton.edu/pubs/Cole_2009_HWD/index.php) |
| [Tracing Versus Freehand for Evaluating Computer-Generated Drawings](https://dl.acm.org/doi/10.1145/3450626.3459819) | SIGGRAPH 2021 | [[project]](https://zachzeyuwang.github.io/tracing-vs-freehand.html) |
| [DifferSketching: How Differently Do People Sketch 3D Objects?](https://dl.acm.org/doi/abs/10.1145/3550454.3555493) | SIGGRAPH Asia 2022 | [[project]](https://chufengxiao.github.io/DifferSketching/) |
| [The Role of Edges in Line Drawing Perception](https://journals.sagepub.com/doi/full/10.1177/0301006621994407) | Perception 2021 | |

## 15. Vision Tasks on Sketches

| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [Deep Learning for Free-Hand Sketch: A Survey](https://ieeexplore.ieee.org/document/9706366) | TPAMI 2022 | [[project]](https://www.research.ed.ac.uk/en/publications/deep-learning-for-free-hand-sketch-a-survey) |
| [OpenSketch: A Richly-Annotated Dataset of Product Design Sketches](https://dl.acm.org/doi/10.1145/3355089.3356533) | SIGGRAPH Asia 2019 | [[project]](https://ns.inria.fr/d3/OpenSketch/) |
| [Creative Flow+ Dataset](https://ieeexplore.ieee.org/document/8953383) | CVPR 2019 | [[project]](https://www.cs.toronto.edu/creativeflow/) |
| [Deep Sketch-Based Modeling: Tips and Tricks](https://arxiv.org/abs/2011.06133) | 3DV 2020 | [[code]](https://github.com/Yueeey/deepsketch) |
| [Neural Strokes: Stylized Line Drawing of 3D Shapes](https://arxiv.org/abs/2110.03900) | ICCV 2021 | [[project]](https://people.cs.umass.edu/~dliu/projects/NeuralStrokes/) |
| [CAD2Sketch: Generating Concept Sketches from CAD Sequences](https://dl.acm.org/doi/abs/10.1145/3550454.3555488) | SIGGRAPH Asia 2022 | [[project]](https://www-sop.inria.fr/reves/Basilic/2022/HLMB22/) |

### 15.1 Sketch Understanding

| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [SketchDesc: Learning Local Sketch Descriptors for Multi-view Correspondence](https://arxiv.org/abs/2001.05744) | TCSVT 2020	 | [[project]](https://dengyuhk.github.io/SketchDesc/) |
| [SketchZooms: Deep Multi-view Descriptors for Matching Line Drawings](https://onlinelibrary.wiley.com/doi/10.1111/cgf.14197) | Computer Graphics Forum 2020 | [[project]](https://ignaciorlando.github.io/publication/2020-cgf-sketchzooms/) |
| [SEVA: Leveraging Sketches to Evaluate Alignment between Human and Machine Visual Abstraction](https://arxiv.org/abs/2312.03035) | NeurIPS 2023 | [[project]](https://seva-benchmark.github.io/) |

### 15.2 Sketch Generation

| Paper | Source | Code/Project Link  |
| --- | --- | --- |
| [CLIPasso: Semantically-Aware Object Sketching](https://dl.acm.org/doi/abs/10.1145/3528223.3530068) | SIGGRAPH 2022 | [[project]](https://clipasso.github.io/clipasso/) |
| [CLIPascene: Scene Sketching with Different Types and Levels of Abstraction](https://www.computer.org/csdl/proceedings-article/iccv/2023/7.18E127/1TJdfQXb3R6) | ICCV 2023 | [[project]](https://clipascene.github.io/CLIPascene/) |
| [SketchKnitter: Vectorized Sketch Generation with Diffusion Models](https://iclr.cc/virtual/2023/poster/11832) | ICLR 2023 | [[project]](https://github.com/wangqiang9/SketchKnitter) |
| [Breathing Life Into Sketches Using Text-to-Video Priors](https://arxiv.org/abs/2311.13608) | CVPR 2024 | [[project]](https://livesketch.github.io/) |
