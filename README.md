# panda_tools

Hardware interface package to wrap the standard commands for each robot actuation. Includes standard algorithms related to kinematics such as collision avoidance and some typical examples such as pnp.

## Environment_setup

For more details about environment setup instructions, check `docs/env_setup`

### Hardware environment

- Franka Emika Cobot connected via Ethernet to panda machine (G5 dell laptop)
- RealSense D435 Camera connected via USB to dev machine (g3 dell laptop)
- ROS communication between the two laptops

### Software environment

- panda machine:
    - Ubuntu 20 + 5.9 realtime kernel
    - ros Noetic

- dev machine:
    - Ubuntu 20
    - ros Noetic
    - CUDA 11

## Package structure

### docs

### config

### launch

### scripts

roslaunch panda_moveit_config franka_control.launch robot_ip:=172.16.0.2
