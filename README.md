# ENPM690_HW3
<a href='https://github.com/abhi1625/turtlebot_walker/blob/master/LICENSE'><img src='https://img.shields.io/badge/License-MIT-brightgreen.svg'/></a>

## Overview
A simple walker algorithm, like roomba, implemented on a 2 wheeled differential-drive robot

## Dependencies
The following dependencies are required to run this package:

- ROS kinetic
- catkin
- Ubuntu 16.04
- Turtlebot packages for sensor msgs
For installing ROS, follow the process given [here](http://wiki.ros.org/kinetic/Installation)

For installing catkin, follow the process given [here](http://wiki.ros.org/catkin#Installing_catkin)

For installing turtlebot packages, in a new terminal enter the following command:
```
sudo apt-get install ros-kinetic-turtlebot-*
```
This will install the turtlebot packages. 

**Note:** catkin is usually installed by default when ROS is installed.

## Building the package
To build this package follow the steps below:
```
mkdir -p ~/catkin_ws/src
cd ~/catkin_ws/src
git clone --recursive https://github.com/abhi1625/ENPM690_HW3.git
cd ..
catkin_make
source devel/setup.bash
```
## Running the demo
Once the build is complete successfully, you can run the obstacle avoidance demo using roslaunch:
```
roslaunch walker walker.launch
```
