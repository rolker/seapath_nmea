cmake_minimum_required(VERSION 2.8.3)
project(seapath_nmea)

find_package(catkin REQUIRED COMPONENTS
  geometry_msgs
  project11_msgs
  sensor_msgs
  rospy
)

catkin_python_setup()

catkin_package(
#  INCLUDE_DIRS include
#  LIBRARIES posmv
#  CATKIN_DEPENDS geometry_msgs project11_msgs rospy
#  DEPENDS system_lib
)

include_directories(
# include
  ${catkin_INCLUDE_DIRS}
)

