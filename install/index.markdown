---
author: admin
comments: false
date: 2016-8-5 20:43:44+00:00
layout: page
slug: install
title: Install
---

# Binary Installation Instructions

MoveIt! is released every month or so into Ubuntu debian packages via the ROS infrastructure. For more information see the [target platforms](http://www.ros.org/reps/rep-0003.html).

MoveIt! is currently released into ROS **Indigo**,  **Kinetic**, and **Lunar**.

**Developers:** see [source install](source/) instructions.

**Virtual Machines:** There have been many reports of problems with the ROS visualization tool RViz when used in virtual machines.
We therefore discourage the use of virtual machines with MoveIt! unless you are not interested in visualization support.

## Prerequisite: Install ROS

Follow all the instructions to install ROS [Indigo](http://www.ros.org/wiki/indigo/Installation/Ubuntu), [Kinetic](http://www.ros.org/wiki/kinetic/Installation/Ubuntu), or
[Lunar](http://www.ros.org/wiki/lunar/Installation/Ubuntu). Please make sure you have followed all steps, including calls to ``rosdep``.

Choose your ROS distribution below:

* * *

## ROS Indigo

*Note for Ubuntu 13.04 32 bit users*: There is a bug with GCC 4.7 on Ubuntu 13.04 32bit with Eigen 3.1.2. It's not likely to be fixed, so upgrade/downgrade your system to 13.04 64 bit resp. 12.04.

### Install Ubuntu Packages

Simply run:

    sudo apt-get install ros-indigo-moveit

### Optional: Install PR2 Ubuntu Packages for MoveIt!

    sudo apt-get install ros-indigo-moveit-full-pr2

### Setup your environment

    source /opt/ros/indigo/setup.bash

See bottom of page for quick start

* * *

## ROS Kinetic

### Install Ubuntu Packages

Simply run:

    sudo apt-get install ros-kinetic-moveit

### Setup your environment

    source /opt/ros/kinetic/setup.bash

See bottom of page for quick start

* * *

## ROS Lunar

### Install Ubuntu Packages

Simply run:

    sudo apt-get install ros-lunar-moveit

### Setup your environment

    source /opt/ros/lunar/setup.bash

See bottom of page for quick start

* * *

## Previous ROS Versions

See [Source Installation Instructions for unsupported versions of MoveIt!](deprecated)

* * *

## Quick Start

Try planning in Rviz with the PR2 move_group demo: [MoveIt! Rviz Plugin Tutorial](http://docs.ros.org/indigo/api/moveit_tutorials/html/doc/ros_visualization/visualization_tutorial.html)
