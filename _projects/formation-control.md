---
title: "Formation control for quadricopters"
excerpt: "In this project, we design algorithms to control quadcopters formations in a distributed way, using consensus theory. One of the main difficulties is that the trajectories of the quadcopters should be without collision, with either static obstacles in the environment or with other quadcopters."

collection: projects
---

In this project, we design **algorithms for controlling drones** (quadricopters) which are parts of a swarm so that, by controlling them in a **distributed** way (any drone takes his own decision based on the **sensing information it can gather**), we can ensure that:

* a **desired configuration** of the formation (indicated by relative positions of the drones) is attained;
* the motion of the different robots does not generate any collision, either with another drone or with elements of the map.

Two videos from Salim Vargas'MSc. thesis:
<div class="fitvidsignore">
<iframe width="49%" height="300" src="https://www.youtube.com/embed/sXTGWBh2l8k" title="Formation control with simultaneous obstacle avoidance and connectivity maintenance" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
<div class="fitvidsignore">
<iframe width="49%" height="300" src="https://www.youtube.com/embed/A9RQxtIBx6s" title="Formation control with 4 Bebops drones" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

### Related thesis

* *Distributed model predictive control for formations of quadrotors* (Msc. thesis), by	Salim Vargas. Co -advised with Héctor Manuel Becerra Fermín. 12/01/2020<br>
<a href="https://cimat.repositorioinstitucional.mx/jspui/bitstream/1008/1106/1/TE%20815.pdf"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a>
* *Vision-Based Formation Control For Unmanned Aerial Vehicles* (Msc. thesis), by Patricia Marisol del Carmen Tavares Ramírez. Co-advised with Héctor Manuel Becerra Fermín. 01/28/2019<br>
<a href="https://cimat.repositorioinstitucional.mx/jspui/bitstream/1008/1005/1/TE%20728.pdf"><i class="fas fa-fw fa-file-pdf zoom" aria-hidden="true"></i></a>
