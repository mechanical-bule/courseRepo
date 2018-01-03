# courseRepo
This folder contains the files for SLAM Robotics & Autonomous Driving course, this course mostly based on: Ubuntu (I use [14.04](http://releases.ubuntu.com/14.04/)) with [ROS Indigo](http://wiki.ros.org/indigo).

Before start, please follow the instruction to install ROS:
- For indigo: [Link](http://wiki.ros.org/indigo/Installation), if you use ubuntu, follow this [link](http://wiki.ros.org/indigo/Installation/Ubuntu)

- For other distribution of ROS, please search google with: ROS + [dirstribution](http://wiki.ros.org/Distributions) + install

# How to creat a ROS Workspace, it is more convenient than catkin_workspace
1. First step:
cd ~/ 
mkdir ROS_WORKSPACE

2. Edit .bashrc

gedit .bashrc # open .bashrc under ~/

paste the following behind source /opt/ros/indigo/setup.bash:

ROS_WORKSPACE=$HOME/ROS_WORKSPACE
export ROS_WORKSPACE
ROS_PACKAGE_PATH=$ROS_WORKSPACE:$ROS_PACKAGE_PATH
export ROS_PACKAGE_PATH
