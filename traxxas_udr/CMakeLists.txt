cmake_minimum_required(VERSION 2.8.3)
project(traxxas_udr)

find_package(catkin REQUIRED COMPONENTS
  traxxas_udr_description
  traxxas_udr_gazebo
)
catkin_metapackage()

