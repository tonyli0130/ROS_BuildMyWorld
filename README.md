# ROS_BuildMyWorld_Project
The BuildMyWorld project creates a gazebo world by using moderator tool and building editor, which interacts with plugin written in C++ language to display a welcome message after the gazebo world is launching. Moreover, importing some objects from Gazebo online library can make the gazebo world more diverse.

## Installation
1. Open a new terminal and build the catkin workspace:

 * `$ mkdir -p /home/workspace/catkin_ws/src`
 
 * `$ cd /home/workspace/catkin_ws/src`
 
 * `$ catkin_init_workspace`
 
  
2. Clone the project under  **/home/workspace/catkin_ws/src** directory:

 * `git clone`
 
 
3. Update and updgrade the workspace image to get the lattest features of Gazebo, open a terminal and write the following statements:

 * `$ sudo apt-get update && sudo apt-get upgrade -y`

## Usage

Now run the BuildMyWorld project under **/home/workspace/catkin_ws/src/BuildMyWorld/world** directory:

 * `gazebo MyWorld.world`
