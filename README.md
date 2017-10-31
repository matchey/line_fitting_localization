# line_fitting_localization
In this repository, I compiled the source code using ROS for the Line Fitting Localization (LFL).

## Hardware Spec
- PC
	- OS : Ubuntu 16.04
	- Memory : 8GB
	- CPU : Intel® Core™ i7-6700 CPU @ 3.40GHz × 8 
	- GPU : GeForce GTX 970/PCle/SSE2
	- Strage : 1TB

- Robot
	- Sensors
		- AMU-1802BR(IMU)
	- Vehicle
		- Differential drive

## Requirements
- ROS kinetic(Ubuntu 16.04)

## How to setup dependencies
### Install ROS kinetic for Ubuntu 16.04
```
$ sudo apt-get install ros-kinetic-desktop-full
```
**NOTE: Please see the details [Install ROS kinetic](http://wiki.ros.org/kinetic/Installation/Ubuntu).**

## How to Build
```
$ cd $HOME
$ cd ros_catkin_ws/src
$ git clone https://github.com/matchey/line_fitting_localization
$ cd ../
$ catkin_make
```

## How to run
$ roslaunch lf node_edge_pf.launch

## Preparation for the execution
### create edge-node graph

### set yaml file

