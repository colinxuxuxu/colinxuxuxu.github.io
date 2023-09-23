---
layout: post
title:  "Mario"
summary: "Implemented Mario with basic collision and a single level"
date:   2023-9-22
preview: /assets/Mario2.jpg
---

![Picture 1](/assets/Mario.png)
[Play Mario Here!](/assets/Mario/Lab04.html)

Since Mario is 2D, the collision check is a little bit of work:
*We first mark the objects we want Mario to collide with in a vector at game start
*Then we loop over the vector to check if Mario overlaps with a collider actor, if he does, find out which side of the block he is touching and add the 
overlap offset to make it look like normal force is acting on the block and Mario.
