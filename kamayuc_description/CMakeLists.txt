cmake_minimum_required(VERSION 2.8.3)
project(kamayuc_description)

find_package(catkin REQUIRED COMPONENTS
  controller_manager
  gazebo_ros
  joint_state_publisher
  robot_state_publisher
  roscpp
  rospy
  rviz
)

catkin_package()

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)