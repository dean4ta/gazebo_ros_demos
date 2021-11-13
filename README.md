# Gazebo ROS Demos

* Author: Dave Coleman <davetcoleman@gmail.com>
* License: GNU General Public License, version 3 (GPL-3.0)

Example robots and code for interfacing Gazebo with ROS

## Tutorials

[ROS URDF](http://gazebosim.org/tutorials/?tut=ros_urdf)

## Quick Start

Default Entry:

    roslaunch rrbot_gazebo rrbot_world.launch rviz:=true

Example of Moving Joints:

    rostopic pub /rrbot/joint1_effort_controller/command std_msgs/Float64 "data: -2.0"

## Develop and Contribute

We welcome any contributions to this repo and encourage you to fork the project then send pull requests back to this parent repo. Thanks for your help!
