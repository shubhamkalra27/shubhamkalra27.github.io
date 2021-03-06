---
layout: post
title: Visualizing Random Walk 
category: Project
tags: random-walk javascript-viz fiddle markov-chain 
---

*M*y probability teacher opened our class of [Markov Chain Model](https://en.wikipedia.org/wiki/Markov_chain) by giving us the drunk man hypothesis - A drunk man will find his way home. We all had a laugh, but I had an urge to try this out everytime I was in those shoes. What better way to simulate this experiment. 

Link to fiddle - Link to fiddle - [http://jsfiddle.net/27thmartian/y16sqcb0/embedded/result/](http://jsfiddle.net/27thmartian/y16sqcb0/embedded/result/)

![Walker](https://github.com/shubhamkalra27/randomwalk/raw/master/recording%20(2).gif)


### Visualisation Notes:

* Walker starts from origin to walk randomly in unit steps
* We need to see if walker will come back to origin
* A random generator decides whether the person goes north-south or west-east.
* A Second randomizer moves walker to forward or backward in the previously selected dimension.
* The chart is re-rendered after the given amount of time, defaulted to 50 ms.
* A walker may or maynot hit the origin. Increase the steps to see if it returns to origin
* At the end of the program, we see the Average Steps taken to Return to Origin

### Assumptions
* Each step takes 1 unit time
* Walker takes one of the equally likely four paths available - North, South, East or West
* Each change in direction is exactly at right angles

### Conclusion
If you let walker walk long enough it will come back to origin

or a drunk person - who can follow the easy assumptions of - 
* walking exact size steps
* turning at exact right angles
will eventually reach home 


![Walker](https://github.com/shubhamkalra27/randomwalk/raw/master/walker.gif)


