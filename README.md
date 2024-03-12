# mujoco_ros_sim

Simple connect between mujoco with ros. 

Mujoco sends joint and sensor data via rostopic, and receives torque or position command data via rostopic.   

mujoco is based on 2.1 // Mujoco is free now!

position/torque command available

※ubuntu 18.04 is recommended since graphical issue at 16.04

## Installation

clone this git to your_catkin_ws/src, then compile with catkin_make