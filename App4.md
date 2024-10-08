# Tangled Tracks

Imagine that you have a set of sensors, and every sensor tracks the coordinates of a single moving object in 2-dimensional space. Each object's trajectory is either a straight line or a circle. 
At any moment the sensor can return a pair of coordinates `(x,y)` along with the current timestamp. 
However, you can't query a particular sensor. You can only query the whole set of sensors, and get the set of object coordinates without any particular order. You need to examine a sequence of sensor data sets, 
identify the objects and plot their trajectories. 

An example of three sets with three objects that move along straight line trajectories.
```
-- First set
0.0,0.0,1725631352
0.0,1.0,1725631352
1.0,1.0,1725631352

– Second set
1.0,0.9,1725637697
0.1,0.1,1725637697
0.1,0.9,1725637697
– Third set
0.2,0.8,1725637710
1.0,0.8,1725637710
0.2,0.2,1725637710
```

