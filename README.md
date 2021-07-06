# position-and-orientation-publisher-node
A documentation of how I made a ROS publisher node that moves the robot to hardcoded coordinates

These steps pick up right after the navigation simulation repository

I started by making a new catkin package by following the steps at http://wiki.ros.org/ROS/Tutorials/CreatingPackage#ROS.2FTutorials.2Fcatkin.2FCreatingPackage.Creating_a_catkin_Package

Then i followed some of the steps at http://wiki.ros.org/rospy_tutorials/Tutorials/WritingPublisherSubscriber

These steps being creating the python script file, making it an executable and editting the CMakeLists.txt file in the catkin package to link the python script

The idea behind this script is making a node that can command the robot to move to a specific destination and orientation through the "move_base_simple/goal" topic


## charging station coordinates

position
* x : 0.5
* y : -0.2
* z : 0.0
      
orientation
* x : 0.0
* y : 0.0
* z : 0.0
* w : 1.0
      
      
## test run

https://user-images.githubusercontent.com/25144777/124675967-57a11f00-dec6-11eb-9732-6cdc0da9deb1.mp4
