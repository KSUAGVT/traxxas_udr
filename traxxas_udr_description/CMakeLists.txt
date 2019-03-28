cmake_minimum_required(VERSION 2.8.3)
project(traxxas_udr_description)
find_package(catkin REQUIRED COMPONENTS
  joint_state_publisher
  robot_state_publisher
  rviz
  xacro
)
catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES traxxas_udr_description
#  CATKIN_DEPENDS joint_state_publisher robot_state_publisher rviz xacro
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

