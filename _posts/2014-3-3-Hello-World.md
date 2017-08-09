---
layout: post
title: You're up and running!
js_stock:
- graphs/stock_timeline.js
---
## About Me
Hi! I am Master student at the [Computer Science Department](http://cs.illinois.edu) of [University of Illinois at Urbana-Champaign](http://illinois.edu). I am broadly interested in data engineering, machine learning and data mining. I am on the job market for full-time opportunity in Fall 2017.

## Projects 

### Autonomous Driving
My team and I developed pedestrain detection and auto braking for a by-wire car provided by [AutonomouStuff](https://autonomoustuff.com). The backend model is a fine-tuned TensorFlow implementation of the Single Shot Detection algorithm. When this model detects a pedestrain, the controlling code will further test if this pedestrain is in the region that requires braking. If yes, this code will publish the ROS topic to signal the car to brake. When the pedestrain passes the region for the car to stop, the car will resume running. Chech out our Github repo [here](https://github.com/tensorpro/MAAV)"

<iframe width="560" height="315" src="https://www.youtube.com/embed/zHKE1t_IEIg" frameborder="0" allowfullscreen></iframe>

### Image Processing
In this half semster-long project I took a closer look at the Neural Style algorithm when applying to image segments. Ideally if someone would like to see different styles at different segments of an image, say a skectch style foreground and a Vangah's stary night style background, one can apply the original Neural Style algorithm to different segments. But my study shows artifacts and style blending harms the result of this simple approach. My study then fine-tunes this approach and achieves promising improvements. Full report [here]({{ site.baseurl }}/images/ECE547_Term_Project.pdf).

<style>
#chartdiv {
  width: 100%;
  height: 500px;
}
</style>
<div id="chartdiv"></div>

![Foo]({{ site.baseurl }}/images/ECE547_Term_Project_tot.png)
