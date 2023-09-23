---
layout: post
title:  "Mario Kart"
summary: "Coded a simple level of Mario Kart implemented with an Opponent AI."
date:   2022-10-09 15:39:40
preview: /assets/postpreview.png
---

![Picture 1](/assets/MarioKart.png)
[Click here to play Mario Kart](/assets/MarioKart/Lab08.html)

Here's some catch:

* The kart implements a spring camera by track the position of the Mario Kart and adding a certain displacement to the camera.
* The Opponent AI is implemented with this logic: Track the check point ahead and calculated the crossproduct to see if it should turn right or turn left. Also uses dot product to see if the check point is up ahead in which case the AI would go forward.
