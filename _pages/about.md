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
Webinar: Speaker at the iQPilot and iQMobility [webinar](https://sites.google.com/view/iqpilot-iqmobility/webinar-invitation) 


# Network Flow for Multi-robot Path Planning
<img src="/images/map_contour.png" title="mapf demo" style="float:right;width:200pt;padding-left:10px;" />
<img src="/images/graph.png" style="float:right;width:200pt;padding-left:10px;" />  
<img src="/images/paths.png" style="float:right;width:200pt;padding-left:10px;" /> <img src="/images/network.png" style="float:right;width:190pt;padding-left:10px;" />   


The problem of **multi-robot path finding and goal allocation** can be abstracted to a **Min-Cost Max-Flow** problem, which can be solved effeciently. [*Figure top left*] contours of the environment. [*Figure top right*] the respective connectivity graph of the computed tesselation and obstacles approximated by ellipses. [*Figure bottom left*] illustrative multi-robot path. [*Figure bottom right*] Time expanded dynamic network of the considered map.

The output of this algorithm is a sequence of convex polygons that lead the robots from their initial to the final set of polygons.

The source code is openly available at [repo](https://github.com/joaosalvado/mrflow)

# Coordination of Multiple Forklifts [ILIAD Project]

<img src="/images/m2iliad.gif" title="mapf demo" style="float:right;width:350pt;padding-left:10px;" />
Multiple forklifts path planning in a *warehouse* environment. This video shows the milestone 2 demo with two forklifts simulating missions of picking and placing items in oposite rooms while sharing a common corridor with a max capacity of a single forklift.

1. Pick-and-place missions are dispached to the fleet of forklifts
2. Integrate task and motion planning with **paths** created via motion planner developed by project partner.
3. Collisions between robots are solved by imposing a **precedences between robots** while accounting for robot dynamic models. 

Tools utilized: [repo](https://github.com/joaosalvado/coordination_oru).
Project [link](http://iliad-project.eu/wp-content/uploads/2017/04/ILIAD-ERF2017-poster.jpg)


