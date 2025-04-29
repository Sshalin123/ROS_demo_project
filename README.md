# Patrolling Robot in Gazebo Simulation Environment

##  Project Overview

This project demonstrates the development of a patrolling robot in a simulated Gazebo environment using ROS2 and Python. The robot is programmed to autonomously navigate a predefined set of waypoints, avoid obstacles, and maintain logs of its patrol activity.

The project was built following the guidelines from [AutomaticAddison's ROS2 Navigation Tutorial](https://automaticaddison.com/how-to-run-an-inspection-with-a-robot-ros-2-navigation/).

---

##  Features Implemented

-  **Patrol a predefined set of waypoints or areas**  
  The robot moves through a sequence of specified coordinates.

-  **Dynamic obstacle avoidance**  
  It dynamically adjusts its path based on detected obstacles using real-time LIDAR data and ROS2 navigation stack.

-  **Return to origin**  
  Upon completing a patrol loop, the robot returns to its starting position.

-  **Patrol logs**  
  The robot maintains a detailed log of:
  - Timestamps of visits
  - Coordinates of visited waypoints

---




