---
permalink: /climatedownscaling/
title: "Xingying Huang"
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/home_image.jpg
excerpt: ''

---

###  Variable-resolution global climate modeling and regional climate modeling

Downscaling is a critically important method for improving the accuracy of regional climate data and for enabling fine-scale climate studies. High-resolution datasets are needed for insight into relevant mesoscale processes, and to capture ocean, atmosphere, and land, and topographic feedback. During my PhD, I led the first study to evaluate the CESM model for modeling regional climate using variable-resolution grids, and contrasted these results to a regional model (the Weather Research and Forecasting Model, WRF). These work highlighted the value of variable-resolution global climate models in resolving regional-scale features while avoiding complications from parameterization optimization, enabling upscaling interactions, and largely addressing the computational expense of uniform-resolution global climate models. _(Huang et al. 2016, JAMES, doi: 10.1002/2015MS000559; Huang and Ullrich, 2017, Journal of Climate, doi: 10.1175/JCLI-D-16-0673.1)_

![](/assets/images/papers/vrcesm_fig1.jpg){: .align-center width="600px" }

**Figure 1: The VR-CESM grid configuration.** The approximate grid spacing in the (a) VR‐CESM 0.25° and (b) VR‐CESM 0.125° meshes used in this study. (c) A depiction of the transition from the global 1° resolution mesh through two layers of refinement to 0.25° and again to 0.125°. (***From Huang et al., 2016, JAMES***)

---
###  Deep-learning based climate downscaling

I am also incorporating cutting-edge machine learning-based methods into climate sciences in support of these goals, as partly revealed in one of my recent work using deep-learning based super-resolution method to retrieve fine-resolution climate information. The strength of this new downscaling method is implied in learning priors/network’s optimal parameters from enough amounts of training data, which proved to be a quick and efficient way for getting finer scale climate variables accurately. Such optimized convolution neural network framework can be developed further for other purposes, as part of future plans. _(Huang, X., 2020, GMD, submitted)_.

![](/assets/images/papers/supres_fig1.jpg){: .align-center width="900px" }

**Figure 2: The overview of the framework of the deep convolutional neural network and its components used in this study.** The network is composed of a sequence of convolutional layers, batch normalization layers, and ReLU layers. Dashed arrow lines represent the skip connections; Gold-colored layers refer to the ones with stride value of 2. The numbers on the top of each convolutional layer refer to the filter size, and the number on the bottom of that refers to the grid size of the image. (***From Huang et al., 2020, Submitted***)
