# rosilo
A metapackage with the current compatible version of the rosilo packages.

# Installation

1. Install Ubuntu 20.04
2. Update with 
```shell
sudo apt update && sudo apt upgrade -y
```
4. Install some dependencies
```shell
sudo apt install git terminator cmake python3-pip libeigen3-dev mesa-common-dev libglu1-mesa-dev -y
```
5. Install catkin-tools
```shell
sudo python3 -m pip install git+https://github.com/catkin/catkin_tools.git
```
5. Install DQRobotics-dev
```shell
sudo add-apt-repository ppa:dqrobotics-dev/development -y
sudo apt-get update
sudo apt-get install libdqrobotics*
```
6. Install ROS Noetic.
```shell
sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'
sudo apt-key adv --keyserver 'hkp://keyserver.ubuntu.com:80' --recv-key C1CF6E31E6BADE8868B172B4F42ED6FBAB17C654
sudo apt update
sudo apt install ros-noetic-ros-base -y
```
