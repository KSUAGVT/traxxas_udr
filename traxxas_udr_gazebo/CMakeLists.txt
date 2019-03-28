cmake_minimum_required(VERSION 2.8.3)
project(traxxas_udr_gazebo)
find_package(catkin REQUIRED COMPONENTS
  ackermann_msgs
  controller_manager
  gazebo_ros
  gazebo_ros_control
  rospy
  std_msgs
  tf
  traxxas_udr_description
  xacro
)

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES traxxas_udr_gazebo
#  CATKIN_DEPENDS ackermann_msgs controller_manager gazebo_ros gazebo_ros_control rospy std_msgs tf traxxas_udr_description xacro
#  DEPENDS system_lib
)

###########
## Build ##
###########

## Specify additional locations of header files
## Your package locations should be listed before other locations
include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)

