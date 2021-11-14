# Generalised Obstacle avoidance in ROS
Generalised obstacle avoider node and launch file for any model in ROS1.
This has been implemented on Ubuntu 18.04 ROS Melodic. 
Can also be used for ROS Kinetic and ROS Neotic

Prerequisites
1. ROS (Full Desktop Version)
2. Robot Model with Laser Scan enabled (Tested on Turtlebot3 Burger and Waffle Pi)

Implementation
1. Clone this repository in ypur catkin_ws using git clone https://github.com/VineetOS/obstacle-avoidance/
2. Load the robot model in Gazebo world with some obstacles
3. Run the obstacle-avoider node using rosrun obstacle-avoider obstacle-avoider
OR roslaunch obstacle-avoider obstacle-avoider.launch

Congrats! Your model has started running!


## Reference
1. http://wiki.ros.org/ROS/Tutorials
2. https://github.com/ROBOTIS-GIT/turtlebot3_simulations.git
3. http://gazebosim.org/tutorials?tut=ros_overview
