---
title: "Trajectory and intention forecasting"
excerpt: "Recent developments in **autonomous driving** have led to very effective vehicles that can coexist with legacy, connected and other autonomous cars while obeying the road rules. One of the main challenges for autonomous cars is to reach coexistence with pedestrians and cyclists in a safe but efficient manner, which implies being able  to **foresee the street users intentions/future motions in the short and mid term**."

collection: projects
---
 There are many challenges to overcome for a safe coexistence of autonomous cars and pedestrians to be possible: the limited on-board observations, the very different weather conditions (rain, snow, dust, etc), the presence of multiple road users in the same scene, the very different motion patterns users may have, the large variety of situations, to give only a few ones.<br>

<img src='/images/illus.png'><br>

Our proposal is oriented to pedestrian/cyclist motion prediction at short (1-2 s) and mid term (10-20 s) for anticipating potential collision risks. Our key insight is that pedestrians/cyclists movements and intents are governed by their context, e.g. social forces and environment constraints or semantics. For an effective estimation of pedestrian or cyclist intent, situation-awareness is of paramount importance, which implies to rely on the immediate surroundings of the users (presence of other users, presence of obstacles, presence of road crossings…), but also on scene semantics. One of the direction we are considering is to use public geo-tagged information (e.g. from search engines such as Google Maps or OpenStreetMap) to extract would-be relevant semantic cues to be used in the inference system. For example, the presence of an elementary school near a crossing may make probable some massive road crossing at peak hours; the presence of a bar may raise the odds for erratic behaviours in late night. Similarly, some latent variables are important to consider for motion prediction: for example, the surrounding obstacle map and the specific spatial goal of a pedestrian on the other side of a crossing will probably influence the shape of his path along the crossing; the streetlight color should be an important factor for the crossing decision; also, would we suspect that a road user is currently looking at his mobile phone, as it occurs frequently in modern day streets, this should modify critically our prediction of its short-term motion and may also lower the odds that the pedestrian takes into account the street light; last, the presence of other pedestrians has also impact on its trajectory.

### Related thesis
{% for post in site.thesis reversed %}
    {% if post.tags contains "htp" %}
      {% include archive-single-publi.html %}
    {% endif %}  
{% endfor %}
