# 3-DOF Non-Planar Robot Project

This repository contains a 3-DOF non-planar robotic arm model designed to be used with ROS 2 and Gazebo. The arm has three revolute joints that allow it to move in 3D space, and it is defined using Xacro/URDF for simulation in Gazebo.

## Prerequisites

- ROS 2 (Humble or compatible version)
- [colcon](https://colcon.readthedocs.io/en/released/) build tool
- Gazebo (comes installed with ROS 2 by default on many setups)

## Steps to Build and Run

1. **Clone this repository** into your ROS 2 workspace.

2. **Build the workspace**:
   ```sh
   colcon build
   ```
3. **Source the setup file**
```sh 
source install/setup.sh
```
4. **Launch Gazebo with the robot model**
```sh
ros2 launch simple_robot_description gazebo.launch.py
```
