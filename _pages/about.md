---
permalink: /
title: Highlights
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
# Distributed Multi-robot Trajectory Optimization [DiMOpt Algorithm] 
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


# Fleet Management on a Bus Depot [iQMobility project]

<img src="/images/dellrud.gif" title="mapf demo" style="float:right;width:350pt;padding-left:10px;" />
<img src="/images/leipzig-clip-opt1.gif" title="mapf demo" style="float:right;width:350pt;padding-left:10px;" />
**Coordination** of fleets of buses on the Dellrud Depot (top video), and on the Leipzig Depot (bottom video). 

1. A sequence of goals are assumed to be given by a Depot Manager which are then posted to the buses. 
2. **Paths** are generated via an **off-shelf motion planner** (e.g. OMPL) or a roadmap of Geo-located **motion primitives**. Moreover, a mixture of pre-computed and lively computed trajectories was also explored. 
3. Collisions between robots are solved by imposing a **precedences between robots** while accounting for robot dynamic models. 

Tools utilized: [repo](https://github.com/joaosalvado/coordination_oru), [OMPL](http://ompl.kavrakilab.org/), *Scania* GPS Maps and Buses.

