TeraRanger Duo ROS Module
=========================

[![Join the chat at https://gitter.im/ehsan-asadi/terarangerduo-ros](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/ehsan-asadi/terarangerduo-ros?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This is the ROS module for the TeraRanger Duo ranging sensor (www.teraranger.com).


Using module
============

To use the ROS node you just need to:
* Create a ROS Workspace
* Copy the node terarangerduo package into the workspace src directory
* Compile using: catkin_make 
* Run using: rosrun terarangerduo terarangerduo_node _portname:=/dev/ttyUSB0

NB: remember to execute the daemon roscore before running the rosrun command
