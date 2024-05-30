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

Ubuntu 22.04 LTS
General purpose t2.micro.
30GB of Storage
PrerequisitesCreate a AWS Account .

# Steps

- Step:1
1. create IAM user "test_user". 
2. Attach role or create policy for ec2 and ssh to ec2.
3. Also attch role for cloudwatch to monitoring ec2. 

- Step:2 
1. Lauch EC2 instance with ubuntu 20.04 free version
2. During ec2 creation attach EBS.
3. Enable cloudwatch monitoring for EC2 creation.
After lauching test "ssh" and "cloudwatch" monitoring.

- Step:3
After successful remote ssh to ec2.

1. Run apt-get update and apt-get upgrade
2. Run script for ros installation step by step.
Verify installation and cloudwatch monitoring. 
