# Online Histogram
## Introduction
Original code obtained from: http://answers.ros.org/question/31384/online-histogram-with-matplotlib/
## Dependencies
Requires ....

ROS Dependencies:
* dynamic_reconfigure
* geometry_msgs
* roscpp
* rospy
* std_msgs.

## Installation
### Compile from source

- Clone XXXX repository into the src folder of an existing or new catkin compatible workspace, and then build using catkin. To compile in ROS Indigo:

```
cd ~/catkin_ws/src
git clone https://github.com/raultron/XXXXX.git
cd ~/catkin_ws
rosdep install --from-paths src -i
catkin_make
```

## Usage


## Units

## Parameters

## Dynamic reconfiguration of PID Parameters
Use the following command for convenient reconfiguration using a graphical user interface:
```
rosrun rqt_reconfigure rqt_reconfigure
``
