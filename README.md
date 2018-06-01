# Robot-Mapping-For-Dummies
A review of the tools you can use to build maps and localize with robots.

```
Note: this is still a work in progress, expect changes and silly mistakes
```

## Introduction

So the brand new camera/lidar/puppy-detector on your robot is working. Obviously smarter people than you and me have built amazing public tools to transform the useless stream of sensor data coming out of it into a beautiful, consistent world map. Or to derive a splendidly accurate estimate of your robot's current position. Right? 

### Right?

After a few google searches, maybe bearing a passing resemblance to "visual keypoint odometry", "lidar 3d mapping", "lidar keypoint comparison", "best odometry from RGB-D framework", "10 loop closure algorithms you probably don't know about", "quitting robotics success story", "sensor fusion SLAM", 
you might have gotten lost and concluded that the problem is harder than it seems, or the smart people are not very good at sharing their amazing tools. Or they're just a pain to find? *What if after six months of head-scratching to build the perfect localizing node, someone casually mentions the exact same thing exists but better, and it was only 5 pages away in some obscure literature search*? Oh no.

And obviously, you've looked at what ROS offers out of the box. Which is very useful if your robot is a 2d roomba with a flat laser scanner. But that's not enough, is it? Otherwise, you wouldn't be here. And to not be casually dismissive, the ROS mapping tools [[1]](http://wiki.ros.org/cn/slam_gmapping/Tutorials/MappingFromLoggedData) are not a bad starting point, there even are some 3D SLAM tutorial(s?) on the ROS wiki [[2]](https://github.com/introlab/rtabmap/wiki/Tutorials), which you might have looked at. And then ended up here anyways. 

Regardless of how it happened, you're here now. You're safe.

### "Oh Lord of Darkness, what Tool is Best for My Robot?"

Before you turn to blood sacrifice and incantations, I hope you will find this to be a *good enough* overview of what currently exists, what it's best at, and where it falls short.
And maybe it'll help you get started faster, impress your PhD supervisor, get paid, or find the love of your life. (Although, before you get your hopes up, I would expect robotics to help marginally less with your love life than, say, eating only garlic bread or wearing a Hannibal Lecter mask.)

## Vocabulary
```
Scratch this section?
```
Are you trying to do SLAM? Just Localization?
A review is only meaningful if the vocabulary is consistent. You might have read on the Google cartographer documentation about it's local SLAM being a *frontend*, and loop closure framework a *backend*. Are those also the terms used by other systems?
...
Descriptor
Frontend/backend
Loop closure
Localization
...

## Tools

```
Todo: Topology based on: sensor input. situation in pipeline. speed. etc...
```

Maplab
Rovio
OrbSlam
Google Cartographer
SegMap
Gmapping
Octomap


...
