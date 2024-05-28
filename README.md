### AWS-Internship-Project

Project for aws internship.


## Problem Title : Deploy a cloud 
A Cloud developer is someone with multiple horizons of skills and ideas , be it Devops,
Debugging or programming . You work at a software company IS Robotics , you work as
a software engineer, you need to deploy ROS (Robot Operating System ) on Cloud
which will allow the devlopers to run their robotic simulation and do more
implementation

We Need to deploy ROS Neotic on the Cloud , Which is essentially going to allow the
developers monitor and run their codes on the cloud .

# Requirements for the Cloud

Ubuntu 20.04 LTS
General purpose t2.micro.
30GB of Storage
PrerequisitesCreate a AWS Account .


Installing Process for ROS (After Cloud is hosted and
running)

Installation ROS

1. Configure your Ubuntu repositories

2. Setup your sources.list

3. Setup your computer to accept software from packages.ros.org.
```
sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'
```
4. Set up your keys
If you haven't already installed curl
```
sudo apt install curl 
```
```
curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add-
```

Installation

5.First, make sure your Debian package index is up-to-date:

```
sudo apt update
```

6. Now pick how much of ROS you would like to install.

Desktop-Full Install: (Recommended) : Everything in Desktop plus 2D/3D simulators and 2D/3D perception packages

```
sudo apt install ros-noetic-desktop-full
```
or click here

7. Environment setup

You must source this script in every bash terminal you use ROS in.

```
source /opt/ros/noetic/setup.bash
```

