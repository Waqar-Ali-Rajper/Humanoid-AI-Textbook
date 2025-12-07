# Title: ROS 2 Basics

ROS 2 works as the nervous system of your robot. It passes data between processes and controls hardware.

Core parts

Nodes: independent programs

Topics: publish and subscribe channels

Services: request and response actions

Actions: long-running tasks

Parameters: runtime configuration

You write ROS 2 nodes in Python. You use rclpy.

Example flow

Camera publishes images

AI node receives images

Planner reads outputs

Controller sends joint commands

What you learn

Create ROS 2 packages

Build nodes with Python

Use launch files

Work with URDF robot files

Test communication between components

Skills for later modules depend on these basics