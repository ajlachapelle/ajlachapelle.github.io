---
title: "Topomap Implementation"
excerpt: "A topological projection algorithm recreated from an academic article<br/><img src=''>"
collection: portfolio
---

Overview
======
When we work with data points in machine learning, they can contain any amount of data crunched into one container with potentially hundreds of dimensions. As such, if we want to understand the data intuitively it is important to be able to boil down this information into a readable format. There are various different algorithms that do this, and they each have to pick and choose which aspects to focus on. This algorithm in particular seeks to maintain topology, which means in short that the closest point in 100 dimensions should still be the closest point in three.

The algorithm itself is not my work, but I did work on implementing it as described in its academic article. This project is mainly a showcase of my ability to employ math skills in my programs, as well as understand technical research language. 

[Original](https://arxiv.org/abs/2009.01512): 
<img
  class="fit-picture"
  src="https://ajlachapelle.github.io/images/teaser_cavities.png"
  alt="Original" />
Recreation:
<img
  class="fit-picture"
  src="https://ajlachapelle.github.io/images/cavities.png"
  alt="Recreation" />

[Source Code](https://github.com/ajlachapelle/TopoMap-recreation)
======
Written in Python
