---
title: "Formation control for quadricopters"
excerpt: "In this project, we design algorithms to control quadcopters formations in a distributed way, using consensus theory. One of the main difficulties is that the trajectories of the quadcopters should be without collision, with either static obstacles in the environment or with other quadcopters."

collection: projects
---

In this project, we design **algorithms for controlling drones** (quadricopters) which are parts of a swarm so that, by controlling them in a **distributed** way (any drone takes his own decision based on the **sensing information it can gather**), we can ensure that:

* a **desired configuration** of the formation (indicated by relative positions of the drones) is attained;
* the motion of the different robots does not generate any collision, either with another drone or with elements of the map.

Two videos from Salim Vargas'MSc. thesis:

<iframe width="50%" src="https://www.youtube.com/embed/sXTGWBh2l8k" title="Formation control with simultaneous obstacle avoidance and connectivity maintenance" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<iframe width="50%" src="https://www.youtube.com/embed/A9RQxtIBx6s" title="Formation control with 4 Bebops drones" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Related thesis
