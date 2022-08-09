---
title: "Towards Ubiquitous Autonomous Driving: The CCSAD Dataset"
excerpt: "Several **online real-world stereo datasets** exist for the development and testing of algorithms in the fields of perception and navigation of autonomous vehicles. However, none of them was recorded in **developing countries**, and therefore they lack the particular challenges that can be found on their streets and roads, like abundant potholes, irregular speed bumpers, and peculiar flows of pedestrians. We introduce a novel dataset that possesses such characteristics."

collection: projects
---

The stereo dataset was recorded in Mexico from a **moving vehicle**. It contains high-resolution stereo images which are complemented with direction and acceleration data obtained from an IMU, GPS data, and data from the car computer.

<table>
<tr>
<td><div class="fitvidsignore">
<iframe width="100%" height="300" src="https://www.youtube.com/embed/jBnM5Fo70vc" title="Obstacle avoidance with vision-driven humanoid locomotion (2)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div></td><td><div class="fitvidsignore">
<iframe width="100%" height="300" src="https://www.youtube.com/embed/DHLWCtNvyCs" title="Obstacle avoidance with vision-driven humanoid locomotion (3)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div></td>
</tr>
</table>

### Related thesis
{% for post in site.thesis reversed %}
    {% if post.tags contains "ccsad" %}
      {% include archive-single-publi.html %}
    {% endif %}  
{% endfor %}

### Related publications
{% for post in site.publications reversed %}
  {% if post.tags contains "ccsad" %}
    {% include archive-single-publi.html %}
  {% endif %}  
{% endfor %}
