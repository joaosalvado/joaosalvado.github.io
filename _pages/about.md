---
permalink: /
title: "Joao Salvado"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
# Distributed Multi-robot Trajectory Optimization (DiMOpt)
<img src="/images/onedown.gif" title="mapf demo" style="float:right;width:200pt;padding-left:10px;" />
 <img src="/images/circle.gif" style="float:right;width:200pt;padding-left:10px;" />    
 <img src="/images/takeover.gif" style="float:right;width:200pt;padding-left:10px;" />  
  <img src="/images/squaresided.gif" style="float:right;width:200pt;padding-left:10px;" /> 

Trajectory optimization approaches can optimally solve the problem of computing trajectories for multiple robots navigating in a shared space. However, such methods are hampered by *complex robot dynamics* and
collision constraints that *couple robot’s decision variables*. We propose a distributed multi-robot optimization algorithm (DiMOpt) which addresses these issues by exploiting:

1.  **Consensus optimization** strategies to tackle coupling collision constraints.
2.  **Single-robot sequential convex programming** (SCP) method for efficiently handling non-convexities introduced by dynamics.
\
The source code is openly available at [repo](https://github.com/joaosalvado/DiMOpt)
